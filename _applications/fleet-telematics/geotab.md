---
app: Geotab
app_slug: geotab
app_url: https://www.geotab.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2430
  key: fleet-mobile-asset-management
  layer: domain
  name: Fleet & Mobile Asset Management
  providers:
  - Link Labs (AirFinder)
  - ORBCOMM (VIACHAIN)
  url: /capabilities/fleet-mobile-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Lytx (Surfsight)
  - Xirgo
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2160
  key: insurance-claims-management
  layer: domain
  name: Insurance Claims Management
  providers:
  - Xtract360
  url: /capabilities/insurance-claims-management/
  via_parent: null
category:
  id: fleet-telematics
  name: Fleet Management & Telematics
  url: /applications/fleet-telematics/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://marketplace.geotab.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2430
    key: fleet-mobile-asset-management
    name: Fleet & Mobile Asset Management
    url: /capabilities/fleet-mobile-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: link-labs
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Link Labs (AirFinder)
  provider: link-labs
  says: lists Link Labs (AirFinder) as an integration
  source: https://marketplace.geotab.com/
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
    agent_band: agent-ready
    agent_readiness: 47.2
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id003
      status: unknown
    slug: lytx
    status: profiled
    tags: &id004
    - Company
    - Fleet Management
    - Vehicle Safety
    - Video Telematics
    url: /providers/lytx/
  layer: domain
  name: Lytx (Surfsight)
  provider: lytx
  says: lists Lytx (Surfsight) as an integration
  source: https://marketplace.geotab.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2430
    key: fleet-mobile-asset-management
    name: Fleet & Mobile Asset Management
    url: /capabilities/fleet-mobile-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id005
      status: unchecked
    slug: orbcomm
    status: profiled
    tags: &id006
    - Asset Tracking
    - Connectivity
    - Fleet Management
    - IoT
    url: /providers/orbcomm/
  layer: domain
  name: ORBCOMM (VIACHAIN)
  provider: orbcomm
  says: lists ORBCOMM (VIACHAIN) as an integration
  source: https://marketplace.geotab.com/
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
    kin_score: 14.7
    mcp: &id007
      status: unchecked
    slug: xirgo
    status: profiled
    tags: &id008
    - Fleet Management
    - IoT
    - Logistics
    - Telematics
    url: /providers/xirgo/
  layer: domain
  name: Xirgo
  provider: xirgo
  says: lists Xirgo as an integration
  source: https://marketplace.geotab.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id009
      status: unchecked
    slug: xtract360
    status: profiled
    tags: &id010
    - Claims
    - Company
    - Fleet Management
    - Insurance
    url: /providers/xtract360/
  layer: domain
  name: Xtract360
  provider: xtract360
  says: lists Xtract360 as an integration
  source: https://marketplace.geotab.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fleet-telematics/geotab/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Link Labs (AirFinder)
  slug: link-labs
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 47.2
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id003
  name: Lytx (Surfsight)
  slug: lytx
  status: profiled
  tags: *id004
  url: /providers/lytx/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id005
  name: ORBCOMM (VIACHAIN)
  slug: orbcomm
  status: profiled
  tags: *id006
  url: /providers/orbcomm/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id007
  name: Xirgo
  slug: xirgo
  status: profiled
  tags: *id008
  url: /providers/xirgo/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id009
  name: Xtract360
  slug: xtract360
  status: profiled
  tags: *id010
  url: /providers/xtract360/
siblings:
- name: Fleetbase
  rows: 15
  url: /applications/fleet-telematics/fleetbase/
- name: Fleetio
  rows: 11
  url: /applications/fleet-telematics/fleetio/
- name: Motive
  rows: 14
  url: /applications/fleet-telematics/motive/
- name: Samsara
  rows: 12
  url: /applications/fleet-telematics/samsara/
- name: Traccar
  rows: 36
  url: /applications/fleet-telematics/traccar/
sitemap: true
title: 'Geotab: Fleet Management & Telematics reference app'
---
