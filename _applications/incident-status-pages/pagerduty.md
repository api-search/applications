---
app: PagerDuty
app_slug: pagerduty
app_url: https://www.pagerduty.com/
author: API Evangelist
capabilities:
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
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  - AWS
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Mixpanel
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.70.10
  key: AE-100.70.10
  layer: agent
  name: Coding Agents
  providers:
  - Cursor
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic Claude Connector
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: incident-status-pages
  name: Incident Management & Status Pages
  url: /applications/incident-status-pages/
counts:
  declared: 6
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
- route: integrations page
  url: https://www.pagerduty.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id010
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id011
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
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
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id014
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id015
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id016
      status: none
    slug: segment
    status: profiled
    tags: &id017
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
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
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id002
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id003
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic Claude Connector
  provider: anthropic
  says: lists Anthropic Claude Connector as an integration
  source: https://www.pagerduty.com/integrations/
  tier: declared
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id004
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id005
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: domain
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://www.pagerduty.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: strong
    in_catalog: true
    kin_score: 60.0
    mcp: &id006
      status: none
    slug: cursor
    status: profiled
    tags: &id007
    - Agents
    - Artificial Intelligence
    - Code Editor
    - Developer Tools
    url: /providers/cursor/
  layer: agent
  name: Cursor
  provider: cursor
  says: lists Cursor as an integration
  source: https://www.pagerduty.com/integrations/
  tier: declared
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id008
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id009
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://www.pagerduty.com/integrations/
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id012
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id013
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.pagerduty.com/integrations/
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
    mcp: &id018
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id019
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.pagerduty.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/incident-status-pages/pagerduty/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id002
  name: Anthropic Claude Connector
  slug: anthropic
  status: profiled
  tags: *id003
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id004
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id005
  url: /providers/amazon-web-services/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: strong
  in_catalog: true
  kin_score: 60.0
  mcp: *id006
  name: Cursor
  slug: cursor
  status: profiled
  tags: *id007
  url: /providers/cursor/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id008
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id009
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id010
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id011
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id012
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id013
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id014
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id015
  url: /providers/mixpanel/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id016
  name: Segment
  slug: segment
  status: profiled
  tags: *id017
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id018
  name: Slack
  slug: slack
  status: profiled
  tags: *id019
  url: /providers/slack/
siblings:
- name: Atlassian Statuspage
  rows: 14
  url: /applications/incident-status-pages/atlassian-statuspage/
- name: Cachet
  rows: 2
  url: /applications/incident-status-pages/cachet/
- name: Dispatch (Netflix)
  rows: 16
  url: /applications/incident-status-pages/dispatch-netflix/
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
sitemap: true
title: 'PagerDuty: Incident Management & Status Pages reference app'
---
