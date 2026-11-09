---
app: Crowdin
app_slug: crowdin
app_url: https://crowdin.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Adobe Experience Manager
  - Contentful
  - Webflow
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Intercom
  - Zendesk Guide
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Figma
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - HubSpot Marketing Hub
  url: /capabilities/digital-marketing-management/
  via_parent: null
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
  - Opal by Welocalize
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
category:
  id: translation
  name: Translation & Localization
  url: /applications/translation/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://store.crowdin.com/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-manager
    status: profiled
    tags: &id002
    - Content Management
    - Digital Asset Management
    - Enterprise CMS
    - Headless CMS
    url: /providers/adobe-experience-manager/
  layer: domain
  name: Adobe Experience Manager
  provider: adobe-experience-manager
  says: lists Adobe Experience Manager as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.5
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id003
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id004
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
  layer: domain
  name: Contentful
  provider: contentful
  says: lists Contentful as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.8
    band: strong
    in_catalog: true
    kin_score: 65.6
    mcp: &id005
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id006
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
  layer: domain
  name: Figma
  provider: figma
  says: lists Figma as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id007
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id008
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id009
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id010
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot Marketing Hub
  provider: hubspot
  says: lists HubSpot Marketing Hub as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id011
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://store.crowdin.com/
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
    agent_band: human-only
    agent_readiness: 3.6
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id013
      status: none
    slug: welocalize
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Company
    - Localization
    - Translation
    url: /providers/welocalize/
  layer: domain
  name: Opal by Welocalize
  provider: welocalize
  says: lists Opal by Welocalize as an integration
  source: https://store.crowdin.com/
  tier: declared
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
    mcp: &id015
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id017
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id018
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id019
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id020
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://store.crowdin.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id021
      status: none
    slug: zendesk
    status: profiled
    tags: &id022
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk Guide
  provider: zendesk
  says: lists Zendesk Guide as an integration
  source: https://store.crowdin.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/translation/crowdin/
providers:
- agent_band: agent-aware
  agent_readiness: 21.8
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id001
  name: Adobe Experience Manager
  slug: adobe-experience-manager
  status: profiled
  tags: *id002
  url: /providers/adobe-experience-manager/
- agent_band: agent-ready
  agent_readiness: 56.5
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id003
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id004
  url: /providers/contentful/
- agent_band: agent-ready
  agent_readiness: 57.8
  band: strong
  in_catalog: true
  kin_score: 65.6
  mcp: *id005
  name: Figma
  slug: figma
  status: profiled
  tags: *id006
  url: /providers/figma/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id007
  name: GitHub
  slug: github
  status: profiled
  tags: *id008
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id009
  name: HubSpot Marketing Hub
  slug: hubspot
  status: profiled
  tags: *id010
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id011
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id012
  url: /providers/intercom/
- agent_band: human-only
  agent_readiness: 3.6
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id013
  name: Opal by Welocalize
  slug: welocalize
  status: profiled
  tags: *id014
  url: /providers/welocalize/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id015
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id016
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id017
  name: Slack
  slug: slack
  status: profiled
  tags: *id018
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id019
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id020
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id021
  name: Zendesk Guide
  slug: zendesk
  status: profiled
  tags: *id022
  url: /providers/zendesk/
siblings:
- name: DeepL
  rows: 9
  url: /applications/translation/deepl/
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
title: 'Crowdin: Translation & Localization reference app'
---
