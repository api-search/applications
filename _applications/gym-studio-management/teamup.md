---
app: TeamUp
app_slug: teamup
app_url: https://www.teamup.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  url: /capabilities/internal-communications-management/
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
  id: gym-studio-management
  name: Gym & Fitness Studio Management
  url: /applications/gym-studio-management/
counts:
  declared: 2
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.teamup.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id001
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id002
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.teamup.com/integrations/
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
    mcp: &id003
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id004
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.teamup.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/gym-studio-management/teamup/
providers:
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id001
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id002
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id003
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id004
  url: /providers/zapier/
siblings:
- name: GYM One
  rows: 4
  url: /applications/gym-studio-management/gym-one/
- name: Mindbody
  rows: 24
  url: /applications/gym-studio-management/mindbody/
- name: wger (gym module)
  rows: 5
  url: /applications/gym-studio-management/wger-gym-module/
- name: Wodify
  rows: 19
  url: /applications/gym-studio-management/wodify/
- name: Zen Planner
  rows: 21
  url: /applications/gym-studio-management/zen-planner/
sitemap: true
title: 'TeamUp: Gym & Fitness Studio Management reference app'
---
