---
app: TeslaLogger
app_slug: teslalogger
app_url: https://github.com/bassmaster187/TeslaLogger
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20.20
  key: AE-200.20.20
  layer: domain
  name: EV Charging
  providers:
  - supercharge.bingo
  - evcc (self-hosted)
  - go-e
  - KEBA
  - openWB (self-hosted)
  - Tesla
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: API Evangelist extension
  id: AE-200.30
  key: AE-200.30
  layer: domain
  name: Home Energy
  providers:
  - Shelly
  url: /capabilities/home-energy/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.30
  key: AE-120.30
  layer: domain
  name: Routing & Navigation
  providers:
  - A Better Route Planner (Iternio)
  url: /capabilities/routing-navigation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - Scan My Tesla
  - Tesla
  - TeslaFi
  - TeslaMate (self-hosted)
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: API Evangelist extension
  id: AE-120.70
  key: AE-120.70
  layer: common
  name: Elevation & Terrain Data
  providers:
  - Open-Elevation
  url: /capabilities/elevation-terrain-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: common
  name: Reverse Geocoding
  providers:
  - MapQuest
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 6
  observed: 9
credits: []
evidence:
- route: documentation
  url: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
- route: source code
  url: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/MapQuestMapProvider.cs
- route: source code
  url: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/ScanMyTesla.cs
- route: source code
  url: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
- route: source code
  url: https://github.com/bassmaster187/TeslaLogger/tree/master/TeslaFi-Import
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.30
    key: AE-120.30
    name: Routing & Navigation
    url: /capabilities/routing-navigation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.3
    mcp: &id002
      source: https://abetterrouteplanner.com/mcp
      status: verified
    slug: iternio
    status: profiled
    tags: &id003
    - Company
    - Electric Vehicles
    - Routing
    - Transportation
    url: /providers/iternio/
  layer: domain
  name: A Better Route Planner (Iternio)
  provider: iternio
  says: ships the A Better Route Planner (Iternio) SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id010
      status: none
    slug: mapquest
    status: profiled
    tags: &id011
    - Geocoding
    - Mapping
    - Maps
    - Navigation
    url: /providers/mapquest/
  layer: common
  name: MapQuest
  provider: mapquest
  says: ships the MapQuest SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/MapQuestMapProvider.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id012
      status: none
    slug: nominatim
    status: profiled
    tags: &id013
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.70
    key: AE-120.70
    name: Elevation & Terrain Data
    url: /capabilities/elevation-terrain-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id014
      status: unknown
    slug: open-elevation
    status: profiled
    tags: &id015
    - Company
    - Elevation
    - Geospatial
    - Open Source
    url: /providers/open-elevation/
  layer: common
  name: Open-Elevation
  provider: open-elevation
  says: ships the Open-Elevation SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
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
    band: minimal
    in_catalog: true
    kin_score: 8.1
    mcp: &id018
      status: unknown
    slug: scanmytesla
    status: profiled
    tags: &id019
    - Automotive
    - Company
    - Diagnostics
    - Telemetry
    url: /providers/scanmytesla/
  layer: domain
  name: Scan My Tesla
  provider: scanmytesla
  says: ships the Scan My Tesla SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/ScanMyTesla.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id022
      status: unknown
    slug: supercharge-bingo
    status: profiled
    tags: &id023
    - Community
    - Company
    - Electric Vehicles
    - Gaming
    url: /providers/supercharge-bingo/
  layer: domain
  name: supercharge.bingo
  provider: supercharge-bingo
  says: ships the supercharge.bingo SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id024
      status: none
    slug: tesla
    status: profiled
    tags: &id025
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla
  provider: tesla
  says: ships the Tesla SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
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
    agent_band: agent-aware
    agent_readiness: 14.4
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id026
      source: https://teslafi.com
      status: documented
    slug: teslafi
    status: profiled
    tags: &id027
    - Company
    - Data-Logger
    - Tesla
    - Vehicle-Analytics
    url: /providers/teslafi/
  layer: domain
  name: TeslaFi
  provider: teslafi
  says: ships the TeslaFi SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/tree/master/TeslaFi-Import
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
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id028
      status: none
    slug: teslamate
    status: profiled
    tags: &id029
    - Company
    - Data-Logger
    - Open Source
    - Tesla
    url: /providers/teslamate/
  layer: domain
  name: TeslaMate (self-hosted)
  provider: teslamate
  says: ships the TeslaMate (self-hosted) SDK or integration code
  source: https://github.com/bassmaster187/TeslaLogger/tree/master/Teslamate-Import
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.2
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id004
      source: https://docs.evcc.io/en/integrations/mcp.md
      status: verified
    slug: evcc
    status: profiled
    tags: &id005
    - Company
    - Electric Vehicles
    - Open Source
    - Smart Charging
    url: /providers/evcc/
  layer: domain
  name: evcc (self-hosted)
  provider: evcc
  says: lists evcc (self-hosted) as an integration
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.4
    mcp: &id006
      status: unknown
    slug: go-e
    status: profiled
    tags: &id007
    - Company
    - EV Charging
    - Hardware
    - Sustainability
    url: /providers/go-e/
  layer: domain
  name: go-e
  provider: go-e
  says: lists go-e as an integration
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.4
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id008
      status: unknown
    slug: keba
    status: profiled
    tags: &id009
    - Automation
    - Company
    - Energy
    - Industrial
    url: /providers/keba/
  layer: domain
  name: KEBA
  provider: keba
  says: lists KEBA as an integration
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id016
      status: unknown
    slug: openwb
    status: profiled
    tags: &id017
    - Company
    - EV Charging
    - Energy
    - Smart Home
    url: /providers/openwb/
  layer: domain
  name: openWB (self-hosted)
  provider: openwb
  says: lists openWB (self-hosted) as an integration
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: AE-200.30
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.5
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id020
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id021
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: lists Shelly as an integration
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts: *id001
  layer: domain
  name: Tesla
  provider: tesla
  says: lists Tesla as an integration
  source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/teslalogger/
providers:
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id002
  name: A Better Route Planner (Iternio)
  slug: iternio
  status: profiled
  tags: *id003
  url: /providers/iternio/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id004
  name: evcc (self-hosted)
  slug: evcc
  status: profiled
  tags: *id005
  url: /providers/evcc/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.4
  mcp: *id006
  name: go-e
  slug: go-e
  status: profiled
  tags: *id007
  url: /providers/go-e/
- agent_band: agent-aware
  agent_readiness: 10.4
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id008
  name: KEBA
  slug: keba
  status: profiled
  tags: *id009
  url: /providers/keba/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id010
  name: MapQuest
  slug: mapquest
  status: profiled
  tags: *id011
  url: /providers/mapquest/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id012
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id013
  url: /providers/nominatim/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id014
  name: Open-Elevation
  slug: open-elevation
  status: profiled
  tags: *id015
  url: /providers/open-elevation/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id016
  name: openWB (self-hosted)
  slug: openwb
  status: profiled
  tags: *id017
  url: /providers/openwb/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id018
  name: Scan My Tesla
  slug: scanmytesla
  status: profiled
  tags: *id019
  url: /providers/scanmytesla/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id020
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id021
  url: /providers/shelly/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id022
  name: supercharge.bingo
  slug: supercharge-bingo
  status: profiled
  tags: *id023
  url: /providers/supercharge-bingo/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id024
  name: Tesla
  slug: tesla
  status: profiled
  tags: *id025
  url: /providers/tesla/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id026
  name: TeslaFi
  slug: teslafi
  status: profiled
  tags: *id027
  url: /providers/teslafi/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id028
  name: TeslaMate (self-hosted)
  slug: teslamate
  status: profiled
  tags: *id029
  url: /providers/teslamate/
siblings:
- name: ChargePoint
  rows: 6
  url: /applications/connected-car-ev-charging/chargepoint/
- name: Electrify America
  rows: 9
  url: /applications/connected-car-ev-charging/electrify-america/
- name: evcc
  rows: 71
  url: /applications/connected-car-ev-charging/evcc/
- name: Open Charge Map
  rows: 13
  url: /applications/connected-car-ev-charging/open-charge-map/
- name: openWB
  rows: 30
  url: /applications/connected-car-ev-charging/openwb/
- name: TeslaMate
  rows: 3
  url: /applications/connected-car-ev-charging/teslamate/
sitemap: true
title: 'TeslaLogger: Connected Car & EV Charging reference app'
---
