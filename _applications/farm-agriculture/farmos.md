---
app: farmOS
app_slug: farmos
app_url: https://github.com/farmOS/farmOS
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Mapbox
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
category:
  id: farm-agriculture
  name: Farm & Agriculture Management
  url: /applications/farm-agriculture/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/farmOS/farmOS/3.x/composer.json
- route: source code
  url: https://github.com/farmOS/farmOS/tree/3.x/modules
- route: source code
  url: https://raw.githubusercontent.com/farmOS/farmOS/3.x/modules/core/map/modules/mapbox/farm_map_mapbox.info.yml
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id001
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id002
    - Geospatial
    - Location
    - Mapping
    - Maps
    url: /providers/mapbox/
  layer: common
  name: Mapbox
  provider: mapbox
  says: ships the Mapbox SDK or integration code
  source: https://raw.githubusercontent.com/farmOS/farmOS/3.x/modules/core/map/modules/mapbox/farm_map_mapbox.info.yml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/farm-agriculture/farmos/
providers:
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id001
  name: Mapbox
  slug: mapbox
  status: profiled
  tags: *id002
  url: /providers/mapbox/
siblings:
- name: AgriWebb
  rows: 11
  url: /applications/farm-agriculture/agriwebb/
- name: Agworld
  rows: 17
  url: /applications/farm-agriculture/agworld/
- name: Climate FieldView
  rows: 20
  url: /applications/farm-agriculture/climate-fieldview/
- name: Farmbrite
  rows: 13
  url: /applications/farm-agriculture/farmbrite/
- name: LiteFarm
  rows: 8
  url: /applications/farm-agriculture/litefarm/
- name: Open Food Network
  rows: 7
  url: /applications/farm-agriculture/open-food-network/
sitemap: true
title: 'farmOS: Farm & Agriculture Management reference app'
---
