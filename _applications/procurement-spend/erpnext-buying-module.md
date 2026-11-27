---
app: ERPNext (Buying module)
app_slug: erpnext-buying-module
app_url: https://github.com/frappe/erpnext
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.50
  key: AE-190.50
  layer: domain
  name: Consumer Data Access
  providers:
  - Plaid
  url: /capabilities/consumer-data-access/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - exchangerate.host
  - Frankfurter
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: common
  name: Video Platforms
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
category:
  id: procurement-spend
  name: Procurement & Spend Management
  url: /applications/procurement-spend/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
- route: source code
  url: https://raw.githubusercontent.com/frappe/erpnext/develop/erpnext/accounts/doctype/currency_exchange_settings/currency_exchange_settings.json
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.0
    mcp: &id001
      status: none
    slug: exchangerate-host
    status: profiled
    tags: &id002
    - Exchange Rates
    - Foreign Exchange
    - Public APIs
    url: /providers/exchangerate-host/
  layer: domain
  name: exchangerate.host
  provider: exchangerate-host
  says: ships the exchangerate.host SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/erpnext/accounts/doctype/currency_exchange_settings/currency_exchange_settings.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 46.7
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id003
      source: https://github.com/lineofflight/frankfurter-mcp
      status: verified
    slug: frankfurter
    status: profiled
    tags: &id004
    - Foreign Exchange
    - MIT
    - Open Source
    - Self-Hosted
    url: /providers/frankfurter/
  layer: domain
  name: Frankfurter
  provider: frankfurter
  says: ships the Frankfurter SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/erpnext/accounts/doctype/currency_exchange_settings/currency_exchange_settings.json
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
    mcp: &id005
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id006
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.1
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id007
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id008
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: ships the Plaid SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id009
      status: none
    slug: youtube
    status: profiled
    tags: &id010
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: common
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/procurement-spend/erpnext-buying-module/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id001
  name: exchangerate.host
  slug: exchangerate-host
  status: profiled
  tags: *id002
  url: /providers/exchangerate-host/
- agent_band: agent-native
  agent_readiness: 46.7
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id003
  name: Frankfurter
  slug: frankfurter
  status: profiled
  tags: *id004
  url: /providers/frankfurter/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id005
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id006
  url: /providers/google-maps/
- agent_band: agent-native
  agent_readiness: 51.1
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id007
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id008
  url: /providers/plaid/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id009
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id010
  url: /providers/youtube/
siblings:
- name: Odoo Purchase
  rows: 1
  url: /applications/procurement-spend/odoo-purchase/
- name: Precoro
  rows: 10
  url: /applications/procurement-spend/precoro/
- name: Procurify
  rows: 10
  url: /applications/procurement-spend/procurify/
- name: Spendflo
  rows: 46
  url: /applications/procurement-spend/spendflo/
- name: Tradogram
  rows: 32
  url: /applications/procurement-spend/tradogram/
- name: Vendr
  rows: 20
  url: /applications/procurement-spend/vendr/
sitemap: true
title: 'ERPNext (Buying module): Procurement & Spend Management reference app'
---
