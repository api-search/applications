---
app: Revenova TMS
app_slug: revenova-tms
app_url: https://revenova.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2480.20
  key: customs-declaration-management
  layer: domain
  name: Customs Declaration Management
  providers:
  - BorderConnect
  url: /capabilities/customs-declaration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Drumkit
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2520
  key: freight-rating-tariff-management
  layer: domain
  name: Freight Rating & Tariff Management
  providers:
  - SMC3
  url: /capabilities/freight-rating-tariff-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510
  key: shipment-visibility-tracking-management
  layer: domain
  name: Shipment Visibility & Tracking Management
  providers:
  - OpenTrack
  url: /capabilities/shipment-visibility-tracking-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
category:
  id: freight-tms
  name: Freight & Transportation Management
  url: /applications/freight-tms/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://revenova.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2480.20
    key: customs-declaration-management
    name: Customs Declaration Management
    url: /capabilities/customs-declaration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.7
    mcp: &id001
      status: unchecked
    slug: borderconnect
    status: profiled
    tags: &id002
    - Company
    url: /providers/borderconnect/
  layer: domain
  name: BorderConnect
  provider: borderconnect
  says: lists BorderConnect as an integration
  source: https://revenova.com/integrations/
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
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 17.2
    mcp: &id003
      status: unchecked
    slug: drumkit
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Company
    - Email Integration
    - Logistics
    url: /providers/drumkit/
  layer: domain
  name: Drumkit
  provider: drumkit
  says: lists Drumkit as an integration
  source: https://revenova.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 49.5
    band: developing
    in_catalog: true
    kin_score: 54.0
    mcp: &id005
      status: unchecked
    slug: opentrack
    status: profiled
    tags: &id006
    - API Integration
    - Container Visibility
    - Freight Tracking
    - Logistics Software
    url: /providers/opentrack/
  layer: domain
  name: OpenTrack
  provider: opentrack
  says: lists OpenTrack as an integration
  source: https://revenova.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id007
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id008
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://revenova.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2520
    key: freight-rating-tariff-management
    name: Freight Rating & Tariff Management
    url: /capabilities/freight-rating-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.8
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id009
      status: unchecked
    slug: smc3
    status: profiled
    tags: &id010
    - Company
    - Logistics
    - Pricing
    - Transportation
    url: /providers/smc3/
  layer: domain
  name: SMC3
  provider: smc3
  says: lists SMC3 as an integration
  source: https://revenova.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/freight-tms/revenova-tms/
providers:
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id001
  name: BorderConnect
  slug: borderconnect
  status: profiled
  tags: *id002
  url: /providers/borderconnect/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 17.2
  mcp: *id003
  name: Drumkit
  slug: drumkit
  status: profiled
  tags: *id004
  url: /providers/drumkit/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: developing
  in_catalog: true
  kin_score: 54.0
  mcp: *id005
  name: OpenTrack
  slug: opentrack
  status: profiled
  tags: *id006
  url: /providers/opentrack/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id007
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id008
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id009
  name: SMC3
  slug: smc3
  status: profiled
  tags: *id010
  url: /providers/smc3/
siblings:
- name: 3G TMS
  rows: 4
  url: /applications/freight-tms/3g-tms/
- name: Descartes Aljex
  rows: 19
  url: /applications/freight-tms/descartes-aljex/
- name: Fleetbase
  rows: 16
  url: /applications/freight-tms/fleetbase/
- name: Rose Rocket
  rows: 28
  url: /applications/freight-tms/rose-rocket/
sitemap: true
title: 'Revenova TMS: Freight & Transportation Management reference app'
---
