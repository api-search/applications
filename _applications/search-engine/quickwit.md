---
app: Quickwit
app_slug: quickwit
app_url: https://github.com/quickwit-oss/quickwit
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
  - Apache Pulsar
  - Google Cloud Pub/Sub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
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
  observed: 8
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.6
    band: exemplar
    in_catalog: true
    kin_score: 70.7
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id009
      status: none
    slug: apache-pulsar
    status: profiled
    tags: &id010
    - Cloud-Native
    - Messaging
    - Multi-Tenant
    - Pub/Sub
    url: /providers/apache-pulsar/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id012
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id015
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id016
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-storage/src/opendal_storage
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/quickwit/
providers:
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id001
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id002
  url: /providers/kinesis/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id005
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id006
  url: /providers/amazon-sqs/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id007
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id008
  url: /providers/apache-kafka/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id009
  name: Apache Pulsar
  slug: apache-pulsar
  status: profiled
  tags: *id010
  url: /providers/apache-pulsar/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id011
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id012
  url: /providers/microsoft-azure-blob-storage/
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
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id015
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id016
  url: /providers/gcp-cloud-storage/
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
- name: OpenSearch
  rows: 23
  url: /applications/search-engine/opensearch/
- name: SearXNG
  rows: 49
  url: /applications/search-engine/searxng/
- name: Typesense
  rows: 5
  url: /applications/search-engine/typesense/
sitemap: true
title: 'Quickwit: Site & App Search reference app'
---
