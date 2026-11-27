---
app: apaleo
app_slug: apaleo
app_url: https://apaleo.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - umnify
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4010.10
  key: direct-channel-distribution-management
  layer: domain
  name: Direct Channel Distribution Management
  providers:
  - GauVendi
  url: /capabilities/direct-channel-distribution-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4040
  key: guest-traveller-management
  layer: domain
  name: Guest & Traveller Management
  providers:
  - LIKE MAGIC
  url: /capabilities/guest-traveller-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4060.10.30
  key: BC-4060.10.30
  layer: domain
  name: Room Assignment & Upgrade
  providers:
  - Sponteous
  url: /capabilities/front-office-operations/
  via_parent: Front Office Operations
- attribution: Turbo EA
  id: BC-4030
  key: travel-revenue-yield-management
  layer: domain
  name: Travel Revenue & Yield Management
  providers:
  - FLYR Hospitality
  - happyhotel
  - N2Pricing
  url: /capabilities/travel-revenue-yield-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.70.20
  key: AE-100.70.20
  layer: domain
  name: Voice Agents
  providers:
  - inCallio
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
category:
  id: hotel-pms
  name: Hotel Property Management
  url: /applications/hotel-pms/
counts:
  declared: 8
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://apaleo.dev/
- route: integrations page
  url: https://store.apaleo.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: flyr
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: FLYR Hospitality
  provider: flyr
  says: lists FLYR Hospitality as an integration
  source: https://store.apaleo.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.10
    key: direct-channel-distribution-management
    name: Direct Channel Distribution Management
    url: /capabilities/direct-channel-distribution-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.9
    band: minimal
    in_catalog: true
    kin_score: 4.6
    mcp: &id003
      status: unchecked
    slug: gauvendi
    status: profiled
    tags: &id004
    - Booking
    - Distribution
    - Revenue Optimization
    url: /providers/gauvendi/
  layer: domain
  name: GauVendi
  provider: gauvendi
  says: lists GauVendi as an integration
  source: https://store.apaleo.com/
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id005
      status: none
    slug: happyhotel
    status: profiled
    tags: &id006
    - Hospitality
    - Hotels
    - Revenue Management
    - Software-as-a-Service
    url: /providers/happyhotel/
  layer: domain
  name: happyhotel
  provider: happyhotel
  says: lists happyhotel as an integration
  source: https://store.apaleo.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.20
    key: AE-100.70.20
    name: Voice Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: incallio
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: inCallio
  provider: incallio
  says: lists inCallio as an integration
  source: https://store.apaleo.com/
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
    agent_band: agent-aware
    agent_readiness: 21.4
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id009
      status: unknown
    slug: like-magic
    status: profiled
    tags: &id010
    - Company
    - Guest Experience
    - Hospitality
    - Technology
    url: /providers/like-magic/
  layer: domain
  name: LIKE MAGIC
  provider: like-magic
  says: lists LIKE MAGIC as an integration
  source: https://store.apaleo.com/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: n2pricing
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: N2Pricing
  provider: n2pricing
  says: lists N2Pricing as an integration
  source: https://store.apaleo.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4060.10.30
    key: BC-4060.10.30
    name: Room Assignment & Upgrade
    url: /capabilities/front-office-operations/
    via_parent: Front Office Operations
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id013
      status: unchecked
    slug: sponteous
    status: profiled
    tags: &id014
    - Company
    - Hospitality
    - Software-as-a-Service
    - Upselling
    url: /providers/sponteous/
  layer: domain
  name: Sponteous
  provider: sponteous
  says: lists Sponteous as an integration
  source: https://store.apaleo.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id015
      status: unknown
    slug: umnify
    status: profiled
    tags: &id016
    - German Market
    - Hospitality
    - Hotel Management
    - Software
    url: /providers/umnify/
  layer: domain
  name: umnify
  provider: umnify
  says: lists umnify as an integration
  source: https://store.apaleo.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hotel-pms/apaleo/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: FLYR Hospitality
  slug: flyr
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: human-only
  agent_readiness: 0.9
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id003
  name: GauVendi
  slug: gauvendi
  status: profiled
  tags: *id004
  url: /providers/gauvendi/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id005
  name: happyhotel
  slug: happyhotel
  status: profiled
  tags: *id006
  url: /providers/happyhotel/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: inCallio
  slug: incallio
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-aware
  agent_readiness: 21.4
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id009
  name: LIKE MAGIC
  slug: like-magic
  status: profiled
  tags: *id010
  url: /providers/like-magic/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: N2Pricing
  slug: n2pricing
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id013
  name: Sponteous
  slug: sponteous
  status: profiled
  tags: *id014
  url: /providers/sponteous/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id015
  name: umnify
  slug: umnify
  status: profiled
  tags: *id016
  url: /providers/umnify/
siblings:
- name: Beds24
  rows: 12
  url: /applications/hotel-pms/beds24/
- name: Cloudbeds
  rows: 16
  url: /applications/hotel-pms/cloudbeds/
- name: Hotelogix
  rows: 32
  url: /applications/hotel-pms/hotelogix/
- name: Mews
  rows: 13
  url: /applications/hotel-pms/mews/
- name: QloApps
  rows: 3
  url: /applications/hotel-pms/qloapps/
sitemap: true
title: 'apaleo: Hotel Property Management reference app'
---
