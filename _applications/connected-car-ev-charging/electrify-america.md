---
app: Electrify America
app_slug: electrify-america
app_url: https://www.electrifyamerica.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - Audi
  - BMW
  - Ford
  - Lucid Motors
  - Mercedes-Benz
  - Nissan
  - Porsche
  - Rivian
  - Volkswagen
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 9
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.electrifyamerica.com/plug-and-charge/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id001
      status: unknown
    slug: audi-connect
    status: profiled
    tags: &id002
    - Automotive
    - Connected Vehicles
    - Mobility
    - Telematics
    url: /providers/audi-connect/
  layer: domain
  name: Audi
  provider: audi-connect
  says: lists Audi as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 20.2
    mcp: &id003
      status: unknown
    slug: bmw
    status: profiled
    tags: &id004
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/bmw/
  layer: domain
  name: BMW
  provider: bmw
  says: lists BMW as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id005
      status: none
    slug: ford
    status: profiled
    tags: &id006
    - Automobiles
    - Cars
    - Connected Vehicles
    - Vehicles
    url: /providers/ford/
  layer: domain
  name: Ford
  provider: ford
  says: lists Ford as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id007
      status: unknown
    slug: lucid-motors
    status: profiled
    tags: &id008
    - Automotive
    - Connected Vehicles
    - Electric Vehicles
    - Luxury Vehicles
    url: /providers/lucid-motors/
  layer: domain
  name: Lucid Motors
  provider: lucid-motors
  says: lists Lucid Motors as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: thin
    in_catalog: true
    kin_score: 29.4
    mcp: &id009
      status: none
    slug: mercedes-benz
    status: profiled
    tags: &id010
    - Automobiles
    - Cars
    - Vehicles
    url: /providers/mercedes-benz/
  layer: domain
  name: Mercedes-Benz
  provider: mercedes-benz
  says: lists Mercedes-Benz as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id011
      status: unknown
    slug: nissan
    status: profiled
    tags: &id012
    - Automobiles
    - Cars
    - Vehicles
    url: /providers/nissan/
  layer: domain
  name: Nissan
  provider: nissan
  says: lists Nissan as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.2
    band: thin
    in_catalog: true
    kin_score: 30.0
    mcp: &id013
      status: none
    slug: porsche
    status: profiled
    tags: &id014
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/porsche/
  layer: domain
  name: Porsche
  provider: porsche
  says: lists Porsche as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id015
      status: none
    slug: rivian-automotive
    status: profiled
    tags: &id016
    - Automotive
    - Connected Vehicles
    - Electric Vehicles
    - Manufacturing
    url: /providers/rivian-automotive/
  layer: domain
  name: Rivian
  provider: rivian-automotive
  says: lists Rivian as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id017
      status: none
    slug: volkswagen
    status: profiled
    tags: &id018
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/volkswagen/
  layer: domain
  name: Volkswagen
  provider: volkswagen
  says: lists Volkswagen as an integration
  source: https://www.electrifyamerica.com/plug-and-charge/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/electrify-america/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id001
  name: Audi
  slug: audi-connect
  status: profiled
  tags: *id002
  url: /providers/audi-connect/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 20.2
  mcp: *id003
  name: BMW
  slug: bmw
  status: profiled
  tags: *id004
  url: /providers/bmw/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id005
  name: Ford
  slug: ford
  status: profiled
  tags: *id006
  url: /providers/ford/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id007
  name: Lucid Motors
  slug: lucid-motors
  status: profiled
  tags: *id008
  url: /providers/lucid-motors/
- agent_band: human-only
  agent_readiness: 0.6
  band: thin
  in_catalog: true
  kin_score: 29.4
  mcp: *id009
  name: Mercedes-Benz
  slug: mercedes-benz
  status: profiled
  tags: *id010
  url: /providers/mercedes-benz/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id011
  name: Nissan
  slug: nissan
  status: profiled
  tags: *id012
  url: /providers/nissan/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 30.0
  mcp: *id013
  name: Porsche
  slug: porsche
  status: profiled
  tags: *id014
  url: /providers/porsche/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id015
  name: Rivian
  slug: rivian-automotive
  status: profiled
  tags: *id016
  url: /providers/rivian-automotive/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Volkswagen
  slug: volkswagen
  status: profiled
  tags: *id018
  url: /providers/volkswagen/
siblings:
- name: ChargePoint
  rows: 6
  url: /applications/connected-car-ev-charging/chargepoint/
- name: evcc
  rows: 71
  url: /applications/connected-car-ev-charging/evcc/
- name: Open Charge Map
  rows: 13
  url: /applications/connected-car-ev-charging/open-charge-map/
- name: openWB
  rows: 30
  url: /applications/connected-car-ev-charging/openwb/
- name: TeslaLogger
  rows: 15
  url: /applications/connected-car-ev-charging/teslalogger/
- name: TeslaMate
  rows: 3
  url: /applications/connected-car-ev-charging/teslamate/
sitemap: true
title: 'Electrify America: Connected Car & EV Charging reference app'
---
