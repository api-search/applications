---
app: Climate FieldView
app_slug: climate-fieldview
app_url: https://climate.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3600
  key: agri-environmental-stewardship-management
  layer: domain
  name: Agri-Environmental Stewardship Management
  providers:
  - Arva Intelligence
  - Regrow
  url: /capabilities/agri-environmental-stewardship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3550
  key: agricultural-inputs-management
  layer: domain
  name: Agricultural Inputs Management
  providers:
  - Agvance (SSI)
  - Pivot Bio
  - WinField United Data Silo
  url: /capabilities/agricultural-inputs-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3530
  key: agronomy-farm-advisory-management
  layer: domain
  name: Agronomy & Farm Advisory Management
  providers:
  - TELUS Agriculture
  url: /capabilities/agronomy-farm-advisory-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3570
  key: commodity-origination-merchandising-management
  layer: domain
  name: Commodity Origination & Merchandising Management
  providers:
  - Combyne
  url: /capabilities/commodity-origination-merchandising-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-120.50
  key: BC-120.50
  layer: domain
  name: Corporate Insurance Management
  providers:
  - Farmers Mutual Hail
  - Great American Insurance Group
  - MyAgData
  url: /capabilities/corporate-insurance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3500.70
  key: crop-monitoring-and-scouting
  layer: domain
  name: Crop Monitoring and Scouting
  providers:
  - DroneDeploy
  - Intelinair
  - Sentera
  url: /capabilities/crop-monitoring-and-scouting/
  via_parent: null
- attribution: Turbo EA
  id: BC-3500
  key: crop-production-management
  layer: domain
  name: Crop Production Management
  providers:
  - Bushel Farm
  url: /capabilities/crop-production-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3540.30
  key: farm-equipment-management
  layer: domain
  name: Farm Equipment Management
  providers:
  - Ag Leader AgFiniti / SMS
  - CLAAS
  - John Deere Operations Center
  url: /capabilities/farm-equipment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3530.20
  key: nutrient-management-planning
  layer: domain
  name: Nutrient Management Planning
  providers:
  - Pattern Ag
  - SoilOptix
  url: /capabilities/nutrient-management-planning/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Traction Ag
  url: /capabilities/general-ledger-management/
  via_parent: null
category:
  id: farm-agriculture
  name: Farm & Agriculture Management
  url: /applications/farm-agriculture/
counts:
  declared: 20
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://climate.com/en-us/partners.html
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3540.30
    key: farm-equipment-management
    name: Farm Equipment Management
    url: /capabilities/farm-equipment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.5
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id001
      status: unknown
    slug: ag-leader
    status: profiled
    tags: &id002
    - Agriculture
    - Company
    - Farm Data
    - Precision Agriculture
    url: /providers/ag-leader/
  layer: domain
  name: Ag Leader AgFiniti / SMS
  provider: ag-leader
  says: lists Ag Leader AgFiniti / SMS as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3550
    key: agricultural-inputs-management
    name: Agricultural Inputs Management
    url: /capabilities/agricultural-inputs-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id003
      status: unknown
    slug: agvance
    status: profiled
    tags: &id004
    - Company
    url: /providers/agvance/
  layer: domain
  name: Agvance (SSI)
  provider: agvance
  says: lists Agvance (SSI) as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3600
    key: agri-environmental-stewardship-management
    name: Agri-Environmental Stewardship Management
    url: /capabilities/agri-environmental-stewardship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id005
      status: unchecked
    slug: arva-intelligence
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: Arva Intelligence
  provider: arva-intelligence
  says: lists Arva Intelligence as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3500
    key: crop-production-management
    name: Crop Production Management
    url: /capabilities/crop-production-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id007
      status: unknown
    slug: bushel
    status: profiled
    tags: &id008
    - Agriculture
    - CRM
    - Farm Management
    - Software-as-a-Service
    url: /providers/bushel/
  layer: domain
  name: Bushel Farm
  provider: bushel
  says: lists Bushel Farm as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3540.30
    key: farm-equipment-management
    name: Farm Equipment Management
    url: /capabilities/farm-equipment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id009
      status: unknown
    slug: claas
    status: profiled
    tags: &id010
    - Agriculture
    - Germany
    - Machinery
    - Manufacturing
    url: /providers/claas/
  layer: domain
  name: CLAAS
  provider: claas
  says: lists CLAAS as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3570
    key: commodity-origination-merchandising-management
    name: Commodity Origination & Merchandising Management
    url: /capabilities/commodity-origination-merchandising-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id011
      status: unknown
    slug: combyne
    status: profiled
    tags: &id012
    - Agriculture
    - Farming
    - Grain
    - Software-as-a-Service
    url: /providers/combyne/
  layer: domain
  name: Combyne
  provider: combyne
  says: lists Combyne as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3500.70
    key: crop-monitoring-and-scouting
    name: Crop Monitoring and Scouting
    url: /capabilities/crop-monitoring-and-scouting/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 29.9
    mcp: &id013
      status: unknown
    slug: dronedeploy
    status: profiled
    tags: &id014
    - Aerial Analytics
    - Drone Mapping
    - Geospatial
    - Reality Capture
    url: /providers/dronedeploy/
  layer: domain
  name: DroneDeploy
  provider: dronedeploy
  says: lists DroneDeploy as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-120.50
    key: BC-120.50
    name: Corporate Insurance Management
    url: /capabilities/corporate-insurance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id015
      status: unknown
    slug: farmers-mutual-hail
    status: profiled
    tags: &id016
    - Agriculture
    - Company
    - Hail
    - Insurance
    url: /providers/farmers-mutual-hail/
  layer: domain
  name: Farmers Mutual Hail
  provider: farmers-mutual-hail
  says: lists Farmers Mutual Hail as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-120.50
    key: BC-120.50
    name: Corporate Insurance Management
    url: /capabilities/corporate-insurance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id017
      status: unknown
    slug: great-american-insurance-group
    status: profiled
    tags: &id018
    - Casualty
    - Insurance
    - Property
    - Specialty
    url: /providers/great-american-insurance-group/
  layer: domain
  name: Great American Insurance Group
  provider: great-american-insurance-group
  says: lists Great American Insurance Group as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3500.70
    key: crop-monitoring-and-scouting
    name: Crop Monitoring and Scouting
    url: /capabilities/crop-monitoring-and-scouting/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: intelinair
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: Intelinair
  provider: intelinair
  says: lists Intelinair as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3540.30
    key: farm-equipment-management
    name: Farm Equipment Management
    url: /capabilities/farm-equipment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id021
      status: none
    slug: john-deere
    status: profiled
    tags: &id022
    - Agriculture
    - Combines
    - Construction
    - Excavators
    url: /providers/john-deere/
  layer: domain
  name: John Deere Operations Center
  provider: john-deere
  says: lists John Deere Operations Center as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-120.50
    key: BC-120.50
    name: Corporate Insurance Management
    url: /capabilities/corporate-insurance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id023
      status: unknown
    slug: myagdata
    status: profiled
    tags: &id024
    - Agriculture
    - Company
    - Reporting
    - USDA
    url: /providers/myagdata/
  layer: domain
  name: MyAgData
  provider: myagdata
  says: lists MyAgData as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3530.20
    key: nutrient-management-planning
    name: Nutrient Management Planning
    url: /capabilities/nutrient-management-planning/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.5
    mcp: &id025
      status: unknown
    slug: pattern-ag
    status: profiled
    tags: &id026
    - AgTech
    - Agriculture
    - Company
    - Soil
    url: /providers/pattern-ag/
  layer: domain
  name: Pattern Ag
  provider: pattern-ag
  says: lists Pattern Ag as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3550
    key: agricultural-inputs-management
    name: Agricultural Inputs Management
    url: /capabilities/agricultural-inputs-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id027
      status: unknown
    slug: pivot-bio
    status: profiled
    tags: &id028
    - AgTech
    - Agriculture
    - Biotechnology
    - Synthetic Biology
    url: /providers/pivot-bio/
  layer: domain
  name: Pivot Bio
  provider: pivot-bio
  says: lists Pivot Bio as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3600
    key: agri-environmental-stewardship-management
    name: Agri-Environmental Stewardship Management
    url: /capabilities/agri-environmental-stewardship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: regrow
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: Regrow
  provider: regrow
  says: lists Regrow as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3500.70
    key: crop-monitoring-and-scouting
    name: Crop Monitoring and Scouting
    url: /capabilities/crop-monitoring-and-scouting/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id031
      status: unknown
    slug: sentera
    status: profiled
    tags: &id032
    - Aerial Imagery
    - Drones
    - Precision Agriculture
    - Sensors
    url: /providers/sentera/
  layer: domain
  name: Sentera
  provider: sentera
  says: lists Sentera as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3530.20
    key: nutrient-management-planning
    name: Nutrient Management Planning
    url: /capabilities/nutrient-management-planning/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id033
      status: none
    slug: soiloptix
    status: profiled
    tags: &id034
    - Agriculture
    - Mapping
    - Precision Agriculture
    - Soil-Analysis
    url: /providers/soiloptix/
  layer: domain
  name: SoilOptix
  provider: soiloptix
  says: lists SoilOptix as an integration
  source: https://climate.com/en-us/partners.html
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
    agent_band: agent-aware
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 50.4
    mcp: &id035
      status: none
    slug: telus
    status: profiled
    tags: &id036
    - Broadband
    - Canada
    - Mobile Network Operator
    - Telecommunications
    url: /providers/telus/
  layer: domain
  name: TELUS Agriculture
  provider: telus
  says: lists TELUS Agriculture as an integration
  source: https://climate.com/en-us/partners.html
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: traction-ag
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: common
  name: Traction Ag
  provider: traction-ag
  says: lists Traction Ag as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3550
    key: agricultural-inputs-management
    name: Agricultural Inputs Management
    url: /capabilities/agricultural-inputs-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 5.8
    mcp: &id039
      status: unknown
    slug: winfield-united
    status: profiled
    tags: &id040
    - AgTech
    - Agriculture
    - Data
    - Farming
    url: /providers/winfield-united/
  layer: domain
  name: WinField United Data Silo
  provider: winfield-united
  says: lists WinField United Data Silo as an integration
  source: https://climate.com/en-us/partners.html
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/farm-agriculture/climate-fieldview/
providers:
- agent_band: agent-aware
  agent_readiness: 20.5
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id001
  name: Ag Leader AgFiniti / SMS
  slug: ag-leader
  status: profiled
  tags: *id002
  url: /providers/ag-leader/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id003
  name: Agvance (SSI)
  slug: agvance
  status: profiled
  tags: *id004
  url: /providers/agvance/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: Arva Intelligence
  slug: arva-intelligence
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id007
  name: Bushel Farm
  slug: bushel
  status: profiled
  tags: *id008
  url: /providers/bushel/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id009
  name: CLAAS
  slug: claas
  status: profiled
  tags: *id010
  url: /providers/claas/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id011
  name: Combyne
  slug: combyne
  status: profiled
  tags: *id012
  url: /providers/combyne/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 29.9
  mcp: *id013
  name: DroneDeploy
  slug: dronedeploy
  status: profiled
  tags: *id014
  url: /providers/dronedeploy/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id015
  name: Farmers Mutual Hail
  slug: farmers-mutual-hail
  status: profiled
  tags: *id016
  url: /providers/farmers-mutual-hail/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id017
  name: Great American Insurance Group
  slug: great-american-insurance-group
  status: profiled
  tags: *id018
  url: /providers/great-american-insurance-group/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Intelinair
  slug: intelinair
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id021
  name: John Deere Operations Center
  slug: john-deere
  status: profiled
  tags: *id022
  url: /providers/john-deere/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id023
  name: MyAgData
  slug: myagdata
  status: profiled
  tags: *id024
  url: /providers/myagdata/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.5
  mcp: *id025
  name: Pattern Ag
  slug: pattern-ag
  status: profiled
  tags: *id026
  url: /providers/pattern-ag/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id027
  name: Pivot Bio
  slug: pivot-bio
  status: profiled
  tags: *id028
  url: /providers/pivot-bio/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: Regrow
  slug: regrow
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id031
  name: Sentera
  slug: sentera
  status: profiled
  tags: *id032
  url: /providers/sentera/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id033
  name: SoilOptix
  slug: soiloptix
  status: profiled
  tags: *id034
  url: /providers/soiloptix/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id035
  name: TELUS Agriculture
  slug: telus
  status: profiled
  tags: *id036
  url: /providers/telus/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: Traction Ag
  slug: traction-ag
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 5.8
  mcp: *id039
  name: WinField United Data Silo
  slug: winfield-united
  status: profiled
  tags: *id040
  url: /providers/winfield-united/
siblings:
- name: AgriWebb
  rows: 11
  url: /applications/farm-agriculture/agriwebb/
- name: Agworld
  rows: 17
  url: /applications/farm-agriculture/agworld/
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
title: 'Climate FieldView: Farm & Agriculture Management reference app'
---
