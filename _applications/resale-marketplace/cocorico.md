---
app: Cocorico
app_slug: cocorico
app_url: https://github.com/Cocolabs-SAS/cocorico
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120
  key: location-mapping
  layer: domain
  name: Location & Mapping
  providers:
  - Google Maps Platform
  url: /capabilities/location-mapping/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Mangopay
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - Microsoft Translator
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: resale-marketplace
  name: Resale & Second-hand Marketplaces
  url: /applications/resale-marketplace/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Cocolabs-SAS/cocorico/blob/master/composer.json
- route: source code
  url: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Login
  provider: facebook
  says: ships the Facebook Login SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
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
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id003
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: location-mapping
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
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
  layer: domain
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: thin
    in_catalog: true
    kin_score: 37.3
    mcp: &id007
      status: none
    slug: mangopay
    status: profiled
    tags: &id008
    - Digital Wallet
    - KYC
    - Marketplace Payments
    - Payments
    url: /providers/mangopay/
  layer: domain
  name: Mangopay
  provider: mangopay
  says: ships the Mangopay SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: microsoft-translator
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: common
  name: Microsoft Translator
  provider: microsoft-translator
  says: ships the Microsoft Translator SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/resale-marketplace/cocorico/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook Login
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id005
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id006
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: thin
  in_catalog: true
  kin_score: 37.3
  mcp: *id007
  name: Mangopay
  slug: mangopay
  status: profiled
  tags: *id008
  url: /providers/mangopay/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Microsoft Translator
  slug: microsoft-translator
  status: queued for profiling
  tags: *id010
  url: null
siblings:
- name: Depop
  rows: 6
  url: /applications/resale-marketplace/depop/
- name: Mercari
  rows: 9
  url: /applications/resale-marketplace/mercari/
- name: Poshmark
  rows: 11
  url: /applications/resale-marketplace/poshmark/
- name: Sharetribe (hosted)
  rows: 11
  url: /applications/resale-marketplace/sharetribe-hosted/
- name: Sharetribe Go
  rows: 11
  url: /applications/resale-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 6
  url: /applications/resale-marketplace/sharetribe-web-template/
- name: Vinted
  rows: 25
  url: /applications/resale-marketplace/vinted/
sitemap: true
title: 'Cocorico: Resale & Second-hand Marketplaces reference app'
---
