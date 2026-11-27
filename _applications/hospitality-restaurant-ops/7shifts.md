---
app: 7shifts
app_slug: 7shifts
app_url: https://www.7shifts.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Aloha (NCR Voyix)
  - Bypass
  - CAKE POS
  - Clover
  - GoTab
  - Lightspeed
  - Oracle MICROS 3700
  - Qu POS
  - Revel Systems
  - Square
  - Toast
  - TouchBistro
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
category:
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.7shifts.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id001
      status: none
    slug: ncr
    status: profiled
    tags: &id002
    - Banking
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/ncr/
  layer: domain
  name: Aloha (NCR Voyix)
  provider: ncr
  says: lists Aloha (NCR Voyix) as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
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
    slug: bypass
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Bypass
  provider: bypass
  says: lists Bypass as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id005
      status: unknown
    slug: cake-pos
    status: profiled
    tags: &id006
    - Company
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/cake-pos/
  layer: domain
  name: CAKE POS
  provider: cake-pos
  says: lists CAKE POS as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 41.3
    mcp: &id007
      status: none
    slug: clover
    status: profiled
    tags: &id008
    - Payments
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/clover/
  layer: domain
  name: Clover
  provider: clover
  says: lists Clover as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: gotab
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: GoTab
  provider: gotab
  says: lists GoTab as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id011
      status: none
    slug: lightspeed
    status: profiled
    tags: &id012
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id013
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id014
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle MICROS 3700
  provider: oracle
  says: lists Oracle MICROS 3700 as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
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
    slug: qu
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Qu POS
  provider: qu
  says: lists Qu POS as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id017
      status: none
    slug: revel-systems
    status: profiled
    tags: &id018
    - Point-of-Sale
    - Restaurant
    - Retail
    - iPad
    url: /providers/revel-systems/
  layer: domain
  name: Revel Systems
  provider: revel-systems
  says: lists Revel Systems as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id019
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id020
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id021
      status: none
    slug: toast
    status: profiled
    tags: &id022
    - Food Service
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/toast/
  layer: domain
  name: Toast
  provider: toast
  says: lists Toast as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id023
      status: none
    slug: touchbistro
    status: profiled
    tags: &id024
    - Hospitality
    - Payments
    - Point-of-Sale
    - Restaurant
    url: /providers/touchbistro/
  layer: domain
  name: TouchBistro
  provider: touchbistro
  says: lists TouchBistro as an integration
  source: https://www.7shifts.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hospitality-restaurant-ops/7shifts/
providers:
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id001
  name: Aloha (NCR Voyix)
  slug: ncr
  status: profiled
  tags: *id002
  url: /providers/ncr/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Bypass
  slug: bypass
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id005
  name: CAKE POS
  slug: cake-pos
  status: profiled
  tags: *id006
  url: /providers/cake-pos/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 41.3
  mcp: *id007
  name: Clover
  slug: clover
  status: profiled
  tags: *id008
  url: /providers/clover/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: GoTab
  slug: gotab
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id011
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id012
  url: /providers/lightspeed/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id013
  name: Oracle MICROS 3700
  slug: oracle
  status: profiled
  tags: *id014
  url: /providers/oracle/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Qu POS
  slug: qu
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-aware
  agent_readiness: 28.2
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id017
  name: Revel Systems
  slug: revel-systems
  status: profiled
  tags: *id018
  url: /providers/revel-systems/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id019
  name: Square
  slug: square
  status: profiled
  tags: *id020
  url: /providers/square/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id021
  name: Toast
  slug: toast
  status: profiled
  tags: *id022
  url: /providers/toast/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id023
  name: TouchBistro
  slug: touchbistro
  status: profiled
  tags: *id024
  url: /providers/touchbistro/
siblings:
- name: apaleo
  rows: 5
  url: /applications/hospitality-restaurant-ops/apaleo/
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
title: '7shifts: Hotel & Restaurant Operations reference app'
---
