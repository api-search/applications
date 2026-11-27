---
app: Decidim
app_slug: decidim
app_url: https://github.com/decidim/decidim
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: domain
  name: Base Map Tiles
  providers:
  - HERE
  - OpenStreetMap
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - LibreTranslate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  - Twitter
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 4
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
- route: documentation
  url: https://docs.decidim.org/en/develop/services/machine_translations.html
- route: documentation
  url: https://docs.decidim.org/en/develop/services/maps.html
- route: documentation
  url: https://docs.decidim.org/en/develop/services/social_providers.html
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
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id003
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id004
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
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
    mcp: &id013
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id014
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: Twitter
  provider: x
  says: ships the Twitter SDK or integration code
  source: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
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
    agent_band: agent-native
    agent_readiness: 54.4
    band: exemplar
    in_catalog: true
    kin_score: 79.0
    mcp: &id005
      status: none
    slug: here
    status: profiled
    tags: &id006
    - Location
    - Mapping
    - Maps
    - Spatial
    url: /providers/here/
  layer: domain
  name: HERE
  provider: here
  says: lists HERE as an integration
  source: https://docs.decidim.org/en/develop/services/maps.html
  tier: declared
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
    agent_readiness: 23.3
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id007
      source: https://github.com/LibreTranslate/LibreTranslate-MCP
      status: verified
    slug: libre-translate
    status: profiled
    tags: &id008
    - Machine Translation
    - Natural Language Processing
    - Open Source
    - Translation
    url: /providers/libre-translate/
  layer: common
  name: LibreTranslate
  provider: libre-translate
  says: lists LibreTranslate as an integration
  source: https://docs.decidim.org/en/develop/services/machine_translations.html
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
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id009
      status: none
    slug: nominatim
    status: profiled
    tags: &id010
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: domain
  name: Nominatim
  provider: nominatim
  says: lists Nominatim as an integration
  source: https://docs.decidim.org/en/develop/services/maps.html
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
  source: https://docs.decidim.org/en/develop/services/maps.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/decidim/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id003
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id004
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 79.0
  mcp: *id005
  name: HERE
  slug: here
  status: profiled
  tags: *id006
  url: /providers/here/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id007
  name: LibreTranslate
  slug: libre-translate
  status: profiled
  tags: *id008
  url: /providers/libre-translate/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id009
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id010
  url: /providers/nominatim/
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
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id013
  name: Twitter
  slug: x
  status: profiled
  tags: *id014
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
- name: FixMyStreet
  rows: 8
  url: /applications/civic-government-services/fixmystreet/
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
title: 'Decidim: Civic & Government Services reference app'
---
