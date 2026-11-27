---
app: Funkwhale
app_slug: funkwhale
app_url: https://dev.funkwhale.audio/funkwhale/funkwhale
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - MusicBrainz
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
  - Last.fm
  - Libre.fm
  - ListenBrainz
  - Maloja
  url: /capabilities/watch-listen-history-sync/
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
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Typesense
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
category:
  id: music-streaming
  name: Music & Audio Streaming
  url: /applications/music-streaming/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
- route: source code
  url: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/funkwhale_api/contrib/scrobbler/funkwhale_startup.py
- route: source code
  url: https://dev.funkwhale.audio/funkwhale/funkwhale/-/tree/develop/api/funkwhale_api/contrib
integrations:
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
    agent_readiness: 25.9
    band: strong
    in_catalog: true
    kin_score: 54.4
    mcp: &id001
      status: none
    slug: lastfm
    status: profiled
    tags: &id002
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
  layer: domain
  name: Last.fm
  provider: lastfm
  says: ships the Last.fm SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/funkwhale_api/contrib/scrobbler/funkwhale_startup.py
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
    agent_readiness: 1.7
    band: emerging
    in_catalog: true
    kin_score: 25.4
    mcp: &id003
      status: none
    slug: libre-fm
    status: profiled
    tags: &id004
    - Company
    - Music
    - Open Source
    - Scrobbling
    url: /providers/libre-fm/
  layer: domain
  name: Libre.fm
  provider: libre-fm
  says: ships the Libre.fm SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/funkwhale_api/contrib/scrobbler/funkwhale_startup.py
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
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id005
      status: none
    slug: listenbrainz
    status: profiled
    tags: &id006
    - Community
    - Data API
    - Music
    - Open Source
    url: /providers/listenbrainz/
  layer: domain
  name: ListenBrainz
  provider: listenbrainz
  says: ships the ListenBrainz SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/tree/develop/api/funkwhale_api/contrib
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
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 20.1
    mcp: &id007
      status: unknown
    slug: maloja
    status: profiled
    tags: &id008
    - Music
    - Scrobble
    - Self-Hosted
    - Statistics
    url: /providers/maloja/
  layer: domain
  name: Maloja
  provider: maloja
  says: ships the Maloja SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/tree/develop/api/funkwhale_api/contrib
  tier: observed
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
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id009
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id010
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
  layer: domain
  name: MusicBrainz
  provider: musicbrainz
  says: ships the MusicBrainz SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
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
    mcp: &id011
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id012
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.3
    band: thin
    in_catalog: true
    kin_score: 39.2
    mcp: &id013
      source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
      status: verified
    slug: typesense
    status: profiled
    tags: &id014
    - Full-Text Search
    - Open Source
    - Search Engines
    - Typo Tolerance
    url: /providers/typesense/
  layer: common
  name: Typesense
  provider: typesense
  says: ships the Typesense SDK or integration code
  source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/music-streaming/funkwhale/
providers:
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id001
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id002
  url: /providers/lastfm/
- agent_band: human-only
  agent_readiness: 1.7
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id003
  name: Libre.fm
  slug: libre-fm
  status: profiled
  tags: *id004
  url: /providers/libre-fm/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id005
  name: ListenBrainz
  slug: listenbrainz
  status: profiled
  tags: *id006
  url: /providers/listenbrainz/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id007
  name: Maloja
  slug: maloja
  status: profiled
  tags: *id008
  url: /providers/maloja/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id009
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id010
  url: /providers/musicbrainz/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id011
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id012
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 47.3
  band: thin
  in_catalog: true
  kin_score: 39.2
  mcp: *id013
  name: Typesense
  slug: typesense
  status: profiled
  tags: *id014
  url: /providers/typesense/
siblings:
- name: Ampache
  rows: 27
  url: /applications/music-streaming/ampache/
- name: beets
  rows: 30
  url: /applications/music-streaming/beets/
- name: Koel
  rows: 18
  url: /applications/music-streaming/koel/
- name: Lidarr
  rows: 24
  url: /applications/music-streaming/lidarr/
- name: Navidrome
  rows: 4
  url: /applications/music-streaming/navidrome/
- name: Spotify
  rows: 4
  url: /applications/music-streaming/spotify/
sitemap: true
title: 'Funkwhale: Music & Audio Streaming reference app'
---
