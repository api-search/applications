---
app: Apache NiFi
app_slug: apache-nifi
app_url: https://github.com/apache/nifi
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Apache Iceberg
  - Google BigQuery
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: domain
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Azure Data Lake Storage
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  - Amazon SNS
  - Amazon SQS
  - Apache Kafka
  - Azure Event Hubs
  - Confluent
  - Google Cloud Pub/Sub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  - Apache IoTDB
  - Azure Cosmos DB
  - Couchbase
  - Hazelcast
  - MongoDB
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Splunk
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: data-integration-etl
  name: Data Integration & ETL
  url: /applications/data-integration-etl/
counts:
  declared: 0
  observed: 35
credits: []
evidence:
- route: source code
  url: https://github.com/apache/nifi/tree/main/nifi-extension-bundles
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id001
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id002
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: domain
  name: Airtable
  provider: airtable
  says: ships the Airtable SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-airtable-bundle
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
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
  layer: domain
  name: Amazon DynamoDB
  provider: amazon-dynamodb
  says: ships the Amazon DynamoDB SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/dynamodb
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
    mcp: &id005
      status: none
    slug: kinesis
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
  layer: domain
  name: Amazon Kinesis
  provider: kinesis
  says: ships the Amazon Kinesis SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/kinesis
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
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
  layer: domain
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/s3
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
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id009
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: domain
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/sns
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
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id012
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: domain
  name: Amazon SQS
  provider: amazon-sqs
  says: ships the Amazon SQS SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/sqs
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
    agent_readiness: 40.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id013
      status: unknown
    slug: apache-iceberg
    status: profiled
    tags: &id014
    - ACID
    - Analytics
    - Apache
    - Data Lake
    url: /providers/apache-iceberg/
  layer: domain
  name: Apache Iceberg
  provider: apache-iceberg
  says: ships the Apache Iceberg SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-iceberg-bundle
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
    agent_band: agent-aware
    agent_readiness: 19.3
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id015
      status: unchecked
    slug: apache-iotdb
    status: profiled
    tags: &id016
    - Company
    - Database
    - IoT
    - Time Series
    url: /providers/apache-iotdb/
  layer: domain
  name: Apache IoTDB
  provider: apache-iotdb
  says: ships the Apache IoTDB SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-iotdb-bundle
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
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-kafka-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id019
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id020
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: domain
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/storage
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
    agent_readiness: 30.9
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id021
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-cosmos-db
    status: profiled
    tags: &id022
    - Database
    - Document Database
    - NoSQL
    - Vector Search
    url: /providers/azure-cosmos-db/
  layer: domain
  name: Azure Cosmos DB
  provider: azure-cosmos-db
  says: ships the Azure Cosmos DB SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/cosmos
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id023
      status: none
    slug: microsoft-azure-data-lake
    status: profiled
    tags: &id024
    - Analytics
    - Big Data
    - Data Lake
    - Hierarchical Storage
    url: /providers/microsoft-azure-data-lake/
  layer: domain
  name: Azure Data Lake Storage
  provider: microsoft-azure-data-lake
  says: ships the Azure Data Lake Storage SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/storage
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
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.4
    mcp: &id025
      source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-event-hubs
      status: verified
    slug: microsoft-azure-event-hubs
    status: profiled
    tags: &id026
    - Big Data
    - Event Streaming
    - IoT
    - Message Ingestion
    url: /providers/microsoft-azure-event-hubs/
  layer: domain
  name: Azure Event Hubs
  provider: microsoft-azure-event-hubs
  says: ships the Azure Event Hubs SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/eventhub
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id027
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id028
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: ships the Box SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-box-bundle
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 87.2
    mcp: &id029
      source: https://github.com/confluentinc/mcp-confluent
      status: verified
    slug: confluent
    status: profiled
    tags: &id030
    - Apache Kafka
    - Data Streaming
    - Event Streaming
    - Stream Processing
    url: /providers/confluent/
  layer: domain
  name: Confluent
  provider: confluent
  says: ships the Confluent SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-confluent-platform-bundle
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
    agent_band: agent-aware
    agent_readiness: 28.4
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id031
      source: https://github.com/couchbase/mcp-server-couchbase
      status: verified
    slug: couchbase
    status: profiled
    tags: &id032
    - Analytics
    - App Services
    - Backup
    - Capella
    url: /providers/couchbase/
  layer: domain
  name: Couchbase
  provider: couchbase
  says: ships the Couchbase SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-couchbase-bundle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id033
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id034
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-dropbox-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id035
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id036
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elasticsearch
  provider: elastic
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-elasticsearch-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id037
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id038
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-github-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id039
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id040
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gitlab-bundle
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
    mcp: &id041
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id042
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: ships the Google BigQuery SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/bigquery
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
    mcp: &id043
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id044
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
  layer: domain
  name: Google Cloud Pub/Sub
  provider: google-cloud-pubsub
  says: ships the Google Cloud Pub/Sub SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/pubsub
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id045
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id046
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: domain
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/storage
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id047
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id048
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/drive
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
    agent_band: agent-aware
    agent_readiness: 16.8
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id049
      status: none
    slug: hazelcast
    status: profiled
    tags: &id050
    - Data Caching
    - Distributed Computing
    - In-Memory Computing
    - Real-Time
    url: /providers/hazelcast/
  layer: domain
  name: Hazelcast
  provider: hazelcast
  says: ships the Hazelcast SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-hazelcast-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id051
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id052
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-hubspot-bundle
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
    agent_readiness: 59.1
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id053
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id054
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: domain
  name: MongoDB
  provider: mongodb
  says: ships the MongoDB SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-mongodb-bundle
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
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id055
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id056
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: domain
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-redis-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id057
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id058
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: ships the Salesforce SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-salesforce-bundle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id059
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id060
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: ships the Shopify SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-shopify-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id061
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id062
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-slack-bundle
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
    mcp: &id063
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id064
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: ships the Snowflake SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-snowflake-bundle
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
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
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
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-splunk-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id067
      status: none
    slug: workday
    status: profiled
    tags: &id068
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: ships the Workday SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-workday-bundle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id069
      status: none
    slug: zendesk
    status: profiled
    tags: &id070
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: ships the Zendesk SDK or integration code
  source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-zendesk-bundle
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/data-integration-etl/apache-nifi/
providers:
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id001
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id002
  url: /providers/airtable/
- agent_band: agent-native
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id003
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id004
  url: /providers/amazon-dynamodb/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id005
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id006
  url: /providers/kinesis/
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
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id009
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id010
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id011
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id012
  url: /providers/amazon-sqs/
- agent_band: agent-native
  agent_readiness: 40.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id013
  name: Apache Iceberg
  slug: apache-iceberg
  status: profiled
  tags: *id014
  url: /providers/apache-iceberg/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id015
  name: Apache IoTDB
  slug: apache-iotdb
  status: profiled
  tags: *id016
  url: /providers/apache-iotdb/
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
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id019
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id020
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 30.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id021
  name: Azure Cosmos DB
  slug: azure-cosmos-db
  status: profiled
  tags: *id022
  url: /providers/azure-cosmos-db/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id023
  name: Azure Data Lake Storage
  slug: microsoft-azure-data-lake
  status: profiled
  tags: *id024
  url: /providers/microsoft-azure-data-lake/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.4
  mcp: *id025
  name: Azure Event Hubs
  slug: microsoft-azure-event-hubs
  status: profiled
  tags: *id026
  url: /providers/microsoft-azure-event-hubs/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id027
  name: Box
  slug: box
  status: profiled
  tags: *id028
  url: /providers/box/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 87.2
  mcp: *id029
  name: Confluent
  slug: confluent
  status: profiled
  tags: *id030
  url: /providers/confluent/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id031
  name: Couchbase
  slug: couchbase
  status: profiled
  tags: *id032
  url: /providers/couchbase/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id033
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id034
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id035
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id036
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id037
  name: GitHub
  slug: github
  status: profiled
  tags: *id038
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id039
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id040
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id041
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id042
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id043
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id044
  url: /providers/google-cloud-pubsub/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id045
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id046
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id047
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id048
  url: /providers/google-drive/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id049
  name: Hazelcast
  slug: hazelcast
  status: profiled
  tags: *id050
  url: /providers/hazelcast/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id051
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id052
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id053
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id054
  url: /providers/mongodb/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id055
  name: Redis
  slug: redis
  status: profiled
  tags: *id056
  url: /providers/redis/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id057
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id058
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id059
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id060
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id061
  name: Slack
  slug: slack
  status: profiled
  tags: *id062
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id063
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id064
  url: /providers/snowflake/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id065
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id066
  url: /providers/splunk/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id067
  name: Workday
  slug: workday
  status: profiled
  tags: *id068
  url: /providers/workday/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id069
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id070
  url: /providers/zendesk/
siblings:
- name: Airbyte
  rows: 135
  url: /applications/data-integration-etl/airbyte/
- name: dlt (dltHub)
  rows: 27
  url: /applications/data-integration-etl/dlt-dlthub/
- name: Estuary Flow
  rows: 87
  url: /applications/data-integration-etl/estuary-flow/
- name: Fivetran
  rows: 99
  url: /applications/data-integration-etl/fivetran/
- name: Hightouch
  rows: 12
  url: /applications/data-integration-etl/hightouch/
sitemap: true
title: 'Apache NiFi: Data Integration & ETL reference app'
---
