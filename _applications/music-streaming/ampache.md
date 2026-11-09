---
app: Ampache
app_slug: ampache
app_url: https://github.com/ampache/ampache
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Amazon
  - Apple (iTunes)
  - Deezer
  - Discogs
  - MusicBrainz
  - TheAudioDB
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Flickr
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.90
  key: AE-170.90
  layer: domain
  name: Self-Hosted Media Servers & Library Automation
  providers:
  - AudioMuse-AI
  - Headphones
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.50
  key: AE-170.20.50
  layer: domain
  name: Song Lyrics & Synced Lyrics
  providers:
  - ChartLyrics
  - LRCLIB
  - Lyrist
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
  url: /capabilities/watch-listen-history-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - Gravatar
  - Libravatar
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: common
  name: Link Shortening & Link-in-Bio
  providers:
  - Bitly
  - YOURLS
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - Matomo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Bluesky
  - Facebook
  - Mastodon
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
category:
  id: music-streaming
  name: Music & Audio Streaming
  url: /applications/music-streaming/
counts:
  declared: 0
  observed: 27
credits: []
evidence:
- route: source code
  url: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon
  provider: amazon
  says: ships the Amazon SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple (iTunes)
  provider: apple
  says: ships the Apple (iTunes) SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    agent_readiness: 7.9
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id005
      status: unknown
    slug: audiomuse
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Music
    - Open Source
    - Self-Hosted
    url: /providers/audiomuse/
  layer: domain
  name: AudioMuse-AI
  provider: audiomuse
  says: ships the AudioMuse-AI SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.4
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id007
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id008
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
  layer: common
  name: Bitly
  provider: bitly
  says: ships the Bitly SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id009
      status: none
    slug: bluesky
    status: profiled
    tags: &id010
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: common
  name: Bluesky
  provider: bluesky
  says: ships the Bluesky SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: chartlyrics
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: ChartLyrics
  provider: chartlyrics
  says: ships the ChartLyrics SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    mcp: &id013
      status: none
    slug: deezer
    status: profiled
    tags: &id014
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/deezer/
  layer: domain
  name: Deezer
  provider: deezer
  says: ships the Deezer SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    mcp: &id015
      status: none
    slug: discogs
    status: profiled
    tags: &id016
    - Catalog
    - Community
    - Marketplace
    - Music
    url: /providers/discogs/
  layer: domain
  name: Discogs
  provider: discogs
  says: ships the Discogs SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id019
      status: none
    slug: flickr
    status: profiled
    tags: &id020
    - Photography
    - Photos
    - Public APIs
    - Social Media
    url: /providers/flickr/
  layer: domain
  name: Flickr
  provider: flickr
  says: ships the Flickr SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id021
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id022
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id023
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id024
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id025
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id026
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
  layer: common
  name: Gravatar
  provider: gravatar
  says: ships the Gravatar SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    band: minimal
    in_catalog: true
    kin_score: 3.5
    mcp: &id027
      status: unknown
    slug: headphones
    status: profiled
    tags: &id028
    - Company
    - Harvest
    - Placeholder
    url: /providers/headphones/
  layer: domain
  name: Headphones
  provider: headphones
  says: ships the Headphones SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    agent_readiness: 23.7
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id029
      status: none
    slug: lastfm
    status: profiled
    tags: &id030
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
  layer: domain
  name: Last.fm
  provider: lastfm
  says: ships the Last.fm SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.3
    mcp: &id031
      status: none
    slug: libravatar
    status: profiled
    tags: &id032
    - Avatars
    - Company
    - Federated
    - Open Source
    url: /providers/libravatar/
  layer: common
  name: Libravatar
  provider: libravatar
  says: ships the Libravatar SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 14.8
    mcp: &id033
      status: none
    slug: libre-fm
    status: profiled
    tags: &id034
    - Company
    - Music
    - Open Source
    - Scrobbling
    url: /providers/libre-fm/
  layer: domain
  name: Libre.fm
  provider: libre-fm
  says: ships the Libre.fm SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    mcp: &id035
      status: none
    slug: listenbrainz
    status: profiled
    tags: &id036
    - Community
    - Data API
    - Music
    - Open Source
    url: /providers/listenbrainz/
  layer: domain
  name: ListenBrainz
  provider: listenbrainz
  says: ships the ListenBrainz SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    mcp: &id037
      status: unknown
    slug: lrclib
    status: profiled
    tags: &id038
    - Company
    - Lyrics
    - Music
    - Open Source
    url: /providers/lrclib/
  layer: domain
  name: LRCLIB
  provider: lrclib
  says: ships the LRCLIB SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    kin_score: 4.2
    mcp: &id039
      status: unknown
    slug: lyrist
    status: profiled
    tags: &id040
    - Lyrics
    - Music
    - Next.js
    - Vercel
    url: /providers/lyrist/
  layer: domain
  name: Lyrist
  provider: lyrist
  says: ships the Lyrist SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id041
      status: none
    slug: mastodon
    status: profiled
    tags: &id042
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
  layer: common
  name: Mastodon
  provider: mastodon
  says: ships the Mastodon SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.4
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id043
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id044
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    mcp: &id045
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id046
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
  layer: domain
  name: MusicBrainz
  provider: musicbrainz
  says: ships the MusicBrainz SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id047
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id048
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
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
    kin_score: 3.3
    mcp: &id049
      status: none
    slug: theaudiodb
    status: profiled
    tags: &id050
    - Music
    - Public APIs
    url: /providers/theaudiodb/
  layer: domain
  name: TheAudioDB
  provider: theaudiodb
  says: ships the TheAudioDB SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id051
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id052
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 14.8
    mcp: &id053
      status: none
    slug: yourls
    status: profiled
    tags: &id054
    - Company
    - Open Source
    - PHP
    - URL Shorteners
    url: /providers/yourls/
  layer: common
  name: YOURLS
  provider: yourls
  says: ships the YOURLS SDK or integration code
  source: https://github.com/ampache/ampache/tree/develop/src/Plugin
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/music-streaming/ampache/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple (iTunes)
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id005
  name: AudioMuse-AI
  slug: audiomuse
  status: profiled
  tags: *id006
  url: /providers/audiomuse/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id007
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id008
  url: /providers/bitly/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id009
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id010
  url: /providers/bluesky/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: ChartLyrics
  slug: chartlyrics
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id013
  name: Deezer
  slug: deezer
  status: profiled
  tags: *id014
  url: /providers/deezer/
- agent_band: agent-ready
  agent_readiness: 32.9
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id015
  name: Discogs
  slug: discogs
  status: profiled
  tags: *id016
  url: /providers/discogs/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id019
  name: Flickr
  slug: flickr
  status: profiled
  tags: *id020
  url: /providers/flickr/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id021
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id022
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id023
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id024
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id025
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id026
  url: /providers/gravatar/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 3.5
  mcp: *id027
  name: Headphones
  slug: headphones
  status: profiled
  tags: *id028
  url: /providers/headphones/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id029
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id030
  url: /providers/lastfm/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.3
  mcp: *id031
  name: Libravatar
  slug: libravatar
  status: profiled
  tags: *id032
  url: /providers/libravatar/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 14.8
  mcp: *id033
  name: Libre.fm
  slug: libre-fm
  status: profiled
  tags: *id034
  url: /providers/libre-fm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id035
  name: ListenBrainz
  slug: listenbrainz
  status: profiled
  tags: *id036
  url: /providers/listenbrainz/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id037
  name: LRCLIB
  slug: lrclib
  status: profiled
  tags: *id038
  url: /providers/lrclib/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id039
  name: Lyrist
  slug: lyrist
  status: profiled
  tags: *id040
  url: /providers/lyrist/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id041
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id042
  url: /providers/mastodon/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id043
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id044
  url: /providers/matomo/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id045
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id046
  url: /providers/musicbrainz/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id047
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id048
  url: /providers/paypal/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id049
  name: TheAudioDB
  slug: theaudiodb
  status: profiled
  tags: *id050
  url: /providers/theaudiodb/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id051
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id052
  url: /providers/x/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.8
  mcp: *id053
  name: YOURLS
  slug: yourls
  status: profiled
  tags: *id054
  url: /providers/yourls/
siblings:
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
- name: Navidrome
  rows: 4
  url: /applications/music-streaming/navidrome/
- name: Spotify
  rows: 4
  url: /applications/music-streaming/spotify/
sitemap: true
title: 'Ampache: Music & Audio Streaming reference app'
---
