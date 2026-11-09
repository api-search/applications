---
app: HomeHarvest
app_slug: homeharvest
app_url: https://github.com/Bunsly/HomeHarvest
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4960.30
  key: listing-data-mls-management
  layer: domain
  name: Listing Data & MLS Management
  providers:
  - Realtor.com
  url: /capabilities/listing-data-mls-management/
  via_parent: null
category:
  id: real-estate-home-search
  name: Real Estate & Home Search
  url: /applications/real-estate-home-search/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/pyproject.toml
- route: documentation
  url: https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/README.md
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.8
    mcp: &id001
      status: unknown
    slug: realtor-com
    status: profiled
    tags: &id002
    - Housing
    - MLS
    - Property Listings
    - Real Estate
    url: /providers/realtor-com/
  layer: domain
  name: Realtor.com
  provider: realtor-com
  says: ships the Realtor.com SDK or integration code
  source: https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/README.md
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/real-estate-home-search/homeharvest/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.8
  mcp: *id001
  name: Realtor.com
  slug: realtor-com
  status: profiled
  tags: *id002
  url: /providers/realtor-com/
siblings:
- name: Flathunter
  rows: 16
  url: /applications/real-estate-home-search/flathunter/
- name: Real Geeks
  rows: 10
  url: /applications/real-estate-home-search/real-geeks/
- name: Realtor.com
  rows: 13
  url: /applications/real-estate-home-search/realtor-com/
- name: Redfin
  rows: 13
  url: /applications/real-estate-home-search/redfin/
- name: Rightmove
  rows: 6
  url: /applications/real-estate-home-search/rightmove/
- name: Zillow
  rows: 14
  url: /applications/real-estate-home-search/zillow/
sitemap: true
title: 'HomeHarvest: Real Estate & Home Search reference app'
---
