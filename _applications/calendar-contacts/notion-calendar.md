---
app: Notion Calendar
app_slug: notion-calendar
app_url: https://www.notion.com/product/calendar
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - Notion
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Around
  - BlueJeans
  - Doxy.me
  - Google Meet
  - Microsoft Teams
  - Webex
  - Whereby
  - Zoom
  url: /capabilities/video-calling/
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
  url: https://www.notion.com/help/notion-calendar-integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id001
      status: none
    slug: around
    status: profiled
    tags: &id002
    - Collaboration
    - Company
    - Video
    - Video Conferencing
    url: /providers/around/
  layer: domain
  name: Around
  provider: around
  says: lists Around as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: bluejeans
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: BlueJeans
  provider: bluejeans
  says: lists BlueJeans as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id005
      status: none
    slug: doxy-me
    status: profiled
    tags: &id006
    - Company
    - HIPAA
    - Telehealth
    - Video
    url: /providers/doxy-me/
  layer: domain
  name: Doxy.me
  provider: doxy-me
  says: lists Doxy.me as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id008
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_band: agent-aware
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id009
      status: none
    slug: google-meet
    status: profiled
    tags: &id010
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id011
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id012
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id013
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id014
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_readiness: 61.1
    band: strong
    in_catalog: true
    kin_score: 64.2
    mcp: &id015
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id016
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: lists Webex as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id017
      status: none
    slug: whereby
    status: profiled
    tags: &id018
    - Communications
    - Real-Time
    - Video
    - WebRTC
    url: /providers/whereby/
  layer: domain
  name: Whereby
  provider: whereby
  says: lists Whereby as an integration
  source: https://www.notion.com/help/notion-calendar-integrations
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
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
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
  source: https://www.notion.com/help/notion-calendar-integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/calendar-contacts/notion-calendar/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id001
  name: Around
  slug: around
  status: profiled
  tags: *id002
  url: /providers/around/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: BlueJeans
  slug: bluejeans
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id005
  name: Doxy.me
  slug: doxy-me
  status: profiled
  tags: *id006
  url: /providers/doxy-me/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id007
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id008
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id009
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id010
  url: /providers/google-meet/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id011
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id012
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id013
  name: Notion
  slug: notion
  status: profiled
  tags: *id014
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 61.1
  band: strong
  in_catalog: true
  kin_score: 64.2
  mcp: *id015
  name: Webex
  slug: webex
  status: profiled
  tags: *id016
  url: /providers/webex/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id017
  name: Whereby
  slug: whereby
  status: profiled
  tags: *id018
  url: /providers/whereby/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
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
- name: Fantastical
  rows: 10
  url: /applications/calendar-contacts/fantastical/
- name: Monica
  rows: 15
  url: /applications/calendar-contacts/monica/
- name: Morgen
  rows: 20
  url: /applications/calendar-contacts/morgen/
- name: Radicale
  rows: 0
  url: /applications/calendar-contacts/radicale/
sitemap: true
title: 'Notion Calendar: Calendar & Contacts reference app'
---
