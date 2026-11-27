---
app: Stalwart Mail Server
app_slug: stalwart-mail-server
app_url: https://github.com/stalwartlabs/stalwart
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  - Meilisearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  - Azure Blob Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-927
  key: AE-927
  layer: common
  name: Domain Registration & Managed DNS
  providers:
  - Amazon Route 53
  - bunny.net
  - Cloudflare
  - deSEC
  - DigitalOcean
  - Gandi
  - Google Cloud DNS
  - Hetzner
  - Linode
  - OVHcloud
  - Porkbun
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: email-client
  name: Email Client & Hosting
  url: /applications/email-client/
counts:
  declared: 0
  observed: 19
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
- route: source code
  url: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
- route: source code
  url: https://github.com/stalwartlabs/stalwart/tree/main/crates/common/src/enterprise/ai
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id001
      status: none
    slug: amazon-route-53
    status: profiled
    tags: &id002
    - Amazon Web Services
    - DNS
    - Domain Registration
    - Health Checks
    url: /providers/amazon-route-53/
  layer: common
  name: Amazon Route 53
  provider: amazon-route-53
  says: ships the Amazon Route 53 SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
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
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
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
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/anthropic.rs
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
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
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 36.7
    mcp: &id009
      status: none
    slug: bunny-net
    status: profiled
    tags: &id010
    - CDN
    - Edge
    - Storage
    - Video
    url: /providers/bunny-net/
  layer: common
  name: bunny.net
  provider: bunny-net
  says: ships the bunny.net SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id011
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id012
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: ships the Cloudflare SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id013
      status: none
    slug: desec
    status: profiled
    tags: &id014
    - Company
    - DNS
    - Open Source
    - Security
    url: /providers/desec/
  layer: common
  name: deSEC
  provider: desec
  says: ships the deSEC SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id015
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id016
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
  layer: common
  name: DigitalOcean
  provider: digital-ocean
  says: ships the DigitalOcean SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
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
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id017
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id018
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elasticsearch
  provider: elastic
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/tree/main/crates/store/src/backend/elastic
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id019
      status: none
    slug: gandi
    status: profiled
    tags: &id020
    - DNS
    - Domain Registrar
    - Domains
    - Email
    url: /providers/gandi/
  layer: common
  name: Gandi
  provider: gandi
  says: ships the Gandi SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: exemplar
    in_catalog: true
    kin_score: 69.9
    mcp: &id021
      status: none
    slug: google-cloud-dns
    status: profiled
    tags: &id022
    - DNS
    - Domain Names
    - Google Cloud
    - Name Resolution
    url: /providers/google-cloud-dns/
  layer: common
  name: Google Cloud DNS
  provider: google-cloud-dns
  says: ships the Google Cloud DNS SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
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
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id023
      status: none
    slug: google-gemini
    status: profiled
    tags: &id024
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/gemini.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id025
      status: none
    slug: hetzner
    status: profiled
    tags: &id026
    - Cloud Hosting
    - DNS
    - Infrastructure
    - Servers
    url: /providers/hetzner/
  layer: common
  name: Hetzner
  provider: hetzner
  says: ships the Hetzner SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id027
      source: https://github.com/linode/mcp-cluster-api
      status: verified
    slug: linode
    status: profiled
    tags: &id028
    - Cloud Computing
    - Infrastructure-as-a-Service
    - Kubernetes
    - Virtual Machines
    url: /providers/linode/
  layer: common
  name: Linode
  provider: linode
  says: ships the Linode SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
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
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id029
      source: https://github.com/meilisearch/meilisearch-mcp
      status: verified
    slug: meilisearch
    status: profiled
    tags: &id030
    - AI Search
    - Full-Text Search
    - Hybrid Search
    - Open Source
    url: /providers/meilisearch/
  layer: domain
  name: Meilisearch
  provider: meilisearch
  says: ships the Meilisearch SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/tree/main/crates/store/src/backend/meili
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
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id031
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/openai.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 43.2
    mcp: &id033
      source: https://mcp.eu.ovhcloud.com/mcp
      status: verified
    slug: ovh-cloud
    status: profiled
    tags: &id034
    - Cloud
    - Compute
    - Hosting
    - Servers
    url: /providers/ovh-cloud/
  layer: common
  name: OVHcloud
  provider: ovh-cloud
  says: ships the OVHcloud SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id035
      status: unchecked
    slug: porkbun
    status: queued for profiling
    tags: &id036 []
    url: null
  layer: common
  name: Porkbun
  provider: porkbun
  says: ships the Porkbun SDK or integration code
  source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
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
    mcp: &id037
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id038
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/stalwart-mail-server/
providers:
- agent_band: agent-ready
  agent_readiness: 35.6
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id001
  name: Amazon Route 53
  slug: amazon-route-53
  status: profiled
  tags: *id002
  url: /providers/amazon-route-53/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
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
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 36.7
  mcp: *id009
  name: bunny.net
  slug: bunny-net
  status: profiled
  tags: *id010
  url: /providers/bunny-net/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id011
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id012
  url: /providers/cloudflare/
- agent_band: human-only
  agent_readiness: 0.7
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id013
  name: deSEC
  slug: desec
  status: profiled
  tags: *id014
  url: /providers/desec/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id015
  name: DigitalOcean
  slug: digital-ocean
  status: profiled
  tags: *id016
  url: /providers/digital-ocean/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id017
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id018
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 18.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id019
  name: Gandi
  slug: gandi
  status: profiled
  tags: *id020
  url: /providers/gandi/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: exemplar
  in_catalog: true
  kin_score: 69.9
  mcp: *id021
  name: Google Cloud DNS
  slug: google-cloud-dns
  status: profiled
  tags: *id022
  url: /providers/google-cloud-dns/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id023
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id024
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id025
  name: Hetzner
  slug: hetzner
  status: profiled
  tags: *id026
  url: /providers/hetzner/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id027
  name: Linode
  slug: linode
  status: profiled
  tags: *id028
  url: /providers/linode/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id029
  name: Meilisearch
  slug: meilisearch
  status: profiled
  tags: *id030
  url: /providers/meilisearch/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id031
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id032
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id033
  name: OVHcloud
  slug: ovh-cloud
  status: profiled
  tags: *id034
  url: /providers/ovh-cloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id035
  name: Porkbun
  slug: porkbun
  status: queued for profiling
  tags: *id036
  url: null
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id037
  name: Redis
  slug: redis
  status: profiled
  tags: *id038
  url: /providers/redis/
siblings:
- name: FairEmail
  rows: 26
  url: /applications/email-client/fairemail/
- name: Mail-in-a-Box
  rows: 5
  url: /applications/email-client/mail-in-a-box/
- name: 'mailcow: dockerized'
  rows: 2
  url: /applications/email-client/mailcow-dockerized/
- name: Proton Mail (Android)
  rows: 3
  url: /applications/email-client/proton-mail-android/
- name: Roundcube Webmail
  rows: 11
  url: /applications/email-client/roundcube-webmail/
- name: Thunderbird for Android
  rows: 7
  url: /applications/email-client/thunderbird-for-android/
sitemap: true
title: 'Stalwart Mail Server: Email Client & Hosting reference app'
---
