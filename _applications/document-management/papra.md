---
app: Papra
app_slug: papra
app_url: https://github.com/papra-hq/papra
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-150.10.50
  key: AE-150.10.50
  layer: domain
  name: Inbound Email Processing
  providers:
  - OwlRelay
  url: /capabilities/email/
  via_parent: Email
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
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Resend
  url: /capabilities/email/
  via_parent: Email
category:
  id: document-management
  name: Document Management & OCR
  url: /applications/document-management/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
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
  layer: domain
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id004
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id005
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.50
    key: AE-150.10.50
    name: Inbound Email Processing
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id007
      status: none
    slug: owlrelay
    status: profiled
    tags: &id008
    - Company
    - Email
    - Open Source
    - Webhook
    url: /providers/owlrelay/
  layer: domain
  name: OwlRelay
  provider: owlrelay
  says: ships the OwlRelay SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id009
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id010
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    agent_readiness: 49.4
    band: strong
    in_catalog: true
    kin_score: 58.9
    mcp: &id011
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id012
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    mcp: &id013
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id014
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/document-management/papra/
providers:
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id001
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id005
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id006
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id007
  name: OwlRelay
  slug: owlrelay
  status: profiled
  tags: *id008
  url: /providers/owlrelay/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id009
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id010
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 49.4
  band: strong
  in_catalog: true
  kin_score: 58.9
  mcp: *id011
  name: Resend
  slug: resend
  status: profiled
  tags: *id012
  url: /providers/resend/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id013
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id014
  url: /providers/stripe/
siblings:
- name: Adobe Acrobat
  rows: 31
  url: /applications/document-management/adobe-acrobat/
- name: Docspell
  rows: 0
  url: /applications/document-management/docspell/
- name: Mayan EDMS
  rows: 1
  url: /applications/document-management/mayan-edms/
- name: paperless-gpt
  rows: 14
  url: /applications/document-management/paperless-gpt/
- name: Paperless-ngx
  rows: 8
  url: /applications/document-management/paperless-ngx/
- name: Stirling-PDF
  rows: 5
  url: /applications/document-management/stirling-pdf/
sitemap: true
title: 'Papra: Document Management & OCR reference app'
---
