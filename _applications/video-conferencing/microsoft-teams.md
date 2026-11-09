---
app: Microsoft Teams
app_slug: microsoft-teams
app_url: https://www.microsoft.com/microsoft-teams/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Visual Studio App Center Crashes
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: video-conferencing
  name: Video Conferencing & Webinars
  url: /applications/video-conferencing/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.teams/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: microsoft-app-center
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: common
  name: Visual Studio App Center Crashes
  provider: microsoft-app-center
  says: ships the Visual Studio App Center Crashes SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.teams/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-conferencing/microsoft-teams/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Visual Studio App Center Crashes
  slug: microsoft-app-center
  status: queued for profiling
  tags: *id002
  url: null
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
title: 'Microsoft Teams: Video Conferencing & Webinars reference app'
---
