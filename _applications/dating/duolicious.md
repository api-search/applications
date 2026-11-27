---
app: Duolicious
app_slug: duolicious
app_url: https://duolicious.app/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Spotify
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: Turbo EA
  id: BC-620.30.30
  key: BC-620.30.30
  layer: common
  name: Cyber Threat Intelligence
  providers:
  - FireHOL IP lists
  url: /capabilities/threat-detection-response-management/
  via_parent: Threat Detection & Response Management
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - RIPE NCC (RIPEstat)
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - RevenueCat
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Apple
  - Discord
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: dating
  name: Dating
  url: /applications/dating/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/duolicious/duolicious-backend/blob/main/backend/requirements.txt
- route: dependency manifest
  url: https://github.com/duolicious/duolicious-frontend/blob/main/package.json
- route: source code
  url: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
- route: source code
  url: https://github.com/duolicious/duolicious-backend/tree/main/backend
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
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple
  provider: apple
  says: ships the Apple SDK or integration code
  source: https://github.com/duolicious/duolicious-frontend/blob/main/package.json
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id003
      status: none
    slug: discord
    status: profiled
    tags: &id004
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.30.30
    key: BC-620.30.30
    name: Cyber Threat Intelligence
    url: /capabilities/threat-detection-response-management/
    via_parent: Threat Detection & Response Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id005
      status: none
    slug: firehol
    status: profiled
    tags: &id006
    - Company
    - IP Reputation
    - Security
    - Threat Intelligence
    url: /providers/firehol/
  layer: common
  name: FireHOL IP lists
  provider: firehol
  says: ships the FireHOL IP lists SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/tree/main/backend
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
    mcp: &id007
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id008
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id009
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id011
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id012
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
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
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id013
      source: https://www.revenuecat.com/docs/tools/mcp
      status: verified
    slug: revenuecat
    status: profiled
    tags: &id014
    - Billing
    - In-App Purchases
    - Mobile
    - Subscription
    url: /providers/revenuecat/
  layer: common
  name: RevenueCat
  provider: revenuecat
  says: ships the RevenueCat SDK or integration code
  source: https://github.com/duolicious/duolicious-frontend/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.3
    band: developing
    in_catalog: true
    kin_score: 39.9
    mcp: &id015
      status: none
    slug: ripe-ncc
    status: profiled
    tags: &id016
    - Company
    - Internet
    - Not-for-profit
    - Regional Internet Registry
    url: /providers/ripe-ncc/
  layer: common
  name: RIPE NCC (RIPEstat)
  provider: ripe-ncc
  says: ships the RIPE NCC (RIPEstat) SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
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
    mcp: &id017
      status: none
    slug: spotify
    status: profiled
    tags: &id018
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/dating/duolicious/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id003
  name: Discord
  slug: discord
  status: profiled
  tags: *id004
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id005
  name: FireHOL IP lists
  slug: firehol
  status: profiled
  tags: *id006
  url: /providers/firehol/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id007
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id008
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id009
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id010
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id011
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id012
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id013
  name: RevenueCat
  slug: revenuecat
  status: profiled
  tags: *id014
  url: /providers/revenuecat/
- agent_band: agent-aware
  agent_readiness: 14.3
  band: developing
  in_catalog: true
  kin_score: 39.9
  mcp: *id015
  name: RIPE NCC (RIPEstat)
  slug: ripe-ncc
  status: profiled
  tags: *id016
  url: /providers/ripe-ncc/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id017
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id018
  url: /providers/spotify/
siblings:
- name: Alovoa
  rows: 2
  url: /applications/dating/alovoa/
- name: Bumble
  rows: 23
  url: /applications/dating/bumble/
- name: Grindr
  rows: 24
  url: /applications/dating/grindr/
- name: Hinge
  rows: 53
  url: /applications/dating/hinge/
- name: pH7Builder
  rows: 8
  url: /applications/dating/ph7builder/
- name: Tinder
  rows: 15
  url: /applications/dating/tinder/
sitemap: true
title: 'Duolicious: Dating reference app'
---
