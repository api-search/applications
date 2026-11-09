---
app: FamilySearch
app_slug: familysearch
app_url: https://www.familysearch.org/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google CrashLytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Adobe Experience Cloud
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: genealogy
  name: Genealogy & Family History
  url: /applications/genealogy/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 54.1
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id002
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id003
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id005
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/genealogy/familysearch/
providers:
- agent_band: agent-ready
  agent_readiness: 54.1
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id002
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id003
  url: /providers/adobe-experience-cloud/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id004
  name: Google CrashLytics
  slug: firebase
  status: profiled
  tags: *id005
  url: /providers/firebase/
siblings:
- name: Ancestry
  rows: 8
  url: /applications/genealogy/ancestry/
- name: Family Tree Maker
  rows: 2
  url: /applications/genealogy/family-tree-maker/
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
title: 'FamilySearch: Genealogy & Family History reference app'
---
