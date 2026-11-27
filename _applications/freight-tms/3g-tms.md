---
app: 3G TMS
app_slug: 3g-tms
app_url: https://www.3gtms.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - IntelliShift
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510
  key: shipment-visibility-tracking-management
  layer: domain
  name: Shipment Visibility & Tracking Management
  providers:
  - Descartes Systems Group
  url: /capabilities/shipment-visibility-tracking-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2420
  key: transport-operations-management
  layer: domain
  name: Transport Operations Management
  providers:
  - PITT OHIO
  url: /capabilities/transport-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Cavallo
  url: /capabilities/general-ledger-management/
  via_parent: null
category:
  id: freight-tms
  name: Freight & Transportation Management
  url: /applications/freight-tms/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.3gtms.com/partners/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id001
      status: unchecked
    slug: cavallo
    status: profiled
    tags: &id002
    - Distribution Software
    - ERP Integration
    - Order-to-Cash
    - Profitability
    url: /providers/cavallo/
  layer: common
  name: Cavallo
  provider: cavallo
  says: lists Cavallo as an integration
  source: https://www.3gtms.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2510
    key: shipment-visibility-tracking-management
    name: Shipment Visibility & Tracking Management
    url: /capabilities/shipment-visibility-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id003
      status: unknown
    slug: descartes
    status: profiled
    tags: &id004
    - Freight Visibility
    - Logistics
    - Shipment Tracking
    - Supply Chain
    url: /providers/descartes/
  layer: domain
  name: Descartes Systems Group
  provider: descartes
  says: lists Descartes Systems Group as an integration
  source: https://www.3gtms.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 15.7
    mcp: &id005
      status: unchecked
    slug: intellishift
    status: profiled
    tags: &id006
    - AI Dashcams
    - Compliance
    - Fleet Management
    - Telematics
    url: /providers/intellishift/
  layer: domain
  name: IntelliShift
  provider: intellishift
  says: lists IntelliShift as an integration
  source: https://www.3gtms.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420
    key: transport-operations-management
    name: Transport Operations Management
    url: /capabilities/transport-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id007
      status: unchecked
    slug: pitt-ohio
    status: profiled
    tags: &id008
    - Company
    url: /providers/pitt-ohio/
  layer: domain
  name: PITT OHIO
  provider: pitt-ohio
  says: lists PITT OHIO as an integration
  source: https://www.3gtms.com/partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/freight-tms/3g-tms/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id001
  name: Cavallo
  slug: cavallo
  status: profiled
  tags: *id002
  url: /providers/cavallo/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id003
  name: Descartes Systems Group
  slug: descartes
  status: profiled
  tags: *id004
  url: /providers/descartes/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 15.7
  mcp: *id005
  name: IntelliShift
  slug: intellishift
  status: profiled
  tags: *id006
  url: /providers/intellishift/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id007
  name: PITT OHIO
  slug: pitt-ohio
  status: profiled
  tags: *id008
  url: /providers/pitt-ohio/
siblings:
- name: Descartes Aljex
  rows: 19
  url: /applications/freight-tms/descartes-aljex/
- name: Fleetbase
  rows: 16
  url: /applications/freight-tms/fleetbase/
- name: Revenova TMS
  rows: 5
  url: /applications/freight-tms/revenova-tms/
- name: Rose Rocket
  rows: 28
  url: /applications/freight-tms/rose-rocket/
sitemap: true
title: '3G TMS: Freight & Transportation Management reference app'
---
