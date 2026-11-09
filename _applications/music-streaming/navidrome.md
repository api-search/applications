---
app: Navidrome
app_slug: navidrome
app_url: https://github.com/navidrome/navidrome
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Deezer
  - Last.fm
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
  - Last.fm
  - ListenBrainz
  url: /capabilities/watch-listen-history-sync/
  via_parent: null
category:
  id: music-streaming
  name: Music & Audio Streaming
  url: /applications/music-streaming/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/navidrome/navidrome/blob/master/go.mod
- route: source code
  url: https://github.com/navidrome/navidrome/blob/master/conf/configuration.go
- route: source code
  url: https://github.com/navidrome/navidrome/tree/master/adapters
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id002
      status: none
    slug: deezer
    status: profiled
    tags: &id003
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/deezer/
  layer: domain
  name: Deezer
  provider: deezer
  says: ships the Deezer SDK or integration code
  source: https://github.com/navidrome/navidrome/tree/master/adapters
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 23.7
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id004
      status: none
    slug: lastfm
    status: profiled
    tags: &id005
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
  layer: domain
  name: Last.fm
  provider: lastfm
  says: ships the Last.fm SDK or integration code
  source: https://github.com/navidrome/navidrome/tree/master/adapters
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Last.fm
  provider: lastfm
  says: ships the Last.fm SDK or integration code
  source: https://github.com/navidrome/navidrome/tree/master/adapters
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id006
      status: none
    slug: listenbrainz
    status: profiled
    tags: &id007
    - Community
    - Data API
    - Music
    - Open Source
    url: /providers/listenbrainz/
  layer: domain
  name: ListenBrainz
  provider: listenbrainz
  says: ships the ListenBrainz SDK or integration code
  source: https://github.com/navidrome/navidrome/tree/master/adapters
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/music-streaming/navidrome/
providers:
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id002
  name: Deezer
  slug: deezer
  status: profiled
  tags: *id003
  url: /providers/deezer/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id004
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id005
  url: /providers/lastfm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id006
  name: ListenBrainz
  slug: listenbrainz
  status: profiled
  tags: *id007
  url: /providers/listenbrainz/
siblings:
- name: Ampache
  rows: 27
  url: /applications/music-streaming/ampache/
- name: beets
  rows: 30
  url: /applications/music-streaming/beets/
- name: Funkwhale
  rows: 7
  url: /applications/music-streaming/funkwhale/
- name: Koel
  rows: 18
  url: /applications/music-streaming/koel/
- name: Lidarr
  rows: 24
  url: /applications/music-streaming/lidarr/
- name: Spotify
  rows: 4
  url: /applications/music-streaming/spotify/
sitemap: true
title: 'Navidrome: Music & Audio Streaming reference app'
---
