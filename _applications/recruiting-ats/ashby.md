---
app: Ashby
app_slug: ashby
app_url: https://www.ashbyhq.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
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
  id: recruiting-ats
  name: Recruiting & Applicant Tracking
  url: /applications/recruiting-ats/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.ashbyhq.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id001
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id002
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.ashbyhq.com/integrations
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
    mcp: &id003
      status: none
    slug: workday
    status: profiled
    tags: &id004
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.ashbyhq.com/integrations
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
    mcp: &id005
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id006
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.ashbyhq.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/ashby/
providers:
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id001
  name: Slack
  slug: slack
  status: profiled
  tags: *id002
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id003
  name: Workday
  slug: workday
  status: profiled
  tags: *id004
  url: /providers/workday/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id005
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id006
  url: /providers/zapier/
siblings:
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
- name: Recruitee
  rows: 7
  url: /applications/recruiting-ats/recruitee/
- name: Teamtailor
  rows: 63
  url: /applications/recruiting-ats/teamtailor/
sitemap: true
title: 'Ashby: Recruiting & Applicant Tracking reference app'
---
