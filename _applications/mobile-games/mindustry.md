---
app: Mindustry
app_slug: mindustry
app_url: https://github.com/Anuken/Mindustry
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.40
  key: AE-180.40
  layer: domain
  name: Game Publishing & Distribution
  providers:
  - Steamworks (steamworks4j; Steam build)
  url: /capabilities/game-publishing-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-180.40.10
  key: AE-180.40.10
  layer: domain
  name: Mods & User-Generated Content Distribution
  providers:
  - GitHub (mod browser)
  url: /capabilities/game-publishing-distribution/
  via_parent: Game Publishing & Distribution
- attribution: API Evangelist extension
  id: AE-180.30.10
  key: AE-180.30.10
  layer: domain
  name: Rich Presence & Player Status
  providers:
  - Discord Rich Presence
  url: /capabilities/player-engagement/
  via_parent: Player Engagement
- attribution: Turbo EA
  id: BC-3740.30
  key: content-delivery-network-operations
  layer: common
  name: Content Delivery Network Operations
  providers:
  - jsDelivr (mod index, server lists)
  url: /capabilities/content-delivery-network-operations/
  via_parent: null
category:
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Anuken/Mindustry/blob/master/build.gradle
- route: source code
  url: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/Vars.java
- route: source code
  url: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/ui/dialogs/ModsDialog.java
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-180.30.10
    key: AE-180.30.10
    name: Rich Presence & Player Status
    url: /capabilities/player-engagement/
    via_parent: Player Engagement
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id001
      status: none
    slug: discord
    status: profiled
    tags: &id002
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord Rich Presence
  provider: discord
  says: ships the Discord Rich Presence SDK or integration code
  source: https://github.com/Anuken/Mindustry/blob/master/build.gradle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.40.10
    key: AE-180.40.10
    name: Mods & User-Generated Content Distribution
    url: /capabilities/game-publishing-distribution/
    via_parent: Game Publishing & Distribution
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
  layer: domain
  name: GitHub (mod browser)
  provider: github
  says: ships the GitHub (mod browser) SDK or integration code
  source: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/ui/dialogs/ModsDialog.java
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id005
      status: none
    slug: jsdelivr
    status: profiled
    tags: &id006
    - Development
    - Public APIs
    url: /providers/jsdelivr/
  layer: common
  name: jsDelivr (mod index, server lists)
  provider: jsdelivr
  says: ships the jsDelivr (mod index, server lists) SDK or integration code
  source: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/Vars.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.40
    key: AE-180.40
    name: Game Publishing & Distribution
    url: /capabilities/game-publishing-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id007
      status: none
    slug: steam
    status: profiled
    tags: &id008
    - Distribution
    - Gaming
    - Steamworks
    - Valve
    url: /providers/steam/
  layer: domain
  name: Steamworks (steamworks4j; Steam build)
  provider: steam
  says: ships the Steamworks (steamworks4j; Steam build) SDK or integration code
  source: https://github.com/Anuken/Mindustry/blob/master/build.gradle
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/mindustry/
providers:
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id001
  name: Discord Rich Presence
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id003
  name: GitHub (mod browser)
  slug: github
  status: profiled
  tags: *id004
  url: /providers/github/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id005
  name: jsDelivr (mod index, server lists)
  slug: jsdelivr
  status: profiled
  tags: *id006
  url: /providers/jsdelivr/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id007
  name: Steamworks (steamworks4j; Steam build)
  slug: steam
  status: profiled
  tags: *id008
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
- name: Nakama
  rows: 10
  url: /applications/mobile-games/nakama/
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
title: 'Mindustry: Mobile & Casual Games (live-ops backend) reference app'
---
