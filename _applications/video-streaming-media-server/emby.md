---
app: Emby
app_slug: emby
app_url: https://emby.media/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.10.20
  key: AE-170.10.20
  layer: domain
  name: Connected TV
  providers:
  - SiliconDust HDHomeRun
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3730.20
  key: BC-3730.20
  layer: domain
  name: Electronic Programme Guide Management
  providers:
  - Schedules Direct
  url: /capabilities/electronic-programme-guide-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
  - Trakt
  url: /capabilities/watch-listen-history-sync/
  via_parent: null
category:
  id: video-streaming-media-server
  name: Video Streaming & Media Server
  url: /applications/video-streaming-media-server/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://emby.media/support/articles/Live-TV.html
- route: integrations page
  url: https://emby.media/support/articles/Plugins.html
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3730.20
    key: BC-3730.20
    name: Electronic Programme Guide Management
    url: /capabilities/electronic-programme-guide-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.1
    mcp: &id001
      status: unknown
    slug: schedules-direct
    status: profiled
    tags: &id002
    - Company
    - Non-Profit
    - Open Source
    - TV Listings
    url: /providers/schedules-direct/
  layer: domain
  name: Schedules Direct
  provider: schedules-direct
  says: lists Schedules Direct as an integration
  source: https://emby.media/support/articles/Live-TV.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.20
    key: AE-170.10.20
    name: Connected TV
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id003
      status: unknown
    slug: silicondust
    status: profiled
    tags: &id004
    - Company
    - Hardware
    - Streaming
    - TV
    url: /providers/silicondust/
  layer: domain
  name: SiliconDust HDHomeRun
  provider: silicondust
  says: lists SiliconDust HDHomeRun as an integration
  source: https://emby.media/support/articles/Live-TV.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id005
      status: none
    slug: trakt
    status: profiled
    tags: &id006
    - Media Tracking
    - Movies
    - Television
    - Video
    url: /providers/trakt/
  layer: domain
  name: Trakt
  provider: trakt
  says: lists Trakt as an integration
  source: https://emby.media/support/articles/Plugins.html
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-streaming-media-server/emby/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.1
  mcp: *id001
  name: Schedules Direct
  slug: schedules-direct
  status: profiled
  tags: *id002
  url: /providers/schedules-direct/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id003
  name: SiliconDust HDHomeRun
  slug: silicondust
  status: profiled
  tags: *id004
  url: /providers/silicondust/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id005
  name: Trakt
  slug: trakt
  status: profiled
  tags: *id006
  url: /providers/trakt/
siblings:
- name: Jellyfin
  rows: 11
  url: /applications/video-streaming-media-server/jellyfin/
- name: MediaCMS
  rows: 2
  url: /applications/video-streaming-media-server/mediacms/
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
title: 'Emby: Video Streaming & Media Server reference app'
---
