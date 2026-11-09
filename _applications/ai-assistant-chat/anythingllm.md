---
app: AnythingLLM
app_slug: anythingllm
app_url: https://github.com/Mintplex-Labs/anything-llm
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Voyage AI
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Anthropic
  - Azure OpenAI
  - Cerebras
  - Cohere
  - DeepSeek
  - Fireworks AI
  - Google Gemini
  - Groq
  - Mistral AI
  - Moonshot AI
  - Novita AI
  - NVIDIA NIM
  - Ollama
  - OpenAI
  - Perplexity
  - SambaNova
  - Together AI
  - Vertex AI
  - xAI
  - Zhipu AI (Z.ai)
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: domain
  name: Model Routing & Gateways
  providers:
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.60.30
  key: AE-110.60.30
  layer: domain
  name: Retrieval-Augmented Generation
  providers:
  - Bing Search
  - Exa
  - Google Programmable Search
  - Keenable
  - SearchApi
  - SerpApi
  - Serper
  - Tavily
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.30.20
  key: AE-110.30.20
  layer: domain
  name: Text-to-Speech
  providers:
  - ElevenLabs
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-110.60.20
  key: AE-110.60.20
  layer: domain
  name: Vector Search
  providers:
  - Chroma
  - DataStax Astra DB
  - LanceDB
  - Milvus
  - Pinecone
  - Qdrant
  - Weaviate
  - Zilliz
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
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
  observed: 43
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
- route: source code
  url: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: domain
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: domain
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: domain
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_band: agent-aware
    agent_readiness: 28.0
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id009
      status: none
    slug: cerebras-systems
    status: profiled
    tags: &id010
    - AI Infrastructure
    - Artificial Intelligence
    - Company
    - Machine Learning
    url: /providers/cerebras-systems/
  layer: domain
  name: Cerebras
  provider: cerebras-systems
  says: ships the Cerebras SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_readiness: 41.4
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id013
      status: none
    slug: cohere
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: domain
  name: Cohere
  provider: cohere
  says: ships the Cohere SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 23.6
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id015
      source: https://github.com/datastax/astra-db-mcp
      status: verified
    slug: datastax
    status: profiled
    tags: &id016
    - Company
    - Database
    - Enterprise
    - Vector Search
    url: /providers/datastax/
  layer: domain
  name: DataStax Astra DB
  provider: datastax
  says: ships the DataStax Astra DB SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id017
      status: none
    slug: deepseek
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: domain
  name: DeepSeek
  provider: deepseek
  says: ships the DeepSeek SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 83.0
    mcp: &id019
      source: https://github.com/elevenlabs/elevenlabs-mcp
      status: verified
    slug: elevenlabs
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Voice
    url: /providers/elevenlabs/
  layer: domain
  name: ElevenLabs
  provider: elevenlabs
  says: ships the ElevenLabs SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    mcp: &id021
      source: https://github.com/exa-labs/exa-mcp-server
      status: verified
    slug: exa-ai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Neural Search
    - Search
    - Web Search
    url: /providers/exa-ai/
  layer: domain
  name: Exa
  provider: exa-ai
  says: ships the Exa SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id023
      source: https://docs.firecrawl.dev/mcp-server
      status: verified
    slug: firecrawl
    status: profiled
    tags: &id024
    - Crawling
    - Data Extraction
    - URLs
    - Web Scraping
    url: /providers/firecrawl/
  layer: agent
  name: Firecrawl
  provider: firecrawl
  says: ships the Firecrawl SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 39.4
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id025
      source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
      status: verified
    slug: fireworks-ai
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Inference
    - LLM
    - Multi-Modal
    url: /providers/fireworks-ai/
  layer: domain
  name: Fireworks AI
  provider: fireworks-ai
  says: ships the Fireworks AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id027
      status: none
    slug: google-gemini
    status: profiled
    tags: &id028
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: domain
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id029
      status: none
    slug: google-custom-search
    status: profiled
    tags: &id030
    - Custom Search
    - Google
    - Image Search
    - Search
    url: /providers/google-custom-search/
  layer: domain
  name: Google Programmable Search
  provider: google-custom-search
  says: ships the Google Programmable Search SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id031
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
  layer: domain
  name: Groq
  provider: groq
  says: ships the Groq SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 37.7
    band: developing
    in_catalog: true
    kin_score: 53.7
    mcp: &id033
      source: https://docs.keenable.ai/mcp
      status: verified
    slug: keenable
    status: profiled
    tags: &id034
    - AI Agents
    - AI Labs
    - Inference Platforms
    - Web Search
    url: /providers/keenable/
  layer: domain
  name: Keenable
  provider: keenable
  says: ships the Keenable SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 24.1
    band: developing
    in_catalog: true
    kin_score: 41.5
    mcp: &id035
      source: https://github.com/lancedb/lancedb-mcp-server
      status: verified
    slug: lancedb
    status: profiled
    tags: &id036
    - Lakehouse
    - Lance Format
    - Multi-Modal
    - Vector Search
    url: /providers/lancedb/
  layer: domain
  name: LanceDB
  provider: lancedb
  says: ships the LanceDB SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    mcp: &id037
      source: https://github.com/zilliztech/mcp-server-milvus
      status: verified
    slug: milvus
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - Embeddings
    - Open Source
    - Vector Search
    url: /providers/milvus/
  layer: domain
  name: Milvus
  provider: milvus
  says: ships the Milvus SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id039
      status: none
    slug: mistral
    status: profiled
    tags: &id040
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: domain
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 36.8
    band: strong
    in_catalog: true
    kin_score: 56.6
    mcp: &id041
      status: unchecked
    slug: kimi-ai
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Inference
    - LLM
    - Long Context
    url: /providers/kimi-ai/
  layer: domain
  name: Moonshot AI
  provider: kimi-ai
  says: ships the Moonshot AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 35.9
    band: developing
    in_catalog: true
    kin_score: 52.6
    mcp: &id043
      source: https://github.com/novitalabs/novita-mcp-server
      status: verified
    slug: novita-ai
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - GPU
    - Inference
    - LLM
    url: /providers/novita-ai/
  layer: domain
  name: Novita AI
  provider: novita-ai
  says: ships the Novita AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_band: agent-aware
    agent_readiness: 26.9
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id045
      status: none
    slug: nvidia-nim
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Inference
    - LLM
    - Microservices
    url: /providers/nvidia-nim/
  layer: domain
  name: NVIDIA NIM
  provider: nvidia-nim
  says: ships the NVIDIA NIM SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id047
      status: none
    slug: ollama
    status: profiled
    tags: &id048
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: domain
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    mcp: &id049
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id051
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: domain
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 67.7
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id053
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id054
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
  layer: domain
  name: Perplexity
  provider: perplexity
  says: ships the Perplexity SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id055
      source: https://github.com/pinecone-io/pinecone-mcp
      status: verified
    slug: pinecone
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - Embeddings
    - RAG
    - Vector Search
    url: /providers/pinecone/
  layer: domain
  name: Pinecone
  provider: pinecone
  says: ships the Pinecone SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_band: agent-ready
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id057
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id058
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    mcp: &id059
      source: https://github.com/qdrant/mcp-server-qdrant
      status: verified
    slug: qdrant
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Database
    - Vector Search
    url: /providers/qdrant/
  layer: domain
  name: Qdrant
  provider: qdrant
  says: ships the Qdrant SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id061
      status: none
    slug: sambanova-systems
    status: profiled
    tags: &id062
    - Artificial Intelligence
    - Company
    - LLM
    - Machine Learning
    url: /providers/sambanova-systems/
  layer: domain
  name: SambaNova
  provider: sambanova-systems
  says: ships the SambaNova SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id063
      source: https://github.com/SearchApi/searchapi-mcp
      status: verified
    slug: searchapi
    status: profiled
    tags: &id064
    - Google Search
    - SERP
    - Search
    - Web Scraping
    url: /providers/searchapi/
  layer: domain
  name: SearchApi
  provider: searchapi
  says: ships the SearchApi SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id065
      source: https://github.com/serpapi/serpapi-mcp
      status: verified
    slug: serpapi
    status: profiled
    tags: &id066
    - Bing
    - Google
    - Search
    - Search Engines
    url: /providers/serpapi/
  layer: domain
  name: SerpApi
  provider: serpapi
  says: ships the SerpApi SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id067
      status: none
    slug: serper
    status: profiled
    tags: &id068
    - Artificial Intelligence
    - Google Search
    - SERP
    - Search
    url: /providers/serper/
  layer: domain
  name: Serper
  provider: serper
  says: ships the Serper SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id069
      source: https://github.com/tavily-ai/tavily-mcp
      status: verified
    slug: tavily
    status: profiled
    tags: &id070
    - AI Agents
    - LLM
    - Search
    - Web Search
    url: /providers/tavily/
  layer: domain
  name: Tavily
  provider: tavily
  says: ships the Tavily SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id071
      status: none
    slug: telegram
    status: profiled
    tags: &id072
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_readiness: 40.4
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id073
      source: https://docs.together.ai/docs/mcp
      status: verified
    slug: together-ai
    status: profiled
    tags: &id074
    - Artificial Intelligence
    - Foundation Models
    - Inference
    - LLM
    url: /providers/together-ai/
  layer: domain
  name: Together AI
  provider: together-ai
  says: ships the Together AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id075
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id076
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: domain
  name: Vertex AI
  provider: google-vertex-ai
  says: ships the Vertex AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 16.1
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id077
      status: none
    slug: voyage-ai
    status: profiled
    tags: &id078
    - Embeddings
    - RAG
    - Rerankers
    - Semantic Search
    url: /providers/voyage-ai/
  layer: domain
  name: Voyage AI
  provider: voyage-ai
  says: ships the Voyage AI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    mcp: &id079
      source: https://github.com/weaviate/mcp-server-weaviate
      status: verified
    slug: weaviate
    status: profiled
    tags: &id080
    - Artificial Intelligence
    - Machine Learning
    - Semantic Search
    - Vector Search
    url: /providers/weaviate/
  layer: domain
  name: Weaviate
  provider: weaviate
  says: ships the Weaviate SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
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
    agent_readiness: 38.8
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id081
      status: none
    slug: xai
    status: profiled
    tags: &id082
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
  layer: domain
  name: xAI
  provider: xai
  says: ships the xAI SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id083
      source: https://docs.z.ai/devpack/mcp/vision-mcp-server
      status: verified
    slug: zhipu-ai
    status: profiled
    tags: &id084
    - Artificial Intelligence
    - GLM
    - Inference
    - LLM
    url: /providers/zhipu-ai/
  layer: domain
  name: Zhipu AI (Z.ai)
  provider: zhipu-ai
  says: ships the Zhipu AI (Z.ai) SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
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
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id085
      source: https://github.com/zilliztech/zilliz-mcp-server
      status: verified
    slug: zilliz
    status: profiled
    tags: &id086
    - Artificial Intelligence
    - Cloud
    - Milvus
    - Vector Search
    url: /providers/zilliz/
  layer: domain
  name: Zilliz
  provider: zilliz
  says: ships the Zilliz SDK or integration code
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ai-assistant-chat/anythingllm/
providers:
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id001
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id002
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id005
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-openai/
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
  agent_readiness: 28.0
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id009
  name: Cerebras
  slug: cerebras-systems
  status: profiled
  tags: *id010
  url: /providers/cerebras-systems/
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
- agent_band: agent-ready
  agent_readiness: 41.4
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id013
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id014
  url: /providers/cohere/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id015
  name: DataStax Astra DB
  slug: datastax
  status: profiled
  tags: *id016
  url: /providers/datastax/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id017
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id018
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 83.0
  mcp: *id019
  name: ElevenLabs
  slug: elevenlabs
  status: profiled
  tags: *id020
  url: /providers/elevenlabs/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id021
  name: Exa
  slug: exa-ai
  status: profiled
  tags: *id022
  url: /providers/exa-ai/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id023
  name: Firecrawl
  slug: firecrawl
  status: profiled
  tags: *id024
  url: /providers/firecrawl/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id025
  name: Fireworks AI
  slug: fireworks-ai
  status: profiled
  tags: *id026
  url: /providers/fireworks-ai/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id027
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id028
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id029
  name: Google Programmable Search
  slug: google-custom-search
  status: profiled
  tags: *id030
  url: /providers/google-custom-search/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id031
  name: Groq
  slug: groq
  status: profiled
  tags: *id032
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id033
  name: Keenable
  slug: keenable
  status: profiled
  tags: *id034
  url: /providers/keenable/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: developing
  in_catalog: true
  kin_score: 41.5
  mcp: *id035
  name: LanceDB
  slug: lancedb
  status: profiled
  tags: *id036
  url: /providers/lancedb/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id037
  name: Milvus
  slug: milvus
  status: profiled
  tags: *id038
  url: /providers/milvus/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id039
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id040
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 36.8
  band: strong
  in_catalog: true
  kin_score: 56.6
  mcp: *id041
  name: Moonshot AI
  slug: kimi-ai
  status: profiled
  tags: *id042
  url: /providers/kimi-ai/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: developing
  in_catalog: true
  kin_score: 52.6
  mcp: *id043
  name: Novita AI
  slug: novita-ai
  status: profiled
  tags: *id044
  url: /providers/novita-ai/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id045
  name: NVIDIA NIM
  slug: nvidia-nim
  status: profiled
  tags: *id046
  url: /providers/nvidia-nim/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id047
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id048
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id049
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id050
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id051
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id052
  url: /providers/openrouter/
- agent_band: agent-native
  agent_readiness: 67.7
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id053
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id054
  url: /providers/perplexity/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 61.2
  mcp: *id055
  name: Pinecone
  slug: pinecone
  status: profiled
  tags: *id056
  url: /providers/pinecone/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id057
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id058
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id059
  name: Qdrant
  slug: qdrant
  status: profiled
  tags: *id060
  url: /providers/qdrant/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id061
  name: SambaNova
  slug: sambanova-systems
  status: profiled
  tags: *id062
  url: /providers/sambanova-systems/
- agent_band: agent-native
  agent_readiness: 60.2
  band: strong
  in_catalog: true
  kin_score: 57.8
  mcp: *id063
  name: SearchApi
  slug: searchapi
  status: profiled
  tags: *id064
  url: /providers/searchapi/
- agent_band: agent-native
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id065
  name: SerpApi
  slug: serpapi
  status: profiled
  tags: *id066
  url: /providers/serpapi/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: strong
  in_catalog: true
  kin_score: 56.5
  mcp: *id067
  name: Serper
  slug: serper
  status: profiled
  tags: *id068
  url: /providers/serper/
- agent_band: agent-ready
  agent_readiness: 46.2
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id069
  name: Tavily
  slug: tavily
  status: profiled
  tags: *id070
  url: /providers/tavily/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id071
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id072
  url: /providers/telegram/
- agent_band: agent-ready
  agent_readiness: 40.4
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id073
  name: Together AI
  slug: together-ai
  status: profiled
  tags: *id074
  url: /providers/together-ai/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id075
  name: Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id076
  url: /providers/google-vertex-ai/
- agent_band: agent-aware
  agent_readiness: 16.1
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id077
  name: Voyage AI
  slug: voyage-ai
  status: profiled
  tags: *id078
  url: /providers/voyage-ai/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id079
  name: Weaviate
  slug: weaviate
  status: profiled
  tags: *id080
  url: /providers/weaviate/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id081
  name: xAI
  slug: xai
  status: profiled
  tags: *id082
  url: /providers/xai/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id083
  name: Zhipu AI (Z.ai)
  slug: zhipu-ai
  status: profiled
  tags: *id084
  url: /providers/zhipu-ai/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id085
  name: Zilliz
  slug: zilliz
  status: profiled
  tags: *id086
  url: /providers/zilliz/
siblings:
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
- name: Open WebUI
  rows: 26
  url: /applications/ai-assistant-chat/open-webui/
- name: Perplexity
  rows: 3
  url: /applications/ai-assistant-chat/perplexity/
sitemap: true
title: 'AnythingLLM: AI Assistant & Chat reference app'
---
