---
app: Open Collective
app_slug: open-collective
app_url: https://github.com/opencollective/opencollective-api
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-210.60
  key: bank-relationship-management
  layer: domain
  name: Bank Relationship Management
  providers:
  - GoCardless Bank Account Data (Nordigen)
  - Plaid
  url: /capabilities/bank-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.40
  key: cross-border-payment-management
  layer: domain
  name: Cross-Border Payment Management
  providers:
  - Wise (TransferWise)
  url: /capabilities/cross-border-payment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-3740.30
  key: BC-3740.30
  layer: common
  name: Content Delivery Network Operations
  providers:
  - Cloudflare
  url: /capabilities/content-delivery-network-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10
  key: AE-160.10
  layer: common
  name: Customer Sign-In
  providers:
  - GitHub
  url: /capabilities/customer-sign-in/
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
  id: donations-crowdfunding
  name: Donations & Crowdfunding
  url: /applications/donations-crowdfunding/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/opencollective/opencollective-api/blob/main/package.json
- route: source code
  url: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: BC-3740.30
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.6
    band: exemplar
    in_catalog: true
    kin_score: 82.8
    mcp: &id003
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id004
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: ships the Cloudflare SDK or integration code
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id007
      source: https://github.com/gocardless/gc-mcp
      status: verified
    slug: nordigen
    status: profiled
    tags: &id008
    - Finance
    - Public APIs
    url: /providers/nordigen/
  layer: domain
  name: GoCardless Bank Account Data (Nordigen)
  provider: nordigen
  says: ships the GoCardless Bank Account Data (Nordigen) SDK or integration code
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
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
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id009
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id010
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id011
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id012
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 52.1
    band: exemplar
    in_catalog: true
    kin_score: 83.4
    mcp: &id013
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id014
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: ships the Plaid SDK or integration code
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
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
    kin_score: 80.6
    mcp: &id015
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id016
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/opencollective/opencollective-api/blob/main/package.json
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id017
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id018
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.40
    key: cross-border-payment-management
    name: Cross-Border Payment Management
    url: /capabilities/cross-border-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.2
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id019
      status: none
    slug: wise
    status: profiled
    tags: &id020
    - Banking
    - Cross-Border
    - Foreign Exchange
    - Payments
    url: /providers/wise/
  layer: domain
  name: Wise (TransferWise)
  provider: wise
  says: ships the Wise (TransferWise) SDK or integration code
  source: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/donations-crowdfunding/open-collective/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-native
  agent_readiness: 69.6
  band: exemplar
  in_catalog: true
  kin_score: 82.8
  mcp: *id003
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id004
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id005
  name: GitHub
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id007
  name: GoCardless Bank Account Data (Nordigen)
  slug: nordigen
  status: profiled
  tags: *id008
  url: /providers/nordigen/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id009
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id010
  url: /providers/hcaptcha/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id011
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id012
  url: /providers/paypal/
- agent_band: agent-native
  agent_readiness: 52.1
  band: exemplar
  in_catalog: true
  kin_score: 83.4
  mcp: *id013
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id014
  url: /providers/plaid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id015
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id016
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id017
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id018
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 41.2
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id019
  name: Wise (TransferWise)
  slug: wise
  status: profiled
  tags: *id020
  url: /providers/wise/
siblings:
- name: Givebutter
  rows: 50
  url: /applications/donations-crowdfunding/givebutter/
- name: GiveWP
  rows: 3
  url: /applications/donations-crowdfunding/givewp/
- name: GoFundMe Pro (Classy)
  rows: 47
  url: /applications/donations-crowdfunding/gofundme-pro-classy/
- name: HCB (Hack Club Bank)
  rows: 13
  url: /applications/donations-crowdfunding/hcb-hack-club-bank/
- name: Liberapay
  rows: 4
  url: /applications/donations-crowdfunding/liberapay/
- name: Patreon
  rows: 23
  url: /applications/donations-crowdfunding/patreon/
sitemap: true
title: 'Open Collective: Donations & Crowdfunding reference app'
---
