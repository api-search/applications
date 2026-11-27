---
app: Morgen
app_slug: morgen
app_url: https://www.morgen.so/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Apple Calendar / iCloud / Apple Reminders
  - Fastmail
  - fruux (CalDAV)
  - Google Calendar
  - Nextcloud (CalDAV)
  - Outlook Calendar / Outlook Email
  - Yahoo (CalDAV)
  - Zoho (CalDAV)
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: domain
  name: Personal Task & To-Do Lists
  providers:
  - Google Tasks
  - Microsoft To Do
  - Todoist
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - ClickUp
  - Linear
  - Notion
  - Obsidian
  url: /capabilities/project-management/
  via_parent: null
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
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: calendar-contacts
  name: Calendar & Contacts
  url: /applications/calendar-contacts/
counts:
  declared: 20
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.morgen.so/integrations
integrations:
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
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Calendar / iCloud / Apple Reminders
  provider: apple
  says: lists Apple Calendar / iCloud / Apple Reminders as an integration
  source: https://www.morgen.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id003
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id004
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: domain
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://www.morgen.so/integrations
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
    agent_readiness: 17.3
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id005
      status: none
    slug: fastmail
    status: profiled
    tags: &id006
    - Business
    - Email
    - Privacy
    - Security
    url: /providers/fastmail/
  layer: domain
  name: Fastmail
  provider: fastmail
  says: lists Fastmail as an integration
  source: https://www.morgen.so/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id007
      status: none
    slug: fruux
    status: profiled
    tags: &id008
    - Calendar
    - Contacts
    - Sync
    - Task
    url: /providers/fruux/
  layer: domain
  name: fruux (CalDAV)
  provider: fruux
  says: lists fruux (CalDAV) as an integration
  source: https://www.morgen.so/integrations
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
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id010
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.morgen.so/integrations
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
    mcp: &id011
      status: none
    slug: google-meet
    status: profiled
    tags: &id012
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://www.morgen.so/integrations
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
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id013
      status: none
    slug: google-tasks
    status: profiled
    tags: &id014
    - Google
    - Productivity
    - Task
    - Task Management
    url: /providers/google-tasks/
  layer: domain
  name: Google Tasks
  provider: google-tasks
  says: lists Google Tasks as an integration
  source: https://www.morgen.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id015
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id016
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://www.morgen.so/integrations
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
    mcp: &id017
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id018
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.morgen.so/integrations
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
    agent_readiness: 25.9
    band: strong
    in_catalog: true
    kin_score: 58.2
    mcp: &id019
      status: none
    slug: microsoft-to-do
    status: profiled
    tags: &id020
    - Microsoft
    - Microsoft 365
    - Productivity
    - Task
    url: /providers/microsoft-to-do/
  layer: domain
  name: Microsoft To Do
  provider: microsoft-to-do
  says: lists Microsoft To Do as an integration
  source: https://www.morgen.so/integrations
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id021
      status: none
    slug: nextcloud
    status: profiled
    tags: &id022
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud (CalDAV)
  provider: nextcloud
  says: lists Nextcloud (CalDAV) as an integration
  source: https://www.morgen.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id023
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id024
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://www.morgen.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id025
      status: none
    slug: obsidian
    status: profiled
    tags: &id026
    - Knowledge Management
    - Markdown
    - Notes
    - Productivity
    url: /providers/obsidian/
  layer: domain
  name: Obsidian
  provider: obsidian
  says: lists Obsidian as an integration
  source: https://www.morgen.so/integrations
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id027
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id028
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook Calendar / Outlook Email
  provider: microsoft-outlook
  says: lists Outlook Calendar / Outlook Email as an integration
  source: https://www.morgen.so/integrations
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
    mcp: &id029
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id030
    - Productivity
    - Task
    - Task Management
    - To-Do
    url: /providers/todoist/
  layer: domain
  name: Todoist
  provider: todoist
  says: lists Todoist as an integration
  source: https://www.morgen.so/integrations
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
    mcp: &id031
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id032
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: lists Webex as an integration
  source: https://www.morgen.so/integrations
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
    agent_readiness: 15.8
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id033
      status: none
    slug: yahoo
    status: profiled
    tags: &id034
    - Advertising
    - DSP
    - Fantasy Sports
    - Programmatic Advertising
    url: /providers/yahoo/
  layer: domain
  name: Yahoo (CalDAV)
  provider: yahoo
  says: lists Yahoo (CalDAV) as an integration
  source: https://www.morgen.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id035
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id036
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.morgen.so/integrations
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
    agent_readiness: 32.4
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id037
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id038
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: domain
  name: Zoho (CalDAV)
  provider: zoho
  says: lists Zoho (CalDAV) as an integration
  source: https://www.morgen.so/integrations
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
    mcp: &id039
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id040
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.morgen.so/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/calendar-contacts/morgen/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple Calendar / iCloud / Apple Reminders
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id003
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id004
  url: /providers/clickup/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id005
  name: Fastmail
  slug: fastmail
  status: profiled
  tags: *id006
  url: /providers/fastmail/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id007
  name: fruux (CalDAV)
  slug: fruux
  status: profiled
  tags: *id008
  url: /providers/fruux/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id009
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id010
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id011
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id012
  url: /providers/google-meet/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id013
  name: Google Tasks
  slug: google-tasks
  status: profiled
  tags: *id014
  url: /providers/google-tasks/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id015
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id016
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id017
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id018
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 58.2
  mcp: *id019
  name: Microsoft To Do
  slug: microsoft-to-do
  status: profiled
  tags: *id020
  url: /providers/microsoft-to-do/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id021
  name: Nextcloud (CalDAV)
  slug: nextcloud
  status: profiled
  tags: *id022
  url: /providers/nextcloud/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id023
  name: Notion
  slug: notion
  status: profiled
  tags: *id024
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id025
  name: Obsidian
  slug: obsidian
  status: profiled
  tags: *id026
  url: /providers/obsidian/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id027
  name: Outlook Calendar / Outlook Email
  slug: microsoft-outlook
  status: profiled
  tags: *id028
  url: /providers/microsoft-outlook/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id029
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id030
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id031
  name: Webex
  slug: webex
  status: profiled
  tags: *id032
  url: /providers/webex/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id033
  name: Yahoo (CalDAV)
  slug: yahoo
  status: profiled
  tags: *id034
  url: /providers/yahoo/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id035
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id036
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id037
  name: Zoho (CalDAV)
  slug: zoho
  status: profiled
  tags: *id038
  url: /providers/zoho/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id039
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id040
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
- name: Notion Calendar
  rows: 10
  url: /applications/calendar-contacts/notion-calendar/
- name: Radicale
  rows: 0
  url: /applications/calendar-contacts/radicale/
sitemap: true
title: 'Morgen: Calendar & Contacts reference app'
---
