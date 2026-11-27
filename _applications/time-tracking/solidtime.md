---
app: solidtime
app_slug: solidtime
app_url: https://github.com/solidtime-io/solidtime
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4330.10
  key: timekeeping-management
  layer: domain
  name: Timekeeping Management
  providers:
  - Clockify importer
  - Harvest importer
  - Toggl Track importer
  url: /capabilities/timekeeping-management/
  via_parent: null
category:
  id: time-tracking
  name: Time Tracking & Timesheets
  url: /applications/time-tracking/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/solidtime-io/solidtime/main/composer.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/solidtime-io/solidtime/main/package.json
- route: source code
  url: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
- route: source code
  url: https://raw.githubusercontent.com/solidtime-io/solidtime/main/.env.example
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id001
      status: none
    slug: clockify
    status: profiled
    tags: &id002
    - Productivity
    - Project Management
    - Time Tracking
    - Timesheets
    url: /providers/clockify/
  layer: domain
  name: Clockify importer
  provider: clockify
  says: ships the Clockify importer SDK or integration code
  source: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.0
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id003
      status: none
    slug: harvest
    status: profiled
    tags: &id004
    - Expense Tracking
    - Invoicing
    - Project Management
    - Time Tracking
    url: /providers/harvest/
  layer: domain
  name: Harvest importer
  provider: harvest
  says: ships the Harvest importer SDK or integration code
  source: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id005
      source: https://registry.modelcontextprotocol.io/v0/servers?search=toggl
      status: verified
    slug: toggl
    status: profiled
    tags: &id006
    - Billing
    - Productivity
    - Project Management
    - Time Tracking
    url: /providers/toggl/
  layer: domain
  name: Toggl Track importer
  provider: toggl
  says: ships the Toggl Track importer SDK or integration code
  source: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/time-tracking/solidtime/
providers:
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id001
  name: Clockify importer
  slug: clockify
  status: profiled
  tags: *id002
  url: /providers/clockify/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id003
  name: Harvest importer
  slug: harvest
  status: profiled
  tags: *id004
  url: /providers/harvest/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id005
  name: Toggl Track importer
  slug: toggl
  status: profiled
  tags: *id006
  url: /providers/toggl/
siblings:
- name: Clockify
  rows: 29
  url: /applications/time-tracking/clockify/
- name: Harvest
  rows: 28
  url: /applications/time-tracking/harvest/
- name: Kimai
  rows: 3
  url: /applications/time-tracking/kimai/
- name: Super Productivity
  rows: 16
  url: /applications/time-tracking/super-productivity/
- name: Toggl Track
  rows: 24
  url: /applications/time-tracking/toggl-track/
sitemap: true
title: 'solidtime: Time Tracking & Timesheets reference app'
---
