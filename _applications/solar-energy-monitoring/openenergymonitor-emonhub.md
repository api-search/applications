---
app: OpenEnergyMonitor (emonHub)
app_slug: openenergymonitor-emonhub
app_url: https://github.com/openenergymonitor/emonhub
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.30
  key: home-energy
  layer: domain
  name: Home Energy
  providers:
  - Eastron (SDM120 meter)
  - GoodWe
  - Renogy
  - Shelly
  - SMA Solar Technology
  - Sunamp
  - Tesla Powerwall
  - Victron Energy (VE.Direct)
  url: /capabilities/home-energy/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - BMW ConnectedDrive
  - Jaguar Land Rover
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - InfluxDB
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: solar-energy-monitoring
  name: Home Energy & Solar Monitoring
  url: /applications/solar-energy-monitoring/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: source code
  url: https://github.com/openenergymonitor/emonhub/tree/master/src/interfacers
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
    agent_band: agent-aware
    agent_readiness: 26.7
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id001
      source: https://api.bmw.com/mcp
      status: documented
    slug: bmw-connecteddrive
    status: profiled
    tags: &id002
    - Automotive
    - Connected Vehicles
    - Telematics
    - Vehicle Data
    url: /providers/bmw-connecteddrive/
  layer: domain
  name: BMW ConnectedDrive
  provider: bmw-connecteddrive
  says: ships the BMW ConnectedDrive SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubBMWInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id003
      status: unchecked
    slug: eastron
    status: profiled
    tags: &id004
    - EV Charging
    - Electricity Meters
    - Energy Measurement
    - Smart Meter
    url: /providers/eastron/
  layer: domain
  name: Eastron (SDM120 meter)
  provider: eastron
  says: ships the Eastron (SDM120 meter) SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSDM120Interfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.5
    mcp: &id005
      status: unchecked
    slug: goodwe
    status: profiled
    tags: &id006
    - Company
    - Energy Storage
    - Inverters
    - Solar
    url: /providers/goodwe/
  layer: domain
  name: GoodWe
  provider: goodwe
  says: ships the GoodWe SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubGoodWeInterfacer.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id007
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id008
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
  layer: common
  name: InfluxDB
  provider: influxdata
  says: ships the InfluxDB SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubInfluxInterfacer.py
  tier: observed
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
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id009
      status: unknown
    slug: jlr
    status: profiled
    tags: &id010
    - Automotive
    - Company
    - Connected Vehicles
    - Vehicle Data
    url: /providers/jlr/
  layer: domain
  name: Jaguar Land Rover
  provider: jlr
  says: ships the Jaguar Land Rover SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubJaguarLandRoverInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.4
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id011
      status: unchecked
    slug: renogy
    status: profiled
    tags: &id012
    - Company
    - Off-Grid
    - Renewable Energy
    - Solar
    url: /providers/renogy/
  layer: domain
  name: Renogy
  provider: renogy
  says: ships the Renogy SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubModbusRenogyInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id013
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id014
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: ships the Shelly SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubShellyInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id015
      status: unknown
    slug: sma-solar
    status: profiled
    tags: &id016
    - Company
    - Energy
    - Inverters
    - Solar
    url: /providers/sma-solar/
  layer: domain
  name: SMA Solar Technology
  provider: sma-solar
  says: ships the SMA Solar Technology SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSMASolarInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id017
      status: unchecked
    slug: sunamp
    status: profiled
    tags: &id018
    - Company
    - Energy
    - Heat Batteries
    - Thermal Storage
    url: /providers/sunamp/
  layer: domain
  name: Sunamp
  provider: sunamp
  says: ships the Sunamp SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSunampInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.2
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id019
      status: unknown
    slug: tesla-energy
    status: profiled
    tags: &id020
    - Battery Storage
    - Clean Energy
    - Energy
    - Solar
    url: /providers/tesla-energy/
  layer: domain
  name: Tesla Powerwall
  provider: tesla-energy
  says: ships the Tesla Powerwall SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubTeslaPowerWallInterfacer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id021
      status: none
    slug: victron-energy
    status: profiled
    tags: &id022
    - Company
    - Energy
    - Off-Grid
    - Renewables
    url: /providers/victron-energy/
  layer: domain
  name: Victron Energy (VE.Direct)
  provider: victron-energy
  says: ships the Victron Energy (VE.Direct) SDK or integration code
  source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubVEDirectInterfacer.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/solar-energy-monitoring/openenergymonitor-emonhub/
providers:
- agent_band: agent-aware
  agent_readiness: 26.7
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id001
  name: BMW ConnectedDrive
  slug: bmw-connecteddrive
  status: profiled
  tags: *id002
  url: /providers/bmw-connecteddrive/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id003
  name: Eastron (SDM120 meter)
  slug: eastron
  status: profiled
  tags: *id004
  url: /providers/eastron/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id005
  name: GoodWe
  slug: goodwe
  status: profiled
  tags: *id006
  url: /providers/goodwe/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id007
  name: InfluxDB
  slug: influxdata
  status: profiled
  tags: *id008
  url: /providers/influxdata/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id009
  name: Jaguar Land Rover
  slug: jlr
  status: profiled
  tags: *id010
  url: /providers/jlr/
- agent_band: agent-aware
  agent_readiness: 7.4
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id011
  name: Renogy
  slug: renogy
  status: profiled
  tags: *id012
  url: /providers/renogy/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id013
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id014
  url: /providers/shelly/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id015
  name: SMA Solar Technology
  slug: sma-solar
  status: profiled
  tags: *id016
  url: /providers/sma-solar/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id017
  name: Sunamp
  slug: sunamp
  status: profiled
  tags: *id018
  url: /providers/sunamp/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id019
  name: Tesla Powerwall
  slug: tesla-energy
  status: profiled
  tags: *id020
  url: /providers/tesla-energy/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id021
  name: Victron Energy (VE.Direct)
  slug: victron-energy
  status: profiled
  tags: *id022
  url: /providers/victron-energy/
siblings:
- name: Enphase App (Enlighten)
  rows: 4
  url: /applications/solar-energy-monitoring/enphase-app-enlighten/
- name: mySolarEdge
  rows: 2
  url: /applications/solar-energy-monitoring/mysolaredge/
- name: OpenEMS
  rows: 27
  url: /applications/solar-energy-monitoring/openems/
- name: Predbat
  rows: 31
  url: /applications/solar-energy-monitoring/predbat/
- name: PVOutput
  rows: 22
  url: /applications/solar-energy-monitoring/pvoutput/
- name: Sense
  rows: 6
  url: /applications/solar-energy-monitoring/sense/
sitemap: true
title: 'OpenEnergyMonitor (emonHub): Home Energy & Solar Monitoring reference app'
---
