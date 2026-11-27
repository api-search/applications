---
app: Typesense
app_slug: typesense
app_url: https://github.com/typesense/typesense
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Azure OpenAI
  - Google (Gemini API)
  - Google Cloud Vertex AI
  - OpenAI
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Cloudflare Workers AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: search-engine
  name: Site & App Search
  url: /applications/search-engine/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: source code
  url: https://github.com/typesense/typesense/blob/HEAD/src/conversation_model.cpp
- route: source code
  url: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    agent_readiness: 29.9
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id001
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: domain
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id003
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id004
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: domain
  name: Cloudflare Workers AI
  provider: cloudflare
  says: ships the Cloudflare Workers AI SDK or integration code
  source: https://github.com/typesense/typesense/blob/HEAD/src/conversation_model.cpp
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
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id005
      status: none
    slug: google-gemini
    status: profiled
    tags: &id006
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: domain
  name: Google (Gemini API)
  provider: google-gemini
  says: ships the Google (Gemini API) SDK or integration code
  source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    agent_band: agent-ready
    agent_readiness: 42.2
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id007
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: domain
  name: Google Cloud Vertex AI
  provider: google-vertex-ai
  says: ships the Google Cloud Vertex AI SDK or integration code
  source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id009
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/typesense/
providers:
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id001
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id002
  url: /providers/microsoft-azure-openai/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id003
  name: Cloudflare Workers AI
  slug: cloudflare
  status: profiled
  tags: *id004
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id005
  name: Google (Gemini API)
  slug: google-gemini
  status: profiled
  tags: *id006
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id007
  name: Google Cloud Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id008
  url: /providers/google-vertex-ai/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id009
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id010
  url: /providers/openai/
siblings:
- name: Algolia
  rows: 7
  url: /applications/search-engine/algolia/
- name: Elasticsearch
  rows: 26
  url: /applications/search-engine/elasticsearch/
- name: Meilisearch
  rows: 4
  url: /applications/search-engine/meilisearch/
- name: OpenSearch
  rows: 23
  url: /applications/search-engine/opensearch/
- name: Quickwit
  rows: 8
  url: /applications/search-engine/quickwit/
- name: SearXNG
  rows: 49
  url: /applications/search-engine/searxng/
sitemap: true
title: 'Typesense: Site & App Search reference app'
---
