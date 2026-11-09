---
access: understanding
agent_layer:
- app: Filestash
  finding: ships an MCP handler plugin (plg_handler_mcp)
  source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
  tier: observed
- app: Box
  finding: first-party Box MCP server connecting Claude, ChatGPT, Gemini and Microsoft Copilot to Box content
  source: https://www.box.com/integrations
  tier: declared
- app: Nextcloud
  finding: Nextcloud Assistant with bring-your-own LLM providers (integration_openai, integration_replicate, integration_alephalpha)
  source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
  tier: declared
apps:
- anchor: nextcloud
  counts:
    declared: 29
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.nextcloud.client/latest/
  - route: integrations page
    url: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
  - route: source code
    url: https://github.com/nextcloud/server/tree/master/apps/files_external/lib/Lib/Backend
  - route: source code
    url: https://github.com/nextcloud/server/tree/master/lib/private/Files/ObjectStore
  - route: source code
    url: https://raw.githubusercontent.com/nextcloud/server/master/apps/files_external/lib/Lib/Backend/AmazonS3.php
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
    source: https://raw.githubusercontent.com/nextcloud/server/master/apps/files_external/lib/Lib/Backend/AmazonS3.php
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
    source: https://github.com/nextcloud/server/tree/master/lib/private/Files/ObjectStore
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
    source: https://github.com/nextcloud/server/tree/master/apps/files_external/lib/Lib/Backend
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Aleph Alpha
    provider: aleph-alpha
    says: lists Aleph Alpha as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: DeepL
    provider: deepl
    says: lists DeepL as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Discourse
    provider: discourse
    says: lists Discourse as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: common
    name: Documenso
    provider: documenso
    says: lists Documenso as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: common
    name: DocuSign
    provider: docusign
    says: lists DocuSign as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
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
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: common
    name: GIPHY
    provider: giphy
    says: lists GIPHY as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
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
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Grist
    provider: grist
    says: lists Grist as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Mastodon
    provider: mastodon
    says: lists Mastodon as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Mattermost
    provider: mattermost
    says: lists Mattermost as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Miro
    provider: miro
    says: lists Miro as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: common
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
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
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: OpenProject
    provider: openproject
    says: lists OpenProject as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: OpenStreetMap
    provider: openstreetmap
    says: lists OpenStreetMap as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Overleaf
    provider: overleaf
    says: lists Overleaf as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Paperless-ngx
    provider: paperless-ngx
    says: lists Paperless-ngx as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: PeerTube
    provider: peertube
    says: lists PeerTube as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Reddit
    provider: reddit
    says: lists Reddit as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Replicate
    provider: replicate
    says: lists Replicate as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Windmill
    provider: windmill
    says: lists Windmill as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zammad
    provider: zammad
    says: lists Zammad as an integration
    source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
    tier: declared
  kind: self-hosted
  name: Nextcloud
  page: /applications/cloud-storage-file-sync/nextcloud/
  slug: nextcloud
  url: https://github.com/nextcloud/server
- anchor: seafile
  counts:
    declared: 7
    observed: 1
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
    layer: domain
    name: Wasabi
    provider: wasabi
    says: lists Wasabi as an integration
    source: https://manual.seafile.com/latest/setup/setup_with_s3/
    tier: declared
  kind: self-hosted
  name: Seafile
  page: /applications/cloud-storage-file-sync/seafile/
  slug: seafile
  url: https://github.com/haiwen/seafile
- anchor: syncthing
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/syncthing/syncthing/main/go.mod
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: MaxMind
    provider: maxmind
    says: ships the MaxMind SDK or integration code
    source: https://raw.githubusercontent.com/syncthing/syncthing/main/go.mod
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
    source: https://raw.githubusercontent.com/syncthing/syncthing/main/go.mod
    tier: observed
  kind: self-hosted
  name: Syncthing
  page: /applications/cloud-storage-file-sync/syncthing/
  slug: syncthing
  url: https://github.com/syncthing/syncthing
- anchor: owncloud-infinite-scale
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/owncloud/ocis/master/go.mod
  - route: documentation
    url: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Collabora Online
    provider: collabora-online
    says: lists Collabora Online as an integration
    source: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft Office (WOPI)
    provider: microsoft-office
    says: lists Microsoft Office (WOPI) as an integration
    source: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: ONLYOFFICE
    provider: onlyoffice
    says: lists ONLYOFFICE as an integration
    source: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
    tier: declared
  kind: self-hosted
  name: ownCloud Infinite Scale
  page: /applications/cloud-storage-file-sync/owncloud-infinite-scale/
  slug: owncloud-infinite-scale
  url: https://github.com/owncloud/ocis
- anchor: rclone
  counts:
    declared: 0
    observed: 71
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
    layer: domain
    name: Zoho WorkDrive
    provider: zoho
    says: ships the Zoho WorkDrive SDK or integration code
    source: https://github.com/rclone/rclone/tree/master/backend
    tier: observed
  kind: self-hosted
  name: rclone
  page: /applications/cloud-storage-file-sync/rclone/
  slug: rclone
  url: https://github.com/rclone/rclone
- anchor: filestash
  counts:
    declared: 0
    observed: 8
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
    layer: domain
    name: Syncthing
    provider: syncthing
    says: ships the Syncthing SDK or integration code
    source: https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
    tier: observed
  kind: self-hosted
  name: Filestash
  page: /applications/cloud-storage-file-sync/filestash/
  slug: filestash
  url: https://github.com/mickael-kerjean/filestash
- anchor: dropbox
  counts:
    declared: 14
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
  - route: integrations page
    url: https://www.dropbox.com/app-integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adjust
    provider: adjust
    says: ships the Adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Adobe
    provider: adobe
    says: lists Adobe as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic (Claude)
    provider: anthropic
    says: lists Anthropic (Claude) as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1120.50
      key: design-software-cad-management
      name: Design Software & CAD Management
      url: /capabilities/design-software-cad-management/
      via_parent: null
    credit: null
    layer: common
    name: Autodesk
    provider: autodesk
    says: lists Autodesk as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: AWS
    provider: amazon-web-services
    says: lists AWS as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: lists Google Gemini as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft 365 (Copilot)
    provider: microsoft-365
    says: lists Microsoft 365 (Copilot) as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI (ChatGPT)
    provider: openai
    says: lists OpenAI (ChatGPT) as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: common
    name: Reclaim.ai
    provider: reclaim-ai
    says: lists Reclaim.ai as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
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
    says: lists Slack as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: xAI (SpaceXAI)
    provider: xai
    says: lists xAI (SpaceXAI) as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.dropbox.com/app-integrations
    tier: declared
  kind: commercial
  name: Dropbox
  page: /applications/cloud-storage-file-sync/dropbox/
  slug: dropbox
  url: https://www.dropbox.com/
- anchor: box
  counts:
    declared: 14
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
  - route: integrations page
    url: https://www.box.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Split
    provider: split
    says: ships the Split SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Adobe Express
    provider: adobe
    says: lists Adobe Express as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic (Claude)
    provider: anthropic
    says: lists Anthropic (Claude) as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620
      key: cybersecurity-management
      name: Cybersecurity Management
      url: /capabilities/cybersecurity-management/
      via_parent: null
    credit: null
    layer: common
    name: Broadcom
    provider: broadcom
    says: lists Broadcom as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google
    provider: google-workspace
    says: lists Google as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: lists Google Gemini as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft 365 (Copilot)
    provider: microsoft-365
    says: lists Microsoft 365 (Copilot) as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI (ChatGPT)
    provider: openai
    says: lists OpenAI (ChatGPT) as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Oracle NetSuite
    provider: netsuite
    says: lists Oracle NetSuite as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620
      key: cybersecurity-management
      name: Cybersecurity Management
      url: /capabilities/cybersecurity-management/
      via_parent: null
    credit: null
    layer: common
    name: Palo Alto Networks
    provider: palo-alto-networks
    says: lists Palo Alto Networks as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.box.com/integrations
    tier: declared
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
    says: lists Slack as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620
      key: cybersecurity-management
      name: Cybersecurity Management
      url: /capabilities/cybersecurity-management/
      via_parent: null
    credit: null
    layer: common
    name: Splunk
    provider: splunk
    says: lists Splunk as an integration
    source: https://www.box.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://www.box.com/integrations
    tier: declared
  kind: commercial
  name: Box
  page: /applications/cloud-storage-file-sync/box/
  slug: box
  url: https://www.box.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: cloud-storage-file-sync
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: File Transfer & Synchronization
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#file-transfer--synchronization
- category: File Transfer - Object Storage & File Servers
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#file-transfer---object-storage--file-servers
- category: Groupware
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#groupware
- category: Files & Folders
  store: zapier
  url: https://zapier.com/apps
name: Cloud Storage & File Sync
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
  why: object storage used as the primary store or a mountable backend
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: consumer and business drives the apps mount, migrate from, or sync to
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI assistants grounded in the user's files
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: document translation inside the file manager
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: exact
  layer: common
  why: linking wiki pages to files
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  fit: exact
  layer: common
  why: sending stored documents for signature
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: attaching files to issues and work packages
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: common
  why: linking repositories and issues to files
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: whiteboards that reference stored files
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: sharing files into team chat
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: linking helpdesk tickets to files
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: spreadsheet-database apps over stored files
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: automation over file events
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: link previews and sharing to social networks
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: common
  why: video link previews and search
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: photo libraries imported or synced as storage
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: map previews and location search
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: office suites for in-browser document editing (WOPI) and productivity integrations
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: document archives the drive hands files to
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: locating relays and discovery servers by IP
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: domain
  why: media DAM/CDN services exposed as file backends
- capability:
    attribution: API Evangelist extension
    id: AE-240.90
    key: AE-240.90
    name: Decentralized Storage & Compute
    url: /capabilities/decentralized-storage-compute/
    via_parent: null
  fit: exact
  layer: domain
  why: decentralized storage networks offered as backends
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: common
  why: editing stored files in creative tools
- capability:
    attribution: Turbo EA
    id: BC-1120.50
    key: design-software-cad-management
    name: Design Software & CAD Management
    url: /capabilities/design-software-cad-management/
    via_parent: null
  fit: exact
  layer: common
  why: opening CAD files from the drive
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: files attached to CRM records
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: sharing files in meetings
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: common
  why: scheduling tied to drive content
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: common
  why: HR content connected to the drive
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: ERP documents connected to the drive
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: enterprise SSO in front of the drive
- capability:
    attribution: Turbo EA
    id: BC-620
    key: cybersecurity-management
    name: Cybersecurity Management
    url: /capabilities/cybersecurity-management/
    via_parent: null
  fit: exact
  layer: common
  why: DLP, SIEM and threat protection over stored content
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep-link SDKs named in Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature-flag SDK named in an Exodus report
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: in-app usage analytics SDKs named in Exodus reports
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
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Nextcloud
      - Seafile
      - rclone
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      - https://raw.githubusercontent.com/nextcloud/server/master/apps/files_external/lib/Lib/Backend/AmazonS3.php
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Filestash
      - Nextcloud
      - rclone
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      - https://github.com/nextcloud/server/tree/master/lib/private/Files/ObjectStore
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Nextcloud
      - Seafile
      - rclone
      band: thin
      in_catalog: true
      kin_score: 36.1
      mcp:
        status: none
      name: OpenStack Swift
      slug: openstack
      sources:
      - https://github.com/nextcloud/server/tree/master/apps/files_external/lib/Lib/Backend
      - https://github.com/rclone/rclone/tree/master/backend
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      status: profiled
      tags:
      - Cloud Platform
      - Infrastructure-as-a-Service
      - Open Source
      - OpenStack
      tier: observed
      url: /providers/openstack/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Seafile
      - rclone
      band: strong
      in_catalog: true
      kin_score: 57.3
      mcp:
        source: https://github.com/minio/mcp-server-aistor
        status: verified
      name: MinIO
      slug: minio
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      status: profiled
      tags:
      - Cloud-Native
      - Object Storage
      - S3 Compatible
      - Storage
      tier: observed
      url: /providers/minio/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Filestash
      - rclone
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://github.com/backblaze-labs/b2-mcp
        status: verified
      name: Backblaze B2
      slug: backblaze
      sources:
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Object Storage
      - Storage
      tier: observed
      url: /providers/backblaze/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Seafile
      - rclone
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        status: none
      name: Hetzner
      slug: hetzner
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      status: profiled
      tags:
      - Cloud Hosting
      - DNS
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/hetzner/
    - agent_band: agent-aware
      agent_readiness: 18.4
      apps:
      - Seafile
      - rclone
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: Ceph
      slug: ceph
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      status: profiled
      tags:
      - Block Storage
      - Distributed Storage
      - Object Storage
      - Storage
      tier: observed
      url: /providers/ceph/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Seafile
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 24.0
      mcp:
        status: none
      name: Wasabi
      slug: wasabi
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - REST API
      - S3 Compatible
      tier: observed
      url: /providers/wasabi/
    - agent_band: agent-native
      agent_readiness: 52.1
      apps:
      - rclone
      band: exemplar
      in_catalog: true
      kin_score: 76.9
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Object Storage
      slug: oracle-cloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Cloud
      - Infrastructure-as-a-Service
      - Oracle
      tier: observed
      url: /providers/oracle-cloud/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - rclone
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - rclone
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://github.com/linode/mcp-cluster-api
        status: verified
      name: Linode (Akamai Cloud)
      slug: linode
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud Computing
      - Infrastructure-as-a-Service
      - Kubernetes
      - Virtual Machines
      tier: observed
      url: /providers/linode/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://github.com/fastly/mcp
        status: verified
      name: Fastly Object Storage
      slug: fastly
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - CDN
      - Edge Cloud
      - Edge Compute
      - WebAssembly
      tier: observed
      url: /providers/fastly/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        source: https://github.com/IBM/mcp
        status: verified
      name: IBM COS
      slug: ibm
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - API Management
      - Artificial Intelligence
      - Database
      - IBM
      tier: observed
      url: /providers/ibm/
    - agent_band: agent-ready
      agent_readiness: 36.2
      apps:
      - Filestash
      band: strong
      in_catalog: true
      kin_score: 59.3
      mcp:
        source: https://github.com/jfrog/mcp-jfrog
        status: verified
      name: JFrog Artifactory
      slug: artifactory
      sources:
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      status: profiled
      tags:
      - Artifacts
      - CI/CD
      - DevOps
      - docker-registry
      tier: observed
      url: /providers/artifactory/
    - agent_band: agent-aware
      agent_readiness: 18.4
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 58.0
      mcp:
        status: none
      name: Impossible Cloud
      slug: impossible-cloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Company
      - Object Storage
      - S3
      tier: observed
      url: /providers/impossible-cloud/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Akamai NetStorage
      slug: akamai
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - CDN
      - Cloud
      - Edge Computing
      - Networks
      tier: observed
      url: /providers/akamai/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        source: https://github.com/scaleway/scaleway-cli
        status: verified
      name: Scaleway
      slug: scaleway
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud Computing
      - Containers
      - Database
      tier: observed
      url: /providers/scaleway/
    - agent_band: agent-aware
      agent_readiness: 23.5
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        source: https://github.com/PureStorage-OpenConnect/flashblade-mcp-server
        status: verified
      name: Pure Storage FlashBlade
      slug: pure-storage
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Data Storage
      - Enterprise Storage
      - Flash Storage
      - Storage
      tier: observed
      url: /providers/pure-storage/
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean Spaces
      slug: digital-ocean
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 41.9
      mcp:
        source: https://mcp.eu.ovhcloud.com/mcp
        status: verified
      name: OVHcloud
      slug: ovh-cloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Compute
      - Hosting
      - Servers
      tier: observed
      url: /providers/ovh-cloud/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        status: unknown
      name: China Mobile EOS
      slug: china-mobile
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - China
      - Mobile Network Operator
      - Network APIs
      - Telecommunications
      tier: observed
      url: /providers/china-mobile/
    - agent_band: agent-ready
      agent_readiness: 43.1
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        status: none
      name: IDrive e2
      slug: idrive
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/idrive/
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: none
      name: Cubbit
      slug: cubbit
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - S3 Compatible
      - Storage
      tier: observed
      url: /providers/cubbit/
    - agent_band: agent-aware
      agent_readiness: 9.7
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        source: https://github.com/qiniu/qiniu-mcp-server
        status: verified
      name: Qiniu Kodo
      slug: qiniu
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - CDN
      - Cloud
      - Company
      - Object Storage
      tier: observed
      url: /providers/qiniu/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        source: https://github.com/ucloud/udb-mysql-mcp-server
        status: verified
      name: UCloud US3
      slug: ucloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud Computing
      - Company
      - Enterprise
      - Infrastructure-as-a-Service
      tier: observed
      url: /providers/ucloud/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/cloudflare-r2/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        source: https://github.com/zadarastorage/zadara-mcp
        status: verified
      name: Zadara
      slug: zadara
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Block Storage
      - Company
      - Object Storage
      - Storage
      tier: observed
      url: /providers/zadara/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        status: none
      name: 3DS OUTSCALE
      slug: outscale
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure-as-a-Service
      - Storage
      tier: observed
      url: /providers/outscale/
    - agent_band: agent-aware
      agent_readiness: 12.9
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        source: https://github.com/TencentCloud/cos-mcp
        status: verified
      name: Tencent COS
      slug: tencentcloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Computing
      - Infrastructure
      tier: observed
      url: /providers/tencentcloud/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 21.7
      mcp:
        status: none
      name: Selectel
      slug: selectel
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Infrastructure
      - Storage
      - VPS
      tier: observed
      url: /providers/selectel/
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 20.6
      mcp:
        source: https://github.com/ionos-cloud/ionoscloud-mcp
        status: verified
      name: IONOS Cloud
      slug: ionos
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Company
      - Domains
      - Hosting
      tier: observed
      url: /providers/ionos/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: none
      name: DreamHost DreamObjects
      slug: dreamhost
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Company
      - Domains
      - Hosting
      tier: observed
      url: /providers/dreamhost/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud OSS
      slug: alibaba
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Commerce
      - E-Commerce
      tier: observed
      url: /providers/alibaba/
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: unknown
      name: Seagate Lyve Cloud
      slug: seagate
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Company
      - Data
      - Enterprise
      - Storage
      tier: observed
      url: /providers/seagate/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        source: https://github.com/huaweicloud/huaweicloud-mcp
        status: verified
      name: Huawei OBS
      slug: huaweicloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Cloud
      - Company
      - Infrastructure-as-a-Service
      - Platform-as-a-Service
      tier: observed
      url: /providers/huaweicloud/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 9.3
      mcp:
        status: none
      name: Hitachi Content Platform
      slug: hitachi-vantara
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - AI Services
      - Data Infrastructure
      - Hybrid Cloud
      - Storage
      tier: observed
      url: /providers/hitachi-vantara/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: none
      name: Magalu Cloud
      slug: magalu-cloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Brazil
      - Cloud
      - Infrastructure
      - Public Cloud
      tier: observed
      url: /providers/magalu-cloud/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 8.6
      mcp:
        status: unknown
      name: QingStor
      slug: qingstor
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Infrastructure
      - Storage
      tier: observed
      url: /providers/qingstor/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: none
      name: Spectra Logic
      slug: spectra-logic
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Backup
      - Company
      - Data Storage
      - Enterprise
      tier: observed
      url: /providers/spectra-logic/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: none
      name: Synology C2
      slug: synology
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - Backup
      - Cloud
      - Company
      - Storage
      tier: observed
      url: /providers/synology/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp: &id001
        source: https://github.com/meganz/mega-mcp
        status: verified
      name: MEGA S4
      slug: mega-nz
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags: &id002
      - Company
      tier: observed
      url: /providers/mega-nz/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: unknown
      name: ArvanCloud
      slug: arvancloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: profiled
      tags:
      - CDN
      - Cloud
      - Storage
      - Video Streaming
      tier: observed
      url: /providers/arvancloud/
    - agent_band: null
      agent_readiness: null
      apps:
      - rclone
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Scality
      slug: scality
      sources:
      - https://github.com/rclone/rclone/tree/master/backend/s3/provider
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Seafile
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        status: none
      name: Exoscale
      slug: exoscale
      sources:
      - https://manual.seafile.com/latest/setup/setup_with_s3/
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Storage
      tier: declared
      url: /providers/exoscale/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Filestash
      - Nextcloud
      - rclone
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Filestash
      - Nextcloud
      - rclone
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Nextcloud
      - rclone
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 57.4
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: observed
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho WorkDrive
      slug: zoho
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Analytics
      - CRM
      - Collaboration
      - Customer Service
      tier: observed
      url: /providers/zoho/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - rclone
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: iCloud Drive
      slug: apple
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        status: none
      name: Filen
      slug: filen
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Encryption
      - Zero Knowledge
      tier: observed
      url: /providers/filen/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 40.3
      mcp:
        status: none
      name: Jottacloud
      slug: jottacloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Company
      - Norwegian
      tier: observed
      url: /providers/jottacloud/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 32.5
      mcp:
        status: none
      name: ShareFile
      slug: citrix-sharefile
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Document Workflow
      - E-Signature
      - File Sharing
      - Secure File Transfer
      tier: observed
      url: /providers/citrix-sharefile/
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 31.7
      mcp:
        status: unknown
      name: OpenDrive
      slug: opendrive
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Collaboration
      - File Sync
      tier: observed
      url: /providers/opendrive/
    - agent_band: agent-aware
      agent_readiness: 6.3
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 28.5
      mcp:
        status: none
      name: Proton Drive
      slug: proton-me
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Encryption
      - Privacy
      tier: observed
      url: /providers/proton-me/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        source: https://mcp.pcloud.com/.well-known/oauth-protected-resource/mcp
        status: verified
      name: pCloud
      slug: pcloud
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - File Sync
      - Security
      tier: observed
      url: /providers/pcloud/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 21.5
      mcp:
        status: unknown
      name: SugarSync
      slug: sugarsync
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Collaboration
      - File Sync
      tier: observed
      url: /providers/sugarsync/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 21.3
      mcp:
        source: https://github.com/putdotio/putio-mcp-server
        status: verified
      name: put.io
      slug: put-io
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Automation
      - Cloud Storage
      - File Management
      - Media Streaming
      tier: observed
      url: /providers/put-io/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: Koofr
      slug: koofr
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - File Sync
      - GDPR
      - Privacy
      tier: observed
      url: /providers/koofr/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 17.2
      mcp:
        status: none
      name: Quatrix (Maytech)
      slug: quatrix
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Company
      - Enterprise
      - File Transfer
      - SecureData
      tier: observed
      url: /providers/quatrix/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Filestash
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        status: none
      name: Syncthing
      slug: syncthing
      sources:
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      status: profiled
      tags:
      - Cross-Platform
      - Encryption
      - File Synchronization
      - Open Source
      tier: observed
      url: /providers/syncthing/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: none
      name: Internxt
      slug: internxt
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Company
      - Encryption
      - Privacy
      tier: observed
      url: /providers/internxt/
    - agent_band: agent-aware
      agent_readiness: 6.4
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: unknown
      name: STRATO HiDrive
      slug: hidrive
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - AES-256 Encryption
      - Cloud Storage
      - Data Protection
      - German
      tier: observed
      url: /providers/hidrive/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp: *id001
      name: MEGA
      slug: mega-nz
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/mega-nz/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: Mail.ru Cloud
      slug: mail-ru
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud
      - Collaboration
      - Russian
      - Storage
      tier: observed
      url: /providers/mail-ru/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: none
      name: Internet Archive
      slug: internet-archive
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Archival
      - Digital Library
      - Non-Profit
      - Open Access
      tier: observed
      url: /providers/internet-archive/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 4.7
      mcp:
        status: none
      name: GoFile
      slug: gofile
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - File Sharing
      - Public APIs
      tier: observed
      url: /providers/gofile/
    - agent_band: null
      agent_readiness: null
      apps:
      - rclone
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Files.com
      slug: files-com
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - rclone
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Yandex Disk
      slug: yandex
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-240.90
      key: AE-240.90
      name: Decentralized Storage & Compute
      url: /capabilities/decentralized-storage-compute/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Filestash
      - rclone
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        status: none
      name: Storj
      slug: storj
      sources:
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - Public APIs
      - Storage
      tier: observed
      url: /providers/storj/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - rclone
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: none
      name: Sia
      slug: sia-tech
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Blockchain
      - Cloud Storage
      - Company
      - Decentralized Storage
      tier: observed
      url: /providers/sia-tech/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - rclone
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        source: https://cloudinary.com/documentation/cloudinary_llm_mcp
        status: verified
      name: Cloudinary
      slug: cloudinary
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Asset Management
      - Digital Asset Management
      - Image Processing
      - Image Transformation
      tier: observed
      url: /providers/cloudinary/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://registry.npmjs.org/@imagekit/api-mcp
        status: verified
      name: ImageKit
      slug: imagekit
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - CDN
      - Image
      - Media
      - Video
      tier: observed
      url: /providers/imagekit/
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Nextcloud
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: none
      name: Paperless-ngx
      slug: paperless-ngx
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/paperless-ngx/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - rclone
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Google Photos
      slug: google-photos
      sources:
      - https://github.com/rclone/rclone/tree/master/backend
      status: profiled
      tags:
      - Albums
      - Google
      - Image
      - Media
      tier: observed
      url: /providers/google-photos/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Filestash
      - ownCloud Infinite Scale
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: ONLYOFFICE
      slug: onlyoffice
      sources:
      - https://github.com/mickael-kerjean/filestash/tree/master/server/plugin
      - https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Box
      - Dropbox
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Box
      - Dropbox
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365 (Copilot)
      slug: microsoft-365
      sources:
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - ownCloud Infinite Scale
      band: exemplar
      in_catalog: true
      kin_score: 69.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: documented
      name: Microsoft Office (WOPI)
      slug: microsoft-office
      sources:
      - https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Microsoft
      - Office
      tier: declared
      url: /providers/microsoft-office/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 33.5
      mcp:
        status: none
      name: Overleaf
      slug: overleaf
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Academic
      - Cloud
      - Collaboration
      - LaTeX
      tier: declared
      url: /providers/overleaf/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ownCloud Infinite Scale
      band: emerging
      in_catalog: true
      kin_score: 19.0
      mcp:
        status: none
      name: Collabora Online
      slug: collabora-online
      sources:
      - https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
      status: profiled
      tags:
      - Collaboration
      - Company
      - Office Suite
      - Real-Time Editing
      tier: declared
      url: /providers/collabora-online/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Box
      - Dropbox
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Box
      - Dropbox
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
      status: profiled
      tags: &id004
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Box
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - Nextcloud
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: declared
      url: /providers/reddit/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://github.com/discourse/discourse-mcp
        status: verified
      name: Discourse
      slug: discourse
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Community
      - Forums
      - Open Source
      tier: declared
      url: /providers/discourse/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: declared
      url: /providers/mastodon/
  - capability:
      attribution: Turbo EA
      id: BC-620
      key: cybersecurity-management
      name: Cybersecurity Management
      url: /capabilities/cybersecurity-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.3
      apps:
      - Box
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://github.com/PaloAltoNetworks/prisma-airs-mcp
        status: verified
      name: Palo Alto Networks
      slug: palo-alto-networks
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Cloud Security
      - Cybersecurity
      - Firewall
      - Network Security
      tier: declared
      url: /providers/palo-alto-networks/
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - Box
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: declared
      url: /providers/splunk/
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - Box
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        source: https://github.com/Broadcom/rally-mcp-workflows
        status: verified
      name: Broadcom
      slug: broadcom
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Cloud Infrastructure
      - Gateways
      - Management
      - Networks
      tier: declared
      url: /providers/broadcom/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 65.9
      apps:
      - Box
      - Dropbox
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe
      slug: adobe
      sources:
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: declared
      url: /providers/adobe/
    - agent_band: agent-native
      agent_readiness: 71.4
      apps:
      - Dropbox
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Box
      - Dropbox
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 37.2
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: declared
      url: /providers/mattermost/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Dropbox
      - Syncthing
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/syncthing/syncthing/main/go.mod
      - https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Seafile
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id003
      name: Firebase (Crashlytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.seafile.seadroid2/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: DocuSign
      slug: docusign
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Documenso
      slug: documenso
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Documents
      - E-Signature
      - Open Source
      - Signing
      tier: declared
      url: /providers/documenso/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - Dropbox
      band: exemplar
      in_catalog: true
      kin_score: 94.6
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - Box
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 65.7
      apps:
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 82.6
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Nextcloud
      band: developing
      in_catalog: true
      kin_score: 42.1
      mcp:
        source: https://www.openproject.org/docs/system-admin-guide/integrations/mcp-server/
        status: verified
      name: OpenProject
      slug: openproject
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Agile
      - Gantt
      - Open Source
      - Project Management
      tier: declared
      url: /providers/openproject/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: declared
      url: /providers/gitlab/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Nextcloud
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 32.6
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: PeerTube
      slug: peertube
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Decentralized
      - Federation
      - Open Source
      - Video
      tier: declared
      url: /providers/peertube/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Nextcloud
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: declared
      url: /providers/openstreetmap/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.5
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Zammad
      slug: zammad
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Help Desk
      - Support
      tier: declared
      url: /providers/zammad/
  - capability:
      attribution: Turbo EA
      id: BC-1120.50
      key: design-software-cad-management
      name: Design Software & CAD Management
      url: /capabilities/design-software-cad-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.1
      apps:
      - Dropbox
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
        status: verified
      name: Autodesk
      slug: autodesk
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - 3D Modeling
      - Autodesk
      - Digital Twin
      - Fortune 1000
      tier: declared
      url: /providers/autodesk/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Box
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Split
      slug: split
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Box
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: none
      name: Oracle NetSuite
      slug: netsuite
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Box
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: Workday
      slug: workday
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: declared
      url: /providers/workday/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Syncthing
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/syncthing/syncthing/main/go.mod
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Box
      band: exemplar
      in_catalog: true
      kin_score: 78.0
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.box.com/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.9
      apps:
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - Nextcloud
      band: developing
      in_catalog: true
      kin_score: 46.4
      mcp:
        source: https://developers.miro.com/docs/miro-mcp
        status: verified
      name: Miro
      slug: miro
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Diagramming
      - Productivity
      - Visual Collaboration
      - Whiteboard
      tier: declared
      url: /providers/miro/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Nextcloud
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: declared
      url: /providers/deepl/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Dropbox
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Nextcloud
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: declared
      url: /providers/giphy/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Dropbox
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        status: none
      name: Reclaim.ai
      slug: reclaim-ai
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Calendar
      - Productivity
      - Scheduling
      tier: declared
      url: /providers/reclaim-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Nextcloud
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        status: none
      name: Grist
      slug: grist
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Collaboration
      - Database
      - No-Code
      - Spreadsheets
      tier: declared
      url: /providers/grist/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Dropbox
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - Dropbox
      band: strong
      in_catalog: true
      kin_score: 56.2
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Nextcloud
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        source: https://www.windmill.dev/docs/core_concepts/mcp
        status: documented
      name: Windmill
      slug: windmill
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Automation
      - Internal Tools
      - Open Source
      - Pro-Code-API-Composition
      tier: declared
      url: /providers/windmill/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Box
      - Dropbox
      - Nextcloud
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Box
      - Dropbox
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic (Claude)
      slug: anthropic
      sources:
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Box
      - Dropbox
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://www.box.com/integrations
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: declared
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Nextcloud
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp:
        source: https://github.com/replicate/replicate-mcp-code-mode
        status: verified
      name: Replicate
      slug: replicate
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Artificial Intelligence
      - Image Generation
      - Language Models
      - Machine Learning
      tier: declared
      url: /providers/replicate/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Nextcloud
      band: developing
      in_catalog: true
      kin_score: 47.2
      mcp:
        status: none
      name: Aleph Alpha
      slug: aleph-alpha
      sources:
      - https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - LLM
      - Machine Learning
      tier: declared
      url: /providers/aleph-alpha/
    - agent_band: agent-ready
      agent_readiness: 38.8
      apps:
      - Dropbox
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: xAI (SpaceXAI)
      slug: xai
      sources:
      - https://www.dropbox.com/app-integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: declared
      url: /providers/xai/
  layer: agent
summary:
  coverage_pct: 96.9
  declared_only: 49
  distinct_providers: 129
  in_catalog: 125
  mcp:
    documented: 3
    none: 52
    unchecked: 4
    verified: 62
  mcp_verified: 62
  mean_kin_score: 43.9
  observed: 80
  queued: 4
  reference_apps: 8
title: 'Cloud Storage & File Sync: application blueprint'
---
