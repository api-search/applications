---
app: JobTread
app_slug: jobtread
app_url: https://www.jobtread.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-500.30
  key: purchase-order-management
  layer: domain
  name: Purchase Order Management
  providers:
  - Heritage Pool Supply Group
  - Home Depot
  - PoolCorp
  - QXO
  - SRS Distribution
  url: /capabilities/purchase-order-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-5060.40.30
  key: BC-5060.40.30
  layer: domain
  name: Reality Capture & Scanning
  providers:
  - RENDR
  url: /capabilities/geospatial-survey-management/
  via_parent: Geospatial & Survey Management
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
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - Gusto
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - NiceJob
  url: /capabilities/reviews-social-proof/
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
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.jobtread.com/integrations
integrations:
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
    agent_readiness: 34.6
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id001
      status: none
    slug: eagleview
    status: profiled
    tags: &id002
    - Aerial Imagery
    - Data Analytics
    - Geospatial
    - Real Estate
    url: /providers/eagleview/
  layer: domain
  name: Eagleview
  provider: eagleview
  says: lists Eagleview as an integration
  source: https://www.jobtread.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id003
      status: none
    slug: gusto
    status: profiled
    tags: &id004
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: common
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://www.jobtread.com/integrations
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
    mcp: &id005
      status: unchecked
    slug: heritage-pool-supply
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: Heritage Pool Supply Group
  provider: heritage-pool-supply
  says: lists Heritage Pool Supply Group as an integration
  source: https://www.jobtread.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 20.2
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id007
      status: none
    slug: home-depot
    status: profiled
    tags: &id008
    - Fortune 100
    url: /providers/home-depot/
  layer: domain
  name: Home Depot
  provider: home-depot
  says: lists Home Depot as an integration
  source: https://www.jobtread.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id009
      status: none
    slug: nicejob
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Reputation Marketing
    - Service Business
    - Software-as-a-Service
    url: /providers/nicejob/
  layer: common
  name: NiceJob
  provider: nicejob
  says: lists NiceJob as an integration
  source: https://www.jobtread.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id011
      status: unknown
    slug: poolcorp
    status: profiled
    tags: &id012
    - Company
    url: /providers/poolcorp/
  layer: domain
  name: PoolCorp
  provider: poolcorp
  says: lists PoolCorp as an integration
  source: https://www.jobtread.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id013
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id014
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.jobtread.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id015
      status: unknown
    slug: qxo-building-products
    status: profiled
    tags: &id016
    - B2B
    - Building Products
    - Construction
    - Distribution
    url: /providers/qxo-building-products/
  layer: domain
  name: QXO
  provider: qxo-building-products
  says: lists QXO as an integration
  source: https://www.jobtread.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-5060.40.30
    key: BC-5060.40.30
    name: Reality Capture & Scanning
    url: /capabilities/geospatial-survey-management/
    via_parent: Geospatial & Survey Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id017
      status: unchecked
    slug: rendr
    status: queued for profiling
    tags: &id018 []
    url: null
  layer: domain
  name: RENDR
  provider: rendr
  says: lists RENDR as an integration
  source: https://www.jobtread.com/integrations
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
    mcp: &id019
      status: unchecked
    slug: srs-distribution
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: SRS Distribution
  provider: srs-distribution
  says: lists SRS Distribution as an integration
  source: https://www.jobtread.com/integrations
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id021
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id022
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.jobtread.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/jobtread/
providers:
- agent_band: agent-ready
  agent_readiness: 34.6
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id001
  name: Eagleview
  slug: eagleview
  status: profiled
  tags: *id002
  url: /providers/eagleview/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id003
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id004
  url: /providers/gusto/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: Heritage Pool Supply Group
  slug: heritage-pool-supply
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-aware
  agent_readiness: 20.2
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id007
  name: Home Depot
  slug: home-depot
  status: profiled
  tags: *id008
  url: /providers/home-depot/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id009
  name: NiceJob
  slug: nicejob
  status: profiled
  tags: *id010
  url: /providers/nicejob/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id011
  name: PoolCorp
  slug: poolcorp
  status: profiled
  tags: *id012
  url: /providers/poolcorp/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id013
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id014
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id015
  name: QXO
  slug: qxo-building-products
  status: profiled
  tags: *id016
  url: /providers/qxo-building-products/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id017
  name: RENDR
  slug: rendr
  status: queued for profiling
  tags: *id018
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: SRS Distribution
  slug: srs-distribution
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id021
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id022
  url: /providers/zapier/
siblings:
- name: CompanyCam
  rows: 15
  url: /applications/construction-management/companycam/
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
title: 'JobTread: Construction Management reference app'
---
