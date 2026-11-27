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
  - Booking.com
  - Expedia
  - SiteMinder
  url: /capabilities/channel-manager-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-4060.10.20
  key: BC-4060.10.20
  layer: domain
  name: Check-In Operations
  providers:
  - Chekin
  url: /capabilities/front-office-operations/
  via_parent: Front Office Operations
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - Tripadvisor
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Abacus (Swiss ERP)
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4040.10
  key: guest-profile-identity-management
  layer: domain
  name: Guest Profile & Identity Management
  providers:
  - Alliants
  url: /capabilities/guest-profile-identity-management/
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
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.mews.com/en/marketplace
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id001
      status: none
    slug: abacus-ch
    status: profiled
    tags: &id002
    - Company
    - ERP
    - Finance
    - Human Resources
    url: /providers/abacus-ch/
  layer: domain
  name: Abacus (Swiss ERP)
  provider: abacus-ch
  says: lists Abacus (Swiss ERP) as an integration
  source: https://www.mews.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4040.10
    key: guest-profile-identity-management
    name: Guest Profile & Identity Management
    url: /capabilities/guest-profile-identity-management/
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
    mcp: &id007
      source: https://beonx.com
      status: documented
    slug: beonx
    status: profiled
    tags: &id008
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
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id009
      status: none
    slug: booking-com
    status: profiled
    tags: &id010
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
    attribution: Turbo EA
    id: BC-4060.10.20
    key: BC-4060.10.20
    name: Check-In Operations
    url: /capabilities/front-office-operations/
    via_parent: Front Office Operations
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 22.0
    mcp: &id011
      status: unknown
    slug: chekin
    status: profiled
    tags: &id012
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
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id013
      source: https://github.com/ExpediaGroup/expedia-travel-recommendations-mcp
      status: verified
    slug: expedia-group
    status: profiled
    tags: &id014
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
    mcp: &id015
      status: unchecked
    slug: profitize
    status: profiled
    tags: &id016
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
    mcp: &id017
      status: none
    slug: siteminder
    status: profiled
    tags: &id018
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
    mcp: &id019
      status: unknown
    slug: spalopia
    status: profiled
    tags: &id020
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
    mcp: &id021
      status: none
    slug: tripadvisor
    status: profiled
    tags: &id022
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
permalink: /applications/hospitality-restaurant-ops/mews/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id001
  name: Abacus (Swiss ERP)
  slug: abacus-ch
  status: profiled
  tags: *id002
  url: /providers/abacus-ch/
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
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 19.3
  mcp: *id007
  name: BEONX
  slug: beonx
  status: profiled
  tags: *id008
  url: /providers/beonx/
- agent_band: agent-ready
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id009
  name: Booking.com
  slug: booking-com
  status: profiled
  tags: *id010
  url: /providers/booking-com/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 22.0
  mcp: *id011
  name: Chekin
  slug: chekin
  status: profiled
  tags: *id012
  url: /providers/chekin/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id013
  name: Expedia
  slug: expedia-group
  status: profiled
  tags: *id014
  url: /providers/expedia-group/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id015
  name: profitize
  slug: profitize
  status: profiled
  tags: *id016
  url: /providers/profitize/
- agent_band: agent-aware
  agent_readiness: 5.5
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id017
  name: SiteMinder
  slug: siteminder
  status: profiled
  tags: *id018
  url: /providers/siteminder/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id019
  name: Spalopia
  slug: spalopia
  status: profiled
  tags: *id020
  url: /providers/spalopia/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id021
  name: Tripadvisor
  slug: tripadvisor
  status: profiled
  tags: *id022
  url: /providers/tripadvisor/
siblings:
- name: 7shifts
  rows: 12
  url: /applications/hospitality-restaurant-ops/7shifts/
- name: apaleo
  rows: 5
  url: /applications/hospitality-restaurant-ops/apaleo/
- name: Cloudbeds
  rows: 3
  url: /applications/hospitality-restaurant-ops/cloudbeds/
- name: MarketMan
  rows: 31
  url: /applications/hospitality-restaurant-ops/marketman/
- name: QloApps
  rows: 3
  url: /applications/hospitality-restaurant-ops/qloapps/
- name: TastyIgniter
  rows: 11
  url: /applications/hospitality-restaurant-ops/tastyigniter/
sitemap: true
title: 'Mews: Hotel & Restaurant Operations reference app'
---
