---
app: TeslaMate
app_slug: teslamate
app_url: https://github.com/teslamate-org/teslamate
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - Tesla
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Grafana
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: common
  name: Reverse Geocoding
  providers:
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/teslamate-org/teslamate/main/elixir/mix.exs
- route: source code
  url: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/tesla_api.ex
- route: source code
  url: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/teslamate/locations/geocoder.ex
- route: source code
  url: https://github.com/teslamate-org/teslamate/tree/main/grafana
integrations:
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
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 60.6
    mcp: &id001
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id002
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: common
  name: Grafana
  provider: grafana-com
  says: ships the Grafana SDK or integration code
  source: https://github.com/teslamate-org/teslamate/tree/main/grafana
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
    mcp: &id003
      status: none
    slug: nominatim
    status: profiled
    tags: &id004
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/teslamate/locations/geocoder.ex
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
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id005
      status: none
    slug: tesla
    status: profiled
    tags: &id006
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla
  provider: tesla
  says: ships the Tesla SDK or integration code
  source: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/tesla_api.ex
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/teslamate/
providers:
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 60.6
  mcp: *id001
  name: Grafana
  slug: grafana-com
  status: profiled
  tags: *id002
  url: /providers/grafana-com/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id003
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id004
  url: /providers/nominatim/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id005
  name: Tesla
  slug: tesla
  status: profiled
  tags: *id006
  url: /providers/tesla/
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
- name: TeslaLogger
  rows: 15
  url: /applications/connected-car-ev-charging/teslalogger/
sitemap: true
title: 'TeslaMate: Connected Car & EV Charging reference app'
---
