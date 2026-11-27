---
app: Webflow
app_slug: webflow
app_url: https://webflow.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Figma
  - LottieFiles
  - Relume
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Google Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: domain
  name: Marketing Operations Management
  providers:
  - Adobe Marketo Engage
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.40.20
  key: AE-140.40.20
  layer: domain
  name: Memberships
  providers:
  - Memberstack
  url: /capabilities/d2c-subscriptions/
  via_parent: D2C Subscriptions
- attribution: API Evangelist extension
  id: AE-931
  key: AE-931
  layer: domain
  name: No-Code App Builders
  providers:
  - Finsweet
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Microsoft Clarity
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Algolia
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Wistia
  url: /capabilities/video-platforms/
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
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Claude MCP connector
  - Gemini MCP connector
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: website-builder-cms
  name: Website Builder, CMS & Blogging
  url: /applications/website-builder-cms/
counts:
  declared: 17
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://webflow.com/apps
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id001
      status: none
    slug: marketo
    status: profiled
    tags: &id002
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
  layer: domain
  name: Adobe Marketo Engage
  provider: marketo
  says: lists Adobe Marketo Engage as an integration
  source: https://webflow.com/apps/detail/adobe-marketo-engage
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.9
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id003
      status: none
    slug: algolia
    status: profiled
    tags: &id004
    - Discovery
    - Personalization
    - Recommendations
    - Search
    url: /providers/algolia/
  layer: domain
  name: Algolia
  provider: algolia
  says: lists Algolia as an integration
  source: https://webflow.com/apps/detail/algolia
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
  name: Claude MCP connector
  provider: anthropic
  says: lists Claude MCP connector as an integration
  source: https://webflow.com/apps/detail/claude
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
    agent_readiness: 59.2
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id007
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id008
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
  layer: domain
  name: Figma
  provider: figma
  says: lists Figma as an integration
  source: https://webflow.com/apps/detail/figma
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-931
    key: AE-931
    name: No-Code App Builders
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.6
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id009
      status: none
    slug: finsweet
    status: profiled
    tags: &id010
    - Agency
    - Design
    - Development
    - Webflow
    url: /providers/finsweet/
  layer: domain
  name: Finsweet
  provider: finsweet
  says: lists Finsweet as an integration
  source: https://webflow.com/apps/detail/finsweet
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
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id011
      status: none
    slug: google-gemini
    status: profiled
    tags: &id012
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Gemini MCP connector
  provider: google-gemini
  says: lists Gemini MCP connector as an integration
  source: https://webflow.com/apps/detail/google-gemini
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id013
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id014
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://webflow.com/apps/detail/google-ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id015
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id016
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://webflow.com/apps/detail/hubspot
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
    agent_band: agent-aware
    agent_readiness: 12.0
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id017
      status: unknown
    slug: lottiefiles
    status: profiled
    tags: &id018
    - Animation
    - Company
    - Design
    - Motion Graphics
    url: /providers/lottiefiles/
  layer: domain
  name: LottieFiles
  provider: lottiefiles
  says: lists LottieFiles as an integration
  source: https://webflow.com/apps/detail/lottiefiles
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id019
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id020
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://webflow.com/apps/detail/make
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.40.20
    key: AE-140.40.20
    name: Memberships
    url: /capabilities/d2c-subscriptions/
    via_parent: D2C Subscriptions
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 41.5
    mcp: &id021
      source: https://developers.memberstack.com/mcp-server
      status: verified
    slug: memberstack
    status: profiled
    tags: &id022
    - Authentication
    - Membership
    - Software-as-a-Service
    - Webflow
    url: /providers/memberstack/
  layer: domain
  name: Memberstack
  provider: memberstack
  says: lists Memberstack as an integration
  source: https://webflow.com/apps/detail/memberstack
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
    agent_readiness: 29.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id023
      source: https://github.com/microsoft/clarity-mcp-server
      status: verified
    slug: microsoft-clarity
    status: profiled
    tags: &id024
    - Analytics
    - Heatmaps
    - Session Recording
    - Web Analytics
    url: /providers/microsoft-clarity/
  layer: domain
  name: Microsoft Clarity
  provider: microsoft-clarity
  says: lists Microsoft Clarity as an integration
  source: https://webflow.com/apps/detail/microsoft-clarity
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
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id025
      source: https://relume.ai/mcp
      status: verified
    slug: relume
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Company
    - Marketing
    - Website Builder
    url: /providers/relume/
  layer: domain
  name: Relume
  provider: relume
  says: lists Relume as an integration
  source: https://webflow.com/apps/detail/relume
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id027
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id028
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://webflow.com/apps/detail/slack
  tier: declared
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
    mcp: &id029
      status: none
    slug: unsplash
    status: profiled
    tags: &id030
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: domain
  name: Unsplash
  provider: unsplash
  says: lists Unsplash as an integration
  source: https://webflow.com/apps/detail/unsplash
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: exemplar
    in_catalog: true
    kin_score: 75.5
    mcp: &id031
      source: https://docs.wistia.com/docs/mcp-server-guide
      status: documented
    slug: wistia
    status: profiled
    tags: &id032
    - Lead Generation
    - Video Analytics
    - Video Hosting
    - Video Marketing
    url: /providers/wistia/
  layer: domain
  name: Wistia
  provider: wistia
  says: lists Wistia as an integration
  source: https://webflow.com/apps/detail/wistia
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id033
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id034
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://webflow.com/apps/detail/zapier
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/website-builder-cms/webflow/
providers:
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id001
  name: Adobe Marketo Engage
  slug: marketo
  status: profiled
  tags: *id002
  url: /providers/marketo/
- agent_band: agent-ready
  agent_readiness: 61.9
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id003
  name: Algolia
  slug: algolia
  status: profiled
  tags: *id004
  url: /providers/algolia/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Claude MCP connector
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id007
  name: Figma
  slug: figma
  status: profiled
  tags: *id008
  url: /providers/figma/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id009
  name: Finsweet
  slug: finsweet
  status: profiled
  tags: *id010
  url: /providers/finsweet/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id011
  name: Gemini MCP connector
  slug: google-gemini
  status: profiled
  tags: *id012
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id013
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id014
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id015
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id016
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 12.0
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id017
  name: LottieFiles
  slug: lottiefiles
  status: profiled
  tags: *id018
  url: /providers/lottiefiles/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id019
  name: Make
  slug: make
  status: profiled
  tags: *id020
  url: /providers/make/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 41.5
  mcp: *id021
  name: Memberstack
  slug: memberstack
  status: profiled
  tags: *id022
  url: /providers/memberstack/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id023
  name: Microsoft Clarity
  slug: microsoft-clarity
  status: profiled
  tags: *id024
  url: /providers/microsoft-clarity/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id025
  name: Relume
  slug: relume
  status: profiled
  tags: *id026
  url: /providers/relume/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id027
  name: Slack
  slug: slack
  status: profiled
  tags: *id028
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id029
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id030
  url: /providers/unsplash/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: exemplar
  in_catalog: true
  kin_score: 75.5
  mcp: *id031
  name: Wistia
  slug: wistia
  status: profiled
  tags: *id032
  url: /providers/wistia/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id033
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id034
  url: /providers/zapier/
siblings:
- name: Directus
  rows: 12
  url: /applications/website-builder-cms/directus/
- name: Ghost
  rows: 76
  url: /applications/website-builder-cms/ghost/
- name: Payload
  rows: 9
  url: /applications/website-builder-cms/payload/
- name: Strapi
  rows: 5
  url: /applications/website-builder-cms/strapi/
- name: WordPress
  rows: 30
  url: /applications/website-builder-cms/wordpress/
sitemap: true
title: 'Webflow: Website Builder, CMS & Blogging reference app'
---
