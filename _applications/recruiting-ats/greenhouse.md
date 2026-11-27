---
app: Greenhouse
app_slug: greenhouse
app_url: https://www.greenhouse.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Checkr
  - Criteria Corp
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - ChartHop
  - Deel
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Paylocity (Texting)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: recruiting-ats
  name: Recruiting & Applicant Tracking
  url: /applications/recruiting-ats/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://integrations.greenhouse.com/
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
    agent_readiness: 47.6
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id001
      status: none
    slug: charthop
    status: profiled
    tags: &id002
    - Company
    - HRIS
    - Human Resources
    - People Analytics
    url: /providers/charthop/
  layer: domain
  name: ChartHop
  provider: charthop
  says: lists ChartHop as an integration
  source: https://integrations.greenhouse.com/
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
    agent_band: agent-ready
    agent_readiness: 52.8
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id003
      status: none
    slug: checkr
    status: profiled
    tags: &id004
    - Background Checks
    - Compliance
    - Employment Screening
    - Human Resources
    url: /providers/checkr/
  layer: domain
  name: Checkr
  provider: checkr
  says: lists Checkr as an integration
  source: https://integrations.greenhouse.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id005
      status: unknown
    slug: criteria-corp
    status: profiled
    tags: &id006
    - Assessment
    - Pre-Employment Testing
    - Talent Development
    - Video Interviewing
    url: /providers/criteria-corp/
  layer: domain
  name: Criteria Corp
  provider: criteria-corp
  says: lists Criteria Corp as an integration
  source: https://integrations.greenhouse.com/
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
    agent_band: agent-native
    agent_readiness: 52.0
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id007
      source: https://developer.deel.com/docs/mcp
      status: documented
    slug: deel-com
    status: profiled
    tags: &id008
    - Employer of Record
    - Global Payroll
    - Human Resources
    - Payroll
    url: /providers/deel-com/
  layer: domain
  name: Deel
  provider: deel-com
  says: lists Deel as an integration
  source: https://integrations.greenhouse.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id009
      status: none
    slug: paylocity
    status: profiled
    tags: &id010
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/paylocity/
  layer: common
  name: Paylocity (Texting)
  provider: paylocity
  says: lists Paylocity (Texting) as an integration
  source: https://integrations.greenhouse.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/greenhouse/
providers:
- agent_band: agent-ready
  agent_readiness: 47.6
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id001
  name: ChartHop
  slug: charthop
  status: profiled
  tags: *id002
  url: /providers/charthop/
- agent_band: agent-ready
  agent_readiness: 52.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id003
  name: Checkr
  slug: checkr
  status: profiled
  tags: *id004
  url: /providers/checkr/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id005
  name: Criteria Corp
  slug: criteria-corp
  status: profiled
  tags: *id006
  url: /providers/criteria-corp/
- agent_band: agent-native
  agent_readiness: 52.0
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id007
  name: Deel
  slug: deel-com
  status: profiled
  tags: *id008
  url: /providers/deel-com/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id009
  name: Paylocity (Texting)
  slug: paylocity
  status: profiled
  tags: *id010
  url: /providers/paylocity/
siblings:
- name: Ashby
  rows: 3
  url: /applications/recruiting-ats/ashby/
- name: Horilla (Recruitment)
  rows: 1
  url: /applications/recruiting-ats/horilla-recruitment/
- name: Lever
  rows: 7
  url: /applications/recruiting-ats/lever/
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
title: 'Greenhouse: Recruiting & Applicant Tracking reference app'
---
