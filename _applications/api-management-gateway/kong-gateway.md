---
app: Kong Gateway
app_slug: kong-gateway
app_url: https://github.com/Kong/kong
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: domain
  name: Serverless Functions
  providers:
  - AWS Lambda
  - Azure Functions
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-620.50.50
  key: BC-620.50.50
  layer: common
  name: Cryptography and Key Management
  providers:
  - Let's Encrypt
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - Loggly
  - OpenTelemetry
  - Prometheus
  - StatsD
  - Zipkin
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Anthropic
  - Azure OpenAI
  - Cohere
  - Google Gemini
  - Hugging Face
  - Mistral AI
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 0
  observed: 17
credits: []
evidence:
- route: source code
  url: https://github.com/Kong/kong/tree/master/kong/llm/drivers
- route: source code
  url: https://github.com/Kong/kong/tree/master/kong/plugins
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
  layer: agent
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id005
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id006
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
  layer: domain
  name: AWS Lambda
  provider: aws-lambda
  says: ships the AWS Lambda SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.0
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-functions
    status: profiled
    tags: &id008
    - Cloud
    - Compute
    - Event-Driven
    - Microsoft Azure
    url: /providers/microsoft-azure-functions/
  layer: domain
  name: Azure Functions
  provider: microsoft-azure-functions
  says: ships the Azure Functions SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: agent
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
    mcp: &id011
      status: none
    slug: cohere
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: agent
  name: Cohere
  provider: cohere
  says: ships the Cohere SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id013
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id014
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    mcp: &id015
      status: none
    slug: google-gemini
    status: profiled
    tags: &id016
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
    mcp: &id017
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id018
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
  layer: agent
  name: Hugging Face
  provider: hugging-face
  says: ships the Hugging Face SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id019
      status: none
    slug: lets-encrypt
    status: profiled
    tags: &id020
    - Certificates
    - Linux Foundation
    - Security
    - TLS
    url: /providers/lets-encrypt/
  layer: common
  name: Let's Encrypt
  provider: lets-encrypt
  says: ships the Let's Encrypt SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    agent_readiness: 5.4
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id021
      status: none
    slug: loggly
    status: profiled
    tags: &id022
    - Company
    - Developer Tools
    - Log Management
    - Logging
    url: /providers/loggly/
  layer: common
  name: Loggly
  provider: loggly
  says: ships the Loggly SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    mcp: &id023
      status: none
    slug: mistral
    status: profiled
    tags: &id024
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: agent
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
    mcp: &id025
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
    kin_score: 38.6
    mcp: &id027
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id028
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
  layer: common
  name: OpenTelemetry
  provider: opentelemetry
  says: ships the OpenTelemetry SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id029
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id030
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: common
  name: Prometheus
  provider: prometheus-io
  says: ships the Prometheus SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id031
      status: none
    slug: statsd
    status: profiled
    tags: &id032
    - Aggregation
    - Daemon
    - DogStatsD
    - Line Protocol
    url: /providers/statsd/
  layer: common
  name: StatsD
  provider: statsd
  says: ships the StatsD SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id033
      status: none
    slug: zipkin
    status: profiled
    tags: &id034
    - Distributed Tracing
    - Microservices
    - Observability
    - Open Source
    url: /providers/zipkin/
  layer: common
  name: Zipkin
  provider: zipkin
  says: ships the Zipkin SDK or integration code
  source: https://github.com/Kong/kong/tree/master/kong/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/kong-gateway/
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
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id005
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id006
  url: /providers/aws-lambda/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id007
  name: Azure Functions
  slug: microsoft-azure-functions
  status: profiled
  tags: *id008
  url: /providers/microsoft-azure-functions/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id009
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-openai/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id011
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id012
  url: /providers/cohere/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id013
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id014
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id015
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id016
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id017
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id018
  url: /providers/hugging-face/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id019
  name: Let's Encrypt
  slug: lets-encrypt
  status: profiled
  tags: *id020
  url: /providers/lets-encrypt/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id021
  name: Loggly
  slug: loggly
  status: profiled
  tags: *id022
  url: /providers/loggly/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id023
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id024
  url: /providers/mistral/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id025
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id026
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id027
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id028
  url: /providers/opentelemetry/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id029
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id030
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id031
  name: StatsD
  slug: statsd
  status: profiled
  tags: *id032
  url: /providers/statsd/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id033
  name: Zipkin
  slug: zipkin
  status: profiled
  tags: *id034
  url: /providers/zipkin/
siblings:
- name: Apache APISIX
  rows: 36
  url: /applications/api-management-gateway/apache-apisix/
- name: Hoppscotch
  rows: 4
  url: /applications/api-management-gateway/hoppscotch/
- name: KrakenD CE
  rows: 12
  url: /applications/api-management-gateway/krakend-ce/
- name: Postman
  rows: 20
  url: /applications/api-management-gateway/postman/
- name: Traefik Proxy
  rows: 15
  url: /applications/api-management-gateway/traefik-proxy/
- name: Tyk Gateway + Tyk Pump
  rows: 24
  url: /applications/api-management-gateway/tyk-gateway-tyk-pump/
- name: Zuplo
  rows: 36
  url: /applications/api-management-gateway/zuplo/
sitemap: true
title: 'Kong Gateway: API Management & Gateways reference app'
---
