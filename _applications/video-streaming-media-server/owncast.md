---
app: Owncast
app_slug: owncast
app_url: https://github.com/owncast/owncast
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind GeoIP
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Oracle Cloud Object Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Discord
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: video-streaming-media-server
  name: Video Streaming & Media Server
  url: /applications/video-streaming-media-server/
counts:
  declared: 1
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/owncast/owncast/blob/develop/go.mod
- route: documentation
  url: https://owncast.online/docs/storage/
- route: source code
  url: https://github.com/owncast/owncast/tree/develop/notifications/discord
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id001
      status: none
    slug: discord
    status: profiled
    tags: &id002
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/owncast/owncast/tree/develop/notifications/discord
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id003
      status: none
    slug: maxmind
    status: profiled
    tags: &id004
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind GeoIP
  provider: maxmind
  says: ships the MaxMind GeoIP SDK or integration code
  source: https://github.com/owncast/owncast/blob/develop/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id005
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle-cloud
    status: profiled
    tags: &id006
    - Cloud Computing
    - Enterprise Cloud
    - Infrastructure-as-a-Service
    - Oracle
    url: /providers/oracle-cloud/
  layer: common
  name: Oracle Cloud Object Storage
  provider: oracle-cloud
  says: lists Oracle Cloud Object Storage as an integration
  source: https://owncast.online/docs/storage/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-streaming-media-server/owncast/
providers:
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id001
  name: Discord
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id003
  name: MaxMind GeoIP
  slug: maxmind
  status: profiled
  tags: *id004
  url: /providers/maxmind/
- agent_band: agent-native
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id005
  name: Oracle Cloud Object Storage
  slug: oracle-cloud
  status: profiled
  tags: *id006
  url: /providers/oracle-cloud/
siblings:
- name: Emby
  rows: 3
  url: /applications/video-streaming-media-server/emby/
- name: Jellyfin
  rows: 11
  url: /applications/video-streaming-media-server/jellyfin/
- name: MediaCMS
  rows: 2
  url: /applications/video-streaming-media-server/mediacms/
- name: PeerTube
  rows: 4
  url: /applications/video-streaming-media-server/peertube/
- name: Plex
  rows: 10
  url: /applications/video-streaming-media-server/plex/
sitemap: true
title: 'Owncast: Video Streaming & Media Server reference app'
---
