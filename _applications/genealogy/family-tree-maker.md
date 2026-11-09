---
app: Family Tree Maker
app_slug: family-tree-maker
app_url: https://www.mackiev.com/ftm/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.110
  key: AE-230.110
  layer: domain
  name: Genealogy Records & Family Trees
  providers:
  - Ancestry tree sync + hints
  - FamilySearch hints
  url: /capabilities/genealogy-records-family-trees/
  via_parent: null
category:
  id: genealogy
  name: Genealogy & Family History
  url: /applications/genealogy/
counts:
  declared: 2
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.mackiev.com/ftm/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.110
    key: AE-230.110
    name: Genealogy Records & Family Trees
    url: /capabilities/genealogy-records-family-trees/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.1
    mcp: &id001
      status: none
    slug: ancestry
    status: profiled
    tags: &id002
    - Company
    - Data Export
    - Family History
    - Genealogy
    url: /providers/ancestry/
  layer: domain
  name: Ancestry tree sync + hints
  provider: ancestry
  says: lists Ancestry tree sync + hints as an integration
  source: https://www.mackiev.com/ftm/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.110
    key: AE-230.110
    name: Genealogy Records & Family Trees
    url: /capabilities/genealogy-records-family-trees/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 7.8
    mcp: &id003
      status: none
    slug: familysearch
    status: profiled
    tags: &id004
    - Data
    - Family History
    - Genealogy
    - Non-Profit
    url: /providers/familysearch/
  layer: domain
  name: FamilySearch hints
  provider: familysearch
  says: lists FamilySearch hints as an integration
  source: https://www.mackiev.com/ftm/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/genealogy/family-tree-maker/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id001
  name: Ancestry tree sync + hints
  slug: ancestry
  status: profiled
  tags: *id002
  url: /providers/ancestry/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id003
  name: FamilySearch hints
  slug: familysearch
  status: profiled
  tags: *id004
  url: /providers/familysearch/
siblings:
- name: Ancestry
  rows: 8
  url: /applications/genealogy/ancestry/
- name: FamilySearch
  rows: 3
  url: /applications/genealogy/familysearch/
- name: Gramps Web
  rows: 11
  url: /applications/genealogy/gramps-web/
- name: RootsMagic
  rows: 4
  url: /applications/genealogy/rootsmagic/
- name: webtrees
  rows: 13
  url: /applications/genealogy/webtrees/
sitemap: true
title: 'Family Tree Maker: Genealogy & Family History reference app'
---
