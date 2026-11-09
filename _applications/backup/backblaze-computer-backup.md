---
app: Backblaze Computer Backup
app_slug: backblaze-computer-backup
app_url: https://www.backblaze.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.backblaze.android/latest/
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.backblaze.android&hl=en
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id003
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.backblaze.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.backblaze.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/backblaze-computer-backup/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id002
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id003
  url: /providers/firebase/
siblings:
- name: Arq Backup
  rows: 11
  url: /applications/backup/arq-backup/
- name: Backrest
  rows: 5
  url: /applications/backup/backrest/
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
title: 'Backblaze Computer Backup: Backup & Device Restore reference app'
---
