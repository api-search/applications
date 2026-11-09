---
app: Meilisearch
app_slug: meilisearch
app_url: https://github.com/meilisearch/meilisearch
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Hugging Face
  - Ollama
  - OpenAI
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Twilio Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: search-engine
  name: Site & App Search
  url: /applications/search-engine/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/Cargo.toml
- route: source code
  url: https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/src/analytics/segment_analytics.rs
- route: source code
  url: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id001
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id002
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
  layer: domain
  name: Hugging Face
  provider: hugging-face
  says: ships the Hugging Face SDK or integration code
  source: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id003
      status: none
    slug: ollama
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: domain
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id005
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id007
      status: none
    slug: segment
    status: profiled
    tags: &id008
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/src/analytics/segment_analytics.rs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/meilisearch/
providers:
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id001
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id002
  url: /providers/hugging-face/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id003
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id004
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id005
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id006
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id007
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id008
  url: /providers/segment/
siblings:
- name: Algolia
  rows: 7
  url: /applications/search-engine/algolia/
- name: Elasticsearch
  rows: 26
  url: /applications/search-engine/elasticsearch/
- name: OpenSearch
  rows: 23
  url: /applications/search-engine/opensearch/
- name: Quickwit
  rows: 8
  url: /applications/search-engine/quickwit/
- name: SearXNG
  rows: 49
  url: /applications/search-engine/searxng/
- name: Typesense
  rows: 5
  url: /applications/search-engine/typesense/
sitemap: true
title: 'Meilisearch: Site & App Search reference app'
---
