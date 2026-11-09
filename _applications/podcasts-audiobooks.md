---
access: understanding
agent_layer: []
apps:
- anchor: audiobookshelf
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/advplyr/audiobookshelf/blob/master/package.json
  - route: source code
    url: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.40
      key: AE-170.20.40
      name: Podcast Directories & Search
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Apple (iTunes Search API)
    provider: apple
    says: ships the Apple (iTunes Search API) SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.30
      key: AE-170.20.30
      name: Audiobooks
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Audible
    provider: audible
    says: ships the Audible SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.30
      key: AE-170.20.30
      name: Audiobooks
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: AudiobookCovers
    provider: audiobookcovers
    says: ships the AudiobookCovers SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.30
      key: AE-170.20.30
      name: Audiobooks
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Audnexus
    provider: audnexus
    says: ships the Audnexus SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: FantLab
    provider: fantlab
    says: ships the FantLab SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Google Books
    provider: google-books
    says: ships the Google Books SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
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
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Open Library
    provider: open-library
    says: ships the Open Library SDK or integration code
    source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
    tier: observed
  kind: self-hosted
  name: Audiobookshelf
  page: /applications/podcasts-audiobooks/audiobookshelf/
  slug: audiobookshelf
  url: https://github.com/advplyr/audiobookshelf
- anchor: antennapod
  counts:
    declared: 0
    observed: 6
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
    layer: domain
    name: PodcastIndex
    provider: podcastindex
    says: ships the PodcastIndex SDK or integration code
    source: https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
    tier: observed
  kind: self-hosted
  name: AntennaPod
  page: /applications/podcasts-audiobooks/antennapod/
  slug: antennapod
  url: https://github.com/AntennaPod/AntennaPod
- anchor: pocket-casts
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/au.com.shiftyjelly.pocketcasts/latest/
  - route: dependency manifest
    url: https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3740.20
      key: ott-streaming-delivery
      name: OTT & Streaming Delivery
      url: /capabilities/ott-streaming-delivery/
      via_parent: null
    credit: null
    layer: common
    name: Google Cast
    provider: google
    says: ships the Google Cast SDK or integration code
    source: https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
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
    source: https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Sign in with Google
    provider: google-identity-platform
    says: ships the Sign in with Google SDK or integration code
    source: https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
    tier: observed
  kind: open-source-saas
  name: Pocket Casts
  page: /applications/podcasts-audiobooks/pocket-casts/
  slug: pocket-casts
  url: https://github.com/Automattic/pocket-casts-android
- anchor: castopod
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/ad-aures/castopod/blob/develop/composer.json
  - route: source code
    url: https://github.com/ad-aures/castopod/blob/develop/.env.example
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
    name: MaxMind GeoIP2
    provider: maxmind
    says: ships the MaxMind GeoIP2 SDK or integration code
    source: https://github.com/ad-aures/castopod/blob/develop/composer.json
    tier: observed
  kind: self-hosted
  name: Castopod
  page: /applications/podcasts-audiobooks/castopod/
  slug: castopod
  url: https://github.com/ad-aures/castopod
- anchor: podverse
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/podverse/podverse-api/blob/develop/package.json
  - route: source code
    url: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: AWS
    provider: amazon-web-services
    says: ships the AWS SDK or integration code
    source: https://github.com/podverse/podverse-api/blob/develop/package.json
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
    name: BitPay
    provider: bitpay
    says: ships the BitPay SDK or integration code
    source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
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
    name: Manticore Search
    provider: manticore
    says: ships the Manticore Search SDK or integration code
    source: https://github.com/podverse/podverse-api/blob/develop/package.json
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
    source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
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
    source: https://github.com/podverse/podverse-api/blob/develop/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.40
      key: AE-170.20.40
      name: Podcast Directories & Search
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: PodcastIndex
    provider: podcastindex
    says: ships the PodcastIndex SDK or integration code
    source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
    tier: observed
  kind: open-source-saas
  name: Podverse
  page: /applications/podcasts-audiobooks/podverse/
  slug: podverse
  url: https://github.com/podverse/podverse-api
- anchor: audible
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
    tier: observed
  kind: commercial
  name: Audible
  page: /applications/podcasts-audiobooks/audible/
  slug: audible
  url: https://www.audible.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: podcasts-audiobooks
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Books
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Music
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Music & Audio
  store: google-play
  url: https://play.google.com/store/apps/category/MUSIC_AND_AUDIO
- category: Books & Reference
  store: google-play
  url: https://play.google.com/store/apps/category/BOOKS_AND_REFERENCE
- category: Media Streaming - Audio Streaming
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#media-streaming---audio-streaming
name: Podcasts & Audiobooks
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.30
    key: AE-170.20.30
    name: Audiobooks
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: audiobook metadata, chapters and covers (Audible, Audnexus, AudiobookCovers)
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: book metadata for audiobook libraries
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: MusicBrainz music/audio metadata
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.40
    key: AE-170.20.40
    name: Podcast Directories & Search
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: podcast directory search (iTunes, PodcastIndex, fyyd); no podcast-directory node exists
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: gpodder-protocol subscription and episode sync
- capability:
    attribution: Turbo EA
    id: BC-3740.20
    key: ott-streaming-delivery
    name: OTT & Streaming Delivery
    url: /capabilities/ott-streaming-delivery/
    via_parent: null
  fit: nearest
  layer: common
  why: casting audio to Cast devices
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app analytics
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash reporting
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: store subscriptions
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Sign in with Google
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: podcast media storage
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: listener geography in podcast analytics
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: memberships
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: new-episode notifications
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: catalog full-text search
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.40
      key: AE-170.20.40
      name: Podcast Directories & Search
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - AntennaPod
      - Audiobookshelf
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple (iTunes Search API)
      slug: apple
      sources:
      - https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - AntennaPod
      - Podverse
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        status: none
      name: PodcastIndex
      slug: podcastindex
      sources:
      - https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
      - https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
      status: profiled
      tags:
      - Discovery
      - Open Data
      - Podcast Index
      - Podcasts
      tier: observed
      url: /providers/podcastindex/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - AntennaPod
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: fyyd
      slug: fyyd
      sources:
      - https://github.com/AntennaPod/AntennaPod/tree/develop/net/discovery/src/main/java/de/danoeh/antennapod/net/discovery
      status: profiled
      tags:
      - Audio
      - Directory
      - Podcasts
      - Search
      tier: observed
      url: /providers/fyyd/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.30
      key: AE-170.20.30
      name: Audiobooks
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - Audiobookshelf
      band: emerging
      in_catalog: true
      kin_score: 15.9
      mcp:
        status: none
      name: Audnexus
      slug: audnexus
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Audiobooks
      - Company
      - Metadata
      - Search
      tier: observed
      url: /providers/audnexus/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Audiobookshelf
      band: minimal
      in_catalog: true
      kin_score: 10.3
      mcp:
        status: unknown
      name: Audible
      slug: audible
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Audiobooks
      - Company
      - Consumer
      - Podcasts
      tier: observed
      url: /providers/audible/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Audiobookshelf
      band: minimal
      in_catalog: true
      kin_score: 7.4
      mcp:
        status: none
      name: AudiobookCovers
      slug: audiobookcovers
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Audiobooks
      - Community
      - Company
      - CoverArt
      tier: observed
      url: /providers/audiobookcovers/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Audiobookshelf
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        status: none
      name: Google Books
      slug: google-books
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Books
      - Ebooks
      - Google
      - Library
      tier: observed
      url: /providers/google-books/
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Audiobookshelf
      band: emerging
      in_catalog: true
      kin_score: 23.9
      mcp:
        status: unknown
      name: Open Library
      slug: open-library
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Authors
      - Books
      - Catalog
      - Covers
      tier: observed
      url: /providers/open-library/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Audiobookshelf
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: none
      name: FantLab
      slug: fantlab
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Community
      - Company
      - Literature
      - Science Fiction
      tier: observed
      url: /providers/fantlab/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - AntennaPod
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Nextcloud (gpodder sync app)
      slug: nextcloud
      sources:
      - https://github.com/AntennaPod/AntennaPod/blob/develop/net/sync/service-interface/src/main/java/de/danoeh/antennapod/net/sync/serviceinterface/SynchronizationProvider.java
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - AntennaPod
      band: emerging
      in_catalog: true
      kin_score: 16.5
      mcp:
        status: none
      name: gpodder.net
      slug: gpodder
      sources:
      - https://github.com/AntennaPod/AntennaPod/blob/develop/net/sync/service-interface/src/main/java/de/danoeh/antennapod/net/sync/serviceinterface/SynchronizationProvider.java
      status: profiled
      tags:
      - Community
      - Open Source
      - Podcasts
      - Sync
      tier: observed
      url: /providers/gpodder/
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
      - Audiobookshelf
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        status: none
      name: MusicBrainz
      slug: musicbrainz
      sources:
      - https://github.com/advplyr/audiobookshelf/tree/master/server/providers
      status: profiled
      tags:
      - Encyclopedia
      - Metadata
      - Music
      - Open Data
      tier: observed
      url: /providers/musicbrainz/
  layer: domain
- capabilities:
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
      - Pocket Casts
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - Audible
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Audible
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
      status: profiled
      tags: &id002
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
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
      - Audible
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
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
      - Podverse
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
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
      - Pocket Casts
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase
      slug: firebase
      sources:
      - https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-3740.20
      key: ott-streaming-delivery
      name: OTT & Streaming Delivery
      url: /capabilities/ott-streaming-delivery/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - AntennaPod
      - Pocket Casts
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Cast
      slug: google
      sources:
      - https://github.com/AntennaPod/AntennaPod/blob/develop/gradle/libs.versions.toml
      - https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
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
      - Podverse
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/podverse/podverse-api/blob/develop/package.json
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Podverse
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: BitPay
      slug: bitpay
      sources:
      - https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
      status: profiled
      tags:
      - Bitcoin
      - Blockchain
      - Cryptocurrency
      - Payments
      tier: observed
      url: /providers/bitpay/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Castopod
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: MaxMind GeoIP2
      slug: maxmind
      sources:
      - https://github.com/ad-aures/castopod/blob/develop/composer.json
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Pocket Casts
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Podverse
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
      status: profiled
      tags: *id002
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
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Podverse
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        source: https://github.com/manticoresoftware/mcp-manticore
        status: verified
      name: Manticore Search
      slug: manticore
      sources:
      - https://github.com/podverse/podverse-api/blob/develop/package.json
      status: profiled
      tags:
      - Elasticsearch Compatible
      - Full-Text Search
      - Search
      - Vector Search
      tier: observed
      url: /providers/manticore/
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
      - Pocket Casts
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Sign in with Google
      slug: google-identity-platform
      sources:
      - https://github.com/Automattic/pocket-casts-android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Podverse
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://github.com/podverse/podverse-api/blob/develop/package.json
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Audible
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.audible.application/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 0
  distinct_providers: 26
  in_catalog: 26
  mcp:
    documented: 0
    none: 14
    unchecked: 0
    verified: 9
  mcp_verified: 9
  mean_kin_score: 40.0
  observed: 26
  queued: 0
  reference_apps: 6
title: 'Podcasts & Audiobooks: application blueprint'
---
