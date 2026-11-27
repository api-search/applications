---
app: InvenTree
app_slug: inventree
app_url: https://github.com/inventree/InvenTree
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1930
  key: electronic-component-sourcing-management
  layer: domain
  name: Electronic Component Sourcing Management
  providers:
  - Digi-Key
  - LCSC Electronics
  - Mouser Electronics
  - TME (Transfer Multisort Elektronik)
  url: /capabilities/electronic-component-sourcing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - Frankfurter
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Postal (postalserver.io)
  url: /capabilities/email/
  via_parent: Email
category:
  id: inventory-warehouse
  name: Inventory & Warehouse Management
  url: /applications/inventory-warehouse/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
- route: source code
  url: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
- route: source code
  url: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/InvenTree/plugin/builtin/integration/currency_exchange.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id001
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id003
      status: none
    slug: digi-key
    status: profiled
    tags: &id004
    - Distribution
    - Electronic Components
    - Public APIs
    - Shopping
    url: /providers/digi-key/
  layer: domain
  name: Digi-Key
  provider: digi-key
  says: ships the Digi-Key SDK or integration code
  source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 46.7
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id005
      source: https://github.com/lineofflight/frankfurter-mcp
      status: verified
    slug: frankfurter
    status: profiled
    tags: &id006
    - Foreign Exchange
    - MIT
    - Open Source
    - Self-Hosted
    url: /providers/frankfurter/
  layer: domain
  name: Frankfurter
  provider: frankfurter
  says: ships the Frankfurter SDK or integration code
  source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/InvenTree/plugin/builtin/integration/currency_exchange.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.8
    mcp: &id007
      status: unknown
    slug: lcsc
    status: profiled
    tags: &id008
    - Company
    - Components
    - Distributor
    - Electronics
    url: /providers/lcsc/
  layer: domain
  name: LCSC Electronics
  provider: lcsc
  says: ships the LCSC Electronics SDK or integration code
  source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.8
    mcp: &id009
      status: none
    slug: mouser
    status: profiled
    tags: &id010
    - Company
    url: /providers/mouser/
  layer: domain
  name: Mouser Electronics
  provider: mouser
  says: ships the Mouser Electronics SDK or integration code
  source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id011
      status: none
    slug: postal-server
    status: profiled
    tags: &id012
    - DevOps
    - Docker
    - Installations
    - Open Source
    url: /providers/postal-server/
  layer: common
  name: Postal (postalserver.io)
  provider: postal-server
  says: ships the Postal (postalserver.io) SDK or integration code
  source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.7
    band: emerging
    in_catalog: true
    kin_score: 17.0
    mcp: &id015
      status: unknown
    slug: tme
    status: profiled
    tags: &id016
    - Company
    url: /providers/tme/
  layer: domain
  name: TME (Transfer Multisort Elektronik)
  provider: tme
  says: ships the TME (Transfer Multisort Elektronik) SDK or integration code
  source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/inventory-warehouse/inventree/
providers:
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id003
  name: Digi-Key
  slug: digi-key
  status: profiled
  tags: *id004
  url: /providers/digi-key/
- agent_band: agent-native
  agent_readiness: 46.7
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id005
  name: Frankfurter
  slug: frankfurter
  status: profiled
  tags: *id006
  url: /providers/frankfurter/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.8
  mcp: *id007
  name: LCSC Electronics
  slug: lcsc
  status: profiled
  tags: *id008
  url: /providers/lcsc/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.8
  mcp: *id009
  name: Mouser Electronics
  slug: mouser
  status: profiled
  tags: *id010
  url: /providers/mouser/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id011
  name: Postal (postalserver.io)
  slug: postal-server
  status: profiled
  tags: *id012
  url: /providers/postal-server/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: emerging
  in_catalog: true
  kin_score: 17.0
  mcp: *id015
  name: TME (Transfer Multisort Elektronik)
  slug: tme
  status: profiled
  tags: *id016
  url: /providers/tme/
siblings:
- name: Cin7
  rows: 15
  url: /applications/inventory-warehouse/cin7/
- name: inFlow Inventory
  rows: 24
  url: /applications/inventory-warehouse/inflow-inventory/
- name: Part-DB
  rows: 20
  url: /applications/inventory-warehouse/part-db/
- name: Shelf
  rows: 5
  url: /applications/inventory-warehouse/shelf/
- name: Snipe-IT
  rows: 5
  url: /applications/inventory-warehouse/snipe-it/
- name: Sortly
  rows: 3
  url: /applications/inventory-warehouse/sortly/
- name: Zoho Inventory
  rows: 0
  url: /applications/inventory-warehouse/zoho-inventory/
sitemap: true
title: 'InvenTree: Inventory & Warehouse Management reference app'
---
