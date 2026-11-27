---
app: Guesty
app_slug: guesty
app_url: https://www.guesty.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4010.50
  key: channel-manager-operations
  layer: domain
  name: Channel Manager Operations
  providers:
  - Airbnb
  - Booking.com
  - Vrbo
  url: /capabilities/channel-manager-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Ximplifi
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4060.20
  key: housekeeping-operations
  layer: domain
  name: Housekeeping Operations
  providers:
  - Breezeway
  url: /capabilities/housekeeping-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-440
  key: pricing-management
  layer: domain
  name: Pricing Management
  providers:
  - Beyond
  - PriceLabs
  - Wheelhouse
  url: /capabilities/pricing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.60
  key: AE-230.60
  layer: domain
  name: Property Data
  providers:
  - AirDNA
  - Key Data
  - Lighthouse
  url: /capabilities/property-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-4950.40
  key: tenant-application-screening
  layer: domain
  name: Tenant Application & Screening
  providers:
  - Autohost
  url: /capabilities/tenant-application-screening/
  via_parent: null
category:
  id: property-management
  name: Property & Rental Management
  url: /applications/property-management/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.guesty.com/marketplace/
integrations:
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
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id001
      status: none
    slug: airbnb
    status: profiled
    tags: &id002
    - Airbnb
    - Hospitality
    - Reservations
    - Travel
    url: /providers/airbnb/
  layer: domain
  name: Airbnb
  provider: airbnb
  says: lists Airbnb as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.60
    key: AE-230.60
    name: Property Data
    url: /capabilities/property-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id003
      status: none
    slug: airdna
    status: profiled
    tags: &id004
    - Market Data
    - Real Estate
    - Short-Term Rental
    - Vacation Rentals
    url: /providers/airdna/
  layer: domain
  name: AirDNA
  provider: airdna
  says: lists AirDNA as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4950.40
    key: tenant-application-screening
    name: Tenant Application & Screening
    url: /capabilities/tenant-application-screening/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 42.0
    mcp: &id005
      source: https://docs.autohost.ai/docs/remote-mcp-server
      status: verified
    slug: autohost
    status: profiled
    tags: &id006
    - Background Checks
    - Company
    - Fraud Prevention
    - Identity Verification
    url: /providers/autohost/
  layer: domain
  name: Autohost
  provider: autohost
  says: lists Autohost as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440
    key: pricing-management
    name: Pricing Management
    url: /capabilities/pricing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.2
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id007
      status: none
    slug: beyond-pricing
    status: profiled
    tags: &id008
    - Company
    - Revenue Management
    - Short-Term Rental
    - Vacation Rentals
    url: /providers/beyond-pricing/
  layer: domain
  name: Beyond
  provider: beyond-pricing
  says: lists Beyond as an integration
  source: https://www.guesty.com/marketplace/
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
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4060.20
    key: housekeeping-operations
    name: Housekeeping Operations
    url: /capabilities/housekeeping-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.4
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id011
      status: unknown
    slug: breezeway
    status: profiled
    tags: &id012
    - Guest Experience
    - Operations Automation
    - Property Management
    - Software-as-a-Service
    url: /providers/breezeway/
  layer: domain
  name: Breezeway
  provider: breezeway
  says: lists Breezeway as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.60
    key: AE-230.60
    name: Property Data
    url: /capabilities/property-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id013
      status: unknown
    slug: key-data
    status: profiled
    tags: &id014
    - Analytics
    - Property Management
    - Real-Time Data
    - Short-Term Rental
    url: /providers/key-data/
  layer: domain
  name: Key Data
  provider: key-data
  says: lists Key Data as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.60
    key: AE-230.60
    name: Property Data
    url: /capabilities/property-data/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: mylighthouse
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Lighthouse
  provider: mylighthouse
  says: lists Lighthouse as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440
    key: pricing-management
    name: Pricing Management
    url: /capabilities/pricing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id017
      status: unchecked
    slug: pricelabs
    status: queued for profiling
    tags: &id018 []
    url: null
  layer: domain
  name: PriceLabs
  provider: pricelabs
  says: lists PriceLabs as an integration
  source: https://www.guesty.com/marketplace/
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
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id019
      status: unchecked
    slug: vrbo
    status: profiled
    tags: &id020
    - Company
    url: /providers/vrbo/
  layer: domain
  name: Vrbo
  provider: vrbo
  says: lists Vrbo as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440
    key: pricing-management
    name: Pricing Management
    url: /capabilities/pricing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: wheelhouse
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Wheelhouse
  provider: wheelhouse
  says: lists Wheelhouse as an integration
  source: https://www.guesty.com/marketplace/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id023
      status: unknown
    slug: ximplifi
    status: profiled
    tags: &id024
    - Accounting
    - Property Management
    - Software-as-a-Service
    - Vacation Rentals
    url: /providers/ximplifi/
  layer: domain
  name: Ximplifi
  provider: ximplifi
  says: lists Ximplifi as an integration
  source: https://www.guesty.com/marketplace/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/property-management/guesty/
providers:
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id001
  name: Airbnb
  slug: airbnb
  status: profiled
  tags: *id002
  url: /providers/airbnb/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id003
  name: AirDNA
  slug: airdna
  status: profiled
  tags: *id004
  url: /providers/airdna/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 42.0
  mcp: *id005
  name: Autohost
  slug: autohost
  status: profiled
  tags: *id006
  url: /providers/autohost/
- agent_band: agent-ready
  agent_readiness: 46.2
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id007
  name: Beyond
  slug: beyond-pricing
  status: profiled
  tags: *id008
  url: /providers/beyond-pricing/
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
  agent_readiness: 19.4
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id011
  name: Breezeway
  slug: breezeway
  status: profiled
  tags: *id012
  url: /providers/breezeway/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id013
  name: Key Data
  slug: key-data
  status: profiled
  tags: *id014
  url: /providers/key-data/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Lighthouse
  slug: mylighthouse
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id017
  name: PriceLabs
  slug: pricelabs
  status: queued for profiling
  tags: *id018
  url: null
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id019
  name: Vrbo
  slug: vrbo
  status: profiled
  tags: *id020
  url: /providers/vrbo/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Wheelhouse
  slug: wheelhouse
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id023
  name: Ximplifi
  slug: ximplifi
  status: profiled
  tags: *id024
  url: /providers/ximplifi/
siblings:
- name: AppFolio
  rows: 6
  url: /applications/property-management/appfolio/
- name: Buildium
  rows: 15
  url: /applications/property-management/buildium/
- name: DoorLoop
  rows: 15
  url: /applications/property-management/doorloop/
- name: Hostaway
  rows: 17
  url: /applications/property-management/hostaway/
- name: Open Condo
  rows: 18
  url: /applications/property-management/open-condo/
sitemap: true
title: 'Guesty: Property & Rental Management reference app'
---
