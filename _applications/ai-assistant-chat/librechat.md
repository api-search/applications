---
app: LibreChat
app_slug: librechat
app_url: https://github.com/danny-avila/LibreChat
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230
  key: AE-230
  layer: domain
  name: Data & Reference Information Services
  providers:
  - OpenWeather
  url: /capabilities/data-reference-information-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Jina AI
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
  - Anyscale
  - Cohere
  - Databricks
  - DeepSeek
  - Fireworks AI
  - Google Gemini
  - Groq
  - Hugging Face
  - Mistral AI
  - OpenAI
  - Perplexity
  - Together AI
  - Vertex AI (Anthropic on Vertex)
  - xAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.20.10
  key: AE-110.20.10
  layer: domain
  name: Image Generation
  providers:
  - Black Forest Labs (Flux)
  url: /capabilities/generative-media/
  via_parent: Generative Media
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: domain
  name: Model Routing & Gateways
  providers:
  - APIpie
  - OpenRouter
  - ShuttleAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.60.30
  key: AE-110.60.30
  layer: domain
  name: Retrieval-Augmented Generation
  providers:
  - Google Custom Search
  - Keenable
  - Serper
  - Tavily
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Microsoft Graph
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Apple
  - Discord
  - Facebook
  - GitHub
  - Google sign-in
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
  - Firebase
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-100.60.20
  key: AE-100.60.20
  layer: agent
  name: Agent Observability
  providers:
  - Langfuse
  url: /capabilities/agent-quality-operations/
  via_parent: Agent Quality & Operations
- attribution: API Evangelist extension
  id: AE-100.10
  key: AE-100.10
  layer: agent
  name: Agent Tool Exposure
  providers:
  - Zapier
  url: /capabilities/agent-tool-exposure/
  via_parent: null
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
  observed: 39
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
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
  facts:
    agent_band: human-only
    agent_readiness: 3.9
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id007
      source: https://github.com/anyscale/mcp-quickstart
      status: verified
    slug: anyscale
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Distributed Computing
    - ML Platform
    - Ray
    url: /providers/anyscale/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id009
      status: unknown
    slug: apipie
    status: profiled
    tags: &id010
    - OpenAI-compatible API
    - Redundant routing
    url: /providers/apipie/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id011
      status: none
    slug: apple
    status: profiled
    tags: &id012
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id014
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id015
      source: https://github.com/black-forest-labs/flux-mcp
      status: verified
    slug: black-forest-labs
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Flux
    - Image Generation
    - Open Weights
    url: /providers/black-forest-labs/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id017
      status: none
    slug: cohere
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id019
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id020
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id021
      status: none
    slug: deepseek
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id023
      status: none
    slug: discord
    status: profiled
    tags: &id024
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id025
      status: none
    slug: facebook
    status: profiled
    tags: &id026
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id027
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id028
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id029
      source: https://docs.firecrawl.dev/mcp-server
      status: verified
    slug: firecrawl
    status: profiled
    tags: &id030
    - Crawling
    - Data Extraction
    - URLs
    - Web Scraping
    url: /providers/firecrawl/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id031
      source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
      status: verified
    slug: fireworks-ai
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Inference
    - LLM
    - Multi-Modal
    url: /providers/fireworks-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id033
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id034
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 51.1
    mcp: &id035
      status: none
    slug: google-custom-search
    status: profiled
    tags: &id036
    - Custom Search
    - Google
    - Image Search
    - Search
    url: /providers/google-custom-search/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id037
      status: none
    slug: google-gemini
    status: profiled
    tags: &id038
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id039
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id040
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id041
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id043
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id044
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id045
      source: https://github.com/jina-ai/MCP
      status: verified
    slug: jina-ai
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Embeddings
    - Machine Learning
    - Reranking
    url: /providers/jina-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: developing
    in_catalog: true
    kin_score: 53.7
    mcp: &id047
      source: https://docs.keenable.ai/mcp
      status: verified
    slug: keenable
    status: profiled
    tags: &id048
    - AI Agents
    - AI Labs
    - Inference Platforms
    - Web Search
    url: /providers/keenable/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id049
      source: https://github.com/langfuse/mcp-server-langfuse
      status: verified
    slug: langfuse
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - LLM
    - Observability
    - Open Source
    url: /providers/langfuse/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id051
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id052
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.0
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id053
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id054
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id055
      status: none
    slug: mistral
    status: profiled
    tags: &id056
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id057
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id058
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id059
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: strong
    in_catalog: true
    kin_score: 60.4
    mcp: &id061
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id062
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
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
  facts:
    agent_band: agent-native
    agent_readiness: 67.7
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id063
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id064
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: strong
    in_catalog: true
    kin_score: 56.5
    mcp: &id065
      status: none
    slug: serper
    status: profiled
    tags: &id066
    - Artificial Intelligence
    - Google Search
    - SERP
    - Search
    url: /providers/serper/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id067
      status: none
    slug: shuttleai
    status: profiled
    tags: &id068
    - Artificial Intelligence
    - Developer Tools
    - Infrastructure
    - Product
    url: /providers/shuttleai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.4
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id071
      source: https://docs.together.ai/docs/mcp
      status: verified
    slug: together-ai
    status: profiled
    tags: &id072
    - Artificial Intelligence
    - Foundation Models
    - Inference
    - LLM
    url: /providers/together-ai/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id073
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id074
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id075
      status: none
    slug: xai
    status: profiled
    tags: &id076
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id077
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id078
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: agent
  name: Zapier
  provider: zapier
  says: ships the Zapier SDK or integration code
  source: https://raw.githubusercontent.com/danny-avila/LibreChat/main/.env.example
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ai-assistant-chat/librechat/
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
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id005
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: human-only
  agent_readiness: 3.9
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id007
  name: Anyscale
  slug: anyscale
  status: profiled
  tags: *id008
  url: /providers/anyscale/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id009
  name: APIpie
  slug: apipie
  status: profiled
  tags: *id010
  url: /providers/apipie/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id011
  name: Apple
  slug: apple
  status: profiled
  tags: *id012
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id013
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id015
  name: Black Forest Labs (Flux)
  slug: black-forest-labs
  status: profiled
  tags: *id016
  url: /providers/black-forest-labs/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id017
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id018
  url: /providers/cohere/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id019
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id020
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id021
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id022
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id023
  name: Discord
  slug: discord
  status: profiled
  tags: *id024
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id025
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id026
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id027
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id028
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id029
  name: Firecrawl
  slug: firecrawl
  status: profiled
  tags: *id030
  url: /providers/firecrawl/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id031
  name: Fireworks AI
  slug: fireworks-ai
  status: profiled
  tags: *id032
  url: /providers/fireworks-ai/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id033
  name: GitHub
  slug: github
  status: profiled
  tags: *id034
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id035
  name: Google Custom Search
  slug: google-custom-search
  status: profiled
  tags: *id036
  url: /providers/google-custom-search/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id037
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id038
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id039
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id040
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id041
  name: Groq
  slug: groq
  status: profiled
  tags: *id042
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id043
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id044
  url: /providers/hugging-face/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id045
  name: Jina AI
  slug: jina-ai
  status: profiled
  tags: *id046
  url: /providers/jina-ai/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id047
  name: Keenable
  slug: keenable
  status: profiled
  tags: *id048
  url: /providers/keenable/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id049
  name: Langfuse
  slug: langfuse
  status: profiled
  tags: *id050
  url: /providers/langfuse/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id051
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id052
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id053
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id054
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id055
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id056
  url: /providers/mistral/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id057
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id058
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id059
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id060
  url: /providers/openrouter/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: strong
  in_catalog: true
  kin_score: 60.4
  mcp: *id061
  name: OpenWeather
  slug: openweathermap
  status: profiled
  tags: *id062
  url: /providers/openweathermap/
- agent_band: agent-native
  agent_readiness: 67.7
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id063
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id064
  url: /providers/perplexity/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: strong
  in_catalog: true
  kin_score: 56.5
  mcp: *id065
  name: Serper
  slug: serper
  status: profiled
  tags: *id066
  url: /providers/serper/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id067
  name: ShuttleAI
  slug: shuttleai
  status: profiled
  tags: *id068
  url: /providers/shuttleai/
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
- agent_band: agent-ready
  agent_readiness: 40.4
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id071
  name: Together AI
  slug: together-ai
  status: profiled
  tags: *id072
  url: /providers/together-ai/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id073
  name: Vertex AI (Anthropic on Vertex)
  slug: google-vertex-ai
  status: profiled
  tags: *id074
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id075
  name: xAI
  slug: xai
  status: profiled
  tags: *id076
  url: /providers/xai/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id077
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id078
  url: /providers/zapier/
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
title: 'LibreChat: AI Assistant & Chat reference app'
---
