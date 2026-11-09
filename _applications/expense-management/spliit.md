---
app: Spliit
app_slug: spliit
app_url: https://github.com/spliit-app/spliit
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Plausible
  - Umami
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: agent
  name: OCR & Document AI
  providers:
  - OpenAI
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
category:
  id: expense-management
  name: Expense & Spend Management
  url: /applications/expense-management/
counts:
  declared: 2
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/spliit-app/spliit/main/package.json
- route: source code
  url: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
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
  source: https://raw.githubusercontent.com/spliit-app/spliit/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id003
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
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
    agent_band: agent-aware
    agent_readiness: 23.1
    band: strong
    in_catalog: true
    kin_score: 63.4
    mcp: &id005
      status: none
    slug: plausible
    status: profiled
    tags: &id006
    - Analytics
    - Cookie-Free
    - Event Tracking
    - GDPR
    url: /providers/plausible/
  layer: common
  name: Plausible
  provider: plausible
  says: lists Plausible as an integration
  source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
  tier: declared
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
    agent_readiness: 38.4
    band: exemplar
    in_catalog: true
    kin_score: 73.3
    mcp: &id007
      status: none
    slug: umami
    status: profiled
    tags: &id008
    - Cookieless Tracking
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/umami/
  layer: common
  name: Umami
  provider: umami
  says: lists Umami as an integration
  source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/expense-management/spliit/
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
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id003
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id004
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: strong
  in_catalog: true
  kin_score: 63.4
  mcp: *id005
  name: Plausible
  slug: plausible
  status: profiled
  tags: *id006
  url: /providers/plausible/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: exemplar
  in_catalog: true
  kin_score: 73.3
  mcp: *id007
  name: Umami
  slug: umami
  status: profiled
  tags: *id008
  url: /providers/umami/
siblings:
- name: Brex
  rows: 82
  url: /applications/expense-management/brex/
- name: Expensify
  rows: 82
  url: /applications/expense-management/expensify/
- name: IHateMoney
  rows: 1
  url: /applications/expense-management/ihatemoney/
- name: Ramp
  rows: 62
  url: /applications/expense-management/ramp/
- name: SAP Concur
  rows: 3
  url: /applications/expense-management/sap-concur/
- name: Splitwise
  rows: 2
  url: /applications/expense-management/splitwise/
sitemap: true
title: 'Spliit: Expense & Spend Management reference app'
---
