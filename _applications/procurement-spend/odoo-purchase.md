---
app: Odoo Purchase
app_slug: odoo-purchase
app_url: https://github.com/odoo/odoo
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-220.20.30
  key: BC-220.20.30
  layer: domain
  name: E-Invoicing and Real-Time Reporting
  providers:
  - Peppol network (OpenPeppol)
  url: /capabilities/indirect-tax-management/
  via_parent: Indirect Tax Management
category:
  id: procurement-spend
  name: Procurement & Spend Management
  url: /applications/procurement-spend/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: source code
  url: https://github.com/odoo/odoo/tree/19.0/addons/account_peppol
integrations:
- capability:
    attribution: Turbo EA
    id: BC-220.20.30
    key: BC-220.20.30
    name: E-Invoicing and Real-Time Reporting
    url: /capabilities/indirect-tax-management/
    via_parent: Indirect Tax Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id001
      status: unchecked
    slug: peppol
    status: profiled
    tags: &id002
    - Digital Trade
    - Interoperability
    - Peppol
    - e-Delivery
    url: /providers/peppol/
  layer: domain
  name: Peppol network (OpenPeppol)
  provider: peppol
  says: ships the Peppol network (OpenPeppol) SDK or integration code
  source: https://github.com/odoo/odoo/tree/19.0/addons/account_peppol
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/procurement-spend/odoo-purchase/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id001
  name: Peppol network (OpenPeppol)
  slug: peppol
  status: profiled
  tags: *id002
  url: /providers/peppol/
siblings:
- name: ERPNext (Buying module)
  rows: 5
  url: /applications/procurement-spend/erpnext-buying-module/
- name: Precoro
  rows: 10
  url: /applications/procurement-spend/precoro/
- name: Procurify
  rows: 10
  url: /applications/procurement-spend/procurify/
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
title: 'Odoo Purchase: Procurement & Spend Management reference app'
---
