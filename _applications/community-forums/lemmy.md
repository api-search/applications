---
app: Lemmy
app_slug: lemmy
app_url: https://github.com/LemmyNet/lemmy
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30.10
  key: AE-170.30.10
  layer: common
  name: Image Processing & Optimisation
  providers:
  - pict-rs
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - PostgreSQL
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: community-forums
  name: Community & Forums
  url: /applications/community-forums/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: source code
  url: https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: emerging
    in_catalog: true
    kin_score: 25.4
    mcp: &id001
      status: unknown
    slug: pict-rs
    status: profiled
    tags: &id002
    - Image Hosting
    - Open Source
    - Rust
    - Self-Hosted
    url: /providers/pict-rs/
  layer: common
  name: pict-rs
  provider: pict-rs
  says: ships the pict-rs SDK or integration code
  source: https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id003
      status: none
    slug: postgresql
    status: profiled
    tags: &id004
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: common
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/community-forums/lemmy/
providers:
- agent_band: agent-aware
  agent_readiness: 17.9
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id001
  name: pict-rs
  slug: pict-rs
  status: profiled
  tags: *id002
  url: /providers/pict-rs/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id003
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id004
  url: /providers/postgresql/
siblings:
- name: Circle
  rows: 36
  url: /applications/community-forums/circle/
- name: Discourse
  rows: 44
  url: /applications/community-forums/discourse/
- name: Flarum
  rows: 4
  url: /applications/community-forums/flarum/
- name: Mastodon
  rows: 10
  url: /applications/community-forums/mastodon/
- name: NodeBB
  rows: 9
  url: /applications/community-forums/nodebb/
sitemap: true
title: 'Lemmy: Community & Forums reference app'
---
