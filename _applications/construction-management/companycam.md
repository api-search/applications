---
app: CompanyCam
app_slug: companycam
app_url: https://companycam.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1150
  key: construction-management
  layer: domain
  name: Construction Management
  providers:
  - JobTread
  url: /capabilities/construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - AccuLynx
  - Aspire (Powered by MindCloud)
  - HighLevel
  - JobNimbus
  - LeadPerfection
  - Leap
  - Roofr
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1050
  key: field-service-management
  layer: domain
  name: Field Service Management
  providers:
  - Jobber
  - ServiceTitan
  url: /capabilities/field-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Smartsheet
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-500.30
  key: purchase-order-management
  layer: domain
  name: Purchase Order Management
  providers:
  - SRS Roof Hub
  url: /capabilities/purchase-order-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.20
  key: AE-120.20.20
  layer: domain
  name: Satellite & Aerial Imagery
  providers:
  - Eagleview
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: construction-management
  name: Construction Management
  url: /applications/construction-management/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://companycam.com/integrations
integrations:
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
    agent_readiness: 46.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id001
      status: none
    slug: acculynx
    status: profiled
    tags: &id002
    - CRM
    - Company
    - Roofing
    - Software-as-a-Service
    url: /providers/acculynx/
  layer: domain
  name: AccuLynx
  provider: acculynx
  says: lists AccuLynx as an integration
  source: https://companycam.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.5
    mcp: &id003
      status: unknown
    slug: aspire-software
    status: profiled
    tags: &id004
    - Automation
    - Company
    - Field Service Management
    - Software
    url: /providers/aspire-software/
  layer: domain
  name: Aspire (Powered by MindCloud)
  provider: aspire-software
  says: lists Aspire (Powered by MindCloud) as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.20
    key: AE-120.20.20
    name: Satellite & Aerial Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: developing
    in_catalog: true
    kin_score: 46.8
    mcp: &id005
      status: none
    slug: eagleview
    status: profiled
    tags: &id006
    - Aerial Imagery
    - Data Analytics
    - Geospatial
    - Real Estate
    url: /providers/eagleview/
  layer: domain
  name: Eagleview
  provider: eagleview
  says: lists Eagleview as an integration
  source: https://companycam.com/integrations
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
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id007
      source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
      status: verified
    slug: highlevel
    status: profiled
    tags: &id008
    - CRM
    - Company
    - Marketing
    - Software-as-a-Service
    url: /providers/highlevel/
  layer: domain
  name: HighLevel
  provider: highlevel
  says: lists HighLevel as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1050
    key: field-service-management
    name: Field Service Management
    url: /capabilities/field-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.3
    band: strong
    in_catalog: true
    kin_score: 54.3
    mcp: &id009
      source: https://github.com/GetJobber/grok-bot-mcp
      status: verified
    slug: jobber
    status: profiled
    tags: &id010
    - Field Service Management
    - Home Service
    - Quoting
    - Scheduling
    url: /providers/jobber/
  layer: domain
  name: Jobber
  provider: jobber
  says: lists Jobber as an integration
  source: https://companycam.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.0
    mcp: &id011
      status: unknown
    slug: jobnimbus
    status: profiled
    tags: &id012
    - CRM
    - Contractors
    - Project Management
    - Roofing
    url: /providers/jobnimbus/
  layer: domain
  name: JobNimbus
  provider: jobnimbus
  says: lists JobNimbus as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1150
    key: construction-management
    name: Construction Management
    url: /capabilities/construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 16.5
    mcp: &id013
      status: none
    slug: jobtread
    status: profiled
    tags: &id014
    - Construction
    - Estimating
    - Project Management
    - Software-as-a-Service
    url: /providers/jobtread/
  layer: domain
  name: JobTread
  provider: jobtread
  says: lists JobTread as an integration
  source: https://companycam.com/integrations
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
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id015
      status: unknown
    slug: leadperfection
    status: profiled
    tags: &id016
    - Company
    url: /providers/leadperfection/
  layer: domain
  name: LeadPerfection
  provider: leadperfection
  says: lists LeadPerfection as an integration
  source: https://companycam.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id017
      status: unknown
    slug: leap-to-digital
    status: profiled
    tags: &id018
    - Company
    - Contractor Software
    - Remodeling
    - Roofing
    url: /providers/leap-to-digital/
  layer: domain
  name: Leap
  provider: leap-to-digital
  says: lists Leap as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id019
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id020
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://companycam.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id021
      status: unknown
    slug: roofr
    status: profiled
    tags: &id022
    - Company
    - Construction
    - Roofing
    - Software-as-a-Service
    url: /providers/roofr/
  layer: domain
  name: Roofr
  provider: roofr
  says: lists Roofr as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1050
    key: field-service-management
    name: Field Service Management
    url: /capabilities/field-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id023
      status: none
    slug: servicetitan
    status: profiled
    tags: &id024
    - Field Service Management
    - HVAC
    - Plumbing
    - Trade
    url: /providers/servicetitan/
  layer: domain
  name: ServiceTitan
  provider: servicetitan
  says: lists ServiceTitan as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.1
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id025
      source: https://github.com/smartsheet-platform/smar-mcp
      status: verified
    slug: smartsheet
    status: profiled
    tags: &id026
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/smartsheet/
  layer: domain
  name: Smartsheet
  provider: smartsheet
  says: lists Smartsheet as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-500.30
    key: purchase-order-management
    name: Purchase Order Management
    url: /capabilities/purchase-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id027
      status: unchecked
    slug: srs-distribution
    status: queued for profiling
    tags: &id028 []
    url: null
  layer: domain
  name: SRS Roof Hub
  provider: srs-distribution
  says: lists SRS Roof Hub as an integration
  source: https://companycam.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id029
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id030
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://companycam.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/companycam/
providers:
- agent_band: agent-ready
  agent_readiness: 46.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id001
  name: AccuLynx
  slug: acculynx
  status: profiled
  tags: *id002
  url: /providers/acculynx/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.5
  mcp: *id003
  name: Aspire (Powered by MindCloud)
  slug: aspire-software
  status: profiled
  tags: *id004
  url: /providers/aspire-software/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: developing
  in_catalog: true
  kin_score: 46.8
  mcp: *id005
  name: Eagleview
  slug: eagleview
  status: profiled
  tags: *id006
  url: /providers/eagleview/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id007
  name: HighLevel
  slug: highlevel
  status: profiled
  tags: *id008
  url: /providers/highlevel/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: strong
  in_catalog: true
  kin_score: 54.3
  mcp: *id009
  name: Jobber
  slug: jobber
  status: profiled
  tags: *id010
  url: /providers/jobber/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.0
  mcp: *id011
  name: JobNimbus
  slug: jobnimbus
  status: profiled
  tags: *id012
  url: /providers/jobnimbus/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 16.5
  mcp: *id013
  name: JobTread
  slug: jobtread
  status: profiled
  tags: *id014
  url: /providers/jobtread/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id015
  name: LeadPerfection
  slug: leadperfection
  status: profiled
  tags: *id016
  url: /providers/leadperfection/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id017
  name: Leap
  slug: leap-to-digital
  status: profiled
  tags: *id018
  url: /providers/leap-to-digital/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id019
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id020
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id021
  name: Roofr
  slug: roofr
  status: profiled
  tags: *id022
  url: /providers/roofr/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id023
  name: ServiceTitan
  slug: servicetitan
  status: profiled
  tags: *id024
  url: /providers/servicetitan/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id025
  name: Smartsheet
  slug: smartsheet
  status: profiled
  tags: *id026
  url: /providers/smartsheet/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id027
  name: SRS Roof Hub
  slug: srs-distribution
  status: queued for profiling
  tags: *id028
  url: null
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id029
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id030
  url: /providers/zapier/
siblings:
- name: JobTread
  rows: 11
  url: /applications/construction-management/jobtread/
- name: Knowify
  rows: 9
  url: /applications/construction-management/knowify/
- name: OpenProject (BIM)
  rows: 7
  url: /applications/construction-management/openproject-bim/
- name: Procore
  rows: 12
  url: /applications/construction-management/procore/
- name: Raken
  rows: 21
  url: /applications/construction-management/raken/
- name: Siteline
  rows: 11
  url: /applications/construction-management/siteline/
sitemap: true
title: 'CompanyCam: Construction Management reference app'
---
