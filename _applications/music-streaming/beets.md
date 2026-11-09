---
app: beets
app_slug: beets
app_url: https://github.com/beetbox/beets
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.60
  key: AE-170.20.60
  layer: domain
  name: Audio Fingerprinting & Music Recognition
  providers:
  - AcousticBrainz
  - AcoustID
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-230
  key: AE-230
  layer: domain
  name: Data & Reference Information Services
  providers:
  - DBpedia
  - Wikipedia
  url: /capabilities/data-reference-information-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - AlbumArt.org
  - Amazon
  - Apple (iTunes Search API)
  - Beatport
  - Cover Art Archive
  - Deezer
  - Discogs
  - Fanart.tv
  - Last.fm
  - MusicBrainz
  - Spotify
  - TIDAL
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.90
  key: AE-170.90
  layer: domain
  name: Self-Hosted Media Servers & Library Automation
  providers:
  - Emby
  - Kodi
  - Plex
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Sonos
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.50
  key: AE-170.20.50
  layer: domain
  name: Song Lyrics & Synced Lyrics
  providers:
  - Genius
  - LRCLIB
  - LRCMux
  - Musixmatch
  - Tekstowo
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
- attribution: API Evangelist extension
  id: AE-240.90
  key: AE-240.90
  layer: common
  name: Decentralized Storage & Compute
  providers:
  - IPFS
  url: /capabilities/decentralized-storage-compute/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - Azure AI Translator
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-230.40.20
  key: AE-230.40.20
  layer: common
  name: Web Search APIs
  providers:
  - Google Custom Search
  url: /capabilities/web-data/
  via_parent: Web Data
category:
  id: music-streaming
  name: Music & Audio Streaming
  url: /applications/music-streaming/
counts:
  declared: 0
  observed: 30
credits: []
evidence:
- route: source code
  url: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
- route: source code
  url: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
- route: source code
  url: https://github.com/beetbox/beets/tree/master/beetsplug
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.60
    key: AE-170.20.60
    name: Audio Fingerprinting & Music Recognition
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id002
      status: unchecked
    slug: acousticbrainz
    status: queued for profiling
    tags: &id003 []
    url: null
  layer: domain
  name: AcousticBrainz
  provider: acousticbrainz
  says: ships the AcousticBrainz SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.60
    key: AE-170.20.60
    name: Audio Fingerprinting & Music Recognition
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id004
      status: none
    slug: acoustid
    status: profiled
    tags: &id005
    - Audio
    - Fingerprinting
    - Music
    - MusicBrainz
    url: /providers/acoustid/
  layer: domain
  name: AcoustID
  provider: acoustid
  says: ships the AcoustID SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    kin_score: 1.3
    mcp: &id006
      status: unknown
    slug: albumart-org
    status: profiled
    tags: &id007
    - Company
    url: /providers/albumart-org/
  layer: domain
  name: AlbumArt.org
  provider: albumart-org
  says: ships the AlbumArt.org SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
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
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id008
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id009
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon
  provider: amazon
  says: ships the Amazon SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
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
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id010
      status: none
    slug: apple
    status: profiled
    tags: &id011
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple (iTunes Search API)
  provider: apple
  says: ships the Apple (iTunes Search API) SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id012
      source: https://github.com/microsoft/azure-speech-mcp-server
      status: verified
    slug: microsoft-cognitive-services
    status: profiled
    tags: &id013
    - Azure AI
    - Computer Vision
    - Natural Language Processing
    - Speech
    url: /providers/microsoft-cognitive-services/
  layer: common
  name: Azure AI Translator
  provider: microsoft-cognitive-services
  says: ships the Azure AI Translator SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
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
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id014
      status: none
    slug: beatport
    status: profiled
    tags: &id015
    - DJ
    - Dance Music
    - Electronic Music
    - Music
    url: /providers/beatport/
  layer: domain
  name: Beatport
  provider: beatport
  says: ships the Beatport SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    kin_score: 6.7
    mcp: &id016
      status: none
    slug: cover-art-archive
    status: profiled
    tags: &id017
    - Community
    - CoverArt
    - Music
    - Open Data
    url: /providers/cover-art-archive/
  layer: domain
  name: Cover Art Archive
  provider: cover-art-archive
  says: ships the Cover Art Archive SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id018
      status: none
    slug: dbpedia
    status: profiled
    tags: &id019
    - Knowledge Graph
    - Linked Data
    - SPARQL
    - Semantic Web
    url: /providers/dbpedia/
  layer: domain
  name: DBpedia
  provider: dbpedia
  says: ships the DBpedia SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
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
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id020
      status: none
    slug: deezer
    status: profiled
    tags: &id021
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/deezer/
  layer: domain
  name: Deezer
  provider: deezer
  says: ships the Deezer SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    agent_band: agent-ready
    agent_readiness: 32.9
    band: thin
    in_catalog: true
    kin_score: 36.6
    mcp: &id022
      status: none
    slug: discogs
    status: profiled
    tags: &id023
    - Catalog
    - Community
    - Marketplace
    - Music
    url: /providers/discogs/
  layer: domain
  name: Discogs
  provider: discogs
  says: ships the Discogs SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id024
      status: none
    slug: emby
    status: profiled
    tags: &id025
    - Media Server
    - Personal Media
    - Streaming
    - Video Library
    url: /providers/emby/
  layer: domain
  name: Emby
  provider: emby
  says: ships the Emby SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    kin_score: 7.8
    mcp: &id026
      status: unknown
    slug: fanart-tv
    status: profiled
    tags: &id027
    - Company
    - Image
    - Media
    - Movies
    url: /providers/fanart-tv/
  layer: domain
  name: Fanart.tv
  provider: fanart-tv
  says: ships the Fanart.tv SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.50
    key: AE-170.20.50
    name: Song Lyrics & Synced Lyrics
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id028
      status: none
    slug: genius
    status: profiled
    tags: &id029
    - Annotation
    - Crowdsourced
    - Lyrics
    - Music
    url: /providers/genius/
  layer: domain
  name: Genius
  provider: genius
  says: ships the Genius SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 51.1
    mcp: &id030
      status: none
    slug: google-custom-search
    status: profiled
    tags: &id031
    - Custom Search
    - Google
    - Image Search
    - Search
    url: /providers/google-custom-search/
  layer: common
  name: Google Custom Search
  provider: google-custom-search
  says: ships the Google Custom Search SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.90
    key: AE-240.90
    name: Decentralized Storage & Compute
    url: /capabilities/decentralized-storage-compute/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id032
      status: none
    slug: ipfs
    status: profiled
    tags: &id033
    - Content-Addressed
    - Decentralized
    - Distributed Storage
    - IPFS
    url: /providers/ipfs/
  layer: common
  name: IPFS
  provider: ipfs
  says: ships the IPFS SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 13.3
    mcp: &id034
      status: none
    slug: kodi
    status: profiled
    tags: &id035
    - Entertainment
    - Home-Theater
    - Media
    - Open Source
    url: /providers/kodi/
  layer: domain
  name: Kodi
  provider: kodi
  says: ships the Kodi SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    mcp: &id036
      status: none
    slug: lastfm
    status: profiled
    tags: &id037
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
  layer: domain
  name: Last.fm
  provider: lastfm
  says: ships the Last.fm SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    mcp: &id038
      status: none
    slug: listenbrainz
    status: profiled
    tags: &id039
    - Community
    - Data API
    - Music
    - Open Source
    url: /providers/listenbrainz/
  layer: domain
  name: ListenBrainz
  provider: listenbrainz
  says: ships the ListenBrainz SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.50
    key: AE-170.20.50
    name: Song Lyrics & Synced Lyrics
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id040
      status: unknown
    slug: lrclib
    status: profiled
    tags: &id041
    - Company
    - Lyrics
    - Music
    - Open Source
    url: /providers/lrclib/
  layer: domain
  name: LRCLIB
  provider: lrclib
  says: ships the LRCLIB SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.50
    key: AE-170.20.50
    name: Song Lyrics & Synced Lyrics
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: emerging
    in_catalog: true
    kin_score: 22.7
    mcp: &id042
      status: unknown
    slug: lrcmux
    status: profiled
    tags: &id043
    - Free
    - Lyrics
    - Music
    - No Auth
    url: /providers/lrcmux/
  layer: domain
  name: LRCMux
  provider: lrcmux
  says: ships the LRCMux SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
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
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id044
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id045
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
  layer: domain
  name: MusicBrainz
  provider: musicbrainz
  says: ships the MusicBrainz SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.50
    key: AE-170.20.50
    name: Song Lyrics & Synced Lyrics
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id046
      status: none
    slug: musixmatch
    status: profiled
    tags: &id047
    - Lyrics
    - Music
    - Translation
    url: /providers/musixmatch/
  layer: domain
  name: Musixmatch
  provider: musixmatch
  says: ships the Musixmatch SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.6
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id048
      status: none
    slug: plex
    status: profiled
    tags: &id049
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: ships the Plex SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.6
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id050
      status: none
    slug: sonos
    status: profiled
    tags: &id051
    - Audio
    - Company
    - Consumer
    - Music
    url: /providers/sonos/
  layer: domain
  name: Sonos
  provider: sonos
  says: ships the Sonos SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
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
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id052
      status: none
    slug: spotify
    status: profiled
    tags: &id053
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.50
    key: AE-170.20.50
    name: Song Lyrics & Synced Lyrics
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id054
      status: unknown
    slug: tekstowo
    status: profiled
    tags: &id055
    - Community
    - Lyrics
    - Music
    - Polish
    url: /providers/tekstowo/
  layer: domain
  name: Tekstowo
  provider: tekstowo
  says: ships the Tekstowo SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
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
    agent_band: agent-ready
    agent_readiness: 34.6
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id056
      status: none
    slug: tidal
    status: profiled
    tags: &id057
    - Hi-Fi
    - HiRes Lossless
    - Music
    - Streaming
    url: /providers/tidal/
  layer: domain
  name: TIDAL
  provider: tidal
  says: ships the TIDAL SDK or integration code
  source: https://github.com/beetbox/beets/tree/master/beetsplug
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id058
      status: none
    slug: wikipedia
    status: profiled
    tags: &id059
    - Encyclopedia
    - Open Data
    - Open Knowledge
    - Public APIs
    url: /providers/wikipedia/
  layer: domain
  name: Wikipedia
  provider: wikipedia
  says: ships the Wikipedia SDK or integration code
  source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/music-streaming/beets/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id002
  name: AcousticBrainz
  slug: acousticbrainz
  status: queued for profiling
  tags: *id003
  url: null
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id004
  name: AcoustID
  slug: acoustid
  status: profiled
  tags: *id005
  url: /providers/acoustid/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id006
  name: AlbumArt.org
  slug: albumart-org
  status: profiled
  tags: *id007
  url: /providers/albumart-org/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id008
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id009
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id010
  name: Apple (iTunes Search API)
  slug: apple
  status: profiled
  tags: *id011
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id012
  name: Azure AI Translator
  slug: microsoft-cognitive-services
  status: profiled
  tags: *id013
  url: /providers/microsoft-cognitive-services/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id014
  name: Beatport
  slug: beatport
  status: profiled
  tags: *id015
  url: /providers/beatport/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id016
  name: Cover Art Archive
  slug: cover-art-archive
  status: profiled
  tags: *id017
  url: /providers/cover-art-archive/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id018
  name: DBpedia
  slug: dbpedia
  status: profiled
  tags: *id019
  url: /providers/dbpedia/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id020
  name: Deezer
  slug: deezer
  status: profiled
  tags: *id021
  url: /providers/deezer/
- agent_band: agent-ready
  agent_readiness: 32.9
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id022
  name: Discogs
  slug: discogs
  status: profiled
  tags: *id023
  url: /providers/discogs/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id024
  name: Emby
  slug: emby
  status: profiled
  tags: *id025
  url: /providers/emby/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id026
  name: Fanart.tv
  slug: fanart-tv
  status: profiled
  tags: *id027
  url: /providers/fanart-tv/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id028
  name: Genius
  slug: genius
  status: profiled
  tags: *id029
  url: /providers/genius/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id030
  name: Google Custom Search
  slug: google-custom-search
  status: profiled
  tags: *id031
  url: /providers/google-custom-search/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id032
  name: IPFS
  slug: ipfs
  status: profiled
  tags: *id033
  url: /providers/ipfs/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 13.3
  mcp: *id034
  name: Kodi
  slug: kodi
  status: profiled
  tags: *id035
  url: /providers/kodi/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id036
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id037
  url: /providers/lastfm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id038
  name: ListenBrainz
  slug: listenbrainz
  status: profiled
  tags: *id039
  url: /providers/listenbrainz/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id040
  name: LRCLIB
  slug: lrclib
  status: profiled
  tags: *id041
  url: /providers/lrclib/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id042
  name: LRCMux
  slug: lrcmux
  status: profiled
  tags: *id043
  url: /providers/lrcmux/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id044
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id045
  url: /providers/musicbrainz/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id046
  name: Musixmatch
  slug: musixmatch
  status: profiled
  tags: *id047
  url: /providers/musixmatch/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id048
  name: Plex
  slug: plex
  status: profiled
  tags: *id049
  url: /providers/plex/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id050
  name: Sonos
  slug: sonos
  status: profiled
  tags: *id051
  url: /providers/sonos/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id052
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id053
  url: /providers/spotify/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id054
  name: Tekstowo
  slug: tekstowo
  status: profiled
  tags: *id055
  url: /providers/tekstowo/
- agent_band: agent-ready
  agent_readiness: 34.6
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id056
  name: TIDAL
  slug: tidal
  status: profiled
  tags: *id057
  url: /providers/tidal/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id058
  name: Wikipedia
  slug: wikipedia
  status: profiled
  tags: *id059
  url: /providers/wikipedia/
siblings:
- name: Ampache
  rows: 27
  url: /applications/music-streaming/ampache/
- name: Funkwhale
  rows: 7
  url: /applications/music-streaming/funkwhale/
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
title: 'beets: Music & Audio Streaming reference app'
---
