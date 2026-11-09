---
app: Arq Backup
app_slug: arq-backup
app_url: https://www.arqbackup.com/
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
  - OneDrive
  - pCloud
  - SharePoint
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - AWS S3 and Glacier
  - Backblaze B2
  - Google Cloud Storage
  - MinIO
  - Storj
  - Wasabi
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
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
  name: AWS S3 and Glacier
  provider: amazon-s3
  says: lists AWS S3 and Glacier as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
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
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 50.9
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
  says: lists Backblaze B2 as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
  tier: declared
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
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
  says: lists Dropbox as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
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
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
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
  says: lists Google Cloud Storage as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
  tier: declared
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
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
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
  says: lists Google Drive as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
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
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
  tier: declared
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
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id013
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id014
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
  tier: declared
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
    agent_readiness: 7.9
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id015
      source: https://mcp.pcloud.com/.well-known/oauth-protected-resource/mcp
      status: verified
    slug: pcloud
    status: profiled
    tags: &id016
    - Backup
    - Cloud Storage
    - File Sync
    - Security
    url: /providers/pcloud/
  layer: domain
  name: pCloud
  provider: pcloud
  says: lists pCloud as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
  tier: declared
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
    agent_readiness: 35.2
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id017
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id018
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: domain
  name: SharePoint
  provider: sharepoint
  says: lists SharePoint as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id019
      status: none
    slug: storj
    status: profiled
    tags: &id020
    - Cloud Storage
    - Object Storage
    - Public APIs
    - Storage
    url: /providers/storj/
  layer: domain
  name: Storj
  provider: storj
  says: lists Storj as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
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
    mcp: &id021
      status: none
    slug: wasabi
    status: profiled
    tags: &id022
    - Cloud Storage
    - Object Storage
    - REST API
    - S3 Compatible
    url: /providers/wasabi/
  layer: domain
  name: Wasabi
  provider: wasabi
  says: lists Wasabi as an integration
  source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/arq-backup/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: AWS S3 and Glacier
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id003
  name: Backblaze B2
  slug: backblaze
  status: profiled
  tags: *id004
  url: /providers/backblaze/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id005
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id006
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id007
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id008
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id009
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id010
  url: /providers/google-drive/
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
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id013
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id014
  url: /providers/microsoft-onedrive/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id015
  name: pCloud
  slug: pcloud
  status: profiled
  tags: *id016
  url: /providers/pcloud/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id017
  name: SharePoint
  slug: sharepoint
  status: profiled
  tags: *id018
  url: /providers/sharepoint/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id019
  name: Storj
  slug: storj
  status: profiled
  tags: *id020
  url: /providers/storj/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id021
  name: Wasabi
  slug: wasabi
  status: profiled
  tags: *id022
  url: /providers/wasabi/
siblings:
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
title: 'Arq Backup: Backup & Device Restore reference app'
---
