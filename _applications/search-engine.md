---
access: understanding
agent_layer: []
apps:
- anchor: meilisearch
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/Cargo.toml
  - route: source code
    url: https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/src/analytics/segment_analytics.rs
  - route: source code
    url: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Hugging Face
    provider: hugging-face
    says: ships the Hugging Face SDK or integration code
    source: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
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
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
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
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
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
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/src/analytics/segment_analytics.rs
    tier: observed
  kind: self-hosted
  name: Meilisearch
  page: /applications/search-engine/meilisearch/
  slug: meilisearch
  url: https://github.com/meilisearch/meilisearch
- anchor: typesense
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: source code
    url: https://github.com/typesense/typesense/blob/HEAD/src/conversation_model.cpp
  - route: source code
    url: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    source: https://github.com/typesense/typesense/blob/HEAD/src/conversation_model.cpp
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
    name: Google (Gemini API)
    provider: google-gemini
    says: ships the Google (Gemini API) SDK or integration code
    source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    name: Google Cloud Vertex AI
    provider: google-vertex-ai
    says: ships the Google Cloud Vertex AI SDK or integration code
    source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
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
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
    tier: observed
  kind: self-hosted
  name: Typesense
  page: /applications/search-engine/typesense/
  slug: typesense
  url: https://github.com/typesense/typesense
- anchor: elasticsearch
  counts:
    declared: 0
    observed: 26
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
    layer: domain
    name: Voyage AI
    provider: voyage-ai
    says: ships the Voyage AI SDK or integration code
    source: https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
    tier: observed
  kind: open-source-saas
  name: Elasticsearch
  page: /applications/search-engine/elasticsearch/
  slug: elasticsearch
  url: https://github.com/elastic/elasticsearch
- anchor: opensearch
  counts:
    declared: 13
    observed: 10
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
    layer: domain
    name: Yandex Cloud
    provider: yandex-cloud
    says: lists Yandex Cloud as an integration
    source: https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
    tier: declared
  kind: self-hosted
  name: OpenSearch
  page: /applications/search-engine/opensearch/
  slug: opensearch
  url: https://github.com/opensearch-project/OpenSearch
- anchor: quickwit
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: source code
    url: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
  - route: source code
    url: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Amazon Kinesis
    provider: kinesis
    says: ships the Amazon Kinesis SDK or integration code
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
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
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/object_storage
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Amazon SQS
    provider: amazon-sqs
    says: ships the Amazon SQS SDK or integration code
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source/queue_sources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Apache Kafka
    provider: apache-kafka
    says: ships the Apache Kafka SDK or integration code
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Apache Pulsar
    provider: apache-pulsar
    says: ships the Apache Pulsar SDK or integration code
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
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
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/object_storage
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Google Cloud Pub/Sub
    provider: google-cloud-pubsub
    says: ships the Google Cloud Pub/Sub SDK or integration code
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
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
    source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/opendal_storage
    tier: observed
  kind: self-hosted
  name: Quickwit
  page: /applications/search-engine/quickwit/
  slug: quickwit
  url: https://github.com/quickwit-oss/quickwit
- anchor: searxng
  counts:
    declared: 0
    observed: 49
  evidence:
  - route: source code
    url: https://github.com/searxng/searxng/tree/master/searx/engines
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    credit: null
    layer: domain
    name: arXiv
    provider: arxiv
    says: ships the arXiv SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/arxiv.py
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
    name: Brave Search API
    provider: brave-browser
    says: ships the Brave Search API SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/braveapi.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: crates.io
    provider: crates-io
    says: ships the crates.io SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/crates.py
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
    name: Crossref
    provider: crossref
    says: ships the Crossref SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/crossref.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Dailymotion
    provider: dailymotion
    says: ships the Dailymotion SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/dailymotion.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: DeepL
    provider: deepl
    says: ships the DeepL SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/deepl.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Deezer
    provider: deezer
    says: ships the Deezer SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/deezer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Docker Hub
    provider: docker-hub
    says: ships the Docker Hub SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/docker_hub.py
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
    source: https://github.com/searxng/searxng/blob/master/searx/engines/exaapi.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Flickr
    provider: flickr
    says: ships the Flickr SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/flickr.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Freesound
    provider: freesound
    says: ships the Freesound SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/freesound.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Genius
    provider: genius
    says: ships the Genius SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/genius.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: GIPHY
    provider: giphy
    says: ships the GIPHY SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/giphy.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/github.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/gitlab.py
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
    name: Google Programmable Search
    provider: google-custom-search
    says: ships the Google Programmable Search SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/google_cse.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Hacker News
    provider: hacker-news
    says: ships the Hacker News SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/hackernews.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.70
      key: AE-110.70
      name: Model Training & Data
      url: /capabilities/model-training-data/
      via_parent: null
    credit: null
    layer: domain
    name: Hugging Face Hub
    provider: hugging-face
    says: ships the Hugging Face Hub SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/huggingface.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Imgur
    provider: imgur
    says: ships the Imgur SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/imgur.py
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
    name: Jina AI
    provider: jina-ai
    says: ships the Jina AI SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/jina.py
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
    name: Kagi
    provider: kagi
    says: ships the Kagi SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/kagi.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Lemmy
    provider: lemmy
    says: ships the Lemmy SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/lemmy.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: LibreTranslate
    provider: libre-translate
    says: ships the LibreTranslate SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/libretranslate.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Mastodon
    provider: mastodon
    says: ships the Mastodon SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/mastodon.py
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
    name: Microsoft Bing
    provider: microsoft-bing
    says: ships the Microsoft Bing SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/bing.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Mixcloud
    provider: mixcloud
    says: ships the Mixcloud SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/mixcloud.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: npm
    provider: npm
    says: ships the npm SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/npm.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Open-Meteo
    provider: open-meteo
    says: ships the Open-Meteo SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/open_meteo.py
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
    name: OpenAlex
    provider: openalex
    says: ships the OpenAlex SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/openalex.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: ships the OpenStreetMap SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/openstreetmap.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Openverse
    provider: openverse
    says: ships the Openverse SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/openverse.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: PeerTube
    provider: peertube
    says: ships the PeerTube SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/peertube.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Pexels
    provider: pexels
    says: ships the Pexels SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/pexels.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Pixabay
    provider: pixabay
    says: ships the Pixabay SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/pixabay.py
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
    name: PubMed
    provider: pubmed
    says: ships the PubMed SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/pubmed.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: PyPI
    provider: pypi
    says: ships the PyPI SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/pypi.py
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
    name: Semantic Scholar
    provider: semantic-scholar
    says: ships the Semantic Scholar SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/semantic_scholar.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: SoundCloud
    provider: soundcloud
    says: ships the SoundCloud SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/soundcloud.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/spotify.py
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
    name: Springer Nature
    provider: springer-nature
    says: ships the Springer Nature SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/springer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Stack Exchange
    provider: stackexchange
    says: ships the Stack Exchange SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/stackexchange.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: TinEye
    provider: tineye
    says: ships the TinEye SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/tineye.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/unsplash.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Vimeo
    provider: vimeo
    says: ships the Vimeo SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/vimeo.py
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
    name: Wikidata
    provider: wikidata
    says: ships the Wikidata SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/wikidata.py
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
    name: Wikipedia
    provider: wikipedia
    says: ships the Wikipedia SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/wikipedia.py
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
    name: Wolfram|Alpha
    provider: wolframalpha
    says: ships the Wolfram|Alpha SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/wolframalpha_api.py
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
    name: Yandex Search API
    provider: yandex
    says: ships the Yandex Search API SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/yandex_api.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube Data API
    provider: youtube
    says: ships the YouTube Data API SDK or integration code
    source: https://github.com/searxng/searxng/blob/master/searx/engines/youtube_api.py
    tier: observed
  kind: self-hosted
  name: SearXNG
  page: /applications/search-engine/searxng/
  slug: searxng
  url: https://github.com/searxng/searxng
- anchor: algolia
  counts:
    declared: 7
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.20
      key: AE-140.10.20
      name: Headless & Composable Commerce
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: BigCommerce
    provider: bigcommerce
    says: lists BigCommerce as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.20
      key: AE-140.10.20
      name: Headless & Composable Commerce
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: commercetools
    provider: commercetools
    says: lists commercetools as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elastic
    says: lists Elasticsearch as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: lists Google BigQuery as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MySQL
    provider: mysql
    says: lists MySQL as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Supabase
    provider: supabase
    says: lists Supabase as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk Knowledge Base
    provider: zendesk
    says: lists Zendesk Knowledge Base as an integration
    source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
    tier: declared
  kind: commercial
  name: Algolia
  page: /applications/search-engine/algolia/
  slug: algolia
  url: https://www.algolia.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: search-engine
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Search Engines
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#search-engines
- category: Store design
  store: shopify-app-store
  url: https://apps.shopify.com/categories
name: Site & App Search
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: domain
  why: vector/semantic search needs a remote embedder
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: engine telemetry to a CDP
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: RAG answers, conversational search, natural-language query parsing
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: snapshot repositories and split storage on object stores (nearest; no object-storage node)
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  fit: exact
  layer: domain
  why: 'enrichment at ingest: entity extraction, OCR (OpenSearch Comprehend/Textract connectors)'
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: common
  why: cluster node discovery on cloud compute
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: common
  why: KMS-backed encryption of stored indices
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: 'streaming ingestion from brokers/queues (gap: no broker node)'
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: OpenTelemetry export
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: domain
  why: metasearch upstream web search engines
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  fit: exact
  layer: domain
  why: encyclopedic, knowledge-engine and scholarly reference sources
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: weather answers in metasearch
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  fit: exact
  layer: domain
  why: map/place search
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: metasearch translation engines
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: video search verticals
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  fit: exact
  layer: domain
  why: music search verticals
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: image search verticals
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: GIF search
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: social/community search verticals
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: code/repository search
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  fit: exact
  layer: domain
  why: package search verticals
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  fit: exact
  layer: domain
  why: container image search
- capability:
    attribution: API Evangelist extension
    id: AE-110.70
    key: AE-110.70
    name: Model Training & Data
    url: /capabilities/model-training-data/
    via_parent: null
  fit: exact
  layer: domain
  why: model hub search (SearXNG huggingface engine)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.20
    key: AE-140.10.20
    name: Headless & Composable Commerce
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: catalog connectors for product search
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: 'migrating from or federating another search engine (gap: no search-engine node)'
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: warehouse connectors as index sources
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: database connectors as index sources
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: exact
  layer: domain
  why: help-center/knowledge-base indexing
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Elasticsearch
      - Meilisearch
      - OpenSearch
      - Typesense
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Elasticsearch
      - OpenSearch
      - Typesense
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Vertex AI
      slug: google-vertex-ai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      - https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Elasticsearch
      - Meilisearch
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp: &id011
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face
      slug: hugging-face
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
      status: profiled
      tags: &id012
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - OpenSearch
      - Typesense
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp: &id005
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      - https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
      status: profiled
      tags: &id006
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Elasticsearch
      - OpenSearch
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: observed
      url: /providers/cohere/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Typesense
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp: &id001
        status: none
      name: Google (Gemini API)
      slug: google-gemini
      sources:
      - https://github.com/typesense/typesense/blob/HEAD/src/text_embedder_remote.cpp
      status: profiled
      tags: &id002
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Elasticsearch
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: Mistral
      slug: mistral
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Elasticsearch
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        source: https://github.com/ContextualAI/contextual-mcp-server
        status: verified
      name: Contextual AI
      slug: contextual-ai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - Grounded Language Model
      - LLM
      - RAG
      tier: observed
      url: /providers/contextual-ai/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Meilisearch
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp: &id007
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/meilisearch/meilisearch/tree/main/crates/milli/src/vector/embedder
      status: profiled
      tags: &id008
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-ready
      agent_readiness: 37.8
      apps:
      - Elasticsearch
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp: &id009
        source: https://github.com/jina-ai/MCP
        status: verified
      name: Jina AI
      slug: jina-ai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags: &id010
      - Artificial Intelligence
      - Embeddings
      - Machine Learning
      - Reranking
      tier: observed
      url: /providers/jina-ai/
    - agent_band: agent-aware
      agent_readiness: 16.1
      apps:
      - Elasticsearch
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: none
      name: Voyage AI
      slug: voyage-ai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Embeddings
      - RAG
      - Rerankers
      - Semantic Search
      tier: observed
      url: /providers/voyage-ai/
    - agent_band: agent-aware
      agent_readiness: 12.9
      apps:
      - Elasticsearch
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        source: https://github.com/TencentCloud/cos-mcp
        status: verified
      name: Tencent Cloud
      slug: tencentcloud
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Computing
      - Infrastructure
      tier: observed
      url: /providers/tencentcloud/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Elasticsearch
      band: emerging
      in_catalog: true
      kin_score: 19.2
      mcp:
        status: none
      name: IBM watsonx
      slug: ibm-watson
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - IBM
      - Machine Learning
      - Natural Language Processing
      tier: observed
      url: /providers/ibm-watson/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - Elasticsearch
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud AI Search
      slug: alibaba
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Commerce
      - E-Commerce
      tier: observed
      url: /providers/alibaba/
    - agent_band: human-only
      agent_readiness: 4.2
      apps:
      - Elasticsearch
      band: emerging
      in_catalog: true
      kin_score: 11.9
      mcp:
        status: none
      name: NVIDIA
      slug: nvidia
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - Computing
      - GPU
      - Machine Learning
      tier: observed
      url: /providers/nvidia/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - OpenSearch
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp: &id003
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags: &id004
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: declared
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - OpenSearch
      band: developing
      in_catalog: true
      kin_score: 47.2
      mcp:
        status: none
      name: Aleph Alpha
      slug: aleph-alpha
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - LLM
      - Machine Learning
      tier: declared
      url: /providers/aleph-alpha/
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenSearch
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Yandex Cloud
      slug: yandex-cloud
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Elasticsearch
      - OpenSearch
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/sagemaker-ai-mcp-server
        status: verified
      name: Amazon SageMaker
      slug: amazon-sagemaker
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Inference
      - Machine Learning
      tier: observed
      url: /providers/amazon-sagemaker/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Elasticsearch
      - OpenSearch
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp: *id001
      name: Google AI Studio
      slug: google-gemini
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - Elasticsearch
      - OpenSearch
      band: developing
      in_catalog: true
      kin_score: 43.3
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Elasticsearch
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Typesense
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare Workers AI
      slug: cloudflare
      sources:
      - https://github.com/typesense/typesense/blob/HEAD/src/conversation_model.cpp
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Elasticsearch
      band: strong
      in_catalog: true
      kin_score: 55.7
      mcp:
        source: https://github.com/openshift/kubernetes-mcp-server
        status: verified
      name: OpenShift AI
      slug: red-hat-openshift
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Containers
      - Enterprise
      - Hybrid Cloud
      - Kubernetes
      tier: observed
      url: /providers/red-hat-openshift/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Elasticsearch
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp: *id003
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Elasticsearch
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        source: https://github.com/microsoft-foundry/mcp-foundry
        status: verified
      name: Azure AI Studio
      slug: azure-ai-foundry
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/azure-ai-foundry/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Elasticsearch
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp: *id005
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Elasticsearch
      band: developing
      in_catalog: true
      kin_score: 41.1
      mcp:
        status: none
      name: AI21
      slug: ai21-labs
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Jamba
      - LLM
      tier: observed
      url: /providers/ai21-labs/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Elasticsearch
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        source: https://docs.fireworks.ai/ecosystem/integrations/development-setup
        status: verified
      name: Fireworks AI
      slug: fireworks-ai
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - Multi-Modal
      tier: observed
      url: /providers/fireworks-ai/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Elasticsearch
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/x-pack/plugin/inference/src/main/java/org/elasticsearch/xpack/inference/services
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - OpenSearch
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp: *id007
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/ollama/
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://www.wikidata.org/wiki/Wikidata:MCP
        status: verified
      name: Wikidata
      slug: wikidata
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/wikidata.py
      status: profiled
      tags:
      - Knowledge Graph
      - Linked Data
      - Open Data
      - Semantic Web
      tier: observed
      url: /providers/wikidata/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp:
        status: none
      name: arXiv
      slug: arxiv
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/arxiv.py
      status: profiled
      tags:
      - Open Access
      - Preprints
      - Research
      - Scholarly Publishing
      tier: observed
      url: /providers/arxiv/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Wikipedia
      slug: wikipedia
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/wikipedia.py
      status: profiled
      tags:
      - Encyclopedia
      - Open Data
      - Open Knowledge
      - Public APIs
      tier: observed
      url: /providers/wikipedia/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 38.5
      mcp:
        source: https://www.wolfram.com/artificial-intelligence/mcp/cloud/
        status: verified
      name: Wolfram|Alpha
      slug: wolframalpha
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/wolframalpha_api.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Computational Knowledge
      - Machine Learning
      - Natural Language Processing
      tier: observed
      url: /providers/wolframalpha/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        status: none
      name: Springer Nature
      slug: springer-nature
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/springer.py
      status: profiled
      tags:
      - Open Access
      - Research
      - Scholarly Content
      - Scholarly Publishing
      tier: observed
      url: /providers/springer-nature/
    - agent_band: agent-aware
      agent_readiness: 17.4
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: Crossref
      slug: crossref
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/crossref.py
      status: profiled
      tags:
      - Citations
      - DOI
      - Funders
      - Identifiers
      tier: observed
      url: /providers/crossref/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: Semantic Scholar
      slug: semantic-scholar
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/semantic_scholar.py
      status: profiled
      tags:
      - Academic
      - Citations
      - Paper
      - Research
      tier: observed
      url: /providers/semantic-scholar/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - SearXNG
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: none
      name: PubMed
      slug: pubmed
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/pubmed.py
      status: profiled
      tags:
      - Biomedical
      - Life Sciences
      - Literature
      - Research
      tier: observed
      url: /providers/pubmed/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SearXNG
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        source: https://github.com/ourresearch/openalex-mcp-server
        status: verified
      name: OpenAlex
      slug: openalex
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/openalex.py
      status: profiled
      tags:
      - Citations
      - Public APIs
      - Research Data
      - Scholarly
      tier: observed
      url: /providers/openalex/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - OpenSearch
      - Quickwit
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/ingestion-kafka
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: observed
      url: /providers/apache-kafka/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - OpenSearch
      - Quickwit
      band: developing
      in_catalog: true
      kin_score: 49.3
      mcp:
        status: none
      name: Amazon Kinesis
      slug: kinesis
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/ingestion-kinesis
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Apache Flink
      - Big Data
      tier: observed
      url: /providers/kinesis/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Quickwit
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source/queue_sources
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Quickwit
      band: thin
      in_catalog: true
      kin_score: 38.7
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Quickwit
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Apache Pulsar
      slug: apache-pulsar
      sources:
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-indexing/src/source
      status: profiled
      tags:
      - Cloud-Native
      - Messaging
      - Multi-Tenant
      - Pub/Sub
      tier: observed
      url: /providers/apache-pulsar/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/flickr.py
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: none
      name: Imgur
      slug: imgur
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/imgur.py
      status: profiled
      tags:
      - Albums
      - Image
      - Image Hosting
      - Photography
      tier: observed
      url: /providers/imgur/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/unsplash.py
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Pexels
      slug: pexels
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/pexels.py
      status: profiled
      tags:
      - Photos
      - Stock Media
      - Video
      tier: observed
      url: /providers/pexels/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Openverse
      slug: openverse
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/openverse.py
      status: profiled
      tags:
      - Audio
      - Creative Commons
      - Image
      - Open Media
      tier: observed
      url: /providers/openverse/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - SearXNG
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: none
      name: Pixabay
      slug: pixabay
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/pixabay.py
      status: profiled
      tags:
      - Illustrations
      - Image
      - Stock Media
      - Video
      tier: observed
      url: /providers/pixabay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SearXNG
      band: minimal
      in_catalog: true
      kin_score: 6.1
      mcp:
        status: none
      name: TinEye
      slug: tineye
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/tineye.py
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/tineye/
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
      - SearXNG
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        source: https://github.com/exa-labs/exa-mcp-server
        status: verified
      name: Exa
      slug: exa-ai
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/exaapi.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Neural Search
      - Search
      - Web Search
      tier: observed
      url: /providers/exa-ai/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        status: none
      name: Google Programmable Search
      slug: google-custom-search
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/google_cse.py
      status: profiled
      tags:
      - Custom Search
      - Google
      - Image Search
      - Search
      tier: observed
      url: /providers/google-custom-search/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/kagisearch/kagimcp
        status: verified
      name: Kagi
      slug: kagi
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/kagi.py
      status: profiled
      tags:
      - AI Search
      - Premium Search
      - Search
      - Summarization
      tier: observed
      url: /providers/kagi/
    - agent_band: agent-ready
      agent_readiness: 37.8
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp: *id009
      name: Jina AI
      slug: jina-ai
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/jina.py
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/jina-ai/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        source: https://github.com/brave/brave-search-mcp-server
        status: verified
      name: Brave Search API
      slug: brave-browser
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/braveapi.py
      status: profiled
      tags:
      - Browser
      - Chromium
      - Privacy
      - Search
      tier: observed
      url: /providers/brave-browser/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SearXNG
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: Microsoft Bing
      slug: microsoft-bing
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/bing.py
      status: profiled
      tags:
      - Image
      - Search
      - Video
      - Web Search
      tier: observed
      url: /providers/microsoft-bing/
    - agent_band: null
      agent_readiness: null
      apps:
      - SearXNG
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Yandex Search API
      slug: yandex
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/yandex_api.py
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/spotify.py
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        status: none
      name: Genius
      slug: genius
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/genius.py
      status: profiled
      tags:
      - Annotation
      - Crowdsourced
      - Lyrics
      - Music
      tier: observed
      url: /providers/genius/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 31.0
      mcp:
        status: none
      name: SoundCloud
      slug: soundcloud
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/soundcloud.py
      status: profiled
      tags:
      - Audio
      - Music
      - OAuth
      - Streaming
      tier: observed
      url: /providers/soundcloud/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: Deezer
      slug: deezer
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/deezer.py
      status: profiled
      tags:
      - Audio
      - Music
      - OAuth
      - Streaming
      tier: observed
      url: /providers/deezer/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SearXNG
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: Mixcloud
      slug: mixcloud
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/mixcloud.py
      status: profiled
      tags:
      - Music
      - Public APIs
      tier: observed
      url: /providers/mixcloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SearXNG
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: Freesound
      slug: freesound
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/freesound.py
      status: profiled
      tags:
      - Music
      - Public APIs
      tier: observed
      url: /providers/freesound/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 41.3
      mcp:
        source: https://github.com/StackExchange/Stack-MCP
        status: verified
      name: Stack Exchange
      slug: stackexchange
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/stackexchange.py
      status: profiled
      tags:
      - Developer Community
      - Knowledge Graph
      - Q&A
      - Stack Overflow
      tier: observed
      url: /providers/stackexchange/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: Lemmy
      slug: lemmy
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/lemmy.py
      status: profiled
      tags:
      - Community
      - Federated
      - Fediverse
      - Link Aggregator
      tier: observed
      url: /providers/lemmy/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: Hacker News
      slug: hacker-news
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/hackernews.py
      status: profiled
      tags:
      - Developer Community
      - Technology News
      - Y Combinator
      tier: observed
      url: /providers/hacker-news/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/mastodon.py
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: observed
      url: /providers/mastodon/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - SearXNG
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube Data API
      slug: youtube
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/youtube_api.py
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/vimeo.py
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: observed
      url: /providers/vimeo/
    - agent_band: agent-ready
      agent_readiness: 32.6
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: PeerTube
      slug: peertube
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/peertube.py
      status: profiled
      tags:
      - Decentralized
      - Federation
      - Open Source
      - Video
      tier: observed
      url: /providers/peertube/
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - SearXNG
      band: minimal
      in_catalog: true
      kin_score: 8.4
      mcp:
        status: none
      name: Dailymotion
      slug: dailymotion
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/dailymotion.py
      status: profiled
      tags:
      - Public APIs
      - Video
      tier: observed
      url: /providers/dailymotion/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - SearXNG
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        status: none
      name: npm
      slug: npm
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/npm.py
      status: profiled
      tags:
      - JavaScript
      - Node.js
      - Package Management
      - Packages
      tier: observed
      url: /providers/npm/
    - agent_band: agent-aware
      agent_readiness: 21.5
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 39.5
      mcp:
        status: none
      name: crates.io
      slug: crates-io
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/crates.py
      status: profiled
      tags:
      - Cargo
      - Crates
      - Package Registry
      - Rust
      tier: observed
      url: /providers/crates-io/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        status: none
      name: PyPI
      slug: pypi
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/pypi.py
      status: profiled
      tags:
      - Developer Tools
      - Open Source
      - Package Management
      - Packages
      tier: observed
      url: /providers/pypi/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.20
      key: AE-140.10.20
      name: Headless & Composable Commerce
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - Algolia
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Algolia
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp:
        source: https://github.com/commercetools/mcp-essentials
        status: verified
      name: commercetools
      slug: commercetools
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - Commerce
      - Composable Commerce
      - E-Commerce
      - GraphQL
      tier: declared
      url: /providers/commercetools/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40
      key: AE-110.40
      name: Language & Document Understanding
      url: /capabilities/language-document-understanding/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - OpenSearch
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: Amazon Comprehend
      slug: amazon-comprehend
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Amazon Web Services
      - Machine Learning
      - Natural Language Processing
      - Text Analysis
      tier: declared
      url: /providers/amazon-comprehend/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - OpenSearch
      band: developing
      in_catalog: true
      kin_score: 52.7
      mcp:
        status: none
      name: Amazon Textract
      slug: amazon-textract
      sources:
      - https://github.com/opensearch-project/ml-commons/tree/main/docs/remote_inference_blueprints
      status: profiled
      tags:
      - Amazon Web Services
      - Document Processing
      - Machine Learning
      - OCR
      tier: declared
      url: /providers/amazon-textract/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - SearXNG
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/deepl.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/libretranslate.py
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: observed
      url: /providers/libre-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - Algolia
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase
      slug: supabase
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: declared
      url: /providers/supabase/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Algolia
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp:
        status: none
      name: MySQL
      slug: mysql
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - Database
      - Open Source
      - RDBMS
      - Relational Database
      tier: declared
      url: /providers/mysql/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - SearXNG
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/github.py
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - SearXNG
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/gitlab.py
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - Algolia
      band: developing
      in_catalog: true
      kin_score: 49.7
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: declared
      url: /providers/google-bigquery/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - SearXNG
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/giphy.py
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: observed
      url: /providers/giphy/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/docker/hub-mcp
        status: verified
      name: Docker Hub
      slug: docker-hub
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/docker_hub.py
      status: profiled
      tags:
      - Containers
      - DevOps
      - Docker
      - Registry
      tier: observed
      url: /providers/docker-hub/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Algolia
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk Knowledge Base
      slug: zendesk
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.70
      key: AE-110.70
      name: Model Training & Data
      url: /capabilities/model-training-data/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - SearXNG
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp: *id011
      name: Hugging Face Hub
      slug: hugging-face
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/huggingface.py
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/hugging-face/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - SearXNG
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/openstreetmap.py
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: observed
      url: /providers/openstreetmap/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Algolia
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: declared
      url: /providers/elastic/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - SearXNG
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Open-Meteo
      slug: open-meteo
      sources:
      - https://github.com/searxng/searxng/blob/master/searx/engines/open_meteo.py
      status: profiled
      tags:
      - Air Quality
      - Forecast
      - Historical Weather
      - Weather
      tier: observed
      url: /providers/open-meteo/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Elasticsearch
      - OpenSearch
      - Quickwit
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/modules/repository-gcs
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/repository-gcs
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/opendal_storage
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Elasticsearch
      - OpenSearch
      - Quickwit
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/modules/repository-s3
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/repository-s3
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/object_storage
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Elasticsearch
      - OpenSearch
      - Quickwit
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/elastic/elasticsearch/tree/main/modules/repository-azure
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/repository-azure
      - https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/object_storage
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.5
      apps:
      - OpenSearch
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Azure (classic)
      slug: microsoft-azure
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/discovery-azure-classic
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - OpenSearch
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        status: none
      name: Amazon EC2
      slug: amazon-ec2
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/discovery-ec2
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud Computing
      - Compute
      - Infrastructure-as-a-Service
      tier: observed
      url: /providers/amazon-ec2/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - OpenSearch
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        source: https://cloud.google.com/compute/docs/reference/mcp
        status: verified
      name: Google Compute Engine
      slug: google-cloud-compute-engine
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/discovery-gce
      status: profiled
      tags:
      - Compute
      - Google Cloud
      - Infrastructure
      - Infrastructure-as-a-Service
      tier: observed
      url: /providers/google-cloud-compute-engine/
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - OpenSearch
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        status: none
      name: AWS KMS
      slug: amazon-kms
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/crypto-kms
      status: profiled
      tags:
      - Amazon Web Services
      - Cryptography
      - Data Protection
      - Encryption
      tier: observed
      url: /providers/amazon-kms/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - OpenSearch
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: OpenTelemetry
      slug: opentelemetry
      sources:
      - https://github.com/opensearch-project/OpenSearch/tree/main/plugins/telemetry-otel
      status: profiled
      tags:
      - Cloud-Native
      - Logging
      - Metrics
      - Monitoring
      tier: observed
      url: /providers/opentelemetry/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Meilisearch
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://github.com/meilisearch/meilisearch/blob/main/crates/meilisearch/src/analytics/segment_analytics.rs
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  layer: common
summary:
  coverage_pct: 97.9
  declared_only: 12
  distinct_providers: 97
  in_catalog: 95
  mcp:
    documented: 1
    none: 54
    unchecked: 2
    verified: 40
  mcp_verified: 40
  mean_kin_score: 44.3
  observed: 85
  queued: 2
  reference_apps: 7
title: 'Site & App Search: application blueprint'
---
