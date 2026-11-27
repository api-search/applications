---
app: Snipe-IT
app_slug: snipe-it
app_url: https://github.com/snipe/snipe-it
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Google Chat
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Rollbar
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Microsoft Graph
  url: /capabilities/email/
  via_parent: Email
category:
  id: inventory-warehouse
  name: Inventory & Warehouse Management
  url: /applications/inventory-warehouse/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
integrations:
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
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id001
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id002
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: common
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
  source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id004
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
  tier: observed
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id005
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id006
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
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
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id007
      source: https://github.com/rollbar/rollbar-mcp-server
      status: verified
    slug: rollbar
    status: profiled
    tags: &id008
    - Debugging
    - DevOps
    - Error Tracking
    - Monitoring
    url: /providers/rollbar/
  layer: common
  name: Rollbar
  provider: rollbar
  says: ships the Rollbar SDK or integration code
  source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
  tier: observed
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
    mcp: &id009
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id010
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/inventory-warehouse/snipe-it/
providers:
- agent_band: agent-ready
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id001
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id002
  url: /providers/google-chat/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id003
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id004
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id005
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id006
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id007
  name: Rollbar
  slug: rollbar
  status: profiled
  tags: *id008
  url: /providers/rollbar/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id009
  name: Slack
  slug: slack
  status: profiled
  tags: *id010
  url: /providers/slack/
siblings:
- name: Cin7
  rows: 15
  url: /applications/inventory-warehouse/cin7/
- name: inFlow Inventory
  rows: 24
  url: /applications/inventory-warehouse/inflow-inventory/
- name: InvenTree
  rows: 8
  url: /applications/inventory-warehouse/inventree/
- name: Part-DB
  rows: 20
  url: /applications/inventory-warehouse/part-db/
- name: Shelf
  rows: 5
  url: /applications/inventory-warehouse/shelf/
- name: Sortly
  rows: 3
  url: /applications/inventory-warehouse/sortly/
- name: Zoho Inventory
  rows: 0
  url: /applications/inventory-warehouse/zoho-inventory/
sitemap: true
title: 'Snipe-IT: Inventory & Warehouse Management reference app'
---
