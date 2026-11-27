---
app: Farmbrite
app_slug: farmbrite
app_url: https://www.farmbrite.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Local Line
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
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
  - Xero
  url: /capabilities/general-ledger-management/
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
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Square
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  - Microsoft Excel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  id: farm-agriculture
  name: Farm & Agriculture Management
  url: /applications/farm-agriculture/
counts:
  declared: 13
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.farmbrite.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id001
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id002
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://www.farmbrite.com/integrations
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id004
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.farmbrite.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id005
      status: none
    slug: google-sheets
    status: profiled
    tags: &id006
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://www.farmbrite.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 16.2
    mcp: &id007
      status: none
    slug: local-line
    status: profiled
    tags: &id008
    - Agriculture
    - E-Commerce
    - Food Tech
    - Supply Chain
    url: /providers/local-line/
  layer: domain
  name: Local Line
  provider: local-line
  says: lists Local Line as an integration
  source: https://www.farmbrite.com/integrations
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
    mcp: &id009
      status: none
    slug: mailchimp
    status: profiled
    tags: &id010
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.farmbrite.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: strong
    in_catalog: true
    kin_score: 55.8
    mcp: &id011
      status: none
    slug: microsoft-excel
    status: profiled
    tags: &id012
    - Automation
    - Data Analysis
    - Microsoft
    - Microsoft 365
    url: /providers/microsoft-excel/
  layer: common
  name: Microsoft Excel
  provider: microsoft-excel
  says: lists Microsoft Excel as an integration
  source: https://www.farmbrite.com/integrations
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
    mcp: &id013
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id014
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.farmbrite.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id015
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id016
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.farmbrite.com/integrations
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
  source: https://www.farmbrite.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id019
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id020
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: common
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.farmbrite.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id021
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id022
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: common
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://www.farmbrite.com/integrations
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
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id023
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id024
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.farmbrite.com/integrations
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
    mcp: &id025
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id026
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.farmbrite.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/farm-agriculture/farmbrite/
providers:
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id001
  name: Asana
  slug: asana
  status: profiled
  tags: *id002
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id003
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id004
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id005
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id006
  url: /providers/google-sheets/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id007
  name: Local Line
  slug: local-line
  status: profiled
  tags: *id008
  url: /providers/local-line/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id009
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id010
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: strong
  in_catalog: true
  kin_score: 55.8
  mcp: *id011
  name: Microsoft Excel
  slug: microsoft-excel
  status: profiled
  tags: *id012
  url: /providers/microsoft-excel/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id013
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id014
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id015
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id016
  url: /providers/shopify/
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
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id019
  name: Square
  slug: square
  status: profiled
  tags: *id020
  url: /providers/square/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id021
  name: Trello
  slug: trello
  status: profiled
  tags: *id022
  url: /providers/trello/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id023
  name: Xero
  slug: xero
  status: profiled
  tags: *id024
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id025
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id026
  url: /providers/zapier/
siblings:
- name: AgriWebb
  rows: 11
  url: /applications/farm-agriculture/agriwebb/
- name: Agworld
  rows: 17
  url: /applications/farm-agriculture/agworld/
- name: Climate FieldView
  rows: 20
  url: /applications/farm-agriculture/climate-fieldview/
- name: farmOS
  rows: 1
  url: /applications/farm-agriculture/farmos/
- name: LiteFarm
  rows: 8
  url: /applications/farm-agriculture/litefarm/
- name: Open Food Network
  rows: 7
  url: /applications/farm-agriculture/open-food-network/
sitemap: true
title: 'Farmbrite: Farm & Agriculture Management reference app'
---
