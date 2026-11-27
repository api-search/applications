---
app: YOURLS
app_slug: yourls
app_url: https://github.com/YOURLS/YOURLS
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Google Charts
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - MaxMind GeoLite2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/YOURLS/YOURLS/blob/master/composer.json
- route: source code
  url: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-geo.php
- route: source code
  url: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-infos.php
integrations:
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: google-charts
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Google Charts
  provider: google-charts
  says: ships the Google Charts SDK or integration code
  source: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-infos.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id003
      status: none
    slug: maxmind
    status: profiled
    tags: &id004
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
  name: MaxMind GeoLite2
  provider: maxmind
  says: ships the MaxMind GeoLite2 SDK or integration code
  source: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-geo.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/yourls/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Google Charts
  slug: google-charts
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id003
  name: MaxMind GeoLite2
  slug: maxmind
  status: profiled
  tags: *id004
  url: /providers/maxmind/
siblings:
- name: Bitly
  rows: 55
  url: /applications/url-shortener-links/bitly/
- name: Dub
  rows: 25
  url: /applications/url-shortener-links/dub/
- name: Kutt
  rows: 1
  url: /applications/url-shortener-links/kutt/
- name: Shlink
  rows: 6
  url: /applications/url-shortener-links/shlink/
- name: Short.io
  rows: 8
  url: /applications/url-shortener-links/short-io/
- name: Sink
  rows: 5
  url: /applications/url-shortener-links/sink/
sitemap: true
title: 'YOURLS: Link Management & URL Shorteners reference app'
---
