---
app: Nakama
app_slug: nakama
app_url: https://github.com/heroiclabs/nakama
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: domain
  name: In-App Purchases & App Store Billing
  providers:
  - App Store receipt validation (verifyReceipt)
  - Facebook Instant Games purchases
  - Google Play purchases/subscriptions validation (androidpublisher v3)
  - Huawei IAP (HMS Core order service)
  - Samsung IAP server API
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-180.30
  key: AE-180.30
  layer: domain
  name: Player Engagement
  providers:
  - Google Play Games Services (games/v1/players/me)
  url: /capabilities/player-engagement/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Facebook Login / Graph friends / Limited Login
  - Google sign-in (ID token check)
  - Sign in with Apple + Game Center identity
  - 'Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList)'
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/heroiclabs/nakama/blob/master/go.mod
- route: source code
  url: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
- route: source code
  url: https://github.com/heroiclabs/nakama/blob/master/iap/iap_samsung.go
- route: source code
  url: https://github.com/heroiclabs/nakama/blob/master/social/social.go
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: App Store receipt validation (verifyReceipt)
  provider: apple
  says: ships the App Store receipt validation (verifyReceipt) SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
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
  name: Facebook Instant Games purchases
  provider: facebook
  says: ships the Facebook Instant Games purchases SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: *id001
  layer: domain
  name: Facebook Login / Graph friends / Limited Login
  provider: facebook
  says: ships the Facebook Login / Graph friends / Limited Login SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.30
    key: AE-180.30
    name: Player Engagement
    url: /capabilities/player-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: google-play-games
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Google Play Games Services (games/v1/players/me)
  provider: google-play-games
  says: ships the Google Play Games Services (games/v1/players/me) SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id009
      status: none
    slug: google-play
    status: profiled
    tags: &id010
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: domain
  name: Google Play purchases/subscriptions validation (androidpublisher v3)
  provider: google-play
  says: ships the Google Play purchases/subscriptions validation (androidpublisher v3) SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
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
  layer: domain
  name: Google sign-in (ID token check)
  provider: google-identity-platform
  says: ships the Google sign-in (ID token check) SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: huawei-mobile-services
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Huawei IAP (HMS Core order service)
  provider: huawei-mobile-services
  says: ships the Huawei IAP (HMS Core order service) SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.3
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id015
      status: none
    slug: samsung
    status: profiled
    tags: &id016
    - Consumer Electronics
    - Developer Platform
    - IoT
    - Mobile
    url: /providers/samsung/
  layer: domain
  name: Samsung IAP server API
  provider: samsung
  says: ships the Samsung IAP server API SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/iap/iap_samsung.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: *id002
  layer: domain
  name: Sign in with Apple + Game Center identity
  provider: apple
  says: ships the Sign in with Apple + Game Center identity SDK or integration code
  source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
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
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id017
      status: none
    slug: steam
    status: profiled
    tags: &id018
    - Distribution
    - Gaming
    - Steamworks
    - Valve
    url: /providers/steam/
  layer: domain
  name: 'Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList)'
  provider: steam
  says: 'ships the Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList) SDK or integration code'
  source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/nakama/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: App Store receipt validation (verifyReceipt)
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id005
  name: Facebook Instant Games purchases
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Google Play Games Services (games/v1/players/me)
  slug: google-play-games
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id009
  name: Google Play purchases/subscriptions validation (androidpublisher v3)
  slug: google-play
  status: profiled
  tags: *id010
  url: /providers/google-play/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id011
  name: Google sign-in (ID token check)
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Huawei IAP (HMS Core order service)
  slug: huawei-mobile-services
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: agent-ready
  agent_readiness: 37.3
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id015
  name: Samsung IAP server API
  slug: samsung
  status: profiled
  tags: *id016
  url: /providers/samsung/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id017
  name: 'Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList)'
  slug: steam
  status: profiled
  tags: *id018
  url: /providers/steam/
siblings:
- name: Candy Crush Saga
  rows: 15
  url: /applications/mobile-games/candy-crush-saga/
- name: Clash of Clans
  rows: 49
  url: /applications/mobile-games/clash-of-clans/
- name: Lichess mobile
  rows: 2
  url: /applications/mobile-games/lichess-mobile/
- name: Mindustry
  rows: 4
  url: /applications/mobile-games/mindustry/
- name: Subway Surfers
  rows: 29
  url: /applications/mobile-games/subway-surfers/
- name: Talo
  rows: 7
  url: /applications/mobile-games/talo/
- name: Unciv
  rows: 3
  url: /applications/mobile-games/unciv/
sitemap: true
title: 'Nakama: Mobile & Casual Games (live-ops backend) reference app'
---
