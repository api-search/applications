---
app: Google Maps
app_slug: google-maps
app_url: https://maps.google.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.maps/latest/
integrations:
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
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id002
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.maps/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/google-maps/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
siblings:
- name: Dawarich
  rows: 14
  url: /applications/maps-navigation/dawarich/
- name: Headway
  rows: 4
  url: /applications/maps-navigation/headway/
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
title: 'Google Maps: Maps, Navigation & GPS reference app'
---
