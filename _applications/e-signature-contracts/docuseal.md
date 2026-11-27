---
app: DocuSeal
app_slug: docuseal
app_url: https://github.com/docusealco/docuseal
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - AWS Secrets Manager
  url: /capabilities/configuration-secrets-management/
  via_parent: null
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
  id: e-signature-contracts
  name: E-signature & Contract Management
  url: /applications/e-signature-contracts/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
- route: documentation
  url: https://github.com/docusealco/docuseal
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
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
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 39.2
    band: exemplar
    in_catalog: true
    kin_score: 77.5
    mcp: &id003
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Configuration
    - Credentials
    - Rotation
    url: /providers/amazon-secrets-manager/
  layer: common
  name: AWS Secrets Manager
  provider: amazon-secrets-manager
  says: ships the AWS Secrets Manager SDK or integration code
  source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
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
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
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
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/e-signature-contracts/docuseal/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-native
  agent_readiness: 39.2
  band: exemplar
  in_catalog: true
  kin_score: 77.5
  mcp: *id003
  name: AWS Secrets Manager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id004
  url: /providers/amazon-secrets-manager/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id005
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id007
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id008
  url: /providers/gcp-cloud-storage/
siblings:
- name: Documenso
  rows: 15
  url: /applications/e-signature-contracts/documenso/
- name: DocuSign
  rows: 16
  url: /applications/e-signature-contracts/docusign/
- name: Dropbox Sign
  rows: 18
  url: /applications/e-signature-contracts/dropbox-sign/
- name: OpenSign
  rows: 7
  url: /applications/e-signature-contracts/opensign/
- name: Zoho Sign
  rows: 24
  url: /applications/e-signature-contracts/zoho-sign/
sitemap: true
title: 'DocuSeal: E-signature & Contract Management reference app'
---
