---
access: understanding
agent_layer:
- app: Kong Gateway
  finding: ships an AI gateway (ai-proxy, ai-prompt-guard/decorator/template plugins) that fronts eight LLM vendors
  source: https://github.com/Kong/kong/tree/master/kong/plugins
  tier: observed
- app: Apache APISIX
  finding: openapi-to-mcp plugin exposes upstream REST APIs as an MCP server; ai-proxy-multi, ai-rag and ai-rate-limiting plugins
  source: https://github.com/apache/apisix/tree/master/apisix/plugins
  tier: observed
- app: Tyk Gateway
  finding: 'native MCP proxying: mcp_api.go, MCP OAuth broker, REST-as-MCP policy and MCP access control middleware'
  source: https://github.com/TykTechnologies/tyk/tree/master/gateway
  tier: observed
- app: Zuplo
  finding: separate AI Gateway, MCP Gateway and MCP Server products; MCP OAuth policies for ten IdPs
  source: https://zuplo.com/docs/policies
  tier: declared
apps:
- anchor: kong-gateway
  counts:
    declared: 0
    observed: 17
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
    layer: common
    name: Zipkin
    provider: zipkin
    says: ships the Zipkin SDK or integration code
    source: https://github.com/Kong/kong/tree/master/kong/plugins
    tier: observed
  kind: self-hosted
  name: Kong Gateway
  page: /applications/api-management-gateway/kong-gateway/
  slug: kong-gateway
  url: https://github.com/Kong/kong
- anchor: apache-apisix
  counts:
    declared: 0
    observed: 36
  evidence:
  - route: source code
    url: https://github.com/apache/apisix/tree/master/apisix/plugins
  - route: source code
    url: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: AI/ML API
    provider: aimlapi
    says: ships the AI/ML API SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.50.20
      key: AE-100.50.20
      name: Agent Security & Guardrails
      url: /capabilities/agent-identity-trust/
      via_parent: Agent Identity & Trust
    credit: null
    layer: agent
    name: Alibaba Cloud
    provider: alibabacloud
    says: ships the Alibaba Cloud SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.50.20
      key: AE-100.50.20
      name: Agent Security & Guardrails
      url: /capabilities/agent-identity-trust/
      via_parent: Agent Identity & Trust
    credit: null
    layer: agent
    name: Amazon Comprehend
    provider: amazon-comprehend
    says: ships the Amazon Comprehend SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
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
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Apache OpenWhisk
    provider: apache-openwhisk
    says: ships the Apache OpenWhisk SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Apache RocketMQ
    provider: apache-rocketmq
    says: ships the Apache RocketMQ SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Apache SkyWalking
    provider: apache-skywalking
    says: ships the Apache SkyWalking SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: AWS Lambda
    provider: aws-lambda
    says: ships the AWS Lambda SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Azure Functions
    provider: microsoft-azure-functions
    says: ships the Azure Functions SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Casdoor
    provider: casdoor
    says: ships the Casdoor SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: common
    name: Chaitin SafeLine
    provider: chaitin
    says: ships the Chaitin SafeLine SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
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
    name: DingTalk
    provider: dingtalk
    says: ships the DingTalk SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Elastic
    provider: elastic
    says: ships the Elastic SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Feishu / Lark
    provider: feishu
    says: ships the Feishu / Lark SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Google Cloud Logging
    provider: google-cloud-logging
    says: ships the Google Cloud Logging SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
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
    name: Grafana Loki
    provider: loki
    says: ships the Grafana Loki SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Keycloak
    provider: keycloak
    says: ships the Keycloak SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lago
    provider: lago
    says: ships the Lago SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.50.20
      key: AE-100.50.20
      name: Agent Security & Guardrails
      url: /capabilities/agent-identity-trust/
      via_parent: Agent Identity & Trust
    credit: null
    layer: agent
    name: Lakera Guard
    provider: lakera
    says: ships the Lakera Guard SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Loggly
    provider: loggly
    says: ships the Loggly SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    credit: null
    layer: domain
    name: Open Policy Agent
    provider: open-policy-agent
    says: ships the Open Policy Agent SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
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
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Splunk
    provider: splunk
    says: ships the Splunk SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Tencent Cloud
    provider: tencentcloud
    says: ships the Tencent Cloud SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
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
    name: Vertex AI
    provider: google-vertex-ai
    says: ships the Vertex AI SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
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
    name: Zipkin
    provider: zipkin
    says: ships the Zipkin SDK or integration code
    source: https://github.com/apache/apisix/tree/master/apisix/plugins
    tier: observed
  kind: self-hosted
  name: Apache APISIX
  page: /applications/api-management-gateway/apache-apisix/
  slug: apache-apisix
  url: https://github.com/apache/apisix
- anchor: tyk-gateway-+-tyk-pump
  counts:
    declared: 0
    observed: 24
  evidence:
  - route: dependency manifest
    url: https://github.com/TykTechnologies/tyk/blob/master/go.mod
  - route: source code
    url: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: Amazon Timestream
    provider: amazon-timestream
    says: ships the Amazon Timestream SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: Elastic
    provider: elastic
    says: ships the Elastic SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: Graylog
    provider: graylog
    says: ships the Graylog SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: InfluxDB
    provider: influxdata
    says: ships the InfluxDB SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: Jaeger
    provider: jaeger
    says: ships the Jaeger SDK or integration code
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    name: Logz.io
    provider: logz-io
    says: ships the Logz.io SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Moesif
    provider: moesif
    says: ships the Moesif SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: NATS
    provider: nats
    says: ships the NATS SDK or integration code
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: RabbitMQ
    provider: rabbitmq
    says: ships the RabbitMQ SDK or integration code
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    name: Resurface
    provider: resurface
    says: ships the Resurface SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
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
    name: Splunk
    provider: splunk
    says: ships the Splunk SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: StatsD
    provider: statsd
    says: ships the StatsD SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
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
    name: Zipkin
    provider: zipkin
    says: ships the Zipkin SDK or integration code
    source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
    tier: observed
  kind: self-hosted
  name: Tyk Gateway + Tyk Pump
  page: /applications/api-management-gateway/tyk-gateway-tyk-pump/
  slug: tyk-gateway-tyk-pump
  url: https://github.com/TykTechnologies/tyk
- anchor: krakend-ce
  counts:
    declared: 0
    observed: 12
  evidence:
  - route: dependency manifest
    url: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: AWS Lambda
    provider: aws-lambda
    says: ships the AWS Lambda SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: Azure Service Bus
    provider: azure-service-bus
    says: ships the Azure Service Bus SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: Elastic
    provider: elastic
    says: ships the Elastic SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: Graylog
    provider: graylog
    says: ships the Graylog SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: HashiCorp Vault
    provider: hvault
    says: ships the HashiCorp Vault SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: NATS
    provider: nats
    says: ships the NATS SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
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
    name: RabbitMQ
    provider: rabbitmq
    says: ships the RabbitMQ SDK or integration code
    source: https://github.com/krakend/krakend-ce/blob/master/go.mod
    tier: observed
  kind: self-hosted
  name: KrakenD CE
  page: /applications/api-management-gateway/krakend-ce/
  slug: krakend-ce
  url: https://github.com/krakend/krakend-ce
- anchor: traefik-proxy
  counts:
    declared: 0
    observed: 15
  evidence:
  - route: dependency manifest
    url: https://github.com/traefik/traefik/blob/master/go.mod
  - route: source code
    url: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
  - route: source code
    url: https://github.com/traefik/traefik/tree/master/pkg/provider
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon ECS
    provider: amazon-ecs
    says: ships the Amazon ECS SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache ZooKeeper
    provider: apache-zookeeper
    says: ships the Apache ZooKeeper SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
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
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Docker
    provider: docker
    says: ships the Docker SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: etcd
    provider: etcd
    says: ships the etcd SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: HashiCorp Consul
    provider: consul
    says: ships the HashiCorp Consul SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
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
    name: InfluxDB
    provider: influxdata
    says: ships the InfluxDB SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kubernetes
    provider: kubernetes
    says: ships the Kubernetes SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    credit: null
    layer: common
    name: Let's Encrypt
    provider: lets-encrypt
    says: ships the Let's Encrypt SDK or integration code
    source: https://github.com/traefik/traefik/blob/master/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nomad
    provider: nomad
    says: ships the Nomad SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
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
    source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
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
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
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
    name: StatsD
    provider: statsd
    says: ships the StatsD SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    credit: null
    layer: common
    name: Tailscale
    provider: tailscale
    says: ships the Tailscale SDK or integration code
    source: https://github.com/traefik/traefik/tree/master/pkg/provider
    tier: observed
  kind: self-hosted
  name: Traefik Proxy
  page: /applications/api-management-gateway/traefik-proxy/
  slug: traefik-proxy
  url: https://github.com/traefik/traefik
- anchor: hoppscotch
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/hoppscotch/hoppscotch/blob/main/packages/hoppscotch-backend/package.json
  - route: source code
    url: https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
  integrations:
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
    source: https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
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
    source: https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
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
    name: Microsoft sign-in
    provider: microsoft-entra
    says: ships the Microsoft sign-in SDK or integration code
    source: https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
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
    source: https://github.com/hoppscotch/hoppscotch/blob/main/packages/hoppscotch-backend/package.json
    tier: observed
  kind: self-hosted
  name: Hoppscotch
  page: /applications/api-management-gateway/hoppscotch/
  slug: hoppscotch
  url: https://github.com/hoppscotch/hoppscotch
- anchor: zuplo
  counts:
    declared: 36
    observed: 0
  evidence:
  - route: documentation
    url: https://zuplo.com/docs/articles/logging
  - route: documentation
    url: https://zuplo.com/docs/policies
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.50.20
      key: AE-100.50.20
      name: Agent Security & Guardrails
      url: /capabilities/agent-identity-trust/
      via_parent: Agent Identity & Trust
    credit: null
    layer: agent
    name: Akamai
    provider: akamai
    says: lists Akamai as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Cognito
    provider: amazon-cognito
    says: lists Amazon Cognito as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amberflo
    provider: amberflo
    says: lists Amberflo as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Auth0
    provider: auth0
    says: lists Auth0 as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS
    provider: amazon-web-services
    says: lists AWS as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS CloudWatch
    provider: amazon-cloudwatch
    says: lists AWS CloudWatch as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    credit: null
    layer: domain
    name: Axiomatics
    provider: axiomatics
    says: lists Axiomatics as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clerk
    provider: clerk-com
    says: lists Clerk as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    credit: null
    layer: agent
    name: Comet Opik
    provider: opik
    says: lists Comet Opik as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Curity
    provider: curity
    says: lists Curity as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Dynatrace
    provider: dynatrace
    says: lists Dynatrace as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Firebase
    provider: firebase
    says: lists Firebase as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    credit: null
    layer: agent
    name: Galileo
    provider: galileo-technologies
    says: lists Galileo as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud
    provider: google-cloud-platform
    says: lists Google Cloud as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Logging
    provider: google-cloud-logging
    says: lists Google Cloud Logging as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google OAuth
    provider: google-identity-platform
    says: lists Google OAuth as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Grafana Loki
    provider: loki
    says: lists Grafana Loki as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Keycloak
    provider: keycloak
    says: lists Keycloak as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Logto
    provider: logto
    says: lists Logto as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Entra
    provider: microsoft-entra
    says: lists Microsoft Entra as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Moesif
    provider: moesif
    says: lists Moesif as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: New Relic
    provider: new-relic
    says: lists New Relic as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: OneLogin
    provider: onelogin
    says: lists OneLogin as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    credit: null
    layer: domain
    name: OpenFGA
    provider: openfga
    says: lists OpenFGA as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    credit: null
    layer: domain
    name: OpenMeter
    provider: openmeter
    says: lists OpenMeter as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ping Identity
    provider: ping-identity
    says: lists Ping Identity as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: PropelAuth
    provider: propelauth
    says: lists PropelAuth as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    credit: null
    layer: domain
    name: ReadMe
    provider: readme
    says: lists ReadMe as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Splunk
    provider: splunk
    says: lists Splunk as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.80
      key: BC-4270.80
      name: Webhook & Event Subscription Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sumo Logic
    provider: sumo-logic
    says: lists Sumo Logic as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Supabase
    provider: supabase
    says: lists Supabase as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: VMware Log Insight
    provider: vmware
    says: lists VMware Log Insight as an integration
    source: https://zuplo.com/docs/articles/logging
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: WorkOS
    provider: workos
    says: lists WorkOS as an integration
    source: https://zuplo.com/docs/policies
    tier: declared
  kind: commercial
  name: Zuplo
  page: /applications/api-management-gateway/zuplo/
  slug: zuplo
  url: https://zuplo.com/
- anchor: postman
  counts:
    declared: 20
    observed: 0
  evidence:
  - route: integrations page
    url: https://learning.postman.com/v11/docs/integrations/available-integrations/postman-integrations.md
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    credit: null
    layer: domain
    name: Apigee
    provider: apigee
    says: lists Apigee as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/apigee-api-management/deploying-an-api-apigee.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.20.10
      key: BC-4270.20.10
      name: SDK Generation & Release
      url: /capabilities/sdk-client-library-management/
      via_parent: SDK & Client Library Management
    credit: null
    layer: domain
    name: APIMatic
    provider: apimatic
    says: lists APIMatic as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/apimatic.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    credit: null
    layer: domain
    name: AWS API Gateway
    provider: aws-api-gateway
    says: lists AWS API Gateway as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/aws-api-gateway.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    credit: null
    layer: domain
    name: Azure API Management
    provider: microsoft-azure-api-management
    says: lists Azure API Management as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/azure-api-management/deploying-an-api-azure.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: lists Azure DevOps as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/azure-devops.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/bitbucket.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: CircleCI
    provider: circleci
    says: lists CircleCI as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/circleci.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/datadog.md
    tier: declared
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
    says: lists GitHub as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/github/overview.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/gitlab.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jenkins
    provider: jenkins
    says: lists Jenkins as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/jenkins.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/jira/overview.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/microsoft-teams.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: New Relic
    provider: new-relic
    says: lists New Relic as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/new-relic.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: PagerDuty
    provider: pagerduty
    says: lists PagerDuty as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/pagerduty.md
    tier: declared
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
    says: lists Slack as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/slack.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Splunk
    provider: splunk
    says: lists Splunk as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/splunk.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: Splunk On-Call (VictorOps)
    provider: victorops
    says: lists Splunk On-Call (VictorOps) as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/splunk-on-call.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4290.60.20
      key: BC-4290.60.20
      name: Uptime Disclosure
      url: /capabilities/service-resilience-commitment-management/
      via_parent: Service Resilience Commitment Management
    credit: null
    layer: common
    name: Statuspage
    provider: statuspage
    says: lists Statuspage as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/statuspage.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Travis CI
    provider: travis-ci
    says: lists Travis CI as an integration
    source: https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/travis-ci.md
    tier: declared
  kind: commercial
  name: Postman
  page: /applications/api-management-gateway/postman/
  slug: postman
  url: https://www.postman.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: api-management-gateway
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Software Development - API Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---api-management
- category: Developer Tools
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
name: API Management & Gateways
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI-gateway proxy plugins forward prompts to hosted model APIs (Kong ai-proxy drivers, APISIX ai-providers)
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: dynamic route/config discovery from orchestrators and KV stores (Traefik providers)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: every gateway ships log/metric/trace exporters; the largest provider cluster in the category
- capability:
    attribution: Turbo EA
    id: BC-620
    key: cybersecurity-management
    name: Cybersecurity Management
    url: /capabilities/cybersecurity-management/
    via_parent: null
  fit: gap
  layer: common
  why: automatic TLS certificate issuance via ACME (Let's Encrypt, Tailscale certs); also WAF (Chaitin)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: APISIX routes to aggregator/router endpoints (OpenRouter, AI/ML API)
- capability:
    attribution: API Evangelist extension
    id: AE-100.50.20
    key: AE-100.50.20
    name: Agent Security & Guardrails
    url: /capabilities/agent-identity-trust/
    via_parent: Agent Identity & Trust
  fit: exact
  layer: agent
  why: prompt/response screening plugins (Lakera Guard, Aliyun and AWS Comprehend moderation, Akamai AI firewall)
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: domain
  why: JWT/OIDC validation against hosted IdPs (Zuplo auth policies, APISIX authz-keycloak/casdoor)
- capability:
    attribution: API Evangelist extension
    id: AE-160.20
    key: AE-160.20
    name: Authorization for Apps
    url: /capabilities/authorization-for-apps/
    via_parent: null
  fit: exact
  layer: domain
  why: fine-grained authorization calls at the gateway (OpenFGA, Okta FGA, Axiomatics, OPA)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: developer sign-in to the gateway console / API client (Hoppscotch GitHub/Google/Microsoft; APISIX DingTalk/Feishu auth)
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: nearest
  layer: common
  why: WAF hand-off (APISIX chaitin-waf)
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: gateways bridge HTTP to message brokers (KrakenD pubsub, Tyk streams, APISIX kafka/rocketmq loggers); no broker node exists
- capability:
    attribution: Turbo EA
    id: BC-2660.10
    key: usage-mediation-management
    name: Usage Mediation Management
    url: /capabilities/usage-mediation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: API metering and usage-based billing exports (Moesif, Amberflo, OpenMeter, Lago, ReadMe metrics)
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: gateway state and analytics stores (Redis, MongoDB, Timestream)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: API analytics forwarded to a CDP (Tyk Pump -> Segment)
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: common
  why: upstream credentials pulled from HashiCorp Vault
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics of the API client itself (PostHog in Hoppscotch)
- capability:
    attribution: API Evangelist extension
    id: AE-100.60.20
    key: AE-100.60.20
    name: Agent Observability
    url: /capabilities/agent-quality-operations/
    via_parent: Agent Quality & Operations
  fit: exact
  layer: agent
  why: LLM-call tracing policies in Zuplo (Comet Opik, Galileo)
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  fit: exact
  layer: domain
  why: Postman pushes API definitions to cloud gateways (Apigee, AWS API Gateway, Azure APIM)
- capability:
    attribution: Turbo EA
    id: BC-4270.20.10
    key: BC-4270.20.10
    name: SDK Generation & Release
    url: /capabilities/sdk-client-library-management/
    via_parent: SDK & Client Library Management
  fit: exact
  layer: domain
  why: SDK generation from the API definition (APIMatic)
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: common
  why: collections and specs synced to source control (GitHub, GitLab, Bitbucket, Azure DevOps)
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  fit: exact
  layer: common
  why: collection runs in CI pipelines (CircleCI, Jenkins, Travis CI)
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: issues created from API tests (Jira)
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: team notifications for monitors and API changes (Slack, Microsoft Teams)
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: monitor failures paged to on-call tools (PagerDuty, Splunk On-Call)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Apache APISIX
      - Zuplo
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: observed
      url: /providers/keycloak/
    - agent_band: agent-aware
      agent_readiness: 21.5
      apps:
      - Apache APISIX
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        source: https://github.com/casdoor/casdoor
        status: documented
      name: Casdoor
      slug: casdoor
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity
      - Identity and Access Management
      tier: observed
      url: /providers/casdoor/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: Amazon Cognito
      slug: amazon-cognito
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Amazon Web Services
      - Authentication
      - Identity
      - OpenID Connect
      tier: declared
      url: /providers/amazon-cognito/
    - agent_band: agent-native
      agent_readiness: 51.9
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://github.com/clerk/mcp-tools
        status: verified
      name: Clerk
      slug: clerk-com
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - Authorization
      - B2B SaaS
      - CIAM
      tier: declared
      url: /providers/clerk-com/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: declared
      url: /providers/auth0/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: &id001
        status: none
      name: Microsoft Entra
      slug: microsoft-entra
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags: &id002
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud
      slug: google-cloud-platform
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: declared
      url: /providers/google-cloud-platform/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: declared
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 57.7
      apps:
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 60.2
      mcp:
        source: https://workos.com/docs/mcp
        status: verified
      name: WorkOS
      slug: workos
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - Identity Provider
      - SAML
      - SSO
      tier: declared
      url: /providers/workos/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp: &id003
        status: none
      name: Google OAuth
      slug: google-identity-platform
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags: &id004
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        status: none
      name: PropelAuth
      slug: propelauth
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - B2B
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/propelauth/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        source: https://github.com/pingidentity/pingone-mcp-server
        status: verified
      name: Ping Identity
      slug: ping-identity
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity
      - SSO
      tier: declared
      url: /providers/ping-identity/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase
      slug: supabase
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: declared
      url: /providers/supabase/
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        status: none
      name: Logto
      slug: logto
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity
      - OpenID Connect
      tier: declared
      url: /providers/logto/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Zuplo
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: declared
      url: /providers/onelogin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Zuplo
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: none
      name: Curity
      slug: curity
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Company
      - Identity
      - OAuth
      - OpenID Connect
      tier: declared
      url: /providers/curity/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Apache APISIX
      - KrakenD CE
      - Tyk Gateway + Tyk Pump
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: observed
      url: /providers/apache-kafka/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - KrakenD CE
      - Tyk Gateway + Tyk Pump
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - KrakenD CE
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 38.5
      mcp:
        status: none
      name: NATS
      slug: nats
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Cloud-Native
      - IoT
      - Message Broker
      - NATS
      tier: observed
      url: /providers/nats/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - KrakenD CE
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: RabbitMQ
      slug: rabbitmq
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - AMQP
      - Distributed Systems
      - Queues
      - RabbitMQ
      tier: observed
      url: /providers/rabbitmq/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - KrakenD CE
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Service Bus
      slug: azure-service-bus
      sources:
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Cloud
      - Enterprise
      - Message Broker
      - Microsoft Azure
      tier: observed
      url: /providers/azure-service-bus/
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Tyk Gateway + Tyk Pump
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: Amazon Kinesis
      slug: kinesis
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Apache Flink
      - Big Data
      tier: observed
      url: /providers/kinesis/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - KrakenD CE
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - KrakenD CE
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Apache APISIX
      band: thin
      in_catalog: true
      kin_score: 26.6
      mcp:
        status: none
      name: Apache RocketMQ
      slug: apache-rocketmq
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Cloud-Native
      - Message Queue
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/apache-rocketmq/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 47.9
      apps:
      - Traefik Proxy
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon ECS
      slug: amazon-ecs
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Containers
      - Docker
      tier: observed
      url: /providers/amazon-ecs/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Traefik Proxy
      band: developing
      in_catalog: true
      kin_score: 51.7
      mcp:
        source: https://github.com/docker/mcp-gateway
        status: verified
      name: Docker
      slug: docker
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Cloud
      - Containers
      - DevOps
      - Developer Tools
      tier: observed
      url: /providers/docker/
    - agent_band: agent-ready
      agent_readiness: 32.6
      apps:
      - Traefik Proxy
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        status: none
      name: Kubernetes
      slug: kubernetes
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Automation
      - CNCF
      - Cloud-Native
      - Containers
      tier: observed
      url: /providers/kubernetes/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Traefik Proxy
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: etcd
      slug: etcd
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Cloud-Native
      - Consensus
      - Distributed Systems
      - Graduated
      tier: observed
      url: /providers/etcd/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Traefik Proxy
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp: &id007
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags: &id008
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - Traefik Proxy
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        status: none
      name: Nomad
      slug: nomad
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Container Orchestration
      - Infrastructure
      - Scheduling
      - Workload Orchestration
      tier: observed
      url: /providers/nomad/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Traefik Proxy
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: none
      name: Apache ZooKeeper
      slug: apache-zookeeper
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Configuration Management
      - Distributed Coordination
      - Leader Election
      - Service Discovery
      tier: observed
      url: /providers/apache-zookeeper/
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - Traefik Proxy
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        source: https://github.com/hashicorp/consul-mcp-server
        status: verified
      name: HashiCorp Consul
      slug: consul
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - ACL
      - Configuration
      - Health Checks
      - Key-Value Store
      tier: observed
      url: /providers/consul/
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Apache APISIX
      - Kong Gateway
      - KrakenD CE
      band: exemplar
      in_catalog: true
      kin_score: 74.9
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
        status: verified
      name: AWS Lambda
      slug: aws-lambda
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Serverless
      tier: observed
      url: /providers/aws-lambda/
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - Apache APISIX
      - Kong Gateway
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Functions
      slug: microsoft-azure-functions
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Cloud
      - Compute
      - Event-Driven
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-functions/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Apache APISIX
      band: thin
      in_catalog: true
      kin_score: 26.7
      mcp:
        status: none
      name: Apache OpenWhisk
      slug: apache-openwhisk
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Cloud-Native
      - Event-Driven
      - Function-as-a-Service
      - Serverless
      tier: observed
      url: /providers/apache-openwhisk/
  - capability:
      attribution: Turbo EA
      id: BC-2660.10
      key: usage-mediation-management
      name: Usage Mediation Management
      url: /capabilities/usage-mediation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Tyk Gateway + Tyk Pump
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        status: none
      name: Moesif
      slug: moesif
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Analytics
      - Governance
      - Monetization
      - Monitoring
      tier: observed
      url: /providers/moesif/
    - agent_band: agent-ready
      agent_readiness: 49.3
      apps:
      - Apache APISIX
      band: developing
      in_catalog: true
      kin_score: 42.0
      mcp:
        source: https://github.com/getlago/lago-agent-toolkit
        status: verified
      name: Lago
      slug: lago
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Billing
      - Metering
      - Open Source
      - Usage-Based
      tier: observed
      url: /providers/lago/
    - agent_band: agent-ready
      agent_readiness: 34.1
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://docs.readme.com/main/docs/mcp
        status: verified
      name: ReadMe
      slug: readme
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - API Reference
      - Developer Hub
      - Documentation
      - Portal
      tier: declared
      url: /providers/readme/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 45.3
      mcp:
        status: none
      name: Amberflo
      slug: amberflo
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - AI Cost Management
      - FinOps
      - Metering
      - Usage-Based Billing
      tier: declared
      url: /providers/amberflo/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - Zuplo
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        status: none
      name: OpenMeter
      slug: openmeter
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Billing
      - CloudEvents
      - Entitlements
      - Usage Metering
      tier: declared
      url: /providers/openmeter/
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://learn.microsoft.com/en-us/azure/api-management/export-rest-mcp-server
        status: verified
      name: Azure API Management
      slug: microsoft-azure-api-management
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/azure-api-management/deploying-an-api-azure.md
      status: profiled
      tags:
      - A2A
      - AI Gateway
      - API Center
      - API Gateway
      tier: declared
      url: /providers/microsoft-azure-api-management/
    - agent_band: agent-ready
      agent_readiness: 42.0
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        status: none
      name: AWS API Gateway
      slug: aws-api-gateway
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/aws-api-gateway.md
      status: profiled
      tags:
      - API Gateway
      - Amazon Web Services
      - Cloud
      - REST
      tier: declared
      url: /providers/aws-api-gateway/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 67.6
      mcp:
        source: https://cloud.google.com/apigee/docs/api-platform/apigee-mcp/apigee-mcp-overview
        status: documented
      name: Apigee
      slug: apigee
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/apigee-api-management/deploying-an-api-apigee.md
      status: profiled
      tags:
      - AI Agents
      - Advanced API Security
      - Analytics
      - Apigee
      tier: declared
      url: /providers/apigee/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Apache APISIX
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Open Policy Agent
      slug: open-policy-agent
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Policies
      - Standards
      tier: observed
      url: /providers/open-policy-agent/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Zuplo
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        status: none
      name: Axiomatics
      slug: axiomatics
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Authorization
      - Company
      - Policy
      - Zero Trust
      tier: declared
      url: /providers/axiomatics/
    - agent_band: agent-ready
      agent_readiness: 35.1
      apps:
      - Zuplo
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: none
      name: OpenFGA
      slug: openfga
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Access Control
      - Authorization
      - Cloud-Native
      - Fine-Grained
      tier: declared
      url: /providers/openfga/
  - capability:
      attribution: Turbo EA
      id: BC-4270.20.10
      key: BC-4270.20.10
      name: SDK Generation & Release
      url: /capabilities/sdk-client-library-management/
      via_parent: SDK & Client Library Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Postman
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/apimatic/apimatic-validator-mcp
        status: verified
      name: APIMatic
      slug: apimatic
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/apimatic.md
      status: profiled
      tags:
      - API Transformation
      - Code Generation
      - Developer Experience
      - Developer Tools
      tier: declared
      url: /providers/apimatic/
  - capability:
      attribution: Turbo EA
      id: BC-4270.80
      key: BC-4270.80
      name: Webhook & Event Subscription Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
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
      agent_readiness: 48.6
      apps:
      - Apache APISIX
      - Kong Gateway
      - Postman
      - Traefik Proxy
      - Tyk Gateway + Tyk Pump
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - Apache APISIX
      - Kong Gateway
      - KrakenD CE
      - Traefik Proxy
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: none
      name: OpenTelemetry
      slug: opentelemetry
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Cloud-Native
      - Logging
      - Metrics
      - Monitoring
      tier: observed
      url: /providers/opentelemetry/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Apache APISIX
      - Postman
      - Tyk Gateway + Tyk Pump
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://learning.postman.com/v11/docs/integrations/available-integrations/splunk.md
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: observed
      url: /providers/splunk/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Apache APISIX
      - Kong Gateway
      - Traefik Proxy
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        source: https://github.com/prometheus/prometheus-mcp
        status: verified
      name: Prometheus
      slug: prometheus-io
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Metrics
      - Monitoring
      - Observability
      - Prometheus
      tier: observed
      url: /providers/prometheus-io/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Apache APISIX
      - KrakenD CE
      - Tyk Gateway + Tyk Pump
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic
      slug: elastic
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Postman
      - Tyk Gateway + Tyk Pump
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      - https://learning.postman.com/v11/docs/integrations/available-integrations/new-relic.md
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Apache APISIX
      - Kong Gateway
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 38.2
      mcp:
        status: none
      name: Zipkin
      slug: zipkin
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Distributed Tracing
      - Microservices
      - Observability
      - Open Source
      tier: observed
      url: /providers/zipkin/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Kong Gateway
      - Traefik Proxy
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        status: none
      name: StatsD
      slug: statsd
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
      status: profiled
      tags:
      - Aggregation
      - Daemon
      - DogStatsD
      - Line Protocol
      tier: observed
      url: /providers/statsd/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Apache APISIX
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
        status: verified
      name: Google Cloud Logging
      slug: google-cloud-logging
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - Cloud
      - Logging
      - Monitoring
      - Observability
      tier: observed
      url: /providers/google-cloud-logging/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Traefik Proxy
      - Tyk Gateway + Tyk Pump
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        source: https://github.com/influxdata/influxdb3_mcp_server
        status: verified
      name: InfluxDB
      slug: influxdata
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
      status: profiled
      tags:
      - Database
      - Monitoring
      - Observability
      - Time Series Database
      tier: observed
      url: /providers/influxdata/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Apache APISIX
      - Kong Gateway
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        status: none
      name: Loggly
      slug: loggly
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Company
      - Developer Tools
      - Log Management
      - Logging
      tier: observed
      url: /providers/loggly/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Apache APISIX
      - Zuplo
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/grafana/loki-mcp
        status: verified
      name: Grafana Loki
      slug: loki
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - Grafana
      - Logging
      - Observability
      - Open Source
      tier: observed
      url: /providers/loki/
    - agent_band: human-only
      agent_readiness: 3.7
      apps:
      - KrakenD CE
      - Tyk Gateway + Tyk Pump
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Graylog
      slug: graylog
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Log Management
      - Logging
      - Observability
      - SIEM
      tier: observed
      url: /providers/graylog/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Tyk Gateway + Tyk Pump
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 58.5
      apps:
      - Apache APISIX
      band: exemplar
      in_catalog: true
      kin_score: 77.1
      mcp:
        source: https://github.com/ClickHouse/mcp-clickhouse
        status: verified
      name: ClickHouse
      slug: clickhouse
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Analytics
      - ClickHouse
      - Cloud Database
      - Column-Oriented
      tier: observed
      url: /providers/clickhouse/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Tyk Gateway + Tyk Pump
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        status: none
      name: Logz.io
      slug: logz-io
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      status: profiled
      tags:
      - Logging
      - Metrics
      - Observability
      - Tracing
      tier: observed
      url: /providers/logz-io/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Tyk Gateway + Tyk Pump
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://github.com/jaegertracing/jaeger
        status: verified
      name: Jaeger
      slug: jaeger
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      status: profiled
      tags:
      - Distributed Tracing
      - Microservices
      - Monitoring
      - Observability
      tier: observed
      url: /providers/jaeger/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Apache APISIX
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        source: https://github.com/TencentCloud/cos-mcp
        status: verified
      name: Tencent Cloud
      slug: tencentcloud
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
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
      - Apache APISIX
      band: emerging
      in_catalog: true
      kin_score: 21.6
      mcp:
        source: https://github.com/apache/skywalking-mcp
        status: verified
      name: Apache SkyWalking
      slug: apache-skywalking
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - APM
      - Application Performance Monitoring
      - Cloud-Native
      - Distributed Tracing
      tier: observed
      url: /providers/apache-skywalking/
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - Tyk Gateway + Tyk Pump
      band: emerging
      in_catalog: true
      kin_score: 19.9
      mcp:
        status: none
      name: Resurface
      slug: resurface
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      status: profiled
      tags:
      - API Analytics
      - API Compliance
      - API Logging
      - API Observability
      tier: observed
      url: /providers/resurface/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 85.6
      mcp:
        source: https://github.com/dynatrace-oss/dynatrace-mcp
        status: verified
      name: Dynatrace
      slug: dynatrace
      sources:
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - AI Operations
      - APM
      - Analytics
      - Application Performance Monitoring
      tier: declared
      url: /providers/dynatrace/
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - Zuplo
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS CloudWatch
      slug: amazon-cloudwatch
      sources:
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: declared
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: VMware Log Insight
      slug: vmware
      sources:
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - Cloud Computing
      - Container Management
      - Hybrid Cloud
      - Infrastructure
      tier: declared
      url: /providers/vmware/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        source: https://docs.sumologic.com/docs/search/mobot/
        status: documented
      name: Sumo Logic
      slug: sumo-logic
      sources:
      - https://zuplo.com/docs/articles/logging
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Security
      tier: declared
      url: /providers/sumo-logic/
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
      - Hoppscotch
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id005
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
      status: profiled
      tags: &id006
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Hoppscotch
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: *id001
      name: Microsoft sign-in
      slug: microsoft-entra
      sources:
      - https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Hoppscotch
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp: *id003
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/hoppscotch/hoppscotch/tree/main/packages/hoppscotch-backend/src/auth/strategies
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Apache APISIX
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        source: https://github.com/open-dingtalk/dingtalk-mcp
        status: verified
      name: DingTalk
      slug: dingtalk
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Enterprise
      tier: observed
      url: /providers/dingtalk/
    - agent_band: null
      agent_readiness: null
      apps:
      - Apache APISIX
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Feishu / Lark
      slug: feishu
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/gitlab.md
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: declared
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id005
      name: GitHub
      slug: github
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/github/overview.md
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/azure-devops.md
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: declared
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/bitbucket.md
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: declared
      url: /providers/bitbucket/
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Kong Gateway
      - Traefik Proxy
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        status: none
      name: Let's Encrypt
      slug: lets-encrypt
      sources:
      - https://github.com/Kong/kong/tree/master/kong/plugins
      - https://github.com/traefik/traefik/blob/master/go.mod
      status: profiled
      tags:
      - Certificates
      - Linux Foundation
      - Security
      - TLS
      tier: observed
      url: /providers/lets-encrypt/
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Traefik Proxy
      band: developing
      in_catalog: true
      kin_score: 40.8
      mcp:
        status: none
      name: Tailscale
      slug: tailscale
      sources:
      - https://github.com/traefik/traefik/tree/master/pkg/provider
      status: profiled
      tags:
      - Mesh Networking
      - VPN
      - WireGuard
      - Zero Trust
      tier: observed
      url: /providers/tailscale/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.1
      apps:
      - Tyk Gateway + Tyk Pump
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: observed
      url: /providers/mongodb/
    - agent_band: agent-native
      agent_readiness: 48.4
      apps:
      - Tyk Gateway + Tyk Pump
      band: exemplar
      in_catalog: true
      kin_score: 73.3
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/timestream-for-influxdb-mcp-server
        status: verified
      name: Amazon Timestream
      slug: amazon-timestream
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - IoT
      - Time Series
      tier: observed
      url: /providers/amazon-timestream/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Tyk Gateway + Tyk Pump
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp: *id007
      name: Redis
      slug: redis
      sources:
      - https://github.com/TykTechnologies/tyk/blob/master/go.mod
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/redis/
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 73.5
      mcp:
        source: https://github.com/CircleCI-Public/mcp-server-circleci
        status: verified
      name: CircleCI
      slug: circleci
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/circleci.md
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/circleci/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Postman
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        source: https://github.com/jenkinsci/mcp-server-plugin
        status: verified
      name: Jenkins
      slug: jenkins
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/jenkins.md
      status: profiled
      tags:
      - Automation
      - Build Server
      - CI/CD
      - Continuous Delivery
      tier: declared
      url: /providers/jenkins/
    - agent_band: agent-aware
      agent_readiness: 18.8
      apps:
      - Postman
      band: thin
      in_catalog: true
      kin_score: 29.9
      mcp:
        status: none
      name: Travis CI
      slug: travis-ci
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/travis-ci.md
      status: profiled
      tags:
      - Builds
      - CI/CD
      - DevOps
      - Open Source
      tier: declared
      url: /providers/travis-ci/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Postman
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/pagerduty.md
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: declared
      url: /providers/pagerduty/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postman
      band: emerging
      in_catalog: true
      kin_score: 18.1
      mcp:
        status: none
      name: Splunk On-Call (VictorOps)
      slug: victorops
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/splunk-on-call.md
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call
      tier: declared
      url: /providers/victorops/
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
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/slack.md
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Postman
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/microsoft-teams.md
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - KrakenD CE
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        source: https://github.com/hashicorp/vault-mcp-server
        status: verified
      name: HashiCorp Vault
      slug: hvault
      sources:
      - https://github.com/krakend/krakend-ce/blob/master/go.mod
      status: profiled
      tags:
      - Encryption
      - Identity
      - Infrastructure
      - Secrets Management
      tier: observed
      url: /providers/hvault/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Tyk Gateway + Tyk Pump
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://github.com/TykTechnologies/tyk-pump/tree/master/pumps
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Hoppscotch
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/hoppscotch/hoppscotch/blob/main/packages/hoppscotch-backend/package.json
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
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Postman
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/jira/overview.md
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Apache APISIX
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        source: https://github.com/chaitin/SafeLine
        status: verified
      name: Chaitin SafeLine
      slug: chaitin
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Cybersecurity
      - Security
      - WAF
      - Web Application Firewall
      tier: observed
      url: /providers/chaitin/
  - capability:
      attribution: Turbo EA
      id: BC-4290.60.20
      key: BC-4290.60.20
      name: Uptime Disclosure
      url: /capabilities/service-resilience-commitment-management/
      via_parent: Service Resilience Commitment Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Postman
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        status: none
      name: Statuspage
      slug: statuspage
      sources:
      - https://learning.postman.com/v11/docs/integrations/available-integrations/statuspage.md
      status: profiled
      tags:
      - Incident Communication
      - Incident Management
      - Status Pages
      - Uptime
      tier: declared
      url: /providers/statuspage/
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
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Apache APISIX
      - Kong Gateway
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
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
      - Apache APISIX
      - Kong Gateway
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Apache APISIX
      - Kong Gateway
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - Apache APISIX
      - Kong Gateway
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Apache APISIX
      - Kong Gateway
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Kong Gateway
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face
      slug: hugging-face
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      status: profiled
      tags:
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Apache APISIX
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Vertex AI
      slug: google-vertex-ai
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Kong Gateway
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
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
      - Apache APISIX
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Kong Gateway
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/Kong/kong/tree/master/kong/llm/drivers
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: observed
      url: /providers/cohere/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.50.20
      key: AE-100.50.20
      name: Agent Security & Guardrails
      url: /capabilities/agent-identity-trust/
      via_parent: Agent Identity & Trust
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Apache APISIX
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: Amazon Comprehend
      slug: amazon-comprehend
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Amazon Web Services
      - Machine Learning
      - Natural Language Processing
      - Text Analysis
      tier: observed
      url: /providers/amazon-comprehend/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Apache APISIX
      band: thin
      in_catalog: true
      kin_score: 39.1
      mcp:
        status: none
      name: Lakera Guard
      slug: lakera
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - AI Security
      - Guardrails
      - LLM Security
      - Prompt Injection
      tier: observed
      url: /providers/lakera/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Apache APISIX
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud
      slug: alibabacloud
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/alibabacloud/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Akamai
      slug: akamai
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - CDN
      - Cloud
      - Edge Computing
      - Networks
      tier: declared
      url: /providers/akamai/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Zuplo
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        source: https://docs.galileo.ai/getting-started/mcp/setup-galileo-mcp
        status: verified
      name: Galileo
      slug: galileo-technologies
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - AI Observability
      - Company
      - Generative AI
      - LLM Evaluation
      tier: declared
      url: /providers/galileo-technologies/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Zuplo
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        source: https://github.com/comet-ml/opik-mcp
        status: verified
      name: Comet Opik
      slug: opik
      sources:
      - https://zuplo.com/docs/policies
      status: profiled
      tags:
      - Evaluation
      - LLM
      - Observability
      - Tracing
      tier: declared
      url: /providers/opik/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.9
      apps:
      - Apache APISIX
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        source: https://docs.aimlapi.com/quickstart/mcp
        status: documented
      name: AI/ML API
      slug: aimlapi
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - AI Models
      - Artificial Intelligence
      - LLM
      - Machine Learning
      tier: observed
      url: /providers/aimlapi/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Apache APISIX
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/apache/apisix/tree/master/apisix/plugins/ai-providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  layer: agent
summary:
  coverage_pct: 99.1
  declared_only: 44
  distinct_providers: 116
  in_catalog: 115
  mcp:
    documented: 4
    none: 47
    unchecked: 1
    verified: 64
  mcp_verified: 64
  mean_kin_score: 54.2
  observed: 72
  queued: 1
  reference_apps: 8
title: 'API Management & Gateways: application blueprint'
---
