---
app: Kutt
app_slug: kutt
app_url: https://github.com/thedevs-network/kutt
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - MaxMind GeoLite (via geoip-lite)
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/thedevs-network/kutt/blob/main/package.json
- route: source code
  url: https://github.com/thedevs-network/kutt/blob/main/.example.env
integrations:
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
    mcp: &id001
      status: none
    slug: maxmind
    status: profiled
    tags: &id002
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
  name: MaxMind GeoLite (via geoip-lite)
  provider: maxmind
  says: ships the MaxMind GeoLite (via geoip-lite) SDK or integration code
  source: https://github.com/thedevs-network/kutt/blob/main/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/kutt/
providers:
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id001
  name: MaxMind GeoLite (via geoip-lite)
  slug: maxmind
  status: profiled
  tags: *id002
  url: /providers/maxmind/
siblings:
- name: Bitly
  rows: 55
  url: /applications/url-shortener-links/bitly/
- name: Dub
  rows: 25
  url: /applications/url-shortener-links/dub/
- name: Shlink
  rows: 6
  url: /applications/url-shortener-links/shlink/
- name: Short.io
  rows: 8
  url: /applications/url-shortener-links/short-io/
- name: Sink
  rows: 5
  url: /applications/url-shortener-links/sink/
- name: YOURLS
  rows: 2
  url: /applications/url-shortener-links/yourls/
sitemap: true
title: 'Kutt: Link Management & URL Shorteners reference app'
---
