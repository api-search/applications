---
app: PeerTube
app_slug: peertube
app_url: https://github.com/Chocobozzz/PeerTube
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
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
  - Amazon S3
  - Scaleway Object Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: video-streaming-media-server
  name: Video Streaming & Media Server
  url: /applications/video-streaming-media-server/
counts:
  declared: 3
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Chocobozzz/PeerTube/blob/develop/package.json
- route: source code
  url: https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
integrations:
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
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
  source: https://github.com/Chocobozzz/PeerTube/blob/develop/package.json
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: lists Amazon S3 as an integration
  source: https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id005
      source: https://github.com/scaleway/scaleway-cli
      status: verified
    slug: scaleway
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Cloud Computing
    - Containers
    - Database
    url: /providers/scaleway/
  layer: common
  name: Scaleway Object Storage
  provider: scaleway
  says: lists Scaleway Object Storage as an integration
  source: https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id007
      status: none
    slug: youtube
    status: profiled
    tags: &id008
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-streaming-media-server/peertube/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id003
  name: MaxMind GeoIP
  slug: maxmind
  status: profiled
  tags: *id004
  url: /providers/maxmind/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id005
  name: Scaleway Object Storage
  slug: scaleway
  status: profiled
  tags: *id006
  url: /providers/scaleway/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id007
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id008
  url: /providers/youtube/
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
- name: Owncast
  rows: 3
  url: /applications/video-streaming-media-server/owncast/
- name: Plex
  rows: 10
  url: /applications/video-streaming-media-server/plex/
sitemap: true
title: 'PeerTube: Video Streaming & Media Server reference app'
---
