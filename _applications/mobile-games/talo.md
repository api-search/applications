---
app: Talo
app_slug: talo
app_url: https://github.com/TaloDev/backend
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.30
  key: AE-180.30
  layer: domain
  name: Player Engagement
  providers:
  - Game Center
  - Google Play Games
  - Steamworks (leaderboards, stats, players)
  url: /capabilities/player-engagement/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - HyperDX (@hyperdx/node-opentelemetry)
  - Sentry (@sentry/node)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe (Talo plan billing)
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/TaloDev/backend/blob/develop/package.json
- route: source code
  url: https://github.com/TaloDev/backend/blob/develop/envs/.env.dev
- route: source code
  url: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-180.30
    key: AE-180.30
    name: Player Engagement
    url: /capabilities/player-engagement/
    via_parent: null
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
  layer: domain
  name: Game Center
  provider: apple
  says: ships the Game Center SDK or integration code
  source: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
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
    mcp: &id003
      status: unchecked
    slug: google-play-games
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Google Play Games
  provider: google-play-games
  says: ships the Google Play Games SDK or integration code
  source: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
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
    agent_band: agent-aware
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id005
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id006
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://github.com/TaloDev/backend/blob/develop/envs/.env.dev
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
    agent_readiness: 37.0
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id007
      status: none
    slug: hyperdx
    status: profiled
    tags: &id008
    - Company
    - Logging
    - Monitoring
    - Observability
    url: /providers/hyperdx/
  layer: common
  name: HyperDX (@hyperdx/node-opentelemetry)
  provider: hyperdx
  says: ships the HyperDX (@hyperdx/node-opentelemetry) SDK or integration code
  source: https://github.com/TaloDev/backend/blob/develop/package.json
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
    mcp: &id009
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id010
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry (@sentry/node)
  provider: sentry-system
  says: ships the Sentry (@sentry/node) SDK or integration code
  source: https://github.com/TaloDev/backend/blob/develop/package.json
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
    agent_band: agent-aware
    agent_readiness: 22.1
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id011
      status: none
    slug: steam
    status: profiled
    tags: &id012
    - Distribution
    - Gaming
    - Steamworks
    - Valve
    url: /providers/steam/
  layer: domain
  name: Steamworks (leaderboards, stats, players)
  provider: steam
  says: ships the Steamworks (leaderboards, stats, players) SDK or integration code
  source: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
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
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id013
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id014
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe (Talo plan billing)
  provider: stripe
  says: ships the Stripe (Talo plan billing) SDK or integration code
  source: https://github.com/TaloDev/backend/blob/develop/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/talo/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Game Center
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Google Play Games
  slug: google-play-games
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id005
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id006
  url: /providers/hcaptcha/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id007
  name: HyperDX (@hyperdx/node-opentelemetry)
  slug: hyperdx
  status: profiled
  tags: *id008
  url: /providers/hyperdx/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id009
  name: Sentry (@sentry/node)
  slug: sentry-system
  status: profiled
  tags: *id010
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id011
  name: Steamworks (leaderboards, stats, players)
  slug: steam
  status: profiled
  tags: *id012
  url: /providers/steam/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id013
  name: Stripe (Talo plan billing)
  slug: stripe
  status: profiled
  tags: *id014
  url: /providers/stripe/
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
- name: Nakama
  rows: 10
  url: /applications/mobile-games/nakama/
- name: Subway Surfers
  rows: 29
  url: /applications/mobile-games/subway-surfers/
- name: Unciv
  rows: 3
  url: /applications/mobile-games/unciv/
sitemap: true
title: 'Talo: Mobile & Casual Games (live-ops backend) reference app'
---
