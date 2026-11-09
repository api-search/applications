---
app: apaleo
app_slug: apaleo
app_url: https://apaleo.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4060.10.20
  key: BC-4060.10.20
  layer: domain
  name: Check-In Operations
  providers:
  - LIKE MAGIC
  url: /capabilities/front-office-operations/
  via_parent: Front Office Operations
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - Customer Alliance
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4040.10
  key: guest-profile-identity-management
  layer: domain
  name: Guest Profile & Identity Management
  providers:
  - umnify
  url: /capabilities/guest-profile-identity-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4030
  key: travel-revenue-yield-management
  layer: domain
  name: Travel Revenue & Yield Management
  providers:
  - FLYR Hospitality
  - happyhotel
  url: /capabilities/travel-revenue-yield-management/
  via_parent: null
category:
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://store.apaleo.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.0
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id001
      status: none
    slug: customer-alliance
    status: profiled
    tags: &id002
    - Company
    - Hospitality
    - Review Management
    - Software-as-a-Service
    url: /providers/customer-alliance/
  layer: domain
  name: Customer Alliance
  provider: customer-alliance
  says: lists Customer Alliance as an integration
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
    mcp: &id003
      status: unchecked
    slug: flyr
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: FLYR Hospitality
  provider: flyr
  says: lists FLYR Hospitality as an integration
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
    kin_score: 18.9
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
    attribution: Turbo EA
    id: BC-4060.10.20
    key: BC-4060.10.20
    name: Check-In Operations
    url: /capabilities/front-office-operations/
    via_parent: Front Office Operations
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id007
      status: unknown
    slug: like-magic
    status: profiled
    tags: &id008
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
    id: BC-4040.10
    key: guest-profile-identity-management
    name: Guest Profile & Identity Management
    url: /capabilities/guest-profile-identity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id009
      status: unknown
    slug: umnify
    status: profiled
    tags: &id010
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
permalink: /applications/hospitality-restaurant-ops/apaleo/
providers:
- agent_band: agent-ready
  agent_readiness: 44.0
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id001
  name: Customer Alliance
  slug: customer-alliance
  status: profiled
  tags: *id002
  url: /providers/customer-alliance/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: FLYR Hospitality
  slug: flyr
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.9
  mcp: *id005
  name: happyhotel
  slug: happyhotel
  status: profiled
  tags: *id006
  url: /providers/happyhotel/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id007
  name: LIKE MAGIC
  slug: like-magic
  status: profiled
  tags: *id008
  url: /providers/like-magic/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id009
  name: umnify
  slug: umnify
  status: profiled
  tags: *id010
  url: /providers/umnify/
siblings:
- name: 7shifts
  rows: 12
  url: /applications/hospitality-restaurant-ops/7shifts/
- name: Cloudbeds
  rows: 3
  url: /applications/hospitality-restaurant-ops/cloudbeds/
- name: MarketMan
  rows: 31
  url: /applications/hospitality-restaurant-ops/marketman/
- name: Mews
  rows: 11
  url: /applications/hospitality-restaurant-ops/mews/
- name: QloApps
  rows: 3
  url: /applications/hospitality-restaurant-ops/qloapps/
- name: TastyIgniter
  rows: 11
  url: /applications/hospitality-restaurant-ops/tastyigniter/
sitemap: true
title: 'apaleo: Hotel & Restaurant Operations reference app'
---
