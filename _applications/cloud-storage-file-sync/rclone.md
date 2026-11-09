---
app: rclone
app_slug: rclone
app_url: https://github.com/rclone/rclone
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
  - Files.com
  - GoFile
  - Google Drive
  - iCloud Drive
  - Internet Archive
  - Internxt
  - Jottacloud
  - Koofr
  - Mail.ru Cloud
  - MEGA
  - OneDrive
  - OpenDrive
  - pCloud
  - Proton Drive
  - put.io
  - Quatrix (Maytech)
  - ShareFile
  - STRATO HiDrive
  - SugarSync
  - Yandex Disk
  - Zoho WorkDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-240.90
  key: AE-240.90
  layer: domain
  name: Decentralized Storage & Compute
  providers:
  - Sia
  - Storj
  url: /capabilities/decentralized-storage-compute/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: domain
  name: Media Asset Management
  providers:
  - Cloudinary
  - ImageKit
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Google Photos
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - 3DS OUTSCALE
  - Akamai NetStorage
  - Alibaba Cloud OSS
  - ArvanCloud
  - AWS S3
  - Azure Blob Storage
  - Backblaze B2
  - Ceph
  - China Mobile EOS
  - Cloudflare R2
  - Cubbit
  - DigitalOcean Spaces
  - DreamHost DreamObjects
  - Fastly Object Storage
  - Google Cloud Storage
  - Hetzner
  - Hitachi Content Platform
  - Huawei OBS
  - IBM COS
  - IDrive e2
  - Impossible Cloud
  - IONOS Cloud
  - Linode (Akamai Cloud)
  - Magalu Cloud
  - MEGA S4
  - MinIO
  - OpenStack Swift
  - Oracle Object Storage
  - OVHcloud
  - Pure Storage FlashBlade
  - QingStor
  - Qiniu Kodo
  - Scaleway
  - Scality
  - Seagate Lyve Cloud
  - Selectel
  - Spectra Logic
  - Synology C2
  - Tencent COS
  - UCloud US3
  - Wasabi
  - Zadara
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 0
  observed: 71
credits: []
evidence:
- route: source code
  url: https://github.com/rclone/rclone/tree/master/backend
- route: source code
  url: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 32.7
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id002
      status: none
    slug: outscale
    status: profiled
    tags: &id003
    - Cloud
    - Compute
    - Infrastructure-as-a-Service
    - Storage
    url: /providers/outscale/
  layer: domain
  name: 3DS OUTSCALE
  provider: outscale
  says: ships the 3DS OUTSCALE SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id004
      status: none
    slug: akamai
    status: profiled
    tags: &id005
    - CDN
    - Cloud
    - Edge Computing
    - Networks
    url: /providers/akamai/
  layer: domain
  name: Akamai NetStorage
  provider: akamai
  says: ships the Akamai NetStorage SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 3.5
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id006
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibaba
    status: profiled
    tags: &id007
    - Cloud
    - Cloud Computing
    - Commerce
    - E-Commerce
    url: /providers/alibaba/
  layer: domain
  name: Alibaba Cloud OSS
  provider: alibaba
  says: ships the Alibaba Cloud OSS SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    kin_score: 4.0
    mcp: &id008
      status: unknown
    slug: arvancloud
    status: profiled
    tags: &id009
    - CDN
    - Cloud
    - Storage
    - Video Streaming
    url: /providers/arvancloud/
  layer: domain
  name: ArvanCloud
  provider: arvancloud
  says: ships the ArvanCloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id010
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id011
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: domain
  name: AWS S3
  provider: amazon-s3
  says: ships the AWS S3 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id012
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id013
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: domain
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id014
      source: https://github.com/backblaze-labs/b2-mcp
      status: verified
    slug: backblaze
    status: profiled
    tags: &id015
    - Backup
    - Cloud Storage
    - Object Storage
    - Storage
    url: /providers/backblaze/
  layer: domain
  name: Backblaze B2
  provider: backblaze
  says: ships the Backblaze B2 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id016
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id017
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: ships the Box SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id018
      status: none
    slug: ceph
    status: profiled
    tags: &id019
    - Block Storage
    - Distributed Storage
    - Object Storage
    - Storage
    url: /providers/ceph/
  layer: domain
  name: Ceph
  provider: ceph
  says: ships the Ceph SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 29.4
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id020
      status: unknown
    slug: china-mobile
    status: profiled
    tags: &id021
    - China
    - Mobile Network Operator
    - Network APIs
    - Telecommunications
    url: /providers/china-mobile/
  layer: domain
  name: China Mobile EOS
  provider: china-mobile
  says: ships the China Mobile EOS SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id022
      source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
      status: verified
    slug: cloudflare-r2
    status: profiled
    tags: &id023
    - Cloud Storage
    - Egress-Free
    - Object Storage
    - S3 Compatible
    url: /providers/cloudflare-r2/
  layer: domain
  name: Cloudflare R2
  provider: cloudflare-r2
  says: ships the Cloudflare R2 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.0
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id024
      source: https://cloudinary.com/documentation/cloudinary_llm_mcp
      status: verified
    slug: cloudinary
    status: profiled
    tags: &id025
    - Asset Management
    - Digital Asset Management
    - Image Processing
    - Image Transformation
    url: /providers/cloudinary/
  layer: domain
  name: Cloudinary
  provider: cloudinary
  says: ships the Cloudinary SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 3.2
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id026
      status: none
    slug: cubbit
    status: profiled
    tags: &id027
    - Cloud Storage
    - Object Storage
    - S3 Compatible
    - Storage
    url: /providers/cubbit/
  layer: domain
  name: Cubbit
  provider: cubbit
  says: ships the Cubbit SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 44.6
    band: developing
    in_catalog: true
    kin_score: 45.0
    mcp: &id028
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id029
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
  layer: domain
  name: DigitalOcean Spaces
  provider: digital-ocean
  says: ships the DigitalOcean Spaces SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id030
      status: none
    slug: dreamhost
    status: profiled
    tags: &id031
    - Cloud
    - Company
    - Domains
    - Hosting
    url: /providers/dreamhost/
  layer: domain
  name: DreamHost DreamObjects
  provider: dreamhost
  says: ships the DreamHost DreamObjects SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id032
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id033
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 24.1
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id034
      source: https://github.com/fastly/mcp
      status: verified
    slug: fastly
    status: profiled
    tags: &id035
    - CDN
    - Edge Cloud
    - Edge Compute
    - WebAssembly
    url: /providers/fastly/
  layer: domain
  name: Fastly Object Storage
  provider: fastly
  says: ships the Fastly Object Storage SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id036
      status: none
    slug: filen
    status: profiled
    tags: &id037
    - Cloud Storage
    - Company
    - Encryption
    - Zero Knowledge
    url: /providers/filen/
  layer: domain
  name: Filen
  provider: filen
  says: ships the Filen SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id038
      status: unchecked
    slug: files-com
    status: queued for profiling
    tags: &id039 []
    url: null
  layer: domain
  name: Files.com
  provider: files-com
  says: ships the Files.com SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.7
    mcp: &id040
      status: none
    slug: gofile
    status: profiled
    tags: &id041
    - File Sharing
    - Public APIs
    url: /providers/gofile/
  layer: domain
  name: GoFile
  provider: gofile
  says: ships the GoFile SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id042
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id043
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: domain
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id044
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id045
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id046
      status: none
    slug: google-photos
    status: profiled
    tags: &id047
    - Albums
    - Google
    - Image
    - Media
    url: /providers/google-photos/
  layer: domain
  name: Google Photos
  provider: google-photos
  says: ships the Google Photos SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 39.7
    mcp: &id048
      status: none
    slug: hetzner
    status: profiled
    tags: &id049
    - Cloud Hosting
    - DNS
    - Infrastructure
    - Servers
    url: /providers/hetzner/
  layer: domain
  name: Hetzner
  provider: hetzner
  says: ships the Hetzner SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 18.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id050
      status: none
    slug: hitachi-vantara
    status: profiled
    tags: &id051
    - AI Services
    - Data Infrastructure
    - Hybrid Cloud
    - Storage
    url: /providers/hitachi-vantara/
  layer: domain
  name: Hitachi Content Platform
  provider: hitachi-vantara
  says: ships the Hitachi Content Platform SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id052
      source: https://github.com/huaweicloud/huaweicloud-mcp
      status: verified
    slug: huaweicloud
    status: profiled
    tags: &id053
    - Cloud
    - Company
    - Infrastructure-as-a-Service
    - Platform-as-a-Service
    url: /providers/huaweicloud/
  layer: domain
  name: Huawei OBS
  provider: huaweicloud
  says: ships the Huawei OBS SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id054
      source: https://github.com/IBM/mcp
      status: verified
    slug: ibm
    status: profiled
    tags: &id055
    - API Management
    - Artificial Intelligence
    - Database
    - IBM
    url: /providers/ibm/
  layer: domain
  name: IBM COS
  provider: ibm
  says: ships the IBM COS SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id056
      status: none
    slug: apple
    status: profiled
    tags: &id057
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: iCloud Drive
  provider: apple
  says: ships the iCloud Drive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id058
      status: none
    slug: idrive
    status: profiled
    tags: &id059
    - Cloud Storage
    - Company
    - Object Storage
    - S3 Compatible
    url: /providers/idrive/
  layer: domain
  name: IDrive e2
  provider: idrive
  says: ships the IDrive e2 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id060
      source: https://registry.npmjs.org/@imagekit/api-mcp
      status: verified
    slug: imagekit
    status: profiled
    tags: &id061
    - CDN
    - Image
    - Media
    - Video
    url: /providers/imagekit/
  layer: domain
  name: ImageKit
  provider: imagekit
  says: ships the ImageKit SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id062
      status: none
    slug: impossible-cloud
    status: profiled
    tags: &id063
    - Cloud
    - Company
    - Object Storage
    - S3
    url: /providers/impossible-cloud/
  layer: domain
  name: Impossible Cloud
  provider: impossible-cloud
  says: ships the Impossible Cloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id064
      status: none
    slug: internet-archive
    status: profiled
    tags: &id065
    - Archival
    - Digital Library
    - Non-Profit
    - Open Access
    url: /providers/internet-archive/
  layer: domain
  name: Internet Archive
  provider: internet-archive
  says: ships the Internet Archive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id066
      status: none
    slug: internxt
    status: profiled
    tags: &id067
    - Cloud Storage
    - Company
    - Encryption
    - Privacy
    url: /providers/internxt/
  layer: domain
  name: Internxt
  provider: internxt
  says: ships the Internxt SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    kin_score: 20.6
    mcp: &id068
      source: https://github.com/ionos-cloud/ionoscloud-mcp
      status: verified
    slug: ionos
    status: profiled
    tags: &id069
    - Cloud
    - Company
    - Domains
    - Hosting
    url: /providers/ionos/
  layer: domain
  name: IONOS Cloud
  provider: ionos
  says: ships the IONOS Cloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id070
      status: none
    slug: jottacloud
    status: profiled
    tags: &id071
    - Backup
    - Cloud Storage
    - Company
    - Norwegian
    url: /providers/jottacloud/
  layer: domain
  name: Jottacloud
  provider: jottacloud
  says: ships the Jottacloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id072
      status: none
    slug: koofr
    status: profiled
    tags: &id073
    - Cloud Storage
    - File Sync
    - GDPR
    - Privacy
    url: /providers/koofr/
  layer: domain
  name: Koofr
  provider: koofr
  says: ships the Koofr SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id074
      source: https://github.com/linode/mcp-cluster-api
      status: verified
    slug: linode
    status: profiled
    tags: &id075
    - Cloud Computing
    - Infrastructure-as-a-Service
    - Kubernetes
    - Virtual Machines
    url: /providers/linode/
  layer: domain
  name: Linode (Akamai Cloud)
  provider: linode
  says: ships the Linode (Akamai Cloud) SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    kin_score: 9.1
    mcp: &id076
      status: none
    slug: magalu-cloud
    status: profiled
    tags: &id077
    - Brazil
    - Cloud
    - Infrastructure
    - Public Cloud
    url: /providers/magalu-cloud/
  layer: domain
  name: Magalu Cloud
  provider: magalu-cloud
  says: ships the Magalu Cloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id078
      status: unknown
    slug: mail-ru
    status: profiled
    tags: &id079
    - Cloud
    - Collaboration
    - Russian
    - Storage
    url: /providers/mail-ru/
  layer: domain
  name: Mail.ru Cloud
  provider: mail-ru
  says: ships the Mail.ru Cloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: &id001
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id080
      source: https://github.com/meganz/mega-mcp
      status: verified
    slug: mega-nz
    status: profiled
    tags: &id081
    - Company
    url: /providers/mega-nz/
  layer: domain
  name: MEGA
  provider: mega-nz
  says: ships the MEGA SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: *id001
  layer: domain
  name: MEGA S4
  provider: mega-nz
  says: ships the MEGA S4 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 26.1
    band: strong
    in_catalog: true
    kin_score: 57.3
    mcp: &id082
      source: https://github.com/minio/mcp-server-aistor
      status: verified
    slug: minio
    status: profiled
    tags: &id083
    - Cloud-Native
    - Object Storage
    - S3 Compatible
    - Storage
    url: /providers/minio/
  layer: domain
  name: MinIO
  provider: minio
  says: ships the MinIO SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id084
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id085
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: OneDrive
  provider: microsoft-onedrive
  says: ships the OneDrive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 5.8
    band: thin
    in_catalog: true
    kin_score: 31.7
    mcp: &id086
      status: unknown
    slug: opendrive
    status: profiled
    tags: &id087
    - Backup
    - Cloud Storage
    - Collaboration
    - File Sync
    url: /providers/opendrive/
  layer: domain
  name: OpenDrive
  provider: opendrive
  says: ships the OpenDrive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id088
      status: none
    slug: openstack
    status: profiled
    tags: &id089
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
  layer: domain
  name: OpenStack Swift
  provider: openstack
  says: ships the OpenStack Swift SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_band: agent-native
    agent_readiness: 52.1
    band: exemplar
    in_catalog: true
    kin_score: 76.9
    mcp: &id090
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle-cloud
    status: profiled
    tags: &id091
    - Cloud Computing
    - Enterprise Cloud
    - Infrastructure-as-a-Service
    - Oracle
    url: /providers/oracle-cloud/
  layer: domain
  name: Oracle Object Storage
  provider: oracle-cloud
  says: ships the Oracle Object Storage SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 41.9
    mcp: &id092
      source: https://mcp.eu.ovhcloud.com/mcp
      status: verified
    slug: ovh-cloud
    status: profiled
    tags: &id093
    - Cloud
    - Compute
    - Hosting
    - Servers
    url: /providers/ovh-cloud/
  layer: domain
  name: OVHcloud
  provider: ovh-cloud
  says: ships the OVHcloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id094
      source: https://mcp.pcloud.com/.well-known/oauth-protected-resource/mcp
      status: verified
    slug: pcloud
    status: profiled
    tags: &id095
    - Backup
    - Cloud Storage
    - File Sync
    - Security
    url: /providers/pcloud/
  layer: domain
  name: pCloud
  provider: pcloud
  says: ships the pCloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 6.3
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id096
      status: none
    slug: proton-me
    status: profiled
    tags: &id097
    - Cloud Storage
    - Company
    - Encryption
    - Privacy
    url: /providers/proton-me/
  layer: domain
  name: Proton Drive
  provider: proton-me
  says: ships the Proton Drive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 23.5
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id098
      source: https://github.com/PureStorage-OpenConnect/flashblade-mcp-server
      status: verified
    slug: pure-storage
    status: profiled
    tags: &id099
    - Data Storage
    - Enterprise Storage
    - Flash Storage
    - Storage
    url: /providers/pure-storage/
  layer: domain
  name: Pure Storage FlashBlade
  provider: pure-storage
  says: ships the Pure Storage FlashBlade SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 21.3
    mcp: &id100
      source: https://github.com/putdotio/putio-mcp-server
      status: verified
    slug: put-io
    status: profiled
    tags: &id101
    - Automation
    - Cloud Storage
    - File Management
    - Media Streaming
    url: /providers/put-io/
  layer: domain
  name: put.io
  provider: put-io
  says: ships the put.io SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id102
      status: unknown
    slug: qingstor
    status: profiled
    tags: &id103
    - Artificial Intelligence
    - Cloud
    - Infrastructure
    - Storage
    url: /providers/qingstor/
  layer: domain
  name: QingStor
  provider: qingstor
  says: ships the QingStor SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 9.7
    band: thin
    in_catalog: true
    kin_score: 37.3
    mcp: &id104
      source: https://github.com/qiniu/qiniu-mcp-server
      status: verified
    slug: qiniu
    status: profiled
    tags: &id105
    - CDN
    - Cloud
    - Company
    - Object Storage
    url: /providers/qiniu/
  layer: domain
  name: Qiniu Kodo
  provider: qiniu
  says: ships the Qiniu Kodo SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    band: emerging
    in_catalog: true
    kin_score: 17.2
    mcp: &id106
      status: none
    slug: quatrix
    status: profiled
    tags: &id107
    - Company
    - Enterprise
    - File Transfer
    - SecureData
    url: /providers/quatrix/
  layer: domain
  name: Quatrix (Maytech)
  provider: quatrix
  says: ships the Quatrix (Maytech) SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    mcp: &id108
      source: https://github.com/scaleway/scaleway-cli
      status: verified
    slug: scaleway
    status: profiled
    tags: &id109
    - Artificial Intelligence
    - Cloud Computing
    - Containers
    - Database
    url: /providers/scaleway/
  layer: domain
  name: Scaleway
  provider: scaleway
  says: ships the Scaleway SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id110
      status: unchecked
    slug: scality
    status: queued for profiling
    tags: &id111 []
    url: null
  layer: domain
  name: Scality
  provider: scality
  says: ships the Scality SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id112
      status: unknown
    slug: seagate
    status: profiled
    tags: &id113
    - Company
    - Data
    - Enterprise
    - Storage
    url: /providers/seagate/
  layer: domain
  name: Seagate Lyve Cloud
  provider: seagate
  says: ships the Seagate Lyve Cloud SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id114
      status: none
    slug: selectel
    status: profiled
    tags: &id115
    - Cloud
    - Infrastructure
    - Storage
    - VPS
    url: /providers/selectel/
  layer: domain
  name: Selectel
  provider: selectel
  says: ships the Selectel SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id116
      status: none
    slug: citrix-sharefile
    status: profiled
    tags: &id117
    - Document Workflow
    - E-Signature
    - File Sharing
    - Secure File Transfer
    url: /providers/citrix-sharefile/
  layer: domain
  name: ShareFile
  provider: citrix-sharefile
  says: ships the ShareFile SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 15.6
    mcp: &id118
      status: none
    slug: sia-tech
    status: profiled
    tags: &id119
    - Blockchain
    - Cloud Storage
    - Company
    - Decentralized Storage
    url: /providers/sia-tech/
  layer: domain
  name: Sia
  provider: sia-tech
  says: ships the Sia SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 14.4
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id120
      status: none
    slug: spectra-logic
    status: profiled
    tags: &id121
    - Backup
    - Company
    - Data Storage
    - Enterprise
    url: /providers/spectra-logic/
  layer: domain
  name: Spectra Logic
  provider: spectra-logic
  says: ships the Spectra Logic SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    kin_score: 6.5
    mcp: &id122
      status: none
    slug: storj
    status: profiled
    tags: &id123
    - Cloud Storage
    - Object Storage
    - Public APIs
    - Storage
    url: /providers/storj/
  layer: domain
  name: Storj
  provider: storj
  says: ships the Storj SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 6.4
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id124
      status: unknown
    slug: hidrive
    status: profiled
    tags: &id125
    - AES-256 Encryption
    - Cloud Storage
    - Data Protection
    - German
    url: /providers/hidrive/
  layer: domain
  name: STRATO HiDrive
  provider: hidrive
  says: ships the STRATO HiDrive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 21.5
    mcp: &id126
      status: unknown
    slug: sugarsync
    status: profiled
    tags: &id127
    - Backup
    - Cloud Storage
    - Collaboration
    - File Sync
    url: /providers/sugarsync/
  layer: domain
  name: SugarSync
  provider: sugarsync
  says: ships the SugarSync SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id128
      status: none
    slug: synology
    status: profiled
    tags: &id129
    - Backup
    - Cloud
    - Company
    - Storage
    url: /providers/synology/
  layer: domain
  name: Synology C2
  provider: synology
  says: ships the Synology C2 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id130
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id131
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
  layer: domain
  name: Tencent COS
  provider: tencentcloud
  says: ships the Tencent COS SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 29.1
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id132
      source: https://github.com/ucloud/udb-mysql-mcp-server
      status: verified
    slug: ucloud
    status: profiled
    tags: &id133
    - Cloud Computing
    - Company
    - Enterprise
    - Infrastructure-as-a-Service
    url: /providers/ucloud/
  layer: domain
  name: UCloud US3
  provider: ucloud
  says: ships the UCloud US3 SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    mcp: &id134
      status: none
    slug: wasabi
    status: profiled
    tags: &id135
    - Cloud Storage
    - Object Storage
    - REST API
    - S3 Compatible
    url: /providers/wasabi/
  layer: domain
  name: Wasabi
  provider: wasabi
  says: ships the Wasabi SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id136
      status: unchecked
    slug: yandex
    status: queued for profiling
    tags: &id137 []
    url: null
  layer: domain
  name: Yandex Disk
  provider: yandex
  says: ships the Yandex Disk SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
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
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id138
      source: https://github.com/zadarastorage/zadara-mcp
      status: verified
    slug: zadara
    status: profiled
    tags: &id139
    - Block Storage
    - Company
    - Object Storage
    - Storage
    url: /providers/zadara/
  layer: domain
  name: Zadara
  provider: zadara
  says: ships the Zadara SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend/s3/provider
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
    agent_readiness: 33.0
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id140
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id141
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: domain
  name: Zoho WorkDrive
  provider: zoho
  says: ships the Zoho WorkDrive SDK or integration code
  source: https://github.com/rclone/rclone/tree/master/backend
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/rclone/
providers:
- agent_band: agent-ready
  agent_readiness: 32.7
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id002
  name: 3DS OUTSCALE
  slug: outscale
  status: profiled
  tags: *id003
  url: /providers/outscale/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id004
  name: Akamai NetStorage
  slug: akamai
  status: profiled
  tags: *id005
  url: /providers/akamai/
- agent_band: human-only
  agent_readiness: 3.5
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id006
  name: Alibaba Cloud OSS
  slug: alibaba
  status: profiled
  tags: *id007
  url: /providers/alibaba/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id008
  name: ArvanCloud
  slug: arvancloud
  status: profiled
  tags: *id009
  url: /providers/arvancloud/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id010
  name: AWS S3
  slug: amazon-s3
  status: profiled
  tags: *id011
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id012
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id013
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id014
  name: Backblaze B2
  slug: backblaze
  status: profiled
  tags: *id015
  url: /providers/backblaze/
- agent_band: agent-ready
  agent_readiness: 57.4
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id016
  name: Box
  slug: box
  status: profiled
  tags: *id017
  url: /providers/box/
- agent_band: agent-aware
  agent_readiness: 18.4
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id018
  name: Ceph
  slug: ceph
  status: profiled
  tags: *id019
  url: /providers/ceph/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id020
  name: China Mobile EOS
  slug: china-mobile
  status: profiled
  tags: *id021
  url: /providers/china-mobile/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id022
  name: Cloudflare R2
  slug: cloudflare-r2
  status: profiled
  tags: *id023
  url: /providers/cloudflare-r2/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id024
  name: Cloudinary
  slug: cloudinary
  status: profiled
  tags: *id025
  url: /providers/cloudinary/
- agent_band: human-only
  agent_readiness: 3.2
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id026
  name: Cubbit
  slug: cubbit
  status: profiled
  tags: *id027
  url: /providers/cubbit/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: developing
  in_catalog: true
  kin_score: 45.0
  mcp: *id028
  name: DigitalOcean Spaces
  slug: digital-ocean
  status: profiled
  tags: *id029
  url: /providers/digital-ocean/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id030
  name: DreamHost DreamObjects
  slug: dreamhost
  status: profiled
  tags: *id031
  url: /providers/dreamhost/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id032
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id033
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id034
  name: Fastly Object Storage
  slug: fastly
  status: profiled
  tags: *id035
  url: /providers/fastly/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id036
  name: Filen
  slug: filen
  status: profiled
  tags: *id037
  url: /providers/filen/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id038
  name: Files.com
  slug: files-com
  status: queued for profiling
  tags: *id039
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.7
  mcp: *id040
  name: GoFile
  slug: gofile
  status: profiled
  tags: *id041
  url: /providers/gofile/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id042
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id043
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id044
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id045
  url: /providers/google-drive/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id046
  name: Google Photos
  slug: google-photos
  status: profiled
  tags: *id047
  url: /providers/google-photos/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id048
  name: Hetzner
  slug: hetzner
  status: profiled
  tags: *id049
  url: /providers/hetzner/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id050
  name: Hitachi Content Platform
  slug: hitachi-vantara
  status: profiled
  tags: *id051
  url: /providers/hitachi-vantara/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id052
  name: Huawei OBS
  slug: huaweicloud
  status: profiled
  tags: *id053
  url: /providers/huaweicloud/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id054
  name: IBM COS
  slug: ibm
  status: profiled
  tags: *id055
  url: /providers/ibm/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id056
  name: iCloud Drive
  slug: apple
  status: profiled
  tags: *id057
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 43.1
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id058
  name: IDrive e2
  slug: idrive
  status: profiled
  tags: *id059
  url: /providers/idrive/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id060
  name: ImageKit
  slug: imagekit
  status: profiled
  tags: *id061
  url: /providers/imagekit/
- agent_band: agent-aware
  agent_readiness: 18.4
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id062
  name: Impossible Cloud
  slug: impossible-cloud
  status: profiled
  tags: *id063
  url: /providers/impossible-cloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id064
  name: Internet Archive
  slug: internet-archive
  status: profiled
  tags: *id065
  url: /providers/internet-archive/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id066
  name: Internxt
  slug: internxt
  status: profiled
  tags: *id067
  url: /providers/internxt/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id068
  name: IONOS Cloud
  slug: ionos
  status: profiled
  tags: *id069
  url: /providers/ionos/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.3
  mcp: *id070
  name: Jottacloud
  slug: jottacloud
  status: profiled
  tags: *id071
  url: /providers/jottacloud/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id072
  name: Koofr
  slug: koofr
  status: profiled
  tags: *id073
  url: /providers/koofr/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id074
  name: Linode (Akamai Cloud)
  slug: linode
  status: profiled
  tags: *id075
  url: /providers/linode/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id076
  name: Magalu Cloud
  slug: magalu-cloud
  status: profiled
  tags: *id077
  url: /providers/magalu-cloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id078
  name: Mail.ru Cloud
  slug: mail-ru
  status: profiled
  tags: *id079
  url: /providers/mail-ru/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id080
  name: MEGA
  slug: mega-nz
  status: profiled
  tags: *id081
  url: /providers/mega-nz/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: strong
  in_catalog: true
  kin_score: 57.3
  mcp: *id082
  name: MinIO
  slug: minio
  status: profiled
  tags: *id083
  url: /providers/minio/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id084
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id085
  url: /providers/microsoft-onedrive/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: thin
  in_catalog: true
  kin_score: 31.7
  mcp: *id086
  name: OpenDrive
  slug: opendrive
  status: profiled
  tags: *id087
  url: /providers/opendrive/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id088
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id089
  url: /providers/openstack/
- agent_band: agent-native
  agent_readiness: 52.1
  band: exemplar
  in_catalog: true
  kin_score: 76.9
  mcp: *id090
  name: Oracle Object Storage
  slug: oracle-cloud
  status: profiled
  tags: *id091
  url: /providers/oracle-cloud/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 41.9
  mcp: *id092
  name: OVHcloud
  slug: ovh-cloud
  status: profiled
  tags: *id093
  url: /providers/ovh-cloud/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id094
  name: pCloud
  slug: pcloud
  status: profiled
  tags: *id095
  url: /providers/pcloud/
- agent_band: agent-aware
  agent_readiness: 6.3
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id096
  name: Proton Drive
  slug: proton-me
  status: profiled
  tags: *id097
  url: /providers/proton-me/
- agent_band: agent-aware
  agent_readiness: 23.5
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id098
  name: Pure Storage FlashBlade
  slug: pure-storage
  status: profiled
  tags: *id099
  url: /providers/pure-storage/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 21.3
  mcp: *id100
  name: put.io
  slug: put-io
  status: profiled
  tags: *id101
  url: /providers/put-io/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id102
  name: QingStor
  slug: qingstor
  status: profiled
  tags: *id103
  url: /providers/qingstor/
- agent_band: agent-aware
  agent_readiness: 9.7
  band: thin
  in_catalog: true
  kin_score: 37.3
  mcp: *id104
  name: Qiniu Kodo
  slug: qiniu
  status: profiled
  tags: *id105
  url: /providers/qiniu/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 17.2
  mcp: *id106
  name: Quatrix (Maytech)
  slug: quatrix
  status: profiled
  tags: *id107
  url: /providers/quatrix/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id108
  name: Scaleway
  slug: scaleway
  status: profiled
  tags: *id109
  url: /providers/scaleway/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id110
  name: Scality
  slug: scality
  status: queued for profiling
  tags: *id111
  url: null
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id112
  name: Seagate Lyve Cloud
  slug: seagate
  status: profiled
  tags: *id113
  url: /providers/seagate/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 21.7
  mcp: *id114
  name: Selectel
  slug: selectel
  status: profiled
  tags: *id115
  url: /providers/selectel/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id116
  name: ShareFile
  slug: citrix-sharefile
  status: profiled
  tags: *id117
  url: /providers/citrix-sharefile/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 15.6
  mcp: *id118
  name: Sia
  slug: sia-tech
  status: profiled
  tags: *id119
  url: /providers/sia-tech/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id120
  name: Spectra Logic
  slug: spectra-logic
  status: profiled
  tags: *id121
  url: /providers/spectra-logic/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id122
  name: Storj
  slug: storj
  status: profiled
  tags: *id123
  url: /providers/storj/
- agent_band: agent-aware
  agent_readiness: 6.4
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id124
  name: STRATO HiDrive
  slug: hidrive
  status: profiled
  tags: *id125
  url: /providers/hidrive/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 21.5
  mcp: *id126
  name: SugarSync
  slug: sugarsync
  status: profiled
  tags: *id127
  url: /providers/sugarsync/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id128
  name: Synology C2
  slug: synology
  status: profiled
  tags: *id129
  url: /providers/synology/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id130
  name: Tencent COS
  slug: tencentcloud
  status: profiled
  tags: *id131
  url: /providers/tencentcloud/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id132
  name: UCloud US3
  slug: ucloud
  status: profiled
  tags: *id133
  url: /providers/ucloud/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id134
  name: Wasabi
  slug: wasabi
  status: profiled
  tags: *id135
  url: /providers/wasabi/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id136
  name: Yandex Disk
  slug: yandex
  status: queued for profiling
  tags: *id137
  url: null
- agent_band: agent-ready
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id138
  name: Zadara
  slug: zadara
  status: profiled
  tags: *id139
  url: /providers/zadara/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id140
  name: Zoho WorkDrive
  slug: zoho
  status: profiled
  tags: *id141
  url: /providers/zoho/
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
- name: Seafile
  rows: 8
  url: /applications/cloud-storage-file-sync/seafile/
- name: Syncthing
  rows: 2
  url: /applications/cloud-storage-file-sync/syncthing/
sitemap: true
title: 'rclone: Cloud Storage & File Sync reference app'
---
