---
app: DeepL
app_slug: deepl
app_url: https://www.deepl.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Google Workspace
  - Microsoft 365 (Word, Outlook, PowerPoint)
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - LinkedIn
  - WhatsApp
  - X (Twitter)
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-250.10
  key: AE-250.10
  layer: common
  name: Package Registries & Distribution
  providers:
  - AWS Marketplace
  url: /capabilities/package-registries-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.10
  key: AE-100.10
  layer: agent
  name: Agent Tool Exposure
  providers:
  - ChatGPT
  - Claude
  url: /capabilities/agent-tool-exposure/
  via_parent: null
category:
  id: translation
  name: Translation & Localization
  url: /applications/translation/
counts:
  declared: 8
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.deepl.mobiletranslator/latest/
- route: integrations page
  url: https://www.deepl.com/en/integrations
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
    kin_score: 80.7
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.deepl.mobiletranslator/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10
    key: AE-250.10
    name: Package Registries & Distribution
    url: /capabilities/package-registries-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS Marketplace
  provider: amazon-web-services
  says: lists AWS Marketplace as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.10
    key: AE-100.10
    name: Agent Tool Exposure
    url: /capabilities/agent-tool-exposure/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
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
  name: ChatGPT
  provider: openai
  says: lists ChatGPT as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.10
    key: AE-100.10
    name: Agent Tool Exposure
    url: /capabilities/agent-tool-exposure/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Claude
  provider: anthropic
  says: lists Claude as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id007
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id008
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: domain
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id009
      status: none
    slug: linkedin
    status: profiled
    tags: &id010
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id012
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365 (Word, Outlook, PowerPoint)
  provider: microsoft-365
  says: lists Microsoft 365 (Word, Outlook, PowerPoint) as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
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
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id015
      status: none
    slug: whatsapp
    status: profiled
    tags: &id016
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id017
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id018
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: lists X (Twitter) as an integration
  source: https://www.deepl.com/en/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/translation/deepl/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: AWS Marketplace
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id003
  name: ChatGPT
  slug: openai
  status: profiled
  tags: *id004
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Claude
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id007
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id008
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id009
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id010
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id011
  name: Microsoft 365 (Word, Outlook, PowerPoint)
  slug: microsoft-365
  status: profiled
  tags: *id012
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id015
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id016
  url: /providers/whatsapp/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id017
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id018
  url: /providers/x/
siblings:
- name: Crowdin
  rows: 11
  url: /applications/translation/crowdin/
- name: LibreTranslate
  rows: 0
  url: /applications/translation/libretranslate/
- name: Lokalise
  rows: 32
  url: /applications/translation/lokalise/
- name: Pontoon
  rows: 13
  url: /applications/translation/pontoon/
- name: Tolgee
  rows: 17
  url: /applications/translation/tolgee/
- name: Weblate
  rows: 33
  url: /applications/translation/weblate/
sitemap: true
title: 'DeepL: Translation & Localization reference app'
---
