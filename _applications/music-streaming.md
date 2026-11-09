---
access: understanding
agent_layer: []
apps:
- anchor: navidrome
  counts:
    declared: 0
    observed: 4
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
    layer: domain
    name: ListenBrainz
    provider: listenbrainz
    says: ships the ListenBrainz SDK or integration code
    source: https://github.com/navidrome/navidrome/tree/master/adapters
    tier: observed
  kind: self-hosted
  name: Navidrome
  page: /applications/music-streaming/navidrome/
  slug: navidrome
  url: https://github.com/navidrome/navidrome
- anchor: funkwhale
  counts:
    declared: 0
    observed: 7
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
    layer: common
    name: Typesense
    provider: typesense
    says: ships the Typesense SDK or integration code
    source: https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
    tier: observed
  kind: self-hosted
  name: Funkwhale
  page: /applications/music-streaming/funkwhale/
  slug: funkwhale
  url: https://dev.funkwhale.audio/funkwhale/funkwhale
- anchor: koel
  counts:
    declared: 10
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/koel/koel/blob/master/composer.json
  - route: source code
    url: https://github.com/koel/koel/blob/master/.env.example
  - route: source code
    url: https://github.com/koel/koel/blob/master/config/services.php
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Algolia
    provider: algolia
    says: ships the Algolia SDK or integration code
    source: https://github.com/koel/koel/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/koel/koel/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Gravatar
    provider: gravatar
    says: ships the Gravatar SDK or integration code
    source: https://github.com/koel/koel/blob/master/config/services.php
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
    name: Laravel Nightwatch
    provider: laravel
    says: ships the Laravel Nightwatch SDK or integration code
    source: https://github.com/koel/koel/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Meilisearch
    provider: meilisearch
    says: ships the Meilisearch SDK or integration code
    source: https://github.com/koel/koel/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://github.com/koel/koel/blob/master/composer.json
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
    source: https://github.com/koel/koel/blob/master/composer.json
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
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/koel/koel/blob/master/composer.json
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
    source: https://github.com/koel/koel/blob/master/.env.example
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
    name: Cloudflare R2
    provider: cloudflare-r2
    says: lists Cloudflare R2 as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
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
    name: DigitalOcean Spaces
    provider: digital-ocean
    says: lists DigitalOcean Spaces as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: lists Google sign-in as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: IPinfo
    provider: ipinfo
    says: lists IPinfo as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
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
    source: https://github.com/koel/koel/blob/master/.env.example
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
    name: ListenBrainz
    provider: listenbrainz
    says: lists ListenBrainz as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
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
    source: https://github.com/koel/koel/blob/master/.env.example
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: Ticketmaster
    provider: ticketmaster
    says: lists Ticketmaster as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://github.com/koel/koel/blob/master/.env.example
    tier: declared
  kind: self-hosted
  name: Koel
  page: /applications/music-streaming/koel/
  slug: koel
  url: https://github.com/koel/koel
- anchor: ampache
  counts:
    declared: 0
    observed: 27
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
    layer: common
    name: YOURLS
    provider: yourls
    says: ships the YOURLS SDK or integration code
    source: https://github.com/ampache/ampache/tree/develop/src/Plugin
    tier: observed
  kind: self-hosted
  name: Ampache
  page: /applications/music-streaming/ampache/
  slug: ampache
  url: https://github.com/ampache/ampache
- anchor: beets
  counts:
    declared: 0
    observed: 30
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
    layer: domain
    name: Wikipedia
    provider: wikipedia
    says: ships the Wikipedia SDK or integration code
    source: https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
    tier: observed
  kind: self-hosted
  name: beets
  page: /applications/music-streaming/beets/
  slug: beets
  url: https://github.com/beetbox/beets
- anchor: lidarr
  counts:
    declared: 0
    observed: 24
  evidence:
  - route: source code
    url: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
  - route: source code
    url: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/MetadataSource
  - route: source code
    url: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Emby
    provider: emby
    says: ships the Emby SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Gotify
    provider: gotify
    says: ships the Gotify SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Headphones
    provider: headphones
    says: ships the Headphones SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Join (joaoapps)
    provider: joaoapps-join
    says: ships the Join (joaoapps) SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Kodi
    provider: kodi
    says: ships the Kodi SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    name: Last.fm
    provider: lastfm
    says: ships the Last.fm SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Notifiarr
    provider: notifiarr
    says: ships the Notifiarr SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: ntfy
    provider: ntfy
    says: ships the ntfy SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Plex
    provider: plex
    says: ships the Plex SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Prowl
    provider: prowl
    says: ships the Prowl SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Pushbullet
    provider: pushbullet
    says: ships the Pushbullet SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Pushcut
    provider: pushcut
    says: ships the Pushcut SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Signal
    provider: signal
    says: ships the Signal SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Simplepush
    provider: simplepush
    says: ships the Simplepush SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Synology
    provider: synology
    says: ships the Synology SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
    tier: observed
  kind: self-hosted
  name: Lidarr
  page: /applications/music-streaming/lidarr/
  slug: lidarr
  url: https://github.com/Lidarr/Lidarr
- anchor: spotify
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
    tier: observed
  kind: commercial
  name: Spotify
  page: /applications/music-streaming/spotify/
  slug: spotify
  url: https://www.spotify.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: music-streaming
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Music
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Music & Audio
  store: google-play
  url: https://play.google.com/store/apps/category/MUSIC_AND_AUDIO
- category: Media Streaming - Audio Streaming
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#media-streaming---audio-streaming
name: Music & Audio Streaming
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: music catalog metadata, art and previews (lyrics and fingerprinting rows sit here as gap)
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: scrobbling and listen-history sync
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: used by reference apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  fit: exact
  layer: domain
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-240.90
    key: AE-240.90
    name: Decentralized Storage & Compute
    url: /capabilities/decentralized-storage-compute/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: used by reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-3770.50
    key: audience-insights-research-management
    name: Audience Insights & Research Management
    url: /capabilities/audience-insights-research-management/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Ampache
      - Funkwhale
      - Koel
      - Lidarr
      - beets
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        status: none
      name: MusicBrainz
      slug: musicbrainz
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Encyclopedia
      - Metadata
      - Music
      - Open Data
      tier: observed
      url: /providers/musicbrainz/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Koel
      - Lidarr
      - Navidrome
      - beets
      band: developing
      in_catalog: true
      kin_score: 54.2
      mcp: &id001
        status: none
      name: Last.fm
      slug: lastfm
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
      - https://github.com/beetbox/beets/tree/master/beetsplug
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags: &id002
      - Audio
      - Music
      - Recommendations
      - Scrobbling
      tier: observed
      url: /providers/lastfm/
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Koel
      - Lidarr
      - beets
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
      - https://github.com/beetbox/beets/tree/master/beetsplug
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Ampache
      - Navidrome
      - beets
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: Deezer
      slug: deezer
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/tree/master/beetsplug
      - https://github.com/navidrome/navidrome/tree/master/adapters
      status: profiled
      tags:
      - Audio
      - Music
      - OAuth
      - Streaming
      tier: observed
      url: /providers/deezer/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Ampache
      - beets
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple (iTunes)
      slug: apple
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Ampache
      - beets
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 32.9
      apps:
      - Ampache
      - beets
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        status: none
      name: Discogs
      slug: discogs
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Catalog
      - Community
      - Marketplace
      - Music
      tier: observed
      url: /providers/discogs/
    - agent_band: agent-ready
      agent_readiness: 34.6
      apps:
      - beets
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        status: none
      name: TIDAL
      slug: tidal
      sources:
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Hi-Fi
      - HiRes Lossless
      - Music
      - Streaming
      tier: observed
      url: /providers/tidal/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - beets
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: none
      name: Beatport
      slug: beatport
      sources:
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - DJ
      - Dance Music
      - Electronic Music
      - Music
      tier: observed
      url: /providers/beatport/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - beets
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        status: unknown
      name: Fanart.tv
      slug: fanart-tv
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
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
      - beets
      band: minimal
      in_catalog: true
      kin_score: 6.7
      mcp:
        status: none
      name: Cover Art Archive
      slug: cover-art-archive
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Community
      - CoverArt
      - Music
      - Open Data
      tier: observed
      url: /providers/cover-art-archive/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ampache
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: none
      name: TheAudioDB
      slug: theaudiodb
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Music
      - Public APIs
      tier: observed
      url: /providers/theaudiodb/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - beets
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: AlbumArt.org
      slug: albumart-org
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/albumart-org/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ampache
      - Funkwhale
      - Koel
      - Navidrome
      - beets
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: none
      name: ListenBrainz
      slug: listenbrainz
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/tree/develop/api/funkwhale_api/contrib
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Community
      - Data API
      - Music
      - Open Source
      tier: observed
      url: /providers/listenbrainz/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Ampache
      - Funkwhale
      - Navidrome
      - beets
      band: developing
      in_catalog: true
      kin_score: 54.2
      mcp: *id001
      name: Last.fm
      slug: lastfm
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/funkwhale_api/contrib/scrobbler/funkwhale_startup.py
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/lastfm/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Ampache
      - Funkwhale
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: none
      name: Libre.fm
      slug: libre-fm
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/funkwhale_api/contrib/scrobbler/funkwhale_startup.py
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Company
      - Music
      - Open Source
      - Scrobbling
      tier: observed
      url: /providers/libre-fm/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Funkwhale
      band: emerging
      in_catalog: true
      kin_score: 17.1
      mcp:
        status: unknown
      name: Maloja
      slug: maloja
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/tree/develop/api/funkwhale_api/contrib
      status: profiled
      tags:
      - Music
      - Scrobble
      - Self-Hosted
      - Statistics
      tier: observed
      url: /providers/maloja/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.6
      apps:
      - Lidarr
      - beets
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: Plex
      slug: plex
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Company
      - Media
      - Streaming
      - Video
      tier: observed
      url: /providers/plex/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Lidarr
      - beets
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Emby
      slug: emby
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Media Server
      - Personal Media
      - Streaming
      - Video Library
      tier: observed
      url: /providers/emby/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Lidarr
      - beets
      band: emerging
      in_catalog: true
      kin_score: 13.3
      mcp:
        status: none
      name: Kodi
      slug: kodi
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Entertainment
      - Home-Theater
      - Media
      - Open Source
      tier: observed
      url: /providers/kodi/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Ampache
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 3.5
      mcp:
        status: unknown
      name: Headphones
      slug: headphones
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Company
      - Harvest
      - Placeholder
      tier: observed
      url: /providers/headphones/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Ampache
      band: minimal
      in_catalog: true
      kin_score: 10.3
      mcp:
        status: unknown
      name: AudioMuse-AI
      slug: audiomuse
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Artificial Intelligence
      - Music
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/audiomuse/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: none
      name: Synology
      slug: synology
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Backup
      - Cloud
      - Company
      - Storage
      tier: observed
      url: /providers/synology/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.50
      key: AE-170.20.50
      name: Song Lyrics & Synced Lyrics
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - Ampache
      - beets
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: unknown
      name: LRCLIB
      slug: lrclib
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
      status: profiled
      tags:
      - Company
      - Lyrics
      - Music
      - Open Source
      tier: observed
      url: /providers/lrclib/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - beets
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        status: none
      name: Genius
      slug: genius
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
      status: profiled
      tags:
      - Annotation
      - Crowdsourced
      - Lyrics
      - Music
      tier: observed
      url: /providers/genius/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - beets
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Musixmatch
      slug: musixmatch
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
      status: profiled
      tags:
      - Lyrics
      - Music
      - Translation
      tier: observed
      url: /providers/musixmatch/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - beets
      band: emerging
      in_catalog: true
      kin_score: 22.7
      mcp:
        status: unknown
      name: LRCMux
      slug: lrcmux
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
      status: profiled
      tags:
      - Free
      - Lyrics
      - Music
      - No Auth
      tier: observed
      url: /providers/lrcmux/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ampache
      band: minimal
      in_catalog: true
      kin_score: 4.2
      mcp:
        status: unknown
      name: Lyrist
      slug: lyrist
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Lyrics
      - Music
      - Next.js
      - Vercel
      tier: observed
      url: /providers/lyrist/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - beets
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: Tekstowo
      slug: tekstowo
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
      status: profiled
      tags:
      - Community
      - Lyrics
      - Music
      - Polish
      tier: observed
      url: /providers/tekstowo/
    - agent_band: null
      agent_readiness: null
      apps:
      - Ampache
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: ChartLyrics
      slug: chartlyrics
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.60
      key: AE-170.20.60
      name: Audio Fingerprinting & Music Recognition
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - beets
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: none
      name: AcoustID
      slug: acoustid
      sources:
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Audio
      - Fingerprinting
      - Music
      - MusicBrainz
      tier: observed
      url: /providers/acoustid/
    - agent_band: null
      agent_readiness: null
      apps:
      - beets
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: AcousticBrainz
      slug: acousticbrainz
      sources:
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - beets
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Wikipedia
      slug: wikipedia
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Encyclopedia
      - Open Data
      - Open Knowledge
      - Public APIs
      tier: observed
      url: /providers/wikipedia/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - beets
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: none
      name: DBpedia
      slug: dbpedia
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Knowledge Graph
      - Linked Data
      - SPARQL
      - Semantic Web
      tier: observed
      url: /providers/dbpedia/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Koel
      band: thin
      in_catalog: true
      kin_score: 38.5
      mcp:
        status: none
      name: Ticketmaster
      slug: ticketmaster
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags:
      - Commerce
      - Concerts
      - Entertainment
      - Event
      tier: declared
      url: /providers/ticketmaster/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Ampache
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - beets
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Sonos
      slug: sonos
      sources:
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Audio
      - Company
      - Consumer
      - Music
      tier: observed
      url: /providers/sonos/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Koel
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
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
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - Lidarr
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: unknown
      name: Pushcut
      slug: pushcut
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Automation
      - Company
      - Shortcuts
      - iOS
      tier: observed
      url: /providers/pushcut/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Lidarr
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Pushbullet
      slug: pushbullet
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Device Sync
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushbullet/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Lidarr
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        source: https://gotify.net/docs/mcp
        status: verified
      name: Gotify
      slug: gotify
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Messaging
      - Notification
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/gotify/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 6.3
      mcp:
        status: unknown
      name: Prowl
      slug: prowl
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Company
      - Mobile
      - Push Notifications
      - iOS
      tier: observed
      url: /providers/prowl/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: unknown
      name: Join (joaoapps)
      slug: joaoapps-join
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/joaoapps-join/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Lidarr
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        source: https://notifiarr.com/api/mcp
        status: documented
      name: Notifiarr
      slug: notifiarr
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Company
      - Integration
      - Monitoring
      - Notification
      tier: observed
      url: /providers/notifiarr/
    - agent_band: null
      agent_readiness: null
      apps:
      - Lidarr
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Simplepush
      slug: simplepush
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Ampache
      - Lidarr
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - Ampache
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: Bluesky
      slug: bluesky
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - At-Protocol
      - Decentralized
      - Federated
      - Open Source
      tier: observed
      url: /providers/bluesky/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Ampache
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Ampache
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: observed
      url: /providers/mastodon/
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
      - Funkwhale
      - Koel
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - Koel
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        source: https://github.com/laravel/mcp
        status: verified
      name: Laravel Nightwatch
      slug: laravel
      sources:
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - Cloud Saas
      - Company
      - Developer Tools
      - PHP
      tier: observed
      url: /providers/laravel/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Spotify
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
      status: profiled
      tags: &id004
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Ampache
      - Koel
      band: developing
      in_catalog: true
      kin_score: 39.8
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      - https://github.com/koel/koel/blob/master/config/services.php
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ampache
      band: emerging
      in_catalog: true
      kin_score: 14.3
      mcp:
        status: none
      name: Libravatar
      slug: libravatar
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Avatars
      - Company
      - Federated
      - Open Source
      tier: observed
      url: /providers/libravatar/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Ampache
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Ampache
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Spotify
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id003
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Koel
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        status: none
      name: Algolia
      slug: algolia
      sources:
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - Discovery
      - Personalization
      - Recommendations
      - Search
      tier: observed
      url: /providers/algolia/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Koel
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://github.com/meilisearch/meilisearch-mcp
        status: verified
      name: Meilisearch
      slug: meilisearch
      sources:
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - AI Search
      - Full-Text Search
      - Hybrid Search
      - Open Source
      tier: observed
      url: /providers/meilisearch/
    - agent_band: agent-ready
      agent_readiness: 47.9
      apps:
      - Funkwhale
      band: developing
      in_catalog: true
      kin_score: 39.5
      mcp:
        source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
        status: verified
      name: Typesense
      slug: typesense
      sources:
      - https://dev.funkwhale.audio/funkwhale/funkwhale/-/blob/develop/api/pyproject.toml
      status: profiled
      tags:
      - Full-Text Search
      - Open Source
      - Search Engines
      - Typo Tolerance
      tier: observed
      url: /providers/typesense/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Koel
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: declared
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Koel
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean Spaces
      slug: digital-ocean
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: declared
      url: /providers/digital-ocean/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Koel
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: declared
      url: /providers/cloudflare-r2/
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - Ampache
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        source: https://dev.bitly.com/bitly-mcp/
        status: verified
      name: Bitly
      slug: bitly
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Analytics
      - Links
      - QR Codes
      - URL Shorteners
      tier: observed
      url: /providers/bitly/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Ampache
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: none
      name: YOURLS
      slug: yourls
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Company
      - Open Source
      - PHP
      - URL Shorteners
      tier: observed
      url: /providers/yourls/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Lidarr
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Lidarr
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Lidarr
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Lidarr
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Lidarr
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Lidarr
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        status: none
      name: Signal
      slug: signal
      sources:
      - https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
      status: profiled
      tags:
      - Cryptography
      - Encryption
      - Messaging
      - Security
      tier: observed
      url: /providers/signal/
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 12.2
      apps:
      - Spotify
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: none
      name: Comscore
      slug: comscore
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
      status: profiled
      tags:
      - Audience Analytics
      - Cloud Saas
      - Company
      - Media Measurement
      tier: observed
      url: /providers/comscore/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Ampache
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Koel
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.90
      key: AE-240.90
      name: Decentralized Storage & Compute
      url: /capabilities/decentralized-storage-compute/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - beets
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: IPFS
      slug: ipfs
      sources:
      - https://github.com/beetbox/beets/tree/master/beetsplug
      status: profiled
      tags:
      - Content-Addressed
      - Decentralized
      - Distributed Storage
      - IPFS
      tier: observed
      url: /providers/ipfs/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Koel
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/ipinfo/mcp
        status: verified
      name: IPinfo
      slug: ipinfo
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags:
      - ASN
      - IP Geolocation
      - IP Intelligence
      - Privacy Detection
      tier: declared
      url: /providers/ipinfo/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - beets
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://github.com/microsoft/azure-speech-mcp-server
        status: verified
      name: Azure AI Translator
      slug: microsoft-cognitive-services
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/lyrics.py
      status: profiled
      tags:
      - Azure AI
      - Computer Vision
      - Natural Language Processing
      - Speech
      tier: observed
      url: /providers/microsoft-cognitive-services/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Spotify
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.spotify.music/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Ampache
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/ampache/ampache/tree/develop/src/Plugin
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Koel
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://github.com/koel/koel/blob/master/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Koel
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/koel/koel/blob/master/.env.example
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.20
      key: AE-230.40.20
      name: Web Search APIs
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - beets
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        status: none
      name: Google Custom Search
      slug: google-custom-search
      sources:
      - https://github.com/beetbox/beets/blob/master/beetsplug/fetchart.py
      status: profiled
      tags:
      - Custom Search
      - Google
      - Image Search
      - Search
      tier: observed
      url: /providers/google-custom-search/
  layer: common
summary:
  coverage_pct: 96.3
  declared_only: 7
  distinct_providers: 82
  in_catalog: 79
  mcp:
    documented: 1
    none: 44
    unchecked: 3
    verified: 22
  mcp_verified: 22
  mean_kin_score: 35.9
  observed: 75
  queued: 3
  reference_apps: 7
title: 'Music & Audio Streaming: application blueprint'
---
