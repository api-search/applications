---
app: Tradify
app_slug: tradify
app_url: https://www.tradifyhq.com/
author: API Evangelist
capabilities:
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
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.tradifyhq.com/features/integrations
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id001
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id002
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.tradifyhq.com/features/integrations
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
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.tradifyhq.com/features/integrations
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
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id005
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id006
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.tradifyhq.com/features/integrations
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
    mcp: &id007
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id008
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.tradifyhq.com/features/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/tradify/
providers:
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id001
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id002
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id003
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id004
  url: /providers/quickbooks/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id005
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id006
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id007
  name: Xero
  slug: xero
  status: profiled
  tags: *id008
  url: /providers/xero/
siblings:
- name: Housecall Pro
  rows: 26
  url: /applications/field-service/housecall-pro/
- name: Jobber
  rows: 34
  url: /applications/field-service/jobber/
- name: OCA Field Service (Odoo)
  rows: 1
  url: /applications/field-service/oca-field-service-odoo/
- name: ServiceM8
  rows: 8
  url: /applications/field-service/servicem8/
- name: ServiceTitan
  rows: 3
  url: /applications/field-service/servicetitan/
- name: Workiz
  rows: 16
  url: /applications/field-service/workiz/
sitemap: true
title: 'Tradify: Field Service & Dispatch reference app'
---
