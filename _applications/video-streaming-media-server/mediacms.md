---
app: MediaCMS
app_slug: mediacms
app_url: https://github.com/mediacms-io/mediacms
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4730.30
  key: learning-environment-management
  layer: domain
  name: Learning Environment Management
  providers:
  - Moodle
  url: /capabilities/learning-environment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: video-streaming-media-server
  name: Video Streaming & Media Server
  url: /applications/video-streaming-media-server/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/mediacms-io/mediacms/blob/main/requirements.txt
- route: source code
  url: https://github.com/mediacms-io/mediacms/tree/main/lms-plugins
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.7
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id001
      status: none
    slug: moodle
    status: profiled
    tags: &id002
    - E-Learning
    - EdTech
    - LMS
    - Moodle
    url: /providers/moodle/
  layer: domain
  name: Moodle
  provider: moodle
  says: ships the Moodle SDK or integration code
  source: https://github.com/mediacms-io/mediacms/tree/main/lms-plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id003
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id004
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/mediacms-io/mediacms/blob/main/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-streaming-media-server/mediacms/
providers:
- agent_band: human-only
  agent_readiness: 1.7
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id001
  name: Moodle
  slug: moodle
  status: profiled
  tags: *id002
  url: /providers/moodle/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id003
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id004
  url: /providers/sentry-system/
siblings:
- name: Emby
  rows: 3
  url: /applications/video-streaming-media-server/emby/
- name: Jellyfin
  rows: 11
  url: /applications/video-streaming-media-server/jellyfin/
- name: Owncast
  rows: 3
  url: /applications/video-streaming-media-server/owncast/
- name: PeerTube
  rows: 4
  url: /applications/video-streaming-media-server/peertube/
- name: Plex
  rows: 10
  url: /applications/video-streaming-media-server/plex/
sitemap: true
title: 'MediaCMS: Video Streaming & Media Server reference app'
---
