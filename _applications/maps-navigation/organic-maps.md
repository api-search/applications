---
app: Organic Maps
app_slug: organic-maps
app_url: https://github.com/organicmaps/organicmaps
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.20.10
  key: AE-210.20.10
  layer: domain
  name: Hotel Booking
  providers:
  - Kayak
  url: /capabilities/lodging-stays/
  via_parent: Lodging & Stays
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
  id: AE-120.40.20
  key: AE-120.40.20
  layer: domain
  name: Place Content & Descriptions
  providers:
  - Wikipedia
  url: /capabilities/places-points-of-interest/
  via_parent: Places & Points of Interest
- attribution: API Evangelist extension
  id: AE-120.50.20
  key: AE-120.50.20
  layer: common
  name: Device Positioning
  providers:
  - Google Play services location
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 0
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/app.organicmaps/latest/
- route: dependency manifest
  url: https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
- route: documentation
  url: https://github.com/organicmaps/organicmaps/blob/master/docs/CREDENTIALS.md
- route: source code
  url: https://github.com/organicmaps/organicmaps/blob/master/android/app/src/main/res/layout/place_page_wikipedia_fragment.xml
- route: source code
  url: https://github.com/organicmaps/organicmaps/blob/master/private.h
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id002
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id004
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google Play services location
  provider: google
  says: ships the Google Play services location SDK or integration code
  source: https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.20.10
    key: AE-210.20.10
    name: Hotel Booking
    url: /capabilities/lodging-stays/
    via_parent: Lodging & Stays
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id005
      status: none
    slug: kayak
    status: profiled
    tags: &id006
    - Company
    - Flights
    - Metasearch
    - Travel
    url: /providers/kayak/
  layer: domain
  name: Kayak
  provider: kayak
  says: ships the Kayak SDK or integration code
  source: https://github.com/organicmaps/organicmaps/blob/master/private.h
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
    mcp: &id007
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id008
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: domain
  name: OpenStreetMap
  provider: openstreetmap
  says: ships the OpenStreetMap SDK or integration code
  source: https://github.com/organicmaps/organicmaps/blob/master/private.h
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.20
    key: AE-120.40.20
    name: Place Content & Descriptions
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id009
      status: none
    slug: wikipedia
    status: profiled
    tags: &id010
    - Encyclopedia
    - Open Data
    - Open Knowledge
    - Public APIs
    url: /providers/wikipedia/
  layer: domain
  name: Wikipedia
  provider: wikipedia
  says: ships the Wikipedia SDK or integration code
  source: https://github.com/organicmaps/organicmaps/blob/master/android/app/src/main/res/layout/place_page_wikipedia_fragment.xml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/organic-maps/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id001
  name: Firebase Crashlytics
  slug: firebase
  status: profiled
  tags: *id002
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id003
  name: Google Play services location
  slug: google
  status: profiled
  tags: *id004
  url: /providers/google/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id005
  name: Kayak
  slug: kayak
  status: profiled
  tags: *id006
  url: /providers/kayak/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id007
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id008
  url: /providers/openstreetmap/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id009
  name: Wikipedia
  slug: wikipedia
  status: profiled
  tags: *id010
  url: /providers/wikipedia/
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
title: 'Organic Maps: Maps, Navigation & GPS reference app'
---
