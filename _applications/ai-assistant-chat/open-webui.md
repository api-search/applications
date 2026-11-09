---
app: Open WebUI
app_slug: open-webui
app_url: https://github.com/open-webui/open-webui
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: domain
  name: OCR & Document AI
  providers:
  - Azure AI Document Intelligence
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.60.30
  key: AE-110.60.30
  layer: domain
  name: Retrieval-Augmented Generation
  providers:
  - Bing Search
  - Brave Search
  - DuckDuckGo
  - Exa
  - Google Programmable Search
  - Jina AI
  - Kagi
  - Linkup
  - Mojeek
  - Ollama
  - Perplexity
  - SearchApi
  - SerpApi
  - Serper
  - Tavily
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.60.20
  key: AE-110.60.20
  layer: domain
  name: Vector Search
  providers:
  - Chroma
  - Milvus
  - Pinecone
  - Qdrant
  - Weaviate
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-100.10.30
  key: AE-100.10.30
  layer: agent
  name: Browser & Computer-Use Automation
  providers:
  - Firecrawl
  url: /capabilities/agent-tool-exposure/
  via_parent: Agent Tool Exposure
category:
  id: ai-assistant-chat
  name: AI Assistant & Chat
  url: /applications/ai-assistant-chat/
counts:
  declared: 0
  observed: 26
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
- route: source code
  url: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
- route: source code
  url: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
integrations:
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id001
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id002
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: domain
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id004
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: domain
  name: Azure AI Document Intelligence
  provider: microsoft-azure
  says: ships the Azure AI Document Intelligence SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
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
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id007
      status: none
    slug: microsoft-bing
    status: profiled
    tags: &id008
    - Image
    - Search
    - Video
    - Web Search
    url: /providers/microsoft-bing/
  layer: domain
  name: Bing Search
  provider: microsoft-bing
  says: ships the Bing Search SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id009
      source: https://github.com/brave/brave-search-mcp-server
      status: verified
    slug: brave-browser
    status: profiled
    tags: &id010
    - Browser
    - Chromium
    - Privacy
    - Search
    url: /providers/brave-browser/
  layer: domain
  name: Brave Search
  provider: brave-browser
  says: ships the Brave Search SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id011
      source: https://github.com/chroma-core/chroma-mcp
      status: verified
    slug: chroma
    status: profiled
    tags: &id012
    - AI-native
    - Apache 2.0
    - Artificial Intelligence
    - Cloud
    url: /providers/chroma/
  layer: domain
  name: Chroma
  provider: chroma
  says: ships the Chroma SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id013
      status: none
    slug: duckduckgo
    status: profiled
    tags: &id014
    - AI Chat
    - Browser
    - Privacy
    - Search
    url: /providers/duckduckgo/
  layer: domain
  name: DuckDuckGo
  provider: duckduckgo
  says: ships the DuckDuckGo SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.0
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id015
      source: https://github.com/exa-labs/exa-mcp-server
      status: verified
    slug: exa-ai
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Neural Search
    - Search
    - Web Search
    url: /providers/exa-ai/
  layer: domain
  name: Exa
  provider: exa-ai
  says: ships the Exa SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.10.30
    key: AE-100.10.30
    name: Browser & Computer-Use Automation
    url: /capabilities/agent-tool-exposure/
    via_parent: Agent Tool Exposure
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id017
      source: https://docs.firecrawl.dev/mcp-server
      status: verified
    slug: firecrawl
    status: profiled
    tags: &id018
    - Crawling
    - Data Extraction
    - URLs
    - Web Scraping
    url: /providers/firecrawl/
  layer: agent
  name: Firecrawl
  provider: firecrawl
  says: ships the Firecrawl SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
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
    mcp: &id019
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id020
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 51.1
    mcp: &id021
      status: none
    slug: google-custom-search
    status: profiled
    tags: &id022
    - Custom Search
    - Google
    - Image Search
    - Search
    url: /providers/google-custom-search/
  layer: domain
  name: Google Programmable Search
  provider: google-custom-search
  says: ships the Google Programmable Search SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id023
      source: https://github.com/jina-ai/MCP
      status: verified
    slug: jina-ai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Embeddings
    - Machine Learning
    - Reranking
    url: /providers/jina-ai/
  layer: domain
  name: Jina AI
  provider: jina-ai
  says: ships the Jina AI SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id025
      source: https://github.com/kagisearch/kagimcp
      status: verified
    slug: kagi
    status: profiled
    tags: &id026
    - AI Search
    - Premium Search
    - Search
    - Summarization
    url: /providers/kagi/
  layer: domain
  name: Kagi
  provider: kagi
  says: ships the Kagi SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id027
      status: unchecked
    slug: linkup
    status: queued for profiling
    tags: &id028 []
    url: null
  layer: domain
  name: Linkup
  provider: linkup
  says: ships the Linkup SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id029
      source: https://github.com/zilliztech/mcp-server-milvus
      status: verified
    slug: milvus
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - Embeddings
    - Open Source
    - Vector Search
    url: /providers/milvus/
  layer: domain
  name: Milvus
  provider: milvus
  says: ships the Milvus SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 21.8
    mcp: &id031
      source: https://github.com/Mojeek/mojeek-search-mcp
      status: verified
    slug: mojeek
    status: profiled
    tags: &id032
    - Community
    - Open Source
    - Privacy
    - Search
    url: /providers/mojeek/
  layer: domain
  name: Mojeek
  provider: mojeek
  says: ships the Mojeek SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id033
      status: none
    slug: ollama
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: domain
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id035
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 67.7
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id037
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id038
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
  layer: domain
  name: Perplexity
  provider: perplexity
  says: ships the Perplexity SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 61.2
    mcp: &id039
      source: https://github.com/pinecone-io/pinecone-mcp
      status: verified
    slug: pinecone
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Embeddings
    - RAG
    - Vector Search
    url: /providers/pinecone/
  layer: domain
  name: Pinecone
  provider: pinecone
  says: ships the Pinecone SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id041
      source: https://github.com/qdrant/mcp-server-qdrant
      status: verified
    slug: qdrant
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Database
    - Vector Search
    url: /providers/qdrant/
  layer: domain
  name: Qdrant
  provider: qdrant
  says: ships the Qdrant SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.2
    band: strong
    in_catalog: true
    kin_score: 57.8
    mcp: &id043
      source: https://github.com/SearchApi/searchapi-mcp
      status: verified
    slug: searchapi
    status: profiled
    tags: &id044
    - Google Search
    - SERP
    - Search
    - Web Scraping
    url: /providers/searchapi/
  layer: domain
  name: SearchApi
  provider: searchapi
  says: ships the SearchApi SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id045
      source: https://github.com/serpapi/serpapi-mcp
      status: verified
    slug: serpapi
    status: profiled
    tags: &id046
    - Bing
    - Google
    - Search
    - Search Engines
    url: /providers/serpapi/
  layer: domain
  name: SerpApi
  provider: serpapi
  says: ships the SerpApi SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: strong
    in_catalog: true
    kin_score: 56.5
    mcp: &id047
      status: none
    slug: serper
    status: profiled
    tags: &id048
    - Artificial Intelligence
    - Google Search
    - SERP
    - Search
    url: /providers/serper/
  layer: domain
  name: Serper
  provider: serper
  says: ships the Serper SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.2
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id049
      source: https://github.com/tavily-ai/tavily-mcp
      status: verified
    slug: tavily
    status: profiled
    tags: &id050
    - AI Agents
    - LLM
    - Search
    - Web Search
    url: /providers/tavily/
  layer: domain
  name: Tavily
  provider: tavily
  says: ships the Tavily SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id051
      source: https://github.com/weaviate/mcp-server-weaviate
      status: verified
    slug: weaviate
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Machine Learning
    - Semantic Search
    - Vector Search
    url: /providers/weaviate/
  layer: domain
  name: Weaviate
  provider: weaviate
  says: ships the Weaviate SDK or integration code
  source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ai-assistant-chat/open-webui/
providers:
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id001
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 51.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id003
  name: Azure AI Document Intelligence
  slug: microsoft-azure
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id007
  name: Bing Search
  slug: microsoft-bing
  status: profiled
  tags: *id008
  url: /providers/microsoft-bing/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id009
  name: Brave Search
  slug: brave-browser
  status: profiled
  tags: *id010
  url: /providers/brave-browser/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id011
  name: Chroma
  slug: chroma
  status: profiled
  tags: *id012
  url: /providers/chroma/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id013
  name: DuckDuckGo
  slug: duckduckgo
  status: profiled
  tags: *id014
  url: /providers/duckduckgo/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id015
  name: Exa
  slug: exa-ai
  status: profiled
  tags: *id016
  url: /providers/exa-ai/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id017
  name: Firecrawl
  slug: firecrawl
  status: profiled
  tags: *id018
  url: /providers/firecrawl/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id019
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id020
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id021
  name: Google Programmable Search
  slug: google-custom-search
  status: profiled
  tags: *id022
  url: /providers/google-custom-search/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id023
  name: Jina AI
  slug: jina-ai
  status: profiled
  tags: *id024
  url: /providers/jina-ai/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id025
  name: Kagi
  slug: kagi
  status: profiled
  tags: *id026
  url: /providers/kagi/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id027
  name: Linkup
  slug: linkup
  status: queued for profiling
  tags: *id028
  url: null
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id029
  name: Milvus
  slug: milvus
  status: profiled
  tags: *id030
  url: /providers/milvus/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 21.8
  mcp: *id031
  name: Mojeek
  slug: mojeek
  status: profiled
  tags: *id032
  url: /providers/mojeek/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id033
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id034
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id035
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id036
  url: /providers/openai/
- agent_band: agent-native
  agent_readiness: 67.7
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id037
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id038
  url: /providers/perplexity/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 61.2
  mcp: *id039
  name: Pinecone
  slug: pinecone
  status: profiled
  tags: *id040
  url: /providers/pinecone/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id041
  name: Qdrant
  slug: qdrant
  status: profiled
  tags: *id042
  url: /providers/qdrant/
- agent_band: agent-native
  agent_readiness: 60.2
  band: strong
  in_catalog: true
  kin_score: 57.8
  mcp: *id043
  name: SearchApi
  slug: searchapi
  status: profiled
  tags: *id044
  url: /providers/searchapi/
- agent_band: agent-native
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id045
  name: SerpApi
  slug: serpapi
  status: profiled
  tags: *id046
  url: /providers/serpapi/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: strong
  in_catalog: true
  kin_score: 56.5
  mcp: *id047
  name: Serper
  slug: serper
  status: profiled
  tags: *id048
  url: /providers/serper/
- agent_band: agent-ready
  agent_readiness: 46.2
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id049
  name: Tavily
  slug: tavily
  status: profiled
  tags: *id050
  url: /providers/tavily/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id051
  name: Weaviate
  slug: weaviate
  status: profiled
  tags: *id052
  url: /providers/weaviate/
siblings:
- name: AnythingLLM
  rows: 43
  url: /applications/ai-assistant-chat/anythingllm/
- name: ChatGPT
  rows: 2
  url: /applications/ai-assistant-chat/chatgpt/
- name: Claude
  rows: 2
  url: /applications/ai-assistant-chat/claude/
- name: Le Chat (Mistral)
  rows: 1
  url: /applications/ai-assistant-chat/le-chat-mistral/
- name: LibreChat
  rows: 39
  url: /applications/ai-assistant-chat/librechat/
- name: LobeChat
  rows: 48
  url: /applications/ai-assistant-chat/lobechat/
- name: Perplexity
  rows: 3
  url: /applications/ai-assistant-chat/perplexity/
sitemap: true
title: 'Open WebUI: AI Assistant & Chat reference app'
---
