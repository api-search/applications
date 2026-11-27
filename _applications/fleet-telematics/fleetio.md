---
app: Fleetio
app_slug: fleetio
app_url: https://www.fleetio.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-940
  key: AE-940
  layer: domain
  name: Fleet Fuel Cards & Fuel Transaction Data
  providers:
  - AtoB
  - CarIQ
  - Coast
  - Comdata
  - Corpay / FLEETCOR
  - EFS
  - Fill-Rite FMS
  - FuelCloud
  - FuelMaster
  - Intevacon
  - WEX
  url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
  via_parent: null
category:
  id: fleet-telematics
  name: Fleet Management & Telematics
  url: /applications/fleet-telematics/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://help.fleetio.com/en_US/integrations/fuel-integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.2
    mcp: &id001
      status: none
    slug: atob
    status: profiled
    tags: &id002
    - Company
    - Fleet Management
    - Fuel Cards
    - Payments
    url: /providers/atob/
  layer: domain
  name: AtoB
  provider: atob
  says: lists AtoB as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
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
    slug: cariq
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: CarIQ
  provider: cariq
  says: lists CarIQ as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.5
    mcp: &id005
      status: unknown
    slug: coast
    status: profiled
    tags: &id006
    - Company
    - Fintech
    - Fleet Management
    - Payments
    url: /providers/coast/
  layer: domain
  name: Coast
  provider: coast
  says: lists Coast as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id007
      status: unchecked
    slug: comdata
    status: profiled
    tags: &id008
    - Company
    - Fleet Management
    - Fuel Services
    - Payments
    url: /providers/comdata/
  layer: domain
  name: Comdata
  provider: comdata
  says: lists Comdata as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.1
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id009
      status: unknown
    slug: corpay
    status: profiled
    tags: &id010
    - Accounts Payable
    - Corporate Payments
    - Cross-Border Payments
    - Payments
    url: /providers/corpay/
  layer: domain
  name: Corpay / FLEETCOR
  provider: corpay
  says: lists Corpay / FLEETCOR as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
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
    slug: efs
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: EFS
  provider: efs
  says: lists EFS as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.7
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id013
      status: unchecked
    slug: fill-rite
    status: profiled
    tags: &id014
    - Chemical Transfer
    - Flow Meters
    - Fuel Transfer
    - Oil Transfer
    url: /providers/fill-rite/
  layer: domain
  name: Fill-Rite FMS
  provider: fill-rite
  says: lists Fill-Rite FMS as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id015
      status: unchecked
    slug: fuelcloud
    status: profiled
    tags: &id016
    - Cloud Services
    - Company
    - Fleet Operations
    - Fuel Management
    url: /providers/fuelcloud/
  layer: domain
  name: FuelCloud
  provider: fuelcloud
  says: lists FuelCloud as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id017
      status: unchecked
    slug: fuelmaster
    status: profiled
    tags: &id018
    - Automotive
    - Company
    - Environment
    - FuelSaving
    url: /providers/fuelmaster/
  layer: domain
  name: FuelMaster
  provider: fuelmaster
  says: lists FuelMaster as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id019
      status: unchecked
    slug: intevacon
    status: profiled
    tags: &id020
    - Company
    - Fleet Card
    - Payments
    - Petroleum
    url: /providers/intevacon/
  layer: domain
  name: Intevacon
  provider: intevacon
  says: lists Intevacon as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id021
      status: none
    slug: wex
    status: profiled
    tags: &id022 []
    url: /providers/wex/
  layer: domain
  name: WEX
  provider: wex
  says: lists WEX as an integration
  source: https://help.fleetio.com/en_US/integrations/fuel-integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fleet-telematics/fleetio/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id001
  name: AtoB
  slug: atob
  status: profiled
  tags: *id002
  url: /providers/atob/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: CarIQ
  slug: cariq
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.5
  mcp: *id005
  name: Coast
  slug: coast
  status: profiled
  tags: *id006
  url: /providers/coast/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id007
  name: Comdata
  slug: comdata
  status: profiled
  tags: *id008
  url: /providers/comdata/
- agent_band: human-only
  agent_readiness: 2.1
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id009
  name: Corpay / FLEETCOR
  slug: corpay
  status: profiled
  tags: *id010
  url: /providers/corpay/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: EFS
  slug: efs
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-aware
  agent_readiness: 21.7
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id013
  name: Fill-Rite FMS
  slug: fill-rite
  status: profiled
  tags: *id014
  url: /providers/fill-rite/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id015
  name: FuelCloud
  slug: fuelcloud
  status: profiled
  tags: *id016
  url: /providers/fuelcloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id017
  name: FuelMaster
  slug: fuelmaster
  status: profiled
  tags: *id018
  url: /providers/fuelmaster/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id019
  name: Intevacon
  slug: intevacon
  status: profiled
  tags: *id020
  url: /providers/intevacon/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id021
  name: WEX
  slug: wex
  status: profiled
  tags: *id022
  url: /providers/wex/
siblings:
- name: Fleetbase
  rows: 15
  url: /applications/fleet-telematics/fleetbase/
- name: Geotab
  rows: 5
  url: /applications/fleet-telematics/geotab/
- name: Motive
  rows: 14
  url: /applications/fleet-telematics/motive/
- name: Samsara
  rows: 12
  url: /applications/fleet-telematics/samsara/
- name: Traccar
  rows: 36
  url: /applications/fleet-telematics/traccar/
sitemap: true
title: 'Fleetio: Fleet Management & Telematics reference app'
---
