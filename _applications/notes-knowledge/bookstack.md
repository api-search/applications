---
app: BookStack
app_slug: bookstack
app_url: https://github.com/BookStackApp/BookStack
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70.10
  key: AE-170.70.10
  layer: domain
  name: Link Unfurling & Rich Embeds
  providers:
  - diagrams.net (draw.io)
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Discord
  - Facebook
  - GitHub
  - GitLab
  - Google sign-in
  - Slack
  - Twitch
  - Twitter / X
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Microsoft Azure AD
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: notes-knowledge
  name: Notes & Personal Knowledge Management
  url: /applications/notes-knowledge/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
- route: source code
  url: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: diagrams-net
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: diagrams.net (draw.io)
  provider: diagrams-net
  says: ships the diagrams.net (draw.io) SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
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
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
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
  says: ships the GitHub SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
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
    mcp: &id009
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
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
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
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
    mcp: &id013
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id014
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Azure AD
  provider: microsoft-entra
  says: ships the Microsoft Azure AD SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id015
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id016
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: ships the Okta SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
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
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
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
    agent_readiness: 36.9
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id019
      status: none
    slug: twitch
    status: profiled
    tags: &id020
    - Entertainment
    - Gaming
    - Live Streaming
    - Streaming
    url: /providers/twitch/
  layer: domain
  name: Twitch
  provider: twitch
  says: ships the Twitch SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
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
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id021
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id022
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter / X
  provider: x
  says: ships the Twitter / X SDK or integration code
  source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/notes-knowledge/bookstack/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: diagrams.net (draw.io)
  slug: diagrams-net
  status: queued for profiling
  tags: *id002
  url: null
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
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id007
  name: GitHub
  slug: github
  status: profiled
  tags: *id008
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id009
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id010
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id013
  name: Microsoft Azure AD
  slug: microsoft-entra
  status: profiled
  tags: *id014
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id015
  name: Okta
  slug: okta
  status: profiled
  tags: *id016
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id017
  name: Slack
  slug: slack
  status: profiled
  tags: *id018
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id019
  name: Twitch
  slug: twitch
  status: profiled
  tags: *id020
  url: /providers/twitch/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id021
  name: Twitter / X
  slug: x
  status: profiled
  tags: *id022
  url: /providers/x/
siblings:
- name: AFFiNE
  rows: 16
  url: /applications/notes-knowledge/affine/
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
- name: Outline
  rows: 18
  url: /applications/notes-knowledge/outline/
- name: Wiki.js
  rows: 21
  url: /applications/notes-knowledge/wiki-js/
sitemap: true
title: 'BookStack: Notes & Personal Knowledge Management reference app'
---
