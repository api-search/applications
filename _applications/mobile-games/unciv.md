---
app: Unciv
app_slug: unciv
app_url: https://github.com/yairm210/Unciv
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox (multiplayer turn files)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-180.40.10
  key: AE-180.40.10
  layer: domain
  name: Mods & User-Generated Content Distribution
  providers:
  - GitHub (mod discovery + download)
  url: /capabilities/game-publishing-distribution/
  via_parent: Game Publishing & Distribution
- attribution: API Evangelist extension
  id: AE-180.30.10
  key: AE-180.30.10
  layer: domain
  name: Rich Presence & Player Status
  providers:
  - Discord Rich Presence (java-discord-rpc)
  url: /capabilities/player-engagement/
  via_parent: Player Engagement
category:
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/yairm210/Unciv/blob/master/gradle/libs.versions.toml
- route: source code
  url: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/github/GithubAPI.kt
- route: source code
  url: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/multiplayer/storage/DropBox.kt
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
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
  name: Discord Rich Presence (java-discord-rpc)
  provider: discord
  says: ships the Discord Rich Presence (java-discord-rpc) SDK or integration code
  source: https://github.com/yairm210/Unciv/blob/master/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id003
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id004
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox (multiplayer turn files)
  provider: dropbox
  says: ships the Dropbox (multiplayer turn files) SDK or integration code
  source: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/multiplayer/storage/DropBox.kt
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub (mod discovery + download)
  provider: github
  says: ships the GitHub (mod discovery + download) SDK or integration code
  source: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/github/GithubAPI.kt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/unciv/
providers:
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id001
  name: Discord Rich Presence (java-discord-rpc)
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id003
  name: Dropbox (multiplayer turn files)
  slug: dropbox
  status: profiled
  tags: *id004
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id005
  name: GitHub (mod discovery + download)
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
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
- name: Talo
  rows: 7
  url: /applications/mobile-games/talo/
sitemap: true
title: 'Unciv: Mobile & Casual Games (live-ops backend) reference app'
---
