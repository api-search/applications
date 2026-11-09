---
app: Team Tracker (Home Assistant)
app_slug: team-tracker-home-assistant
app_url: https://github.com/vasqued2/ha-teamtracker
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.80.40
  key: AE-180.80.40
  layer: domain
  name: Sports Data
  providers:
  - CFL scoreboard JSON (cflscoreboard.cfl.ca)
  - ESPN site API scoreboards
  - HockeyTech league feed (lscluster.hockeytech.com)
  - MLB Stats API (statsapi.mlb.com)
  url: /capabilities/sports-betting-fantasy/
  via_parent: Sports, Betting & Fantasy
category:
  id: sports-fantasy
  name: Sports Scores & Fantasy
  url: /applications/sports-fantasy/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: source code
  url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/const.py
- route: source code
  url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_cflscoreboard.py
- route: source code
  url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_espn.py
- route: source code
  url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_hockeytech.py
- route: source code
  url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_mlbstats.py
integrations:
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
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id001
      status: none
    slug: cfl
    status: profiled
    tags: &id002
    - Canada
    - Football
    - Professional League
    - Sports
    url: /providers/cfl/
  layer: domain
  name: CFL scoreboard JSON (cflscoreboard.cfl.ca)
  provider: cfl
  says: ships the CFL scoreboard JSON (cflscoreboard.cfl.ca) SDK or integration code
  source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_cflscoreboard.py
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
  name: ESPN site API scoreboards
  provider: espn
  says: ships the ESPN site API scoreboards SDK or integration code
  source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_espn.py
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
    agent_band: agent-aware
    agent_readiness: 5.4
    band: minimal
    in_catalog: true
    kin_score: 8.8
    mcp: &id005
      status: none
    slug: hockeytech
    status: profiled
    tags: &id006
    - Analytics
    - Data
    - Sports
    - Streaming
    url: /providers/hockeytech/
  layer: domain
  name: HockeyTech league feed (lscluster.hockeytech.com)
  provider: hockeytech
  says: ships the HockeyTech league feed (lscluster.hockeytech.com) SDK or integration code
  source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_hockeytech.py
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
    agent_band: agent-aware
    agent_readiness: 13.9
    band: emerging
    in_catalog: true
    kin_score: 22.2
    mcp: &id007
      status: none
    slug: major-league-baseball
    status: profiled
    tags: &id008
    - Analytics
    - Baseball
    - Entertainment
    - Media
    url: /providers/major-league-baseball/
  layer: domain
  name: MLB Stats API (statsapi.mlb.com)
  provider: major-league-baseball
  says: ships the MLB Stats API (statsapi.mlb.com) SDK or integration code
  source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_mlbstats.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sports-fantasy/team-tracker-home-assistant/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id001
  name: CFL scoreboard JSON (cflscoreboard.cfl.ca)
  slug: cfl
  status: profiled
  tags: *id002
  url: /providers/cfl/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id003
  name: ESPN site API scoreboards
  slug: espn
  status: profiled
  tags: *id004
  url: /providers/espn/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: minimal
  in_catalog: true
  kin_score: 8.8
  mcp: *id005
  name: HockeyTech league feed (lscluster.hockeytech.com)
  slug: hockeytech
  status: profiled
  tags: *id006
  url: /providers/hockeytech/
- agent_band: agent-aware
  agent_readiness: 13.9
  band: emerging
  in_catalog: true
  kin_score: 22.2
  mcp: *id007
  name: MLB Stats API (statsapi.mlb.com)
  slug: major-league-baseball
  status: profiled
  tags: *id008
  url: /providers/major-league-baseball/
siblings:
- name: ESPN
  rows: 10
  url: /applications/sports-fantasy/espn/
- name: ffscrapr
  rows: 6
  url: /applications/sports-fantasy/ffscrapr/
- name: GameDay Bot (fantasy_football_chat_bot)
  rows: 4
  url: /applications/sports-fantasy/gameday-bot-fantasy-football-chat-bot/
- name: MMM-MyScoreboard
  rows: 2
  url: /applications/sports-fantasy/mmm-myscoreboard/
- name: Sleeper
  rows: 8
  url: /applications/sports-fantasy/sleeper/
- name: theScore
  rows: 26
  url: /applications/sports-fantasy/thescore/
- name: Yahoo Fantasy
  rows: 8
  url: /applications/sports-fantasy/yahoo-fantasy/
sitemap: true
title: 'Team Tracker (Home Assistant): Sports Scores & Fantasy reference app'
---
