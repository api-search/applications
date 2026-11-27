---
app: OneBusAway Android
app_slug: onebusaway-android
app_url: https://github.com/OneBusAway/onebusaway-android
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.30.40
  key: AE-210.30.40
  layer: domain
  name: Public Transit Data
  providers:
  - MobilityData
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps Platform
  - MapLibre
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Pelias
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Plausible
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: public-transit
  name: Public Transit
  url: /applications/public-transit/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
- route: dependency manifest
  url: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id003
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
  tier: observed
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
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id004
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id005
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id006
      status: unchecked
    slug: maplibre
    status: profiled
    tags: &id007
    - Company
    - Geospatial
    - Mapping
    - Open Source
    url: /providers/maplibre/
  layer: common
  name: MapLibre
  provider: maplibre
  says: ships the MapLibre SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.2
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id008
      status: unchecked
    slug: mobilitydata
    status: profiled
    tags: &id009
    - Data Standards
    - Mobility
    - Non-Profit
    - Open Source
    url: /providers/mobilitydata/
  layer: domain
  name: MobilityData
  provider: mobilitydata
  says: ships the MobilityData SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
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
    agent_band: agent-ready
    agent_readiness: 33.3
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id010
      status: none
    slug: pelias
    status: profiled
    tags: &id011
    - Geocoding
    - Geospatial
    - Open Source
    - Reverse Geocoding
    url: /providers/pelias/
  layer: common
  name: Pelias
  provider: pelias
  says: ships the Pelias SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.6
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id012
      status: none
    slug: plausible
    status: profiled
    tags: &id013
    - Analytics
    - Cookie-Free
    - Event Tracking
    - GDPR
    url: /providers/plausible/
  layer: common
  name: Plausible
  provider: plausible
  says: ships the Plausible SDK or integration code
  source: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/public-transit/onebusaway-android/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id002
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id003
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id004
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id005
  url: /providers/google-maps/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id006
  name: MapLibre
  slug: maplibre
  status: profiled
  tags: *id007
  url: /providers/maplibre/
- agent_band: agent-ready
  agent_readiness: 36.2
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id008
  name: MobilityData
  slug: mobilitydata
  status: profiled
  tags: *id009
  url: /providers/mobilitydata/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id010
  name: Pelias
  slug: pelias
  status: profiled
  tags: *id011
  url: /providers/pelias/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id012
  name: Plausible
  slug: plausible
  status: profiled
  tags: *id013
  url: /providers/plausible/
siblings:
- name: Citymapper
  rows: 23
  url: /applications/public-transit/citymapper/
- name: Moovit
  rows: 17
  url: /applications/public-transit/moovit/
- name: MOTIS (Transitous)
  rows: 7
  url: /applications/public-transit/motis-transitous/
- name: OpenTripPlanner
  rows: 9
  url: /applications/public-transit/opentripplanner/
- name: Transit
  rows: 9
  url: /applications/public-transit/transit/
sitemap: true
title: 'OneBusAway Android: Public Transit reference app'
---
