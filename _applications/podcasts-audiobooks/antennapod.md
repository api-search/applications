---
app: AntennaPod
app_slug: antennapod
app_url: https://github.com/AntennaPod/AntennaPod
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.40
  key: AE-170.20.40
  layer: domain
  name: Podcast Directories & Search
  providers:
  - Apple (iTunes Search API)
  - fyyd
  - PodcastIndex
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
  - gpodder.net
  - Nextcloud (gpodder sync app)
  url: /capabilities/watch-listen-history-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-3740.20
  key: ott-streaming-delivery
  layer: common
  name: OTT & Streaming Delivery
  providers:
  - Google Cast
  url: /capabilities/ott-streaming-delivery/
  via_parent: null
category:
  id: podcasts-audiobooks
  name: Podcasts & Audiobooks
  url: /applications/podcasts-audiobooks/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/AntennaPod/AntennaPod/blob/develop/gradle/libs.versions.toml
- route: source code
  url: https://github.com/AntennaPod/AntennaPod/blob/develop/net/sync/service-interface/src/main/java/de/danoeh/antennapod/net/sync/serviceinterface/SynchronizationProvider.java
- route: source code
  url: https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.40
    key: AE-170.20.40
    name: Podcast Directories & Search
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple (iTunes Search API)
  provider: apple
  says: ships the Apple (iTunes Search API) SDK or integration code
  source: https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.40
    key: AE-170.20.40
    name: Podcast Directories & Search
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.9
    mcp: &id003
      status: unknown
    slug: fyyd
    status: profiled
    tags: &id004
    - Audio
    - Directory
    - Podcasts
    - Search
    url: /providers/fyyd/
  layer: domain
  name: fyyd
  provider: fyyd
  says: ships the fyyd SDK or integration code
  source: https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3740.20
    key: ott-streaming-delivery
    name: OTT & Streaming Delivery
    url: /capabilities/ott-streaming-delivery/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id005
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id006
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google Cast
  provider: google
  says: ships the Google Cast SDK or integration code
  source: https://github.com/AntennaPod/AntennaPod/blob/develop/gradle/libs.versions.toml
  tier: observed
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
    agent_readiness: 13.0
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id007
      status: none
    slug: gpodder
    status: profiled
    tags: &id008
    - Community
    - Open Source
    - Podcasts
    - Sync
    url: /providers/gpodder/
  layer: domain
  name: gpodder.net
  provider: gpodder
  says: ships the gpodder.net SDK or integration code
  source: https://github.com/AntennaPod/AntennaPod/blob/develop/net/sync/service-interface/src/main/java/de/danoeh/antennapod/net/sync/serviceinterface/SynchronizationProvider.java
  tier: observed
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id009
      status: none
    slug: nextcloud
    status: profiled
    tags: &id010
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud (gpodder sync app)
  provider: nextcloud
  says: ships the Nextcloud (gpodder sync app) SDK or integration code
  source: https://github.com/AntennaPod/AntennaPod/blob/develop/net/sync/service-interface/src/main/java/de/danoeh/antennapod/net/sync/serviceinterface/SynchronizationProvider.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.40
    key: AE-170.20.40
    name: Podcast Directories & Search
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id011
      status: none
    slug: podcastindex
    status: profiled
    tags: &id012
    - Discovery
    - Open Data
    - Podcast Index
    - Podcasts
    url: /providers/podcastindex/
  layer: domain
  name: PodcastIndex
  provider: podcastindex
  says: ships the PodcastIndex SDK or integration code
  source: https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/podcasts-audiobooks/antennapod/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple (iTunes Search API)
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id003
  name: fyyd
  slug: fyyd
  status: profiled
  tags: *id004
  url: /providers/fyyd/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id005
  name: Google Cast
  slug: google
  status: profiled
  tags: *id006
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 13.0
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id007
  name: gpodder.net
  slug: gpodder
  status: profiled
  tags: *id008
  url: /providers/gpodder/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id009
  name: Nextcloud (gpodder sync app)
  slug: nextcloud
  status: profiled
  tags: *id010
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id011
  name: PodcastIndex
  slug: podcastindex
  status: profiled
  tags: *id012
  url: /providers/podcastindex/
siblings:
- name: Audible
  rows: 4
  url: /applications/podcasts-audiobooks/audible/
- name: Audiobookshelf
  rows: 8
  url: /applications/podcasts-audiobooks/audiobookshelf/
- name: Castopod
  rows: 1
  url: /applications/podcasts-audiobooks/castopod/
- name: Pocket Casts
  rows: 5
  url: /applications/podcasts-audiobooks/pocket-casts/
- name: Podverse
  rows: 7
  url: /applications/podcasts-audiobooks/podverse/
sitemap: true
title: 'AntennaPod: Podcasts & Audiobooks reference app'
---
