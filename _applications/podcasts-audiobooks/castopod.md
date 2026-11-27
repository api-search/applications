---
app: Castopod
app_slug: castopod
app_url: https://github.com/ad-aures/castopod
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind GeoIP2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
category:
  id: podcasts-audiobooks
  name: Podcasts & Audiobooks
  url: /applications/podcasts-audiobooks/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ad-aures/castopod/blob/develop/composer.json
- route: source code
  url: https://github.com/ad-aures/castopod/blob/develop/.env.example
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
  layer: common
  name: MaxMind GeoIP2
  provider: maxmind
  says: ships the MaxMind GeoIP2 SDK or integration code
  source: https://github.com/ad-aures/castopod/blob/develop/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/podcasts-audiobooks/castopod/
providers:
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id001
  name: MaxMind GeoIP2
  slug: maxmind
  status: profiled
  tags: *id002
  url: /providers/maxmind/
siblings:
- name: AntennaPod
  rows: 6
  url: /applications/podcasts-audiobooks/antennapod/
- name: Audible
  rows: 4
  url: /applications/podcasts-audiobooks/audible/
- name: Audiobookshelf
  rows: 8
  url: /applications/podcasts-audiobooks/audiobookshelf/
- name: Pocket Casts
  rows: 5
  url: /applications/podcasts-audiobooks/pocket-casts/
- name: Podverse
  rows: 7
  url: /applications/podcasts-audiobooks/podverse/
sitemap: true
title: 'Castopod: Podcasts & Audiobooks reference app'
---
