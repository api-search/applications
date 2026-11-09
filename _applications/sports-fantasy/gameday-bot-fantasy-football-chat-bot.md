---
app: GameDay Bot (fantasy_football_chat_bot)
app_slug: gameday-bot-fantasy-football-chat-bot
app_url: https://github.com/dtcarls/fantasy_football_chat_bot
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.80.20
  key: AE-180.80.20
  layer: domain
  name: Fantasy Sports
  providers:
  - ESPN Fantasy via espn_api
  url: /capabilities/sports-betting-fantasy/
  via_parent: Sports, Betting & Fantasy
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Discord webhook
  - GroupMe bots API
  - Slack incoming webhook
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: sports-fantasy
  name: Sports Scores & Fantasy
  url: /applications/sports-fantasy/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/requirements.txt
- route: source code
  url: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/chat/groupme.py
- route: source code
  url: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
integrations:
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
  layer: common
  name: Discord webhook
  provider: discord
  says: ships the Discord webhook SDK or integration code
  source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
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
  name: ESPN Fantasy via espn_api
  provider: espn
  says: ships the ESPN Fantasy via espn_api SDK or integration code
  source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/requirements.txt
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id005
      status: none
    slug: groupme
    status: profiled
    tags: &id006
    - Chat
    - Company
    - Consumer
    - Messaging
    url: /providers/groupme/
  layer: common
  name: GroupMe bots API
  provider: groupme
  says: ships the GroupMe bots API SDK or integration code
  source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/chat/groupme.py
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
    mcp: &id007
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id008
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack incoming webhook
  provider: slack
  says: ships the Slack incoming webhook SDK or integration code
  source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sports-fantasy/gameday-bot-fantasy-football-chat-bot/
providers:
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id001
  name: Discord webhook
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id003
  name: ESPN Fantasy via espn_api
  slug: espn
  status: profiled
  tags: *id004
  url: /providers/espn/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id005
  name: GroupMe bots API
  slug: groupme
  status: profiled
  tags: *id006
  url: /providers/groupme/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id007
  name: Slack incoming webhook
  slug: slack
  status: profiled
  tags: *id008
  url: /providers/slack/
siblings:
- name: ESPN
  rows: 10
  url: /applications/sports-fantasy/espn/
- name: ffscrapr
  rows: 6
  url: /applications/sports-fantasy/ffscrapr/
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
title: 'GameDay Bot (fantasy_football_chat_bot): Sports Scores & Fantasy reference app'
---
