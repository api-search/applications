---
access: understanding
agent_layer: []
apps:
- anchor: jobspy
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: documentation
    url: https://github.com/speedyapply/JobSpy/blob/main/README.md
  - route: source code
    url: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Bayt
    provider: bayt
    says: ships the Bayt SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: BDJobs
    provider: bdjobs
    says: ships the BDJobs SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Glassdoor
    provider: glassdoor
    says: ships the Glassdoor SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Google Jobs
    provider: google
    says: ships the Google Jobs SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: HelloWork
    provider: hellowork
    says: ships the HelloWork SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Indeed
    provider: indeed
    says: ships the Indeed SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn Jobs
    provider: linkedin
    says: ships the LinkedIn Jobs SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Naukri
    provider: naukri
    says: ships the Naukri SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: ZipRecruiter
    provider: ziprecruiter
    says: ships the ZipRecruiter SDK or integration code
    source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
    tier: observed
  kind: self-hosted
  name: JobSpy
  page: /applications/job-search/jobspy/
  slug: jobspy
  url: https://github.com/speedyapply/JobSpy
- anchor: reactive-resume
  counts:
    declared: 1
    observed: 29
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
    layer: common
    name: Cloudflare R2
    provider: cloudflare
    says: lists Cloudflare R2 as an integration
    source: https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
    tier: declared
  kind: self-hosted
  name: Reactive Resume
  page: /applications/job-search/reactive-resume/
  slug: reactive-resume
  url: https://github.com/amruthpillai/reactive-resume
- anchor: jobsync
  counts:
    declared: 2
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/Gsync/jobsync/blob/main/package.json
  - route: documentation
    url: https://github.com/Gsync/jobsync/blob/main/README.md
  - route: source code
    url: https://github.com/Gsync/jobsync/blob/main/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: DeepSeek
    provider: deepseek
    says: ships the DeepSeek SDK or integration code
    source: https://github.com/Gsync/jobsync/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/Gsync/jobsync/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/Gsync/jobsync/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/Gsync/jobsync/blob/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: OpenObserve
    provider: openobserve
    says: ships the OpenObserve SDK or integration code
    source: https://github.com/Gsync/jobsync/blob/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/Gsync/jobsync/blob/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Greenhouse Job Board
    provider: greenhouse
    says: lists Greenhouse Job Board as an integration
    source: https://github.com/Gsync/jobsync/blob/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Lever Postings
    provider: lever
    says: lists Lever Postings as an integration
    source: https://github.com/Gsync/jobsync/blob/main/README.md
    tier: declared
  kind: self-hosted
  name: JobSync
  page: /applications/job-search/jobsync/
  slug: jobsync
  url: https://github.com/Gsync/jobsync
- anchor: resume-matcher
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: source code
    url: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Azure AI Foundry
    provider: microsoft-azure-openai
    says: ships the Azure AI Foundry SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: DeepSeek
    provider: deepseek
    says: ships the DeepSeek SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
    tier: observed
  kind: self-hosted
  name: Resume Matcher
  page: /applications/job-search/resume-matcher/
  slug: resume-matcher
  url: https://github.com/srbhr/Resume-Matcher
- anchor: indeed
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.indeed.android.jobsearch/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.indeed.android.jobsearch/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.indeed.android.jobsearch/latest/
    tier: observed
  kind: commercial
  name: Indeed
  page: /applications/job-search/indeed/
  slug: indeed
  url: https://www.indeed.com/
- anchor: linkedin
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
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
    name: Cedexis Radar
    provider: cedexis
    says: ships the Cedexis Radar SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
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
    name: Microsoft Visual Studio App Center
    provider: microsoft-app-center
    says: ships the Microsoft Visual Studio App Center SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
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
    name: Microsoft Visual Studio App Center
    provider: microsoft-app-center
    says: ships the Microsoft Visual Studio App Center SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
    tier: observed
  kind: commercial
  name: LinkedIn
  page: /applications/job-search/linkedin/
  slug: linkedin
  url: https://www.linkedin.com/jobs/
- anchor: glassdoor
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.glassdoor.app/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.glassdoor.app/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.glassdoor.app/latest/
    tier: observed
  kind: commercial
  name: Glassdoor
  page: /applications/job-search/glassdoor/
  slug: glassdoor
  url: https://www.glassdoor.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: job-search
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: job-search
  store: github-topics
  url: https://github.com/topics/job-search
name: Job Search
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Job Listings Search & Aggregation: LinkedIn Jobs, Indeed, Glassdoor, ZipRecruiter'
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: resume review, job matching, cover letters and tailoring in Reactive Resume, JobSync and Resume Matcher
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: Ollama for local, private resume processing
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: domain
  why: AI assistant researches companies and reads job pages
- capability:
    attribution: API Evangelist extension
    id: AE-230.40
    key: web-data
    name: Web Data
    url: /capabilities/web-data/
    via_parent: null
  fit: exact
  layer: domain
  why: page scraping of job listings (Firecrawl)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: sign-in with LinkedIn, Google, GitHub, Apple
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: resume PDFs and photos in object storage
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Redis queue and cache
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: .cv personal domains for published resumes
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: common
  why: UI translations
- capability:
    attribution: API Evangelist extension
    id: AE-170.80.10
    key: AE-170.80.10
    name: Web Fonts & Typography
    url: /capabilities/design-creative-editing/
    via_parent: Design & Creative Editing
  fit: exact
  layer: common
  why: resume typography
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: nearest
  layer: common
  why: mobile reminders
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: OTel traces and logs
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the channels themselves: every app publishes to and reads from social networks (also hosts the social-listening gap rows)'
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app customer feedback
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution SDKs in the Android apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.120
      key: AE-230.120
      name: Job Listings Search & Aggregation
      url: /capabilities/job-listings-search-aggregation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - JobSpy
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp: &id001
        status: none
      name: LinkedIn Jobs
      slug: linkedin
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags: &id002
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - JobSpy
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Jobs
      slug: google
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - JobSpy
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp:
        status: none
      name: Indeed
      slug: indeed
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Careers
      - Employment
      - Hiring
      - Job Search
      tier: observed
      url: /providers/indeed/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - JobSpy
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Glassdoor
      slug: glassdoor
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Employer Reviews
      - Job Search
      - Recruiting
      - Salaries
      tier: observed
      url: /providers/glassdoor/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - JobSpy
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: unknown
      name: ZipRecruiter
      slug: ziprecruiter
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Job
      - Job Board
      - Public APIs
      - Recruiting
      tier: observed
      url: /providers/ziprecruiter/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - JobSpy
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unchecked
      name: BDJobs
      slug: bdjobs
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/bdjobs/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - JobSpy
      band: minimal
      in_catalog: true
      kin_score: 7.2
      mcp:
        status: unchecked
      name: Bayt
      slug: bayt
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Careers
      - JobSite
      - Middle East
      - North-Africa
      tier: observed
      url: /providers/bayt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - JobSpy
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: Naukri
      slug: naukri
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Careers
      - Company
      - Job
      - Recruiting
      tier: observed
      url: /providers/naukri/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - JobSpy
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unchecked
      name: HelloWork
      slug: hellowork
      sources:
      - https://github.com/speedyapply/JobSpy/tree/main/jobspy
      status: profiled
      tags:
      - Company
      - Employment
      - Job Search
      - Recruiting
      tier: observed
      url: /providers/hellowork/
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - JobSync
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        status: none
      name: Greenhouse Job Board
      slug: greenhouse
      sources:
      - https://github.com/Gsync/jobsync/blob/main/README.md
      status: profiled
      tags:
      - Applicant Tracking
      - Greenhouse
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/greenhouse/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - JobSync
      band: strong
      in_catalog: true
      kin_score: 55.0
      mcp:
        status: unknown
      name: Lever Postings
      slug: lever
      sources:
      - https://github.com/Gsync/jobsync/blob/main/README.md
      status: profiled
      tags:
      - Applicant Tracking
      - Human Resources
      - Recruiting
      - Talent Acquisition
      tier: declared
      url: /providers/lever/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.20
      key: AE-230.40.20
      name: Web Search APIs
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.0
      apps:
      - Reactive Resume
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/exa-labs/exa-mcp-server
        status: verified
      name: Exa
      slug: exa-ai
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Neural Search
      - Search
      - Web Search
      tier: observed
      url: /providers/exa-ai/
    - agent_band: agent-ready
      agent_readiness: 45.6
      apps:
      - Reactive Resume
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        source: https://github.com/tavily-ai/tavily-mcp
        status: verified
      name: Tavily
      slug: tavily
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - AI Agents
      - LLM
      - Search
      - Web Search
      tier: observed
      url: /providers/tavily/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Reactive Resume
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: unchecked
      name: SearXNG
      slug: searxng
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Metasearch
      - Open Source
      - Privacy
      - Search
      tier: observed
      url: /providers/searxng/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.5
      apps:
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 34.6
      mcp:
        status: unchecked
      name: OlaCV
      slug: olacv
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - API Integration
      - Domain Registry
      - Marketplace
      - Premium Domains
      tier: observed
      url: /providers/olacv/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Reactive Resume
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp: *id001
      name: LinkedIn sign-in
      slug: linkedin
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/linkedin/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - LinkedIn
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40
      key: web-data
      name: Web Data
      url: /capabilities/web-data/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Reactive Resume
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://docs.firecrawl.dev/mcp-server
        status: verified
      name: Firecrawl
      slug: firecrawl
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Crawling
      - Data Extraction
      - URLs
      - Web Scraping
      tier: observed
      url: /providers/firecrawl/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Glassdoor
      - Indeed
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.glassdoor.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.indeed.android.jobsearch/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 45.5
      apps:
      - JobSync
      band: developing
      in_catalog: true
      kin_score: 41.6
      mcp:
        source: https://openobserve.ai/docs/integration/ai/mcp/
        status: verified
      name: OpenObserve
      slug: openobserve
      sources:
      - https://github.com/Gsync/jobsync/blob/main/.env.example
      status: profiled
      tags:
      - Logs
      - Metrics
      - Observability
      - Traces
      tier: observed
      url: /providers/openobserve/
    - agent_band: null
      agent_readiness: null
      apps:
      - LinkedIn
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Cedexis Radar
      slug: cedexis
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - LinkedIn
      band: null
      in_catalog: false
      kin_score: null
      mcp: &id007
        status: unchecked
      name: Microsoft Visual Studio App Center
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: queued for profiling
      tags: &id008 []
      tier: observed
      url: null
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
      - Reactive Resume
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub sign-in
      slug: github
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Reactive Resume
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
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
      - Reactive Resume
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - LinkedIn
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: profiled
      tags: *id004
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
      agent_readiness: 34.8
      apps:
      - Reactive Resume
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Reactive Resume
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel Blob
      slug: vercel
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 26.3
      mcp:
        status: none
      name: SeaweedFS
      slug: seaweedfs
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Company
      - Distributed File System
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/seaweedfs/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Reactive Resume
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare R2
      slug: cloudflare
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: declared
      url: /providers/cloudflare/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Indeed
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.indeed.android.jobsearch/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - LinkedIn
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: null
      agent_readiness: null
      apps:
      - LinkedIn
      band: null
      in_catalog: false
      kin_score: null
      mcp: *id007
      name: Microsoft Visual Studio App Center
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: queued for profiling
      tags: *id008
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - LinkedIn
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Reactive Resume
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Glassdoor
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.glassdoor.app/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.5
      apps:
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 30.6
      mcp:
        source: https://github.com/expo/expo-mcp
        status: verified
      name: Expo
      slug: expo
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/apps/mobile/package.json
      status: profiled
      tags:
      - Build Automation
      - Mobile Development
      - Over-the-Air Updates
      - React Native
      tier: observed
      url: /providers/expo/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://mcp.crowdin.com/v2/mcp
        status: verified
      name: Crowdin
      slug: crowdin
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - Localization
      - REST
      - TMS
      - Translation
      tier: observed
      url: /providers/crowdin/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Reactive Resume
      band: developing
      in_catalog: true
      kin_score: 54.2
      mcp:
        status: none
      name: Google Fonts
      slug: google-fonts
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/.env.example
      status: profiled
      tags:
      - CSS
      - Design
      - Fonts
      - Google Fonts
      tier: observed
      url: /providers/google-fonts/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - JobSync
      - Reactive Resume
      - Resume Matcher
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/Gsync/jobsync/blob/main/package.json
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - JobSync
      - Reactive Resume
      - Resume Matcher
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/Gsync/jobsync/blob/main/package.json
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - JobSync
      - Reactive Resume
      - Resume Matcher
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/Gsync/jobsync/blob/main/package.json
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Reactive Resume
      - Resume Matcher
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - JobSync
      - Resume Matcher
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/Gsync/jobsync/blob/main/.env.example
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - Reactive Resume
      - Resume Matcher
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Resume Matcher
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure AI Foundry
      slug: microsoft-azure-openai
      sources:
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - Reactive Resume
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - Reactive Resume
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Cerebras
      slug: cerebras-systems
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - AI Infrastructure
      - Artificial Intelligence
      - Company
      - Machine Learning
      tier: observed
      url: /providers/cerebras-systems/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Reactive Resume
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral
      slug: mistral
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
        status: verified
      name: Fireworks AI
      slug: fireworks-ai
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
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
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://docs.together.ai/docs/mcp
        status: verified
      name: Together AI
      slug: together-ai
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Inference
      - LLM
      tier: observed
      url: /providers/together-ai/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Reactive Resume
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: none
      name: xAI
      slug: xai
      sources:
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: observed
      url: /providers/xai/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - JobSync
      - Reactive Resume
      - Resume Matcher
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/Gsync/jobsync/blob/main/package.json
      - https://github.com/amruthpillai/reactive-resume/blob/main/packages/api/package.json
      - https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
  layer: agent
summary:
  coverage_pct: 95.9
  declared_only: 3
  distinct_providers: 49
  in_catalog: 47
  mcp:
    documented: 0
    none: 17
    unchecked: 7
    verified: 22
  mcp_verified: 22
  mean_kin_score: 47.3
  observed: 46
  queued: 2
  reference_apps: 7
title: 'Job Search: application blueprint'
---
