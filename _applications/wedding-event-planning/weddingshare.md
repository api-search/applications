---
app: WeddingShare
app_slug: weddingshare
app_url: https://github.com/Cirx08/WeddingShare
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Gotify
  - ntfy
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: wedding-event-planning
  name: Wedding & Event Planning
  url: /applications/wedding-event-planning/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Cirx08/WeddingShare/blob/main/WeddingShare/WeddingShare.csproj
- route: source code
  url: https://github.com/Cirx08/WeddingShare/tree/main/WeddingShare/Helpers/Notifications
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id001
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id002
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/Cirx08/WeddingShare/tree/main/WeddingShare/Helpers/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id003
      status: none
    slug: ntfy
    status: profiled
    tags: &id004
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/Cirx08/WeddingShare/tree/main/WeddingShare/Helpers/Notifications
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/wedding-event-planning/weddingshare/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id001
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id002
  url: /providers/gotify/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id003
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id004
  url: /providers/ntfy/
siblings:
- name: Aisle Planner
  rows: 6
  url: /applications/wedding-event-planning/aisle-planner/
- name: HoneyBook
  rows: 40
  url: /applications/wedding-event-planning/honeybook/
- name: Joy
  rows: 12
  url: /applications/wedding-event-planning/joy/
- name: Planning Pod
  rows: 23
  url: /applications/wedding-event-planning/planning-pod/
- name: Rallly
  rows: 16
  url: /applications/wedding-event-planning/rallly/
- name: The Knot Wedding Planner
  rows: 0
  url: /applications/wedding-event-planning/the-knot-wedding-planner/
sitemap: true
title: 'WeddingShare: Wedding & Event Planning reference app'
---
