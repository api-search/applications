---
app: Pontoon
app_slug: pontoon
app_url: https://github.com/mozilla/pontoon
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Caighdean (cadhan.com)
  - Google Cloud AutoML Translation
  - Google Cloud Translation
  - Microsoft Translator
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.40.30
  key: AE-110.40.30
  layer: domain
  name: Translation Memory & Terminology Lookup
  providers:
  - Microsoft Terminology Service
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - GitLab
  - Google sign-in
  - Mozilla accounts
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: translation
  name: Translation & Localization
  url: /applications/translation/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/mozilla/pontoon/blob/main/requirements/1-prod.in
- route: source code
  url: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
- route: source code
  url: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.0
    mcp: &id001
      status: unknown
    slug: caighdean
    status: profiled
    tags: &id002
    - Company
    - Irish
    - Language
    - Open Source
    url: /providers/caighdean/
  layer: domain
  name: Caighdean (cadhan.com)
  provider: caighdean
  says: ships the Caighdean (cadhan.com) SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    mcp: &id003
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id004
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id005
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.2
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id009
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: domain
  name: Google Cloud AutoML Translation
  provider: google-cloud-automl
  says: ships the Google Cloud AutoML Translation SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id011
      status: none
    slug: google-translate
    status: profiled
    tags: &id012
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: domain
  name: Google Cloud Translation
  provider: google-translate
  says: ships the Google Cloud Translation SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.30
    key: AE-110.40.30
    name: Translation Memory & Terminology Lookup
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: microsoft-terminology
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Microsoft Terminology Service
  provider: microsoft-terminology
  says: ships the Microsoft Terminology Service SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id017
      source: https://github.com/microsoft/azure-speech-mcp-server
      status: verified
    slug: microsoft-cognitive-services
    status: profiled
    tags: &id018
    - Azure AI
    - Computer Vision
    - Natural Language Processing
    - Speech
    url: /providers/microsoft-cognitive-services/
  layer: domain
  name: Microsoft Translator
  provider: microsoft-cognitive-services
  says: ships the Microsoft Translator SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    agent_readiness: 6.3
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id019
      status: none
    slug: mozilla-accounts
    status: profiled
    tags: &id020
    - Authentication
    - Company
    - Identity
    - Mozilla
    url: /providers/mozilla-accounts/
  layer: common
  name: Mozilla accounts
  provider: mozilla-accounts
  says: ships the Mozilla accounts SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
    mcp: &id021
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id022
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/requirements/1-prod.in
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
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id025
      status: none
    slug: sendgrid
    status: profiled
    tags: &id026
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/translation/pontoon/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id001
  name: Caighdean (cadhan.com)
  slug: caighdean
  status: profiled
  tags: *id002
  url: /providers/caighdean/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id003
  name: GitHub
  slug: github
  status: profiled
  tags: *id004
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id005
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id006
  url: /providers/gitlab/
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
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id009
  name: Google Cloud AutoML Translation
  slug: google-vertex-ai
  status: profiled
  tags: *id010
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id011
  name: Google Cloud Translation
  slug: google-translate
  status: profiled
  tags: *id012
  url: /providers/google-translate/
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
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Microsoft Terminology Service
  slug: microsoft-terminology
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 32.2
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id017
  name: Microsoft Translator
  slug: microsoft-cognitive-services
  status: profiled
  tags: *id018
  url: /providers/microsoft-cognitive-services/
- agent_band: agent-aware
  agent_readiness: 6.3
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id019
  name: Mozilla accounts
  slug: mozilla-accounts
  status: profiled
  tags: *id020
  url: /providers/mozilla-accounts/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id021
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id022
  url: /providers/new-relic/
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
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id025
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id026
  url: /providers/sendgrid/
siblings:
- name: Crowdin
  rows: 11
  url: /applications/translation/crowdin/
- name: DeepL
  rows: 9
  url: /applications/translation/deepl/
- name: LibreTranslate
  rows: 0
  url: /applications/translation/libretranslate/
- name: Lokalise
  rows: 32
  url: /applications/translation/lokalise/
- name: Tolgee
  rows: 17
  url: /applications/translation/tolgee/
- name: Weblate
  rows: 33
  url: /applications/translation/weblate/
sitemap: true
title: 'Pontoon: Translation & Localization reference app'
---
