---
app: Cocorico
app_slug: cocorico
app_url: https://github.com/Cocolabs-SAS/cocorico
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.40.10
  key: AE-120.40.10
  layer: domain
  name: Place Search
  providers:
  - Google Places
  url: /capabilities/places-points-of-interest/
  via_parent: Places & Points of Interest
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - IPInfoDB
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Mangopay
  url: /capabilities/payment-processing-management/
  via_parent: null
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
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: home-services-marketplace
  name: Home Services Marketplaces
  url: /applications/home-services-marketplace/
counts:
  declared: 0
  observed: 7
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
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
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
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id005
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-places
    status: profiled
    tags: &id006
    - Geolocation
    - Google
    - Location
    - Restaurant
    url: /providers/google-places/
  layer: domain
  name: Google Places
  provider: google-places
  says: ships the Google Places SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id007
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id008
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id009
      status: none
    slug: ipinfodb
    status: profiled
    tags: &id010
    - Geocoding
    - Public APIs
    url: /providers/ipinfodb/
  layer: common
  name: IPInfoDB
  provider: ipinfodb
  says: ships the IPInfoDB SDK or integration code
  source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
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
    mcp: &id011
      status: none
    slug: mangopay
    status: profiled
    tags: &id012
    - Digital Wallet
    - KYC
    - Marketplace Payments
    - Payments
    url: /providers/mangopay/
  layer: common
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
    mcp: &id013
      status: unchecked
    slug: microsoft-translator
    status: queued for profiling
    tags: &id014 []
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
permalink: /applications/home-services-marketplace/cocorico/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook
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
  agent_readiness: 40.3
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id005
  name: Google Places
  slug: google-places
  status: profiled
  tags: *id006
  url: /providers/google-places/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id007
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id008
  url: /providers/google-tag-manager/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id009
  name: IPInfoDB
  slug: ipinfodb
  status: profiled
  tags: *id010
  url: /providers/ipinfodb/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: thin
  in_catalog: true
  kin_score: 37.3
  mcp: *id011
  name: Mangopay
  slug: mangopay
  status: profiled
  tags: *id012
  url: /providers/mangopay/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Microsoft Translator
  slug: microsoft-translator
  status: queued for profiling
  tags: *id014
  url: null
siblings:
- name: Angi
  rows: 0
  url: /applications/home-services-marketplace/angi/
- name: Housecall Pro
  rows: 15
  url: /applications/home-services-marketplace/housecall-pro/
- name: Sharetribe Go
  rows: 13
  url: /applications/home-services-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 5
  url: /applications/home-services-marketplace/sharetribe-web-template/
- name: Taskrabbit
  rows: 4
  url: /applications/home-services-marketplace/taskrabbit/
- name: Thumbtack
  rows: 6
  url: /applications/home-services-marketplace/thumbtack/
sitemap: true
title: 'Cocorico: Home Services Marketplaces reference app'
---
