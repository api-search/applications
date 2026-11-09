---
app: Prometheus Alertmanager
app_slug: prometheus-alertmanager
app_url: https://github.com/prometheus/alertmanager
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - incident.io
  - Opsgenie
  - PagerDuty
  - VictorOps
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Discord
  - Mattermost
  - Microsoft Teams
  - Rocket.Chat
  - Slack
  - Telegram
  - Webex
  - WeChat (Work)
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon SNS
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - Jira
  url: /capabilities/software-product-engineering-management/
  via_parent: null
category:
  id: observability-monitoring
  name: Observability, Monitoring & Status Pages
  url: /applications/observability-monitoring/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: source code
  url: https://github.com/prometheus/alertmanager/tree/main/notify
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id003
      status: none
    slug: discord
    status: profiled
    tags: &id004
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
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
    agent_band: agent-native
    agent_readiness: 50.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id005
      source: https://help.incident.io/
      status: documented
    slug: incident-io
    status: profiled
    tags: &id006
    - AIOps
    - Incident Management
    - Incident Response
    - Monitoring
    url: /providers/incident-io/
  layer: domain
  name: incident.io
  provider: incident-io
  says: ships the incident.io SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
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
    mcp: &id007
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id008
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id009
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id010
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: domain
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
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
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
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
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 48.9
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
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
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
    agent_readiness: 48.9
    band: developing
    in_catalog: true
    kin_score: 51.2
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
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id017
      status: none
    slug: pushover
    status: profiled
    tags: &id018
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id019
      source: https://docs.rocket.chat/docs/mcp-server
      status: verified
    slug: rocketchat
    status: profiled
    tags: &id020
    - Collaboration
    - Communications
    - Company
    - Open Source
    url: /providers/rocketchat/
  layer: domain
  name: Rocket.Chat
  provider: rocketchat
  says: ships the Rocket.Chat SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
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
    mcp: &id021
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id022
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id023
      status: none
    slug: telegram
    status: profiled
    tags: &id024
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.8
    mcp: &id025
      status: none
    slug: victorops
    status: profiled
    tags: &id026
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: domain
  name: VictorOps
  provider: victorops
  says: ships the VictorOps SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
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
    agent_readiness: 61.1
    band: strong
    in_catalog: true
    kin_score: 64.2
    mcp: &id027
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id028
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id029
      status: none
    slug: wechat
    status: profiled
    tags: &id030
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeChat (Work)
  provider: wechat
  says: ships the WeChat (Work) SDK or integration code
  source: https://github.com/prometheus/alertmanager/tree/main/notify
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/observability-monitoring/prometheus-alertmanager/
providers:
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id001
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id002
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id003
  name: Discord
  slug: discord
  status: profiled
  tags: *id004
  url: /providers/discord/
- agent_band: agent-native
  agent_readiness: 50.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id005
  name: incident.io
  slug: incident-io
  status: profiled
  tags: *id006
  url: /providers/incident-io/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id007
  name: Jira
  slug: jira
  status: profiled
  tags: *id008
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id009
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id010
  url: /providers/mattermost/
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
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id013
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id014
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id015
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id016
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id017
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id018
  url: /providers/pushover/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id019
  name: Rocket.Chat
  slug: rocketchat
  status: profiled
  tags: *id020
  url: /providers/rocketchat/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id021
  name: Slack
  slug: slack
  status: profiled
  tags: *id022
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id023
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id024
  url: /providers/telegram/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id025
  name: VictorOps
  slug: victorops
  status: profiled
  tags: *id026
  url: /providers/victorops/
- agent_band: agent-ready
  agent_readiness: 61.1
  band: strong
  in_catalog: true
  kin_score: 64.2
  mcp: *id027
  name: Webex
  slug: webex
  status: profiled
  tags: *id028
  url: /providers/webex/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id029
  name: WeChat (Work)
  slug: wechat
  status: profiled
  tags: *id030
  url: /providers/wechat/
siblings:
- name: Datadog
  rows: 21
  url: /applications/observability-monitoring/datadog/
- name: Gatus
  rows: 38
  url: /applications/observability-monitoring/gatus/
- name: Grafana
  rows: 30
  url: /applications/observability-monitoring/grafana/
- name: Netdata
  rows: 22
  url: /applications/observability-monitoring/netdata/
- name: Sentry
  rows: 31
  url: /applications/observability-monitoring/sentry/
- name: Uptime Kuma
  rows: 50
  url: /applications/observability-monitoring/uptime-kuma/
sitemap: true
title: 'Prometheus Alertmanager: Observability, Monitoring & Status Pages reference app'
---
