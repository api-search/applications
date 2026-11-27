---
access: understanding
agent_layer:
- app: Open WebUI
  finding: 'MCP client: mcp Python SDK in core dependencies; connects to external MCP tool servers'
  source: https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
  tier: observed
- app: LibreChat
  finding: MCP client (@modelcontextprotocol/sdk) plus its own agents runtime (@librechat/agents)
  source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
  tier: observed
- app: LobeChat
  finding: MCP client (@modelcontextprotocol/sdk), a skill/plugin market SDK, cloud sandbox and Claude Code tools
  source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
  tier: observed
- app: AnythingLLM
  finding: MCP client (@modelcontextprotocol/sdk) with agent skills and web-search tools
  source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
  tier: observed
apps:
- anchor: open-webui
  counts:
    declared: 0
    observed: 26
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
    layer: domain
    name: Weaviate
    provider: weaviate
    says: ships the Weaviate SDK or integration code
    source: https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
    tier: observed
  kind: self-hosted
  name: Open WebUI
  page: /applications/ai-assistant-chat/open-webui/
  slug: open-webui
  url: https://github.com/open-webui/open-webui
- anchor: librechat
  counts:
    declared: 0
    observed: 39
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
  - route: source code
    url: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Anyscale
    provider: anyscale
    says: ships the Anyscale SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: APIpie
    provider: apipie
    says: ships the APIpie SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: ships the Apple SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: Black Forest Labs (Flux)
    provider: black-forest-labs
    says: ships the Black Forest Labs (Flux) SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Cohere
    provider: cohere
    says: ships the Cohere SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: DeepSeek
    provider: deepseek
    says: ships the DeepSeek SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10.30
      key: AE-100.10.30
      name: Browser & Computer-Use Automation
      url: /capabilities/agent-tool-exposure/
      via_parent: Agent Tool Exposure
    credit: null
    layer: agent
    name: Firecrawl
    provider: firecrawl
    says: ships the Firecrawl SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Fireworks AI
    provider: fireworks-ai
    says: ships the Fireworks AI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Google Custom Search
    provider: google-custom-search
    says: ships the Google Custom Search SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Hugging Face
    provider: hugging-face
    says: ships the Hugging Face SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Jina AI
    provider: jina-ai
    says: ships the Jina AI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Keenable
    provider: keenable
    says: ships the Keenable SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    credit: null
    layer: agent
    name: Langfuse
    provider: langfuse
    says: ships the Langfuse SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    credit: null
    layer: domain
    name: OpenWeather
    provider: openweathermap
    says: ships the OpenWeather SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Perplexity
    provider: perplexity
    says: ships the Perplexity SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Serper
    provider: serper
    says: ships the Serper SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: ShuttleAI
    provider: shuttleai
    says: ships the ShuttleAI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Tavily
    provider: tavily
    says: ships the Tavily SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Together AI
    provider: together-ai
    says: ships the Together AI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Vertex AI (Anthropic on Vertex)
    provider: google-vertex-ai
    says: ships the Vertex AI (Anthropic on Vertex) SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: xAI
    provider: xai
    says: ships the xAI SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: Zapier
    provider: zapier
    says: ships the Zapier SDK or integration code
    source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
    tier: observed
  kind: self-hosted
  name: LibreChat
  page: /applications/ai-assistant-chat/librechat/
  slug: librechat
  url: https://github.com/danny-avila/LibreChat
- anchor: lobechat
  counts:
    declared: 0
    observed: 48
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
  - route: source code
    url: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: AI21 Labs
    provider: ai21-labs
    says: ships the AI21 Labs SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Azure AI Foundry
    provider: azure-ai-foundry
    says: ships the Azure AI Foundry SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Baidu (ERNIE)
    provider: baidu
    says: ships the Baidu (ERNIE) SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: Black Forest Labs
    provider: black-forest-labs
    says: ships the Black Forest Labs SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Cerebras
    provider: cerebras-systems
    says: ships the Cerebras SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Cloudflare Workers AI
    provider: cloudflare
    says: ships the Cloudflare Workers AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Cohere
    provider: cohere
    says: ships the Cohere SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: Composio
    provider: composio
    says: ships the Composio SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: DeepSeek
    provider: deepseek
    says: ships the DeepSeek SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: fal
    provider: fal-ai
    says: ships the fal SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Fireworks AI
    provider: fireworks-ai
    says: ships the Fireworks AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Hugging Face
    provider: hugging-face
    says: ships the Hugging Face SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Jina AI
    provider: jina-ai
    says: ships the Jina AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    credit: null
    layer: agent
    name: Langfuse
    provider: langfuse
    says: ships the Langfuse SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: MiniMax
    provider: minimax-ai
    says: ships the MiniMax SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Moonshot AI
    provider: kimi-ai
    says: ships the Moonshot AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Neon
    provider: neon
    says: ships the Neon SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Novita AI
    provider: novita-ai
    says: ships the Novita AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: NVIDIA NIM
    provider: nvidia-nim
    says: ships the NVIDIA NIM SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Perplexity
    provider: perplexity
    says: ships the Perplexity SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Qwen
    provider: qwen
    says: ships the Qwen SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: Replicate
    provider: replicate
    says: ships the Replicate SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: SambaNova
    provider: sambanova-systems
    says: ships the SambaNova SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: SiliconFlow
    provider: siliconflow
    says: ships the SiliconFlow SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: StepFun
    provider: stepfun
    says: ships the StepFun SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.80.30
      key: BC-4270.80.30
      name: Webhook Delivery Reliability Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: Webhook & Event Subscription Management
    credit: null
    layer: common
    name: Svix
    provider: svix
    says: ships the Svix SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Together AI
    provider: together-ai
    says: ships the Together AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Upstage
    provider: upstage
    says: ships the Upstage SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Upstash
    provider: upstash
    says: ships the Upstash SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Vercel
    provider: vercel
    says: ships the Vercel SDK or integration code
    source: https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Vertex AI
    provider: google-vertex-ai
    says: ships the Vertex AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Volcengine (ByteDance cloud)
    provider: volcengine
    says: ships the Volcengine (ByteDance cloud) SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: xAI
    provider: xai
    says: ships the xAI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Zhipu AI
    provider: zhipu-ai
    says: ships the Zhipu AI SDK or integration code
    source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
    tier: observed
  kind: open-source-saas
  name: LobeChat
  page: /applications/ai-assistant-chat/lobechat/
  slug: lobechat
  url: https://github.com/lobehub/lobe-chat
- anchor: anythingllm
  counts:
    declared: 0
    observed: 43
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
    layer: domain
    name: Zilliz
    provider: zilliz
    says: ships the Zilliz SDK or integration code
    source: https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
    tier: observed
  kind: self-hosted
  name: AnythingLLM
  page: /applications/ai-assistant-chat/anythingllm/
  slug: anythingllm
  url: https://github.com/Mintplex-Labs/anything-llm
- anchor: chatgpt
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.openai.chatgpt/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.openai.chatgpt/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.openai.chatgpt/latest/
    tier: observed
  kind: commercial
  name: ChatGPT
  page: /applications/ai-assistant-chat/chatgpt/
  slug: chatgpt
  url: https://chatgpt.com/
- anchor: claude
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.anthropic.claude/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.anthropic.claude/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.anthropic.claude/latest/
    tier: observed
  kind: commercial
  name: Claude
  page: /applications/ai-assistant-chat/claude/
  slug: claude
  url: https://claude.ai/
- anchor: perplexity
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
    tier: observed
  kind: commercial
  name: Perplexity
  page: /applications/ai-assistant-chat/perplexity/
  slug: perplexity
  url: https://www.perplexity.ai/
- anchor: le-chat-(mistral)
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/ai.mistral.chat/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ai.mistral.chat/latest/
    tier: observed
  kind: commercial
  name: Le Chat (Mistral)
  page: /applications/ai-assistant-chat/le-chat-mistral/
  slug: le-chat-mistral
  url: https://chat.mistral.ai/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: ai-assistant-chat
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Generative Artificial Intelligence (GenAI)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#generative-artificial-intelligence-genai
- category: Productivity
  store: slack-marketplace
  url: https://slack.com/apps
- category: AI Tools
  store: zapier
  url: https://zapier.com/apps
name: AI Assistant & Chat
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: the chat app is a front end over hosted model APIs; every reference app ships multi-vendor LLM connectors [AE id AE-110.10.10; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: aggregators (OpenRouter) let a chat app reach many models through one key [AE id AE-110.10.30; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.10
    key: AE-110.20.10
    name: Image Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  fit: exact
  layer: domain
  why: image tools inside the chat (Flux, fal, Replicate) [AE id AE-110.20.10; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: voice replies [AE id AE-110.30.20; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: document extraction for uploaded files [AE id AE-110.40.20; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: domain
  why: embedding engines for chat-with-your-documents [AE id AE-110.60.10; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: domain
  why: vector stores behind RAG / knowledge bases [AE id AE-110.60.20; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: domain
  why: web-search grounding APIs; no web-search node exists, RAG is the nearest [AE id AE-110.60.30; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: agent
  why: page scraping / crawl tools the assistant calls [AE id AE-100.10.30; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-100.10
    key: AE-100.10
    name: Agent Tool Exposure
    url: /capabilities/agent-tool-exposure/
    via_parent: null
  fit: exact
  layer: agent
  why: third-party tool catalogs the assistant calls (Composio, Zapier NLA) [AE id AE-100.10; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: API Evangelist extension
    id: AE-100.60.20
    key: AE-100.60.20
    name: Agent Observability
    url: /capabilities/agent-quality-operations/
    via_parent: Agent Quality & Operations
  fit: exact
  layer: agent
  why: LLM tracing (Langfuse) [AE id AE-100.60.20; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash / error reporting
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics / telemetry
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution in the mobile app
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: file uploads to object storage; no object-storage capability
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in strategies [AE id AE-160.10.30; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: paid plans
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: verification / password email [AE id AE-150.10.10; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: Turbo EA
    id: BC-4270.80.30
    key: BC-4270.80.30
    name: Webhook Delivery Reliability Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: Webhook & Event Subscription Management
  fit: exact
  layer: common
  why: webhook delivery (Svix); no webhook capability
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: the assistant answers inside messaging apps (bot adapters) [AE id AE-150.20.20; dotted form rejected by schema capability_ref pattern, recorded hyphenated with fit gap]
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: Slack / Discord bot adapters
- capability:
    attribution: Turbo EA
    id: BC-610
    key: information-data-management
    name: Information & Data Management
    url: /capabilities/information-data-management/
    via_parent: null
  fit: nearest
  layer: common
  why: serverless database / queue backing the hosted app
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: nearest
  layer: common
  why: hosting / dev platform; no hosting capability
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Microsoft Graph file picker / people search
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  fit: exact
  layer: domain
  why: reference data tools (weather)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      - Open WebUI
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      - Open WebUI
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp: &id001
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags: &id002
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Vertex AI (Anthropic on Vertex)
      slug: google-vertex-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
        status: verified
      name: Fireworks AI
      slug: fireworks-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Multi-Modal
      tier: observed
      url: /providers/fireworks-ai/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: observed
      url: /providers/cohere/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://docs.together.ai/docs/mcp
        status: verified
      name: Together AI
      slug: together-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Inference
      - LLM
      tier: observed
      url: /providers/together-ai/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: none
      name: xAI
      slug: xai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: observed
      url: /providers/xai/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - LibreChat
      - LobeChat
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face
      slug: hugging-face
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - AnythingLLM
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        status: none
      name: Moonshot AI
      slug: kimi-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Long Context
      tier: observed
      url: /providers/kimi-ai/
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - AnythingLLM
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Cerebras
      slug: cerebras-systems
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - AI Infrastructure
      - Artificial Intelligence
      - Company
      - Machine Learning
      tier: observed
      url: /providers/cerebras-systems/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - AnythingLLM
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        status: none
      name: SambaNova
      slug: sambanova-systems
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - LLM
      - Machine Learning
      tier: observed
      url: /providers/sambanova-systems/
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - AnythingLLM
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 59.7
      mcp:
        status: none
      name: NVIDIA NIM
      slug: nvidia-nim
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Microservices
      tier: observed
      url: /providers/nvidia-nim/
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - AnythingLLM
      - LobeChat
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        source: https://github.com/novitalabs/novita-mcp-server
        status: verified
      name: Novita AI
      slug: novita-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - GPU
      - Inference
      - LLM
      tier: observed
      url: /providers/novita-ai/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - AnythingLLM
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://docs.z.ai/devpack/mcp/vision-mcp-server
        status: verified
      name: Zhipu AI
      slug: zhipu-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - GLM
      - Inference
      - LLM
      tier: observed
      url: /providers/zhipu-ai/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - AnythingLLM
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp: &id003
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags: &id004
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - LobeChat
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare Workers AI
      slug: cloudflare
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - AnythingLLM
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 37.8
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft-foundry/mcp-foundry
        status: verified
      name: Azure AI Foundry
      slug: azure-ai-foundry
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/azure-ai-foundry/
    - agent_band: agent-native
      agent_readiness: 65.5
      apps:
      - LibreChat
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: StepFun
      slug: stepfun
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat Completions
      - LLM
      - Multi-Modal
      tier: observed
      url: /providers/stepfun/
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - LobeChat
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        status: none
      name: AI21 Labs
      slug: ai21-labs
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Jamba
      - LLM
      tier: observed
      url: /providers/ai21-labs/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp: &id005
        source: https://github.com/jina-ai/MCP
        status: verified
      name: Jina AI
      slug: jina-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags: &id006
      - Artificial Intelligence
      - Embeddings
      - Machine Learning
      - Reranking
      tier: observed
      url: /providers/jina-ai/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://github.com/MiniMax-AI/MiniMax-MCP
        status: verified
      name: MiniMax
      slug: minimax-ai
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Multi-Modal
      tier: observed
      url: /providers/minimax-ai/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Qwen
      slug: qwen
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Open Source
      tier: observed
      url: /providers/qwen/
    - agent_band: agent-aware
      agent_readiness: 18.1
      apps:
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        status: none
      name: SiliconFlow
      slug: siliconflow
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Open Source
      tier: observed
      url: /providers/siliconflow/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - LibreChat
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        source: https://github.com/anyscale/mcp-quickstart
        status: verified
      name: Anyscale
      slug: anyscale
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Distributed Computing
      - ML Platform
      - Ray
      tier: observed
      url: /providers/anyscale/
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - LobeChat
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        source: https://github.com/baidu-maps/mcp
        status: verified
      name: Baidu (ERNIE)
      slug: baidu
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Machine Learning
      - Technology
      tier: observed
      url: /providers/baidu/
    - agent_band: null
      agent_readiness: null
      apps:
      - LobeChat
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Upstage
      slug: upstage
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - LobeChat
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Volcengine (ByteDance cloud)
      slug: volcengine
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - AnythingLLM
      - LibreChat
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 61.6
      mcp:
        status: none
      name: Google Programmable Search
      slug: google-custom-search
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Custom Search
      - Google
      - Image Search
      - Search
      tier: observed
      url: /providers/google-custom-search/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - AnythingLLM
      - LibreChat
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 55.4
      mcp:
        status: none
      name: Serper
      slug: serper
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Google Search
      - SERP
      - Search
      tier: observed
      url: /providers/serper/
    - agent_band: agent-ready
      agent_readiness: 45.6
      apps:
      - AnythingLLM
      - LibreChat
      - Open WebUI
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        source: https://github.com/tavily-ai/tavily-mcp
        status: verified
      name: Tavily
      slug: tavily
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - AI Agents
      - LLM
      - Search
      - Web Search
      tier: observed
      url: /providers/tavily/
    - agent_band: agent-native
      agent_readiness: 41.3
      apps:
      - AnythingLLM
      - Open WebUI
      band: exemplar
      in_catalog: true
      kin_score: 74.3
      mcp:
        source: https://github.com/serpapi/serpapi-mcp
        status: verified
      name: SerpApi
      slug: serpapi
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Bing
      - Google
      - Search
      - Search Engines
      tier: observed
      url: /providers/serpapi/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - AnythingLLM
      - Open WebUI
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Bing Search
      slug: microsoft
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Cloud
      - Fortune 100
      - Microsoft
      - Software
      tier: observed
      url: /providers/microsoft/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - AnythingLLM
      - LibreChat
      band: strong
      in_catalog: true
      kin_score: 63.7
      mcp:
        source: https://docs.keenable.ai/mcp
        status: verified
      name: Keenable
      slug: keenable
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - AI Agents
      - AI Labs
      - Inference Platforms
      - Web Search
      tier: observed
      url: /providers/keenable/
    - agent_band: agent-ready
      agent_readiness: 60.0
      apps:
      - AnythingLLM
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/exa-labs/exa-mcp-server
        status: verified
      name: Exa
      slug: exa-ai
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Neural Search
      - Search
      - Web Search
      tier: observed
      url: /providers/exa-ai/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - AnythingLLM
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://github.com/SearchApi/searchapi-mcp
        status: verified
      name: SearchApi
      slug: searchapi
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Google Search
      - SERP
      - Search
      - Web Scraping
      tier: observed
      url: /providers/searchapi/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp: *id001
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - Open WebUI
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: DuckDuckGo
      slug: duckduckgo
      sources:
      - https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
      status: profiled
      tags:
      - AI Chat
      - Browser
      - Privacy
      - Search
      tier: observed
      url: /providers/duckduckgo/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Open WebUI
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        source: https://github.com/kagisearch/kagimcp
        status: verified
      name: Kagi
      slug: kagi
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: profiled
      tags:
      - AI Search
      - Premium Search
      - Search
      - Summarization
      tier: observed
      url: /providers/kagi/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Open WebUI
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp: *id003
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Open WebUI
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp: *id005
      name: Jina AI
      slug: jina-ai
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/jina-ai/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Open WebUI
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        source: https://github.com/brave/brave-search-mcp-server
        status: verified
      name: Brave Search
      slug: brave-browser
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: profiled
      tags:
      - Browser
      - Chromium
      - Privacy
      - Search
      tier: observed
      url: /providers/brave-browser/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Open WebUI
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        source: https://github.com/Mojeek/mojeek-search-mcp
        status: verified
      name: Mojeek
      slug: mojeek
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: profiled
      tags:
      - Community
      - Open Source
      - Privacy
      - Search
      tier: observed
      url: /providers/mojeek/
    - agent_band: null
      agent_readiness: null
      apps:
      - Open WebUI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Linkup
      slug: linkup
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - AnythingLLM
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 60.1
      mcp:
        source: https://github.com/pinecone-io/pinecone-mcp
        status: verified
      name: Pinecone
      slug: pinecone
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - RAG
      - Vector Search
      tier: observed
      url: /providers/pinecone/
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - AnythingLLM
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 59.2
      mcp:
        source: https://github.com/chroma-core/chroma-mcp
        status: verified
      name: Chroma
      slug: chroma
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      - https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
      status: profiled
      tags:
      - AI-native
      - Apache 2.0
      - Artificial Intelligence
      - Cloud
      tier: observed
      url: /providers/chroma/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - AnythingLLM
      - Open WebUI
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://github.com/weaviate/mcp-server-weaviate
        status: verified
      name: Weaviate
      slug: weaviate
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Machine Learning
      - Semantic Search
      - Vector Search
      tier: observed
      url: /providers/weaviate/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - AnythingLLM
      - Open WebUI
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/zilliztech/mcp-server-milvus
        status: verified
      name: Milvus
      slug: milvus
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Open Source
      - Vector Search
      tier: observed
      url: /providers/milvus/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - AnythingLLM
      - Open WebUI
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/qdrant/mcp-server-qdrant
        status: verified
      name: Qdrant
      slug: qdrant
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/vector/dbs
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Database
      - Vector Search
      tier: observed
      url: /providers/qdrant/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - AnythingLLM
      band: developing
      in_catalog: true
      kin_score: 53.2
      mcp:
        source: https://github.com/datastax/astra-db-mcp
        status: verified
      name: DataStax Astra DB
      slug: datastax
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Company
      - Database
      - Enterprise
      - Vector Search
      tier: observed
      url: /providers/datastax/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - AnythingLLM
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        source: https://github.com/lancedb/lancedb-mcp-server
        status: verified
      name: LanceDB
      slug: lancedb
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Lakehouse
      - Lance Format
      - Multi-Modal
      - Vector Search
      tier: observed
      url: /providers/lancedb/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - AnythingLLM
      band: thin
      in_catalog: true
      kin_score: 31.7
      mcp:
        source: https://github.com/zilliztech/zilliz-mcp-server
        status: verified
      name: Zilliz
      slug: zilliz
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Milvus
      - Vector Search
      tier: observed
      url: /providers/zilliz/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - AnythingLLM
      - LibreChat
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - LibreChat
      band: emerging
      in_catalog: true
      kin_score: 22.4
      mcp:
        status: none
      name: ShuttleAI
      slug: shuttleai
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Developer Tools
      - Infrastructure
      - Product
      tier: observed
      url: /providers/shuttleai/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - LibreChat
      band: emerging
      in_catalog: true
      kin_score: 17.2
      mcp:
        status: unknown
      name: APIpie
      slug: apipie
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - OpenAI-compatible API
      - Redundant routing
      tier: observed
      url: /providers/apipie/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 29.9
      mcp:
        source: https://github.com/black-forest-labs/flux-mcp
        status: verified
      name: Black Forest Labs (Flux)
      slug: black-forest-labs
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Flux
      - Image Generation
      - Open Weights
      tier: observed
      url: /providers/black-forest-labs/
    - agent_band: agent-ready
      agent_readiness: 53.2
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://docs.fal.ai/model-apis/mcp
        status: verified
      name: fal
      slug: fal-ai
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Generative Media
      - Image Generation
      tier: observed
      url: /providers/fal-ai/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        source: https://github.com/replicate/replicate-mcp-code-mode
        status: verified
      name: Replicate
      slug: replicate
      sources:
      - https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Image Generation
      - Language Models
      - Machine Learning
      tier: observed
      url: /providers/replicate/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - LibreChat
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp: *id005
      name: Jina AI
      slug: jina-ai
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/jina-ai/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - AnythingLLM
      band: emerging
      in_catalog: true
      kin_score: 24.2
      mcp:
        status: none
      name: Voyage AI
      slug: voyage-ai
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      status: profiled
      tags:
      - Embeddings
      - RAG
      - Rerankers
      - Semantic Search
      tier: observed
      url: /providers/voyage-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - LibreChat
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeather
      slug: openweathermap
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/openweathermap/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Open WebUI
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure AI Document Intelligence
      slug: microsoft-azure
      sources:
      - https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - AnythingLLM
      band: exemplar
      in_catalog: true
      kin_score: 83.2
      mcp:
        source: https://github.com/elevenlabs/elevenlabs-mcp
        status: verified
      name: ElevenLabs
      slug: elevenlabs
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/elevenlabs/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - LibreChat
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id011
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags: &id012
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - LibreChat
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - LibreChat
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - LibreChat
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp: &id009
        status: none
      name: Discord
      slug: discord
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags: &id010
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - LibreChat
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - LibreChat
      - Open WebUI
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      - https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - LibreChat
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Open WebUI
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/open-webui/open-webui/main/pyproject.toml
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - LibreChat
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id007
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags: &id008
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - ChatGPT
      - Claude
      - Le Chat (Mistral)
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/ai.mistral.chat/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.anthropic.claude/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.openai.chatgpt/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Perplexity
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id007
      name: Firebase (Crashlytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - ChatGPT
      - Claude
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.anthropic.claude/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.openai.chatgpt/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Perplexity
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id007
      name: Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - AnythingLLM
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - LobeChat
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - LobeChat
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp: *id009
      name: Discord
      slug: discord
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        source: https://github.com/neondatabase/mcp-server-neon
        status: verified
      name: Neon
      slug: neon
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Database
      - Infrastructure
      - PostgreSQL
      - Serverless
      tier: observed
      url: /providers/neon/
    - agent_band: agent-ready
      agent_readiness: 46.7
      apps:
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://github.com/upstash/mcp-server
        status: verified
      name: Upstash
      slug: upstash
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Kafka
      - Messaging
      - Redis
      - Serverless
      tier: observed
      url: /providers/upstash/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - LibreChat
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - AnythingLLM
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/package.json
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - LibreChat
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/api/package.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel
      slug: vercel
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Perplexity
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/ai.perplexity.app.android/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - LobeChat
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - LobeChat
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id011
      name: GitHub
      slug: github
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/github/
  - capability:
      attribution: Turbo EA
      id: BC-4270.80.30
      key: BC-4270.80.30
      name: Webhook Delivery Reliability Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: Webhook & Event Subscription Management
    providers:
    - agent_band: agent-native
      agent_readiness: 52.1
      apps:
      - LobeChat
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        status: none
      name: Svix
      slug: svix
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Webhook
      - Webhook Delivery
      - Webhook Sending
      - Webhooks As A Service
      tier: observed
      url: /providers/svix/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10.30
      key: AE-100.10.30
      name: Browser & Computer-Use Automation
      url: /capabilities/agent-tool-exposure/
      via_parent: Agent Tool Exposure
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - AnythingLLM
      - LibreChat
      - Open WebUI
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://docs.firecrawl.dev/mcp-server
        status: verified
      name: Firecrawl
      slug: firecrawl
      sources:
      - https://github.com/open-webui/open-webui/tree/main/backend/open_webui/retrieval/web
      - https://raw.githubusercontent.com/Mintplex-Labs/anything-llm/master/server/.env.example
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Crawling
      - Data Extraction
      - URLs
      - Web Scraping
      tier: observed
      url: /providers/firecrawl/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - LibreChat
      - LobeChat
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        source: https://github.com/langfuse/mcp-server-langfuse
        status: verified
      name: Langfuse
      slug: langfuse
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Observability
      - Open Source
      tier: observed
      url: /providers/langfuse/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - LibreChat
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - LobeChat
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        source: https://github.com/ComposioHQ/composio
        status: verified
      name: Composio
      slug: composio
      sources:
      - https://raw.githubusercontent.com/lobehub/lobe-chat/main/package.json
      status: profiled
      tags:
      - AI Agents
      - Authentication
      - Integration
      - MCP
      tier: observed
      url: /providers/composio/
  layer: agent
summary:
  coverage_pct: 96.8
  declared_only: 0
  distinct_providers: 93
  in_catalog: 90
  mcp:
    documented: 0
    none: 27
    unchecked: 3
    verified: 62
  mcp_verified: 62
  mean_kin_score: 53.2
  observed: 93
  queued: 3
  reference_apps: 8
title: 'AI Assistant & Chat: application blueprint'
---
