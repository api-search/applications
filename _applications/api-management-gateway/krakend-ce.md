---
app: KrakenD CE
app_slug: krakend-ce
app_url: https://github.com/krakend/krakend-ce
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Amazon SNS
  - Amazon SQS
  - Apache Kafka
  - Azure Service Bus
  - Google Cloud Pub/Sub
  - NATS
  - RabbitMQ
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: domain
  name: Serverless Functions
  providers:
  - AWS Lambda
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - HashiCorp Vault
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Elastic
  - Graylog
  - OpenTelemetry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 0
  observed: 12
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id005
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id006
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
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
  facts:
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 74.9
    mcp: &id007
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id008
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id009
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-service-bus
    status: profiled
    tags: &id010
    - Cloud
    - Enterprise
    - Message Broker
    - Microsoft Azure
    url: /providers/azure-service-bus/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id011
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id012
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id013
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id014
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.7
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id015
      status: none
    slug: graylog
    status: profiled
    tags: &id016
    - Log Management
    - Logging
    - Observability
    - SIEM
    url: /providers/graylog/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id017
      source: https://github.com/hashicorp/vault-mcp-server
      status: verified
    slug: hvault
    status: profiled
    tags: &id018
    - Encryption
    - Identity
    - Infrastructure
    - Secrets Management
    url: /providers/hvault/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 38.5
    mcp: &id019
      status: none
    slug: nats
    status: profiled
    tags: &id020
    - Cloud-Native
    - IoT
    - Message Broker
    - NATS
    url: /providers/nats/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id021
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id022
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id023
      status: none
    slug: rabbitmq
    status: profiled
    tags: &id024
    - AMQP
    - Distributed Systems
    - Queues
    - RabbitMQ
    url: /providers/rabbitmq/
  layer: domain
  name: RabbitMQ
  provider: rabbitmq
  says: ships the RabbitMQ SDK or integration code
  source: https://github.com/krakend/krakend-ce/blob/master/go.mod
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/krakend-ce/
providers:
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id001
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id002
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id003
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id004
  url: /providers/amazon-sqs/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id005
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id006
  url: /providers/apache-kafka/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 74.9
  mcp: *id007
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id008
  url: /providers/aws-lambda/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id009
  name: Azure Service Bus
  slug: azure-service-bus
  status: profiled
  tags: *id010
  url: /providers/azure-service-bus/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id011
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id012
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id013
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id014
  url: /providers/google-cloud-pubsub/
- agent_band: human-only
  agent_readiness: 3.7
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id015
  name: Graylog
  slug: graylog
  status: profiled
  tags: *id016
  url: /providers/graylog/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id017
  name: HashiCorp Vault
  slug: hvault
  status: profiled
  tags: *id018
  url: /providers/hvault/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 38.5
  mcp: *id019
  name: NATS
  slug: nats
  status: profiled
  tags: *id020
  url: /providers/nats/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id021
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id022
  url: /providers/opentelemetry/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id023
  name: RabbitMQ
  slug: rabbitmq
  status: profiled
  tags: *id024
  url: /providers/rabbitmq/
siblings:
- name: Apache APISIX
  rows: 36
  url: /applications/api-management-gateway/apache-apisix/
- name: Hoppscotch
  rows: 4
  url: /applications/api-management-gateway/hoppscotch/
- name: Kong Gateway
  rows: 17
  url: /applications/api-management-gateway/kong-gateway/
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
title: 'KrakenD CE: API Management & Gateways reference app'
---
