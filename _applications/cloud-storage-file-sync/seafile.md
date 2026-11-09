---
app: Seafile
app_slug: seafile
app_url: https://github.com/haiwen/seafile
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  - Ceph
  - Exoscale
  - Hetzner
  - MinIO
  - OpenStack Swift
  - Wasabi
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics)
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 7
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.seafile.seadroid2/latest/
- route: documentation
  url: https://manual.seafile.com/latest/setup/setup_with_s3/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id008
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seafile.seadroid2/latest/
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
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  says: lists Amazon S3 as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
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
    agent_readiness: 18.4
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id003
      status: none
    slug: ceph
    status: profiled
    tags: &id004
    - Block Storage
    - Distributed Storage
    - Object Storage
    - Storage
    url: /providers/ceph/
  layer: domain
  name: Ceph
  provider: ceph
  says: lists Ceph as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
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
    agent_readiness: 26.0
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id005
      status: none
    slug: exoscale
    status: profiled
    tags: &id006
    - Cloud
    - Compute
    - Infrastructure
    - Storage
    url: /providers/exoscale/
  layer: domain
  name: Exoscale
  provider: exoscale
  says: lists Exoscale as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
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
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 39.7
    mcp: &id009
      status: none
    slug: hetzner
    status: profiled
    tags: &id010
    - Cloud Hosting
    - DNS
    - Infrastructure
    - Servers
    url: /providers/hetzner/
  layer: domain
  name: Hetzner
  provider: hetzner
  says: lists Hetzner as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
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
    agent_readiness: 26.1
    band: strong
    in_catalog: true
    kin_score: 57.3
    mcp: &id011
      source: https://github.com/minio/mcp-server-aistor
      status: verified
    slug: minio
    status: profiled
    tags: &id012
    - Cloud-Native
    - Object Storage
    - S3 Compatible
    - Storage
    url: /providers/minio/
  layer: domain
  name: MinIO
  provider: minio
  says: lists MinIO as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.1
    mcp: &id013
      status: none
    slug: openstack
    status: profiled
    tags: &id014
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
  layer: domain
  name: OpenStack Swift
  provider: openstack
  says: lists OpenStack Swift as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id015
      status: none
    slug: wasabi
    status: profiled
    tags: &id016
    - Cloud Storage
    - Object Storage
    - REST API
    - S3 Compatible
    url: /providers/wasabi/
  layer: domain
  name: Wasabi
  provider: wasabi
  says: lists Wasabi as an integration
  source: https://manual.seafile.com/latest/setup/setup_with_s3/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/seafile/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 18.4
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id003
  name: Ceph
  slug: ceph
  status: profiled
  tags: *id004
  url: /providers/ceph/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id005
  name: Exoscale
  slug: exoscale
  status: profiled
  tags: *id006
  url: /providers/exoscale/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id007
  name: Firebase (Crashlytics)
  slug: firebase
  status: profiled
  tags: *id008
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id009
  name: Hetzner
  slug: hetzner
  status: profiled
  tags: *id010
  url: /providers/hetzner/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: strong
  in_catalog: true
  kin_score: 57.3
  mcp: *id011
  name: MinIO
  slug: minio
  status: profiled
  tags: *id012
  url: /providers/minio/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id013
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id014
  url: /providers/openstack/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id015
  name: Wasabi
  slug: wasabi
  status: profiled
  tags: *id016
  url: /providers/wasabi/
siblings:
- name: Box
  rows: 18
  url: /applications/cloud-storage-file-sync/box/
- name: Dropbox
  rows: 18
  url: /applications/cloud-storage-file-sync/dropbox/
- name: Filestash
  rows: 8
  url: /applications/cloud-storage-file-sync/filestash/
- name: Nextcloud
  rows: 32
  url: /applications/cloud-storage-file-sync/nextcloud/
- name: ownCloud Infinite Scale
  rows: 3
  url: /applications/cloud-storage-file-sync/owncloud-infinite-scale/
- name: rclone
  rows: 71
  url: /applications/cloud-storage-file-sync/rclone/
- name: Syncthing
  rows: 2
  url: /applications/cloud-storage-file-sync/syncthing/
sitemap: true
title: 'Seafile: Cloud Storage & File Sync reference app'
---
