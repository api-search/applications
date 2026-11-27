---
app: FreshBooks
app_slug: freshbooks
app_url: https://www.freshbooks.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: accounting-invoicing
  name: Accounting & Invoicing
  url: /applications/accounting-invoicing/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
- route: integrations page
  url: https://www.freshbooks.com/payments
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: Adjust
  provider: adjust
  says: ships the Adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id004
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id005
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id006
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id007
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id008
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/accounting-invoicing/freshbooks/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id005
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id006
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id007
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id008
  url: /providers/google-tag-manager/
siblings:
- name: Akaunting
  rows: 7
  url: /applications/accounting-invoicing/akaunting/
- name: Crater
  rows: 2
  url: /applications/accounting-invoicing/crater/
- name: ERPNext
  rows: 3
  url: /applications/accounting-invoicing/erpnext/
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
title: 'FreshBooks: Accounting & Invoicing reference app'
---
