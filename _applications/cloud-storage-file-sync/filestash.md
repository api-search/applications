---
app: Filestash
app_slug: filestash
app_url: https://github.com/mickael-kerjean/filestash
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  - Google Drive
  - Syncthing
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-240.90
  key: AE-240.90
  layer: domain
  name: Decentralized Storage & Compute
  providers:
  - Storj
  url: /capabilities/decentralized-storage-compute/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Azure Blob Storage
  - Backblaze B2
  - JFrog Artifactory
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: common
  name: End-User Computing Management
  providers:
  - ONLYOFFICE
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: source code
  url: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
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
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id001
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id002
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: domain
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
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
    mcp: &id003
      source: https://github.com/backblaze-labs/b2-mcp
      status: verified
    slug: backblaze
    status: profiled
    tags: &id004
    - Backup
    - Cloud Storage
    - Object Storage
    - Storage
    url: /providers/backblaze/
  layer: domain
  name: Backblaze B2
  provider: backblaze
  says: ships the Backblaze B2 SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
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
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id005
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
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
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id008
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
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
    agent_readiness: 35.5
    band: strong
    in_catalog: true
    kin_score: 58.9
    mcp: &id009
      source: https://github.com/jfrog/mcp-jfrog
      status: verified
    slug: artifactory
    status: profiled
    tags: &id010
    - Artifacts
    - CI/CD
    - DevOps
    - docker-registry
    url: /providers/artifactory/
  layer: domain
  name: JFrog Artifactory
  provider: artifactory
  says: ships the JFrog Artifactory SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: onlyoffice
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: common
  name: ONLYOFFICE
  provider: onlyoffice
  says: ships the ONLYOFFICE SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.90
    key: AE-240.90
    name: Decentralized Storage & Compute
    url: /capabilities/decentralized-storage-compute/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.7
    mcp: &id013
      status: none
    slug: storj
    status: profiled
    tags: &id014
    - Cloud Storage
    - Object Storage
    - Public APIs
    - Storage
    url: /providers/storj/
  layer: domain
  name: Storj
  provider: storj
  says: ships the Storj SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
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
    agent_band: agent-aware
    agent_readiness: 15.9
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id015
      status: none
    slug: syncthing
    status: profiled
    tags: &id016
    - Cross-Platform
    - Encryption
    - File Synchronization
    - Open Source
    url: /providers/syncthing/
  layer: domain
  name: Syncthing
  provider: syncthing
  says: ships the Syncthing SDK or integration code
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/filestash/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id001
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id002
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 27.4
  band: developing
  in_catalog: true
  kin_score: 49.6
  mcp: *id003
  name: Backblaze B2
  slug: backblaze
  status: profiled
  tags: *id004
  url: /providers/backblaze/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id005
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id006
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id007
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id008
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: strong
  in_catalog: true
  kin_score: 58.9
  mcp: *id009
  name: JFrog Artifactory
  slug: artifactory
  status: profiled
  tags: *id010
  url: /providers/artifactory/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: ONLYOFFICE
  slug: onlyoffice
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id013
  name: Storj
  slug: storj
  status: profiled
  tags: *id014
  url: /providers/storj/
- agent_band: agent-aware
  agent_readiness: 15.9
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id015
  name: Syncthing
  slug: syncthing
  status: profiled
  tags: *id016
  url: /providers/syncthing/
siblings:
- name: Box
  rows: 18
  url: /applications/cloud-storage-file-sync/box/
- name: Dropbox
  rows: 18
  url: /applications/cloud-storage-file-sync/dropbox/
- name: Nextcloud
  rows: 32
  url: /applications/cloud-storage-file-sync/nextcloud/
- name: ownCloud Infinite Scale
  rows: 3
  url: /applications/cloud-storage-file-sync/owncloud-infinite-scale/
- name: rclone
  rows: 71
  url: /applications/cloud-storage-file-sync/rclone/
- name: Seafile
  rows: 8
  url: /applications/cloud-storage-file-sync/seafile/
- name: Syncthing
  rows: 2
  url: /applications/cloud-storage-file-sync/syncthing/
sitemap: true
title: 'Filestash: Cloud Storage & File Sync reference app'
---
