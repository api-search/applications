---
access: understanding
agent_layer: []
apps:
- anchor: jellyfin
  counts:
    declared: 0
    observed: 11
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
    layer: domain
    name: Trakt
    provider: trakt
    says: ships the Trakt SDK or integration code
    source: https://github.com/jellyfin/jellyfin-plugin-trakt
    tier: observed
  kind: self-hosted
  name: Jellyfin
  page: /applications/video-streaming-media-server/jellyfin/
  slug: jellyfin
  url: https://github.com/jellyfin/jellyfin
- anchor: peertube
  counts:
    declared: 3
    observed: 1
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
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
    tier: declared
  kind: self-hosted
  name: PeerTube
  page: /applications/video-streaming-media-server/peertube/
  slug: peertube
  url: https://github.com/Chocobozzz/PeerTube
- anchor: owncast
  counts:
    declared: 1
    observed: 2
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
    layer: common
    name: Oracle Cloud Object Storage
    provider: oracle-cloud
    says: lists Oracle Cloud Object Storage as an integration
    source: https://owncast.online/docs/storage/
    tier: declared
  kind: self-hosted
  name: Owncast
  page: /applications/video-streaming-media-server/owncast/
  slug: owncast
  url: https://github.com/owncast/owncast
- anchor: mediacms
  counts:
    declared: 0
    observed: 2
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
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://github.com/mediacms-io/mediacms/blob/main/requirements.txt
    tier: observed
  kind: self-hosted
  name: MediaCMS
  page: /applications/video-streaming-media-server/mediacms/
  slug: mediacms
  url: https://github.com/mediacms-io/mediacms
- anchor: plex
  counts:
    declared: 9
    observed: 1
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
    layer: domain
    name: TheTVDB
    provider: tvdb
    says: lists TheTVDB as an integration
    source: https://support.plex.tv/articles/200241558-agents/
    tier: declared
  kind: commercial
  name: Plex
  page: /applications/video-streaming-media-server/plex/
  slug: plex
  url: https://www.plex.tv/
- anchor: emby
  counts:
    declared: 3
    observed: 0
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
    layer: domain
    name: Trakt
    provider: trakt
    says: lists Trakt as an integration
    source: https://emby.media/support/articles/Plugins.html
    tier: declared
  kind: commercial
  name: Emby
  page: /applications/video-streaming-media-server/emby/
  slug: emby
  url: https://emby.media/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: video-streaming-media-server
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Entertainment
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Photo & Video
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Entertainment
  store: google-play
  url: https://play.google.com/store/apps/category/ENTERTAINMENT
- category: Video Players & Editors
  store: google-play
  url: https://play.google.com/store/apps/category/VIDEO_PLAYERS
- category: Media Streaming - Video Streaming
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#media-streaming---video-streaming
- category: Media Streaming - Multimedia Streaming
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#media-streaming---multimedia-streaming
name: Video Streaming & Media Server
needs:
- capability:
    attribution: Turbo EA
    id: BC-3710.20
    key: metadata-cataloguing
    name: Metadata Cataloguing
    url: /capabilities/metadata-cataloguing/
    via_parent: null
  fit: exact
  layer: domain
  why: film/TV/anime metadata and artwork scrapers -- the core of every media server library
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: music metadata (MusicBrainz, TheAudioDB, Last.fm, AllMusic)
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: watch/listen history sync (Trakt, ListenBrainz); no node fits, see NOTES candidate
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: S3-compatible storage for VOD files and live HLS segments
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: importing videos from hosted platforms (YouTube)
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: viewer geography from GeoIP databases
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: nearest
  layer: common
  why: go-live notifications to Discord
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error tracking (Sentry)
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: embedding video in an LMS via LTI (Moodle)
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.20
    key: AE-170.10.20
    name: Connected TV
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: nearest
  layer: domain
  why: live TV tuners and guide data (nearest; EPG is a candidate node)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-3710.20
      key: metadata-cataloguing
      name: Metadata Cataloguing
      url: /capabilities/metadata-cataloguing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Jellyfin
      - Plex
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: The Movie Database
      slug: tmdb
      sources:
      - https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Catalog
      - Discovery
      - Entertainment
      - Image
      tier: observed
      url: /providers/tmdb/
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - Jellyfin
      - Plex
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        status: unknown
      name: TheTVDB
      slug: tvdb
      sources:
      - https://github.com/jellyfin/jellyfin-plugin-tvdb
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Entertainment
      - Media Metadata
      - Movies
      - Television
      tier: observed
      url: /providers/tvdb/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Jellyfin
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: AniList
      slug: anilist
      sources:
      - https://github.com/jellyfin/jellyfin-plugin-anilist
      status: profiled
      tags:
      - Anime
      - Entertainment
      - Manga
      - Media
      tier: observed
      url: /providers/anilist/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Jellyfin
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: OMDb
      slug: omdb
      sources:
      - https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
      status: profiled
      tags:
      - Entertainment
      - Metadata
      - Movies
      - Television
      tier: observed
      url: /providers/omdb/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - Jellyfin
      band: minimal
      in_catalog: true
      kin_score: 7.3
      mcp:
        status: unknown
      name: AniDB
      slug: anidb
      sources:
      - https://github.com/jellyfin/jellyfin-plugin-anidb
      status: profiled
      tags:
      - Anime
      - Public APIs
      tier: observed
      url: /providers/anidb/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Plex
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: none
      name: IMDb
      slug: imdb
      sources:
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Company
      - Data
      - Entertainment
      - Movies
      tier: declared
      url: /providers/imdb/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.30
      key: AE-170.10.30
      name: Film & TV Metadata, Artwork & Subtitles
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Jellyfin
      - Plex
      band: minimal
      in_catalog: true
      kin_score: 10.3
      mcp:
        status: unknown
      name: Fanart.tv
      slug: fanart-tv
      sources:
      - https://github.com/jellyfin/jellyfin-plugin-fanart
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Company
      - Image
      - Media
      - Movies
      tier: observed
      url: /providers/fanart-tv/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Jellyfin
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        source: https://mcp.opensubtitles.com
        status: verified
      name: OpenSubtitles
      slug: opensubtitles
      sources:
      - https://github.com/jellyfin/jellyfin-plugin-opensubtitles
      status: profiled
      tags:
      - Company
      - Media
      - Subtitles
      - Video
      tier: observed
      url: /providers/opensubtitles/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Plex
      band: emerging
      in_catalog: true
      kin_score: 12.4
      mcp:
        status: unknown
      name: CineMaterial
      slug: cinematerial
      sources:
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Archives
      - Company
      - Media
      - Movies
      tier: declared
      url: /providers/cinematerial/
    - agent_band: null
      agent_readiness: null
      apps:
      - Plex
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Rotten Tomatoes
      slug: rotten-tomatoes
      sources:
      - https://support.plex.tv/articles/200241558-agents/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Jellyfin
      - Plex
      band: thin
      in_catalog: true
      kin_score: 38.2
      mcp:
        status: none
      name: MusicBrainz
      slug: musicbrainz
      sources:
      - https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Encyclopedia
      - Metadata
      - Music
      - Open Data
      tier: observed
      url: /providers/musicbrainz/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Jellyfin
      band: minimal
      in_catalog: true
      kin_score: 2.4
      mcp:
        status: none
      name: TheAudioDB
      slug: theaudiodb
      sources:
      - https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
      status: profiled
      tags:
      - Music
      - Public APIs
      tier: observed
      url: /providers/theaudiodb/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Plex
      band: strong
      in_catalog: true
      kin_score: 54.4
      mcp:
        status: none
      name: Last.fm
      slug: lastfm
      sources:
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Audio
      - Music
      - Recommendations
      - Scrobbling
      tier: declared
      url: /providers/lastfm/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Plex
      band: minimal
      in_catalog: true
      kin_score: 1.8
      mcp:
        status: unknown
      name: AllMusic
      slug: allmusic
      sources:
      - https://support.plex.tv/articles/200241558-agents/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/allmusic/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Emby
      - Jellyfin
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Trakt
      slug: trakt
      sources:
      - https://emby.media/support/articles/Plugins.html
      - https://github.com/jellyfin/jellyfin-plugin-trakt
      status: profiled
      tags:
      - Media Tracking
      - Movies
      - Television
      - Video
      tier: observed
      url: /providers/trakt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Jellyfin
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: ListenBrainz
      slug: listenbrainz
      sources:
      - https://github.com/jellyfin/jellyfin/tree/master/MediaBrowser.Providers/Plugins
      status: profiled
      tags:
      - Community
      - Data API
      - Music
      - Open Source
      tier: observed
      url: /providers/listenbrainz/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.20
      key: AE-170.10.20
      name: Connected TV
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Emby
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: unknown
      name: SiliconDust HDHomeRun
      slug: silicondust
      sources:
      - https://emby.media/support/articles/Live-TV.html
      status: profiled
      tags:
      - Company
      - Hardware
      - Streaming
      - TV
      tier: declared
      url: /providers/silicondust/
  - capability:
      attribution: Turbo EA
      id: BC-3730.20
      key: BC-3730.20
      name: Electronic Programme Guide Management
      url: /capabilities/electronic-programme-guide-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Emby
      band: emerging
      in_catalog: true
      kin_score: 15.1
      mcp:
        status: unknown
      name: Schedules Direct
      slug: schedules-direct
      sources:
      - https://emby.media/support/articles/Live-TV.html
      status: profiled
      tags:
      - Company
      - Non-Profit
      - Open Source
      - TV Listings
      tier: declared
      url: /providers/schedules-direct/
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - MediaCMS
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Moodle
      slug: moodle
      sources:
      - https://github.com/mediacms-io/mediacms/tree/main/lms-plugins
      status: profiled
      tags:
      - E-Learning
      - EdTech
      - LMS
      - Moodle
      tier: observed
      url: /providers/moodle/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - PeerTube
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - PeerTube
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: declared
      url: /providers/amazon-s3/
    - agent_band: agent-native
      agent_readiness: 53.7
      apps:
      - Owncast
      band: exemplar
      in_catalog: true
      kin_score: 75.6
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Cloud Object Storage
      slug: oracle-cloud
      sources:
      - https://owncast.online/docs/storage/
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Cloud
      - Infrastructure-as-a-Service
      - Oracle
      tier: declared
      url: /providers/oracle-cloud/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - PeerTube
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/scaleway/scaleway-cli
        status: verified
      name: Scaleway Object Storage
      slug: scaleway
      sources:
      - https://github.com/Chocobozzz/PeerTube/blob/develop/config/default.yaml
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud Computing
      - Containers
      - Database
      tier: declared
      url: /providers/scaleway/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Owncast
      - PeerTube
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind GeoIP
      slug: maxmind
      sources:
      - https://github.com/Chocobozzz/PeerTube/blob/develop/package.json
      - https://github.com/owncast/owncast/blob/develop/go.mod
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - MediaCMS
      - Plex
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/mediacms-io/mediacms/blob/main/requirements.txt
      - https://reports.exodus-privacy.eu.org/en/reports/com.plexapp.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Owncast
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/owncast/owncast/tree/develop/notifications/discord
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  layer: common
summary:
  coverage_pct: 96.2
  declared_only: 11
  distinct_providers: 26
  in_catalog: 25
  mcp:
    documented: 0
    none: 13
    unchecked: 1
    verified: 5
  mcp_verified: 5
  mean_kin_score: 34.3
  observed: 15
  queued: 1
  reference_apps: 6
title: 'Video Streaming & Media Server: application blueprint'
---
