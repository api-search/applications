---
app: CasaOS
app_slug: casaos
app_url: https://github.com/IceWhaleTech/CasaOS
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.40.10
  key: BC-4200.40.10
  layer: domain
  name: Source Code Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: Software Construction Management
category:
  id: personal-dashboard-homelab
  name: Personal Dashboard & Homelab
  url: /applications/personal-dashboard-homelab/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/IceWhaleTech/CasaOS/blob/main/go.mod
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id001
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id002
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/IceWhaleTech/CasaOS/blob/main/go.mod
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-dashboard-homelab/casaos/
providers:
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id001
  name: GitHub
  slug: github
  status: profiled
  tags: *id002
  url: /providers/github/
siblings:
- name: Dashy
  rows: 35
  url: /applications/personal-dashboard-homelab/dashy/
- name: Glance
  rows: 16
  url: /applications/personal-dashboard-homelab/glance/
- name: Homarr
  rows: 65
  url: /applications/personal-dashboard-homelab/homarr/
- name: Homepage
  rows: 102
  url: /applications/personal-dashboard-homelab/homepage/
- name: Homer
  rows: 43
  url: /applications/personal-dashboard-homelab/homer/
sitemap: true
title: 'CasaOS: Personal Dashboard & Homelab reference app'
---
