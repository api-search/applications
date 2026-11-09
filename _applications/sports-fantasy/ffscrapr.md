---
app: ffscrapr
app_slug: ffscrapr
app_url: https://github.com/ffverse/ffscrapr
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.80.20
  key: AE-180.80.20
  layer: domain
  name: Fantasy Sports
  providers:
  - DynastyProcess player-ID and values data files
  - ESPN Fantasy league API (lm-api-reads.fantasy.espn.com)
  - Fleaflicker API
  - MyFantasyLeague API (api.myfantasyleague.com)
  - Sleeper API (api.sleeper.app/v1)
  url: /capabilities/sports-betting-fantasy/
  via_parent: Sports, Betting & Fantasy
- attribution: API Evangelist extension
  id: AE-180.80.40
  key: AE-180.80.40
  layer: domain
  name: Sports Data
  providers:
  - nflverse data via nflreadr
  url: /capabilities/sports-betting-fantasy/
  via_parent: Sports, Betting & Fantasy
category:
  id: sports-fantasy
  name: Sports Scores & Fantasy
  url: /applications/sports-fantasy/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ffverse/ffscrapr/blob/main/DESCRIPTION
- route: source code
  url: https://github.com/ffverse/ffscrapr/blob/main/R/1_import_dp.R
- route: source code
  url: https://github.com/ffverse/ffscrapr/blob/main/R/espn_api.R
- route: source code
  url: https://github.com/ffverse/ffscrapr/blob/main/R/flea_api.R
- route: source code
  url: https://github.com/ffverse/ffscrapr/blob/main/R/mfl_api.R
- route: source code
  url: https://github.com/ffverse/ffscrapr/blob/main/R/sleeper_api.R
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.20
    key: AE-180.80.20
    name: Fantasy Sports
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.0
    mcp: &id001
      status: none
    slug: dynastyprocess
    status: profiled
    tags: &id002
    - Analytics
    - Company
    - Data
    - Fantasy Football
    url: /providers/dynastyprocess/
  layer: domain
  name: DynastyProcess player-ID and values data files
  provider: dynastyprocess
  says: ships the DynastyProcess player-ID and values data files SDK or integration code
  source: https://github.com/ffverse/ffscrapr/blob/main/R/1_import_dp.R
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.20
    key: AE-180.80.20
    name: Fantasy Sports
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id003
      status: none
    slug: espn
    status: profiled
    tags: &id004
    - Broadcasting
    - Company
    - Media
    - Sports
    url: /providers/espn/
  layer: domain
  name: ESPN Fantasy league API (lm-api-reads.fantasy.espn.com)
  provider: espn
  says: ships the ESPN Fantasy league API (lm-api-reads.fantasy.espn.com) SDK or integration code
  source: https://github.com/ffverse/ffscrapr/blob/main/R/espn_api.R
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.20
    key: AE-180.80.20
    name: Fantasy Sports
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id005
      status: none
    slug: fleaflicker
    status: profiled
    tags: &id006
    - Company
    - Fantasy Sports
    - Football
    - Sports
    url: /providers/fleaflicker/
  layer: domain
  name: Fleaflicker API
  provider: fleaflicker
  says: ships the Fleaflicker API SDK or integration code
  source: https://github.com/ffverse/ffscrapr/blob/main/R/flea_api.R
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.20
    key: AE-180.80.20
    name: Fantasy Sports
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id007
      status: unknown
    slug: myfantasyleague
    status: profiled
    tags: &id008
    - Custom Scoring
    - Fantasy Sports
    - Football
    - League-Management
    url: /providers/myfantasyleague/
  layer: domain
  name: MyFantasyLeague API (api.myfantasyleague.com)
  provider: myfantasyleague
  says: ships the MyFantasyLeague API (api.myfantasyleague.com) SDK or integration code
  source: https://github.com/ffverse/ffscrapr/blob/main/R/mfl_api.R
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.40
    key: AE-180.80.40
    name: Sports Data
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id009
      status: none
    slug: nflverse
    status: profiled
    tags: &id010
    - Analytics
    - Data
    - Open Source
    - Sports
    url: /providers/nflverse/
  layer: domain
  name: nflverse data via nflreadr
  provider: nflverse
  says: ships the nflverse data via nflreadr SDK or integration code
  source: https://github.com/ffverse/ffscrapr/blob/main/DESCRIPTION
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.20
    key: AE-180.80.20
    name: Fantasy Sports
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 30.2
    mcp: &id011
      status: unknown
    slug: sleeper
    status: profiled
    tags: &id012
    - Company
    - Fantasy Football
    - Fantasy Sports
    - Sports
    url: /providers/sleeper/
  layer: domain
  name: Sleeper API (api.sleeper.app/v1)
  provider: sleeper
  says: ships the Sleeper API (api.sleeper.app/v1) SDK or integration code
  source: https://github.com/ffverse/ffscrapr/blob/main/R/sleeper_api.R
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sports-fantasy/ffscrapr/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id001
  name: DynastyProcess player-ID and values data files
  slug: dynastyprocess
  status: profiled
  tags: *id002
  url: /providers/dynastyprocess/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id003
  name: ESPN Fantasy league API (lm-api-reads.fantasy.espn.com)
  slug: espn
  status: profiled
  tags: *id004
  url: /providers/espn/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id005
  name: Fleaflicker API
  slug: fleaflicker
  status: profiled
  tags: *id006
  url: /providers/fleaflicker/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id007
  name: MyFantasyLeague API (api.myfantasyleague.com)
  slug: myfantasyleague
  status: profiled
  tags: *id008
  url: /providers/myfantasyleague/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id009
  name: nflverse data via nflreadr
  slug: nflverse
  status: profiled
  tags: *id010
  url: /providers/nflverse/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 30.2
  mcp: *id011
  name: Sleeper API (api.sleeper.app/v1)
  slug: sleeper
  status: profiled
  tags: *id012
  url: /providers/sleeper/
siblings:
- name: ESPN
  rows: 10
  url: /applications/sports-fantasy/espn/
- name: GameDay Bot (fantasy_football_chat_bot)
  rows: 4
  url: /applications/sports-fantasy/gameday-bot-fantasy-football-chat-bot/
- name: MMM-MyScoreboard
  rows: 2
  url: /applications/sports-fantasy/mmm-myscoreboard/
- name: Sleeper
  rows: 8
  url: /applications/sports-fantasy/sleeper/
- name: Team Tracker (Home Assistant)
  rows: 4
  url: /applications/sports-fantasy/team-tracker-home-assistant/
- name: theScore
  rows: 26
  url: /applications/sports-fantasy/thescore/
- name: Yahoo Fantasy
  rows: 8
  url: /applications/sports-fantasy/yahoo-fantasy/
sitemap: true
title: 'ffscrapr: Sports Scores & Fantasy reference app'
---
