---
app: ServiceTitan
app_slug: servicetitan
app_url: https://www.servicetitan.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Desktop/Online
  - Sage Intacct
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
category:
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://help.servicetitan.com/docs/accounting-integrations-overview
integrations:
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
    mcp: &id001
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id002
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Desktop/Online
  provider: quickbooks
  says: lists QuickBooks Desktop/Online as an integration
  source: https://help.servicetitan.com/docs/accounting-integrations-overview
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id003
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id004
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: common
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://help.servicetitan.com/docs/accounting-integrations-overview
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
    mcp: &id005
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id006
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://help.servicetitan.com/docs/accounting-integrations-overview
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/servicetitan/
providers:
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id001
  name: QuickBooks Desktop/Online
  slug: quickbooks
  status: profiled
  tags: *id002
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id003
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id004
  url: /providers/sage-intacct/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id005
  name: Xero
  slug: xero
  status: profiled
  tags: *id006
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
- name: Tradify
  rows: 4
  url: /applications/field-service/tradify/
- name: Workiz
  rows: 16
  url: /applications/field-service/workiz/
sitemap: true
title: 'ServiceTitan: Field Service & Dispatch reference app'
---
