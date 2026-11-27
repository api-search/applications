---
app: Boulevard
app_slug: boulevard
app_url: https://www.joinblvd.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.90
  key: AE-130.90
  layer: domain
  name: Beauty & Personal Care
  providers:
  - Green Circle Salons
  url: /capabilities/beauty-personal-care/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.80
  key: AE-210.80
  layer: domain
  name: Booking Channel Distribution
  providers:
  - Facebook (Book Now)
  - Instagram (Book Now)
  - Reserve with Google
  url: /capabilities/booking-channel-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.10
  key: AE-140.30.10
  layer: domain
  name: Buy Now, Pay Later
  providers:
  - Affirm
  - Klarna
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-530
  key: inventory-management
  layer: domain
  name: Inventory Management
  providers:
  - Vish
  url: /capabilities/inventory-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4940
  key: property-management-operations
  layer: domain
  name: Property Management Operations
  providers:
  - OPERA PMS
  url: /capabilities/property-management-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: reviews-social-proof
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Widewail
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Apple Calendar
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: agent
  name: Virtual Receptionists & Answering Services
  providers:
  - REACH.ai
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 16
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.joinblvd.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id001
      status: none
    slug: affirm
    status: profiled
    tags: &id002
    - Buy Now Pay Later
    - Fintech
    - Lending
    - Payments
    url: /providers/affirm/
  layer: domain
  name: Affirm
  provider: affirm
  says: lists Affirm as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple Calendar
  provider: apple
  says: lists Apple Calendar as an integration
  source: https://www.joinblvd.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook (Book Now)
  provider: facebook
  says: lists Facebook (Book Now) as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id008
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.90
    key: AE-130.90
    name: Beauty & Personal Care
    url: /capabilities/beauty-personal-care/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id009
      status: unchecked
    slug: green-circle-salons
    status: profiled
    tags: &id010
    - Beauty
    - Environment
    - Salon
    - Sustainability
    url: /providers/green-circle-salons/
  layer: domain
  name: Green Circle Salons
  provider: green-circle-salons
  says: lists Green Circle Salons as an integration
  source: https://www.joinblvd.com/integrations
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
    mcp: &id011
      status: none
    slug: instagram
    status: profiled
    tags: &id012
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram (Book Now)
  provider: instagram
  says: lists Instagram (Book Now) as an integration
  source: https://www.joinblvd.com/integrations
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
    mcp: &id013
      status: none
    slug: klarna
    status: profiled
    tags: &id014
    - Buy Now Pay Later
    - Cards
    - Fintech
    - Payments
    url: /providers/klarna/
  layer: domain
  name: Klarna
  provider: klarna
  says: lists Klarna as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id015
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id016
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4940
    key: property-management-operations
    name: Property Management Operations
    url: /capabilities/property-management-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id017
      status: none
    slug: oracle-hospitality
    status: profiled
    tags: &id018
    - Hospitality
    - Hotels
    - Travel
    - United States
    url: /providers/oracle-hospitality/
  layer: domain
  name: OPERA PMS
  provider: oracle-hospitality
  says: lists OPERA PMS as an integration
  source: https://www.joinblvd.com/integrations
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
    mcp: &id019
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id020
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: reach-ai
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: agent
  name: REACH.ai
  provider: reach-ai
  says: lists REACH.ai as an integration
  source: https://www.joinblvd.com/integrations
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
    mcp: &id023
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id024
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Reserve with Google
  provider: google
  says: lists Reserve with Google as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id025
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id026
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id027
      status: unchecked
    slug: vish
    status: queued for profiling
    tags: &id028 []
    url: null
  layer: domain
  name: Vish
  provider: vish
  says: lists Vish as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id029
      status: unchecked
    slug: widewail
    status: profiled
    tags: &id030
    - Automotive
    - Company
    - Customer Intelligence
    - Software-as-a-Service
    url: /providers/widewail/
  layer: domain
  name: Widewail
  provider: widewail
  says: lists Widewail as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id031
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id032
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.joinblvd.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/boulevard/
providers:
- agent_band: agent-ready
  agent_readiness: 34.5
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id001
  name: Affirm
  slug: affirm
  status: profiled
  tags: *id002
  url: /providers/affirm/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple Calendar
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook (Book Now)
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id007
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id008
  url: /providers/google-calendar/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id009
  name: Green Circle Salons
  slug: green-circle-salons
  status: profiled
  tags: *id010
  url: /providers/green-circle-salons/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id011
  name: Instagram (Book Now)
  slug: instagram
  status: profiled
  tags: *id012
  url: /providers/instagram/
- agent_band: agent-native
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id013
  name: Klarna
  slug: klarna
  status: profiled
  tags: *id014
  url: /providers/klarna/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id015
  name: Okta
  slug: okta
  status: profiled
  tags: *id016
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id017
  name: OPERA PMS
  slug: oracle-hospitality
  status: profiled
  tags: *id018
  url: /providers/oracle-hospitality/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id019
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id020
  url: /providers/quickbooks/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: REACH.ai
  slug: reach-ai
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id023
  name: Reserve with Google
  slug: google
  status: profiled
  tags: *id024
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id025
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id026
  url: /providers/shopify/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id027
  name: Vish
  slug: vish
  status: queued for profiling
  tags: *id028
  url: null
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id029
  name: Widewail
  slug: widewail
  status: profiled
  tags: *id030
  url: /providers/widewail/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id031
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id032
  url: /providers/zapier/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Fresha
  rows: 6
  url: /applications/salon-spa-management/fresha/
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
title: 'Boulevard: Salon & Spa Management reference app'
---
