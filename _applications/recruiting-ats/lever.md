---
app: Lever
app_slug: lever
app_url: https://www.lever.co/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Verified First
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - ADP
  - BambooHR
  - HiBob
  - Justworks
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.10.10
  key: BC-300.10.10
  layer: domain
  name: Workforce Sourcing
  providers:
  - Indeed
  - LinkedIn
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
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
  url: https://marketplace.lever.co/
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
    agent_band: agent-ready
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: adp
    status: profiled
    tags: &id002
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
  layer: domain
  name: ADP
  provider: adp
  says: lists ADP as an integration
  source: https://marketplace.lever.co/
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
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 40.9
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
  source: https://marketplace.lever.co/
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
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id005
      source: https://apidocs.hibob.com/docs/hibob-mcp-server
      status: verified
    slug: bob
    status: profiled
    tags: &id006
    - Employee Management
    - HRIS
    - Human Resources
    - Time Off
    url: /providers/bob/
  layer: domain
  name: HiBob
  provider: bob
  says: lists HiBob as an integration
  source: https://marketplace.lever.co/
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
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id007
      status: none
    slug: indeed
    status: profiled
    tags: &id008
    - Careers
    - Employment
    - Hiring
    - Job Search
    url: /providers/indeed/
  layer: domain
  name: Indeed
  provider: indeed
  says: lists Indeed as an integration
  source: https://marketplace.lever.co/
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
    agent_readiness: 41.7
    band: developing
    in_catalog: true
    kin_score: 47.0
    mcp: &id009
      status: none
    slug: justworks
    status: profiled
    tags: &id010
    - Benefits
    - Human Resources
    - PEO
    - Payroll
    url: /providers/justworks/
  layer: domain
  name: Justworks
  provider: justworks
  says: lists Justworks as an integration
  source: https://marketplace.lever.co/
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
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id011
      status: none
    slug: linkedin
    status: profiled
    tags: &id012
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://marketplace.lever.co/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: emerging
    in_catalog: true
    kin_score: 19.8
    mcp: &id013
      status: none
    slug: verified-first
    status: profiled
    tags: &id014
    - Background Checks
    - Company
    - Screening
    - Verification
    url: /providers/verified-first/
  layer: domain
  name: Verified First
  provider: verified-first
  says: lists Verified First as an integration
  source: https://marketplace.lever.co/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/lever/
providers:
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: ADP
  slug: adp
  status: profiled
  tags: *id002
  url: /providers/adp/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id003
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id004
  url: /providers/bamboohr/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id005
  name: HiBob
  slug: bob
  status: profiled
  tags: *id006
  url: /providers/bob/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id007
  name: Indeed
  slug: indeed
  status: profiled
  tags: *id008
  url: /providers/indeed/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id009
  name: Justworks
  slug: justworks
  status: profiled
  tags: *id010
  url: /providers/justworks/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id011
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id012
  url: /providers/linkedin/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 19.8
  mcp: *id013
  name: Verified First
  slug: verified-first
  status: profiled
  tags: *id014
  url: /providers/verified-first/
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
- name: OpenCATS
  rows: 2
  url: /applications/recruiting-ats/opencats/
- name: Recruitee
  rows: 7
  url: /applications/recruiting-ats/recruitee/
- name: Teamtailor
  rows: 63
  url: /applications/recruiting-ats/teamtailor/
sitemap: true
title: 'Lever: Recruiting & Applicant Tracking reference app'
---
