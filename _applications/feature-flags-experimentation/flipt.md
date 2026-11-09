---
app: Flipt
app_slug: flipt
app_url: https://github.com/flipt-io/flipt
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-250.10.20
  key: AE-250.10.20
  layer: domain
  name: Container Registries
  providers:
  - Amazon ECR
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Twilio Segment
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/flipt-io/flipt/blob/main/go.mod
- route: source code
  url: https://github.com/flipt-io/flipt/tree/main/internal/server/authn/method
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id002
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-ecr
    status: profiled
    tags: &id003
    - Amazon Web Services
    - Container Images
    - Container Registry
    - Containers
    url: /providers/amazon-ecr/
  layer: domain
  name: Amazon ECR
  provider: amazon-ecr
  says: ships the Amazon ECR SDK or integration code
  source: https://github.com/flipt-io/flipt/blob/main/go.mod
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
    mcp: &id004
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id005
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/flipt-io/flipt/blob/main/go.mod
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
    mcp: &id006
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id007
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/flipt-io/flipt/blob/main/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id008
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id009
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/flipt-io/flipt/blob/main/go.mod
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: *id001
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/flipt-io/flipt/tree/main/internal/server/authn/method
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
    mcp: &id010
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id011
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/flipt-io/flipt/blob/main/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id012
      status: none
    slug: segment
    status: profiled
    tags: &id013
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://github.com/flipt-io/flipt/blob/main/go.mod
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/flipt/
providers:
- agent_band: agent-aware
  agent_readiness: 27.7
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id002
  name: Amazon ECR
  slug: amazon-ecr
  status: profiled
  tags: *id003
  url: /providers/amazon-ecr/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id004
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id005
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id006
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id007
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id008
  name: GitHub
  slug: github
  status: profiled
  tags: *id009
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id010
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id011
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id012
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id013
  url: /providers/segment/
siblings:
- name: ConfigCat
  rows: 18
  url: /applications/feature-flags-experimentation/configcat/
- name: Flagsmith
  rows: 16
  url: /applications/feature-flags-experimentation/flagsmith/
- name: GrowthBook
  rows: 20
  url: /applications/feature-flags-experimentation/growthbook/
- name: LaunchDarkly
  rows: 91
  url: /applications/feature-flags-experimentation/launchdarkly/
- name: Statsig
  rows: 33
  url: /applications/feature-flags-experimentation/statsig/
- name: Unleash
  rows: 4
  url: /applications/feature-flags-experimentation/unleash/
sitemap: true
title: 'Flipt: Feature Flags & Experimentation reference app'
---
