---
app: Headway
app_slug: headway
app_url: https://github.com/headwaymaps/headway
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: domain
  name: Base Map Tiles
  providers:
  - OpenStreetMap
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - Pelias
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.30.30
  key: AE-120.30.30
  layer: domain
  name: Transit Routing
  providers:
  - OpenTripPlanner
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
- attribution: API Evangelist extension
  id: AE-120.30.10
  key: AE-120.30.10
  layer: domain
  name: Turn-by-Turn Directions
  providers:
  - Valhalla
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: documentation
  url: https://github.com/headwaymaps/headway/blob/main/README.md
- route: source code
  url: https://github.com/headwaymaps/headway/tree/main/services
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
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id001
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id002
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: domain
  name: OpenStreetMap
  provider: openstreetmap
  says: ships the OpenStreetMap SDK or integration code
  source: https://github.com/headwaymaps/headway/tree/main/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.30
    key: AE-120.30.30
    name: Transit Routing
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id003
      status: none
    slug: opentripplanner
    status: profiled
    tags: &id004
    - Multi-Modal
    - Open Source
    - Routing
    - Transportation
    url: /providers/opentripplanner/
  layer: domain
  name: OpenTripPlanner
  provider: opentripplanner
  says: ships the OpenTripPlanner SDK or integration code
  source: https://github.com/headwaymaps/headway/tree/main/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.6
    band: emerging
    in_catalog: true
    kin_score: 23.8
    mcp: &id005
      status: none
    slug: pelias
    status: profiled
    tags: &id006
    - Geocoding
    - Geospatial
    - Open Source
    - Reverse Geocoding
    url: /providers/pelias/
  layer: domain
  name: Pelias
  provider: pelias
  says: ships the Pelias SDK or integration code
  source: https://github.com/headwaymaps/headway/tree/main/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: emerging
    in_catalog: true
    kin_score: 25.7
    mcp: &id007
      status: none
    slug: valhalla
    status: profiled
    tags: &id008
    - Mapping
    - Navigation
    - OpenStreetMap
    - Routing
    url: /providers/valhalla/
  layer: domain
  name: Valhalla
  provider: valhalla
  says: ships the Valhalla SDK or integration code
  source: https://github.com/headwaymaps/headway/tree/main/services
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/headway/
providers:
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id001
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id002
  url: /providers/openstreetmap/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id003
  name: OpenTripPlanner
  slug: opentripplanner
  status: profiled
  tags: *id004
  url: /providers/opentripplanner/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: emerging
  in_catalog: true
  kin_score: 23.8
  mcp: *id005
  name: Pelias
  slug: pelias
  status: profiled
  tags: *id006
  url: /providers/pelias/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: emerging
  in_catalog: true
  kin_score: 25.7
  mcp: *id007
  name: Valhalla
  slug: valhalla
  status: profiled
  tags: *id008
  url: /providers/valhalla/
siblings:
- name: Dawarich
  rows: 14
  url: /applications/maps-navigation/dawarich/
- name: Google Maps
  rows: 1
  url: /applications/maps-navigation/google-maps/
- name: komoot
  rows: 5
  url: /applications/maps-navigation/komoot/
- name: Organic Maps
  rows: 5
  url: /applications/maps-navigation/organic-maps/
- name: OsmAnd
  rows: 4
  url: /applications/maps-navigation/osmand/
- name: Traccar
  rows: 31
  url: /applications/maps-navigation/traccar/
- name: Waze
  rows: 1
  url: /applications/maps-navigation/waze/
sitemap: true
title: 'Headway: Maps, Navigation & GPS reference app'
---
