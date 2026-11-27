---
app: Mastodon
app_slug: mastodon
app_url: https://github.com/mastodon/mastodon
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - DeepL
  - LibreTranslate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - PostgreSQL
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - OpenTelemetry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - OpenStack Swift
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: community-forums
  name: Community & Forums
  url: /applications/community-forums/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
- route: source code
  url: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
- route: source code
  url: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
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
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
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
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id004
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
  tier: observed
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
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id005
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id007
      source: https://github.com/elastic/mcp-server-elasticsearch
      status: verified
    slug: elasticsearch
    status: profiled
    tags: &id008
    - Analytics
    - Database
    - Full-Text Search
    - NoSQL
    url: /providers/elasticsearch/
  layer: common
  name: Elasticsearch
  provider: elasticsearch
  says: ships the Elasticsearch SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id009
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id010
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id011
      source: https://github.com/LibreTranslate/LibreTranslate-MCP
      status: verified
    slug: libre-translate
    status: profiled
    tags: &id012
    - Machine Translation
    - Natural Language Processing
    - Open Source
    - Translation
    url: /providers/libre-translate/
  layer: domain
  name: LibreTranslate
  provider: libre-translate
  says: ships the LibreTranslate SDK or integration code
  source: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
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
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id013
      status: none
    slug: openstack
    status: profiled
    tags: &id014
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
  layer: common
  name: OpenStack Swift
  provider: openstack
  says: ships the OpenStack Swift SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id015
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id016
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
  layer: common
  name: OpenTelemetry
  provider: opentelemetry
  says: ships the OpenTelemetry SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id017
      status: none
    slug: postgresql
    status: profiled
    tags: &id018
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: common
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id019
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id020
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/community-forums/mastodon/
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
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id005
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id006
  url: /providers/deepl/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id007
  name: Elasticsearch
  slug: elasticsearch
  status: profiled
  tags: *id008
  url: /providers/elasticsearch/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id009
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id010
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id011
  name: LibreTranslate
  slug: libre-translate
  status: profiled
  tags: *id012
  url: /providers/libre-translate/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id013
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id014
  url: /providers/openstack/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id015
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id016
  url: /providers/opentelemetry/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id017
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id018
  url: /providers/postgresql/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id019
  name: Redis
  slug: redis
  status: profiled
  tags: *id020
  url: /providers/redis/
siblings:
- name: Circle
  rows: 36
  url: /applications/community-forums/circle/
- name: Discourse
  rows: 44
  url: /applications/community-forums/discourse/
- name: Flarum
  rows: 4
  url: /applications/community-forums/flarum/
- name: Lemmy
  rows: 2
  url: /applications/community-forums/lemmy/
- name: NodeBB
  rows: 9
  url: /applications/community-forums/nodebb/
sitemap: true
title: 'Mastodon: Community & Forums reference app'
---
