---
app: Jellyfin
app_slug: jellyfin
app_url: https://github.com/jellyfin/jellyfin
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.10.30
  key: AE-170.10.30
  layer: domain
  name: Film & TV Metadata, Artwork & Subtitles
  providers:
  - Fanart.tv
  - OpenSubtitles
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3710.20
  key: metadata-cataloguing
  layer: domain
  name: Metadata Cataloguing
  providers:
  - AniDB
  - AniList
  - OMDb
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
  - MusicBrainz
  - TheAudioDB
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
  - ListenBrainz
  - Trakt
  url: /capabilities/watch-listen-history-sync/
  via_parent: null
category:
  id: video-streaming-media-server
  name: Video Streaming & Media Server
  url: /applications/video-streaming-media-server/
counts:
  declared: 0
  observed: 11
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.jellyfin.mobile/latest/
- route: source code
  url: https://github.com/jellyfin/jellyfin-plugin-opensubtitles
- route: source code
  url: https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.20
    key: metadata-cataloguing
    name: Metadata Cataloguing
    url: /capabilities/metadata-cataloguing/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.1
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id001
      status: unknown
    slug: anidb
    status: profiled
    tags: &id002
    - Anime
    - Public APIs
    url: /providers/anidb/
  layer: domain
  name: AniDB
  provider: anidb
  says: ships the AniDB SDK or integration code
  source: https://github.com/jellyfin/jellyfin-plugin-anidb
  tier: observed
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
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id003
      status: none
    slug: anilist
    status: profiled
    tags: &id004
    - Anime
    - Entertainment
    - Manga
    - Media
    url: /providers/anilist/
  layer: domain
  name: AniList
  provider: anilist
  says: ships the AniList SDK or integration code
  source: https://github.com/jellyfin/jellyfin-plugin-anilist
  tier: observed
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
  says: ships the Fanart.tv SDK or integration code
  source: https://github.com/jellyfin/jellyfin-plugin-fanart
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
    mcp: &id007
      status: none
    slug: listenbrainz
    status: profiled
    tags: &id008
    - Community
    - Data API
    - Music
    - Open Source
    url: /providers/listenbrainz/
  layer: domain
  name: ListenBrainz
  provider: listenbrainz
  says: ships the ListenBrainz SDK or integration code
  source: https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
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
  source: https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
  tier: observed
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id011
      status: none
    slug: omdb
    status: profiled
    tags: &id012
    - Entertainment
    - Metadata
    - Movies
    - Television
    url: /providers/omdb/
  layer: domain
  name: OMDb
  provider: omdb
  says: ships the OMDb SDK or integration code
  source: https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
  tier: observed
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
    kin_score: 3.4
    mcp: &id013
      source: https://mcp.opensubtitles.com
      status: verified
    slug: opensubtitles
    status: profiled
    tags: &id014
    - Company
    - Media
    - Subtitles
    - Video
    url: /providers/opensubtitles/
  layer: domain
  name: OpenSubtitles
  provider: opensubtitles
  says: ships the OpenSubtitles SDK or integration code
  source: https://github.com/jellyfin/jellyfin-plugin-opensubtitles
  tier: observed
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
    mcp: &id015
      status: none
    slug: tmdb
    status: profiled
    tags: &id016
    - Catalog
    - Discovery
    - Entertainment
    - Image
    url: /providers/tmdb/
  layer: domain
  name: The Movie Database
  provider: tmdb
  says: ships the The Movie Database SDK or integration code
  source: https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
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
    kin_score: 2.4
    mcp: &id017
      status: none
    slug: theaudiodb
    status: profiled
    tags: &id018
    - Music
    - Public APIs
    url: /providers/theaudiodb/
  layer: domain
  name: TheAudioDB
  provider: theaudiodb
  says: ships the TheAudioDB SDK or integration code
  source: https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
  tier: observed
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
  says: ships the TheTVDB SDK or integration code
  source: https://github.com/jellyfin/jellyfin-plugin-tvdb
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
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id021
      status: none
    slug: trakt
    status: profiled
    tags: &id022
    - Media Tracking
    - Movies
    - Television
    - Video
    url: /providers/trakt/
  layer: domain
  name: Trakt
  provider: trakt
  says: ships the Trakt SDK or integration code
  source: https://github.com/jellyfin/jellyfin-plugin-trakt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-streaming-media-server/jellyfin/
providers:
- agent_band: human-only
  agent_readiness: 1.1
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id001
  name: AniDB
  slug: anidb
  status: profiled
  tags: *id002
  url: /providers/anidb/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id003
  name: AniList
  slug: anilist
  status: profiled
  tags: *id004
  url: /providers/anilist/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id007
  name: ListenBrainz
  slug: listenbrainz
  status: profiled
  tags: *id008
  url: /providers/listenbrainz/
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
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id011
  name: OMDb
  slug: omdb
  status: profiled
  tags: *id012
  url: /providers/omdb/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id013
  name: OpenSubtitles
  slug: opensubtitles
  status: profiled
  tags: *id014
  url: /providers/opensubtitles/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id015
  name: The Movie Database
  slug: tmdb
  status: profiled
  tags: *id016
  url: /providers/tmdb/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.4
  mcp: *id017
  name: TheAudioDB
  slug: theaudiodb
  status: profiled
  tags: *id018
  url: /providers/theaudiodb/
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
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id021
  name: Trakt
  slug: trakt
  status: profiled
  tags: *id022
  url: /providers/trakt/
siblings:
- name: Emby
  rows: 3
  url: /applications/video-streaming-media-server/emby/
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
title: 'Jellyfin: Video Streaming & Media Server reference app'
---
