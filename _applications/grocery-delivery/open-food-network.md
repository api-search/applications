---
app: Open Food Network
app_slug: open-food-network
app_url: https://github.com/openfoodfoundation/openfoodnetwork
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.100.30
  key: AE-140.100.30
  layer: domain
  name: Food Supply Chain Data Exchange
  providers:
  - Data Food Consortium
  url: /capabilities/quick-local-commerce/
  via_parent: Quick & Local Commerce
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - GNU Taler
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
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
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
- route: source code
  url: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/.env
integrations:
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
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id003
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id004
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.30
    key: AE-140.100.30
    name: Food Supply Chain Data Exchange
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id005
      status: unchecked
    slug: data-food-consortium
    status: profiled
    tags: &id006
    - Company
    - Food
    - Interoperability
    - Open Standard
    url: /providers/data-food-consortium/
  layer: domain
  name: Data Food Consortium
  provider: data-food-consortium
  says: ships the Data Food Consortium SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id007
      status: unknown
    slug: gnu-taler
    status: profiled
    tags: &id008
    - Ecash
    - Finance
    - Open Source
    - Payments
    url: /providers/gnu-taler/
  layer: common
  name: GNU Taler
  provider: gnu-taler
  says: ships the GNU Taler SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id011
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id012
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id013
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id014
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    mcp: &id015
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id016
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/grocery-delivery/open-food-network/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id003
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id004
  url: /providers/bugsnag/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id005
  name: Data Food Consortium
  slug: data-food-consortium
  status: profiled
  tags: *id006
  url: /providers/data-food-consortium/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id007
  name: GNU Taler
  slug: gnu-taler
  status: profiled
  tags: *id008
  url: /providers/gnu-taler/
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
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id011
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id012
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id013
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id014
  url: /providers/paypal/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id015
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id016
  url: /providers/stripe/
siblings:
- name: Ever Demand
  rows: 12
  url: /applications/grocery-delivery/ever-demand/
- name: Grocy
  rows: 1
  url: /applications/grocery-delivery/grocy/
- name: Instacart
  rows: 8
  url: /applications/grocery-delivery/instacart/
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
title: 'Open Food Network: Grocery Delivery reference app'
---
