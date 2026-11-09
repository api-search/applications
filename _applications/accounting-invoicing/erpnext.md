---
app: ERPNext
app_slug: erpnext
app_url: https://github.com/frappe/erpnext
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1380.70
  key: reconciliation-management
  layer: domain
  name: Reconciliation Management
  providers:
  - Plaid
  url: /capabilities/reconciliation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10
  key: AE-120.10
  layer: common
  name: Geocoding
  providers:
  - Google Maps
  url: /capabilities/geocoding/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - YouTube
  url: /capabilities/media-asset-management/
  via_parent: null
category:
  id: accounting-invoicing
  name: Accounting & Invoicing
  url: /applications/accounting-invoicing/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
- route: documentation
  url: https://docs.frappe.io/erpnext/user/manual/en/payment-gateways
- route: source code
  url: https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id001
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id002
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1380.70
    key: reconciliation-management
    name: Reconciliation Management
    url: /capabilities/reconciliation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 52.1
    band: exemplar
    in_catalog: true
    kin_score: 83.4
    mcp: &id003
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id004
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: ships the Plaid SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id005
      status: none
    slug: youtube
    status: profiled
    tags: &id006
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: common
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/accounting-invoicing/erpnext/
providers:
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id001
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id002
  url: /providers/google-maps/
- agent_band: agent-native
  agent_readiness: 52.1
  band: exemplar
  in_catalog: true
  kin_score: 83.4
  mcp: *id003
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id004
  url: /providers/plaid/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id005
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id006
  url: /providers/youtube/
siblings:
- name: Akaunting
  rows: 7
  url: /applications/accounting-invoicing/akaunting/
- name: Crater
  rows: 2
  url: /applications/accounting-invoicing/crater/
- name: FreshBooks
  rows: 4
  url: /applications/accounting-invoicing/freshbooks/
- name: Invoice Ninja
  rows: 42
  url: /applications/accounting-invoicing/invoice-ninja/
- name: QuickBooks
  rows: 9
  url: /applications/accounting-invoicing/quickbooks/
- name: SolidInvoice
  rows: 30
  url: /applications/accounting-invoicing/solidinvoice/
- name: Xero
  rows: 8
  url: /applications/accounting-invoicing/xero/
- name: Zoho Invoice
  rows: 14
  url: /applications/accounting-invoicing/zoho-invoice/
sitemap: true
title: 'ERPNext: Accounting & Invoicing reference app'
---
