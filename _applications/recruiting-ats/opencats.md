---
app: OpenCATS
app_slug: opencats
app_url: https://github.com/opencats/OpenCATS
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.10
  key: BC-300.10.10
  layer: domain
  name: Workforce Sourcing
  providers:
  - Indeed
  - SimplyHired
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
category:
  id: recruiting-ats
  name: Recruiting & Applicant Tracking
  url: /applications/recruiting-ats/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/opencats/OpenCATS/blob/master/composer.json
- route: source code
  url: https://github.com/opencats/OpenCATS/blob/master/config.php
- route: source code
  url: https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
integrations:
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
    agent_readiness: 29.0
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id001
      status: none
    slug: indeed
    status: profiled
    tags: &id002
    - Careers
    - Employment
    - Hiring
    - Job Search
    url: /providers/indeed/
  layer: domain
  name: Indeed
  provider: indeed
  says: ships the Indeed SDK or integration code
  source: https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-300.10.10
    key: BC-300.10.10
    name: Workforce Sourcing
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: simplyhired
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: SimplyHired
  provider: simplyhired
  says: ships the SimplyHired SDK or integration code
  source: https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/opencats/
providers:
- agent_band: agent-ready
  agent_readiness: 29.0
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id001
  name: Indeed
  slug: indeed
  status: profiled
  tags: *id002
  url: /providers/indeed/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: SimplyHired
  slug: simplyhired
  status: queued for profiling
  tags: *id004
  url: null
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
- name: Recruitee
  rows: 7
  url: /applications/recruiting-ats/recruitee/
- name: Teamtailor
  rows: 63
  url: /applications/recruiting-ats/teamtailor/
sitemap: true
title: 'OpenCATS: Recruiting & Applicant Tracking reference app'
---
