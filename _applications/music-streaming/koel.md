---
app: Koel
app_slug: koel
app_url: https://github.com/koel/koel
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - Ticketmaster
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Spotify
  - Last.fm
  - MusicBrainz
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
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
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - IPinfo
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Laravel Nightwatch
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Algolia
  - Meilisearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Cloudflare R2
  - DigitalOcean Spaces
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: music-streaming
  name: Music & Audio Streaming
  url: /applications/music-streaming/
counts:
  declared: 10
  observed: 8
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 61.9
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id001
      status: none
    slug: algolia
    status: profiled
    tags: &id002
    - Discovery
    - Personalization
    - Recommendations
    - Search
    url: /providers/algolia/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id009
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id013
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id014
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id017
      source: https://github.com/laravel/mcp
      status: verified
    slug: laravel
    status: profiled
    tags: &id018
    - Cloud Saas
    - Company
    - Developer Tools
    - PHP
    url: /providers/laravel/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id023
      source: https://github.com/meilisearch/meilisearch-mcp
      status: verified
    slug: meilisearch
    status: profiled
    tags: &id024
    - AI Search
    - Full-Text Search
    - Hybrid Search
    - Open Source
    url: /providers/meilisearch/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id027
      status: none
    slug: pusher
    status: profiled
    tags: &id028
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id029
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id030
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id031
      status: none
    slug: spotify
    status: profiled
    tags: &id032
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id005
      source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
      status: verified
    slug: cloudflare-r2
    status: profiled
    tags: &id006
    - Cloud Storage
    - Egress-Free
    - Object Storage
    - S3 Compatible
    url: /providers/cloudflare-r2/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id007
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id008
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 63.6
    mcp: &id015
      source: https://github.com/ipinfo/mcp
      status: verified
    slug: ipinfo
    status: profiled
    tags: &id016
    - ASN
    - IP Geolocation
    - IP Intelligence
    - Privacy Detection
    url: /providers/ipinfo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: strong
    in_catalog: true
    kin_score: 54.4
    mcp: &id019
      status: none
    slug: lastfm
    status: profiled
    tags: &id020
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id021
      status: none
    slug: listenbrainz
    status: profiled
    tags: &id022
    - Community
    - Data API
    - Music
    - Open Source
    url: /providers/listenbrainz/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id025
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id026
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.1
    band: developing
    in_catalog: true
    kin_score: 39.7
    mcp: &id033
      status: none
    slug: ticketmaster
    status: profiled
    tags: &id034
    - Commerce
    - Concerts
    - Entertainment
    - Event
    url: /providers/ticketmaster/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id035
      status: none
    slug: youtube
    status: profiled
    tags: &id036
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://github.com/koel/koel/blob/master/.env.example
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/music-streaming/koel/
providers:
- agent_band: agent-ready
  agent_readiness: 61.9
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id001
  name: Algolia
  slug: algolia
  status: profiled
  tags: *id002
  url: /providers/algolia/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id005
  name: Cloudflare R2
  slug: cloudflare-r2
  status: profiled
  tags: *id006
  url: /providers/cloudflare-r2/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id007
  name: DigitalOcean Spaces
  slug: digital-ocean
  status: profiled
  tags: *id008
  url: /providers/digital-ocean/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id009
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id010
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id013
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id014
  url: /providers/gravatar/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 63.6
  mcp: *id015
  name: IPinfo
  slug: ipinfo
  status: profiled
  tags: *id016
  url: /providers/ipinfo/
- agent_band: agent-ready
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id017
  name: Laravel Nightwatch
  slug: laravel
  status: profiled
  tags: *id018
  url: /providers/laravel/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id019
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id020
  url: /providers/lastfm/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id021
  name: ListenBrainz
  slug: listenbrainz
  status: profiled
  tags: *id022
  url: /providers/listenbrainz/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id023
  name: Meilisearch
  slug: meilisearch
  status: profiled
  tags: *id024
  url: /providers/meilisearch/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id025
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id026
  url: /providers/musicbrainz/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id027
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id028
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id029
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id030
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id031
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id032
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id033
  name: Ticketmaster
  slug: ticketmaster
  status: profiled
  tags: *id034
  url: /providers/ticketmaster/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id035
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id036
  url: /providers/youtube/
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
title: 'Koel: Music & Audio Streaming reference app'
---
