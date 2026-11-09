---
app: Monica
app_slug: monica
app_url: https://github.com/monicahq/monica
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Mapbox
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - LocationIQ
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-170.30.10
  key: AE-170.30.10
  layer: common
  name: Image Processing & Optimisation
  providers:
  - Uploadcare
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
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
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Meilisearch
  - Typesense
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - GitHub
  - Google sign-in
  - Kanidm
  - Keycloak
  - LinkedIn
  - Microsoft (Azure)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: calendar-contacts
  name: Calendar & Contacts
  url: /applications/calendar-contacts/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/monicahq/monica/blob/HEAD/composer.json
- route: source code
  url: https://github.com/monicahq/monica/blob/HEAD/.env.example
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
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
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id003
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id004
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id005
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id006
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id007
      status: none
    slug: kanidm
    status: profiled
    tags: &id008
    - Authentication
    - Company
    - Identity
    - Open Source
    url: /providers/kanidm/
  layer: common
  name: Kanidm
  provider: kanidm
  says: ships the Kanidm SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id009
      status: none
    slug: keycloak
    status: profiled
    tags: &id010
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: common
  name: Keycloak
  provider: keycloak
  says: ships the Keycloak SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    agent_readiness: 39.6
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id011
      source: https://github.com/laravel/mcp
      status: verified
    slug: laravel
    status: profiled
    tags: &id012
    - Cloud Saas
    - Company
    - Developer Tools
    - PHP
    url: /providers/laravel/
  layer: common
  name: Laravel Nightwatch
  provider: laravel
  says: ships the Laravel Nightwatch SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id013
      status: none
    slug: linkedin
    status: profiled
    tags: &id014
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: common
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    kin_score: 5.6
    mcp: &id015
      status: none
    slug: locationiq
    status: profiled
    tags: &id016
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/locationiq/
  layer: common
  name: LocationIQ
  provider: locationiq
  says: ships the LocationIQ SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/.env.example
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id017
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id018
    - Geospatial
    - Location
    - Mapping
    - Maps
    url: /providers/mapbox/
  layer: common
  name: Mapbox
  provider: mapbox
  says: ships the Mapbox SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/.env.example
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
    kin_score: 52.0
    mcp: &id019
      source: https://github.com/meilisearch/meilisearch-mcp
      status: verified
    slug: meilisearch
    status: profiled
    tags: &id020
    - AI Search
    - Full-Text Search
    - Hybrid Search
    - Open Source
    url: /providers/meilisearch/
  layer: common
  name: Meilisearch
  provider: meilisearch
  says: ships the Meilisearch SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/.env.example
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id021
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id022
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft (Azure)
  provider: microsoft-entra
  says: ships the Microsoft (Azure) SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
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
    kin_score: 80.6
    mcp: &id023
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id024
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id025
      status: none
    slug: telegram
    status: profiled
    tags: &id026
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/.env.example
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
    agent_band: agent-ready
    agent_readiness: 47.9
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id027
      source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
      status: verified
    slug: typesense
    status: profiled
    tags: &id028
    - Full-Text Search
    - Open Source
    - Search Engines
    - Typo Tolerance
    url: /providers/typesense/
  layer: common
  name: Typesense
  provider: typesense
  says: ships the Typesense SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id029
      status: none
    slug: uploadcare
    status: profiled
    tags: &id030
    - CDN
    - File Management
    - File Upload
    - Image Transformation
    url: /providers/uploadcare/
  layer: common
  name: Uploadcare
  provider: uploadcare
  says: ships the Uploadcare SDK or integration code
  source: https://github.com/monicahq/monica/blob/HEAD/.env.example
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/calendar-contacts/monica/
providers:
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id001
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id003
  name: GitHub
  slug: github
  status: profiled
  tags: *id004
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id005
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id006
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id007
  name: Kanidm
  slug: kanidm
  status: profiled
  tags: *id008
  url: /providers/kanidm/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id009
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id010
  url: /providers/keycloak/
- agent_band: agent-ready
  agent_readiness: 39.6
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id011
  name: Laravel Nightwatch
  slug: laravel
  status: profiled
  tags: *id012
  url: /providers/laravel/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id013
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id014
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id015
  name: LocationIQ
  slug: locationiq
  status: profiled
  tags: *id016
  url: /providers/locationiq/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id017
  name: Mapbox
  slug: mapbox
  status: profiled
  tags: *id018
  url: /providers/mapbox/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id019
  name: Meilisearch
  slug: meilisearch
  status: profiled
  tags: *id020
  url: /providers/meilisearch/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id021
  name: Microsoft (Azure)
  slug: microsoft-entra
  status: profiled
  tags: *id022
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id023
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id024
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id025
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id026
  url: /providers/telegram/
- agent_band: agent-ready
  agent_readiness: 47.9
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id027
  name: Typesense
  slug: typesense
  status: profiled
  tags: *id028
  url: /providers/typesense/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id029
  name: Uploadcare
  slug: uploadcare
  status: profiled
  tags: *id030
  url: /providers/uploadcare/
siblings:
- name: DAVx5
  rows: 14
  url: /applications/calendar-contacts/davx5/
- name: Etar
  rows: 0
  url: /applications/calendar-contacts/etar/
- name: Fantastical
  rows: 10
  url: /applications/calendar-contacts/fantastical/
- name: Morgen
  rows: 20
  url: /applications/calendar-contacts/morgen/
- name: Notion Calendar
  rows: 10
  url: /applications/calendar-contacts/notion-calendar/
- name: Radicale
  rows: 0
  url: /applications/calendar-contacts/radicale/
sitemap: true
title: 'Monica: Calendar & Contacts reference app'
---
