---
app: Friendica
app_slug: friendica
app_url: https://github.com/friendica/friendica
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Dreamwidth
  - InsaneJournal
  - LiveJournal
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50.10
  key: AE-170.50.10
  layer: domain
  name: Online Communities
  providers:
  - Discourse
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Bluesky
  - Nitter
  - pnut.io
  - Tumblr
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Invidious
  url: /capabilities/video-platforms/
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
  - OpenStreetMap
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Matomo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: common
  name: Reverse Geocoding
  providers:
  - GeoNames
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: common
  name: Weather & Environment
  providers:
  - OpenWeatherMap
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: social-network
  name: Social Networking & Microblogging
  url: /applications/social-network/
counts:
  declared: 0
  observed: 20
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/friendica/friendica/blob/develop/composer.json
- route: source code
  url: https://github.com/friendica/friendica-addons
integrations:
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
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/s3_storage
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
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id003
      status: none
    slug: bluesky
    status: profiled
    tags: &id004
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: domain
  name: Bluesky
  provider: bluesky
  says: ships the Bluesky SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/bluesky
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id005
      source: https://github.com/discourse/discourse-mcp
      status: verified
    slug: discourse
    status: profiled
    tags: &id006
    - Community
    - Forums
    - Open Source
    url: /providers/discourse/
  layer: domain
  name: Discourse
  provider: discourse
  says: ships the Discourse SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/discourse
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.4
    mcp: &id007
      status: none
    slug: dreamwidth
    status: profiled
    tags: &id008
    - Community
    - Company
    - Creative
    - Open Source
    url: /providers/dreamwidth/
  layer: domain
  name: Dreamwidth
  provider: dreamwidth
  says: ships the Dreamwidth SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/dwpost
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id009
      status: none
    slug: geonames
    status: profiled
    tags: &id010
    - Geocoding
    - Public APIs
    url: /providers/geonames/
  layer: common
  name: GeoNames
  provider: geonames
  says: ships the GeoNames SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/geonames
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
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id011
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id012
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/googlemaps
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
  source: https://github.com/friendica/friendica-addons/tree/develop/gravatar
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.4
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id015
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id016
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: ships the IFTTT SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/ifttt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id017
      status: unknown
    slug: insanejournal
    status: profiled
    tags: &id018
    - Blogging
    - Company
    - Journaling
    - Social Network
    url: /providers/insanejournal/
  layer: domain
  name: InsaneJournal
  provider: insanejournal
  says: ships the InsaneJournal SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/ijpost
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id019
      status: none
    slug: invidious
    status: profiled
    tags: &id020
    - Frontend
    - Open Source
    - Privacy
    - Video
    url: /providers/invidious/
  layer: domain
  name: Invidious
  provider: invidious
  says: ships the Invidious SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/invidious
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
    kin_score: 21.5
    mcp: &id021
      status: none
    slug: libravatar
    status: profiled
    tags: &id022
    - Avatars
    - Company
    - Federated
    - Open Source
    url: /providers/libravatar/
  layer: common
  name: Libravatar
  provider: libravatar
  says: ships the Libravatar SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/libravatar
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id023
      status: unknown
    slug: livejournal
    status: profiled
    tags: &id024
    - Blogging
    - Community
    - Company
    - Social
    url: /providers/livejournal/
  layer: domain
  name: LiveJournal
  provider: livejournal
  says: ships the LiveJournal SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/ljpost
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
    agent_readiness: 41.3
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id025
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id026
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/piwik
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.6
    mcp: &id027
      status: none
    slug: nitter
    status: profiled
    tags: &id028
    - Company
    - Open Source
    - Privacy
    - TwitterAlternative
    url: /providers/nitter/
  layer: domain
  name: Nitter
  provider: nitter
  says: ships the Nitter SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/nitter
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
    agent_band: agent-aware
    agent_readiness: 28.3
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id029
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id030
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: common
  name: OpenStreetMap
  provider: openstreetmap
  says: ships the OpenStreetMap SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/openstreetmap
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id031
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id032
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: common
  name: OpenWeatherMap
  provider: openweathermap
  says: ships the OpenWeatherMap SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/curweather
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
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id033
      status: unknown
    slug: pnut
    status: profiled
    tags: &id034
    - API-First
    - Community
    - Company
    - Social
    url: /providers/pnut/
  layer: domain
  name: pnut.io
  provider: pnut
  says: ships the pnut.io SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/pnut
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id035
      status: none
    slug: tumblr
    status: profiled
    tags: &id036
    - Public APIs
    - Social
    url: /providers/tumblr/
  layer: domain
  name: Tumblr
  provider: tumblr
  says: ships the Tumblr SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/tumblr
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id037
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id038
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: ships the WordPress SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/wppost
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
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id039
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id040
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/friendica/friendica-addons/tree/develop/twitter
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-network/friendica/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id003
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id004
  url: /providers/bluesky/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id005
  name: Discourse
  slug: discourse
  status: profiled
  tags: *id006
  url: /providers/discourse/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id007
  name: Dreamwidth
  slug: dreamwidth
  status: profiled
  tags: *id008
  url: /providers/dreamwidth/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id009
  name: GeoNames
  slug: geonames
  status: profiled
  tags: *id010
  url: /providers/geonames/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id011
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id012
  url: /providers/google-maps/
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
  agent_readiness: 42.4
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id015
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id016
  url: /providers/ifttt/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id017
  name: InsaneJournal
  slug: insanejournal
  status: profiled
  tags: *id018
  url: /providers/insanejournal/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id019
  name: Invidious
  slug: invidious
  status: profiled
  tags: *id020
  url: /providers/invidious/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.5
  mcp: *id021
  name: Libravatar
  slug: libravatar
  status: profiled
  tags: *id022
  url: /providers/libravatar/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id023
  name: LiveJournal
  slug: livejournal
  status: profiled
  tags: *id024
  url: /providers/livejournal/
- agent_band: agent-ready
  agent_readiness: 41.3
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id025
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id026
  url: /providers/matomo/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id027
  name: Nitter
  slug: nitter
  status: profiled
  tags: *id028
  url: /providers/nitter/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id029
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id030
  url: /providers/openstreetmap/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id031
  name: OpenWeatherMap
  slug: openweathermap
  status: profiled
  tags: *id032
  url: /providers/openweathermap/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id033
  name: pnut.io
  slug: pnut
  status: profiled
  tags: *id034
  url: /providers/pnut/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id035
  name: Tumblr
  slug: tumblr
  status: profiled
  tags: *id036
  url: /providers/tumblr/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id037
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id038
  url: /providers/wordpress/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id039
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id040
  url: /providers/x/
siblings:
- name: Bluesky
  rows: 4
  url: /applications/social-network/bluesky/
- name: Instagram
  rows: 2
  url: /applications/social-network/instagram/
- name: Mastodon
  rows: 9
  url: /applications/social-network/mastodon/
- name: Misskey
  rows: 11
  url: /applications/social-network/misskey/
- name: Pixelfed
  rows: 11
  url: /applications/social-network/pixelfed/
- name: Threads
  rows: 2
  url: /applications/social-network/threads/
sitemap: true
title: 'Friendica: Social Networking & Microblogging reference app'
---
