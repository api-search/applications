---
app: Fantastical
app_slug: fantastical
app_url: https://flexibits.com/fantastical
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Exchange
  - Google Calendar
  - iCloud / FaceTime
  - Microsoft 365
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: domain
  name: Personal Task & To-Do Lists
  providers:
  - Todoist
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Google Meet
  - Microsoft Teams
  - Webex
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - AccuWeather
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: calendar-contacts
  name: Calendar & Contacts
  url: /applications/calendar-contacts/
counts:
  declared: 10
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://flexibits.com/fantastical
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id001
      status: none
    slug: accuweather
    status: profiled
    tags: &id002
    - Forecast
    - Location Services
    - Meteorology
    - Weather
    url: /providers/accuweather/
  layer: domain
  name: AccuWeather
  provider: accuweather
  says: lists AccuWeather as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id003
      status: none
    slug: microsoft-exchange
    status: profiled
    tags: &id004
    - Calendar
    - Collaboration
    - Contacts
    - Email
    url: /providers/microsoft-exchange/
  layer: domain
  name: Exchange
  provider: microsoft-exchange
  says: lists Exchange as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id005
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id006
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id007
      status: none
    slug: google-meet
    status: profiled
    tags: &id008
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id009
      status: none
    slug: apple
    status: profiled
    tags: &id010
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: iCloud / FaceTime
  provider: apple
  says: lists iCloud / FaceTime as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id012
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id013
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id014
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-923
    key: AE-923
    name: Personal Task & To-Do Lists
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id015
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id016
    - Productivity
    - Task
    - Task Management
    - To-Do
    url: /providers/todoist/
  layer: domain
  name: Todoist
  provider: todoist
  says: lists Todoist as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id017
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id018
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: lists Webex as an integration
  source: https://flexibits.com/fantastical
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id019
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id020
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://flexibits.com/fantastical
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/calendar-contacts/fantastical/
providers:
- agent_band: agent-aware
  agent_readiness: 24.9
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id001
  name: AccuWeather
  slug: accuweather
  status: profiled
  tags: *id002
  url: /providers/accuweather/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id003
  name: Exchange
  slug: microsoft-exchange
  status: profiled
  tags: *id004
  url: /providers/microsoft-exchange/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id005
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id006
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id007
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id008
  url: /providers/google-meet/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id009
  name: iCloud / FaceTime
  slug: apple
  status: profiled
  tags: *id010
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id011
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id012
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id013
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id014
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id015
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id016
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id017
  name: Webex
  slug: webex
  status: profiled
  tags: *id018
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id019
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id020
  url: /providers/zoom/
siblings:
- name: DAVx5
  rows: 14
  url: /applications/calendar-contacts/davx5/
- name: Etar
  rows: 0
  url: /applications/calendar-contacts/etar/
- name: Monica
  rows: 15
  url: /applications/calendar-contacts/monica/
- name: Morgen
  rows: 20
  url: /applications/calendar-contacts/morgen/
- name: Notion Calendar
  rows: 10
  url: /applications/calendar-contacts/notion-calendar/
- name: Radicale
  rows: 0
  url: /applications/calendar-contacts/radicale/
sitemap: true
title: 'Fantastical: Calendar & Contacts reference app'
---
