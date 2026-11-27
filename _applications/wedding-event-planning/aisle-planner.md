---
app: Aisle Planner
app_slug: aisle-planner
app_url: https://www.aisleplanner.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Apple account (AP Connect)
  - Google account (AP Connect)
  - Microsoft account (AP Connect)
  url: /capabilities/mailbox-calendar-sync/
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
  id: wedding-event-planning
  name: Wedding & Event Planning
  url: /applications/wedding-event-planning/
counts:
  declared: 6
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://help.aisleplanner.com/en/collections/1547142-integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple account (AP Connect)
  provider: apple
  says: lists Apple account (AP Connect) as an integration
  source: https://help.aisleplanner.com/en/collections/1547142-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id004
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google account (AP Connect)
  provider: google
  says: lists Google account (AP Connect) as an integration
  source: https://help.aisleplanner.com/en/collections/1547142-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id005
      status: none
    slug: mailchimp
    status: profiled
    tags: &id006
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://help.aisleplanner.com/en/collections/1547142-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id008
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft account (AP Connect)
  provider: microsoft-graph
  says: lists Microsoft account (AP Connect) as an integration
  source: https://help.aisleplanner.com/en/collections/1547142-integrations
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
    mcp: &id009
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id010
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://help.aisleplanner.com/en/collections/1547142-integrations
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
    mcp: &id011
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id012
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://help.aisleplanner.com/en/collections/1547142-integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/wedding-event-planning/aisle-planner/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple account (AP Connect)
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id003
  name: Google account (AP Connect)
  slug: google
  status: profiled
  tags: *id004
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id005
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id006
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id007
  name: Microsoft account (AP Connect)
  slug: microsoft-graph
  status: profiled
  tags: *id008
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id009
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id010
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id011
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id012
  url: /providers/zapier/
siblings:
- name: HoneyBook
  rows: 40
  url: /applications/wedding-event-planning/honeybook/
- name: Joy
  rows: 12
  url: /applications/wedding-event-planning/joy/
- name: Planning Pod
  rows: 23
  url: /applications/wedding-event-planning/planning-pod/
- name: Rallly
  rows: 16
  url: /applications/wedding-event-planning/rallly/
- name: The Knot Wedding Planner
  rows: 0
  url: /applications/wedding-event-planning/the-knot-wedding-planner/
- name: WeddingShare
  rows: 2
  url: /applications/wedding-event-planning/weddingshare/
sitemap: true
title: 'Aisle Planner: Wedding & Event Planning reference app'
---
