---
app: Flathunter
app_slug: flathunter
app_url: https://github.com/flathunters/flathunter
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4960.30
  key: listing-data-mls-management
  layer: domain
  name: Listing Data & MLS Management
  providers:
  - idealista
  - Immobiliare.it
  - ImmobilienScout24
  - Immowelt
  - Kleinanzeigen
  - Subito.it
  - VRM Immo
  - WG-Gesucht
  url: /capabilities/listing-data-mls-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Google Cloud Firestore
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-120.30
  key: AE-120.30
  layer: common
  name: Routing & Navigation
  providers:
  - Google Maps Distance Matrix API
  url: /capabilities/routing-navigation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Mattermost
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-230.40.10
  key: AE-230.40.10
  layer: common
  name: Web Scraping
  providers:
  - 2captcha
  - Capmonster
  - ImageTyperz
  url: /capabilities/web-data/
  via_parent: Web Data
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram Bot API
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: real-estate-home-search
  name: Real Estate & Home Search
  url: /applications/real-estate-home-search/
counts:
  declared: 1
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/flathunters/flathunter/main/Pipfile
- route: source code
  url: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
- route: source code
  url: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
- route: source code
  url: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
- route: source code
  url: https://raw.githubusercontent.com/flathunters/flathunter/main/config.yaml.dist
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.9
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id001
      source: https://github.com/2captcha/2captcha-mcp
      status: verified
    slug: 2captcha
    status: profiled
    tags: &id002
    - Automation
    - CAPTCHA Solving
    - Data Extraction
    - Web Scraping
    url: /providers/2captcha/
  layer: common
  name: 2captcha
  provider: 2captcha
  says: ships the 2captcha SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.0
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id003
      source: https://github.com/CapMonsterCloud/capmonster-mcp-captcha-solver
      status: verified
    slug: capmonster
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Automation
    - CAPTCHA
    - Company
    url: /providers/capmonster/
  layer: common
  name: Capmonster
  provider: capmonster
  says: ships the Capmonster SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 54.4
    mcp: &id005
      source: https://firebase.google.com/docs/cli/mcp-server
      status: verified
    slug: google-cloud-firestore
    status: profiled
    tags: &id006
    - Database
    - Documents
    - Google Cloud
    - NoSQL
    url: /providers/google-cloud-firestore/
  layer: common
  name: Google Cloud Firestore
  provider: google-cloud-firestore
  says: ships the Google Cloud Firestore SDK or integration code
  source: https://raw.githubusercontent.com/flathunters/flathunter/main/Pipfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: idealista
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: idealista
  provider: idealista
  says: ships the idealista SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id011
      status: unknown
    slug: imagetyperz
    status: profiled
    tags: &id012
    - Automation
    - CAPTCHA
    - Company
    - Services
    url: /providers/imagetyperz/
  layer: common
  name: ImageTyperz
  provider: imagetyperz
  says: ships the ImageTyperz SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.9
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id013
      status: none
    slug: immobiliare
    status: profiled
    tags: &id014
    - Company
    - Italy
    - Property Listings
    - Real Estate
    url: /providers/immobiliare/
  layer: domain
  name: Immobiliare.it
  provider: immobiliare
  says: ships the Immobiliare.it SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id015
      status: none
    slug: immobilienscout24
    status: profiled
    tags: &id016
    - Company
    - Germany
    - Marketplace
    - Real Estate
    url: /providers/immobilienscout24/
  layer: domain
  name: ImmobilienScout24
  provider: immobilienscout24
  says: ships the ImmobilienScout24 SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.9
    band: emerging
    in_catalog: true
    kin_score: 23.1
    mcp: &id017
      status: unknown
    slug: immowelt
    status: profiled
    tags: &id018
    - Austria
    - Germany
    - Marketplace
    - Real Estate
    url: /providers/immowelt/
  layer: domain
  name: Immowelt
  provider: immowelt
  says: ships the Immowelt SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id019
      status: none
    slug: kleinanzeigen
    status: profiled
    tags: &id020
    - Classifieds
    - Germany
    - Marketplace
    - free-ads
    url: /providers/kleinanzeigen/
  layer: domain
  name: Kleinanzeigen
  provider: kleinanzeigen
  says: ships the Kleinanzeigen SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id021
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id022
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: common
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id023
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id024
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id025
      status: unknown
    slug: subito
    status: profiled
    tags: &id026
    - Classifieds
    - E-Commerce
    - Italy
    - Marketplace
    url: /providers/subito/
  layer: domain
  name: Subito.it
  provider: subito
  says: ships the Subito.it SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
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
    mcp: &id027
      status: none
    slug: telegram
    status: profiled
    tags: &id028
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram Bot API
  provider: telegram
  says: ships the Telegram Bot API SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.3
    mcp: &id029
      status: unknown
    slug: vrm-immo
    status: profiled
    tags: &id030
    - Company
    - Germany
    - Marketplace
    - Real Estate
    url: /providers/vrm-immo/
  layer: domain
  name: VRM Immo
  provider: vrm-immo
  says: ships the VRM Immo SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id031
      status: unknown
    slug: wg-gesucht
    status: profiled
    tags: &id032
    - Germany
    - Housing
    - Marketplace
    - Rentals
    url: /providers/wg-gesucht/
  layer: domain
  name: WG-Gesucht
  provider: wg-gesucht
  says: ships the WG-Gesucht SDK or integration code
  source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.30
    key: AE-120.30
    name: Routing & Navigation
    url: /capabilities/routing-navigation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
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
  layer: common
  name: Google Maps Distance Matrix API
  provider: google-maps
  says: lists Google Maps Distance Matrix API as an integration
  source: https://raw.githubusercontent.com/flathunters/flathunter/main/config.yaml.dist
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/real-estate-home-search/flathunter/
providers:
- agent_band: agent-aware
  agent_readiness: 12.9
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id001
  name: 2captcha
  slug: 2captcha
  status: profiled
  tags: *id002
  url: /providers/2captcha/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id003
  name: Capmonster
  slug: capmonster
  status: profiled
  tags: *id004
  url: /providers/capmonster/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id005
  name: Google Cloud Firestore
  slug: google-cloud-firestore
  status: profiled
  tags: *id006
  url: /providers/google-cloud-firestore/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id007
  name: Google Maps Distance Matrix API
  slug: google-maps
  status: profiled
  tags: *id008
  url: /providers/google-maps/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: idealista
  slug: idealista
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id011
  name: ImageTyperz
  slug: imagetyperz
  status: profiled
  tags: *id012
  url: /providers/imagetyperz/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id013
  name: Immobiliare.it
  slug: immobiliare
  status: profiled
  tags: *id014
  url: /providers/immobiliare/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id015
  name: ImmobilienScout24
  slug: immobilienscout24
  status: profiled
  tags: *id016
  url: /providers/immobilienscout24/
- agent_band: agent-aware
  agent_readiness: 18.9
  band: emerging
  in_catalog: true
  kin_score: 23.1
  mcp: *id017
  name: Immowelt
  slug: immowelt
  status: profiled
  tags: *id018
  url: /providers/immowelt/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id019
  name: Kleinanzeigen
  slug: kleinanzeigen
  status: profiled
  tags: *id020
  url: /providers/kleinanzeigen/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id021
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id022
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id023
  name: Slack
  slug: slack
  status: profiled
  tags: *id024
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id025
  name: Subito.it
  slug: subito
  status: profiled
  tags: *id026
  url: /providers/subito/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id027
  name: Telegram Bot API
  slug: telegram
  status: profiled
  tags: *id028
  url: /providers/telegram/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.3
  mcp: *id029
  name: VRM Immo
  slug: vrm-immo
  status: profiled
  tags: *id030
  url: /providers/vrm-immo/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id031
  name: WG-Gesucht
  slug: wg-gesucht
  status: profiled
  tags: *id032
  url: /providers/wg-gesucht/
siblings:
- name: HomeHarvest
  rows: 1
  url: /applications/real-estate-home-search/homeharvest/
- name: Real Geeks
  rows: 10
  url: /applications/real-estate-home-search/real-geeks/
- name: Realtor.com
  rows: 13
  url: /applications/real-estate-home-search/realtor-com/
- name: Redfin
  rows: 13
  url: /applications/real-estate-home-search/redfin/
- name: Rightmove
  rows: 6
  url: /applications/real-estate-home-search/rightmove/
- name: Zillow
  rows: 14
  url: /applications/real-estate-home-search/zillow/
sitemap: true
title: 'Flathunter: Real Estate & Home Search reference app'
---
