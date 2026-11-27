---
app: Feedly
app_slug: feedly
app_url: https://feedly.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - Pocket
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: Turbo EA
  id: BC-830.10
  key: knowledge-capture-management
  layer: domain
  name: Knowledge Capture Management
  providers:
  - Evernote
  - OneNote
  url: /capabilities/knowledge-capture-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Buffer
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 8
  observed: 0
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.devhd.feedly/latest/
- route: integrations page
  url: https://docs.feedly.com/collection/420-integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id001
      status: none
    slug: buffer
    status: profiled
    tags: &id002
    - Analytics
    - Publishing
    - Scheduling
    - Social Media
    url: /providers/buffer/
  layer: domain
  name: Buffer
  provider: buffer
  says: lists Buffer as an integration
  source: https://docs.feedly.com/collection/420-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.10
    key: knowledge-capture-management
    name: Knowledge Capture Management
    url: /capabilities/knowledge-capture-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.0
    band: developing
    in_catalog: true
    kin_score: 53.0
    mcp: &id003
      source: https://dev.evernote.com/
      status: documented
    slug: evernote
    status: profiled
    tags: &id004
    - Company
    - Knowledge Management
    - Note Taking
    - Productivity
    url: /providers/evernote/
  layer: domain
  name: Evernote
  provider: evernote
  says: lists Evernote as an integration
  source: https://docs.feedly.com/collection/420-integrations
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
    agent_readiness: 42.4
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id005
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id006
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: lists IFTTT as an integration
  source: https://docs.feedly.com/collection/420-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id007
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id008
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://docs.feedly.com/collection/420-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.10
    key: knowledge-capture-management
    name: Knowledge Capture Management
    url: /capabilities/knowledge-capture-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id009
      status: none
    slug: microsoft-onenote
    status: profiled
    tags: &id010
    - Microsoft
    - Microsoft 365
    - Notebooks
    - Notes
    url: /providers/microsoft-onenote/
  layer: domain
  name: OneNote
  provider: microsoft-onenote
  says: lists OneNote as an integration
  source: https://docs.feedly.com/collection/420-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.3
    mcp: &id011
      status: none
    slug: pocket
    status: profiled
    tags: &id012
    - Bookmarking
    - Productivity
    - Public APIs
    url: /providers/pocket/
  layer: domain
  name: Pocket
  provider: pocket
  says: lists Pocket as an integration
  source: https://docs.feedly.com/collection/420-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id013
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id014
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://docs.feedly.com/collection/420-integrations
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
    mcp: &id015
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id016
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://docs.feedly.com/collection/420-integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/feedly/
providers:
- agent_band: agent-ready
  agent_readiness: 43.2
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id001
  name: Buffer
  slug: buffer
  status: profiled
  tags: *id002
  url: /providers/buffer/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: developing
  in_catalog: true
  kin_score: 53.0
  mcp: *id003
  name: Evernote
  slug: evernote
  status: profiled
  tags: *id004
  url: /providers/evernote/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id005
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id006
  url: /providers/ifttt/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id007
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id008
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id009
  name: OneNote
  slug: microsoft-onenote
  status: profiled
  tags: *id010
  url: /providers/microsoft-onenote/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id011
  name: Pocket
  slug: pocket
  status: profiled
  tags: *id012
  url: /providers/pocket/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id013
  name: Slack
  slug: slack
  status: profiled
  tags: *id014
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id015
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id016
  url: /providers/zapier/
siblings:
- name: FreshRSS
  rows: 21
  url: /applications/news-feed-reader/freshrss/
- name: Karakeep
  rows: 4
  url: /applications/news-feed-reader/karakeep/
- name: Linkwarden
  rows: 55
  url: /applications/news-feed-reader/linkwarden/
- name: Miniflux
  rows: 28
  url: /applications/news-feed-reader/miniflux/
- name: NewsBlur
  rows: 11
  url: /applications/news-feed-reader/newsblur/
- name: Readwise Reader
  rows: 10
  url: /applications/news-feed-reader/readwise-reader/
- name: Wallabag
  rows: 8
  url: /applications/news-feed-reader/wallabag/
sitemap: true
title: 'Feedly: News, Feeds & Read-Later reference app'
---
