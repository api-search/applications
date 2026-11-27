---
app: Sharetribe Web Template
app_slug: sharetribe-web-template
app_url: https://github.com/sharetribe/web-template
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120
  key: location-mapping
  layer: domain
  name: Location & Mapping
  providers:
  - Google Maps Platform
  - Mapbox
  url: /capabilities/location-mapping/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: resale-marketplace
  name: Resale & Second-hand Marketplaces
  url: /applications/resale-marketplace/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/sharetribe/web-template/blob/main/package.json
- route: source code
  url: https://github.com/sharetribe/web-template/blob/main/.env-template
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
  source: https://github.com/sharetribe/web-template/blob/main/package.json
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
    mcp: &id003
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id004
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: domain
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/sharetribe/web-template/blob/main/.env-template
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id005
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id006
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/sharetribe/web-template/blob/main/package.json
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
    agent_readiness: 45.2
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id007
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id008
    - Geospatial
    - Location
    - Mapping
    - Maps
    url: /providers/mapbox/
  layer: domain
  name: Mapbox
  provider: mapbox
  says: ships the Mapbox SDK or integration code
  source: https://github.com/sharetribe/web-template/blob/main/.env-template
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id009
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id010
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/sharetribe/web-template/blob/main/package.json
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
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id011
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id012
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/sharetribe/web-template/blob/main/.env-template
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/resale-marketplace/sharetribe-web-template/
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
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id003
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id004
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id005
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id006
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id007
  name: Mapbox
  slug: mapbox
  status: profiled
  tags: *id008
  url: /providers/mapbox/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id009
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id010
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id011
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id012
  url: /providers/stripe/
siblings:
- name: Cocorico
  rows: 5
  url: /applications/resale-marketplace/cocorico/
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
- name: Vinted
  rows: 25
  url: /applications/resale-marketplace/vinted/
sitemap: true
title: 'Sharetribe Web Template: Resale & Second-hand Marketplaces reference app'
---
