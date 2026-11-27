---
app: Outline
app_slug: outline
app_url: https://github.com/outline/outline
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - Notion
  - Slab
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70.10
  key: AE-170.70.10
  layer: domain
  name: Link Unfurling & Rich Embeds
  providers:
  - Dropbox
  - Figma
  - GitHub
  - GitLab
  - Iframely
  - Linear
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Discord
  - Google sign-in
  - Slack
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-3740.30
  key: content-delivery-network-operations
  layer: common
  name: Content Delivery Network Operations
  providers:
  - Amazon CloudFront
  url: /capabilities/content-delivery-network-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - Matomo
  - Umami
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Microsoft (Azure AD)
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: notes-knowledge
  name: Notes & Personal Knowledge Management
  url: /applications/notes-knowledge/
counts:
  declared: 0
  observed: 18
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/outline/outline/main/package.json
- route: source code
  url: https://github.com/outline/outline/tree/main/plugins
- route: source code
  url: https://raw.githubusercontent.com/outline/outline/main/.env.sample
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id001
      status: none
    slug: cloudfront
    status: profiled
    tags: &id002
    - Amazon Web Services
    - CDN
    - Caching
    - Content Delivery
    url: /providers/cloudfront/
  layer: common
  name: Amazon CloudFront
  provider: cloudfront
  says: ships the Amazon CloudFront SDK or integration code
  source: https://raw.githubusercontent.com/outline/outline/main/.env.sample
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id003
      status: none
    slug: discord
    status: profiled
    tags: &id004
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id005
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://raw.githubusercontent.com/outline/outline/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
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
  says: ships the Figma SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id009
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id011
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
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
    mcp: &id013
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id014
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
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
    mcp: &id015
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id016
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.5
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id017
      status: unknown
    slug: iframely
    status: profiled
    tags: &id018
    - Content
    - Embed
    - Media
    - URLs
    url: /providers/iframely/
  layer: domain
  name: Iframely
  provider: iframely
  says: ships the Iframely SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id019
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id020
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: ships the Linear SDK or integration code
  source: https://raw.githubusercontent.com/outline/outline/main/package.json
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
    agent_readiness: 41.3
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id021
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id022
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id023
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id024
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft (Azure AD)
  provider: microsoft-entra
  says: ships the Microsoft (Azure AD) SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id025
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id026
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: ships the Notion SDK or integration code
  source: https://raw.githubusercontent.com/outline/outline/main/package.json
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id027
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id028
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/outline/outline/main/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id029
      status: none
    slug: slab
    status: profiled
    tags: &id030
    - Collaboration
    - Documentation
    - Knowledge Base
    - Wiki
    url: /providers/slab/
  layer: domain
  name: Slab
  provider: slab
  says: ships the Slab SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/outline/outline/main/.env.sample
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
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id033
      status: none
    slug: umami
    status: profiled
    tags: &id034
    - Cookieless Tracking
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/umami/
  layer: common
  name: Umami
  provider: umami
  says: ships the Umami SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
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
    mcp: &id035
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id036
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: ships the Zapier SDK or integration code
  source: https://github.com/outline/outline/tree/main/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/notes-knowledge/outline/
providers:
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id001
  name: Amazon CloudFront
  slug: cloudfront
  status: profiled
  tags: *id002
  url: /providers/cloudfront/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id003
  name: Discord
  slug: discord
  status: profiled
  tags: *id004
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id005
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id006
  url: /providers/dropbox/
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
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id011
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id012
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id013
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id014
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id015
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 4.5
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id017
  name: Iframely
  slug: iframely
  status: profiled
  tags: *id018
  url: /providers/iframely/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id019
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id020
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 41.3
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id021
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id022
  url: /providers/matomo/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id023
  name: Microsoft (Azure AD)
  slug: microsoft-entra
  status: profiled
  tags: *id024
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id025
  name: Notion
  slug: notion
  status: profiled
  tags: *id026
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id027
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id028
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id029
  name: Slab
  slug: slab
  status: profiled
  tags: *id030
  url: /providers/slab/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id033
  name: Umami
  slug: umami
  status: profiled
  tags: *id034
  url: /providers/umami/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id035
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id036
  url: /providers/zapier/
siblings:
- name: AFFiNE
  rows: 16
  url: /applications/notes-knowledge/affine/
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
- name: Wiki.js
  rows: 21
  url: /applications/notes-knowledge/wiki-js/
sitemap: true
title: 'Outline: Notes & Personal Knowledge Management reference app'
---
