---
access: understanding
agent_layer: []
apps:
- anchor: restic
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: source code
    url: https://github.com/restic/restic/tree/master/internal/backend
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/restic/restic/tree/master/internal/backend
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/restic/restic/tree/master/internal/backend
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Backblaze B2
    provider: backblaze
    says: ships the Backblaze B2 SDK or integration code
    source: https://github.com/restic/restic/tree/master/internal/backend
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/restic/restic/tree/master/internal/backend
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: OpenStack Swift
    provider: openstack
    says: ships the OpenStack Swift SDK or integration code
    source: https://github.com/restic/restic/tree/master/internal/backend
    tier: observed
  kind: self-hosted
  name: Restic
  page: /applications/backup/restic/
  slug: restic
  url: https://github.com/restic/restic
- anchor: kopia
  counts:
    declared: 0
    observed: 6
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
    layer: common
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/kopia/kopia/tree/master/notification/sender
    tier: observed
  kind: self-hosted
  name: Kopia
  page: /applications/backup/kopia/
  slug: kopia
  url: https://github.com/kopia/kopia
- anchor: duplicati
  counts:
    declared: 0
    observed: 31
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
    layer: domain
    name: Wasabi
    provider: wasabi
    says: ships the Wasabi SDK or integration code
    source: https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
    tier: observed
  kind: self-hosted
  name: Duplicati
  page: /applications/backup/duplicati/
  slug: duplicati
  url: https://github.com/duplicati/duplicati
- anchor: borgmatic
  counts:
    declared: 0
    observed: 9
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
    layer: common
    name: Zabbix
    provider: zabbix
    says: ships the Zabbix SDK or integration code
    source: https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
    tier: observed
  kind: self-hosted
  name: borgmatic
  page: /applications/backup/borgmatic/
  slug: borgmatic
  url: https://github.com/borgmatic-collective/borgmatic
- anchor: backrest
  counts:
    declared: 0
    observed: 5
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
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
    tier: observed
  kind: self-hosted
  name: Backrest
  page: /applications/backup/backrest/
  slug: backrest
  url: https://github.com/garethgeorge/backrest
- anchor: velero
  counts:
    declared: 20
    observed: 0
  evidence:
  - route: documentation
    url: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Alibaba Cloud OSS
    provider: alibaba
    says: lists Alibaba Cloud OSS as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon EBS
    provider: amazon-ebs
    says: lists Amazon EBS as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: lists Azure Blob Storage as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Azure Managed Disks
    provider: microsoft-azure
    says: lists Azure Managed Disks as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Cloudian HyperStore
    provider: cloudian
    says: lists Cloudian HyperStore as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: DigitalOcean
    provider: digital-ocean
    says: lists DigitalOcean as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Compute Engine disks
    provider: google-cloud-platform
    says: lists Google Compute Engine disks as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: HPE Storage
    provider: hpe
    says: lists HPE Storage as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: HuaweiCloud OBS
    provider: huaweicloud
    says: lists HuaweiCloud OBS as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: IBM Cloud
    provider: ibm
    says: lists IBM Cloud as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MinIO
    provider: minio
    says: lists MinIO as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: OpenEBS
    provider: openebs
    says: lists OpenEBS as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: OpenStack Swift/Cinder
    provider: openstack
    says: lists OpenStack Swift/Cinder as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Oracle Cloud
    provider: oracle-cloud
    says: lists Oracle Cloud as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Portworx
    provider: portworx
    says: lists Portworx as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Storj
    provider: storj
    says: lists Storj as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Tencent Cloud
    provider: tencentcloud
    says: lists Tencent Cloud as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: VMware vSphere
    provider: vmware
    says: lists VMware vSphere as an integration
    source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
    tier: declared
  kind: self-hosted
  name: Velero
  page: /applications/backup/velero/
  slug: velero
  url: https://github.com/vmware-tanzu/velero
- anchor: arq-backup
  counts:
    declared: 11
    observed: 0
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
    layer: domain
    name: Wasabi
    provider: wasabi
    says: lists Wasabi as an integration
    source: https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
    tier: declared
  kind: commercial
  name: Arq Backup
  page: /applications/backup/arq-backup/
  slug: arq-backup
  url: https://www.arqbackup.com/
- anchor: idrive
  counts:
    declared: 6
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
  - route: integrations page
    url: https://www.idrive.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://www.idrive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.idrive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.idrive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.idrive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: lists Microsoft Entra ID as an integration
    source: https://www.idrive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.idrive.com/
    tier: declared
  kind: commercial
  name: IDrive
  page: /applications/backup/idrive/
  slug: idrive
  url: https://www.idrive.com/
- anchor: backblaze-computer-backup
  counts:
    declared: 0
    observed: 2
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
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.backblaze.android/latest/
    tier: observed
  kind: commercial
  name: Backblaze Computer Backup
  page: /applications/backup/backblaze-computer-backup/
  slug: backblaze-computer-backup
  url: https://www.backblaze.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: backup
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Backup
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#backup
name: Backup & Device Restore
needs:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: Every reference app writes encrypted, deduplicated snapshots to an object store or snapshots block volumes; this is the core dependency of the category.
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: Duplicati, Kopia and Arq accept consumer drives (Google Drive, OneDrive, Dropbox, Box, pCloud) as backup targets.
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: Job success/failure pushed to a phone (Pushover, ntfy, Gotify).
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: Job reports sent to a Telegram bot.
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: Job reports posted to a team chat channel (Slack, Discord).
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  fit: exact
  layer: common
  why: Dead-man-switch / heartbeat pings so a missed backup raises an alert (Healthchecks.io, Cronitor, Uptime Kuma, Zabbix).
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: Failed backups open a PagerDuty incident.
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: Backup errors and logs shipped to Sentry or Loki.
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  fit: exact
  layer: domain
  why: Commercial backup suites pull data out of SaaS tenants (Microsoft 365, Google Workspace, Salesforce, Box, Dropbox) to back it up; the BC node is framed from the SaaS vendor side, so the fit is nearest.
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the mobile apps
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Arq Backup
      - Duplicati
      - Kopia
      - Restic
      - Velero
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://github.com/kopia/kopia/tree/master/repo/blob
      - https://github.com/restic/restic/tree/master/internal/backend
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Arq Backup
      - Duplicati
      - Kopia
      - Restic
      - Velero
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://github.com/kopia/kopia/tree/master/repo/blob
      - https://github.com/restic/restic/tree/master/internal/backend
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Duplicati
      - Kopia
      - Restic
      - Velero
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://github.com/kopia/kopia/tree/master/repo/blob
      - https://github.com/restic/restic/tree/master/internal/backend
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - Arq Backup
      - Duplicati
      - Kopia
      - Restic
      band: developing
      in_catalog: true
      kin_score: 49.6
      mcp:
        source: https://github.com/backblaze-labs/b2-mcp
        status: verified
      name: Backblaze B2
      slug: backblaze
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://github.com/kopia/kopia/tree/master/repo/blob
      - https://github.com/restic/restic/tree/master/internal/backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Object Storage
      - Storage
      tier: observed
      url: /providers/backblaze/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Duplicati
      - Restic
      - Velero
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        status: none
      name: OpenStack Swift
      slug: openstack
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://github.com/restic/restic/tree/master/internal/backend
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud Platform
      - Infrastructure-as-a-Service
      - Open Source
      - OpenStack
      tier: observed
      url: /providers/openstack/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Arq Backup
      - Duplicati
      - Velero
      band: minimal
      in_catalog: true
      kin_score: 5.7
      mcp:
        status: none
      name: Storj
      slug: storj
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - Public APIs
      - Storage
      tier: observed
      url: /providers/storj/
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - Duplicati
      - Velero
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        source: https://github.com/IBM/mcp
        status: verified
      name: IBM Cloud Object Storage
      slug: ibm
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - API Management
      - Artificial Intelligence
      - Database
      - IBM
      tier: observed
      url: /providers/ibm/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Duplicati
      - Velero
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        source: https://github.com/TencentCloud/cos-mcp
        status: verified
      name: Tencent COS
      slug: tencentcloud
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Computing
      - Infrastructure
      tier: observed
      url: /providers/tencentcloud/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Arq Backup
      - Duplicati
      band: emerging
      in_catalog: true
      kin_score: 23.4
      mcp:
        status: none
      name: Wasabi
      slug: wasabi
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - REST API
      - S3 Compatible
      tier: observed
      url: /providers/wasabi/
    - agent_band: human-only
      agent_readiness: 3.4
      apps:
      - Duplicati
      - Velero
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud OSS
      slug: alibaba
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Commerce
      - E-Commerce
      tier: observed
      url: /providers/alibaba/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Arq Backup
      - Velero
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        source: https://github.com/minio/mcp-server-aistor
        status: verified
      name: MinIO
      slug: minio
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Cloud-Native
      - Object Storage
      - S3 Compatible
      - Storage
      tier: declared
      url: /providers/minio/
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Duplicati
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: Sakura Cloud object storage
      slug: sakura-internet
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud Computing
      - Company
      - Hosting
      - Infrastructure-as-a-Service
      tier: observed
      url: /providers/sakura-internet/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Duplicati
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        status: none
      name: Impossible Cloud
      slug: impossible-cloud
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud
      - Company
      - Object Storage
      - S3
      tier: observed
      url: /providers/impossible-cloud/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - Duplicati
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/scaleway/scaleway-cli
        status: verified
      name: Scaleway
      slug: scaleway
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud Computing
      - Containers
      - Database
      tier: observed
      url: /providers/scaleway/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Duplicati
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        status: none
      name: IDrive e2
      slug: idrive
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/idrive/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Duplicati
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/cloudflare-r2/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duplicati
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: none
      name: DreamHost DreamObjects
      slug: dreamhost
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud
      - Company
      - Domains
      - Hosting
      tier: observed
      url: /providers/dreamhost/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Duplicati
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: none
      name: Selectel
      slug: selectel
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud
      - Infrastructure
      - Storage
      - VPS
      tier: observed
      url: /providers/selectel/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Duplicati
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: unknown
      name: Storadera
      slug: storadera
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Backup
      - Cloud
      - S3
      - Storage
      tier: observed
      url: /providers/storadera/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duplicati
      band: emerging
      in_catalog: true
      kin_score: 19.4
      mcp:
        status: none
      name: Internxt
      slug: internxt
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Encryption
      - Privacy
      tier: observed
      url: /providers/internxt/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Duplicati
      band: emerging
      in_catalog: true
      kin_score: 19.4
      mcp:
        status: unknown
      name: Seagate Lyve Cloud
      slug: seagate
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Company
      - Data
      - Enterprise
      - Storage
      tier: observed
      url: /providers/seagate/
    - agent_band: agent-aware
      agent_readiness: 13.4
      apps:
      - Duplicati
      band: emerging
      in_catalog: true
      kin_score: 16.0
      mcp:
        source: https://github.com/Infomaniak/mcp-server-kdrive
        status: verified
      name: Infomaniak Swiss Backup
      slug: infomaniak
      sources:
      - https://raw.githubusercontent.com/duplicati/duplicati/master/Duplicati/Library/Backend/S3/S3Backend.cs
      status: profiled
      tags:
      - Cloud
      - Company
      - Email
      - Hosting
      tier: observed
      url: /providers/infomaniak/
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Velero
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Managed Disks
      slug: microsoft-azure
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-azure/
    - agent_band: agent-native
      agent_readiness: 53.7
      apps:
      - Velero
      band: exemplar
      in_catalog: true
      kin_score: 75.6
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Cloud
      slug: oracle-cloud
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Cloud
      - Infrastructure-as-a-Service
      - Oracle
      tier: declared
      url: /providers/oracle-cloud/
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Velero
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        status: none
      name: Amazon EBS
      slug: amazon-ebs
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Amazon Web Services
      - Block Storage
      - EBS
      - EC2
      tier: declared
      url: /providers/amazon-ebs/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Velero
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Compute Engine disks
      slug: google-cloud-platform
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: declared
      url: /providers/google-cloud-platform/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Velero
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: VMware vSphere
      slug: vmware
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud Computing
      - Container Management
      - Hybrid Cloud
      - Infrastructure
      tier: declared
      url: /providers/vmware/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Velero
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean
      slug: digital-ocean
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: declared
      url: /providers/digital-ocean/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Velero
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        source: https://github.com/HewlettPackard/gl-mcp
        status: verified
      name: HPE Storage
      slug: hpe
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud
      - Compute
      - Edge to Cloud
      - Infrastructure-as-a-Service
      tier: declared
      url: /providers/hpe/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Velero
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: Portworx
      slug: portworx
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud-Native
      - Containers
      - Data Management
      - Kubernetes
      tier: declared
      url: /providers/portworx/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Velero
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: none
      name: OpenEBS
      slug: openebs
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud-Native
      - Containers
      - Kubernetes
      - Open Source
      tier: declared
      url: /providers/openebs/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Velero
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        status: none
      name: Cloudian HyperStore
      slug: cloudian
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Object Storage
      - Storage
      tier: declared
      url: /providers/cloudian/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Velero
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        source: https://github.com/huaweicloud/huaweicloud-mcp
        status: verified
      name: HuaweiCloud OBS
      slug: huaweicloud
      sources:
      - https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
      status: profiled
      tags:
      - Cloud
      - Company
      - Infrastructure-as-a-Service
      - Platform-as-a-Service
      tier: declared
      url: /providers/huaweicloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Arq Backup
      - Duplicati
      - Kopia
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://github.com/kopia/kopia/tree/master/repo/blob
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Arq Backup
      - Duplicati
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: SharePoint
      slug: sharepoint
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: observed
      url: /providers/sharepoint/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Arq Backup
      - Duplicati
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Arq Backup
      - Duplicati
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp: &id003
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags: &id004
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - Arq Backup
      - Duplicati
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        source: https://mcp.pcloud.com/.well-known/oauth-protected-resource/mcp
        status: verified
      name: pCloud
      slug: pcloud
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      - https://www.arqbackup.com/documentation/arq7/English.lproj/storageLocations.html
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - File Sync
      - Security
      tier: observed
      url: /providers/pcloud/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Duplicati
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp: &id001
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      status: profiled
      tags: &id002
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: observed
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Duplicati
      band: strong
      in_catalog: true
      kin_score: 54.3
      mcp:
        status: none
      name: Filen
      slug: filen
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Encryption
      - Zero Knowledge
      tier: observed
      url: /providers/filen/
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - Duplicati
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Jottacloud
      slug: jottacloud
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Company
      - Norwegian
      tier: observed
      url: /providers/jottacloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duplicati
      band: emerging
      in_catalog: true
      kin_score: 13.0
      mcp:
        source: https://github.com/meganz/mega-mcp
        status: verified
      name: MEGA
      slug: mega-nz
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Backend
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/mega-nz/
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - IDrive
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.idrive.com/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - IDrive
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.idrive.com/
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - IDrive
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.idrive.com/
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - IDrive
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://www.idrive.com/
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - IDrive
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp: *id001
      name: Box
      slug: box
      sources:
      - https://www.idrive.com/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - IDrive
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp: *id003
      name: Dropbox
      slug: dropbox
      sources:
      - https://www.idrive.com/
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/dropbox/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-600.40.20
      key: BC-600.40.20
      name: IT Job Scheduling and Batch Operations
      url: /capabilities/it-operations-management/
      via_parent: IT Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - Backrest
      - borgmatic
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        status: none
      name: Healthchecks.io
      slug: healthchecks-io
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      - https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
      status: profiled
      tags:
      - Cron
      - DevOps
      - Monitoring
      - Open Source
      tier: observed
      url: /providers/healthchecks-io/
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - borgmatic
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: Cronitor
      slug: cronitor
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - Alerting
      - Cron Jobs
      - Monitoring
      - Scheduled Tasks
      tier: observed
      url: /providers/cronitor/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - borgmatic
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Zabbix
      slug: zabbix
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - Alerting
      - Infrastructure
      - Monitoring
      - Networks
      tier: observed
      url: /providers/zabbix/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - borgmatic
      band: emerging
      in_catalog: true
      kin_score: 20.6
      mcp:
        status: none
      name: Uptime Kuma
      slug: uptime-kuma
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - Dashboards
      - Monitoring
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/uptime-kuma/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Backblaze Computer Backup
      - IDrive
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.backblaze.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - borgmatic
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - borgmatic
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana Loki
      slug: grafana-com
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Kopia
      - borgmatic
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      - https://github.com/kopia/kopia/tree/master/notification/sender
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - borgmatic
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Backrest
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        source: https://gotify.net/docs/mcp
        status: verified
      name: Gotify
      slug: gotify
      sources:
      - https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
      status: profiled
      tags:
      - Messaging
      - Notification
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/gotify/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Backrest
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Backrest
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Backblaze Computer Backup
      - IDrive
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.backblaze.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Backrest
      - Duplicati
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/duplicati/duplicati/tree/master/Duplicati/Library/Modules/Builtin
      - https://github.com/garethgeorge/backrest/tree/main/internal/hook/types
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - borgmatic
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://github.com/borgmatic-collective/borgmatic/tree/main/borgmatic/hooks/monitoring
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: observed
      url: /providers/pagerduty/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 18
  distinct_providers: 60
  in_catalog: 60
  mcp:
    documented: 0
    none: 26
    unchecked: 0
    verified: 32
  mcp_verified: 32
  mean_kin_score: 46.5
  observed: 42
  queued: 0
  reference_apps: 9
title: 'Backup & Device Restore: application blueprint'
---
