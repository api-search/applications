---
app: Open Salon
app_slug: open-salon
app_url: https://github.com/clawnify/open-salon
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Cloudflare D1
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: common
  name: Serverless Functions
  providers:
  - Cloudflare Workers
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/clawnify/open-salon/blob/main/package.json
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id001
      source: https://github.com/cloudflare/mcp-server-cloudflare
      status: verified
    slug: cloudflare-d1
    status: profiled
    tags: &id002
    - Database
    - Edge Computing
    - SQLite
    - Serverless
    url: /providers/cloudflare-d1/
  layer: common
  name: Cloudflare D1
  provider: cloudflare-d1
  says: ships the Cloudflare D1 SDK or integration code
  source: https://github.com/clawnify/open-salon/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id003
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id004
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare Workers
  provider: cloudflare
  says: ships the Cloudflare Workers SDK or integration code
  source: https://github.com/clawnify/open-salon/blob/main/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/open-salon/
providers:
- agent_band: agent-ready
  agent_readiness: 30.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id001
  name: Cloudflare D1
  slug: cloudflare-d1
  status: profiled
  tags: *id002
  url: /providers/cloudflare-d1/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id003
  name: Cloudflare Workers
  slug: cloudflare
  status: profiled
  tags: *id004
  url: /providers/cloudflare/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Boulevard
  rows: 16
  url: /applications/salon-spa-management/boulevard/
- name: Fresha
  rows: 6
  url: /applications/salon-spa-management/fresha/
- name: Mindbody
  rows: 22
  url: /applications/salon-spa-management/mindbody/
- name: Salon Booking System
  rows: 44
  url: /applications/salon-spa-management/salon-booking-system/
- name: Square Appointments
  rows: 32
  url: /applications/salon-spa-management/square-appointments/
- name: Vagaro
  rows: 2
  url: /applications/salon-spa-management/vagaro/
sitemap: true
title: 'Open Salon: Salon & Spa Management reference app'
---
