---
app: FixMyStreet
app_slug: fixmystreet
app_url: https://github.com/mysociety/fixmystreet
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: domain
  name: Base Map Tiles
  providers:
  - Bing Maps
  - Google Maps
  - OpenStreetMap
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - MapIt (mySociety)
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Twitter
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 5
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
- route: documentation
  url: https://fixmystreet.org/customising/config/
integrations:
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
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id013
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id014
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
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
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id015
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id016
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: Twitter
  provider: x
  says: ships the Twitter SDK or integration code
  source: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
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
  says: lists Amazon S3 as an integration
  source: https://fixmystreet.org/customising/config/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.5
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id003
      status: none
    slug: bing-maps
    status: profiled
    tags: &id004
    - Geocoding
    - Geospatial
    - Maps
    - Routing
    url: /providers/bing-maps/
  layer: domain
  name: Bing Maps
  provider: bing-maps
  says: lists Bing Maps as an integration
  source: https://fixmystreet.org/customising/config/
  tier: declared
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
    mcp: &id007
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id008
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: domain
  name: Google Maps
  provider: google-maps
  says: lists Google Maps as an integration
  source: https://fixmystreet.org/customising/config/
  tier: declared
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
    kin_score: 2.5
    mcp: &id009
      status: unchecked
    slug: mapit
    status: profiled
    tags: &id010
    - Company
    - Location
    - Mapping
    - United Kingdom
    url: /providers/mapit/
  layer: domain
  name: MapIt (mySociety)
  provider: mapit
  says: lists MapIt (mySociety) as an integration
  source: https://fixmystreet.org/customising/config/
  tier: declared
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
    mcp: &id011
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id012
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: domain
  name: OpenStreetMap
  provider: openstreetmap
  says: lists OpenStreetMap as an integration
  source: https://fixmystreet.org/customising/config/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/fixmystreet/
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
- agent_band: human-only
  agent_readiness: 3.5
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id003
  name: Bing Maps
  slug: bing-maps
  status: profiled
  tags: *id004
  url: /providers/bing-maps/
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
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id007
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id008
  url: /providers/google-maps/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id009
  name: MapIt (mySociety)
  slug: mapit
  status: profiled
  tags: *id010
  url: /providers/mapit/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id011
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id012
  url: /providers/openstreetmap/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id013
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id014
  url: /providers/twilio/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id015
  name: Twitter
  slug: x
  status: profiled
  tags: *id016
  url: /providers/x/
siblings:
- name: Accela Civic Platform
  rows: 4
  url: /applications/civic-government-services/accela-civic-platform/
- name: Alaveteli
  rows: 4
  url: /applications/civic-government-services/alaveteli/
- name: CONSUL Democracy
  rows: 5
  url: /applications/civic-government-services/consul-democracy/
- name: Decidim
  rows: 7
  url: /applications/civic-government-services/decidim/
- name: Go Vocal (CitizenLab)
  rows: 10
  url: /applications/civic-government-services/go-vocal-citizenlab/
- name: Granicus (govDelivery)
  rows: 1
  url: /applications/civic-government-services/granicus-govdelivery/
- name: SeeClickFix (CivicPlus)
  rows: 21
  url: /applications/civic-government-services/seeclickfix-civicplus/
sitemap: true
title: 'FixMyStreet: Civic & Government Services reference app'
---
