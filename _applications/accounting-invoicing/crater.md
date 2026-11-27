---
app: Crater
app_slug: crater
app_url: https://github.com/crater-invoice/crater
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon Web Services
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.60
  key: tenant-backup-export-management
  layer: common
  name: Tenant Backup & Export Management
  providers:
  - Dropbox
  url: /capabilities/tenant-backup-export-management/
  via_parent: null
category:
  id: accounting-invoicing
  name: Accounting & Invoicing
  url: /applications/accounting-invoicing/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
- route: documentation
  url: https://docs.craterapp.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services
  provider: amazon-web-services
  says: ships the Amazon Web Services SDK or integration code
  source: https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.60
    key: tenant-backup-export-management
    name: Tenant Backup & Export Management
    url: /capabilities/tenant-backup-export-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id003
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id004
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/accounting-invoicing/crater/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: Amazon Web Services
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id003
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id004
  url: /providers/dropbox/
siblings:
- name: Akaunting
  rows: 7
  url: /applications/accounting-invoicing/akaunting/
- name: ERPNext
  rows: 3
  url: /applications/accounting-invoicing/erpnext/
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
title: 'Crater: Accounting & Invoicing reference app'
---
