---
app: OpenSearch
app_slug: opensearch
app_url: https://github.com/opensearch-project/OpenSearch
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Aleph Alpha
  - Amazon Bedrock
  - Azure OpenAI
  - Cohere
  - Google Vertex AI
  - OpenAI
  - Yandex Cloud
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Amazon SageMaker
  - DeepSeek
  - Google Gemini
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  - Apache Kafka
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-110.40
  key: AE-110.40
  layer: domain
  name: Language & Document Understanding
  providers:
  - Amazon Comprehend
  - Amazon Textract
  url: /capabilities/language-document-understanding/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - AWS KMS
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - Amazon EC2
  - Google Compute Engine
  - Microsoft Azure (classic)
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - OpenTelemetry
  url: /capabilities/observability-management/
  via_parent: null
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
  declared: 13
  observed: 10
credits: []
evidence:
- route: documentation
  url: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
- route: source code
  url: https://github.com/opensearch-project/OpenSearch/tree/main/plugins
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.4
    band: exemplar
    in_catalog: true
    kin_score: 71.0
    mcp: &id007
      status: none
    slug: amazon-ec2
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Cloud Computing
    - Compute
    - Infrastructure-as-a-Service
    url: /providers/amazon-ec2/
  layer: common
  name: Amazon EC2
  provider: amazon-ec2
  says: ships the Amazon EC2 SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/discovery-ec2
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
    agent_readiness: 44.6
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id009
      status: none
    slug: kinesis
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
  layer: domain
  name: Amazon Kinesis
  provider: kinesis
  says: ships the Amazon Kinesis SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/ingestion-kinesis
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
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id012
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/repository-s3
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
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id017
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id018
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: domain
  name: Apache Kafka
  provider: apache-kafka
  says: ships the Apache Kafka SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/ingestion-kafka
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
    agent_readiness: 44.1
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id019
      status: none
    slug: amazon-kms
    status: profiled
    tags: &id020
    - Amazon Web Services
    - Cryptography
    - Data Protection
    - Encryption
    url: /providers/amazon-kms/
  layer: common
  name: AWS KMS
  provider: amazon-kms
  says: ships the AWS KMS SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/crypto-kms
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
    mcp: &id021
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id022
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/repository-azure
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
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/repository-gcs
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
    agent_readiness: 42.9
    band: strong
    in_catalog: true
    kin_score: 62.7
    mcp: &id031
      source: https://cloud.google.com/compute/docs/reference/mcp
      status: verified
    slug: google-cloud-compute-engine
    status: profiled
    tags: &id032
    - Compute
    - Google Cloud
    - Infrastructure
    - Infrastructure-as-a-Service
    url: /providers/google-cloud-compute-engine/
  layer: common
  name: Google Compute Engine
  provider: google-cloud-compute-engine
  says: ships the Google Compute Engine SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/discovery-gce
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
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id037
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id038
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: common
  name: Microsoft Azure (classic)
  provider: microsoft-azure
  says: ships the Microsoft Azure (classic) SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/discovery-azure-classic
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
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id043
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id044
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
  layer: common
  name: OpenTelemetry
  provider: opentelemetry
  says: ships the OpenTelemetry SDK or integration code
  source: https://github.com/opensearch-project/OpenSearch/tree/main/plugins/telemetry-otel
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
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 47.8
    mcp: &id001
      status: none
    slug: aleph-alpha
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Company
    - LLM
    - Machine Learning
    url: /providers/aleph-alpha/
  layer: domain
  name: Aleph Alpha
  provider: aleph-alpha
  says: lists Aleph Alpha as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
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
  says: lists Amazon Bedrock as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id005
      status: none
    slug: amazon-comprehend
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Machine Learning
    - Natural Language Processing
    - Text Analysis
    url: /providers/amazon-comprehend/
  layer: domain
  name: Amazon Comprehend
  provider: amazon-comprehend
  says: lists Amazon Comprehend as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    mcp: &id013
      source: https://github.com/awslabs/mcp/tree/main/src/sagemaker-ai-mcp-server
      status: verified
    slug: amazon-sagemaker
    status: profiled
    tags: &id014
    - Amazon Web Services
    - Artificial Intelligence
    - Inference
    - Machine Learning
    url: /providers/amazon-sagemaker/
  layer: domain
  name: Amazon SageMaker
  provider: amazon-sagemaker
  says: lists Amazon SageMaker as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.6
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id015
      status: none
    slug: amazon-textract
    status: profiled
    tags: &id016
    - Amazon Web Services
    - Document Processing
    - Machine Learning
    - OCR
    url: /providers/amazon-textract/
  layer: domain
  name: Amazon Textract
  provider: amazon-textract
  says: lists Amazon Textract as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    mcp: &id023
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: domain
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: lists Azure OpenAI as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    mcp: &id025
      status: none
    slug: cohere
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: domain
  name: Cohere
  provider: cohere
  says: lists Cohere as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    mcp: &id027
      status: none
    slug: deepseek
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: domain
  name: DeepSeek
  provider: deepseek
  says: lists DeepSeek as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    mcp: &id033
      status: none
    slug: google-gemini
    status: profiled
    tags: &id034
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: domain
  name: Google Gemini
  provider: google-gemini
  says: lists Google Gemini as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
    mcp: &id035
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: domain
  name: Google Vertex AI
  provider: google-vertex-ai
  says: lists Google Vertex AI as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
  layer: domain
  name: Ollama
  provider: ollama
  says: lists Ollama as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
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
  layer: domain
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id045
      status: unchecked
    slug: yandex-cloud
    status: queued for profiling
    tags: &id046 []
    url: null
  layer: domain
  name: Yandex Cloud
  provider: yandex-cloud
  says: lists Yandex Cloud as an integration
  source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/opensearch/
providers:
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 47.8
  mcp: *id001
  name: Aleph Alpha
  slug: aleph-alpha
  status: profiled
  tags: *id002
  url: /providers/aleph-alpha/
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id003
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id005
  name: Amazon Comprehend
  slug: amazon-comprehend
  status: profiled
  tags: *id006
  url: /providers/amazon-comprehend/
- agent_band: agent-native
  agent_readiness: 45.4
  band: exemplar
  in_catalog: true
  kin_score: 71.0
  mcp: *id007
  name: Amazon EC2
  slug: amazon-ec2
  status: profiled
  tags: *id008
  url: /providers/amazon-ec2/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id009
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id010
  url: /providers/kinesis/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id011
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id012
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 36.7
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id013
  name: Amazon SageMaker
  slug: amazon-sagemaker
  status: profiled
  tags: *id014
  url: /providers/amazon-sagemaker/
- agent_band: agent-native
  agent_readiness: 41.6
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id015
  name: Amazon Textract
  slug: amazon-textract
  status: profiled
  tags: *id016
  url: /providers/amazon-textract/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id017
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id018
  url: /providers/apache-kafka/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id019
  name: AWS KMS
  slug: amazon-kms
  status: profiled
  tags: *id020
  url: /providers/amazon-kms/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id021
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id022
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id023
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id024
  url: /providers/microsoft-azure-openai/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id025
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id026
  url: /providers/cohere/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id027
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id028
  url: /providers/deepseek/
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
  agent_readiness: 42.9
  band: strong
  in_catalog: true
  kin_score: 62.7
  mcp: *id031
  name: Google Compute Engine
  slug: google-cloud-compute-engine
  status: profiled
  tags: *id032
  url: /providers/google-cloud-compute-engine/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id033
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id034
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id035
  name: Google Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id036
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id037
  name: Microsoft Azure (classic)
  slug: microsoft-azure
  status: profiled
  tags: *id038
  url: /providers/microsoft-azure/
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
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id043
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id044
  url: /providers/opentelemetry/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id045
  name: Yandex Cloud
  slug: yandex-cloud
  status: queued for profiling
  tags: *id046
  url: null
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
title: 'OpenSearch: Site & App Search reference app'
---
