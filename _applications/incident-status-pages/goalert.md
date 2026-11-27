---
app: GoAlert
app_slug: goalert
app_url: https://github.com/target/goalert
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.50
  key: AE-150.10.50
  layer: domain
  name: Inbound Email Processing
  providers:
  - Mailgun
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Grafana
  - Prometheus Alertmanager
  - Site24x7
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: domain
  name: Programmable Voice
  providers:
  - Twilio
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: incident-status-pages
  name: Incident Management & Status Pages
  url: /applications/incident-status-pages/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/target/goalert/blob/master/go.mod
- route: source code
  url: https://github.com/target/goalert
- route: source code
  url: https://github.com/target/goalert/tree/master/notification
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id002
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id003
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/target/goalert/blob/master/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.6
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id004
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id005
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: domain
  name: Grafana
  provider: grafana-com
  says: ships the Grafana SDK or integration code
  source: https://github.com/target/goalert
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.50
    key: AE-150.10.50
    name: Inbound Email Processing
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id006
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id007
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: domain
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/target/goalert
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id008
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id009
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: domain
  name: Prometheus Alertmanager
  provider: prometheus-io
  says: ships the Prometheus Alertmanager SDK or integration code
  source: https://github.com/target/goalert
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id010
      source: https://www.site24x7.com/help/aiops/mcp-server.html
      status: documented
    slug: site24x7
    status: profiled
    tags: &id011
    - Infrastructure
    - Monitoring
    - Observability
    - Uptime
    url: /providers/site24x7/
  layer: domain
  name: Site24x7
  provider: site24x7
  says: ships the Site24x7 SDK or integration code
  source: https://github.com/target/goalert
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
    mcp: &id012
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id013
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/target/goalert/blob/master/go.mod
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id014
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id015
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/target/goalert/tree/master/notification
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts: *id001
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/target/goalert/tree/master/notification
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/incident-status-pages/goalert/
providers:
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id002
  name: GitHub
  slug: github
  status: profiled
  tags: *id003
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id004
  name: Grafana
  slug: grafana-com
  status: profiled
  tags: *id005
  url: /providers/grafana-com/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id006
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id007
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id008
  name: Prometheus Alertmanager
  slug: prometheus-io
  status: profiled
  tags: *id009
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id010
  name: Site24x7
  slug: site24x7
  status: profiled
  tags: *id011
  url: /providers/site24x7/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id012
  name: Slack
  slug: slack
  status: profiled
  tags: *id013
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id014
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id015
  url: /providers/twilio/
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
title: 'GoAlert: Incident Management & Status Pages reference app'
---
