---
app: QloApps
app_slug: qloapps
app_url: https://github.com/Qloapps/QloApps
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4010.40
  key: metasearch-distribution-management
  layer: domain
  name: Metasearch Distribution Management
  providers:
  - Google Hotel Ads
  url: /capabilities/metasearch-distribution-management/
  via_parent: null
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
category:
  id: hotel-pms
  name: Hotel Property Management
  url: /applications/hotel-pms/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/Qloapps/QloApps/develop/composer.json
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
  source: https://github.com/Qloapps/QloApps/tree/develop/modules
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4010.40
    key: metasearch-distribution-management
    name: Metasearch Distribution Management
    url: /capabilities/metasearch-distribution-management/
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
  name: Google Hotel Ads
  provider: google
  says: ships the Google Hotel Ads SDK or integration code
  source: https://github.com/Qloapps/QloApps/tree/develop/modules
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
  source: https://github.com/Qloapps/QloApps/tree/develop/modules
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hotel-pms/qloapps/
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
  name: Google Hotel Ads
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
- name: apaleo
  rows: 8
  url: /applications/hotel-pms/apaleo/
- name: Beds24
  rows: 12
  url: /applications/hotel-pms/beds24/
- name: Cloudbeds
  rows: 16
  url: /applications/hotel-pms/cloudbeds/
- name: Hotelogix
  rows: 32
  url: /applications/hotel-pms/hotelogix/
- name: Mews
  rows: 13
  url: /applications/hotel-pms/mews/
sitemap: true
title: 'QloApps: Hotel Property Management reference app'
---
