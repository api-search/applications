---
app: AFFiNE
app_slug: affine
app_url: https://github.com/toeverything/AFFiNE
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - RevenueCat
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google Cloud Logging
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
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Cloudflare (Workers AI)
  - Google Gemini
  - Google Vertex AI
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.20.10
  key: AE-110.20.10
  layer: agent
  name: Image Generation
  providers:
  - fal
  url: /capabilities/generative-media/
  via_parent: Generative Media
- attribution: API Evangelist extension
  id: AE-230.40.20
  key: AE-230.40.20
  layer: agent
  name: Web Search APIs
  providers:
  - Exa
  url: /capabilities/web-data/
  via_parent: Web Data
category:
  id: notes-knowledge
  name: Notes & Personal Knowledge Management
  url: /applications/notes-knowledge/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins
- route: source code
  url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
- route: source code
  url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
- route: source code
  url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
- route: source code
  url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
integrations:
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
    mcp: &id001
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id002
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
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
  layer: agent
  name: Cloudflare (Workers AI)
  provider: cloudflare
  says: ships the Cloudflare (Workers AI) SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id005
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id006
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/captcha/config.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.0
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id007
      source: https://github.com/exa-labs/exa-mcp-server
      status: verified
    slug: exa-ai
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Neural Search
    - Search
    - Web Search
    url: /providers/exa-ai/
  layer: agent
  name: Exa
  provider: exa-ai
  says: ships the Exa SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.10
    key: AE-110.20.10
    name: Image Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id009
      source: https://docs.fal.ai/model-apis/mcp
      status: verified
    slug: fal-ai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Generative AI
    - Generative Media
    - Image Generation
    url: /providers/fal-ai/
  layer: agent
  name: fal
  provider: fal-ai
  says: ships the fal SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id014
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/calendar/providers
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
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 76.2
    mcp: &id015
      source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
      status: verified
    slug: google-cloud-logging
    status: profiled
    tags: &id016
    - Cloud
    - Logging
    - Monitoring
    - Observability
    url: /providers/google-cloud-logging/
  layer: common
  name: Google Cloud Logging
  provider: google-cloud-logging
  says: ships the Google Cloud Logging SDK or integration code
  source: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/gcloud
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
    mcp: &id017
      status: none
    slug: google-gemini
    status: profiled
    tags: &id018
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    mcp: &id019
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id020
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
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
    agent_readiness: 42.2
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id021
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: agent
  name: Google Vertex AI
  provider: google-vertex-ai
  says: ships the Google Vertex AI SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    mcp: &id023
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id025
      source: https://www.revenuecat.com/docs/tools/mcp
      status: verified
    slug: revenuecat
    status: profiled
    tags: &id026
    - Billing
    - In-App Purchases
    - Mobile
    - Subscription
    url: /providers/revenuecat/
  layer: common
  name: RevenueCat
  provider: revenuecat
  says: ships the RevenueCat SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id027
      status: none
    slug: apple
    status: profiled
    tags: &id028
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
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
    mcp: &id029
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id030
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id031
      status: none
    slug: unsplash
    status: profiled
    tags: &id032
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: domain
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/notes-knowledge/affine/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id001
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id003
  name: Cloudflare (Workers AI)
  slug: cloudflare
  status: profiled
  tags: *id004
  url: /providers/cloudflare/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id005
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id006
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id007
  name: Exa
  slug: exa-ai
  status: profiled
  tags: *id008
  url: /providers/exa-ai/
- agent_band: agent-ready
  agent_readiness: 53.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id009
  name: fal
  slug: fal-ai
  status: profiled
  tags: *id010
  url: /providers/fal-ai/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id011
  name: GitHub
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id013
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id014
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 76.2
  mcp: *id015
  name: Google Cloud Logging
  slug: google-cloud-logging
  status: profiled
  tags: *id016
  url: /providers/google-cloud-logging/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id017
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id018
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id019
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id020
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id021
  name: Google Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id022
  url: /providers/google-vertex-ai/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id023
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id024
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id025
  name: RevenueCat
  slug: revenuecat
  status: profiled
  tags: *id026
  url: /providers/revenuecat/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id027
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id028
  url: /providers/apple/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id029
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id030
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id031
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id032
  url: /providers/unsplash/
siblings:
- name: BookStack
  rows: 11
  url: /applications/notes-knowledge/bookstack/
- name: Joplin
  rows: 5
  url: /applications/notes-knowledge/joplin/
- name: Logseq
  rows: 3
  url: /applications/notes-knowledge/logseq/
- name: Notion
  rows: 12
  url: /applications/notes-knowledge/notion/
- name: Obsidian
  rows: 0
  url: /applications/notes-knowledge/obsidian/
- name: Outline
  rows: 18
  url: /applications/notes-knowledge/outline/
- name: Wiki.js
  rows: 21
  url: /applications/notes-knowledge/wiki-js/
sitemap: true
title: 'AFFiNE: Notes & Personal Knowledge Management reference app'
---
