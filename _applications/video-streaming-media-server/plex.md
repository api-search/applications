---
app: Plex
app_slug: plex
app_url: https://www.plex.tv/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.10.30
  key: AE-170.10.30
  layer: domain
  name: Film & TV Metadata, Artwork & Subtitles
  providers:
  - CineMaterial
  - Fanart.tv
  - Rotten Tomatoes
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3710.20
  key: metadata-cataloguing
  layer: domain
  name: Metadata Cataloguing
  providers:
  - IMDb
  - The Movie Database
  - TheTVDB
  url: /capabilities/metadata-cataloguing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - AllMusic
  - Last.fm
  - MusicBrainz
  url: /capabilities/audio-music/
  via_parent: Audio & Music
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
  declared: 9
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.plexapp.android/latest/
- route: documentation
  url: https://support.plex.tv/articles/200241558-agents/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id015
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id016
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.plexapp.android/latest/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.8
    mcp: &id001
      status: unknown
    slug: allmusic
    status: profiled
    tags: &id002
    - Company
    url: /providers/allmusic/
  layer: domain
  name: AllMusic
  provider: allmusic
  says: lists AllMusic as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.30
    key: AE-170.10.30
    name: Film & TV Metadata, Artwork & Subtitles
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id003
      status: unknown
    slug: cinematerial
    status: profiled
    tags: &id004
    - Archives
    - Company
    - Media
    - Movies
    url: /providers/cinematerial/
  layer: domain
  name: CineMaterial
  provider: cinematerial
  says: lists CineMaterial as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.30
    key: AE-170.10.30
    name: Film & TV Metadata, Artwork & Subtitles
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id005
      status: unknown
    slug: fanart-tv
    status: profiled
    tags: &id006
    - Company
    - Image
    - Media
    - Movies
    url: /providers/fanart-tv/
  layer: domain
  name: Fanart.tv
  provider: fanart-tv
  says: lists Fanart.tv as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710.20
    key: metadata-cataloguing
    name: Metadata Cataloguing
    url: /capabilities/metadata-cataloguing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id007
      status: none
    slug: imdb
    status: profiled
    tags: &id008
    - Company
    - Data
    - Entertainment
    - Movies
    url: /providers/imdb/
  layer: domain
  name: IMDb
  provider: imdb
  says: lists IMDb as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
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
    agent_readiness: 25.9
    band: strong
    in_catalog: true
    kin_score: 54.4
    mcp: &id009
      status: none
    slug: lastfm
    status: profiled
    tags: &id010
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
  layer: domain
  name: Last.fm
  provider: lastfm
  says: lists Last.fm as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
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
    mcp: &id011
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id012
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
  layer: domain
  name: MusicBrainz
  provider: musicbrainz
  says: lists MusicBrainz as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.30
    key: AE-170.10.30
    name: Film & TV Metadata, Artwork & Subtitles
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: rotten-tomatoes
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Rotten Tomatoes
  provider: rotten-tomatoes
  says: lists Rotten Tomatoes as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710.20
    key: metadata-cataloguing
    name: Metadata Cataloguing
    url: /capabilities/metadata-cataloguing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id017
      status: none
    slug: tmdb
    status: profiled
    tags: &id018
    - Catalog
    - Discovery
    - Entertainment
    - Image
    url: /providers/tmdb/
  layer: domain
  name: The Movie Database
  provider: tmdb
  says: lists The Movie Database as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710.20
    key: metadata-cataloguing
    name: Metadata Cataloguing
    url: /capabilities/metadata-cataloguing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.3
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id019
      status: unknown
    slug: tvdb
    status: profiled
    tags: &id020
    - Entertainment
    - Media Metadata
    - Movies
    - Television
    url: /providers/tvdb/
  layer: domain
  name: TheTVDB
  provider: tvdb
  says: lists TheTVDB as an integration
  source: https://support.plex.tv/articles/200241558-agents/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-streaming-media-server/plex/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.8
  mcp: *id001
  name: AllMusic
  slug: allmusic
  status: profiled
  tags: *id002
  url: /providers/allmusic/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id003
  name: CineMaterial
  slug: cinematerial
  status: profiled
  tags: *id004
  url: /providers/cinematerial/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id005
  name: Fanart.tv
  slug: fanart-tv
  status: profiled
  tags: *id006
  url: /providers/fanart-tv/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id007
  name: IMDb
  slug: imdb
  status: profiled
  tags: *id008
  url: /providers/imdb/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id009
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id010
  url: /providers/lastfm/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id011
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id012
  url: /providers/musicbrainz/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Rotten Tomatoes
  slug: rotten-tomatoes
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id015
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id016
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id017
  name: The Movie Database
  slug: tmdb
  status: profiled
  tags: *id018
  url: /providers/tmdb/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id019
  name: TheTVDB
  slug: tvdb
  status: profiled
  tags: *id020
  url: /providers/tvdb/
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
- name: PeerTube
  rows: 4
  url: /applications/video-streaming-media-server/peertube/
sitemap: true
title: 'Plex: Video Streaming & Media Server reference app'
---
