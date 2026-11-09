---
app: Duplicati
app_slug: duplicati
app_url: https://github.com/duplicati/duplicati
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Filen
  - Google Drive
  - Jottacloud
  - MEGA
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
  - Alibaba Cloud OSS
  - Amazon S3
  - Azure Blob Storage
  - Backblaze B2
  - Cloudflare R2
  - DreamHost DreamObjects
  - Google Cloud Storage
  - IBM Cloud Object Storage
  - IDrive e2
  - Impossible Cloud
  - Infomaniak Swiss Backup
  - Internxt
  - OpenStack Swift
  - Sakura Cloud object storage
  - Scaleway
  - Seagate Lyve Cloud
  - Selectel
  - Storadera
  - Storj
  - Tencent COS
  - Wasabi
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  observed: 31
credits: []
evidence:
- route: source code
  url: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
- route: source code
  url: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Modules/Builtin
- route: source code
  url: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_band: human-only
    agent_readiness: 3.5
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id001
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibaba
    status: profiled
    tags: &id002
    - Cloud
    - Cloud Computing
    - Commerce
    - E-Commerce
    url: /providers/alibaba/
  layer: domain
  name: Alibaba Cloud OSS
  provider: alibaba
  says: ships the Alibaba Cloud OSS SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: domain
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id006
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: domain
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id007
      source: https://github.com/backblaze-labs/b2-mcp
      status: verified
    slug: backblaze
    status: profiled
    tags: &id008
    - Backup
    - Cloud Storage
    - Object Storage
    - Storage
    url: /providers/backblaze/
  layer: domain
  name: Backblaze B2
  provider: backblaze
  says: ships the Backblaze B2 SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 57.4
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id009
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: ships the Box SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 27.7
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id011
      source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
      status: verified
    slug: cloudflare-r2
    status: profiled
    tags: &id012
    - Cloud Storage
    - Egress-Free
    - Object Storage
    - S3 Compatible
    url: /providers/cloudflare-r2/
  layer: domain
  name: Cloudflare R2
  provider: cloudflare-r2
  says: ships the Cloudflare R2 SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id013
      status: none
    slug: dreamhost
    status: profiled
    tags: &id014
    - Cloud
    - Company
    - Domains
    - Hosting
    url: /providers/dreamhost/
  layer: domain
  name: DreamHost DreamObjects
  provider: dreamhost
  says: ships the DreamHost DreamObjects SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id015
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id016
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 33.7
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id017
      status: none
    slug: filen
    status: profiled
    tags: &id018
    - Cloud Storage
    - Company
    - Encryption
    - Zero Knowledge
    url: /providers/filen/
  layer: domain
  name: Filen
  provider: filen
  says: ships the Filen SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id019
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id020
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: domain
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id022
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id023
      source: https://github.com/IBM/mcp
      status: verified
    slug: ibm
    status: profiled
    tags: &id024
    - API Management
    - Artificial Intelligence
    - Database
    - IBM
    url: /providers/ibm/
  layer: domain
  name: IBM Cloud Object Storage
  provider: ibm
  says: ships the IBM Cloud Object Storage SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 43.1
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id025
      status: none
    slug: idrive
    status: profiled
    tags: &id026
    - Cloud Storage
    - Company
    - Object Storage
    - S3 Compatible
    url: /providers/idrive/
  layer: domain
  name: IDrive e2
  provider: idrive
  says: ships the IDrive e2 SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 18.4
    band: strong
    in_catalog: true
    kin_score: 58.0
    mcp: &id027
      status: none
    slug: impossible-cloud
    status: profiled
    tags: &id028
    - Cloud
    - Company
    - Object Storage
    - S3
    url: /providers/impossible-cloud/
  layer: domain
  name: Impossible Cloud
  provider: impossible-cloud
  says: ships the Impossible Cloud SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id029
      source: https://github.com/Infomaniak/mcp-server-kdrive
      status: verified
    slug: infomaniak
    status: profiled
    tags: &id030
    - Cloud
    - Company
    - Email
    - Hosting
    url: /providers/infomaniak/
  layer: domain
  name: Infomaniak Swiss Backup
  provider: infomaniak
  says: ships the Infomaniak Swiss Backup SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id031
      status: none
    slug: internxt
    status: profiled
    tags: &id032
    - Cloud Storage
    - Company
    - Encryption
    - Privacy
    url: /providers/internxt/
  layer: domain
  name: Internxt
  provider: internxt
  says: ships the Internxt SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.3
    mcp: &id033
      status: none
    slug: jottacloud
    status: profiled
    tags: &id034
    - Backup
    - Cloud Storage
    - Company
    - Norwegian
    url: /providers/jottacloud/
  layer: domain
  name: Jottacloud
  provider: jottacloud
  says: ships the Jottacloud SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id035
      source: https://github.com/meganz/mega-mcp
      status: verified
    slug: mega-nz
    status: profiled
    tags: &id036
    - Company
    url: /providers/mega-nz/
  layer: domain
  name: MEGA
  provider: mega-nz
  says: ships the MEGA SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id037
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id038
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: OneDrive
  provider: microsoft-onedrive
  says: ships the OneDrive SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.1
    mcp: &id039
      status: none
    slug: openstack
    status: profiled
    tags: &id040
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
  layer: domain
  name: OpenStack Swift
  provider: openstack
  says: ships the OpenStack Swift SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 7.9
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id041
      source: https://mcp.pcloud.com/.well-known/oauth-protected-resource/mcp
      status: verified
    slug: pcloud
    status: profiled
    tags: &id042
    - Backup
    - Cloud Storage
    - File Sync
    - Security
    url: /providers/pcloud/
  layer: domain
  name: pCloud
  provider: pcloud
  says: ships the pCloud SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 34.7
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id043
      status: none
    slug: sakura-internet
    status: profiled
    tags: &id044
    - Cloud Computing
    - Company
    - Hosting
    - Infrastructure-as-a-Service
    url: /providers/sakura-internet/
  layer: domain
  name: Sakura Cloud object storage
  provider: sakura-internet
  says: ships the Sakura Cloud object storage SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id045
      source: https://github.com/scaleway/scaleway-cli
      status: verified
    slug: scaleway
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Cloud Computing
    - Containers
    - Database
    url: /providers/scaleway/
  layer: domain
  name: Scaleway
  provider: scaleway
  says: ships the Scaleway SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 10.8
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id047
      status: unknown
    slug: seagate
    status: profiled
    tags: &id048
    - Company
    - Data
    - Enterprise
    - Storage
    url: /providers/seagate/
  layer: domain
  name: Seagate Lyve Cloud
  provider: seagate
  says: ships the Seagate Lyve Cloud SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 21.6
    band: emerging
    in_catalog: true
    kin_score: 21.7
    mcp: &id049
      status: none
    slug: selectel
    status: profiled
    tags: &id050
    - Cloud
    - Infrastructure
    - Storage
    - VPS
    url: /providers/selectel/
  layer: domain
  name: Selectel
  provider: selectel
  says: ships the Selectel SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_readiness: 35.2
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id051
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id052
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: domain
  name: SharePoint
  provider: sharepoint
  says: ships the SharePoint SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 8.6
    band: emerging
    in_catalog: true
    kin_score: 14.9
    mcp: &id053
      status: unknown
    slug: storadera
    status: profiled
    tags: &id054
    - Backup
    - Cloud
    - S3
    - Storage
    url: /providers/storadera/
  layer: domain
  name: Storadera
  provider: storadera
  says: ships the Storadera SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id055
      status: none
    slug: storj
    status: profiled
    tags: &id056
    - Cloud Storage
    - Object Storage
    - Public APIs
    - Storage
    url: /providers/storj/
  layer: domain
  name: Storj
  provider: storj
  says: ships the Storj SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id057
      status: none
    slug: telegram
    status: profiled
    tags: &id058
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Modules/Builtin
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
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id059
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
  layer: domain
  name: Tencent COS
  provider: tencentcloud
  says: ships the Tencent COS SDK or integration code
  source: https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
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
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id061
      status: none
    slug: wasabi
    status: profiled
    tags: &id062
    - Cloud Storage
    - Object Storage
    - REST API
    - S3 Compatible
    url: /providers/wasabi/
  layer: domain
  name: Wasabi
  provider: wasabi
  says: ships the Wasabi SDK or integration code
  source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/duplicati/
providers:
- agent_band: human-only
  agent_readiness: 3.5
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id001
  name: Alibaba Cloud OSS
  slug: alibaba
  status: profiled
  tags: *id002
  url: /providers/alibaba/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id005
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id007
  name: Backblaze B2
  slug: backblaze
  status: profiled
  tags: *id008
  url: /providers/backblaze/
- agent_band: agent-ready
  agent_readiness: 57.4
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id009
  name: Box
  slug: box
  status: profiled
  tags: *id010
  url: /providers/box/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id011
  name: Cloudflare R2
  slug: cloudflare-r2
  status: profiled
  tags: *id012
  url: /providers/cloudflare-r2/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id013
  name: DreamHost DreamObjects
  slug: dreamhost
  status: profiled
  tags: *id014
  url: /providers/dreamhost/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id015
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id016
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id017
  name: Filen
  slug: filen
  status: profiled
  tags: *id018
  url: /providers/filen/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id019
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id020
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id021
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id022
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id023
  name: IBM Cloud Object Storage
  slug: ibm
  status: profiled
  tags: *id024
  url: /providers/ibm/
- agent_band: agent-ready
  agent_readiness: 43.1
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id025
  name: IDrive e2
  slug: idrive
  status: profiled
  tags: *id026
  url: /providers/idrive/
- agent_band: agent-aware
  agent_readiness: 18.4
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id027
  name: Impossible Cloud
  slug: impossible-cloud
  status: profiled
  tags: *id028
  url: /providers/impossible-cloud/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id029
  name: Infomaniak Swiss Backup
  slug: infomaniak
  status: profiled
  tags: *id030
  url: /providers/infomaniak/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id031
  name: Internxt
  slug: internxt
  status: profiled
  tags: *id032
  url: /providers/internxt/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.3
  mcp: *id033
  name: Jottacloud
  slug: jottacloud
  status: profiled
  tags: *id034
  url: /providers/jottacloud/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id035
  name: MEGA
  slug: mega-nz
  status: profiled
  tags: *id036
  url: /providers/mega-nz/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id037
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id038
  url: /providers/microsoft-onedrive/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id039
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id040
  url: /providers/openstack/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id041
  name: pCloud
  slug: pcloud
  status: profiled
  tags: *id042
  url: /providers/pcloud/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id043
  name: Sakura Cloud object storage
  slug: sakura-internet
  status: profiled
  tags: *id044
  url: /providers/sakura-internet/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id045
  name: Scaleway
  slug: scaleway
  status: profiled
  tags: *id046
  url: /providers/scaleway/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id047
  name: Seagate Lyve Cloud
  slug: seagate
  status: profiled
  tags: *id048
  url: /providers/seagate/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 21.7
  mcp: *id049
  name: Selectel
  slug: selectel
  status: profiled
  tags: *id050
  url: /providers/selectel/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id051
  name: SharePoint
  slug: sharepoint
  status: profiled
  tags: *id052
  url: /providers/sharepoint/
- agent_band: agent-aware
  agent_readiness: 8.6
  band: emerging
  in_catalog: true
  kin_score: 14.9
  mcp: *id053
  name: Storadera
  slug: storadera
  status: profiled
  tags: *id054
  url: /providers/storadera/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id055
  name: Storj
  slug: storj
  status: profiled
  tags: *id056
  url: /providers/storj/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id057
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id058
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id059
  name: Tencent COS
  slug: tencentcloud
  status: profiled
  tags: *id060
  url: /providers/tencentcloud/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id061
  name: Wasabi
  slug: wasabi
  status: profiled
  tags: *id062
  url: /providers/wasabi/
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
title: 'Duplicati: Backup & Device Restore reference app'
---
