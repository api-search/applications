---
app: GitHub
app_slug: github
app_url: https://github.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.20.40
  key: AE-110.20.40
  layer: agent
  name: Code Generation
  providers:
  - Anthropic (Claude models in Copilot)
  - Google Gemini (in Copilot)
  - OpenAI (GPT models in Copilot)
  - xAI Grok (in Copilot)
  url: /capabilities/generative-media/
  via_parent: Generative Media
category:
  id: ci-cd-devops
  name: Code Hosting, CI/CD & DevOps
  url: /applications/ci-cd-devops/
counts:
  declared: 4
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
- route: documentation
  url: https://docs.github.com/en/copilot/reference/ai-models/supported-models
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id005
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.40
    key: AE-110.20.40
    name: Code Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id002
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id003
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic (Claude models in Copilot)
  provider: anthropic
  says: lists Anthropic (Claude models in Copilot) as an integration
  source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.40
    key: AE-110.20.40
    name: Code Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id006
      status: none
    slug: google-gemini
    status: profiled
    tags: &id007
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini (in Copilot)
  provider: google-gemini
  says: lists Google Gemini (in Copilot) as an integration
  source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.40
    key: AE-110.20.40
    name: Code Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id008
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id009
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI (GPT models in Copilot)
  provider: openai
  says: lists OpenAI (GPT models in Copilot) as an integration
  source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.40
    key: AE-110.20.40
    name: Code Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id010
      status: none
    slug: xai
    status: profiled
    tags: &id011
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
  layer: agent
  name: xAI Grok (in Copilot)
  provider: xai
  says: lists xAI Grok (in Copilot) as an integration
  source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ci-cd-devops/github/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id002
  name: Anthropic (Claude models in Copilot)
  slug: anthropic
  status: profiled
  tags: *id003
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id004
  name: Firebase (Crashlytics)
  slug: google-firebase
  status: profiled
  tags: *id005
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id006
  name: Google Gemini (in Copilot)
  slug: google-gemini
  status: profiled
  tags: *id007
  url: /providers/google-gemini/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id008
  name: OpenAI (GPT models in Copilot)
  slug: openai
  status: profiled
  tags: *id009
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id010
  name: xAI Grok (in Copilot)
  slug: xai
  status: profiled
  tags: *id011
  url: /providers/xai/
siblings:
- name: CircleCI
  rows: 54
  url: /applications/ci-cd-devops/circleci/
- name: Coolify
  rows: 21
  url: /applications/ci-cd-devops/coolify/
- name: Gitea
  rows: 24
  url: /applications/ci-cd-devops/gitea/
- name: GitLab
  rows: 54
  url: /applications/ci-cd-devops/gitlab/
- name: Woodpecker CI
  rows: 3
  url: /applications/ci-cd-devops/woodpecker-ci/
sitemap: true
title: 'GitHub: Code Hosting, CI/CD & DevOps reference app'
---
