---
app: Phraseanet
app_slug: phraseanet
app_url: https://github.com/alchemy-fr/Phraseanet
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: domain
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - GeoNames
  url: /capabilities/geocoding/
  via_parent: Geocoding
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
  id: AE-150.70
  key: AE-150.70
  layer: domain
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Facebook
  - GitHub
  - LinkedIn
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Dailymotion
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
category:
  id: digital-asset-management
  name: Digital Asset Management
  url: /applications/digital-asset-management/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
- route: source code
  url: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
- route: source code
  url: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: minimal
    in_catalog: true
    kin_score: 8.2
    mcp: &id001
      status: none
    slug: dailymotion
    status: profiled
    tags: &id002
    - Public APIs
    - Video
    url: /providers/dailymotion/
  layer: domain
  name: Dailymotion
  provider: dailymotion
  says: ships the Dailymotion SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
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
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id003
      source: https://github.com/elastic/mcp-server-elasticsearch
      status: verified
    slug: elasticsearch
    status: profiled
    tags: &id004
    - Analytics
    - Database
    - Full-Text Search
    - NoSQL
    url: /providers/elasticsearch/
  layer: domain
  name: Elasticsearch
  provider: elasticsearch
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
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
    agent_readiness: 25.1
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id007
      status: none
    slug: flickr
    status: profiled
    tags: &id008
    - Photography
    - Photos
    - Public APIs
    - Social Media
    url: /providers/flickr/
  layer: domain
  name: Flickr
  provider: flickr
  says: ships the Flickr SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
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
  layer: domain
  name: GeoNames
  provider: geonames
  says: ships the GeoNames SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
  tier: observed
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id013
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id014
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: domain
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
  tier: observed
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id015
      status: none
    slug: linkedin
    status: profiled
    tags: &id016
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
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
    mcp: &id017
      status: none
    slug: pusher
    status: profiled
    tags: &id018
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: domain
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
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
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id019
      status: none
    slug: youtube
    status: profiled
    tags: &id020
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/digital-asset-management/phraseanet/
providers:
- agent_band: human-only
  agent_readiness: 3.8
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id001
  name: Dailymotion
  slug: dailymotion
  status: profiled
  tags: *id002
  url: /providers/dailymotion/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id003
  name: Elasticsearch
  slug: elasticsearch
  status: profiled
  tags: *id004
  url: /providers/elasticsearch/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id007
  name: Flickr
  slug: flickr
  status: profiled
  tags: *id008
  url: /providers/flickr/
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
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id011
  name: GitHub
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id013
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id014
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id015
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id016
  url: /providers/linkedin/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id017
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id018
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id019
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id020
  url: /providers/youtube/
siblings:
- name: Bynder
  rows: 71
  url: /applications/digital-asset-management/bynder/
- name: Canto
  rows: 33
  url: /applications/digital-asset-management/canto/
- name: Cloudinary
  rows: 56
  url: /applications/digital-asset-management/cloudinary/
- name: Frontify
  rows: 55
  url: /applications/digital-asset-management/frontify/
- name: ResourceSpace
  rows: 15
  url: /applications/digital-asset-management/resourcespace/
sitemap: true
title: 'Phraseanet: Digital Asset Management reference app'
---
