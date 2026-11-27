---
app: CosmoLex
app_slug: cosmolex
app_url: https://www.cosmolex.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-150
  key: legal-management
  layer: domain
  name: Legal Management
  providers:
  - Orion Law
  - Rocket Matter
  url: /capabilities/legal-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330
  key: time-and-engagement-billing-management
  layer: domain
  name: Time and Engagement Billing Management
  providers:
  - Tabs3
  url: /capabilities/time-and-engagement-billing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.10
  key: timekeeping-management
  layer: domain
  name: Timekeeping Management
  providers:
  - TimeSolv
  url: /capabilities/timekeeping-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Office 365
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 6
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.cosmolex.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id001
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id002
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.cosmolex.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id003
      source: https://learn.microsoft.com/en-us/microsoft-agent-365/tooling-servers-overview
      status: verified
    slug: microsoft-office-365
    status: profiled
    tags: &id004
    - Cloud
    - Collaboration
    - Enterprise
    - Microsoft
    url: /providers/microsoft-office-365/
  layer: common
  name: Office 365
  provider: microsoft-office-365
  says: lists Office 365 as an integration
  source: https://www.cosmolex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id005
      status: none
    slug: orion-law
    status: profiled
    tags: &id006
    - Law
    - Legal Tech
    - Software
    - Software-as-a-Service
    url: /providers/orion-law/
  layer: domain
  name: Orion Law
  provider: orion-law
  says: lists Orion Law as an integration
  source: https://www.cosmolex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 42.1
    mcp: &id007
      status: unknown
    slug: rocket-matter
    status: profiled
    tags: &id008
    - Company
    - Legal Tech
    - Practice Management
    - Software-as-a-Service
    url: /providers/rocket-matter/
  layer: domain
  name: Rocket Matter
  provider: rocket-matter
  says: lists Rocket Matter as an integration
  source: https://www.cosmolex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330
    key: time-and-engagement-billing-management
    name: Time and Engagement Billing Management
    url: /capabilities/time-and-engagement-billing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id009
      status: unknown
    slug: tabs3
    status: profiled
    tags: &id010
    - Company
    - Legal Tech
    - Practice Management
    - Software-as-a-Service
    url: /providers/tabs3/
  layer: domain
  name: Tabs3
  provider: tabs3
  says: lists Tabs3 as an integration
  source: https://www.cosmolex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id011
      status: unknown
    slug: timesolv
    status: profiled
    tags: &id012
    - Billing
    - Company
    - Legal Tech
    - Time Tracking
    url: /providers/timesolv/
  layer: domain
  name: TimeSolv
  provider: timesolv
  says: lists TimeSolv as an integration
  source: https://www.cosmolex.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/cosmolex/
providers:
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id001
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id002
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id003
  name: Office 365
  slug: microsoft-office-365
  status: profiled
  tags: *id004
  url: /providers/microsoft-office-365/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id005
  name: Orion Law
  slug: orion-law
  status: profiled
  tags: *id006
  url: /providers/orion-law/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 42.1
  mcp: *id007
  name: Rocket Matter
  slug: rocket-matter
  status: profiled
  tags: *id008
  url: /providers/rocket-matter/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id009
  name: Tabs3
  slug: tabs3
  status: profiled
  tags: *id010
  url: /providers/tabs3/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id011
  name: TimeSolv
  slug: timesolv
  status: profiled
  tags: *id012
  url: /providers/timesolv/
siblings:
- name: ArkCase
  rows: 8
  url: /applications/legal-practice/arkcase/
- name: Clio
  rows: 0
  url: /applications/legal-practice/clio/
- name: Filevine
  rows: 5
  url: /applications/legal-practice/filevine/
- name: Lawmatics
  rows: 29
  url: /applications/legal-practice/lawmatics/
- name: MyCase
  rows: 28
  url: /applications/legal-practice/mycase/
- name: PracticePanther
  rows: 19
  url: /applications/legal-practice/practicepanther/
- name: Smokeball
  rows: 4
  url: /applications/legal-practice/smokeball/
sitemap: true
title: 'CosmoLex: Legal Practice Management reference app'
---
