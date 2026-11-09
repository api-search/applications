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
  id: social-network
  name: Social Networking & Microblogging
  url: /applications/social-network/
counts:
  declared: 0
  observed: 9
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.joinmastodon.android/latest/
- route: dependency manifest
  url: https://github.com/mastodon/mastodon/blob/main/Gemfile
- route: source code
  url: https://github.com/mastodon/mastodon/blob/main/.env.production.sample
- route: source code
  url: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
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
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/mastodon/mastodon/blob/main/Gemfile
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
  source: https://github.com/mastodon/mastodon/blob/main/Gemfile
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
    agent_readiness: 36.4
    band: strong
    in_catalog: true
    kin_score: 60.8
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
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id007
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id008
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: common
  name: Elasticsearch
  provider: elastic
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/mastodon/mastodon/blob/main/.env.production.sample
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 31.5
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
  source: https://github.com/mastodon/mastodon/blob/main/Gemfile
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
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 26.2
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.1
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
  source: https://github.com/mastodon/mastodon/blob/main/Gemfile
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
    kin_score: 12.2
    mcp: &id015
      status: none
    slug: postgresql
    status: profiled
    tags: &id016
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: common
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://github.com/mastodon/mastodon/blob/main/Gemfile
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
    agent_band: agent-native
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id017
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id018
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/mastodon/mastodon/blob/main/Gemfile
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-network/mastodon/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id005
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id006
  url: /providers/deepl/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id007
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id008
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id009
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id010
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 26.2
  mcp: *id011
  name: LibreTranslate
  slug: libre-translate
  status: profiled
  tags: *id012
  url: /providers/libre-translate/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id013
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id014
  url: /providers/openstack/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id015
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id016
  url: /providers/postgresql/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id017
  name: Redis
  slug: redis
  status: profiled
  tags: *id018
  url: /providers/redis/
siblings:
- name: Bluesky
  rows: 4
  url: /applications/social-network/bluesky/
- name: Friendica
  rows: 20
  url: /applications/social-network/friendica/
- name: Instagram
  rows: 2
  url: /applications/social-network/instagram/
- name: Misskey
  rows: 11
  url: /applications/social-network/misskey/
- name: Pixelfed
  rows: 11
  url: /applications/social-network/pixelfed/
- name: Threads
  rows: 2
  url: /applications/social-network/threads/
sitemap: true
title: 'Mastodon: Social Networking & Microblogging reference app'
---
