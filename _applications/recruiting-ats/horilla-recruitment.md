---
app: Horilla (Recruitment)
app_slug: horilla-recruitment
app_url: https://github.com/horilla-opensource/horilla
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.10
  key: BC-300.10.10
  layer: domain
  name: Workforce Sourcing
  providers:
  - LinkedIn
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
category:
  id: recruiting-ats
  name: Recruiting & Applicant Tracking
  url: /applications/recruiting-ats/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: source code
  url: https://github.com/horilla-opensource/horilla/blob/master/recruitment/models.py
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
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id001
      status: none
    slug: linkedin
    status: profiled
    tags: &id002
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/horilla-opensource/horilla/blob/master/recruitment/models.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/horilla-recruitment/
providers:
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id001
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id002
  url: /providers/linkedin/
siblings:
- name: Ashby
  rows: 3
  url: /applications/recruiting-ats/ashby/
- name: Greenhouse
  rows: 5
  url: /applications/recruiting-ats/greenhouse/
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
title: 'Horilla (Recruitment): Recruiting & Applicant Tracking reference app'
---
