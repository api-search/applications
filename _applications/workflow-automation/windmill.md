---
app: Windmill
app_slug: windmill
app_url: https://github.com/windmill-labs/windmill
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - BigQuery (bigquery feature)
  - Snowflake (snowflake feature)
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Amazon SQS (sqs trigger)
  - Google Cloud Pub/Sub (gcp trigger)
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - Oracle Database (oracle crate)
  - SQL Server (tiberius)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - AWS Secrets Manager
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe (stripe feature)
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3 (object_store aws)
  - Azure Blob Storage (object_store azure)
  - Google Cloud Storage (object_store gcp)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock (aws-sdk-bedrock)
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: workflow-automation
  name: Workflow Automation & iPaaS
  url: /applications/workflow-automation/
counts:
  declared: 0
  observed: 12
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
- route: dependency manifest
  url: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
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
    agent_band: agent-native
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
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
  name: Amazon Bedrock (aws-sdk-bedrock)
  provider: amazon-bedrock
  says: ships the Amazon Bedrock (aws-sdk-bedrock) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
  name: Amazon S3 (object_store aws)
  provider: amazon-s3
  says: ships the Amazon S3 (object_store aws) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
  name: Amazon SQS (sqs trigger)
  provider: amazon-sqs
  says: ships the Amazon SQS (sqs trigger) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
    agent_band: agent-native
    agent_readiness: 39.2
    band: exemplar
    in_catalog: true
    kin_score: 77.5
    mcp: &id007
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Configuration
    - Credentials
    - Rotation
    url: /providers/amazon-secrets-manager/
  layer: common
  name: AWS Secrets Manager
  provider: amazon-secrets-manager
  says: ships the AWS Secrets Manager SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id010
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage (object_store azure)
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage (object_store azure) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id011
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id012
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: BigQuery (bigquery feature)
  provider: google-bigquery
  says: ships the BigQuery (bigquery feature) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
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
  name: Google Cloud Pub/Sub (gcp trigger)
  provider: google-cloud-pubsub
  says: ships the Google Cloud Pub/Sub (gcp trigger) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
  name: Google Cloud Storage (object_store gcp)
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage (object_store gcp) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
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
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id017
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id018
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Database (oracle crate)
  provider: oracle
  says: ships the Oracle Database (oracle crate) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
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
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id019
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id020
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake (snowflake feature)
  provider: snowflake
  says: ships the Snowflake (snowflake feature) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
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
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id021
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id022
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: domain
  name: SQL Server (tiberius)
  provider: microsoft-sql-server
  says: ships the SQL Server (tiberius) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe (stripe feature)
  provider: stripe
  says: ships the Stripe (stripe feature) SDK or integration code
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/workflow-automation/windmill/
providers:
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id001
  name: Amazon Bedrock (aws-sdk-bedrock)
  slug: amazon-bedrock
  status: profiled
  tags: *id002
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3 (object_store aws)
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
  name: Amazon SQS (sqs trigger)
  slug: amazon-sqs
  status: profiled
  tags: *id006
  url: /providers/amazon-sqs/
- agent_band: agent-native
  agent_readiness: 39.2
  band: exemplar
  in_catalog: true
  kin_score: 77.5
  mcp: *id007
  name: AWS Secrets Manager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id008
  url: /providers/amazon-secrets-manager/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id009
  name: Azure Blob Storage (object_store azure)
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id011
  name: BigQuery (bigquery feature)
  slug: google-bigquery
  status: profiled
  tags: *id012
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id013
  name: Google Cloud Pub/Sub (gcp trigger)
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
  name: Google Cloud Storage (object_store gcp)
  slug: gcp-cloud-storage
  status: profiled
  tags: *id016
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id017
  name: Oracle Database (oracle crate)
  slug: oracle
  status: profiled
  tags: *id018
  url: /providers/oracle/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id019
  name: Snowflake (snowflake feature)
  slug: snowflake
  status: profiled
  tags: *id020
  url: /providers/snowflake/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id021
  name: SQL Server (tiberius)
  slug: microsoft-sql-server
  status: profiled
  tags: *id022
  url: /providers/microsoft-sql-server/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe (stripe feature)
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
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
- name: n8n
  rows: 39
  url: /applications/workflow-automation/n8n/
sitemap: true
title: 'Windmill: Workflow Automation & iPaaS reference app'
---
