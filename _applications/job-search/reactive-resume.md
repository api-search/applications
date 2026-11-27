---
app: Reactive Resume
app_slug: reactive-resume
app_url: https://github.com/amruthpillai/reactive-resume
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-927
  key: AE-927
  layer: domain
  name: Domain Registration & Managed DNS
  providers:
  - OlaCV
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-230.40
  key: web-data
  layer: domain
  name: Web Data
  providers:
  - Firecrawl
  url: /capabilities/web-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.40.20
  key: AE-230.40.20
  layer: domain
  name: Web Search APIs
  providers:
  - Exa
  - SearXNG
  - Tavily
  url: /capabilities/web-data/
  via_parent: Web Data
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
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Expo
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub sign-in
  - Google sign-in
  - LinkedIn sign-in
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - SeaweedFS
  - Vercel Blob
  - Cloudflare R2
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-170.70.20
  key: AE-170.70.20
  layer: common
  name: Translation Management & Localization
  providers:
  - Crowdin
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-170.80.10
  key: AE-170.80.10
  layer: common
  name: Web Fonts & Typography
  providers:
  - Google Fonts
  url: /capabilities/design-creative-editing/
  via_parent: Design & Creative Editing
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Cerebras
  - Cohere
  - DeepSeek
  - Fireworks AI
  - Google Gemini
  - Groq
  - Mistral
  - OpenAI
  - Perplexity
  - Together AI
  - xAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: agent
  name: On-Device & Edge Inference
  providers:
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: job-search
  name: Job Search
  url: /applications/job-search/
counts:
  declared: 1
  observed: 29
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/amruthpillai/reactive-resume/blob/main/apps/mobile/package.json
- route: dependency manifest
  url: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
- route: source code
  url: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
- route: source code
  url: https://github.com/amruthpillai/reactive-resume/tree/main/packages/mcp
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
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 27.9
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id005
      status: none
    slug: cerebras-systems
    status: profiled
    tags: &id006
    - AI Infrastructure
    - Artificial Intelligence
    - Company
    - Machine Learning
    url: /providers/cerebras-systems/
  layer: agent
  name: Cerebras
  provider: cerebras-systems
  says: ships the Cerebras SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 40.6
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id009
      status: none
    slug: cohere
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: agent
  name: Cohere
  provider: cohere
  says: ships the Cohere SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id011
      source: https://mcp.crowdin.com/v2/mcp
      status: verified
    slug: crowdin
    status: profiled
    tags: &id012
    - Localization
    - REST
    - TMS
    - Translation
    url: /providers/crowdin/
  layer: common
  name: Crowdin
  provider: crowdin
  says: ships the Crowdin SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id013
      status: none
    slug: deepseek
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: agent
  name: DeepSeek
  provider: deepseek
  says: ships the DeepSeek SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.0
    band: strong
    in_catalog: true
    kin_score: 57.7
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
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.5
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id017
      source: https://github.com/expo/expo-mcp
      status: verified
    slug: expo
    status: profiled
    tags: &id018
    - Build Automation
    - Mobile Development
    - Over-the-Air Updates
    - React Native
    url: /providers/expo/
  layer: common
  name: Expo
  provider: expo
  says: ships the Expo SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/apps/mobile/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40
    key: web-data
    name: Web Data
    url: /capabilities/web-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id019
      source: https://docs.firecrawl.dev/mcp-server
      status: verified
    slug: firecrawl
    status: profiled
    tags: &id020
    - Crawling
    - Data Extraction
    - URLs
    - Web Scraping
    url: /providers/firecrawl/
  layer: domain
  name: Firecrawl
  provider: firecrawl
  says: ships the Firecrawl SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 39.0
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id021
      source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
      status: verified
    slug: fireworks-ai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Inference
    - LLM
    - Multi-Modal
    url: /providers/fireworks-ai/
  layer: agent
  name: Fireworks AI
  provider: fireworks-ai
  says: ships the Fireworks AI SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id023
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id024
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub sign-in
  provider: github
  says: ships the GitHub sign-in SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.80.10
    key: AE-170.80.10
    name: Web Fonts & Typography
    url: /capabilities/design-creative-editing/
    via_parent: Design & Creative Editing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id025
      status: none
    slug: google-fonts
    status: profiled
    tags: &id026
    - CSS
    - Design
    - Fonts
    - Google Fonts
    url: /providers/google-fonts/
  layer: common
  name: Google Fonts
  provider: google-fonts
  says: ships the Google Fonts SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id029
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id030
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 21.2
    band: thin
    in_catalog: true
    kin_score: 32.3
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
  layer: agent
  name: Groq
  provider: groq
  says: ships the Groq SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id033
      status: none
    slug: linkedin
    status: profiled
    tags: &id034
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn sign-in
  provider: linkedin
  says: ships the LinkedIn sign-in SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id035
      status: none
    slug: mistral
    status: profiled
    tags: &id036
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: agent
  name: Mistral
  provider: mistral
  says: ships the Mistral SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 43.5
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id037
      status: unchecked
    slug: olacv
    status: profiled
    tags: &id038
    - API Integration
    - Domain Registry
    - Marketplace
    - Premium Domains
    url: /providers/olacv/
  layer: domain
  name: OlaCV
  provider: olacv
  says: ships the OlaCV SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id039
      status: none
    slug: ollama
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    mcp: &id041
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 66.6
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id043
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id044
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
  layer: agent
  name: Perplexity
  provider: perplexity
  says: ships the Perplexity SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    mcp: &id045
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id046
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id047
      status: unchecked
    slug: searxng
    status: profiled
    tags: &id048
    - Metasearch
    - Open Source
    - Privacy
    - Search
    url: /providers/searxng/
  layer: domain
  name: SearXNG
  provider: searxng
  says: ships the SearXNG SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 26.3
    mcp: &id049
      status: none
    slug: seaweedfs
    status: profiled
    tags: &id050
    - Company
    - Distributed File System
    - Object Storage
    - S3 Compatible
    url: /providers/seaweedfs/
  layer: common
  name: SeaweedFS
  provider: seaweedfs
  says: ships the SeaweedFS SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id051
      status: none
    slug: apple
    status: profiled
    tags: &id052
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id053
      source: https://github.com/tavily-ai/tavily-mcp
      status: verified
    slug: tavily
    status: profiled
    tags: &id054
    - AI Agents
    - LLM
    - Search
    - Web Search
    url: /providers/tavily/
  layer: domain
  name: Tavily
  provider: tavily
  says: ships the Tavily SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
    agent_readiness: 40.0
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id055
      source: https://docs.together.ai/docs/mcp
      status: verified
    slug: together-ai
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - Foundation Models
    - Inference
    - LLM
    url: /providers/together-ai/
  layer: agent
  name: Together AI
  provider: together-ai
  says: ships the Together AI SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id057
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id058
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: common
  name: Vercel Blob
  provider: vercel
  says: ships the Vercel Blob SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    kin_score: 32.3
    mcp: &id059
      status: none
    slug: xai
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
  layer: agent
  name: xAI
  provider: xai
  says: ships the xAI SDK or integration code
  source: https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id007
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id008
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare R2
  provider: cloudflare
  says: lists Cloudflare R2 as an integration
  source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/job-search/reactive-resume/
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
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 27.9
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id005
  name: Cerebras
  slug: cerebras-systems
  status: profiled
  tags: *id006
  url: /providers/cerebras-systems/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id007
  name: Cloudflare R2
  slug: cloudflare
  status: profiled
  tags: *id008
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id009
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id010
  url: /providers/cohere/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id011
  name: Crowdin
  slug: crowdin
  status: profiled
  tags: *id012
  url: /providers/crowdin/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id013
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id014
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id015
  name: Exa
  slug: exa-ai
  status: profiled
  tags: *id016
  url: /providers/exa-ai/
- agent_band: agent-aware
  agent_readiness: 20.5
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id017
  name: Expo
  slug: expo
  status: profiled
  tags: *id018
  url: /providers/expo/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id019
  name: Firecrawl
  slug: firecrawl
  status: profiled
  tags: *id020
  url: /providers/firecrawl/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id021
  name: Fireworks AI
  slug: fireworks-ai
  status: profiled
  tags: *id022
  url: /providers/fireworks-ai/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id023
  name: GitHub sign-in
  slug: github
  status: profiled
  tags: *id024
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id025
  name: Google Fonts
  slug: google-fonts
  status: profiled
  tags: *id026
  url: /providers/google-fonts/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id027
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id028
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id029
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id030
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id031
  name: Groq
  slug: groq
  status: profiled
  tags: *id032
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id033
  name: LinkedIn sign-in
  slug: linkedin
  status: profiled
  tags: *id034
  url: /providers/linkedin/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id035
  name: Mistral
  slug: mistral
  status: profiled
  tags: *id036
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 43.5
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id037
  name: OlaCV
  slug: olacv
  status: profiled
  tags: *id038
  url: /providers/olacv/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id039
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id040
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id041
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id042
  url: /providers/openai/
- agent_band: agent-native
  agent_readiness: 66.6
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id043
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id044
  url: /providers/perplexity/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id045
  name: Redis
  slug: redis
  status: profiled
  tags: *id046
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id047
  name: SearXNG
  slug: searxng
  status: profiled
  tags: *id048
  url: /providers/searxng/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id049
  name: SeaweedFS
  slug: seaweedfs
  status: profiled
  tags: *id050
  url: /providers/seaweedfs/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id051
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id052
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 45.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id053
  name: Tavily
  slug: tavily
  status: profiled
  tags: *id054
  url: /providers/tavily/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id055
  name: Together AI
  slug: together-ai
  status: profiled
  tags: *id056
  url: /providers/together-ai/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id057
  name: Vercel Blob
  slug: vercel
  status: profiled
  tags: *id058
  url: /providers/vercel/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id059
  name: xAI
  slug: xai
  status: profiled
  tags: *id060
  url: /providers/xai/
siblings:
- name: Glassdoor
  rows: 2
  url: /applications/job-search/glassdoor/
- name: Indeed
  rows: 2
  url: /applications/job-search/indeed/
- name: JobSpy
  rows: 9
  url: /applications/job-search/jobspy/
- name: JobSync
  rows: 8
  url: /applications/job-search/jobsync/
- name: LinkedIn
  rows: 7
  url: /applications/job-search/linkedin/
- name: Resume Matcher
  rows: 8
  url: /applications/job-search/resume-matcher/
sitemap: true
title: 'Reactive Resume: Job Search reference app'
---
