---
app: Grafana OnCall
app_slug: grafana-oncall
app_url: https://github.com/grafana/oncall
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - ElastAlert
  - Kapacitor
  - Prometheus Alertmanager
  - PRTG
  - Zabbix
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: domain
  name: Programmable Voice
  providers:
  - Exotel
  - Twilio
  - Zvonok
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
  - Mattermost
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
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
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: incident-status-pages
  name: Incident Management & Status Pages
  url: /applications/incident-status-pages/
counts:
  declared: 0
  observed: 14
credits: []
evidence:
- route: source code
  url: https://github.com/grafana/oncall/blob/dev/engine/apps/social_auth/backends.py
- route: source code
  url: https://github.com/grafana/oncall/tree/dev/engine/apps
- route: source code
  url: https://github.com/grafana/oncall/tree/dev/engine/apps/integrations/metadata/heartbeat
- route: source code
  url: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id002
      status: unchecked
    slug: elastalert
    status: profiled
    tags: &id003
    - Alerting
    - Elasticsearch
    - Monitoring
    - OpenSearch
    url: /providers/elastalert/
  layer: domain
  name: ElastAlert
  provider: elastalert
  says: ships the ElastAlert SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id004
      source: https://github.com/exotel/ExotelMCP
      status: verified
    slug: exotel
    status: profiled
    tags: &id005
    - Cloud Telephony
    - India
    - SMS
    - Voice
    url: /providers/exotel/
  layer: domain
  name: Exotel
  provider: exotel
  says: ships the Exotel SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
    mcp: &id006
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id007
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
  tier: observed
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
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id008
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id009
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google sign-in
  provider: google
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/grafana/oncall/blob/dev/engine/apps/social_auth/backends.py
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
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id010
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id011
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
  layer: domain
  name: Kapacitor
  provider: influxdata
  says: ships the Kapacitor SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
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
    agent_band: agent-aware
    agent_readiness: 25.2
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id012
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id013
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: domain
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
    mcp: &id014
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id015
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: domain
  name: Prometheus Alertmanager
  provider: prometheus-io
  says: ships the Prometheus Alertmanager SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
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
    agent_readiness: 14.8
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id016
      status: unchecked
    slug: paessler
    status: profiled
    tags: &id017
    - IT
    - Monitoring
    - Networks
    - Software
    url: /providers/paessler/
  layer: domain
  name: PRTG
  provider: paessler
  says: ships the PRTG SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps/integrations/metadata/heartbeat
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
  says: ships the Slack SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id020
      status: none
    slug: telegram
    status: profiled
    tags: &id021
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
    mcp: &id022
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id023
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id024
      status: none
    slug: zabbix
    status: profiled
    tags: &id025
    - Alerting
    - Infrastructure
    - Monitoring
    - Networks
    url: /providers/zabbix/
  layer: domain
  name: Zabbix
  provider: zabbix
  says: ships the Zabbix SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.5
    band: thin
    in_catalog: true
    kin_score: 29.3
    mcp: &id026
      status: unchecked
    slug: zvonok
    status: profiled
    tags: &id027
    - Artificial Intelligence
    - Automation
    - Company
    - Telephony
    url: /providers/zvonok/
  layer: domain
  name: Zvonok
  provider: zvonok
  says: ships the Zvonok SDK or integration code
  source: https://github.com/grafana/oncall/tree/dev/engine/apps
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/incident-status-pages/grafana-oncall/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id002
  name: ElastAlert
  slug: elastalert
  status: profiled
  tags: *id003
  url: /providers/elastalert/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id004
  name: Exotel
  slug: exotel
  status: profiled
  tags: *id005
  url: /providers/exotel/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id006
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id007
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id008
  name: Google sign-in
  slug: google
  status: profiled
  tags: *id009
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id010
  name: Kapacitor
  slug: influxdata
  status: profiled
  tags: *id011
  url: /providers/influxdata/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id012
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id013
  url: /providers/mattermost/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id014
  name: Prometheus Alertmanager
  slug: prometheus-io
  status: profiled
  tags: *id015
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id016
  name: PRTG
  slug: paessler
  status: profiled
  tags: *id017
  url: /providers/paessler/
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
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id020
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id021
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id022
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id023
  url: /providers/twilio/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id024
  name: Zabbix
  slug: zabbix
  status: profiled
  tags: *id025
  url: /providers/zabbix/
- agent_band: agent-aware
  agent_readiness: 24.5
  band: thin
  in_catalog: true
  kin_score: 29.3
  mcp: *id026
  name: Zvonok
  slug: zvonok
  status: profiled
  tags: *id027
  url: /providers/zvonok/
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
- name: incident.io
  rows: 20
  url: /applications/incident-status-pages/incident-io/
- name: PagerDuty
  rows: 10
  url: /applications/incident-status-pages/pagerduty/
sitemap: true
title: 'Grafana OnCall: Incident Management & Status Pages reference app'
---
