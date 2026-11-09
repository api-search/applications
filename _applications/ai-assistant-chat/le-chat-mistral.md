---
app: Le Chat (Mistral)
app_slug: le-chat-mistral
app_url: https://chat.mistral.ai/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: ai-assistant-chat
  name: AI Assistant & Chat
  url: /applications/ai-assistant-chat/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/ai.mistral.chat/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id001
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id002
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/ai.mistral.chat/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ai-assistant-chat/le-chat-mistral/
providers:
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id001
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id002
  url: /providers/sentry-system/
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
- name: LibreChat
  rows: 39
  url: /applications/ai-assistant-chat/librechat/
- name: LobeChat
  rows: 48
  url: /applications/ai-assistant-chat/lobechat/
- name: Open WebUI
  rows: 26
  url: /applications/ai-assistant-chat/open-webui/
- name: Perplexity
  rows: 3
  url: /applications/ai-assistant-chat/perplexity/
sitemap: true
title: 'Le Chat (Mistral): AI Assistant & Chat reference app'
---
