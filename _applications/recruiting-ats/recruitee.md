---
app: Recruitee
app_slug: recruitee
app_url: https://recruitee.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - AFAS
  - BambooHR
  - SAP SuccessFactors
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.10.10
  key: BC-300.10.10
  layer: domain
  name: Workforce Sourcing
  providers:
  - LinkedIn
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: recruiting-ats
  name: Recruiting & Applicant Tracking
  url: /applications/recruiting-ats/
counts:
  declared: 7
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://recruitee.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id001
      status: unknown
    slug: afas
    status: profiled
    tags: &id002
    - Company
    - ERP
    - Human Resources
    - Payroll
    url: /providers/afas/
  layer: domain
  name: AFAS
  provider: afas
  says: lists AFAS as an integration
  source: https://recruitee.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id003
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id004
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
  layer: domain
  name: BambooHR
  provider: bamboohr
  says: lists BambooHR as an integration
  source: https://recruitee.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.10
    key: BC-300.10.10
    name: Workforce Sourcing
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id005
      status: none
    slug: linkedin
    status: profiled
    tags: &id006
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://recruitee.com/integrations
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
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id007
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id008
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://recruitee.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 26.2
    mcp: &id009
      status: none
    slug: sap-successfactors
    status: profiled
    tags: &id010
    - HCM
    - Human Resources
    - Payroll
    - Talent Management
    url: /providers/sap-successfactors/
  layer: domain
  name: SAP SuccessFactors
  provider: sap-successfactors
  says: lists SAP SuccessFactors as an integration
  source: https://recruitee.com/integrations
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
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id011
      status: none
    slug: workday
    status: profiled
    tags: &id012
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://recruitee.com/integrations
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
    mcp: &id013
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id014
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://recruitee.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/recruitee/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id001
  name: AFAS
  slug: afas
  status: profiled
  tags: *id002
  url: /providers/afas/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id003
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id004
  url: /providers/bamboohr/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id005
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id006
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id007
  name: Make
  slug: make
  status: profiled
  tags: *id008
  url: /providers/make/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 26.2
  mcp: *id009
  name: SAP SuccessFactors
  slug: sap-successfactors
  status: profiled
  tags: *id010
  url: /providers/sap-successfactors/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id011
  name: Workday
  slug: workday
  status: profiled
  tags: *id012
  url: /providers/workday/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id013
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id014
  url: /providers/zapier/
siblings:
- name: Ashby
  rows: 3
  url: /applications/recruiting-ats/ashby/
- name: Greenhouse
  rows: 5
  url: /applications/recruiting-ats/greenhouse/
- name: Horilla (Recruitment)
  rows: 1
  url: /applications/recruiting-ats/horilla-recruitment/
- name: Lever
  rows: 7
  url: /applications/recruiting-ats/lever/
- name: OpenCATS
  rows: 2
  url: /applications/recruiting-ats/opencats/
- name: Teamtailor
  rows: 63
  url: /applications/recruiting-ats/teamtailor/
sitemap: true
title: 'Recruitee: Recruiting & Applicant Tracking reference app'
---
