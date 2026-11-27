---
app: AgriWebb
app_slug: agriwebb
app_url: https://www.agriwebb.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3530
  key: agronomy-farm-advisory-management
  layer: domain
  name: Agronomy & Farm Advisory Management
  providers:
  - RCS (Resource Consulting Services)
  url: /capabilities/agronomy-farm-advisory-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3590.60.10
  key: BC-3590.60.10
  layer: domain
  name: Animal Identification Tagging
  providers:
  - Allflex (MSD Animal Health)
  - Shearwell Data
  url: /capabilities/livestock-identification-and-movement-compliance/
  via_parent: Livestock Identification and Movement Compliance
- attribution: API Evangelist extension
  id: AE-934
  key: AE-934
  layer: domain
  name: Farm Water & Tank Monitoring
  providers:
  - Agbot
  - Farmbot Monitoring Solutions
  - Farmo
  url: /capabilities/farm-water-tank-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.20
  key: AE-120.20.20
  layer: domain
  name: Satellite & Aerial Imagery
  providers:
  - Cibo Labs
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-3510.70.10
  key: BC-3510.70.10
  layer: domain
  name: Weight Gain Recording
  providers:
  - Gallagher
  - Te Pari
  - Tru-Test (Datamars)
  url: /capabilities/growth-and-performance-recording/
  via_parent: Growth and Performance Recording
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Figured
  url: /capabilities/general-ledger-management/
  via_parent: null
category:
  id: farm-agriculture
  name: Farm & Agriculture Management
  url: /applications/farm-agriculture/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.agriwebb.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-934
    key: AE-934
    name: Farm Water & Tank Monitoring
    url: /capabilities/farm-water-tank-monitoring/
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
    slug: agbot
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Agbot
  provider: agbot
  says: lists Agbot as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3590.60.10
    key: BC-3590.60.10
    name: Animal Identification Tagging
    url: /capabilities/livestock-identification-and-movement-compliance/
    via_parent: Livestock Identification and Movement Compliance
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: allflex
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Allflex (MSD Animal Health)
  provider: allflex
  says: lists Allflex (MSD Animal Health) as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.20
    key: AE-120.20.20
    name: Satellite & Aerial Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id005
      status: none
    slug: cibo-labs
    status: profiled
    tags: &id006
    - Agriculture
    - Data Analytics
    - Geospatial
    - Satellite Imagery
    url: /providers/cibo-labs/
  layer: domain
  name: Cibo Labs
  provider: cibo-labs
  says: lists Cibo Labs as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-934
    key: AE-934
    name: Farm Water & Tank Monitoring
    url: /capabilities/farm-water-tank-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id007
      status: unknown
    slug: farmbot-monitoring
    status: profiled
    tags: &id008
    - AgTech
    - Australia
    - Sensors
    - Water Monitoring
    url: /providers/farmbot-monitoring/
  layer: domain
  name: Farmbot Monitoring Solutions
  provider: farmbot-monitoring
  says: lists Farmbot Monitoring Solutions as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-934
    key: AE-934
    name: Farm Water & Tank Monitoring
    url: /capabilities/farm-water-tank-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.9
    band: emerging
    in_catalog: true
    kin_score: 20.7
    mcp: &id009
      status: unknown
    slug: farmo
    status: profiled
    tags: &id010
    - Agriculture
    - Industrial
    - Remote Monitoring
    - Smart City
    url: /providers/farmo/
  layer: domain
  name: Farmo
  provider: farmo
  says: lists Farmo as an integration
  source: https://www.agriwebb.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 20.8
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id011
      status: unknown
    slug: figured
    status: profiled
    tags: &id012
    - Agriculture
    - Farm Management
    - Finance
    - Software-as-a-Service
    url: /providers/figured/
  layer: common
  name: Figured
  provider: figured
  says: lists Figured as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3510.70.10
    key: BC-3510.70.10
    name: Weight Gain Recording
    url: /capabilities/growth-and-performance-recording/
    via_parent: Growth and Performance Recording
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id013
      status: unknown
    slug: gallagher-animal-management
    status: profiled
    tags: &id014
    - Animal Management
    - Electric Fencing
    - Weighing
    - eID
    url: /providers/gallagher-animal-management/
  layer: domain
  name: Gallagher
  provider: gallagher-animal-management
  says: lists Gallagher as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3530
    key: agronomy-farm-advisory-management
    name: Agronomy & Farm Advisory Management
    url: /capabilities/agronomy-farm-advisory-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.4
    mcp: &id015
      status: unknown
    slug: rcs
    status: profiled
    tags: &id016
    - Agriculture
    - Consulting
    - Professional Development
    - Training
    url: /providers/rcs/
  layer: domain
  name: RCS (Resource Consulting Services)
  provider: rcs
  says: lists RCS (Resource Consulting Services) as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3590.60.10
    key: BC-3590.60.10
    name: Animal Identification Tagging
    url: /capabilities/livestock-identification-and-movement-compliance/
    via_parent: Livestock Identification and Movement Compliance
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 13.9
    mcp: &id017
      status: unknown
    slug: shearwell
    status: profiled
    tags: &id018
    - Animal Identification
    - Farm Management
    - Livestock
    - RFID
    url: /providers/shearwell/
  layer: domain
  name: Shearwell Data
  provider: shearwell
  says: lists Shearwell Data as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3510.70.10
    key: BC-3510.70.10
    name: Weight Gain Recording
    url: /capabilities/growth-and-performance-recording/
    via_parent: Growth and Performance Recording
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.9
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id019
      status: unknown
    slug: te-pari
    status: profiled
    tags: &id020
    - Company
    - Equipment
    - Livestock
    - New Zealand
    url: /providers/te-pari/
  layer: domain
  name: Te Pari
  provider: te-pari
  says: lists Te Pari as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3510.70.10
    key: BC-3510.70.10
    name: Weight Gain Recording
    url: /capabilities/growth-and-performance-recording/
    via_parent: Growth and Performance Recording
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id021
      status: none
    slug: tru-test
    status: profiled
    tags: &id022
    - Agriculture
    - Company
    - Data
    - Livestock
    url: /providers/tru-test/
  layer: domain
  name: Tru-Test (Datamars)
  provider: tru-test
  says: lists Tru-Test (Datamars) as an integration
  source: https://www.agriwebb.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/farm-agriculture/agriwebb/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Agbot
  slug: agbot
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Allflex (MSD Animal Health)
  slug: allflex
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id005
  name: Cibo Labs
  slug: cibo-labs
  status: profiled
  tags: *id006
  url: /providers/cibo-labs/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id007
  name: Farmbot Monitoring Solutions
  slug: farmbot-monitoring
  status: profiled
  tags: *id008
  url: /providers/farmbot-monitoring/
- agent_band: agent-aware
  agent_readiness: 6.9
  band: emerging
  in_catalog: true
  kin_score: 20.7
  mcp: *id009
  name: Farmo
  slug: farmo
  status: profiled
  tags: *id010
  url: /providers/farmo/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id011
  name: Figured
  slug: figured
  status: profiled
  tags: *id012
  url: /providers/figured/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id013
  name: Gallagher
  slug: gallagher-animal-management
  status: profiled
  tags: *id014
  url: /providers/gallagher-animal-management/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.4
  mcp: *id015
  name: RCS (Resource Consulting Services)
  slug: rcs
  status: profiled
  tags: *id016
  url: /providers/rcs/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 13.9
  mcp: *id017
  name: Shearwell Data
  slug: shearwell
  status: profiled
  tags: *id018
  url: /providers/shearwell/
- agent_band: human-only
  agent_readiness: 4.9
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id019
  name: Te Pari
  slug: te-pari
  status: profiled
  tags: *id020
  url: /providers/te-pari/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id021
  name: Tru-Test (Datamars)
  slug: tru-test
  status: profiled
  tags: *id022
  url: /providers/tru-test/
siblings:
- name: Agworld
  rows: 17
  url: /applications/farm-agriculture/agworld/
- name: Climate FieldView
  rows: 20
  url: /applications/farm-agriculture/climate-fieldview/
- name: Farmbrite
  rows: 13
  url: /applications/farm-agriculture/farmbrite/
- name: farmOS
  rows: 1
  url: /applications/farm-agriculture/farmos/
- name: LiteFarm
  rows: 8
  url: /applications/farm-agriculture/litefarm/
- name: Open Food Network
  rows: 7
  url: /applications/farm-agriculture/open-food-network/
sitemap: true
title: 'AgriWebb: Farm & Agriculture Management reference app'
---
