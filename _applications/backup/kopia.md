---
app: Kopia
app_slug: kopia
app_url: https://github.com/kopia/kopia
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Backblaze B2
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: source code
  url: https://github.com/kopia/kopia/tree/master/notification/sender
- route: source code
  url: https://github.com/kopia/kopia/tree/master/repo/blob
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: domain
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/kopia/kopia/tree/master/repo/blob
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id004
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: domain
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/kopia/kopia/tree/master/repo/blob
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.4
    band: developing
    in_catalog: true
    kin_score: 49.6
    mcp: &id005
      source: https://github.com/backblaze-labs/b2-mcp
      status: verified
    slug: backblaze
    status: profiled
    tags: &id006
    - Backup
    - Cloud Storage
    - Object Storage
    - Storage
    url: /providers/backblaze/
  layer: domain
  name: Backblaze B2
  provider: backblaze
  says: ships the Backblaze B2 SDK or integration code
  source: https://github.com/kopia/kopia/tree/master/repo/blob
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id007
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id008
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: domain
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/kopia/kopia/tree/master/repo/blob
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/kopia/kopia/tree/master/repo/blob
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
  source: https://github.com/kopia/kopia/tree/master/notification/sender
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/kopia/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 27.4
  band: developing
  in_catalog: true
  kin_score: 49.6
  mcp: *id005
  name: Backblaze B2
  slug: backblaze
  status: profiled
  tags: *id006
  url: /providers/backblaze/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id007
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id008
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id009
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id010
  url: /providers/google-drive/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id011
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id012
  url: /providers/pushover/
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
- name: borgmatic
  rows: 9
  url: /applications/backup/borgmatic/
- name: Duplicati
  rows: 31
  url: /applications/backup/duplicati/
- name: IDrive
  rows: 8
  url: /applications/backup/idrive/
- name: Restic
  rows: 5
  url: /applications/backup/restic/
- name: Velero
  rows: 20
  url: /applications/backup/velero/
sitemap: true
title: 'Kopia: Backup & Device Restore reference app'
---
