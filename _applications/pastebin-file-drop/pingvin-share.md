---
app: Pingvin Share
app_slug: pingvin-share
app_url: https://github.com/stonith404/pingvin-share
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Discord
  - GitHub
  - Google sign-in
  - Microsoft sign-in (Entra ID)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: pastebin-file-drop
  name: Pastebin, File Drop & Quick Share
  url: /applications/pastebin-file-drop/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/stonith404/pingvin-share/main/backend/package.json
- route: source code
  url: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: domain
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/stonith404/pingvin-share/main/backend/package.json
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
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
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
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
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
    mcp: &id007
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id008
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id009
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id010
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft sign-in (Entra ID)
  provider: microsoft-entra
  says: ships the Microsoft sign-in (Entra ID) SDK or integration code
  source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pastebin-file-drop/pingvin-share/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
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
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id005
  name: GitHub
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id007
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id008
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id009
  name: Microsoft sign-in (Entra ID)
  slug: microsoft-entra
  status: profiled
  tags: *id010
  url: /providers/microsoft-entra/
siblings:
- name: LocalSend
  rows: 2
  url: /applications/pastebin-file-drop/localsend/
- name: PrivateBin
  rows: 5
  url: /applications/pastebin-file-drop/privatebin/
- name: PsiTransfer
  rows: 0
  url: /applications/pastebin-file-drop/psitransfer/
- name: Send (timvisee fork of Firefox Send)
  rows: 4
  url: /applications/pastebin-file-drop/send-timvisee-fork-of-firefox-send/
- name: WeTransfer
  rows: 2
  url: /applications/pastebin-file-drop/wetransfer/
- name: Zipline
  rows: 5
  url: /applications/pastebin-file-drop/zipline/
sitemap: true
title: 'Pingvin Share: Pastebin, File Drop & Quick Share reference app'
---
