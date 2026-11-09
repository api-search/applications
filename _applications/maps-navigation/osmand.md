---
app: OsmAnd
app_slug: osmand
app_url: https://github.com/osmandapp/OsmAnd
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.80
  key: AE-120.80
  layer: domain
  name: Map Data Contribution & Editing
  providers:
  - OpenStreetMap
  url: /capabilities/map-data-contribution-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.40
  key: AE-120.20.40
  layer: domain
  name: Street-Level Imagery
  providers:
  - Mapillary
  - Panoramax
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Google Play Billing
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/net.osmand/latest/
- route: dependency manifest
  url: https://github.com/osmandapp/OsmAnd/blob/master/OsmAnd/build-common.gradle
- route: source code
  url: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id001
      status: none
    slug: google-play
    status: profiled
    tags: &id002
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play Billing
  provider: google-play
  says: ships the Google Play Billing SDK or integration code
  source: https://github.com/osmandapp/OsmAnd/blob/master/OsmAnd/build-common.gradle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.40
    key: AE-120.20.40
    name: Street-Level Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: mapillary
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Mapillary
  provider: mapillary
  says: ships the Mapillary SDK or integration code
  source: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.80
    key: AE-120.80
    name: Map Data Contribution & Editing
    url: /capabilities/map-data-contribution-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id005
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id006
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: domain
  name: OpenStreetMap
  provider: openstreetmap
  says: ships the OpenStreetMap SDK or integration code
  source: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.40
    key: AE-120.20.40
    name: Street-Level Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id007
      status: none
    slug: panoramax
    status: profiled
    tags: &id008
    - Company
    - Mapping
    - Open Data
    - Photography
    url: /providers/panoramax/
  layer: domain
  name: Panoramax
  provider: panoramax
  says: ships the Panoramax SDK or integration code
  source: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/osmand/
providers:
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id001
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id002
  url: /providers/google-play/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Mapillary
  slug: mapillary
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id005
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id006
  url: /providers/openstreetmap/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id007
  name: Panoramax
  slug: panoramax
  status: profiled
  tags: *id008
  url: /providers/panoramax/
siblings:
- name: Dawarich
  rows: 14
  url: /applications/maps-navigation/dawarich/
- name: Google Maps
  rows: 1
  url: /applications/maps-navigation/google-maps/
- name: Headway
  rows: 4
  url: /applications/maps-navigation/headway/
- name: komoot
  rows: 5
  url: /applications/maps-navigation/komoot/
- name: Organic Maps
  rows: 5
  url: /applications/maps-navigation/organic-maps/
- name: Traccar
  rows: 31
  url: /applications/maps-navigation/traccar/
- name: Waze
  rows: 1
  url: /applications/maps-navigation/waze/
sitemap: true
title: 'OsmAnd: Maps, Navigation & GPS reference app'
---
