---
app: Procurify
app_slug: procurify
app_url: https://www.procurify.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Microsoft Dynamics 365 Business Central
  - NetSuite
  - QuickBooks
  - Sage Intacct
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-957
  key: AE-957
  layer: domain
  name: PunchOut Catalog Commerce
  providers:
  - Amazon Business
  - Grainger
  - Home Depot
  - Staples Advantage
  - Uline
  - ZAGENO
  url: /capabilities/purchase-order-management/
  via_parent: Purchase Order Management
category:
  id: procurement-spend
  name: Procurement & Spend Management
  url: /applications/procurement-spend/
counts:
  declared: 10
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.procurify.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.7
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id001
      source: https://docs.business.amazon.com/
      status: documented
    slug: amazon-business
    status: profiled
    tags: &id002
    - B2B
    - Company
    - Marketplace
    - Procurement
    url: /providers/amazon-business/
  layer: domain
  name: Amazon Business
  provider: amazon-business
  says: lists Amazon Business as an integration
  source: https://www.procurify.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id003
      status: unknown
    slug: ww-grainger
    status: profiled
    tags: &id004
    - Distribution
    - Fortune 500
    - Industrial Supply
    - MRO
    url: /providers/ww-grainger/
  layer: domain
  name: Grainger
  provider: ww-grainger
  says: lists Grainger as an integration
  source: https://www.procurify.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id005
      status: none
    slug: home-depot
    status: profiled
    tags: &id006
    - Fortune 100
    url: /providers/home-depot/
  layer: domain
  name: Home Depot
  provider: home-depot
  says: lists Home Depot as an integration
  source: https://www.procurify.com/integrations/
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id007
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id008
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: domain
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://www.procurify.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id009
      status: none
    slug: netsuite
    status: profiled
    tags: &id010
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: NetSuite
  provider: netsuite
  says: lists NetSuite as an integration
  source: https://www.procurify.com/integrations/
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
    mcp: &id011
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id012
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.procurify.com/integrations/
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
    mcp: &id013
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id014
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.procurify.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id015
      status: none
    slug: staples
    status: profiled
    tags: &id016
    - B2B
    - Office Supplies
    - Procurement
    - Retail
    url: /providers/staples/
  layer: domain
  name: Staples Advantage
  provider: staples
  says: lists Staples Advantage as an integration
  source: https://www.procurify.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id017
      status: unchecked
    slug: uline
    status: profiled
    tags: &id018
    - Company
    - Industrial Supplies
    - Packaging
    - Shipping
    url: /providers/uline/
  layer: domain
  name: Uline
  provider: uline
  says: lists Uline as an integration
  source: https://www.procurify.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 8.5
    band: emerging
    in_catalog: true
    kin_score: 14.9
    mcp: &id019
      status: none
    slug: zageno
    status: profiled
    tags: &id020
    - Company
    - Life Sciences
    - Marketplace
    - Procurement
    url: /providers/zageno/
  layer: domain
  name: ZAGENO
  provider: zageno
  says: lists ZAGENO as an integration
  source: https://www.procurify.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/procurement-spend/procurify/
providers:
- agent_band: agent-aware
  agent_readiness: 26.7
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id001
  name: Amazon Business
  slug: amazon-business
  status: profiled
  tags: *id002
  url: /providers/amazon-business/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id003
  name: Grainger
  slug: ww-grainger
  status: profiled
  tags: *id004
  url: /providers/ww-grainger/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id005
  name: Home Depot
  slug: home-depot
  status: profiled
  tags: *id006
  url: /providers/home-depot/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id007
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id008
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id009
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id010
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id011
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id012
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id013
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id014
  url: /providers/sage-intacct/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id015
  name: Staples Advantage
  slug: staples
  status: profiled
  tags: *id016
  url: /providers/staples/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id017
  name: Uline
  slug: uline
  status: profiled
  tags: *id018
  url: /providers/uline/
- agent_band: agent-aware
  agent_readiness: 8.5
  band: emerging
  in_catalog: true
  kin_score: 14.9
  mcp: *id019
  name: ZAGENO
  slug: zageno
  status: profiled
  tags: *id020
  url: /providers/zageno/
siblings:
- name: ERPNext (Buying module)
  rows: 5
  url: /applications/procurement-spend/erpnext-buying-module/
- name: Odoo Purchase
  rows: 1
  url: /applications/procurement-spend/odoo-purchase/
- name: Precoro
  rows: 10
  url: /applications/procurement-spend/precoro/
- name: Spendflo
  rows: 46
  url: /applications/procurement-spend/spendflo/
- name: Tradogram
  rows: 32
  url: /applications/procurement-spend/tradogram/
- name: Vendr
  rows: 20
  url: /applications/procurement-spend/vendr/
sitemap: true
title: 'Procurify: Procurement & Spend Management reference app'
---
