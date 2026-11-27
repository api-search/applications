---
app: Sharetribe Go
app_slug: sharetribe-go
app_url: https://github.com/sharetribe/sharetribe
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
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
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Airbrake
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Flying Sphinx
  - Sphinx Search
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
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
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  url: /capabilities/email/
  via_parent: Email
category:
  id: home-services-marketplace
  name: Home Services Marketplaces
  url: /applications/home-services-marketplace/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 25.8
    mcp: &id001
      status: none
    slug: airbrake
    status: profiled
    tags: &id002
    - Application Performance Monitoring
    - DevOps
    - Error Monitoring
    - Observability
    url: /providers/airbrake/
  layer: common
  name: Airbrake
  provider: airbrake
  says: ships the Airbrake SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id005
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id009
      status: unchecked
    slug: flying-sphinx
    status: profiled
    tags: &id010
    - Addon
    - Heroku
    - Search
    - Sphinx
    url: /providers/flying-sphinx/
  layer: common
  name: Flying Sphinx
  provider: flying-sphinx
  says: ships the Flying Sphinx SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id011
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id012
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    mcp: &id013
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id014
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    mcp: &id015
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: ships the Intercom SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    mcp: &id017
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id018
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    mcp: &id019
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id020
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id021
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id022
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.7
    mcp: &id023
      status: unchecked
    slug: sphinx-search
    status: profiled
    tags: &id024
    - Enterprise
    - Full-Text Search
    - Open Source
    - Search
    url: /providers/sphinx-search/
  layer: common
  name: Sphinx Search
  provider: sphinx-search
  says: ships the Sphinx Search SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    mcp: &id025
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id026
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/home-services-marketplace/sharetribe-go/
providers:
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 25.8
  mcp: *id001
  name: Airbrake
  slug: airbrake
  status: profiled
  tags: *id002
  url: /providers/airbrake/
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
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id005
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id006
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id009
  name: Flying Sphinx
  slug: flying-sphinx
  status: profiled
  tags: *id010
  url: /providers/flying-sphinx/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id011
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id012
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id013
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id014
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id015
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id016
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id017
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id018
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id019
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id020
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id021
  name: Redis
  slug: redis
  status: profiled
  tags: *id022
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id023
  name: Sphinx Search
  slug: sphinx-search
  status: profiled
  tags: *id024
  url: /providers/sphinx-search/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id025
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id026
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
title: 'Sharetribe Go: Home Services Marketplaces reference app'
---
