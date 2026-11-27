---
app: Knowify
app_slug: knowify
app_url: https://www.knowify.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-150.10
  key: contract-management
  layer: domain
  name: Contract Management
  providers:
  - AIA Contract Documents
  url: /capabilities/contract-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.80.40
  key: BC-300.80.40
  layer: domain
  name: Employment Law Compliance
  providers:
  - eBacon
  - Lumber
  url: /capabilities/employee-labour-relations/
  via_parent: Employee & Labour Relations
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - CompanyCam
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: Turbo EA
  id: BC-1350.40
  key: BC-1350.40
  layer: domain
  name: Supply Chain Finance Management
  providers:
  - Billd
  url: /capabilities/supply-chain-finance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.30
  key: accounts-receivable-management
  layer: common
  name: Accounts Receivable Management
  providers:
  - QuickBooks Payments
  url: /capabilities/accounts-receivable-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Online / Desktop / Enterprise Suite
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - QuickBooks Online Payroll / QuickBooks Time
  url: /capabilities/human-capital-management/
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
  declared: 9
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.knowify.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 20.3
    mcp: &id002
      status: unknown
    slug: aia-contract-documents
    status: profiled
    tags: &id003
    - Architecture
    - Company
    - Construction
    - Contracts
    url: /providers/aia-contract-documents/
  layer: domain
  name: AIA Contract Documents
  provider: aia-contract-documents
  says: lists AIA Contract Documents as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1350.40
    key: BC-1350.40
    name: Supply Chain Finance Management
    url: /capabilities/supply-chain-finance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.0
    mcp: &id004
      status: unknown
    slug: billd
    status: profiled
    tags: &id005
    - Construction
    - Financing
    - Subcontractors
    - Working Capital
    url: /providers/billd/
  layer: domain
  name: Billd
  provider: billd
  says: lists Billd as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id006
      status: none
    slug: companycam
    status: profiled
    tags: &id007
    - Company
    - Construction
    - Field Service Management
    - Photos
    url: /providers/companycam/
  layer: domain
  name: CompanyCam
  provider: companycam
  says: lists CompanyCam as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.80.40
    key: BC-300.80.40
    name: Employment Law Compliance
    url: /capabilities/employee-labour-relations/
    via_parent: Employee & Labour Relations
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id008
      status: unknown
    slug: ebacon
    status: profiled
    tags: &id009
    - Compliance
    - Construction
    - Payroll
    - Software
    url: /providers/ebacon/
  layer: domain
  name: eBacon
  provider: ebacon
  says: lists eBacon as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.80.40
    key: BC-300.80.40
    name: Employment Law Compliance
    url: /capabilities/employee-labour-relations/
    via_parent: Employee & Labour Relations
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.5
    mcp: &id010
      status: unknown
    slug: lumber
    status: profiled
    tags: &id011
    - Company
    - Construction
    - Payroll
    - Workforce Management
    url: /providers/lumber/
  layer: domain
  name: Lumber
  provider: lumber
  says: lists Lumber as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id012
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id013
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online / Desktop / Enterprise Suite
  provider: quickbooks
  says: lists QuickBooks Online / Desktop / Enterprise Suite as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: QuickBooks Online Payroll / QuickBooks Time
  provider: quickbooks
  says: lists QuickBooks Online Payroll / QuickBooks Time as an integration
  source: https://www.knowify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.30
    key: accounts-receivable-management
    name: Accounts Receivable Management
    url: /capabilities/accounts-receivable-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: QuickBooks Payments
  provider: quickbooks
  says: lists QuickBooks Payments as an integration
  source: https://www.knowify.com/integrations
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
    mcp: &id014
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id015
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.knowify.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/knowify/
providers:
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 20.3
  mcp: *id002
  name: AIA Contract Documents
  slug: aia-contract-documents
  status: profiled
  tags: *id003
  url: /providers/aia-contract-documents/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.0
  mcp: *id004
  name: Billd
  slug: billd
  status: profiled
  tags: *id005
  url: /providers/billd/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id006
  name: CompanyCam
  slug: companycam
  status: profiled
  tags: *id007
  url: /providers/companycam/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id008
  name: eBacon
  slug: ebacon
  status: profiled
  tags: *id009
  url: /providers/ebacon/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.5
  mcp: *id010
  name: Lumber
  slug: lumber
  status: profiled
  tags: *id011
  url: /providers/lumber/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id012
  name: QuickBooks Online / Desktop / Enterprise Suite
  slug: quickbooks
  status: profiled
  tags: *id013
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id014
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id015
  url: /providers/zapier/
siblings:
- name: CompanyCam
  rows: 15
  url: /applications/construction-management/companycam/
- name: JobTread
  rows: 11
  url: /applications/construction-management/jobtread/
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
title: 'Knowify: Construction Management reference app'
---
