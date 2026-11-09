---
app: n8n
app_slug: n8n
app_url: https://github.com/n8n-io/n8n
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Snowflake (snowflake-sdk)
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Confluent (@confluentinc/kafka-javascript, schema registry)
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Discord (@chat-adapter/discord)
  - Microsoft Teams (@chat-adapter/teams)
  - Slack (@chat-adapter/slack)
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - MongoDB
  - Oracle Database (oracledb)
  - SQL Server (mssql)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Linear (@chat-adapter/linear)
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram (@chat-adapter/telegram)
  - WhatsApp (@chat-adapter/whatsapp)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - 1Password Connect
  - AWS Secrets Manager
  - Azure Key Vault
  - Google Cloud Secret Manager
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - AWS (@aws-sdk/credential-providers)
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry (@sentry/node)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog (posthog-node)
  - RudderStack
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.60.20
  key: AE-100.60.20
  layer: agent
  name: Agent Observability
  providers:
  - LangSmith
  url: /capabilities/agent-quality-operations/
  via_parent: Agent Quality & Operations
- attribution: API Evangelist extension
  id: AE-100.20.30
  key: AE-100.20.30
  layer: agent
  name: Agent Runtime & Memory
  providers:
  - Zep (@getzep/zep-cloud)
  url: /capabilities/agent-to-agent-interoperability/
  via_parent: Agent-to-Agent Interoperability
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Anthropic (@langchain/anthropic)
  - Cohere
  - Google Gemini (@google/genai, @langchain/google-genai)
  - Groq
  - Hugging Face (@huggingface/inference)
  - Mistral AI
  - Ollama
  - OpenAI
  - Vertex AI (@langchain/google-vertexai)
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.60.20
  key: AE-110.60.20
  layer: agent
  name: Vector Search
  providers:
  - Azure AI Search (@azure/search-documents)
  - Chroma
  - Milvus (@zilliz/milvus2-sdk-node)
  - Pinecone
  - Qdrant
  - Supabase (vector store)
  - Weaviate
  - Xata
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
category:
  id: workflow-automation
  name: Workflow Automation & iPaaS
  url: /applications/workflow-automation/
counts:
  declared: 0
  observed: 39
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
- route: dependency manifest
  url: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
- route: dependency manifest
  url: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id001
      source: https://1password.dev/environments/mcp-server
      status: verified
    slug: 1password
    status: profiled
    tags: &id002
    - Password Manager
    - Passwords
    - Secrets
    - Security
    url: /providers/1password/
  layer: common
  name: 1Password Connect
  provider: 1password
  says: ships the 1Password Connect SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
  layer: agent
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
  layer: agent
  name: Anthropic (@langchain/anthropic)
  provider: anthropic
  says: ships the Anthropic (@langchain/anthropic) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id008
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS (@aws-sdk/credential-providers)
  provider: amazon-web-services
  says: ships the AWS (@aws-sdk/credential-providers) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id009
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Configuration
    - Credentials
    - Rotation
    url: /providers/amazon-secrets-manager/
  layer: common
  name: AWS Secrets Manager
  provider: amazon-secrets-manager
  says: ships the AWS Secrets Manager SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: azure-ai-search
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Cloud
    - Microsoft Azure
    - Search
    url: /providers/azure-ai-search/
  layer: agent
  name: Azure AI Search (@azure/search-documents)
  provider: azure-ai-search
  says: ships the Azure AI Search (@azure/search-documents) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 53.3
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-key-vault
    status: profiled
    tags: &id014
    - Certificates
    - Cloud Security
    - Cryptography
    - Key Management
    url: /providers/microsoft-azure-key-vault/
  layer: common
  name: Azure Key Vault
  provider: microsoft-azure-key-vault
  says: ships the Azure Key Vault SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    mcp: &id015
      source: https://github.com/chroma-core/chroma-mcp
      status: verified
    slug: chroma
    status: profiled
    tags: &id016
    - AI-native
    - Apache 2.0
    - Artificial Intelligence
    - Cloud
    url: /providers/chroma/
  layer: agent
  name: Chroma
  provider: chroma
  says: ships the Chroma SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
  layer: agent
  name: Cohere
  provider: cohere
  says: ships the Cohere SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.2
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id019
      source: https://github.com/confluentinc/mcp-confluent
      status: verified
    slug: confluent
    status: profiled
    tags: &id020
    - Apache Kafka
    - Data Streaming
    - Event Streaming
    - Stream Processing
    url: /providers/confluent/
  layer: domain
  name: Confluent (@confluentinc/kafka-javascript, schema registry)
  provider: confluent
  says: ships the Confluent (@confluentinc/kafka-javascript, schema registry) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
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
    mcp: &id021
      status: none
    slug: discord
    status: profiled
    tags: &id022
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord (@chat-adapter/discord)
  provider: discord
  says: ships the Discord (@chat-adapter/discord) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id023
      status: none
    slug: google-cloud-secret-manager
    status: profiled
    tags: &id024
    - Configuration
    - Credentials
    - Google Cloud
    - Key Management
    url: /providers/google-cloud-secret-manager/
  layer: common
  name: Google Cloud Secret Manager
  provider: google-cloud-secret-manager
  says: ships the Google Cloud Secret Manager SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    mcp: &id025
      status: none
    slug: google-gemini
    status: profiled
    tags: &id026
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini (@google/genai, @langchain/google-genai)
  provider: google-gemini
  says: ships the Google Gemini (@google/genai, @langchain/google-genai) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    mcp: &id027
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
  layer: agent
  name: Groq
  provider: groq
  says: ships the Groq SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    mcp: &id029
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id030
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
  layer: agent
  name: Hugging Face (@huggingface/inference)
  provider: hugging-face
  says: ships the Hugging Face (@huggingface/inference) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    agent_readiness: 31.9
    band: thin
    in_catalog: true
    kin_score: 38.5
    mcp: &id031
      source: https://github.com/langchain-ai/langsmith-mcp-server
      status: verified
    slug: langsmith
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Evaluation
    - LLM
    - Observability
    url: /providers/langsmith/
  layer: agent
  name: LangSmith
  provider: langsmith
  says: ships the LangSmith SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id033
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id034
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear (@chat-adapter/linear)
  provider: linear-app
  says: ships the Linear (@chat-adapter/linear) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id035
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id036
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams (@chat-adapter/teams)
  provider: microsoft-teams
  says: ships the Microsoft Teams (@chat-adapter/teams) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
  layer: agent
  name: Milvus (@zilliz/milvus2-sdk-node)
  provider: milvus
  says: ships the Milvus (@zilliz/milvus2-sdk-node) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
  layer: agent
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    agent_readiness: 56.0
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id041
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id042
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: domain
  name: MongoDB
  provider: mongodb
  says: ships the MongoDB SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
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
    mcp: &id043
      status: none
    slug: ollama
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    mcp: &id045
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id047
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id048
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Database (oracledb)
  provider: oracle
  says: ships the Oracle Database (oracledb) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
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
    mcp: &id049
      source: https://github.com/pinecone-io/pinecone-mcp
      status: verified
    slug: pinecone
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - Embeddings
    - RAG
    - Vector Search
    url: /providers/pinecone/
  layer: agent
  name: Pinecone
  provider: pinecone
  says: ships the Pinecone SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    mcp: &id051
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id052
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog (posthog-node)
  provider: posthog
  says: ships the PostHog (posthog-node) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    mcp: &id053
      source: https://github.com/qdrant/mcp-server-qdrant
      status: verified
    slug: qdrant
    status: profiled
    tags: &id054
    - Artificial Intelligence
    - Database
    - Vector Search
    url: /providers/qdrant/
  layer: agent
  name: Qdrant
  provider: qdrant
  says: ships the Qdrant SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    agent_readiness: 58.1
    band: exemplar
    in_catalog: true
    kin_score: 78.5
    mcp: &id055
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id056
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
  layer: common
  name: RudderStack
  provider: rudderstack
  says: ships the RudderStack SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id057
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id058
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry (@sentry/node)
  provider: sentry-system
  says: ships the Sentry (@sentry/node) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    mcp: &id059
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id060
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack (@chat-adapter/slack)
  provider: slack
  says: ships the Slack (@chat-adapter/slack) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id061
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id062
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake (snowflake-sdk)
  provider: snowflake
  says: ships the Snowflake (snowflake-sdk) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id063
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id064
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: domain
  name: SQL Server (mssql)
  provider: microsoft-sql-server
  says: ships the SQL Server (mssql) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
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
    agent_readiness: 48.1
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id065
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id066
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
  layer: agent
  name: Supabase (vector store)
  provider: supabase
  says: ships the Supabase (vector store) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    mcp: &id067
      status: none
    slug: telegram
    status: profiled
    tags: &id068
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram (@chat-adapter/telegram)
  provider: telegram
  says: ships the Telegram (@chat-adapter/telegram) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    mcp: &id069
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id070
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: agent
  name: Vertex AI (@langchain/google-vertexai)
  provider: google-vertex-ai
  says: ships the Vertex AI (@langchain/google-vertexai) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    mcp: &id071
      source: https://github.com/weaviate/mcp-server-weaviate
      status: verified
    slug: weaviate
    status: profiled
    tags: &id072
    - Artificial Intelligence
    - Machine Learning
    - Semantic Search
    - Vector Search
    url: /providers/weaviate/
  layer: agent
  name: Weaviate
  provider: weaviate
  says: ships the Weaviate SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
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
    agent_band: agent-ready
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id073
      status: none
    slug: whatsapp
    status: profiled
    tags: &id074
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp (@chat-adapter/whatsapp)
  provider: whatsapp
  says: ships the WhatsApp (@chat-adapter/whatsapp) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
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
    agent_readiness: 35.6
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id075
      source: https://github.com/xataio/mcp
      status: verified
    slug: xata
    status: profiled
    tags: &id076
    - Database
    - Developer Tools
    - PostgreSQL
    - Serverless
    url: /providers/xata/
  layer: agent
  name: Xata
  provider: xata
  says: ships the Xata SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.20.30
    key: AE-100.20.30
    name: Agent Runtime & Memory
    url: /capabilities/agent-to-agent-interoperability/
    via_parent: Agent-to-Agent Interoperability
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.4
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id077
      source: https://github.com/getzep/graphiti/tree/main/mcp_server
      status: verified
    slug: zep
    status: profiled
    tags: &id078
    - AI Agents
    - Knowledge Graph
    - Memory
    - Temporal Graph
    url: /providers/zep/
  layer: agent
  name: Zep (@getzep/zep-cloud)
  provider: zep
  says: ships the Zep (@getzep/zep-cloud) SDK or integration code
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/workflow-automation/n8n/
providers:
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id001
  name: 1Password Connect
  slug: 1password
  status: profiled
  tags: *id002
  url: /providers/1password/
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
  name: Anthropic (@langchain/anthropic)
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id007
  name: AWS (@aws-sdk/credential-providers)
  slug: amazon-web-services
  status: profiled
  tags: *id008
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id009
  name: AWS Secrets Manager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id010
  url: /providers/amazon-secrets-manager/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id011
  name: Azure AI Search (@azure/search-documents)
  slug: azure-ai-search
  status: profiled
  tags: *id012
  url: /providers/azure-ai-search/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 53.3
  mcp: *id013
  name: Azure Key Vault
  slug: microsoft-azure-key-vault
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-key-vault/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id015
  name: Chroma
  slug: chroma
  status: profiled
  tags: *id016
  url: /providers/chroma/
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
  agent_readiness: 46.2
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id019
  name: Confluent (@confluentinc/kafka-javascript, schema registry)
  slug: confluent
  status: profiled
  tags: *id020
  url: /providers/confluent/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id021
  name: Discord (@chat-adapter/discord)
  slug: discord
  status: profiled
  tags: *id022
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id023
  name: Google Cloud Secret Manager
  slug: google-cloud-secret-manager
  status: profiled
  tags: *id024
  url: /providers/google-cloud-secret-manager/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id025
  name: Google Gemini (@google/genai, @langchain/google-genai)
  slug: google-gemini
  status: profiled
  tags: *id026
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id027
  name: Groq
  slug: groq
  status: profiled
  tags: *id028
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id029
  name: Hugging Face (@huggingface/inference)
  slug: hugging-face
  status: profiled
  tags: *id030
  url: /providers/hugging-face/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: thin
  in_catalog: true
  kin_score: 38.5
  mcp: *id031
  name: LangSmith
  slug: langsmith
  status: profiled
  tags: *id032
  url: /providers/langsmith/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id033
  name: Linear (@chat-adapter/linear)
  slug: linear-app
  status: profiled
  tags: *id034
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id035
  name: Microsoft Teams (@chat-adapter/teams)
  slug: microsoft-teams
  status: profiled
  tags: *id036
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id037
  name: Milvus (@zilliz/milvus2-sdk-node)
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
  agent_readiness: 56.0
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id041
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id042
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id043
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id044
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id045
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id046
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id047
  name: Oracle Database (oracledb)
  slug: oracle
  status: profiled
  tags: *id048
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 61.2
  mcp: *id049
  name: Pinecone
  slug: pinecone
  status: profiled
  tags: *id050
  url: /providers/pinecone/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id051
  name: PostHog (posthog-node)
  slug: posthog
  status: profiled
  tags: *id052
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id053
  name: Qdrant
  slug: qdrant
  status: profiled
  tags: *id054
  url: /providers/qdrant/
- agent_band: agent-ready
  agent_readiness: 58.1
  band: exemplar
  in_catalog: true
  kin_score: 78.5
  mcp: *id055
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id056
  url: /providers/rudderstack/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id057
  name: Sentry (@sentry/node)
  slug: sentry-system
  status: profiled
  tags: *id058
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id059
  name: Slack (@chat-adapter/slack)
  slug: slack
  status: profiled
  tags: *id060
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id061
  name: Snowflake (snowflake-sdk)
  slug: snowflake
  status: profiled
  tags: *id062
  url: /providers/snowflake/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id063
  name: SQL Server (mssql)
  slug: microsoft-sql-server
  status: profiled
  tags: *id064
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id065
  name: Supabase (vector store)
  slug: supabase
  status: profiled
  tags: *id066
  url: /providers/supabase/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id067
  name: Telegram (@chat-adapter/telegram)
  slug: telegram
  status: profiled
  tags: *id068
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id069
  name: Vertex AI (@langchain/google-vertexai)
  slug: google-vertex-ai
  status: profiled
  tags: *id070
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id071
  name: Weaviate
  slug: weaviate
  status: profiled
  tags: *id072
  url: /providers/weaviate/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id073
  name: WhatsApp (@chat-adapter/whatsapp)
  slug: whatsapp
  status: profiled
  tags: *id074
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id075
  name: Xata
  slug: xata
  status: profiled
  tags: *id076
  url: /providers/xata/
- agent_band: agent-aware
  agent_readiness: 15.4
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id077
  name: Zep (@getzep/zep-cloud)
  slug: zep
  status: profiled
  tags: *id078
  url: /providers/zep/
siblings:
- name: Activepieces
  rows: 15
  url: /applications/workflow-automation/activepieces/
- name: Automatisch
  rows: 76
  url: /applications/workflow-automation/automatisch/
- name: Huginn
  rows: 25
  url: /applications/workflow-automation/huginn/
- name: IFTTT
  rows: 3
  url: /applications/workflow-automation/ifttt/
- name: Microsoft Power Automate
  rows: 1
  url: /applications/workflow-automation/microsoft-power-automate/
- name: Windmill
  rows: 12
  url: /applications/workflow-automation/windmill/
sitemap: true
title: 'n8n: Workflow Automation & iPaaS reference app'
---
