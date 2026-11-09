---
app: Apache APISIX
app_slug: apache-apisix
app_url: https://github.com/apache/apisix
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.20
  key: AE-160.20
  layer: domain
  name: Authorization for Apps
  providers:
  - Open Policy Agent
  url: /capabilities/authorization-for-apps/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: domain
  name: Identity & Access Management
  providers:
  - Casdoor
  - Keycloak
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Apache Kafka
  - Apache RocketMQ
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: domain
  name: Serverless Functions
  providers:
  - Apache OpenWhisk
  - AWS Lambda
  - Azure Functions
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-2660.10
  key: usage-mediation-management
  layer: domain
  name: Usage Mediation Management
  providers:
  - Lago
  url: /capabilities/usage-mediation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Apache SkyWalking
  - ClickHouse
  - Datadog
  - Elastic
  - Google Cloud Logging
  - Grafana Loki
  - Loggly
  - OpenTelemetry
  - Prometheus
  - Splunk
  - Tencent Cloud
  - Zipkin
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - DingTalk
  - Feishu / Lark
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: common
  name: Threat Detection & Response Management
  providers:
  - Chaitin SafeLine
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.50.20
  key: AE-100.50.20
  layer: agent
  name: Agent Security & Guardrails
  providers:
  - Alibaba Cloud
  - Amazon Comprehend
  - Lakera Guard
  url: /capabilities/agent-identity-trust/
  via_parent: Agent Identity & Trust
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Anthropic
  - Azure OpenAI
  - DeepSeek
  - Google Gemini
  - OpenAI
  - Vertex AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: agent
  name: Model Routing & Gateways
  providers:
  - AI/ML API
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 0
  observed: 36
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 54.0
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id001
      source: https://docs.aimlapi.com/quickstart/mcp
      status: documented
    slug: aimlapi
    status: profiled
    tags: &id002
    - AI Models
    - Artificial Intelligence
    - LLM
    - Machine Learning
    url: /providers/aimlapi/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id003
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibabacloud
    status: profiled
    tags: &id004
    - Company
    url: /providers/alibabacloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 51.4
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id007
      status: none
    slug: amazon-comprehend
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Machine Learning
    - Natural Language Processing
    - Text Analysis
    url: /providers/amazon-comprehend/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id009
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id010
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id011
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id012
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.0
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id013
      status: none
    slug: apache-openwhisk
    status: profiled
    tags: &id014
    - Cloud-Native
    - Event-Driven
    - Function-as-a-Service
    - Serverless
    url: /providers/apache-openwhisk/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id015
      status: none
    slug: apache-rocketmq
    status: profiled
    tags: &id016
    - Cloud-Native
    - Message Queue
    - Messaging
    - Pub/Sub
    url: /providers/apache-rocketmq/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 22.4
    mcp: &id017
      source: https://github.com/apache/skywalking-mcp
      status: verified
    slug: apache-skywalking
    status: profiled
    tags: &id018
    - APM
    - Application Performance Monitoring
    - Cloud-Native
    - Distributed Tracing
    url: /providers/apache-skywalking/
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
  facts:
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id019
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id020
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.0
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id021
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-functions
    status: profiled
    tags: &id022
    - Cloud
    - Compute
    - Event-Driven
    - Microsoft Azure
    url: /providers/microsoft-azure-functions/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 44.6
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id025
      source: https://github.com/casdoor/casdoor
      status: documented
    slug: casdoor
    status: profiled
    tags: &id026
    - Authentication
    - Authorization
    - Identity
    - Identity and Access Management
    url: /providers/casdoor/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: thin
    in_catalog: true
    kin_score: 36.1
    mcp: &id027
      source: https://github.com/chaitin/SafeLine
      status: verified
    slug: chaitin
    status: profiled
    tags: &id028
    - Cybersecurity
    - Security
    - WAF
    - Web Application Firewall
    url: /providers/chaitin/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 76.9
    mcp: &id029
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id030
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id031
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id032
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id033
      status: none
    slug: deepseek
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id035
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id036
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id037
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id038
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id039
      status: unchecked
    slug: feishu
    status: queued for profiling
    tags: &id040 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.0
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id041
      source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
      status: verified
    slug: google-cloud-logging
    status: profiled
    tags: &id042
    - Cloud
    - Logging
    - Monitoring
    - Observability
    url: /providers/google-cloud-logging/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id043
      status: none
    slug: google-gemini
    status: profiled
    tags: &id044
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.9
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id045
      source: https://github.com/grafana/loki-mcp
      status: verified
    slug: loki
    status: profiled
    tags: &id046
    - Grafana
    - Logging
    - Observability
    - Open Source
    url: /providers/loki/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id047
      status: none
    slug: keycloak
    status: profiled
    tags: &id048
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.5
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id049
      source: https://github.com/getlago/lago-agent-toolkit
      status: verified
    slug: lago
    status: profiled
    tags: &id050
    - Billing
    - Metering
    - Open Source
    - Usage-Based
    url: /providers/lago/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 39.1
    mcp: &id051
      status: none
    slug: lakera
    status: profiled
    tags: &id052
    - AI Security
    - Guardrails
    - LLM Security
    - Prompt Injection
    url: /providers/lakera/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id053
      status: none
    slug: loggly
    status: profiled
    tags: &id054
    - Company
    - Developer Tools
    - Log Management
    - Logging
    url: /providers/loggly/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id055
      status: none
    slug: open-policy-agent
    status: profiled
    tags: &id056
    - Policies
    - Standards
    url: /providers/open-policy-agent/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id061
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id062
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id063
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id064
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id065
      status: none
    slug: splunk
    status: profiled
    tags: &id066
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id067
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id068
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id071
      status: none
    slug: zipkin
    status: profiled
    tags: &id072
    - Distributed Tracing
    - Microservices
    - Observability
    - Open Source
    url: /providers/zipkin/
  layer: common
  name: Zipkin
  provider: zipkin
  says: ships the Zipkin SDK or integration code
  source: https://github.com/apache/apisix/tree/master/apisix/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/apache-apisix/
providers:
- agent_band: agent-ready
  agent_readiness: 54.0
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id001
  name: AI/ML API
  slug: aimlapi
  status: profiled
  tags: *id002
  url: /providers/aimlapi/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id003
  name: Alibaba Cloud
  slug: alibabacloud
  status: profiled
  tags: *id004
  url: /providers/alibabacloud/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id005
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id006
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id007
  name: Amazon Comprehend
  slug: amazon-comprehend
  status: profiled
  tags: *id008
  url: /providers/amazon-comprehend/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id009
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id010
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id011
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id012
  url: /providers/apache-kafka/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id013
  name: Apache OpenWhisk
  slug: apache-openwhisk
  status: profiled
  tags: *id014
  url: /providers/apache-openwhisk/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id015
  name: Apache RocketMQ
  slug: apache-rocketmq
  status: profiled
  tags: *id016
  url: /providers/apache-rocketmq/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 22.4
  mcp: *id017
  name: Apache SkyWalking
  slug: apache-skywalking
  status: profiled
  tags: *id018
  url: /providers/apache-skywalking/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id019
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id020
  url: /providers/aws-lambda/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id021
  name: Azure Functions
  slug: microsoft-azure-functions
  status: profiled
  tags: *id022
  url: /providers/microsoft-azure-functions/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id023
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id024
  url: /providers/microsoft-azure-openai/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id025
  name: Casdoor
  slug: casdoor
  status: profiled
  tags: *id026
  url: /providers/casdoor/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id027
  name: Chaitin SafeLine
  slug: chaitin
  status: profiled
  tags: *id028
  url: /providers/chaitin/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 76.9
  mcp: *id029
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id030
  url: /providers/clickhouse/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id031
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id032
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id033
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id034
  url: /providers/deepseek/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id035
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id036
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id037
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id038
  url: /providers/elastic/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id039
  name: Feishu / Lark
  slug: feishu
  status: queued for profiling
  tags: *id040
  url: null
- agent_band: agent-ready
  agent_readiness: 50.0
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id041
  name: Google Cloud Logging
  slug: google-cloud-logging
  status: profiled
  tags: *id042
  url: /providers/google-cloud-logging/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id043
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id044
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 18.9
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id045
  name: Grafana Loki
  slug: loki
  status: profiled
  tags: *id046
  url: /providers/loki/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id047
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id048
  url: /providers/keycloak/
- agent_band: agent-ready
  agent_readiness: 43.5
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id049
  name: Lago
  slug: lago
  status: profiled
  tags: *id050
  url: /providers/lago/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 39.1
  mcp: *id051
  name: Lakera Guard
  slug: lakera
  status: profiled
  tags: *id052
  url: /providers/lakera/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id053
  name: Loggly
  slug: loggly
  status: profiled
  tags: *id054
  url: /providers/loggly/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id055
  name: Open Policy Agent
  slug: open-policy-agent
  status: profiled
  tags: *id056
  url: /providers/open-policy-agent/
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
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id061
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id062
  url: /providers/opentelemetry/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id063
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id064
  url: /providers/prometheus-io/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id065
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id066
  url: /providers/splunk/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id067
  name: Tencent Cloud
  slug: tencentcloud
  status: profiled
  tags: *id068
  url: /providers/tencentcloud/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id069
  name: Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id070
  url: /providers/google-vertex-ai/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id071
  name: Zipkin
  slug: zipkin
  status: profiled
  tags: *id072
  url: /providers/zipkin/
siblings:
- name: Hoppscotch
  rows: 4
  url: /applications/api-management-gateway/hoppscotch/
- name: Kong Gateway
  rows: 17
  url: /applications/api-management-gateway/kong-gateway/
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
title: 'Apache APISIX: API Management & Gateways reference app'
---
