---
app: Ever Demand
app_slug: ever-demand
app_url: https://github.com/ever-co/ever-demand
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120
  key: location-mapping
  layer: domain
  name: Location & Mapping
  providers:
  - Google Maps
  url: /capabilities/location-mapping/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - Unleash
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - ipstack
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Amazon CloudWatch
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
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - Mixpanel
  url: /capabilities/product-usage-analytics/
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
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: grocery-delivery
  name: Grocery Delivery
  url: /applications/grocery-delivery/
counts:
  declared: 0
  observed: 12
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
- route: dependency manifest
  url: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 43.4
    band: exemplar
    in_catalog: true
    kin_score: 77.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id002
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: common
  name: Amazon CloudWatch
  provider: amazon-cloudwatch
  says: ships the Amazon CloudWatch SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    mcp: &id007
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id008
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    mcp: &id009
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id010
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: domain
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id013
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: ships the Intercom SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    agent_band: agent-ready
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id015
      status: none
    slug: ipstack
    status: profiled
    tags: &id016
    - Geocoding
    - IP Geolocation
    - Location
    - Threat Intelligence
    url: /providers/ipstack/
  layer: common
  name: ipstack
  provider: ipstack
  says: ships the ipstack SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id017
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id018
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    mcp: &id019
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id020
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    mcp: &id021
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id022
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.4
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id023
      source: https://github.com/Unleash/unleash-mcp
      status: verified
    slug: unleash
    status: profiled
    tags: &id024
    - A/B Testing
    - Feature Flags
    - Feature Management
    - Progressive Delivery
    url: /providers/unleash/
  layer: common
  name: Unleash
  provider: unleash
  says: ships the Unleash SDK or integration code
  source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/grocery-delivery/ever-demand/
providers:
- agent_band: agent-native
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id001
  name: Amazon CloudWatch
  slug: amazon-cloudwatch
  status: profiled
  tags: *id002
  url: /providers/amazon-cloudwatch/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id007
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id008
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id009
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id010
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id013
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id014
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id015
  name: ipstack
  slug: ipstack
  status: profiled
  tags: *id016
  url: /providers/ipstack/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id017
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id018
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id019
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id020
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id021
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id022
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id023
  name: Unleash
  slug: unleash
  status: profiled
  tags: *id024
  url: /providers/unleash/
siblings:
- name: Grocy
  rows: 1
  url: /applications/grocery-delivery/grocy/
- name: Instacart
  rows: 8
  url: /applications/grocery-delivery/instacart/
- name: Open Food Network
  rows: 8
  url: /applications/grocery-delivery/open-food-network/
- name: Picnic
  rows: 4
  url: /applications/grocery-delivery/picnic/
- name: Shipt
  rows: 5
  url: /applications/grocery-delivery/shipt/
- name: Weee!
  rows: 7
  url: /applications/grocery-delivery/weee/
sitemap: true
title: 'Ever Demand: Grocery Delivery reference app'
---
