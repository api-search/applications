---
app: komoot
app_slug: komoot
app_url: https://www.komoot.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Garmin
  - Wahoo Fitness
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook Analytics
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login / Share
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 2
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
- route: integrations page
  url: https://www.komoot.com/connect
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id002
      status: none
    slug: facebook
    status: profiled
    tags: &id003
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook Login / Share
  provider: facebook
  says: ships the Facebook Login / Share SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id005
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id006
      status: none
    slug: garmin
    status: profiled
    tags: &id007
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
  layer: domain
  name: Garmin
  provider: garmin
  says: lists Garmin as an integration
  source: https://www.komoot.com/connect
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id008
      status: none
    slug: wahoo
    status: profiled
    tags: &id009
    - Bike Computers
    - Cycling
    - Endurance Training
    - Fitness
    url: /providers/wahoo/
  layer: domain
  name: Wahoo Fitness
  provider: wahoo
  says: lists Wahoo Fitness as an integration
  source: https://www.komoot.com/connect
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/komoot/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id002
  name: Facebook Analytics
  slug: facebook
  status: profiled
  tags: *id003
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id004
  name: Firebase (Crashlytics / Analytics)
  slug: google-firebase
  status: profiled
  tags: *id005
  url: /providers/google-firebase/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id006
  name: Garmin
  slug: garmin
  status: profiled
  tags: *id007
  url: /providers/garmin/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id008
  name: Wahoo Fitness
  slug: wahoo
  status: profiled
  tags: *id009
  url: /providers/wahoo/
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
title: 'komoot: Maps, Navigation & GPS reference app'
---
