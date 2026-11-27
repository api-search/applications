---
app: Fresha
app_slug: fresha
app_url: https://www.fresha.com/for-business
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.80
  key: AE-210.80
  layer: domain
  name: Booking Channel Distribution
  providers:
  - Facebook bookings
  - Instagram bookings
  - Reserve with Google
  url: /capabilities/booking-channel-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.10
  key: AE-140.30.10
  layer: domain
  name: Buy Now, Pay Later
  providers:
  - Klarna
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 6
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.fresha.com/blog/fresha-xero-quickbooks-accounting-integrations
- route: documentation
  url: https://www.fresha.com/help-center/knowledge-base/billing-and-fees/100694-xero-accounting-overview
- route: documentation
  url: https://www.fresha.com/help-center/knowledge-base/online-presence/101349-get-booked-on-reserve-with-google
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook bookings
  provider: facebook
  says: lists Facebook bookings as an integration
  source: https://www.fresha.com/help-center/knowledge-base/online-presence/101349-get-booked-on-reserve-with-google
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id003
      status: none
    slug: instagram
    status: profiled
    tags: &id004
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram bookings
  provider: instagram
  says: lists Instagram bookings as an integration
  source: https://www.fresha.com/help-center/knowledge-base/online-presence/101349-get-booked-on-reserve-with-google
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id005
      status: none
    slug: klarna
    status: profiled
    tags: &id006
    - Buy Now Pay Later
    - Cards
    - Fintech
    - Payments
    url: /providers/klarna/
  layer: domain
  name: Klarna
  provider: klarna
  says: lists Klarna as an integration
  source: https://www.fresha.com/blog/fresha-xero-quickbooks-accounting-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id007
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id008
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.fresha.com/blog/fresha-xero-quickbooks-accounting-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id010
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Reserve with Google
  provider: google
  says: lists Reserve with Google as an integration
  source: https://www.fresha.com/help-center/knowledge-base/online-presence/101349-get-booked-on-reserve-with-google
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id011
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id012
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.fresha.com/help-center/knowledge-base/billing-and-fees/100694-xero-accounting-overview
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/fresha/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook bookings
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id003
  name: Instagram bookings
  slug: instagram
  status: profiled
  tags: *id004
  url: /providers/instagram/
- agent_band: agent-native
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id005
  name: Klarna
  slug: klarna
  status: profiled
  tags: *id006
  url: /providers/klarna/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id007
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id008
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id009
  name: Reserve with Google
  slug: google
  status: profiled
  tags: *id010
  url: /providers/google/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id011
  name: Xero
  slug: xero
  status: profiled
  tags: *id012
  url: /providers/xero/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Boulevard
  rows: 16
  url: /applications/salon-spa-management/boulevard/
- name: Mindbody
  rows: 22
  url: /applications/salon-spa-management/mindbody/
- name: Open Salon
  rows: 2
  url: /applications/salon-spa-management/open-salon/
- name: Salon Booking System
  rows: 44
  url: /applications/salon-spa-management/salon-booking-system/
- name: Square Appointments
  rows: 32
  url: /applications/salon-spa-management/square-appointments/
- name: Vagaro
  rows: 2
  url: /applications/salon-spa-management/vagaro/
sitemap: true
title: 'Fresha: Salon & Spa Management reference app'
---
