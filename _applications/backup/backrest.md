---
app: Backrest
app_slug: backrest
app_url: https://github.com/garethgeorge/backrest
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.40.20
  key: BC-600.40.20
  layer: common
  name: IT Job Scheduling and Batch Operations
  providers:
  - Healthchecks.io
  url: /capabilities/it-operations-management/
  via_parent: IT Operations Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Gotify
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: source code
  url: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
integrations:
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
    mcp: &id001
      status: none
    slug: discord
    status: profiled
    tags: &id002
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
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
    mcp: &id003
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id004
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
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
    agent_readiness: 17.2
    band: developing
    in_catalog: true
    kin_score: 43.4
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
  source: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
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
    mcp: &id007
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id008
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
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
    mcp: &id009
      status: none
    slug: telegram
    status: profiled
    tags: &id010
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/backrest/
providers:
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id001
  name: Discord
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id003
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id004
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id005
  name: Healthchecks.io
  slug: healthchecks-io
  status: profiled
  tags: *id006
  url: /providers/healthchecks-io/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id007
  name: Slack
  slug: slack
  status: profiled
  tags: *id008
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id009
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id010
  url: /providers/telegram/
siblings:
- name: Arq Backup
  rows: 11
  url: /applications/backup/arq-backup/
- name: Backblaze Computer Backup
  rows: 2
  url: /applications/backup/backblaze-computer-backup/
- name: borgmatic
  rows: 9
  url: /applications/backup/borgmatic/
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
title: 'Backrest: Backup & Device Restore reference app'
---
