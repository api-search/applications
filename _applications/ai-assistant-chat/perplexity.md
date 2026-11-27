---
app: Perplexity
app_slug: perplexity
app_url: https://www.perplexity.ai/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Singular
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
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
category:
  id: ai-assistant-chat
  name: AI Assistant & Chat
  url: /applications/ai-assistant-chat/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
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
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id003
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id004
      status: none
    slug: singular
    status: profiled
    tags: &id005
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: common
  name: Singular
  provider: singular
  says: ships the Singular SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ai-assistant-chat/perplexity/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id002
  name: Firebase (Crashlytics)
  slug: google-firebase
  status: profiled
  tags: *id003
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id004
  name: Singular
  slug: singular
  status: profiled
  tags: *id005
  url: /providers/singular/
siblings:
- name: AnythingLLM
  rows: 43
  url: /applications/ai-assistant-chat/anythingllm/
- name: ChatGPT
  rows: 2
  url: /applications/ai-assistant-chat/chatgpt/
- name: Claude
  rows: 2
  url: /applications/ai-assistant-chat/claude/
- name: Le Chat (Mistral)
  rows: 1
  url: /applications/ai-assistant-chat/le-chat-mistral/
- name: LibreChat
  rows: 39
  url: /applications/ai-assistant-chat/librechat/
- name: LobeChat
  rows: 48
  url: /applications/ai-assistant-chat/lobechat/
- name: Open WebUI
  rows: 26
  url: /applications/ai-assistant-chat/open-webui/
sitemap: true
title: 'Perplexity: AI Assistant & Chat reference app'
---
