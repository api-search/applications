---
app: NewsBlur
app_slug: newsblur
app_url: https://github.com/samuelclay/NewsBlur
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
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
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Apple (APNs)
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  - Sign in with Apple
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
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 0
  observed: 11
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.newsblur/latest/
- route: dependency manifest
  url: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    mcp: &id002
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id003
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id004
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id005
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: common
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id006
      status: none
    slug: apple
    status: profiled
    tags: &id007
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple (APNs)
  provider: apple
  says: ships the Apple (APNs) SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id008
      status: none
    slug: google-gemini
    status: profiled
    tags: &id009
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: common
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    mcp: &id010
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id011
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id012
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id013
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    mcp: &id014
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id015
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    mcp: &id016
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id017
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: *id001
  layer: common
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    mcp: &id018
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id019
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id020
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id021
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/newsblur/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id002
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id003
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id004
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id005
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id006
  name: Apple (APNs)
  slug: apple
  status: profiled
  tags: *id007
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id008
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id009
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id010
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id011
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id012
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id013
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id014
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id015
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id016
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id017
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id018
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id019
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id020
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id021
  url: /providers/x/
siblings:
- name: Feedly
  rows: 8
  url: /applications/news-feed-reader/feedly/
- name: FreshRSS
  rows: 21
  url: /applications/news-feed-reader/freshrss/
- name: Karakeep
  rows: 4
  url: /applications/news-feed-reader/karakeep/
- name: Linkwarden
  rows: 55
  url: /applications/news-feed-reader/linkwarden/
- name: Miniflux
  rows: 28
  url: /applications/news-feed-reader/miniflux/
- name: Readwise Reader
  rows: 10
  url: /applications/news-feed-reader/readwise-reader/
- name: Wallabag
  rows: 8
  url: /applications/news-feed-reader/wallabag/
sitemap: true
title: 'NewsBlur: News, Feeds & Read-Later reference app'
---
