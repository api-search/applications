---
app: Freshdesk
app_slug: freshdesk
app_url: https://www.freshworks.com/freshdesk/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: domain
  name: Software Product Engineering Management
  providers:
  - Atlassian Jira Plus
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics / Crashlytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: common
  name: Scheduling & Appointment Management
  providers:
  - Google Calendar
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
category:
  id: helpdesk-ticketing
  name: Help Desk & Customer Support
  url: /applications/helpdesk-ticketing/
counts:
  declared: 4
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
- route: integrations page
  url: https://www.freshworks.com/apps/freshdesk/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 23.0
    mcp: &id003
      status: none
    slug: branch-io
    status: profiled
    tags: &id004
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id008
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id001
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id002
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Atlassian Jira Plus
  provider: jira
  says: lists Atlassian Jira Plus as an integration
  source: https://www.freshworks.com/apps/freshdesk/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
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
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.freshworks.com/apps/freshdesk/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id009
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id010
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.freshworks.com/apps/freshdesk/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id011
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id012
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.freshworks.com/apps/freshdesk/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/helpdesk-ticketing/freshdesk/
providers:
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id001
  name: Atlassian Jira Plus
  slug: jira
  status: profiled
  tags: *id002
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id003
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id004
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id005
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id006
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id007
  name: Google Firebase Analytics / Crashlytics
  slug: firebase
  status: profiled
  tags: *id008
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id009
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id010
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id011
  name: Slack
  slug: slack
  status: profiled
  tags: *id012
  url: /providers/slack/
siblings:
- name: Chatwoot
  rows: 33
  url: /applications/helpdesk-ticketing/chatwoot/
- name: FreeScout
  rows: 12
  url: /applications/helpdesk-ticketing/freescout/
- name: Help Scout
  rows: 24
  url: /applications/helpdesk-ticketing/help-scout/
- name: Intercom
  rows: 1
  url: /applications/helpdesk-ticketing/intercom/
- name: Zammad
  rows: 23
  url: /applications/helpdesk-ticketing/zammad/
- name: Zendesk
  rows: 2
  url: /applications/helpdesk-ticketing/zendesk/
sitemap: true
title: 'Freshdesk: Help Desk & Customer Support reference app'
---
