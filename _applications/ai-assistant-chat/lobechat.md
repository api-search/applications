---
app: LobeChat
app_slug: lobechat
app_url: https://github.com/lobehub/lobe-chat
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - AI21 Labs
  - Amazon Bedrock
  - Anthropic
  - Azure AI Foundry
  - Baidu (ERNIE)
  - Cerebras
  - Cloudflare Workers AI
  - Cohere
  - DeepSeek
  - Fireworks AI
  - Google Gemini
  - Groq
  - Hugging Face
  - Jina AI
  - MiniMax
  - Mistral AI
  - Moonshot AI
  - Novita AI
  - NVIDIA NIM
  - Ollama
  - OpenAI
  - Perplexity
  - Qwen
  - SambaNova
  - SiliconFlow
  - StepFun
  - Together AI
  - Upstage
  - Vertex AI
  - Volcengine (ByteDance cloud)
  - xAI
  - Zhipu AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.20.10
  key: AE-110.20.10
  layer: domain
  name: Image Generation
  providers:
  - Black Forest Labs
  - fal
  - Replicate
  url: /capabilities/generative-media/
  via_parent: Generative Media
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
  id: AE-932
  key: AE-932
  layer: common
  name: Edge Functions & Edge Config Stores
  providers:
  - Vercel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Neon
  - Upstash
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Resend
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-4270.80.30
  key: BC-4270.80.30
  layer: common
  name: Webhook Delivery Reliability Management
  providers:
  - Svix
  url: /capabilities/webhook-event-subscription-management/
  via_parent: Webhook & Event Subscription Management
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
  - Composio
  url: /capabilities/agent-tool-exposure/
  via_parent: null
category:
  id: ai-assistant-chat
  name: AI Assistant & Chat
  url: /applications/ai-assistant-chat/
counts:
  declared: 0
  observed: 48
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 41.1
    mcp: &id001
      status: none
    slug: ai21-labs
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Foundation Models
    - Jamba
    - LLM
    url: /providers/ai21-labs/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id007
      source: https://github.com/microsoft-foundry/mcp-foundry
      status: verified
    slug: azure-ai-foundry
    status: profiled
    tags: &id008
    - AI Agents
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/azure-ai-foundry/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 6.0
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id009
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id011
      source: https://github.com/black-forest-labs/flux-mcp
      status: verified
    slug: black-forest-labs
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Flux
    - Image Generation
    - Open Weights
    url: /providers/black-forest-labs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.0
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id013
      status: none
    slug: cerebras-systems
    status: profiled
    tags: &id014
    - AI Infrastructure
    - Artificial Intelligence
    - Company
    - Machine Learning
    url: /providers/cerebras-systems/
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
  facts:
    agent_band: agent-native
    agent_readiness: 69.6
    band: exemplar
    in_catalog: true
    kin_score: 82.8
    mcp: &id015
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id016
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.9
    band: strong
    in_catalog: true
    kin_score: 62.3
    mcp: &id019
      source: https://github.com/ComposioHQ/composio
      status: verified
    slug: composio
    status: profiled
    tags: &id020
    - AI Agents
    - Authentication
    - Integration
    - MCP
    url: /providers/composio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.1
    band: strong
    in_catalog: true
    kin_score: 65.6
    mcp: &id025
      source: https://docs.fal.ai/model-apis/mcp
      status: verified
    slug: fal-ai
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Generative AI
    - Generative Media
    - Image Generation
    url: /providers/fal-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id027
      source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
      status: verified
    slug: fireworks-ai
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Inference
    - LLM
    - Multi-Modal
    url: /providers/fireworks-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id029
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id030
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id031
      status: none
    slug: google-gemini
    status: profiled
    tags: &id032
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id033
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id035
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id036
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id037
      source: https://github.com/jina-ai/MCP
      status: verified
    slug: jina-ai
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - Embeddings
    - Machine Learning
    - Reranking
    url: /providers/jina-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id039
      source: https://github.com/langfuse/mcp-server-langfuse
      status: verified
    slug: langfuse
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - LLM
    - Observability
    - Open Source
    url: /providers/langfuse/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id041
      source: https://github.com/MiniMax-AI/MiniMax-MCP
      status: verified
    slug: minimax-ai
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Inference
    - LLM
    - Multi-Modal
    url: /providers/minimax-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id043
      status: none
    slug: mistral
    status: profiled
    tags: &id044
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.8
    band: strong
    in_catalog: true
    kin_score: 56.6
    mcp: &id045
      status: unchecked
    slug: kimi-ai
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Inference
    - LLM
    - Long Context
    url: /providers/kimi-ai/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id047
      source: https://github.com/neondatabase/mcp-server-neon
      status: verified
    slug: neon
    status: profiled
    tags: &id048
    - Database
    - Infrastructure
    - PostgreSQL
    - Serverless
    url: /providers/neon/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: developing
    in_catalog: true
    kin_score: 52.6
    mcp: &id049
      source: https://github.com/novitalabs/novita-mcp-server
      status: verified
    slug: novita-ai
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - GPU
    - Inference
    - LLM
    url: /providers/novita-ai/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.9
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id051
      status: none
    slug: nvidia-nim
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Inference
    - LLM
    - Microservices
    url: /providers/nvidia-nim/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id053
      status: none
    slug: ollama
    status: profiled
    tags: &id054
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id055
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id057
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id058
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
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
  facts:
    agent_band: agent-native
    agent_readiness: 67.7
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id059
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id060
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id061
      status: none
    slug: qwen
    status: profiled
    tags: &id062
    - Artificial Intelligence
    - Inference
    - LLM
    - Open Source
    url: /providers/qwen/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id063
      source: https://github.com/replicate/replicate-mcp-code-mode
      status: verified
    slug: replicate
    status: profiled
    tags: &id064
    - Artificial Intelligence
    - Image Generation
    - Language Models
    - Machine Learning
    url: /providers/replicate/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.4
    band: strong
    in_catalog: true
    kin_score: 58.9
    mcp: &id065
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id066
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id067
      status: none
    slug: sambanova-systems
    status: profiled
    tags: &id068
    - Artificial Intelligence
    - Company
    - LLM
    - Machine Learning
    url: /providers/sambanova-systems/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id069
      status: none
    slug: siliconflow
    status: profiled
    tags: &id070
    - Artificial Intelligence
    - Inference
    - LLM
    - Open Source
    url: /providers/siliconflow/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id071
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id072
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id073
      status: none
    slug: stepfun
    status: profiled
    tags: &id074
    - Artificial Intelligence
    - Chat Completions
    - LLM
    - Multi-Modal
    url: /providers/stepfun/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id075
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id076
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-native
    agent_readiness: 53.1
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id077
      status: none
    slug: svix
    status: profiled
    tags: &id078
    - Webhook
    - Webhook Delivery
    - Webhook Sending
    - Webhooks As A Service
    url: /providers/svix/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id079
      status: none
    slug: telegram
    status: profiled
    tags: &id080
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.4
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id081
      source: https://docs.together.ai/docs/mcp
      status: verified
    slug: together-ai
    status: profiled
    tags: &id082
    - Artificial Intelligence
    - Foundation Models
    - Inference
    - LLM
    url: /providers/together-ai/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id083
      status: unchecked
    slug: upstage
    status: queued for profiling
    tags: &id084 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id085
      source: https://github.com/upstash/mcp-server
      status: verified
    slug: upstash
    status: profiled
    tags: &id086
    - Kafka
    - Messaging
    - Redis
    - Serverless
    url: /providers/upstash/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.2
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id087
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id088
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id089
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id090
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id091
      status: unchecked
    slug: volcengine
    status: queued for profiling
    tags: &id092 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id093
      status: none
    slug: xai
    status: profiled
    tags: &id094
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id095
      source: https://docs.z.ai/devpack/mcp/vision-mcp-server
      status: verified
    slug: zhipu-ai
    status: profiled
    tags: &id096
    - Artificial Intelligence
    - GLM
    - Inference
    - LLM
    url: /providers/zhipu-ai/
  layer: domain
  name: Zhipu AI
  provider: zhipu-ai
  says: ships the Zhipu AI SDK or integration code
  source: https://github.com/lobehub/lobe-chat/tree/main/packages/model-runtime/src/providers
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ai-assistant-chat/lobechat/
providers:
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 41.1
  mcp: *id001
  name: AI21 Labs
  slug: ai21-labs
  status: profiled
  tags: *id002
  url: /providers/ai21-labs/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id003
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
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
- agent_band: agent-aware
  agent_readiness: 23.7
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id007
  name: Azure AI Foundry
  slug: azure-ai-foundry
  status: profiled
  tags: *id008
  url: /providers/azure-ai-foundry/
- agent_band: agent-aware
  agent_readiness: 6.0
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id009
  name: Baidu (ERNIE)
  slug: baidu
  status: profiled
  tags: *id010
  url: /providers/baidu/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id011
  name: Black Forest Labs
  slug: black-forest-labs
  status: profiled
  tags: *id012
  url: /providers/black-forest-labs/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id013
  name: Cerebras
  slug: cerebras-systems
  status: profiled
  tags: *id014
  url: /providers/cerebras-systems/
- agent_band: agent-native
  agent_readiness: 69.6
  band: exemplar
  in_catalog: true
  kin_score: 82.8
  mcp: *id015
  name: Cloudflare Workers AI
  slug: cloudflare
  status: profiled
  tags: *id016
  url: /providers/cloudflare/
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
  agent_readiness: 30.9
  band: strong
  in_catalog: true
  kin_score: 62.3
  mcp: *id019
  name: Composio
  slug: composio
  status: profiled
  tags: *id020
  url: /providers/composio/
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
- agent_band: agent-ready
  agent_readiness: 48.1
  band: strong
  in_catalog: true
  kin_score: 65.6
  mcp: *id025
  name: fal
  slug: fal-ai
  status: profiled
  tags: *id026
  url: /providers/fal-ai/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id027
  name: Fireworks AI
  slug: fireworks-ai
  status: profiled
  tags: *id028
  url: /providers/fireworks-ai/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id029
  name: GitHub
  slug: github
  status: profiled
  tags: *id030
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id031
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id032
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id033
  name: Groq
  slug: groq
  status: profiled
  tags: *id034
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id035
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id036
  url: /providers/hugging-face/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id037
  name: Jina AI
  slug: jina-ai
  status: profiled
  tags: *id038
  url: /providers/jina-ai/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id039
  name: Langfuse
  slug: langfuse
  status: profiled
  tags: *id040
  url: /providers/langfuse/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id041
  name: MiniMax
  slug: minimax-ai
  status: profiled
  tags: *id042
  url: /providers/minimax-ai/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id043
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id044
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 36.8
  band: strong
  in_catalog: true
  kin_score: 56.6
  mcp: *id045
  name: Moonshot AI
  slug: kimi-ai
  status: profiled
  tags: *id046
  url: /providers/kimi-ai/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id047
  name: Neon
  slug: neon
  status: profiled
  tags: *id048
  url: /providers/neon/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: developing
  in_catalog: true
  kin_score: 52.6
  mcp: *id049
  name: Novita AI
  slug: novita-ai
  status: profiled
  tags: *id050
  url: /providers/novita-ai/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id051
  name: NVIDIA NIM
  slug: nvidia-nim
  status: profiled
  tags: *id052
  url: /providers/nvidia-nim/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id053
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id054
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id055
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id056
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id057
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id058
  url: /providers/openrouter/
- agent_band: agent-native
  agent_readiness: 67.7
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id059
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id060
  url: /providers/perplexity/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id061
  name: Qwen
  slug: qwen
  status: profiled
  tags: *id062
  url: /providers/qwen/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id063
  name: Replicate
  slug: replicate
  status: profiled
  tags: *id064
  url: /providers/replicate/
- agent_band: agent-ready
  agent_readiness: 49.4
  band: strong
  in_catalog: true
  kin_score: 58.9
  mcp: *id065
  name: Resend
  slug: resend
  status: profiled
  tags: *id066
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id067
  name: SambaNova
  slug: sambanova-systems
  status: profiled
  tags: *id068
  url: /providers/sambanova-systems/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id069
  name: SiliconFlow
  slug: siliconflow
  status: profiled
  tags: *id070
  url: /providers/siliconflow/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id071
  name: Slack
  slug: slack
  status: profiled
  tags: *id072
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id073
  name: StepFun
  slug: stepfun
  status: profiled
  tags: *id074
  url: /providers/stepfun/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id075
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id076
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 53.1
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id077
  name: Svix
  slug: svix
  status: profiled
  tags: *id078
  url: /providers/svix/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id079
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id080
  url: /providers/telegram/
- agent_band: agent-ready
  agent_readiness: 40.4
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id081
  name: Together AI
  slug: together-ai
  status: profiled
  tags: *id082
  url: /providers/together-ai/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id083
  name: Upstage
  slug: upstage
  status: queued for profiling
  tags: *id084
  url: null
- agent_band: agent-ready
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id085
  name: Upstash
  slug: upstash
  status: profiled
  tags: *id086
  url: /providers/upstash/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id087
  name: Vercel
  slug: vercel
  status: profiled
  tags: *id088
  url: /providers/vercel/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id089
  name: Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id090
  url: /providers/google-vertex-ai/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id091
  name: Volcengine (ByteDance cloud)
  slug: volcengine
  status: queued for profiling
  tags: *id092
  url: null
- agent_band: agent-ready
  agent_readiness: 38.8
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id093
  name: xAI
  slug: xai
  status: profiled
  tags: *id094
  url: /providers/xai/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id095
  name: Zhipu AI
  slug: zhipu-ai
  status: profiled
  tags: *id096
  url: /providers/zhipu-ai/
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
- name: Open WebUI
  rows: 26
  url: /applications/ai-assistant-chat/open-webui/
- name: Perplexity
  rows: 3
  url: /applications/ai-assistant-chat/perplexity/
sitemap: true
title: 'LobeChat: AI Assistant & Chat reference app'
---
