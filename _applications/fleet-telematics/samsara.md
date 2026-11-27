---
app: Samsara
app_slug: samsara
app_url: https://www.samsara.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20
  key: connected-vehicles
  layer: domain
  name: Connected Vehicles
  providers:
  - Ford Pro
  - General Motors
  - Liebherr
  - Navistar
  - Rivian
  url: /capabilities/connected-vehicles/
  via_parent: null
- attribution: Turbo EA
  id: BC-2420.10
  key: dispatch-management
  layer: domain
  name: Dispatch Management
  providers:
  - McLeod LoadMaster
  url: /capabilities/dispatch-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-940
  key: AE-940
  layer: domain
  name: Fleet Fuel Cards & Fuel Transaction Data
  providers:
  - FLEETCOR Fuel Card
  - WEX Fleet Card
  url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.20
  key: fleet-maintenance-management
  layer: domain
  name: Fleet Maintenance Management
  providers:
  - Penske eDVIR (built by ATI)
  url: /capabilities/fleet-maintenance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Carrier Transicold (Lynx Fleet)
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2130
  key: insurance-underwriting-management
  layer: domain
  name: Insurance Underwriting Management
  providers:
  - Acuity Insurance
  - Fenchurch General Insurance
  url: /capabilities/insurance-underwriting-management/
  via_parent: null
category:
  id: fleet-telematics
  name: Fleet Management & Telematics
  url: /applications/fleet-telematics/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.samsara.com/marketplace
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2130
    key: insurance-underwriting-management
    name: Insurance Underwriting Management
    url: /capabilities/insurance-underwriting-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 14.5
    mcp: &id001
      status: unchecked
    slug: acuity-insurance
    status: profiled
    tags: &id002
    - Company
    - Insurance
    - Mutual
    - Personal Insurance
    url: /providers/acuity-insurance/
  layer: domain
  name: Acuity Insurance
  provider: acuity-insurance
  says: lists Acuity Insurance as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 2.8
    mcp: &id003
      status: unchecked
    slug: carrier-transicold
    status: profiled
    tags: &id004
    - Cold Chain
    - Company
    - IoT
    - Transport Refrigeration
    url: /providers/carrier-transicold/
  layer: domain
  name: Carrier Transicold (Lynx Fleet)
  provider: carrier-transicold
  says: lists Carrier Transicold (Lynx Fleet) as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2130
    key: insurance-underwriting-management
    name: Insurance Underwriting Management
    url: /capabilities/insurance-underwriting-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.2
    mcp: &id005
      status: unchecked
    slug: fenchurch-general-insurance
    status: profiled
    tags: &id006
    - Company
    - Finance
    - General Insurance
    - Insurance
    url: /providers/fenchurch-general-insurance/
  layer: domain
  name: Fenchurch General Insurance
  provider: fenchurch-general-insurance
  says: lists Fenchurch General Insurance as an integration
  source: https://www.samsara.com/marketplace
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
    mcp: &id007
      status: unknown
    slug: corpay
    status: profiled
    tags: &id008
    - Accounts Payable
    - Corporate Payments
    - Cross-Border Payments
    - Payments
    url: /providers/corpay/
  layer: domain
  name: FLEETCOR Fuel Card
  provider: corpay
  says: lists FLEETCOR Fuel Card as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20
    key: connected-vehicles
    name: Connected Vehicles
    url: /capabilities/connected-vehicles/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id009
      source: https://www.ford.com/ford-vehicle-mcp/mcp
      status: documented
    slug: fordpass
    status: profiled
    tags: &id010
    - Automotive
    - Connected Vehicles
    - Fleet Management
    - Telematics
    url: /providers/fordpass/
  layer: domain
  name: Ford Pro
  provider: fordpass
  says: lists Ford Pro as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20
    key: connected-vehicles
    name: Connected Vehicles
    url: /capabilities/connected-vehicles/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id011
      status: none
    slug: general-motors
    status: profiled
    tags: &id012
    - Automobiles
    - Cars
    - Connected Vehicles
    - Vehicles
    url: /providers/general-motors/
  layer: domain
  name: General Motors
  provider: general-motors
  says: lists General Motors as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20
    key: connected-vehicles
    name: Connected Vehicles
    url: /capabilities/connected-vehicles/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.6
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id013
      status: unchecked
    slug: liebherr
    status: profiled
    tags: &id014
    - Company
    - Engineering
    - Heavy Equipment
    - Manufacturing
    url: /providers/liebherr/
  layer: domain
  name: Liebherr
  provider: liebherr
  says: lists Liebherr as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.10
    key: dispatch-management
    name: Dispatch Management
    url: /capabilities/dispatch-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: minimal
    in_catalog: true
    kin_score: 8.3
    mcp: &id015
      status: unchecked
    slug: mcleod-software
    status: profiled
    tags: &id016
    - Logistics
    - Software
    - TMS
    - Transportation
    url: /providers/mcleod-software/
  layer: domain
  name: McLeod LoadMaster
  provider: mcleod-software
  says: lists McLeod LoadMaster as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20
    key: connected-vehicles
    name: Connected Vehicles
    url: /capabilities/connected-vehicles/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.7
    mcp: &id017
      status: unknown
    slug: navistar-international
    status: profiled
    tags: &id018
    - Commercial Vehicles
    - Fortune 500
    - Manufacturing
    - Trucks
    url: /providers/navistar-international/
  layer: domain
  name: Navistar
  provider: navistar-international
  says: lists Navistar as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2430.20
    key: fleet-maintenance-management
    name: Fleet Maintenance Management
    url: /capabilities/fleet-maintenance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id019
      status: unknown
    slug: penske
    status: profiled
    tags: &id020
    - Automotive
    - Logistics
    - Transportation
    - Truck Leasing
    url: /providers/penske/
  layer: domain
  name: Penske eDVIR (built by ATI)
  provider: penske
  says: lists Penske eDVIR (built by ATI) as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20
    key: connected-vehicles
    name: Connected Vehicles
    url: /capabilities/connected-vehicles/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.2
    mcp: &id021
      status: none
    slug: rivian-automotive
    status: profiled
    tags: &id022
    - Automotive
    - Connected Vehicles
    - Electric Vehicles
    - Manufacturing
    url: /providers/rivian-automotive/
  layer: domain
  name: Rivian
  provider: rivian-automotive
  says: lists Rivian as an integration
  source: https://www.samsara.com/marketplace
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
    mcp: &id023
      status: none
    slug: wex
    status: profiled
    tags: &id024 []
    url: /providers/wex/
  layer: domain
  name: WEX Fleet Card
  provider: wex
  says: lists WEX Fleet Card as an integration
  source: https://www.samsara.com/marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fleet-telematics/samsara/
providers:
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 14.5
  mcp: *id001
  name: Acuity Insurance
  slug: acuity-insurance
  status: profiled
  tags: *id002
  url: /providers/acuity-insurance/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.8
  mcp: *id003
  name: Carrier Transicold (Lynx Fleet)
  slug: carrier-transicold
  status: profiled
  tags: *id004
  url: /providers/carrier-transicold/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id005
  name: Fenchurch General Insurance
  slug: fenchurch-general-insurance
  status: profiled
  tags: *id006
  url: /providers/fenchurch-general-insurance/
- agent_band: human-only
  agent_readiness: 2.1
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id007
  name: FLEETCOR Fuel Card
  slug: corpay
  status: profiled
  tags: *id008
  url: /providers/corpay/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id009
  name: Ford Pro
  slug: fordpass
  status: profiled
  tags: *id010
  url: /providers/fordpass/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id011
  name: General Motors
  slug: general-motors
  status: profiled
  tags: *id012
  url: /providers/general-motors/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id013
  name: Liebherr
  slug: liebherr
  status: profiled
  tags: *id014
  url: /providers/liebherr/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: minimal
  in_catalog: true
  kin_score: 8.3
  mcp: *id015
  name: McLeod LoadMaster
  slug: mcleod-software
  status: profiled
  tags: *id016
  url: /providers/mcleod-software/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.7
  mcp: *id017
  name: Navistar
  slug: navistar-international
  status: profiled
  tags: *id018
  url: /providers/navistar-international/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id019
  name: Penske eDVIR (built by ATI)
  slug: penske
  status: profiled
  tags: *id020
  url: /providers/penske/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.2
  mcp: *id021
  name: Rivian
  slug: rivian-automotive
  status: profiled
  tags: *id022
  url: /providers/rivian-automotive/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id023
  name: WEX Fleet Card
  slug: wex
  status: profiled
  tags: *id024
  url: /providers/wex/
siblings:
- name: Fleetbase
  rows: 15
  url: /applications/fleet-telematics/fleetbase/
- name: Fleetio
  rows: 11
  url: /applications/fleet-telematics/fleetio/
- name: Geotab
  rows: 5
  url: /applications/fleet-telematics/geotab/
- name: Motive
  rows: 14
  url: /applications/fleet-telematics/motive/
- name: Traccar
  rows: 36
  url: /applications/fleet-telematics/traccar/
sitemap: true
title: 'Samsara: Fleet Management & Telematics reference app'
---
