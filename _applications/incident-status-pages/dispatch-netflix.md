---
app: Dispatch (Netflix)
app_slug: dispatch-netflix
app_url: https://github.com/Netflix/dispatch
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - Opsgenie
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - AWS SQS
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Google Groups
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Confluence
  - Google Docs
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.20
  key: AE-160.10.20
  layer: common
  name: Multi-Factor Authentication
  providers:
  - Duo
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - GitHub
  - Jira
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Gmail
  url: /capabilities/email/
  via_parent: Email
category:
  id: incident-status-pages
  name: Incident Management & Status Pages
  url: /applications/incident-status-pages/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/Netflix/dispatch/blob/main/src/dispatch/plugins/dispatch_aws/plugin.py
- route: source code
  url: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
- route: source code
  url: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: domain
  name: AWS SQS
  provider: amazon-sqs
  says: ships the AWS SQS SDK or integration code
  source: https://github.com/Netflix/dispatch/blob/main/src/dispatch/plugins/dispatch_aws/plugin.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id003
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: confluence
    status: profiled
    tags: &id004
    - Collaboration
    - Content Management
    - Documentation
    - Knowledge Base
    url: /providers/confluence/
  layer: common
  name: Confluence
  provider: confluence
  says: ships the Confluence SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id005
      status: none
    slug: duo-security
    status: profiled
    tags: &id006
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: common
  name: Duo
  provider: duo-security
  says: ships the Duo SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id007
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id008
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id009
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id010
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: gmail
  says: ships the Gmail SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
  tier: observed
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
    mcp: &id011
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id012
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id013
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-docs
    status: profiled
    tags: &id014
    - Collaboration
    - Documents
    - Google Workspace
    - Productivity
    url: /providers/google-docs/
  layer: common
  name: Google Docs
  provider: google-docs
  says: ships the Google Docs SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id015
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id016
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id017
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id018
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Groups
  provider: google-workspace
  says: ships the Google Groups SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
  tier: observed
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id019
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id020
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
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
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id023
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id025
      status: none
    slug: opsgenie
    status: profiled
    tags: &id026
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id027
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id028
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id029
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id030
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
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
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id031
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id032
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: ships the Zoom SDK or integration code
  source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/incident-status-pages/dispatch-netflix/
providers:
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id001
  name: AWS SQS
  slug: amazon-sqs
  status: profiled
  tags: *id002
  url: /providers/amazon-sqs/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id003
  name: Confluence
  slug: confluence
  status: profiled
  tags: *id004
  url: /providers/confluence/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id005
  name: Duo
  slug: duo-security
  status: profiled
  tags: *id006
  url: /providers/duo-security/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id007
  name: GitHub
  slug: github
  status: profiled
  tags: *id008
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id009
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id010
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id011
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id012
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id013
  name: Google Docs
  slug: google-docs
  status: profiled
  tags: *id014
  url: /providers/google-docs/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id015
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id016
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id017
  name: Google Groups
  slug: google-workspace
  status: profiled
  tags: *id018
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id019
  name: Jira
  slug: jira
  status: profiled
  tags: *id020
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id021
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id022
  url: /providers/microsoft-teams/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id023
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id024
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id025
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id026
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id027
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id028
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id029
  name: Slack
  slug: slack
  status: profiled
  tags: *id030
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id031
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id032
  url: /providers/zoom/
siblings:
- name: Atlassian Statuspage
  rows: 14
  url: /applications/incident-status-pages/atlassian-statuspage/
- name: Cachet
  rows: 2
  url: /applications/incident-status-pages/cachet/
- name: FireHydrant
  rows: 35
  url: /applications/incident-status-pages/firehydrant/
- name: GoAlert
  rows: 8
  url: /applications/incident-status-pages/goalert/
- name: Grafana OnCall
  rows: 14
  url: /applications/incident-status-pages/grafana-oncall/
- name: incident.io
  rows: 20
  url: /applications/incident-status-pages/incident-io/
- name: PagerDuty
  rows: 10
  url: /applications/incident-status-pages/pagerduty/
sitemap: true
title: 'Dispatch (Netflix): Incident Management & Status Pages reference app'
---
