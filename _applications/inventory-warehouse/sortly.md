---
app: Sortly
app_slug: sortly
app_url: https://www.sortly.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
category:
  id: inventory-warehouse
  name: Inventory & Warehouse Management
  url: /applications/inventory-warehouse/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.sortly.com/features/integrations/
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id001
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id002
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.sortly.com/features/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id003
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id004
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.sortly.com/features/integrations/
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
    mcp: &id005
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id006
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.sortly.com/features/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/inventory-warehouse/sortly/
providers:
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id001
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id002
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id003
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id004
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id005
  name: Slack
  slug: slack
  status: profiled
  tags: *id006
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
- name: Snipe-IT
  rows: 5
  url: /applications/inventory-warehouse/snipe-it/
- name: Zoho Inventory
  rows: 0
  url: /applications/inventory-warehouse/zoho-inventory/
sitemap: true
title: 'Sortly: Inventory & Warehouse Management reference app'
---
