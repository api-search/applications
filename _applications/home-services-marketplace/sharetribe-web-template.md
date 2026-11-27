---
app: Sharetribe Web Template
app_slug: sharetribe-web-template
app_url: https://github.com/sharetribe/web-template
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: domain
  name: Base Map Tiles
  providers:
  - Mapbox
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: home-services-marketplace
  name: Home Services Marketplaces
  url: /applications/home-services-marketplace/
counts:
  declared: 0
  observed: 5
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
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/sharetribe/web-template/blob/main/package.json
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
    mcp: &id003
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id004
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
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.2
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id005
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id006
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
    mcp: &id007
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id008
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
    mcp: &id009
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id010
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
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
permalink: /applications/home-services-marketplace/sharetribe-web-template/
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
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id003
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id004
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id005
  name: Mapbox
  slug: mapbox
  status: profiled
  tags: *id006
  url: /providers/mapbox/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id007
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id008
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id009
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id010
  url: /providers/stripe/
siblings:
- name: Angi
  rows: 0
  url: /applications/home-services-marketplace/angi/
- name: Cocorico
  rows: 7
  url: /applications/home-services-marketplace/cocorico/
- name: Housecall Pro
  rows: 15
  url: /applications/home-services-marketplace/housecall-pro/
- name: Sharetribe Go
  rows: 13
  url: /applications/home-services-marketplace/sharetribe-go/
- name: Taskrabbit
  rows: 4
  url: /applications/home-services-marketplace/taskrabbit/
- name: Thumbtack
  rows: 6
  url: /applications/home-services-marketplace/thumbtack/
sitemap: true
title: 'Sharetribe Web Template: Home Services Marketplaces reference app'
---
