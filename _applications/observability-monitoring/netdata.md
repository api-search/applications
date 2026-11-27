---
app: Netdata
app_slug: netdata
app_url: https://github.com/netdata/netdata
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - Alerta
  - ilert
  - Opsgenie
  - PagerDuty
  - SIGNL4
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Discord
  - Flock
  - Microsoft Teams
  - Rocket.Chat
  - Slack
  - Telegram
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Dynatrace
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon SNS
  - Gotify
  - ntfy
  - Prowl
  - Pushbullet
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Kavenegar
  - MessageBird
  - SMSEagle
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: observability-monitoring
  name: Observability, Monitoring & Status Pages
  url: /applications/observability-monitoring/
counts:
  declared: 0
  observed: 22
credits: []
evidence:
- route: source code
  url: https://github.com/netdata/netdata/tree/master/src/health/notifications
integrations:
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id001
      status: none
    slug: alerta
    status: profiled
    tags: &id002
    - Alerting
    - Company
    - Monitoring
    - Open Source
    url: /providers/alerta/
  layer: domain
  name: Alerta
  provider: alerta
  says: ships the Alerta SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id005
      status: none
    slug: discord
    status: profiled
    tags: &id006
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_band: agent-ready
    agent_readiness: 43.8
    band: exemplar
    in_catalog: true
    kin_score: 85.6
    mcp: &id007
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id008
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
  layer: domain
  name: Dynatrace
  provider: dynatrace
  says: ships the Dynatrace SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    kin_score: 3.4
    mcp: &id009
      status: none
    slug: flock
    status: profiled
    tags: &id010
    - Commercial Motor
    - Company
    - Insurance
    - Insurtech
    url: /providers/flock/
  layer: domain
  name: Flock
  provider: flock
  says: ships the Flock SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id011
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id012
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id013
      source: https://github.com/iLert/mcp-ilert
      status: verified
    slug: ilert
    status: profiled
    tags: &id014
    - Alert Routing
    - Escalation Policies
    - Incident Management
    - On-Call Alerting
    url: /providers/ilert/
  layer: domain
  name: ilert
  provider: ilert
  says: ships the ilert SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.3
    mcp: &id015
      status: none
    slug: kavenegar
    status: profiled
    tags: &id016
    - Company
    url: /providers/kavenegar/
  layer: common
  name: Kavenegar
  provider: kavenegar
  says: ships the Kavenegar SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 70.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id017
      source: https://github.com/messagebird/bird-ai
      status: verified
    slug: bird
    status: profiled
    tags: &id018
    - Communications
    - Email
    - SMS
    - WhatsApp
    url: /providers/bird/
  layer: common
  name: MessageBird
  provider: bird
  says: ships the MessageBird SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id019
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id020
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id021
      status: none
    slug: ntfy
    status: profiled
    tags: &id022
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    mcp: &id023
      status: none
    slug: opsgenie
    status: profiled
    tags: &id024
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    mcp: &id025
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id026
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id027
      status: unknown
    slug: prowl
    status: profiled
    tags: &id028
    - Company
    - Mobile
    - Push Notifications
    - iOS
    url: /providers/prowl/
  layer: common
  name: Prowl
  provider: prowl
  says: ships the Prowl SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 30.2
    mcp: &id029
      status: none
    slug: pushbullet
    status: profiled
    tags: &id030
    - Device Sync
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushbullet/
  layer: common
  name: Pushbullet
  provider: pushbullet
  says: ships the Pushbullet SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id031
      status: none
    slug: pushover
    status: profiled
    tags: &id032
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    kin_score: 2.9
    mcp: &id033
      source: https://docs.rocket.chat/docs/mcp-server
      status: verified
    slug: rocketchat
    status: profiled
    tags: &id034
    - Collaboration
    - Communications
    - Company
    - Open Source
    url: /providers/rocketchat/
  layer: domain
  name: Rocket.Chat
  provider: rocketchat
  says: ships the Rocket.Chat SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 18.1
    band: thin
    in_catalog: true
    kin_score: 36.7
    mcp: &id035
      status: none
    slug: signl4
    status: profiled
    tags: &id036
    - Alerting
    - Incident Management
    - Mobile Alerts
    - On-Call
    url: /providers/signl4/
  layer: domain
  name: SIGNL4
  provider: signl4
  says: ships the SIGNL4 SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id037
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id038
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id039
      status: none
    slug: smseagle
    status: profiled
    tags: &id040
    - Alerting
    - Company
    - IoT
    - SMS
    url: /providers/smseagle/
  layer: common
  name: SMSEagle
  provider: smseagle
  says: ships the SMSEagle SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id041
      status: none
    slug: telegram
    status: profiled
    tags: &id042
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id043
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id044
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/netdata/netdata/tree/master/src/health/notifications
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/observability-monitoring/netdata/
providers:
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id001
  name: Alerta
  slug: alerta
  status: profiled
  tags: *id002
  url: /providers/alerta/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id003
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id004
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id005
  name: Discord
  slug: discord
  status: profiled
  tags: *id006
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 43.8
  band: exemplar
  in_catalog: true
  kin_score: 85.6
  mcp: *id007
  name: Dynatrace
  slug: dynatrace
  status: profiled
  tags: *id008
  url: /providers/dynatrace/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id009
  name: Flock
  slug: flock
  status: profiled
  tags: *id010
  url: /providers/flock/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id011
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id012
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id013
  name: ilert
  slug: ilert
  status: profiled
  tags: *id014
  url: /providers/ilert/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.3
  mcp: *id015
  name: Kavenegar
  slug: kavenegar
  status: profiled
  tags: *id016
  url: /providers/kavenegar/
- agent_band: agent-native
  agent_readiness: 70.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id017
  name: MessageBird
  slug: bird
  status: profiled
  tags: *id018
  url: /providers/bird/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id019
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id020
  url: /providers/microsoft-teams/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id021
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id022
  url: /providers/ntfy/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id023
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id024
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id025
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id026
  url: /providers/pagerduty/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id027
  name: Prowl
  slug: prowl
  status: profiled
  tags: *id028
  url: /providers/prowl/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 30.2
  mcp: *id029
  name: Pushbullet
  slug: pushbullet
  status: profiled
  tags: *id030
  url: /providers/pushbullet/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id031
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id032
  url: /providers/pushover/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id033
  name: Rocket.Chat
  slug: rocketchat
  status: profiled
  tags: *id034
  url: /providers/rocketchat/
- agent_band: agent-aware
  agent_readiness: 18.1
  band: thin
  in_catalog: true
  kin_score: 36.7
  mcp: *id035
  name: SIGNL4
  slug: signl4
  status: profiled
  tags: *id036
  url: /providers/signl4/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id037
  name: Slack
  slug: slack
  status: profiled
  tags: *id038
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 3.8
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id039
  name: SMSEagle
  slug: smseagle
  status: profiled
  tags: *id040
  url: /providers/smseagle/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id041
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id042
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id043
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id044
  url: /providers/twilio/
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
- name: Prometheus Alertmanager
  rows: 15
  url: /applications/observability-monitoring/prometheus-alertmanager/
- name: Sentry
  rows: 31
  url: /applications/observability-monitoring/sentry/
- name: Uptime Kuma
  rows: 50
  url: /applications/observability-monitoring/uptime-kuma/
sitemap: true
title: 'Netdata: Observability, Monitoring & Status Pages reference app'
---
