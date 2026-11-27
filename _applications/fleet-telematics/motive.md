---
app: Motive
app_slug: motive
app_url: https://gomotive.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20
  key: connected-vehicles
  layer: domain
  name: Connected Vehicles
  providers:
  - John Deere JDLink
  - Komatsu Komtrax
  - Stellantis
  url: /capabilities/connected-vehicles/
  via_parent: null
- attribution: Turbo EA
  id: BC-2420.10
  key: dispatch-management
  layer: domain
  name: Dispatch Management
  providers:
  - Alvys
  - AscendTMS
  - HCSS
  url: /capabilities/dispatch-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-940
  key: AE-940
  layer: domain
  name: Fleet Fuel Cards & Fuel Transaction Data
  providers:
  - AtoB
  url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.20
  key: fleet-maintenance-management
  layer: domain
  name: Fleet Maintenance Management
  providers:
  - AMCS Fleet Maintenance
  - AUTOsist
  url: /capabilities/fleet-maintenance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2400
  key: freight-capacity-management
  layer: domain
  name: Freight Capacity Management
  providers:
  - Amazon Relay
  url: /capabilities/freight-capacity-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1050.20
  key: service-dispatch-management
  layer: domain
  name: Service Dispatch Management
  providers:
  - Arrivy
  url: /capabilities/service-dispatch-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - ADP
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Auth0 Single Sign-On
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: fleet-telematics
  name: Fleet Management & Telematics
  url: /applications/fleet-telematics/
counts:
  declared: 14
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://marketplace.gomotive.com/
- route: integrations page
  url: https://marketplace.gomotive.com/t/categories/tms
integrations:
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.8
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id001
      status: none
    slug: adp
    status: profiled
    tags: &id002
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
  layer: common
  name: ADP
  provider: adp
  says: lists ADP as an integration
  source: https://marketplace.gomotive.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id003
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id004
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: common
  name: Airtable
  provider: airtable
  says: lists Airtable as an integration
  source: https://marketplace.gomotive.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id005
      source: https://docs.alvys.com/en/api/guides/mcp
      status: verified
    slug: alvys
    status: profiled
    tags: &id006
    - Company
    url: /providers/alvys/
  layer: domain
  name: Alvys
  provider: alvys
  says: lists Alvys as an integration
  source: https://marketplace.gomotive.com/t/categories/tms
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id007
      status: unchecked
    slug: amazon-relay
    status: profiled
    tags: &id008
    - Company
    - Freight
    - Logistics
    - Transportation
    url: /providers/amazon-relay/
  layer: domain
  name: Amazon Relay
  provider: amazon-relay
  says: lists Amazon Relay as an integration
  source: https://marketplace.gomotive.com/
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
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id009
      status: none
    slug: amcs-group
    status: profiled
    tags: &id010
    - Company
    - Recycling
    - Transport
    - Waste Management
    url: /providers/amcs-group/
  layer: domain
  name: AMCS Fleet Maintenance
  provider: amcs-group
  says: lists AMCS Fleet Maintenance as an integration
  source: https://marketplace.gomotive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1050.20
    key: service-dispatch-management
    name: Service Dispatch Management
    url: /capabilities/service-dispatch-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id011
      status: unchecked
    slug: arrivy
    status: profiled
    tags: &id012
    - Cloud Platform
    - Company
    - Field Service Management
    - Operations Software
    url: /providers/arrivy/
  layer: domain
  name: Arrivy
  provider: arrivy
  says: lists Arrivy as an integration
  source: https://marketplace.gomotive.com/t/categories/tms
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
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id013
      status: unchecked
    slug: ascendtms
    status: profiled
    tags: &id014
    - Company
    - Logistics
    - Software-as-a-Service
    - Transportation
    url: /providers/ascendtms/
  layer: domain
  name: AscendTMS
  provider: ascendtms
  says: lists AscendTMS as an integration
  source: https://marketplace.gomotive.com/t/categories/tms
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
    kin_score: 15.2
    mcp: &id015
      status: none
    slug: atob
    status: profiled
    tags: &id016
    - Company
    - Fleet Management
    - Fuel Cards
    - Payments
    url: /providers/atob/
  layer: domain
  name: AtoB
  provider: atob
  says: lists AtoB as an integration
  source: https://marketplace.gomotive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id017
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id018
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0 Single Sign-On
  provider: auth0
  says: lists Auth0 Single Sign-On as an integration
  source: https://marketplace.gomotive.com/
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 19.4
    mcp: &id019
      status: unchecked
    slug: autosist
    status: profiled
    tags: &id020
    - Fleet Management
    - Maintenance
    - Software
    - Software-as-a-Service
    url: /providers/autosist/
  layer: domain
  name: AUTOsist
  provider: autosist
  says: lists AUTOsist as an integration
  source: https://marketplace.gomotive.com/
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
    agent_band: agent-ready
    agent_readiness: 39.2
    band: developing
    in_catalog: true
    kin_score: 43.2
    mcp: &id021
      status: unchecked
    slug: hcss
    status: profiled
    tags: &id022
    - Construction
    - Estimating
    - Project Management
    - Software
    url: /providers/hcss/
  layer: domain
  name: HCSS
  provider: hcss
  says: lists HCSS as an integration
  source: https://marketplace.gomotive.com/
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
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id023
      status: none
    slug: john-deere
    status: profiled
    tags: &id024
    - Agriculture
    - Combines
    - Construction
    - Excavators
    url: /providers/john-deere/
  layer: domain
  name: John Deere JDLink
  provider: john-deere
  says: lists John Deere JDLink as an integration
  source: https://marketplace.gomotive.com/
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id025
      status: unchecked
    slug: komatsu
    status: profiled
    tags: &id026
    - Company
    - Construction
    - Industrial Equipment
    - Mining
    url: /providers/komatsu/
  layer: domain
  name: Komatsu Komtrax
  provider: komatsu
  says: lists Komatsu Komtrax as an integration
  source: https://marketplace.gomotive.com/
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
    agent_readiness: 19.9
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id027
      status: none
    slug: stellantis
    status: profiled
    tags: &id028
    - Automotive
    - Company
    - Manufacturing
    - Mobility
    url: /providers/stellantis/
  layer: domain
  name: Stellantis
  provider: stellantis
  says: lists Stellantis as an integration
  source: https://marketplace.gomotive.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fleet-telematics/motive/
providers:
- agent_band: agent-ready
  agent_readiness: 39.8
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id001
  name: ADP
  slug: adp
  status: profiled
  tags: *id002
  url: /providers/adp/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id003
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id004
  url: /providers/airtable/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id005
  name: Alvys
  slug: alvys
  status: profiled
  tags: *id006
  url: /providers/alvys/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id007
  name: Amazon Relay
  slug: amazon-relay
  status: profiled
  tags: *id008
  url: /providers/amazon-relay/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id009
  name: AMCS Fleet Maintenance
  slug: amcs-group
  status: profiled
  tags: *id010
  url: /providers/amcs-group/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id011
  name: Arrivy
  slug: arrivy
  status: profiled
  tags: *id012
  url: /providers/arrivy/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id013
  name: AscendTMS
  slug: ascendtms
  status: profiled
  tags: *id014
  url: /providers/ascendtms/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id015
  name: AtoB
  slug: atob
  status: profiled
  tags: *id016
  url: /providers/atob/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id017
  name: Auth0 Single Sign-On
  slug: auth0
  status: profiled
  tags: *id018
  url: /providers/auth0/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 19.4
  mcp: *id019
  name: AUTOsist
  slug: autosist
  status: profiled
  tags: *id020
  url: /providers/autosist/
- agent_band: agent-ready
  agent_readiness: 39.2
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id021
  name: HCSS
  slug: hcss
  status: profiled
  tags: *id022
  url: /providers/hcss/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id023
  name: John Deere JDLink
  slug: john-deere
  status: profiled
  tags: *id024
  url: /providers/john-deere/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id025
  name: Komatsu Komtrax
  slug: komatsu
  status: profiled
  tags: *id026
  url: /providers/komatsu/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id027
  name: Stellantis
  slug: stellantis
  status: profiled
  tags: *id028
  url: /providers/stellantis/
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
- name: Samsara
  rows: 12
  url: /applications/fleet-telematics/samsara/
- name: Traccar
  rows: 36
  url: /applications/fleet-telematics/traccar/
sitemap: true
title: 'Motive: Fleet Management & Telematics reference app'
---
