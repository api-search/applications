---
app: Elasticsearch
app_slug: elasticsearch
app_url: https://github.com/elastic/elasticsearch
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Alibaba Cloud AI Search
  - Cohere
  - Contextual AI
  - Google Vertex AI
  - Hugging Face
  - IBM watsonx
  - Jina AI
  - Mistral
  - NVIDIA
  - OpenAI
  - Tencent Cloud
  - Voyage AI
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - AI21
  - Amazon Bedrock
  - Amazon SageMaker
  - Anthropic
  - Azure AI Studio
  - Azure OpenAI
  - DeepSeek
  - Fireworks AI
  - Google AI Studio
  - Groq
  - OpenShift AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: search-engine
  name: Site & App Search
  url: /applications/search-engine/
counts:
  declared: 0
  observed: 26
credits: []
evidence:
- route: source code
  url: https://github.com/elastic/elasticsearch/tree/main/modules
- route: source code
  url: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 39.7
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
  name: AI21
  provider: ai21-labs
  says: ships the AI21 SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_band: human-only
    agent_readiness: 3.4
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id003
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibaba
    status: profiled
    tags: &id004
    - Cloud
    - Cloud Computing
    - Commerce
    - E-Commerce
    url: /providers/alibaba/
  layer: domain
  name: Alibaba Cloud AI Search
  provider: alibaba
  says: ships the Alibaba Cloud AI Search SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: domain
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/modules/repository-s3
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
    agent_readiness: 36.7
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id009
      source: https://github.com/awslabs/mcp/tree/main/src/sagemaker-ai-mcp-server
      status: verified
    slug: amazon-sagemaker
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Artificial Intelligence
    - Inference
    - Machine Learning
    url: /providers/amazon-sagemaker/
  layer: domain
  name: Amazon SageMaker
  provider: amazon-sagemaker
  says: ships the Amazon SageMaker SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    mcp: &id011
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id012
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: domain
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id013
      source: https://github.com/microsoft-foundry/mcp-foundry
      status: verified
    slug: azure-ai-foundry
    status: profiled
    tags: &id014
    - AI Agents
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/azure-ai-foundry/
  layer: domain
  name: Azure AI Studio
  provider: azure-ai-foundry
  says: ships the Azure AI Studio SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id016
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/modules/repository-azure
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
    agent_readiness: 29.9
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id017
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: domain
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 40.6
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id019
      status: none
    slug: cohere
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: domain
  name: Cohere
  provider: cohere
  says: ships the Cohere SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 28.7
    band: developing
    in_catalog: true
    kin_score: 43.9
    mcp: &id021
      source: https://github.com/ContextualAI/contextual-mcp-server
      status: verified
    slug: contextual-ai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Grounded Language Model
    - LLM
    - RAG
    url: /providers/contextual-ai/
  layer: domain
  name: Contextual AI
  provider: contextual-ai
  says: ships the Contextual AI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    mcp: &id023
      status: none
    slug: deepseek
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: domain
  name: DeepSeek
  provider: deepseek
  says: ships the DeepSeek SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
  layer: domain
  name: Google AI Studio
  provider: google-gemini
  says: ships the Google AI Studio SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id029
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id030
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/modules/repository-gcs
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
    mcp: &id031
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: domain
  name: Google Vertex AI
  provider: google-vertex-ai
  says: ships the Google Vertex AI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 36.9
    band: exemplar
    in_catalog: true
    kin_score: 69.1
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
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id037
      status: none
    slug: ibm-watson
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - IBM
    - Machine Learning
    - Natural Language Processing
    url: /providers/ibm-watson/
  layer: domain
  name: IBM watsonx
  provider: ibm-watson
  says: ships the IBM watsonx SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 37.1
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id039
      source: https://github.com/jina-ai/MCP
      status: verified
    slug: jina-ai
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Embeddings
    - Machine Learning
    - Reranking
    url: /providers/jina-ai/
  layer: domain
  name: Jina AI
  provider: jina-ai
  says: ships the Jina AI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id041
      status: none
    slug: mistral
    status: profiled
    tags: &id042
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: domain
  name: Mistral
  provider: mistral
  says: ships the Mistral SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 5.2
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id043
      status: none
    slug: nvidia
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - Computing
    - GPU
    - Machine Learning
    url: /providers/nvidia/
  layer: domain
  name: NVIDIA
  provider: nvidia
  says: ships the NVIDIA SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id047
      source: https://github.com/openshift/kubernetes-mcp-server
      status: verified
    slug: red-hat-openshift
    status: profiled
    tags: &id048
    - Containers
    - Enterprise
    - Hybrid Cloud
    - Kubernetes
    url: /providers/red-hat-openshift/
  layer: domain
  name: OpenShift AI
  provider: red-hat-openshift
  says: ships the OpenShift AI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id049
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
  layer: domain
  name: Tencent Cloud
  provider: tencentcloud
  says: ships the Tencent Cloud SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
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
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 24.2
    mcp: &id051
      status: none
    slug: voyage-ai
    status: profiled
    tags: &id052
    - Embeddings
    - RAG
    - Rerankers
    - Semantic Search
    url: /providers/voyage-ai/
  layer: domain
  name: Voyage AI
  provider: voyage-ai
  says: ships the Voyage AI SDK or integration code
  source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/elasticsearch/
providers:
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id001
  name: AI21
  slug: ai21-labs
  status: profiled
  tags: *id002
  url: /providers/ai21-labs/
- agent_band: human-only
  agent_readiness: 3.4
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id003
  name: Alibaba Cloud AI Search
  slug: alibaba
  status: profiled
  tags: *id004
  url: /providers/alibaba/
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id005
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id006
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id007
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id008
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 36.7
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id009
  name: Amazon SageMaker
  slug: amazon-sagemaker
  status: profiled
  tags: *id010
  url: /providers/amazon-sagemaker/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id011
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id012
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id013
  name: Azure AI Studio
  slug: azure-ai-foundry
  status: profiled
  tags: *id014
  url: /providers/azure-ai-foundry/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id015
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id017
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id018
  url: /providers/microsoft-azure-openai/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id019
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id020
  url: /providers/cohere/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id021
  name: Contextual AI
  slug: contextual-ai
  status: profiled
  tags: *id022
  url: /providers/contextual-ai/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id023
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id024
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id025
  name: Fireworks AI
  slug: fireworks-ai
  status: profiled
  tags: *id026
  url: /providers/fireworks-ai/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id027
  name: Google AI Studio
  slug: google-gemini
  status: profiled
  tags: *id028
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id029
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id030
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id031
  name: Google Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id032
  url: /providers/google-vertex-ai/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id033
  name: Groq
  slug: groq
  status: profiled
  tags: *id034
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id035
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id036
  url: /providers/hugging-face/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id037
  name: IBM watsonx
  slug: ibm-watson
  status: profiled
  tags: *id038
  url: /providers/ibm-watson/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id039
  name: Jina AI
  slug: jina-ai
  status: profiled
  tags: *id040
  url: /providers/jina-ai/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id041
  name: Mistral
  slug: mistral
  status: profiled
  tags: *id042
  url: /providers/mistral/
- agent_band: agent-aware
  agent_readiness: 5.2
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id043
  name: NVIDIA
  slug: nvidia
  status: profiled
  tags: *id044
  url: /providers/nvidia/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id045
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id046
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id047
  name: OpenShift AI
  slug: red-hat-openshift
  status: profiled
  tags: *id048
  url: /providers/red-hat-openshift/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id049
  name: Tencent Cloud
  slug: tencentcloud
  status: profiled
  tags: *id050
  url: /providers/tencentcloud/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 24.2
  mcp: *id051
  name: Voyage AI
  slug: voyage-ai
  status: profiled
  tags: *id052
  url: /providers/voyage-ai/
siblings:
- name: Algolia
  rows: 7
  url: /applications/search-engine/algolia/
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
- name: Typesense
  rows: 5
  url: /applications/search-engine/typesense/
sitemap: true
title: 'Elasticsearch: Site & App Search reference app'
---
