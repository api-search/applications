---
app: Notion
app_slug: notion
app_url: https://www.notion.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.60.30
  key: AE-110.60.30
  layer: agent
  name: Retrieval-Augmented Generation
  providers:
  - GitHub
  - Gmail
  - Google Calendar
  - Google Drive
  - Jira
  - Linear
  - Microsoft OneDrive
  - Microsoft Outlook
  - Microsoft SharePoint
  - Microsoft Teams
  - Slack
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
category:
  id: notes-knowledge
  name: Notes & Personal Knowledge Management
  url: /applications/notes-knowledge/
counts:
  declared: 11
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/notion.id/latest/
- route: integrations page
  url: https://www.notion.com/help/notion-ai-connectors
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id002
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/notion.id/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id003
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id004
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: agent
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id005
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id006
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: agent
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
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
  layer: agent
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: agent
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id011
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id012
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: agent
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id013
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id014
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: agent
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id015
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id016
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: agent
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: lists Microsoft OneDrive as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id017
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id018
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: agent
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id019
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id020
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: agent
  name: Microsoft SharePoint
  provider: sharepoint
  says: lists Microsoft SharePoint as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id021
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id022
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: agent
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id023
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id024
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: agent
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.notion.com/help/notion-ai-connectors
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/notes-knowledge/notion/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id001
  name: Firebase Crashlytics
  slug: firebase
  status: profiled
  tags: *id002
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id003
  name: GitHub
  slug: github
  status: profiled
  tags: *id004
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id005
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id006
  url: /providers/google-gmail/
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
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id009
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id010
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id011
  name: Jira
  slug: jira
  status: profiled
  tags: *id012
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id013
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id014
  url: /providers/linear-app/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id015
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id016
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id017
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id018
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id019
  name: Microsoft SharePoint
  slug: sharepoint
  status: profiled
  tags: *id020
  url: /providers/sharepoint/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id021
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id022
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id023
  name: Slack
  slug: slack
  status: profiled
  tags: *id024
  url: /providers/slack/
siblings:
- name: AFFiNE
  rows: 16
  url: /applications/notes-knowledge/affine/
- name: BookStack
  rows: 11
  url: /applications/notes-knowledge/bookstack/
- name: Joplin
  rows: 5
  url: /applications/notes-knowledge/joplin/
- name: Logseq
  rows: 3
  url: /applications/notes-knowledge/logseq/
- name: Obsidian
  rows: 0
  url: /applications/notes-knowledge/obsidian/
- name: Outline
  rows: 18
  url: /applications/notes-knowledge/outline/
- name: Wiki.js
  rows: 21
  url: /applications/notes-knowledge/wiki-js/
sitemap: true
title: 'Notion: Notes & Personal Knowledge Management reference app'
---
