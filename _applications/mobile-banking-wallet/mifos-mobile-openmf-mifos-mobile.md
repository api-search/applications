---
app: Mifos Mobile (openMF mifos-mobile)
app_slug: mifos-mobile-openmf-mifos-mobile
app_url: https://github.com/openMF/mifos-mobile
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-936
  key: AE-936
  layer: domain
  name: Core Banking Platforms
  providers:
  - Apache Fineract (Mifos platform)
  url: /capabilities/core-banking-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics + Performance
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.70
  key: software-marketplace-listing-management
  layer: common
  name: Software Marketplace Listing Management
  providers:
  - Google Play (Integrity, In-App Review, In-App Update)
  url: /capabilities/software-marketplace-listing-management/
  via_parent: null
category:
  id: mobile-banking-wallet
  name: Mobile Banking & Payments Wallet
  url: /applications/mobile-banking-wallet/
counts:
  declared: 1
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
- route: documentation
  url: https://github.com/openMF/mifos-mobile
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id005
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Crashlytics + Performance
  provider: firebase
  says: ships the Firebase Crashlytics + Performance SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
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
    mcp: &id006
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id007
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id008
      status: none
    slug: google-play
    status: profiled
    tags: &id009
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play (Integrity, In-App Review, In-App Update)
  provider: google-play
  says: ships the Google Play (Integrity, In-App Review, In-App Update) SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-936
    key: AE-936
    name: Core Banking Platforms
    url: /capabilities/core-banking-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id002
      status: none
    slug: apache-fineract
    status: profiled
    tags: &id003
    - Banking
    - Company
    - Fintech
    - Open Source
    url: /providers/apache-fineract/
  layer: domain
  name: Apache Fineract (Mifos platform)
  provider: apache-fineract
  says: lists Apache Fineract (Mifos platform) as an integration
  source: https://github.com/openMF/mifos-mobile
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-banking-wallet/mifos-mobile-openmf-mifos-mobile/
providers:
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id002
  name: Apache Fineract (Mifos platform)
  slug: apache-fineract
  status: profiled
  tags: *id003
  url: /providers/apache-fineract/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id004
  name: Firebase Analytics
  slug: firebase
  status: profiled
  tags: *id005
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id006
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id007
  url: /providers/google-maps/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id008
  name: Google Play (Integrity, In-App Review, In-App Update)
  slug: google-play
  status: profiled
  tags: *id009
  url: /providers/google-play/
siblings:
- name: Cash App
  rows: 7
  url: /applications/mobile-banking-wallet/cash-app/
- name: Mifos Pay (openMF mobile-wallet)
  rows: 5
  url: /applications/mobile-banking-wallet/mifos-pay-openmf-mobile-wallet/
- name: PayPal
  rows: 3
  url: /applications/mobile-banking-wallet/paypal/
- name: Revolut
  rows: 3
  url: /applications/mobile-banking-wallet/revolut/
- name: Wise
  rows: 15
  url: /applications/mobile-banking-wallet/wise/
sitemap: true
title: 'Mifos Mobile (openMF mifos-mobile): Mobile Banking & Payments Wallet reference app'
---
