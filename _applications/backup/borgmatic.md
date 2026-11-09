---
app: borgmatic
app_slug: borgmatic
app_url: https://github.com/borgmatic-collective/borgmatic
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.40.20
  key: BC-600.40.20
  layer: common
  name: IT Job Scheduling and Batch Operations
  providers:
  - Cronitor
  - Healthchecks.io
  - Uptime Kuma
  - Zabbix
  url: /capabilities/it-operations-management/
  via_parent: IT Operations Management
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Grafana Loki
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - ntfy
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: source code
  url: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/data_source
- route: source code
  url: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id001
      status: none
    slug: cronitor
    status: profiled
    tags: &id002
    - Alerting
    - Cron Jobs
    - Monitoring
    - Scheduled Tasks
    url: /providers/cronitor/
  layer: common
  name: Cronitor
  provider: cronitor
  says: ships the Cronitor SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
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
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 60.6
    mcp: &id003
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id004
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: common
  name: Grafana Loki
  provider: grafana-com
  says: ships the Grafana Loki SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id005
      status: none
    slug: healthchecks-io
    status: profiled
    tags: &id006
    - Cron
    - DevOps
    - Monitoring
    - Open Source
    url: /providers/healthchecks-io/
  layer: common
  name: Healthchecks.io
  provider: healthchecks-io
  says: ships the Healthchecks.io SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
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
    kin_score: 9.9
    mcp: &id007
      status: none
    slug: ntfy
    status: profiled
    tags: &id008
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
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
    mcp: &id009
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id010
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: common
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
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
    mcp: &id011
      status: none
    slug: pushover
    status: profiled
    tags: &id012
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id015
      status: none
    slug: uptime-kuma
    status: profiled
    tags: &id016
    - Dashboards
    - Monitoring
    - Open Source
    - Self-Hosted
    url: /providers/uptime-kuma/
  layer: common
  name: Uptime Kuma
  provider: uptime-kuma
  says: ships the Uptime Kuma SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.1
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id017
      status: none
    slug: zabbix
    status: profiled
    tags: &id018
    - Alerting
    - Infrastructure
    - Monitoring
    - Networks
    url: /providers/zabbix/
  layer: common
  name: Zabbix
  provider: zabbix
  says: ships the Zabbix SDK or integration code
  source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/borgmatic/
providers:
- agent_band: agent-ready
  agent_readiness: 40.7
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id001
  name: Cronitor
  slug: cronitor
  status: profiled
  tags: *id002
  url: /providers/cronitor/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 60.6
  mcp: *id003
  name: Grafana Loki
  slug: grafana-com
  status: profiled
  tags: *id004
  url: /providers/grafana-com/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id005
  name: Healthchecks.io
  slug: healthchecks-io
  status: profiled
  tags: *id006
  url: /providers/healthchecks-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id007
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id008
  url: /providers/ntfy/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id009
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id010
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id011
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id012
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id015
  name: Uptime Kuma
  slug: uptime-kuma
  status: profiled
  tags: *id016
  url: /providers/uptime-kuma/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id017
  name: Zabbix
  slug: zabbix
  status: profiled
  tags: *id018
  url: /providers/zabbix/
siblings:
- name: Arq Backup
  rows: 11
  url: /applications/backup/arq-backup/
- name: Backblaze Computer Backup
  rows: 2
  url: /applications/backup/backblaze-computer-backup/
- name: Backrest
  rows: 5
  url: /applications/backup/backrest/
- name: Duplicati
  rows: 31
  url: /applications/backup/duplicati/
- name: IDrive
  rows: 8
  url: /applications/backup/idrive/
- name: Kopia
  rows: 6
  url: /applications/backup/kopia/
- name: Restic
  rows: 5
  url: /applications/backup/restic/
- name: Velero
  rows: 20
  url: /applications/backup/velero/
sitemap: true
title: 'borgmatic: Backup & Device Restore reference app'
---
