---
app: Tyk Gateway + Tyk Pump
app_slug: tyk-gateway-tyk-pump
app_url: https://github.com/TykTechnologies/tyk
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  - Amazon SQS
  - Apache Kafka
  - NATS
  - RabbitMQ
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-2660.10
  key: usage-mediation-management
  layer: domain
  name: Usage Mediation Management
  providers:
  - Moesif
  url: /capabilities/usage-mediation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Amazon Timestream
  - MongoDB
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - Elastic
  - Graylog
  - InfluxDB
  - Jaeger
  - Logz.io
  - New Relic
  - OpenTelemetry
  - Prometheus
  - Resurface
  - Sentry
  - Splunk
  - StatsD
  - Zipkin
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 0
  observed: 24
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id001
      status: none
    slug: kinesis
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 59.8
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id005
      source: https://github.com/awslabs/mcp/tree/main/src/timestream-for-influxdb-mcp-server
      status: verified
    slug: amazon-timestream
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Database
    - IoT
    - Time Series
    url: /providers/amazon-timestream/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id007
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id008
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id009
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id010
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
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
  facts:
    agent_band: human-only
    agent_readiness: 3.7
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id013
      status: none
    slug: graylog
    status: profiled
    tags: &id014
    - Log Management
    - Logging
    - Observability
    - SIEM
    url: /providers/graylog/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.1
    band: strong
    in_catalog: true
    kin_score: 64.0
    mcp: &id015
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id016
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id017
      source: https://github.com/jaegertracing/jaeger
      status: verified
    slug: jaeger
    status: profiled
    tags: &id018
    - Distributed Tracing
    - Microservices
    - Monitoring
    - Observability
    url: /providers/jaeger/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id019
      status: none
    slug: logz-io
    status: profiled
    tags: &id020
    - Logging
    - Metrics
    - Observability
    - Tracing
    url: /providers/logz-io/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id021
      status: none
    slug: moesif
    status: profiled
    tags: &id022
    - Analytics
    - Governance
    - Monetization
    - Monitoring
    url: /providers/moesif/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.0
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id023
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id024
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: developing
    in_catalog: true
    kin_score: 39.9
    mcp: &id025
      status: none
    slug: nats
    status: profiled
    tags: &id026
    - Cloud-Native
    - IoT
    - Message Broker
    - NATS
    url: /providers/nats/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.7
    band: exemplar
    in_catalog: true
    kin_score: 76.5
    mcp: &id027
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id028
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id029
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id030
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id031
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id032
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.0
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id033
      status: none
    slug: rabbitmq
    status: profiled
    tags: &id034
    - AMQP
    - Distributed Systems
    - Queues
    - RabbitMQ
    url: /providers/rabbitmq/
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
  facts:
    agent_band: agent-native
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id035
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id036
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id037
      status: none
    slug: resurface
    status: profiled
    tags: &id038
    - API Analytics
    - API Compliance
    - API Logging
    - API Observability
    url: /providers/resurface/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id039
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id040
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id041
      status: none
    slug: splunk
    status: profiled
    tags: &id042
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id043
      status: none
    slug: statsd
    status: profiled
    tags: &id044
    - Aggregation
    - Daemon
    - DogStatsD
    - Line Protocol
    url: /providers/statsd/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id045
      status: none
    slug: segment
    status: profiled
    tags: &id046
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id047
      status: none
    slug: zipkin
    status: profiled
    tags: &id048
    - Distributed Tracing
    - Microservices
    - Observability
    - Open Source
    url: /providers/zipkin/
  layer: common
  name: Zipkin
  provider: zipkin
  says: ships the Zipkin SDK or integration code
  source: https://github.com/TykTechnologies/tyk/blob/master/go.mod
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/tyk-gateway-tyk-pump/
providers:
- agent_band: agent-ready
  agent_readiness: 29.4
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id001
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id002
  url: /providers/kinesis/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id003
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id004
  url: /providers/amazon-sqs/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id005
  name: Amazon Timestream
  slug: amazon-timestream
  status: profiled
  tags: *id006
  url: /providers/amazon-timestream/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id007
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id008
  url: /providers/apache-kafka/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id009
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id010
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id011
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id012
  url: /providers/elastic/
- agent_band: human-only
  agent_readiness: 3.7
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id013
  name: Graylog
  slug: graylog
  status: profiled
  tags: *id014
  url: /providers/graylog/
- agent_band: agent-ready
  agent_readiness: 35.1
  band: strong
  in_catalog: true
  kin_score: 64.0
  mcp: *id015
  name: InfluxDB
  slug: influxdata
  status: profiled
  tags: *id016
  url: /providers/influxdata/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id017
  name: Jaeger
  slug: jaeger
  status: profiled
  tags: *id018
  url: /providers/jaeger/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id019
  name: Logz.io
  slug: logz-io
  status: profiled
  tags: *id020
  url: /providers/logz-io/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id021
  name: Moesif
  slug: moesif
  status: profiled
  tags: *id022
  url: /providers/moesif/
- agent_band: agent-ready
  agent_readiness: 56.0
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id023
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id024
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: developing
  in_catalog: true
  kin_score: 39.9
  mcp: *id025
  name: NATS
  slug: nats
  status: profiled
  tags: *id026
  url: /providers/nats/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id027
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id028
  url: /providers/new-relic/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id029
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id030
  url: /providers/opentelemetry/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id031
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id032
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 20.0
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id033
  name: RabbitMQ
  slug: rabbitmq
  status: profiled
  tags: *id034
  url: /providers/rabbitmq/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id035
  name: Redis
  slug: redis
  status: profiled
  tags: *id036
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id037
  name: Resurface
  slug: resurface
  status: profiled
  tags: *id038
  url: /providers/resurface/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id039
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id040
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id041
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id042
  url: /providers/splunk/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id043
  name: StatsD
  slug: statsd
  status: profiled
  tags: *id044
  url: /providers/statsd/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id045
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id046
  url: /providers/segment/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id047
  name: Zipkin
  slug: zipkin
  status: profiled
  tags: *id048
  url: /providers/zipkin/
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
- name: KrakenD CE
  rows: 12
  url: /applications/api-management-gateway/krakend-ce/
- name: Postman
  rows: 20
  url: /applications/api-management-gateway/postman/
- name: Traefik Proxy
  rows: 15
  url: /applications/api-management-gateway/traefik-proxy/
- name: Zuplo
  rows: 36
  url: /applications/api-management-gateway/zuplo/
sitemap: true
title: 'Tyk Gateway + Tyk Pump: API Management & Gateways reference app'
---
