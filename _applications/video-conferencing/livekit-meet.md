---
app: LiveKit Meet
app_slug: livekit-meet
app_url: https://github.com/livekit-examples/meet
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.30
  key: AE-110.30
  layer: domain
  name: Speech & Voice
  providers:
  - Krisp
  url: /capabilities/speech-voice/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - LiveKit (Cloud or self-hosted SFU)
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: video-conferencing
  name: Video Conferencing & Webinars
  url: /applications/video-conferencing/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
- route: source code
  url: https://raw.githubusercontent.com/livekit-examples/meet/main/.env.example
integrations:
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
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id001
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id002
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30
    key: AE-110.30
    name: Speech & Voice
    url: /capabilities/speech-voice/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id003
      status: none
    slug: krisp
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Company
    - Speech
    - Voice AI
    url: /providers/krisp/
  layer: domain
  name: Krisp
  provider: krisp
  says: ships the Krisp SDK or integration code
  source: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id005
      status: none
    slug: livekit
    status: profiled
    tags: &id006
    - Audio
    - Real-Time
    - Video
    - WebRTC
    url: /providers/livekit/
  layer: domain
  name: LiveKit (Cloud or self-hosted SFU)
  provider: livekit
  says: ships the LiveKit (Cloud or self-hosted SFU) SDK or integration code
  source: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-conferencing/livekit-meet/
providers:
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id001
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id002
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id003
  name: Krisp
  slug: krisp
  status: profiled
  tags: *id004
  url: /providers/krisp/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id005
  name: LiveKit (Cloud or self-hosted SFU)
  slug: livekit
  status: profiled
  tags: *id006
  url: /providers/livekit/
siblings:
- name: BigBlueButton
  rows: 5
  url: /applications/video-conferencing/bigbluebutton/
- name: Jitsi Meet
  rows: 9
  url: /applications/video-conferencing/jitsi-meet/
- name: Microsoft Teams
  rows: 1
  url: /applications/video-conferencing/microsoft-teams/
- name: Nextcloud Talk
  rows: 8
  url: /applications/video-conferencing/nextcloud-talk/
- name: Webex Meetings
  rows: 2
  url: /applications/video-conferencing/webex-meetings/
- name: Zoom
  rows: 7
  url: /applications/video-conferencing/zoom/
sitemap: true
title: 'LiveKit Meet: Video Conferencing & Webinars reference app'
---
