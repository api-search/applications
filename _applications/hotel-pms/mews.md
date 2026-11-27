---
app: Mews
app_slug: mews
app_url: https://www.mews.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4010.50
  key: channel-manager-operations
  layer: domain
  name: Channel Manager Operations
  providers:
  - SiteMinder
  url: /capabilities/channel-manager-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30
  key: consumer-payment-options
  layer: domain
  name: Consumer Payment Options
  providers:
  - Apple Pay
  - Google Pay
  url: /capabilities/consumer-payment-options/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - Tripadvisor
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.30.10
  key: AE-160.30.10
  layer: domain
  name: Document Verification
  providers:
  - Chekin
  url: /capabilities/identity-verification/
  via_parent: Identity Verification
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - 24SevenOffice
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4040
  key: guest-traveller-management
  layer: domain
  name: Guest & Traveller Management
  providers:
  - Alliants
  url: /capabilities/guest-traveller-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4020
  key: reservation-booking-management
  layer: domain
  name: Reservation & Booking Management
  providers:
  - Spalopia
  url: /capabilities/reservation-booking-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4010
  key: travel-distribution-channel-management
  layer: domain
  name: Travel Distribution & Channel Management
  providers:
  - Amadeus iHotelier
  - Booking.com
  - Expedia
  url: /capabilities/travel-distribution-channel-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4030
  key: travel-revenue-yield-management
  layer: domain
  name: Travel Revenue & Yield Management
  providers:
  - BEONX
  - profitize
  url: /capabilities/travel-revenue-yield-management/
  via_parent: null
category:
  id: hotel-pms
  name: Hotel Property Management
  url: /applications/hotel-pms/
counts:
  declared: 13
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.mews.com/en/marketplace
- route: integrations page
  url: https://www.mews.com/en/products/payments
integrations:
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id001
      status: unchecked
    slug: 24sevenoffice
    status: profiled
    tags: &id002
    - Accounting
    - Business Management
    - Norway
    - Payroll
    url: /providers/24sevenoffice/
  layer: domain
  name: 24SevenOffice
  provider: 24sevenoffice
  says: lists 24SevenOffice as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4040
    key: guest-traveller-management
    name: Guest & Traveller Management
    url: /capabilities/guest-traveller-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id003
      status: none
    slug: alliants
    status: profiled
    tags: &id004
    - Company
    - DigitalKeys
    - Hospitality
    - Software-as-a-Service
    url: /providers/alliants/
  layer: domain
  name: Alliants
  provider: alliants
  says: lists Alliants as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id005
      status: none
    slug: amadeus
    status: profiled
    tags: &id006
    - Flights
    - Reservations
    - Travel
    - Travel Technology
    url: /providers/amadeus/
  layer: domain
  name: Amadeus iHotelier
  provider: amadeus
  says: lists Amadeus iHotelier as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30
    key: consumer-payment-options
    name: Consumer Payment Options
    url: /capabilities/consumer-payment-options/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id007
      status: none
    slug: apple-pay
    status: profiled
    tags: &id008
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
  layer: domain
  name: Apple Pay
  provider: apple-pay
  says: lists Apple Pay as an integration
  source: https://www.mews.com/en/products/payments
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 19.3
    mcp: &id009
      source: https://beonx.com
      status: documented
    slug: beonx
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Company
    - Hospitality
    - Revenue Management
    url: /providers/beonx/
  layer: domain
  name: BEONX
  provider: beonx
  says: lists BEONX as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id011
      status: none
    slug: booking-com
    status: profiled
    tags: &id012
    - Accommodation
    - Booking
    - Hospitality
    - Travel
    url: /providers/booking-com/
  layer: domain
  name: Booking.com
  provider: booking-com
  says: lists Booking.com as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.10
    key: AE-160.30.10
    name: Document Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 22.0
    mcp: &id013
      status: unknown
    slug: chekin
    status: profiled
    tags: &id014
    - Check-in
    - Compliance
    - Hospitality
    - SDK
    url: /providers/chekin/
  layer: domain
  name: Chekin
  provider: chekin
  says: lists Chekin as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id015
      source: https://github.com/ExpediaGroup/expedia-travel-recommendations-mcp
      status: verified
    slug: expedia-group
    status: profiled
    tags: &id016
    - Flights
    - Hotels
    - Lodging
    - Travel
    url: /providers/expedia-group/
  layer: domain
  name: Expedia
  provider: expedia-group
  says: lists Expedia as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30
    key: consumer-payment-options
    name: Consumer Payment Options
    url: /capabilities/consumer-payment-options/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id017
      status: none
    slug: google-pay
    status: profiled
    tags: &id018
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: domain
  name: Google Pay
  provider: google-pay
  says: lists Google Pay as an integration
  source: https://www.mews.com/en/products/payments
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id019
      status: unchecked
    slug: profitize
    status: profiled
    tags: &id020
    - Company
    url: /providers/profitize/
  layer: domain
  name: profitize
  provider: profitize
  says: lists profitize as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.5
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id021
      status: none
    slug: siteminder
    status: profiled
    tags: &id022
    - Booking Engine
    - Channel Manager
    - Hospitality
    - Hotel Distribution
    url: /providers/siteminder/
  layer: domain
  name: SiteMinder
  provider: siteminder
  says: lists SiteMinder as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4020
    key: reservation-booking-management
    name: Reservation & Booking Management
    url: /capabilities/reservation-booking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id023
      status: unknown
    slug: spalopia
    status: profiled
    tags: &id024
    - Booking
    - Company
    - Spa
    - Wellness
    url: /providers/spalopia/
  layer: domain
  name: Spalopia
  provider: spalopia
  says: lists Spalopia as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id025
      status: none
    slug: tripadvisor
    status: profiled
    tags: &id026
    - Attractions
    - Hospitality
    - Hotels
    - Restaurant
    url: /providers/tripadvisor/
  layer: domain
  name: Tripadvisor
  provider: tripadvisor
  says: lists Tripadvisor as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hotel-pms/mews/
providers:
- agent_band: agent-aware
  agent_readiness: 19.3
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id001
  name: 24SevenOffice
  slug: 24sevenoffice
  status: profiled
  tags: *id002
  url: /providers/24sevenoffice/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id003
  name: Alliants
  slug: alliants
  status: profiled
  tags: *id004
  url: /providers/alliants/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id005
  name: Amadeus iHotelier
  slug: amadeus
  status: profiled
  tags: *id006
  url: /providers/amadeus/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id007
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id008
  url: /providers/apple-pay/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 19.3
  mcp: *id009
  name: BEONX
  slug: beonx
  status: profiled
  tags: *id010
  url: /providers/beonx/
- agent_band: agent-ready
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id011
  name: Booking.com
  slug: booking-com
  status: profiled
  tags: *id012
  url: /providers/booking-com/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 22.0
  mcp: *id013
  name: Chekin
  slug: chekin
  status: profiled
  tags: *id014
  url: /providers/chekin/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id015
  name: Expedia
  slug: expedia-group
  status: profiled
  tags: *id016
  url: /providers/expedia-group/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id017
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id018
  url: /providers/google-pay/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id019
  name: profitize
  slug: profitize
  status: profiled
  tags: *id020
  url: /providers/profitize/
- agent_band: agent-aware
  agent_readiness: 5.5
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id021
  name: SiteMinder
  slug: siteminder
  status: profiled
  tags: *id022
  url: /providers/siteminder/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id023
  name: Spalopia
  slug: spalopia
  status: profiled
  tags: *id024
  url: /providers/spalopia/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id025
  name: Tripadvisor
  slug: tripadvisor
  status: profiled
  tags: *id026
  url: /providers/tripadvisor/
siblings:
- name: apaleo
  rows: 8
  url: /applications/hotel-pms/apaleo/
- name: Beds24
  rows: 12
  url: /applications/hotel-pms/beds24/
- name: Cloudbeds
  rows: 16
  url: /applications/hotel-pms/cloudbeds/
- name: Hotelogix
  rows: 32
  url: /applications/hotel-pms/hotelogix/
- name: QloApps
  rows: 3
  url: /applications/hotel-pms/qloapps/
sitemap: true
title: 'Mews: Hotel Property Management reference app'
---
