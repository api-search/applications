---
app: MMM-MyScoreboard
app_slug: mmm-myscoreboard
app_url: https://github.com/jclarke0000/MMM-MyScoreboard
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.80.40
  key: AE-180.80.40
  layer: domain
  name: Sports Data
  providers:
  - ESPN site API scoreboards (site.api.espn.com)
  - Sportsnet stats ticker (mobile-statsv2.sportsnet.ca)
  url: /capabilities/sports-betting-fantasy/
  via_parent: Sports, Betting & Fantasy
category:
  id: sports-fantasy
  name: Sports Scores & Fantasy
  url: /applications/sports-fantasy/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/package.json
- route: source code
  url: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/ESPN.js
- route: source code
  url: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/SNET.js
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
    kin_score: 4.1
    mcp: &id001
      status: none
    slug: espn
    status: profiled
    tags: &id002
    - Broadcasting
    - Company
    - Media
    - Sports
    url: /providers/espn/
  layer: domain
  name: ESPN site API scoreboards (site.api.espn.com)
  provider: espn
  says: ships the ESPN site API scoreboards (site.api.espn.com) SDK or integration code
  source: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/ESPN.js
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
    agent_readiness: 5.6
    band: minimal
    in_catalog: true
    kin_score: 5.4
    mcp: &id003
      status: unknown
    slug: sportsnet
    status: profiled
    tags: &id004
    - Canada
    - Media
    - News
    - Sports
    url: /providers/sportsnet/
  layer: domain
  name: Sportsnet stats ticker (mobile-statsv2.sportsnet.ca)
  provider: sportsnet
  says: ships the Sportsnet stats ticker (mobile-statsv2.sportsnet.ca) SDK or integration code
  source: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/SNET.js
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sports-fantasy/mmm-myscoreboard/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id001
  name: ESPN site API scoreboards (site.api.espn.com)
  slug: espn
  status: profiled
  tags: *id002
  url: /providers/espn/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: minimal
  in_catalog: true
  kin_score: 5.4
  mcp: *id003
  name: Sportsnet stats ticker (mobile-statsv2.sportsnet.ca)
  slug: sportsnet
  status: profiled
  tags: *id004
  url: /providers/sportsnet/
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
title: 'MMM-MyScoreboard: Sports Scores & Fantasy reference app'
---
