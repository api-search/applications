---
app: Atlassian Statuspage
app_slug: atlassian-statuspage
app_url: https://www.atlassian.com/software/statuspage
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
  - VictorOps
  - xMatters
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Datadog
  - Librato
  - New Relic
  - Pingdom
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Twitter
  url: /capabilities/social-networks-community/
  via_parent: null
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
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: common
  name: IT Service Management
  providers:
  - Jira Service Management
  url: /capabilities/it-service-management/
  via_parent: null
category:
  id: incident-status-pages
  name: Incident Management & Status Pages
  url: /applications/incident-status-pages/
counts:
  declared: 14
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.atlassian.com/software/statuspage/integrations
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
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
  layer: domain
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
    mcp: &id003
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id005
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id006
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira Service Management
  provider: jira
  says: lists Jira Service Management as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id007
      status: none
    slug: librato
    status: profiled
    tags: &id008
    - Company
    - Developer Tools
    - Metrics
    - Monitoring
    url: /providers/librato/
  layer: domain
  name: Librato
  provider: librato
  says: lists Librato as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id011
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id012
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: domain
  name: New Relic
  provider: new-relic
  says: lists New Relic as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
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
    mcp: &id013
      status: none
    slug: opsgenie
    status: profiled
    tags: &id014
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: lists Opsgenie as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
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
    mcp: &id015
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id016
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: lists PagerDuty as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 17.7
    mcp: &id017
      status: unknown
    slug: pingdom
    status: profiled
    tags: &id018
    - Monitoring
    - Performance Monitoring
    - Uptime Monitoring
    - Website Monitoring
    url: /providers/pingdom/
  layer: domain
  name: Pingdom
  provider: pingdom
  says: lists Pingdom as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
    mcp: &id019
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id020
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id021
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id022
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter
  provider: x
  says: lists Twitter as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id023
      status: none
    slug: victorops
    status: profiled
    tags: &id024
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: domain
  name: VictorOps
  provider: victorops
  says: lists VictorOps as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
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
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id025
      status: none
    slug: xmatters
    status: profiled
    tags: &id026
    - Alerting
    - Incident Management
    - On-Call
    - Service Reliability
    url: /providers/xmatters/
  layer: domain
  name: xMatters
  provider: xmatters
  says: lists xMatters as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
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
    mcp: &id027
      status: none
    slug: zendesk
    status: profiled
    tags: &id028
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.atlassian.com/software/statuspage/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/incident-status-pages/atlassian-statuspage/
providers:
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id001
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id002
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id003
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id004
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id005
  name: Jira Service Management
  slug: jira
  status: profiled
  tags: *id006
  url: /providers/jira/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id007
  name: Librato
  slug: librato
  status: profiled
  tags: *id008
  url: /providers/librato/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id009
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id010
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id011
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id012
  url: /providers/new-relic/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id013
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id014
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id015
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id016
  url: /providers/pagerduty/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 17.7
  mcp: *id017
  name: Pingdom
  slug: pingdom
  status: profiled
  tags: *id018
  url: /providers/pingdom/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id019
  name: Slack
  slug: slack
  status: profiled
  tags: *id020
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id021
  name: Twitter
  slug: x
  status: profiled
  tags: *id022
  url: /providers/x/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id023
  name: VictorOps
  slug: victorops
  status: profiled
  tags: *id024
  url: /providers/victorops/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id025
  name: xMatters
  slug: xmatters
  status: profiled
  tags: *id026
  url: /providers/xmatters/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id027
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id028
  url: /providers/zendesk/
siblings:
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
- name: PagerDuty
  rows: 10
  url: /applications/incident-status-pages/pagerduty/
sitemap: true
title: 'Atlassian Statuspage: Incident Management & Status Pages reference app'
---
