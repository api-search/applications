---
app: QloApps
app_slug: qloapps
app_url: https://github.com/Qloapps/QloApps
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Duitku
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4010
  key: travel-distribution-channel-management
  layer: domain
  name: Travel Distribution & Channel Management
  providers:
  - Google Hotel Center
  url: /capabilities/travel-distribution-channel-management/
  via_parent: null
category:
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: source code
  url: https://github.com/Qloapps/QloApps/tree/develop/modules
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.1
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id001
      status: unknown
    slug: duitku
    status: profiled
    tags: &id002
    - Company
    - Fintech
    - Indonesia
    - Payments
    url: /providers/duitku/
  layer: domain
  name: Duitku
  provider: duitku
  says: ships the Duitku SDK or integration code
  source: https://github.com/Qloapps/QloApps/tree/develop/modules/qloduitkupayment
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
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
  layer: domain
  name: Google Hotel Center
  provider: google
  says: ships the Google Hotel Center SDK or integration code
  source: https://github.com/Qloapps/QloApps/tree/develop/modules/qlogooglehotelconnector
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id005
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id006
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/Qloapps/QloApps/tree/develop/modules/qlopaypalcommerce
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hospitality-restaurant-ops/qloapps/
providers:
- agent_band: human-only
  agent_readiness: 1.1
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id001
  name: Duitku
  slug: duitku
  status: profiled
  tags: *id002
  url: /providers/duitku/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id003
  name: Google Hotel Center
  slug: google
  status: profiled
  tags: *id004
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id005
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id006
  url: /providers/paypal/
siblings:
- name: 7shifts
  rows: 12
  url: /applications/hospitality-restaurant-ops/7shifts/
- name: apaleo
  rows: 5
  url: /applications/hospitality-restaurant-ops/apaleo/
- name: Cloudbeds
  rows: 3
  url: /applications/hospitality-restaurant-ops/cloudbeds/
- name: MarketMan
  rows: 31
  url: /applications/hospitality-restaurant-ops/marketman/
- name: Mews
  rows: 11
  url: /applications/hospitality-restaurant-ops/mews/
- name: TastyIgniter
  rows: 11
  url: /applications/hospitality-restaurant-ops/tastyigniter/
sitemap: true
title: 'QloApps: Hotel & Restaurant Operations reference app'
---
