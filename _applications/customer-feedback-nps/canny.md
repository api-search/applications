---
app: Canny
app_slug: canny
app_url: https://canny.io
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Intercom
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.10
  key: product-discovery-backlog-management
  layer: domain
  name: Product Discovery & Backlog Management
  providers:
  - Asana
  - Azure DevOps
  - ClickUp
  - GitHub
  - Jira
  - Linear
  url: /capabilities/product-discovery-backlog-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Discord
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Google Workspace
  - Microsoft Entra ID
  - Okta
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: customer-feedback-nps
  name: Customer Feedback & NPS
  url: /applications/customer-feedback-nps/
counts:
  declared: 18
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://canny.io/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id001
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id002
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: exemplar
    in_catalog: true
    kin_score: 81.9
    mcp: &id003
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id004
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure DevOps
  provider: microsoft-azure-devops
  says: lists Azure DevOps as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id005
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id006
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: domain
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://canny.io/integrations
  tier: declared
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id007
      status: none
    slug: discord
    status: profiled
    tags: &id008
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id009
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id011
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id012
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id013
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id014
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id015
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id016
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id017
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
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
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id021
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id022
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id023
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id024
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: lists Microsoft Entra ID as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id025
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id026
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id027
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id028
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: common
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id029
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id030
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id031
      status: none
    slug: segment
    status: profiled
    tags: &id032
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://canny.io/integrations
  tier: declared
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
    mcp: &id033
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id034
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://canny.io/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id035
      status: none
    slug: zendesk
    status: profiled
    tags: &id036
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://canny.io/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/customer-feedback-nps/canny/
providers:
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id001
  name: Asana
  slug: asana
  status: profiled
  tags: *id002
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: exemplar
  in_catalog: true
  kin_score: 81.9
  mcp: *id003
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id005
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id006
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id007
  name: Discord
  slug: discord
  status: profiled
  tags: *id008
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id011
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id012
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id013
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id014
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id015
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id016
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id017
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id018
  url: /providers/intercom/
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
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id021
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id022
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id023
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id024
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id025
  name: Okta
  slug: okta
  status: profiled
  tags: *id026
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id027
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id028
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id029
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id030
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id031
  name: Segment
  slug: segment
  status: profiled
  tags: *id032
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id033
  name: Slack
  slug: slack
  status: profiled
  tags: *id034
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id035
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id036
  url: /providers/zendesk/
siblings:
- name: ClearFlask
  rows: 15
  url: /applications/customer-feedback-nps/clearflask/
- name: Fider
  rows: 8
  url: /applications/customer-feedback-nps/fider/
- name: Formbricks
  rows: 22
  url: /applications/customer-feedback-nps/formbricks/
- name: Retently
  rows: 17
  url: /applications/customer-feedback-nps/retently/
- name: SurveyMonkey
  rows: 6
  url: /applications/customer-feedback-nps/surveymonkey/
- name: Survicate
  rows: 25
  url: /applications/customer-feedback-nps/survicate/
sitemap: true
title: 'Canny: Customer Feedback & NPS reference app'
---
