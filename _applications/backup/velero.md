---
app: Velero
app_slug: velero
app_url: https://github.com/vmware-tanzu/velero
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Alibaba Cloud OSS
  - Amazon EBS
  - Amazon S3
  - Azure Blob Storage
  - Azure Managed Disks
  - Cloudian HyperStore
  - DigitalOcean
  - Google Cloud Storage
  - Google Compute Engine disks
  - HPE Storage
  - HuaweiCloud OBS
  - IBM Cloud
  - MinIO
  - OpenEBS
  - OpenStack Swift/Cinder
  - Oracle Cloud
  - Portworx
  - Storj
  - Tencent Cloud
  - VMware vSphere
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 20
  observed: 0
credits: []
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
  facts:
    agent_band: human-only
    agent_readiness: 3.4
    band: emerging
    in_catalog: true
    kin_score: 17.9
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id003
      status: none
    slug: amazon-ebs
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Block Storage
    - EBS
    - EC2
    url: /providers/amazon-ebs/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id008
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id010
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id011
      status: none
    slug: cloudian
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Company
    - Object Storage
    - Storage
    url: /providers/cloudian/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id013
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id014
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id015
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id016
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id017
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id018
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: developing
    in_catalog: true
    kin_score: 39.7
    mcp: &id019
      source: https://github.com/HewlettPackard/gl-mcp
      status: verified
    slug: hpe
    status: profiled
    tags: &id020
    - Cloud
    - Compute
    - Edge to Cloud
    - Infrastructure-as-a-Service
    url: /providers/hpe/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.7
    mcp: &id021
      source: https://github.com/huaweicloud/huaweicloud-mcp
      status: verified
    slug: huaweicloud
    status: profiled
    tags: &id022
    - Cloud
    - Company
    - Infrastructure-as-a-Service
    - Platform-as-a-Service
    url: /providers/huaweicloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: strong
    in_catalog: true
    kin_score: 65.8
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id025
      source: https://github.com/minio/mcp-server-aistor
      status: verified
    slug: minio
    status: profiled
    tags: &id026
    - Cloud-Native
    - Object Storage
    - S3 Compatible
    - Storage
    url: /providers/minio/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id027
      status: none
    slug: openebs
    status: profiled
    tags: &id028
    - Cloud-Native
    - Containers
    - Kubernetes
    - Open Source
    url: /providers/openebs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id029
      status: none
    slug: openstack
    status: profiled
    tags: &id030
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
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
  facts:
    agent_band: agent-native
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id031
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle-cloud
    status: profiled
    tags: &id032
    - Cloud Computing
    - Enterprise Cloud
    - Infrastructure-as-a-Service
    - Oracle
    url: /providers/oracle-cloud/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id033
      status: none
    slug: portworx
    status: profiled
    tags: &id034
    - Cloud-Native
    - Containers
    - Data Management
    - Kubernetes
    url: /providers/portworx/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.7
    mcp: &id035
      status: none
    slug: storj
    status: profiled
    tags: &id036
    - Cloud Storage
    - Object Storage
    - Public APIs
    - Storage
    url: /providers/storj/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id037
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id039
      status: none
    slug: vmware
    status: profiled
    tags: &id040
    - Cloud Computing
    - Container Management
    - Hybrid Cloud
    - Infrastructure
    url: /providers/vmware/
  layer: domain
  name: VMware vSphere
  provider: vmware
  says: lists VMware vSphere as an integration
  source: https://raw.githubusercontent.com/vmware-tanzu/velero/main/site/content/docs/main/supported-providers.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/velero/
providers:
- agent_band: human-only
  agent_readiness: 3.4
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id001
  name: Alibaba Cloud OSS
  slug: alibaba
  status: profiled
  tags: *id002
  url: /providers/alibaba/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id003
  name: Amazon EBS
  slug: amazon-ebs
  status: profiled
  tags: *id004
  url: /providers/amazon-ebs/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id007
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id008
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id009
  name: Azure Managed Disks
  slug: microsoft-azure
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id011
  name: Cloudian HyperStore
  slug: cloudian
  status: profiled
  tags: *id012
  url: /providers/cloudian/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id013
  name: DigitalOcean
  slug: digital-ocean
  status: profiled
  tags: *id014
  url: /providers/digital-ocean/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id015
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id016
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id017
  name: Google Compute Engine disks
  slug: google-cloud-platform
  status: profiled
  tags: *id018
  url: /providers/google-cloud-platform/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id019
  name: HPE Storage
  slug: hpe
  status: profiled
  tags: *id020
  url: /providers/hpe/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.7
  mcp: *id021
  name: HuaweiCloud OBS
  slug: huaweicloud
  status: profiled
  tags: *id022
  url: /providers/huaweicloud/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id023
  name: IBM Cloud
  slug: ibm
  status: profiled
  tags: *id024
  url: /providers/ibm/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id025
  name: MinIO
  slug: minio
  status: profiled
  tags: *id026
  url: /providers/minio/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id027
  name: OpenEBS
  slug: openebs
  status: profiled
  tags: *id028
  url: /providers/openebs/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id029
  name: OpenStack Swift/Cinder
  slug: openstack
  status: profiled
  tags: *id030
  url: /providers/openstack/
- agent_band: agent-native
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id031
  name: Oracle Cloud
  slug: oracle-cloud
  status: profiled
  tags: *id032
  url: /providers/oracle-cloud/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id033
  name: Portworx
  slug: portworx
  status: profiled
  tags: *id034
  url: /providers/portworx/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id035
  name: Storj
  slug: storj
  status: profiled
  tags: *id036
  url: /providers/storj/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id037
  name: Tencent Cloud
  slug: tencentcloud
  status: profiled
  tags: *id038
  url: /providers/tencentcloud/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id039
  name: VMware vSphere
  slug: vmware
  status: profiled
  tags: *id040
  url: /providers/vmware/
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
- name: Kopia
  rows: 6
  url: /applications/backup/kopia/
- name: Restic
  rows: 5
  url: /applications/backup/restic/
sitemap: true
title: 'Velero: Backup & Device Restore reference app'
---
