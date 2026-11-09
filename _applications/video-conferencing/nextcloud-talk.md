---
app: Nextcloud Talk
app_slug: nextcloud-talk
app_url: https://github.com/nextcloud/spreed
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Discord
  - Mattermost
  - Microsoft Teams
  - Rocket.Chat
  - Slack
  - Steam chat
  - Telegram
  - Zulip
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: video-conferencing
  name: Video Conferencing & Webinars
  url: /applications/video-conferencing/
counts:
  declared: 0
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.nextcloud.talk2/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/nextcloud/spreed/main/composer.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/nextcloud/spreed/main/package.json
- route: source code
  url: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id003
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id004
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: domain
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id005
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id006
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id007
      source: https://docs.rocket.chat/docs/mcp-server
      status: verified
    slug: rocketchat
    status: profiled
    tags: &id008
    - Collaboration
    - Communications
    - Company
    - Open Source
    url: /providers/rocketchat/
  layer: domain
  name: Rocket.Chat
  provider: rocketchat
  says: ships the Rocket.Chat SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    mcp: &id009
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id010
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 34.4
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
  name: Steam chat
  provider: steam
  says: ships the Steam chat SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id013
      status: none
    slug: telegram
    status: profiled
    tags: &id014
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
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
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id015
      source: https://github.com/zulip/zulipmcp
      status: verified
    slug: zulip
    status: profiled
    tags: &id016
    - Collaboration
    - Messaging
    - Team Chat
    - Webhook
    url: /providers/zulip/
  layer: domain
  name: Zulip
  provider: zulip
  says: ships the Zulip SDK or integration code
  source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-conferencing/nextcloud-talk/
providers:
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id001
  name: Discord
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id003
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id004
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id005
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id006
  url: /providers/microsoft-teams/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id007
  name: Rocket.Chat
  slug: rocketchat
  status: profiled
  tags: *id008
  url: /providers/rocketchat/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id009
  name: Slack
  slug: slack
  status: profiled
  tags: *id010
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id011
  name: Steam chat
  slug: steam
  status: profiled
  tags: *id012
  url: /providers/steam/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id013
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id014
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id015
  name: Zulip
  slug: zulip
  status: profiled
  tags: *id016
  url: /providers/zulip/
siblings:
- name: BigBlueButton
  rows: 5
  url: /applications/video-conferencing/bigbluebutton/
- name: Jitsi Meet
  rows: 9
  url: /applications/video-conferencing/jitsi-meet/
- name: LiveKit Meet
  rows: 3
  url: /applications/video-conferencing/livekit-meet/
- name: Microsoft Teams
  rows: 1
  url: /applications/video-conferencing/microsoft-teams/
- name: Webex Meetings
  rows: 2
  url: /applications/video-conferencing/webex-meetings/
- name: Zoom
  rows: 7
  url: /applications/video-conferencing/zoom/
sitemap: true
title: 'Nextcloud Talk: Video Conferencing & Webinars reference app'
---
