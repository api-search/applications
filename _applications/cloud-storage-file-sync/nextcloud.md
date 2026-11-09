---
app: Nextcloud
app_slug: nextcloud
app_url: https://github.com/nextcloud/server
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
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Paperless-ngx
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - OpenStack Swift
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - OpenStreetMap
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: common
  name: Contract Execution Management
  providers:
  - Documenso
  - DocuSign
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zammad
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: common
  name: End-User Computing Management
  providers:
  - Overleaf
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Mattermost
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: common
  name: Knowledge Management
  providers:
  - Notion
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Miro
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - DeepL
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: common
  name: Photo & Image Libraries
  providers:
  - GIPHY
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira
  - OpenProject
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Discourse
  - Mastodon
  - Reddit
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Grist
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: common
  name: Video Hosting & Encoding
  providers:
  - PeerTube
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Windmill
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Aleph Alpha
  - OpenAI
  - Replicate
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 29
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.1
    mcp: &id043
      status: none
    slug: openstack
    status: profiled
    tags: &id044
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: developing
    in_catalog: true
    kin_score: 47.2
    mcp: &id001
      status: none
    slug: aleph-alpha
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Company
    - LLM
    - Machine Learning
    url: /providers/aleph-alpha/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.4
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id007
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id009
      source: https://github.com/discourse/discourse-mcp
      status: verified
    slug: discourse
    status: profiled
    tags: &id010
    - Community
    - Forums
    - Open Source
    url: /providers/discourse/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id011
      status: none
    slug: documenso
    status: profiled
    tags: &id012
    - Documents
    - E-Signature
    - Open Source
    - Signing
    url: /providers/documenso/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id013
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id014
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id017
      status: none
    slug: giphy
    status: profiled
    tags: &id018
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id019
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id020
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id021
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id022
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id023
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id024
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: thin
    in_catalog: true
    kin_score: 36.6
    mcp: &id025
      status: none
    slug: grist
    status: profiled
    tags: &id026
    - Collaboration
    - Database
    - No-Code
    - Spreadsheets
    url: /providers/grist/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id027
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id028
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id029
      status: none
    slug: mastodon
    status: profiled
    tags: &id030
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id031
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id032
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id033
      source: https://developers.miro.com/docs/miro-mcp
      status: verified
    slug: miro
    status: profiled
    tags: &id034
    - Diagramming
    - Productivity
    - Visual Collaboration
    - Whiteboard
    url: /providers/miro/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id035
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id036
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id039
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 42.1
    mcp: &id041
      source: https://www.openproject.org/docs/system-admin-guide/integrations/mcp-server/
      status: verified
    slug: openproject
    status: profiled
    tags: &id042
    - Agile
    - Gantt
    - Open Source
    - Project Management
    url: /providers/openproject/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id045
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id046
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 33.5
    mcp: &id047
      status: none
    slug: overleaf
    status: profiled
    tags: &id048
    - Academic
    - Cloud
    - Collaboration
    - LaTeX
    url: /providers/overleaf/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id049
      status: none
    slug: paperless-ngx
    status: profiled
    tags: &id050
    - Company
    url: /providers/paperless-ngx/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.6
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id051
      status: none
    slug: peertube
    status: profiled
    tags: &id052
    - Decentralized
    - Federation
    - Open Source
    - Video
    url: /providers/peertube/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id053
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id054
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id055
      source: https://github.com/replicate/replicate-mcp-code-mode
      status: verified
    slug: replicate
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - Image Generation
    - Language Models
    - Machine Learning
    url: /providers/replicate/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id057
      source: https://www.windmill.dev/docs/core_concepts/mcp
      status: documented
    slug: windmill
    status: profiled
    tags: &id058
    - Automation
    - Internal Tools
    - Open Source
    - Pro-Code-API-Composition
    url: /providers/windmill/
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
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id059
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id060
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id061
      status: none
    slug: youtube
    status: profiled
    tags: &id062
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.5
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id063
      status: none
    slug: zammad
    status: profiled
    tags: &id064
    - Artificial Intelligence
    - Company
    - Help Desk
    - Support
    url: /providers/zammad/
  layer: common
  name: Zammad
  provider: zammad
  says: lists Zammad as an integration
  source: https://api.github.com/search/repositories?q=org:nextcloud+integration_+in:name&per_page=100
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/nextcloud/
providers:
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 47.2
  mcp: *id001
  name: Aleph Alpha
  slug: aleph-alpha
  status: profiled
  tags: *id002
  url: /providers/aleph-alpha/
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
  agent_readiness: 36.4
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id007
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id008
  url: /providers/deepl/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id009
  name: Discourse
  slug: discourse
  status: profiled
  tags: *id010
  url: /providers/discourse/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id011
  name: Documenso
  slug: documenso
  status: profiled
  tags: *id012
  url: /providers/documenso/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id013
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id014
  url: /providers/docusign/
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
- agent_band: agent-aware
  agent_readiness: 21.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id017
  name: GIPHY
  slug: giphy
  status: profiled
  tags: *id018
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id019
  name: GitHub
  slug: github
  status: profiled
  tags: *id020
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id021
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id022
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id023
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id024
  url: /providers/google-drive/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id025
  name: Grist
  slug: grist
  status: profiled
  tags: *id026
  url: /providers/grist/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id027
  name: Jira
  slug: jira
  status: profiled
  tags: *id028
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id029
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id030
  url: /providers/mastodon/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id031
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id032
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id033
  name: Miro
  slug: miro
  status: profiled
  tags: *id034
  url: /providers/miro/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id035
  name: Notion
  slug: notion
  status: profiled
  tags: *id036
  url: /providers/notion/
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
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id039
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id040
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 42.1
  mcp: *id041
  name: OpenProject
  slug: openproject
  status: profiled
  tags: *id042
  url: /providers/openproject/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id043
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id044
  url: /providers/openstack/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id045
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id046
  url: /providers/openstreetmap/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 33.5
  mcp: *id047
  name: Overleaf
  slug: overleaf
  status: profiled
  tags: *id048
  url: /providers/overleaf/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id049
  name: Paperless-ngx
  slug: paperless-ngx
  status: profiled
  tags: *id050
  url: /providers/paperless-ngx/
- agent_band: agent-ready
  agent_readiness: 32.6
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id051
  name: PeerTube
  slug: peertube
  status: profiled
  tags: *id052
  url: /providers/peertube/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id053
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id054
  url: /providers/reddit/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id055
  name: Replicate
  slug: replicate
  status: profiled
  tags: *id056
  url: /providers/replicate/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id057
  name: Windmill
  slug: windmill
  status: profiled
  tags: *id058
  url: /providers/windmill/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id059
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id060
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id061
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id062
  url: /providers/youtube/
- agent_band: agent-aware
  agent_readiness: 23.5
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id063
  name: Zammad
  slug: zammad
  status: profiled
  tags: *id064
  url: /providers/zammad/
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
title: 'Nextcloud: Cloud Storage & File Sync reference app'
---
