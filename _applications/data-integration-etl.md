---
access: understanding
agent_layer: []
apps:
- anchor: airbyte
  counts:
    declared: 0
    observed: 135
  evidence:
  - route: source code
    url: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Adobe Commerce (Magento)
    provider: adobe-commerce
    says: ships the Adobe Commerce (Magento) SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-adobe-commerce-magento
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aircall
    provider: aircall
    says: ships the Aircall SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-aircall
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Airtable
    provider: airtable
    says: ships the Airtable SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-airtable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Ads
    provider: amazon-ads
    says: ships the Amazon Ads SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-amazon-ads
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: ships the Amazon DynamoDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-dynamodb
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-kinesis
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: ships the Amazon Redshift SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-redshift
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-s3
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-amazon-sqs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-amplitude
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Apache Cassandra
    provider: cassandra
    says: ships the Apache Cassandra SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-cassandra
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Doris
    provider: apache-doris
    says: ships the Apache Doris SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-doris
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-kafka
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pulsar
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-appsflyer
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: ships the Asana SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-asana
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ashby
    provider: ashby
    says: ships the Ashby SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-ashby
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-azure-blob-storage
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: ships the Box SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-box
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Braintree
    provider: braintree
    says: ships the Braintree SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-braintree
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: ships the Braze SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-braze
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Brevo
    provider: brevo
    says: ships the Brevo SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-brevo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chargebee
    provider: chargebee
    says: ships the Chargebee SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-chargebee
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Chroma
    provider: chroma
    says: ships the Chroma SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-chroma
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-clickhouse
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Cloudflare R2
    provider: cloudflare
    says: ships the Cloudflare R2 SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-r2
    tier: observed
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
    says: ships the commercetools SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-commercetools
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Confluence
    provider: confluence
    says: ships the Confluence SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-confluence
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Convex
    provider: convex
    says: ships the Convex SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-convex
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Couchbase
    provider: couchbase
    says: ships the Couchbase SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-couchbase
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cumul.io
    provider: cumulio
    says: ships the Cumul.io SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-cumulio
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Customer.io
    provider: customer-io
    says: ships the Customer.io SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-customer-io
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databend
    provider: databend
    says: ships the Databend SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-databend
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-databricks
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-datadog
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: DataStax Astra DB
    provider: datastax
    says: ships the DataStax Astra DB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-astra
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: deepset
    provider: deepset
    says: ships the deepset SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-deepset
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: DuckDB
    provider: duckdb
    says: ships the DuckDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-duckdb
    tier: observed
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
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-elasticsearch
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Exasol
    provider: exasol
    says: ships the Exasol SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-exasol
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook / Meta Ads
    provider: facebook
    says: ships the Facebook / Meta Ads SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-facebook-marketing
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Firebase / Firestore
    provider: firebase
    says: ships the Firebase / Firestore SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-firestore
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Firebolt
    provider: firebolt
    says: ships the Firebolt SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-firebolt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: ships the Freshdesk SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-freshdesk
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Front
    provider: front
    says: ships the Front SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-front
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-github
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-gitlab
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.80
      key: webhook-event-subscription-management
      name: Webhook & Event Subscription Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: null
    credit: null
    layer: domain
    name: GlassFlow
    provider: glassflow
    says: ships the GlassFlow SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-glassflow
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gong
    provider: gong
    says: ships the Gong SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-gong
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ads
    provider: google-ads
    says: ships the Google Ads SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-ads
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-analytics-data-api
    tier: observed
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
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-bigquery
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pubsub
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-gcs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-drive
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Search Console
    provider: google-search-console
    says: ships the Google Search Console SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-search-console
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-google-sheets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenhouse
    provider: greenhouse
    says: ships the Greenhouse SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-greenhouse
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: ships the HiBob SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-hibob
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-hubspot
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: IBM Db2
    provider: ibm-db2
    says: ships the IBM Db2 SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-db2
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: incident.io
    provider: incident-io
    says: ships the incident.io SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-incident-io
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: ships the Intercom SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-intercom
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Iterable
    provider: iterable
    says: ships the Iterable SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-iterable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-jira
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Keen
    provider: keen
    says: ships the Keen SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-keen
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: ships the Klaviyo SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-klaviyo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-linear
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn Ads
    provider: linkedin-ads
    says: ships the LinkedIn Ads SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-linkedin-ads
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-mailchimp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MariaDB
    provider: mariadb
    says: ships the MariaDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mariadb-columnstore
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Marketo
    provider: marketo
    says: ships the Marketo SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-marketo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Meilisearch
    provider: meilisearch
    says: ships the Meilisearch SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-meilisearch
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Advertising (Bing Ads)
    provider: microsoft-advertising
    says: ships the Microsoft Advertising (Bing Ads) SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-bing-ads
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: ships the Microsoft Dynamics 365 SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-dataverse
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: ships the Microsoft OneDrive SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-onedrive
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: ships the Microsoft SharePoint SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-sharepoint
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mssql
    tier: observed
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
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-teams
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Milvus
    provider: milvus
    says: ships the Milvus SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-milvus
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-mixpanel
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: ships the monday.com SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-monday
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mongodb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: MotherDuck
    provider: motherduck
    says: ships the MotherDuck SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-motherduck
    tier: observed
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
    says: ships the MySQL SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mysql
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: ships the Notion SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-notion
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-okta
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Oracle Database
    provider: oracle
    says: ships the Oracle Database SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-oracle
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle NetSuite
    provider: netsuite
    says: ships the Oracle NetSuite SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-netsuite
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Outreach
    provider: outreach
    says: ships the Outreach SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-outreach
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: pgvector
    provider: pgvector
    says: ships the pgvector SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pgvector
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Pinecone
    provider: pinecone
    says: ships the Pinecone SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pinecone
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: ships the Pipedrive SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-pipedrive
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-postgres
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-posthog
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Qdrant
    provider: qdrant
    says: ships the Qdrant SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-qdrant
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: ships the QuickBooks SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-quickbooks
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-rabbitmq
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Ragie
    provider: ragie-ai
    says: ships the Ragie SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-ragie
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Recharge
    provider: recharge-payments
    says: ships the Recharge SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-recharge
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-redis
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
    name: Redpanda
    provider: redpanda
    says: ships the Redpanda SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-redpanda
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: RingCentral
    provider: ringcentral
    says: ships the RingCentral SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-ringcentral
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rockset
    provider: rockset
    says: ships the Rockset SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-rockset
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-salesforce
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: ScyllaDB
    provider: scylladb
    says: ships the ScyllaDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-scylla
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-sendgrid
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
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-sentry
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: ships the Shopify SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-shopify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SingleStore
    provider: singlestore
    says: ships the SingleStore SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-singlestore
    tier: observed
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
    says: ships the Slack SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-slack
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Smartsheet
    provider: smartsheet
    says: ships the Smartsheet SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-smartsheets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snapchat Ads
    provider: snapchat
    says: ships the Snapchat Ads SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-snapchat-marketing
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-snowflake
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Starburst Galaxy
    provider: starburst
    says: ships the Starburst Galaxy SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-starburst-galaxy
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-stripe
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: SurrealDB
    provider: surrealdb
    says: ships the SurrealDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-surrealdb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teradata
    provider: teradata
    says: ships the Teradata SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-teradata
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: TiDB (PingCAP)
    provider: pingcap
    says: ships the TiDB (PingCAP) SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-tidb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok Ads
    provider: tiktok
    says: ships the TikTok Ads SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-tiktok-marketing
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Timeplus
    provider: timeplus
    says: ships the Timeplus SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-timeplus
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-twilio
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-segment
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Typesense
    provider: typesense
    says: ships the Typesense SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-typesense
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Vectara
    provider: vectara
    says: ships the Vectara SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-vectara
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: ships the Vertica SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-vertica
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Weaviate
    provider: weaviate
    says: ships the Weaviate SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-weaviate
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workable
    provider: workable
    says: ships the Workable SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-workable
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Xata
    provider: xata
    says: ships the Xata SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-xata
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: ships the Xero SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-xero
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Yellowbrick
    provider: yellowbrick
    says: ships the Yellowbrick SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-yellowbrick
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: YugabyteDB
    provider: yugabyte
    says: ships the YugabyteDB SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-yugabytedb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-zendesk-support
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho CRM
    provider: zoho
    says: ships the Zoho CRM SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-zoho-crm
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zuora
    provider: zuora
    says: ships the Zuora SDK or integration code
    source: https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-zuora
    tier: observed
  kind: self-hosted
  name: Airbyte
  page: /applications/data-integration-etl/airbyte/
  slug: airbyte
  url: https://github.com/airbytehq/airbyte
- anchor: dlt-(dlthub)
  counts:
    declared: 0
    observed: 27
  evidence:
  - route: source code
    url: https://github.com/dlt-hub/verified-sources/tree/master/sources
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Airtable
    provider: airtable
    says: ships the Airtable SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/airtable
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
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/kinesis
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
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/kafka
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: ships the Asana SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/asana_dlt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bing Webmaster Tools
    provider: microsoft-bing
    says: ships the Bing Webmaster Tools SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/bing_webmaster
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook / Meta Ads
    provider: facebook
    says: ships the Facebook / Meta Ads SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/facebook_ads
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: ships the Freshdesk SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/freshdesk
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/github
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ads
    provider: google-ads
    says: ships the Google Ads SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/google_ads
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/google_analytics
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/google_sheets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/hubspot
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/jira
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/matomo
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: ships the Microsoft SharePoint SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/sharepoint
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/mongodb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: ships the Notion SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/notion
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Personio
    provider: personio
    says: ships the Personio SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/personio
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: ships the Pipedrive SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/pipedrive
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/pg_replication
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/salesforce
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: ServiceNow
    provider: servicenow
    says: ships the ServiceNow SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/servicenow
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: ships the Shopify SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/shopify_dlt
    tier: observed
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
    says: ships the Slack SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/slack
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/stripe_analytics
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workable
    provider: workable
    says: ships the Workable SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/workable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://github.com/dlt-hub/verified-sources/tree/master/sources/zendesk
    tier: observed
  kind: self-hosted
  name: dlt (dltHub)
  page: /applications/data-integration-etl/dlt-dlthub/
  slug: dlt-dlthub
  url: https://github.com/dlt-hub/verified-sources
- anchor: estuary-flow
  counts:
    declared: 0
    observed: 87
  evidence:
  - route: source code
    url: https://github.com/estuary/connectors
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aircall
    provider: aircall
    says: ships the Aircall SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-aircall-native
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Airtable
    provider: airtable
    says: ships the Airtable SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-airtable
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: ships the Amazon DynamoDB SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-dynamodb
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
    name: Amazon EventBridge
    provider: amazon-eventbridge
    says: ships the Amazon EventBridge SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-eventbridge
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
    source: https://github.com/estuary/connectors/tree/main/source-kinesis
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: ships the Amazon Redshift SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-redshift
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-s3-parquet
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
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-sns
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
    source: https://github.com/estuary/connectors/tree/main/source-sqs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Iceberg
    provider: apache-iceberg
    says: ships the Apache Iceberg SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-iceberg
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
    source: https://github.com/estuary/connectors/tree/main/materialize-kafka
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-appsflyer
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: ships the Asana SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-asana
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ashby
    provider: ashby
    says: ships the Ashby SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-ashby
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-azure-blob-parquet
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Braintree
    provider: braintree
    says: ships the Braintree SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-braintree-native
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Brevo
    provider: brevo
    says: ships the Brevo SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-brevo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chargebee
    provider: chargebee
    says: ships the Chargebee SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-chargebee-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-clickhouse
    tier: observed
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
    says: ships the commercetools SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-commercetools
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Criteo
    provider: criteo
    says: ships the Criteo SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-criteo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-databricks
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
    source: https://github.com/estuary/connectors/tree/main/source-datadog
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-dropbox
    tier: observed
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
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-elasticsearch
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook / Meta Ads
    provider: facebook
    says: ships the Facebook / Meta Ads SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-facebook-marketing-native
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Firebase / Firestore
    provider: firebase
    says: ships the Firebase / Firestore SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-firestore
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Front
    provider: front
    says: ships the Front SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-front
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Genesys
    provider: genesys
    says: ships the Genesys SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-genesys
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gladly
    provider: gladly
    says: ships the Gladly SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-gladly
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gong
    provider: gong
    says: ships the Gong SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-gong
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ads
    provider: google-ads
    says: ships the Google Ads SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-google-ads
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-google-analytics-data-api-native
    tier: observed
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
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-bigquery
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Bigtable
    provider: google-cloud-bigtable
    says: ships the Google Cloud Bigtable SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-bigtable
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
    source: https://github.com/estuary/connectors/tree/main/materialize-google-pubsub
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Spanner
    provider: google-cloud-spanner
    says: ships the Google Cloud Spanner SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-spanner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-gcs-parquet
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-google-drive
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: Google Play Console
    provider: google-play
    says: ships the Google Play Console SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-google-play
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-google-sheets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenhouse
    provider: greenhouse
    says: ships the Greenhouse SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-greenhouse-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: ships the HiBob SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-hibob
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-hubspot
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: IBM Db2
    provider: ibm-db2
    says: ships the IBM Db2 SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-db2-batch
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: incident.io
    provider: incident-io
    says: ships the incident.io SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-incident-io
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: ships the Intercom SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-intercom-native
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Iterable
    provider: iterable
    says: ships the Iterable SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-iterable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-jira-native
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: ships the Klaviyo SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-klaviyo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-linear
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn Ads
    provider: linkedin-ads
    says: ships the LinkedIn Ads SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-linkedin-ads-v2
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-mailchimp-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Advertising (Bing Ads)
    provider: microsoft-advertising
    says: ships the Microsoft Advertising (Bing Ads) SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-bing-ads-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: ships the Microsoft Dynamics 365 SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-dynamics-365-finance-and-operations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Fabric
    provider: microsoft-fabric
    says: ships the Microsoft Fabric SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-azure-fabric-warehouse
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: ships the Microsoft OneDrive SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-onedrive
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: ships the Microsoft SharePoint SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-sharepoint
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-sqlserver
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-mixpanel-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: ships the monday.com SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-monday
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-mongodb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: MotherDuck
    provider: motherduck
    says: ships the MotherDuck SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-motherduck
    tier: observed
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
    says: ships the MySQL SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-mysql
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: ships the Notion SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-notion
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-okta
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Oracle Database
    provider: oracle
    says: ships the Oracle Database SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-oracle
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Outreach
    provider: outreach
    says: ships the Outreach SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-outreach
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-pendo
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Pinecone
    provider: pinecone
    says: ships the Pinecone SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-pinecone
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-postgres
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-posthog
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: ships the QuickBooks SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-quickbooks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Recharge
    provider: recharge-payments
    says: ships the Recharge SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-recharge
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: RingCentral
    provider: ringcentral
    says: ships the RingCentral SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-ringcentral
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sage Intacct
    provider: sage-intacct
    says: ships the Sage Intacct SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-sage-intacct
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-salesforce-native
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
    source: https://github.com/estuary/connectors/tree/main/source-sentry
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: ships the Shopify SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-shopify-native
    tier: observed
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
    says: ships the Slack SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-slack
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Smartsheet
    provider: smartsheet
    says: ships the Smartsheet SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-smartsheet
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/materialize-snowflake
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-stripe-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok Ads
    provider: tiktok
    says: ships the TikTok Ads SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-tiktok-ads-native
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-twilio
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-zendesk-support-native
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zuora
    provider: zuora
    says: ships the Zuora SDK or integration code
    source: https://github.com/estuary/connectors/tree/main/source-zuora
    tier: observed
  kind: open-source-saas
  name: Estuary Flow
  page: /applications/data-integration-etl/estuary-flow/
  slug: estuary-flow
  url: https://github.com/estuary/connectors
- anchor: apache-nifi
  counts:
    declared: 0
    observed: 35
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
    layer: domain
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-zendesk-bundle
    tier: observed
  kind: self-hosted
  name: Apache NiFi
  page: /applications/data-integration-etl/apache-nifi/
  slug: apache-nifi
  url: https://github.com/apache/nifi
- anchor: fivetran
  counts:
    declared: 99
    observed: 0
  evidence:
  - route: integrations page
    url: https://fivetran.com/docs/connectors
  - route: integrations page
    url: https://fivetran.com/docs/destinations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Adobe Commerce (Magento)
    provider: adobe-commerce
    says: lists Adobe Commerce (Magento) as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aircall
    provider: aircall
    says: lists Aircall as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: lists Amazon DynamoDB as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
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
    says: lists Amazon Kinesis as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Amazon Redshift
    provider: amazon-redshift
    says: lists Amazon Redshift as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
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
    says: lists Apache Kafka as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: lists AppsFlyer as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ashby
    provider: ashby
    says: lists Ashby as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: lists Azure Blob Storage as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Azure Cosmos DB
    provider: azure-cosmos-db
    says: lists Azure Cosmos DB as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Azure Synapse
    provider: microsoft-azure-synapse-analytics
    says: lists Azure Synapse as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Braintree
    provider: braintree
    says: lists Braintree as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Brevo
    provider: brevo
    says: lists Brevo as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chargebee
    provider: chargebee
    says: lists Chargebee as an integration
    source: https://fivetran.com/docs/connectors
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
    name: ClickHouse
    provider: clickhouse
    says: lists ClickHouse as an integration
    source: https://fivetran.com/docs/destinations
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
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Confluent
    provider: confluent
    says: lists Confluent as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Convex
    provider: convex
    says: lists Convex as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Criteo
    provider: criteo
    says: lists Criteo as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Databricks
    provider: databricks
    says: lists Databricks as an integration
    source: https://fivetran.com/docs/destinations
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
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook / Meta Ads
    provider: facebook
    says: lists Facebook / Meta Ads as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Firebase / Firestore
    provider: firebase
    says: lists Firebase / Firestore as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Front
    provider: front
    says: lists Front as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Genesys
    provider: genesys
    says: lists Genesys as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gladly
    provider: gladly
    says: lists Gladly as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gong
    provider: gong
    says: lists Gong as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ads
    provider: google-ads
    says: lists Google Ads as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://fivetran.com/docs/connectors
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
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: Google Play Console
    provider: google-play
    says: lists Google Play Console as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Search Console
    provider: google-search-console
    says: lists Google Search Console as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenhouse
    provider: greenhouse
    says: lists Greenhouse as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: lists HiBob as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://fivetran.com/docs/connectors
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
    name: IBM Db2
    provider: ibm-db2
    says: lists IBM Db2 as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: incident.io
    provider: incident-io
    says: lists incident.io as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Iterable
    provider: iterable
    says: lists Iterable as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn Ads
    provider: linkedin-ads
    says: lists LinkedIn Ads as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://fivetran.com/docs/connectors
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
    name: MariaDB
    provider: mariadb
    says: lists MariaDB as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Materialize
    provider: materialize
    says: lists Materialize as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Matomo
    provider: matomo
    says: lists Matomo as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Advertising (Bing Ads)
    provider: microsoft-advertising
    says: lists Microsoft Advertising (Bing Ads) as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: lists Microsoft SharePoint as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: lists Microsoft SQL Server as an integration
    source: https://fivetran.com/docs/destinations
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
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Milvus
    provider: milvus
    says: lists Milvus as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://fivetran.com/docs/connectors
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
    name: MongoDB
    provider: mongodb
    says: lists MongoDB as an integration
    source: https://fivetran.com/docs/connectors
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
    name: MotherDuck
    provider: motherduck
    says: lists MotherDuck as an integration
    source: https://fivetran.com/docs/destinations
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
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Oracle Database
    provider: oracle
    says: lists Oracle Database as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle NetSuite
    provider: netsuite
    says: lists Oracle NetSuite as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Outreach
    provider: outreach
    says: lists Outreach as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Pendo
    provider: pendoio
    says: lists Pendo as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Personio
    provider: personio
    says: lists Personio as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://fivetran.com/docs/connectors
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
    name: PostgreSQL
    provider: postgresql
    says: lists PostgreSQL as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: PostHog
    provider: posthog
    says: lists PostHog as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Recharge
    provider: recharge-payments
    says: lists Recharge as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: RingCentral
    provider: ringcentral
    says: lists RingCentral as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: lists SendGrid as an integration
    source: https://fivetran.com/docs/connectors
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
    name: Sentry
    provider: sentry-system
    says: lists Sentry as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://fivetran.com/docs/connectors
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
    name: SingleStore
    provider: singlestore
    says: lists SingleStore as an integration
    source: https://fivetran.com/docs/destinations
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
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://fivetran.com/docs/connectors
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
    name: SurrealDB
    provider: surrealdb
    says: lists SurrealDB as an integration
    source: https://fivetran.com/docs/destinations
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
    name: Teradata
    provider: teradata
    says: lists Teradata as an integration
    source: https://fivetran.com/docs/destinations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zuora
    provider: zuora
    says: lists Zuora as an integration
    source: https://fivetran.com/docs/connectors
    tier: declared
  kind: commercial
  name: Fivetran
  page: /applications/data-integration-etl/fivetran/
  slug: fivetran
  url: https://fivetran.com
- anchor: hightouch
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://docs.hightouch.com/destinations/overview
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook / Meta Ads
    provider: facebook
    says: lists Facebook / Meta Ads as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ads
    provider: google-ads
    says: lists Google Ads as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Iterable
    provider: iterable
    says: lists Iterable as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn Ads
    provider: linkedin-ads
    says: lists LinkedIn Ads as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://docs.hightouch.com/destinations/overview
    tier: declared
  kind: commercial
  name: Hightouch
  page: /applications/data-integration-etl/hightouch/
  slug: hightouch
  url: https://hightouch.com
author: API Evangelist
candidates: []
credits: []
html: public
id: data-integration-etl
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: ETL Tools
  store: g2
  url: https://www.g2.com/categories/etl-tools
- category: Data Integration
  store: g2
  url: https://www.g2.com/categories/data-integration
- category: Reverse ETL
  store: g2
  url: https://www.g2.com/categories/reverse-etl
name: Data Integration & ETL
needs:
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Analytics & BI Management: Snowflake, Google BigQuery, Amazon Redshift, Databricks'
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: operational databases are both CDC sources and load targets
- capability:
    attribution: Turbo EA
    id: BC-4270.80
    key: webhook-event-subscription-management
    name: Webhook & Event Subscription Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: null
  fit: gap
  layer: domain
  why: 'event streams and queues are sources and sinks (gap: no event-streaming node)'
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: ad-platform spend and performance reporting
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: domain
  why: vector databases are a new class of destination for RAG pipelines
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: helpdesk tickets and conversations replicated to the warehouse
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: email/engagement platforms as sources and reverse-ETL targets
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: CRM is the most-replicated SaaS source and the main reverse-ETL target
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: product analytics events exported and activated
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: issue and work tracking data
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: domain
  why: object stores are data-lake destinations and file sources (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: file drives as file sources
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: accounting/ERP ledgers
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: spreadsheets as both sources and destinations
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ATS recruiting data
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: domain
  why: HRIS employee data
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: monitoring and log data
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: domain
  why: subscription billing data
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: payments data replicated for finance
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: storefront orders and catalog
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: code-host activity data (nearest)
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: chat messages as sources and alert sinks
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CDP event streams
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: directory and auth logs
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  fit: exact
  layer: common
  why: messaging/telephony logs
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.20
    key: AE-140.10.20
    name: Headless & Composable Commerce
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: headless commerce orders
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: incident records
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: nearest
  layer: domain
  why: app-store sales and reviews data (nearest)
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: Apache Kafka, Amazon Kinesis, Google Cloud Pub/Sub (Integration and API Management)
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: Elasticsearch, Meilisearch, Typesense (Search and Discovery Management)
stack:
- capabilities:
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
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mongodb
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-mongodb-bundle
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: observed
      url: /providers/mongodb/
    - agent_band: agent-native
      agent_readiness: 41.0
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon DynamoDB
      slug: amazon-dynamodb
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-dynamodb
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/dynamodb
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - Document Store
      - Key-Value Store
      tier: observed
      url: /providers/amazon-dynamodb/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: PostgreSQL
      slug: postgresql
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-postgres
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/pg_replication
      status: profiled
      tags:
      - Database
      - Open Source
      - Relational Database
      - SQL
      tier: observed
      url: /providers/postgresql/
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Database
      slug: oracle
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-oracle
      - https://github.com/estuary/connectors/tree/main/source-oracle
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: observed
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 67.0
      mcp:
        source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
        status: verified
      name: Microsoft SQL Server
      slug: microsoft-sql-server
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mssql
      - https://github.com/estuary/connectors/tree/main/materialize-sqlserver
      status: profiled
      tags:
      - Cloud
      - Data Management
      - Database
      - Enterprise
      tier: observed
      url: /providers/microsoft-sql-server/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase / Firestore
      slug: google-firebase
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-firestore
      - https://github.com/estuary/connectors/tree/main/source-firestore
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: MySQL
      slug: mysql
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mysql
      - https://github.com/estuary/connectors/tree/main/materialize-mysql
      status: profiled
      tags:
      - Database
      - Open Source
      - RDBMS
      - Relational Database
      tier: observed
      url: /providers/mysql/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: emerging
      in_catalog: true
      kin_score: 14.0
      mcp:
        status: none
      name: IBM Db2
      slug: ibm-db2
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-db2
      - https://github.com/estuary/connectors/tree/main/source-db2-batch
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Relational Database
      - SQL
      tier: observed
      url: /providers/ibm-db2/
    - agent_band: agent-ready
      agent_readiness: 30.9
      apps:
      - Apache NiFi
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Cosmos DB
      slug: azure-cosmos-db
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/cosmos
      status: profiled
      tags:
      - Database
      - Document Database
      - NoSQL
      - Vector Search
      tier: observed
      url: /providers/azure-cosmos-db/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Airbyte
      - Apache NiFi
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/couchbase/mcp-server-couchbase
        status: verified
      name: Couchbase
      slug: couchbase
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-couchbase
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-couchbase-bundle
      status: profiled
      tags:
      - Analytics
      - App Services
      - Backup
      - Capella
      tier: observed
      url: /providers/couchbase/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Airbyte
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://docs.convex.dev/ai/convex-mcp-server
        status: verified
      name: Convex
      slug: convex
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-convex
      status: profiled
      tags:
      - Backend
      - Database
      - Functions
      - Real-Time
      tier: observed
      url: /providers/convex/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Airbyte
      - Apache NiFi
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-redis
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-redis-bundle
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Airbyte
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: unchecked
      name: MariaDB
      slug: mariadb
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-mariadb-columnstore
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Open Source
      tier: observed
      url: /providers/mariadb/
    - agent_band: agent-aware
      agent_readiness: 16.1
      apps:
      - Airbyte
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        source: https://github.com/surrealdb/surrealmcp
        status: verified
      name: SurrealDB
      slug: surrealdb
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-surrealdb
      status: profiled
      tags:
      - Database
      - Document Database
      - Graph Database
      - Multi-Model
      tier: observed
      url: /providers/surrealdb/
    - agent_band: agent-ready
      agent_readiness: 40.5
      apps:
      - Airbyte
      band: exemplar
      in_catalog: true
      kin_score: 68.4
      mcp:
        source: https://docs.pingcap.com/ai/tidb-mcp-server/
        status: verified
      name: TiDB (PingCAP)
      slug: pingcap
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-tidb
      status: profiled
      tags:
      - Database
      - Distributed SQL
      - HTAP
      - tidb
      tier: observed
      url: /providers/pingcap/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Airbyte
      band: exemplar
      in_catalog: true
      kin_score: 67.3
      mcp:
        source: https://github.com/yugabyte/yugabytedb-mcp-server
        status: verified
      name: YugabyteDB
      slug: yugabyte
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-yugabytedb
      status: profiled
      tags:
      - Company
      - Database
      - Distributed SQL
      - PostgreSQL
      tier: observed
      url: /providers/yugabyte/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Estuary Flow
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://docs.cloud.google.com/bigtable/docs/use-bigtable-mcp
        status: verified
      name: Google Cloud Bigtable
      slug: google-cloud-bigtable
      sources:
      - https://github.com/estuary/connectors/tree/main/materialize-bigtable
      status: profiled
      tags:
      - Bigtable
      - Database
      - Google Cloud
      - NoSQL
      tier: observed
      url: /providers/google-cloud-bigtable/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Estuary Flow
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud Spanner
      slug: google-cloud-spanner
      sources:
      - https://github.com/estuary/connectors/tree/main/materialize-spanner
      status: profiled
      tags:
      - Database
      - Distributed
      - Google Cloud
      - Relational
      tier: observed
      url: /providers/google-cloud-spanner/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 53.2
      mcp:
        source: https://github.com/datastax/astra-db-mcp
        status: verified
      name: DataStax Astra DB
      slug: datastax
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-astra
      status: profiled
      tags:
      - Company
      - Database
      - Enterprise
      - Vector Search
      tier: observed
      url: /providers/datastax/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 45.2
      mcp:
        source: https://cloud.docs.scylladb.com/stable/api-docs/mcp.html
        status: verified
      name: ScyllaDB
      slug: scylladb
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-scylla
      status: profiled
      tags:
      - Cassandra Compatible
      - Database
      - DynamoDB Compatible
      - NoSQL
      tier: observed
      url: /providers/scylladb/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        source: https://github.com/xataio/mcp
        status: verified
      name: Xata
      slug: xata
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-xata
      status: profiled
      tags:
      - Database
      - Developer Tools
      - PostgreSQL
      - Serverless
      tier: observed
      url: /providers/xata/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Apache Cassandra
      slug: cassandra
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-cassandra
      status: profiled
      tags:
      - Apache
      - Big Data
      - Database
      - Distributed
      tier: observed
      url: /providers/cassandra/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Apache NiFi
      band: thin
      in_catalog: true
      kin_score: 28.5
      mcp:
        status: unchecked
      name: Apache IoTDB
      slug: apache-iotdb
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-iotdb-bundle
      status: profiled
      tags:
      - Company
      - Database
      - IoT
      - Time Series
      tier: observed
      url: /providers/apache-iotdb/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Apache NiFi
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: none
      name: Hazelcast
      slug: hazelcast
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-hazelcast-bundle
      status: profiled
      tags:
      - Data Caching
      - Distributed Computing
      - In-Memory Computing
      - Real-Time
      tier: observed
      url: /providers/hazelcast/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-snowflake
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-snowflake-bundle
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: observed
      url: /providers/snowflake/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-bigquery
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/bigquery
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: observed
      url: /providers/google-bigquery/
    - agent_band: agent-ready
      agent_readiness: 58.5
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 77.1
      mcp:
        source: https://github.com/ClickHouse/mcp-clickhouse
        status: verified
      name: ClickHouse
      slug: clickhouse
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-clickhouse
      - https://github.com/estuary/connectors/tree/main/materialize-clickhouse
      status: profiled
      tags:
      - Analytics
      - ClickHouse
      - Cloud Database
      - Column-Oriented
      tier: observed
      url: /providers/clickhouse/
    - agent_band: agent-native
      agent_readiness: 44.5
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
        status: verified
      name: Amazon Redshift
      slug: amazon-redshift
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-redshift
      - https://github.com/estuary/connectors/tree/main/materialize-redshift
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Lake
      tier: observed
      url: /providers/amazon-redshift/
    - agent_band: agent-native
      agent_readiness: 65.5
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-databricks
      - https://github.com/estuary/connectors/tree/main/materialize-databricks
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        source: https://github.com/motherduckdb/mcp-server-motherduck
        status: verified
      name: MotherDuck
      slug: motherduck
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-motherduck
      - https://github.com/estuary/connectors/tree/main/materialize-motherduck
      status: profiled
      tags:
      - Data Warehouse
      - DuckDB
      - SQL
      - Serverless
      tier: observed
      url: /providers/motherduck/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Airbyte
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 52.8
      mcp:
        source: https://github.com/Teradata/teradata-mcp-server
        status: verified
      name: Teradata
      slug: teradata
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-teradata
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Data Management
      - Data Warehousing
      tier: observed
      url: /providers/teradata/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Airbyte
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://github.com/singlestore-labs/mcp-server-singlestore
        status: verified
      name: SingleStore
      slug: singlestore
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-singlestore
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Database
      - SQL
      tier: observed
      url: /providers/singlestore/
    - agent_band: agent-native
      agent_readiness: 40.2
      apps:
      - Apache NiFi
      - Estuary Flow
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: unknown
      name: Apache Iceberg
      slug: apache-iceberg
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-iceberg-bundle
      - https://github.com/estuary/connectors/tree/main/materialize-iceberg
      status: profiled
      tags:
      - ACID
      - Analytics
      - Apache
      - Data Lake
      tier: observed
      url: /providers/apache-iceberg/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Estuary Flow
      band: strong
      in_catalog: true
      kin_score: 66.4
      mcp:
        source: https://github.com/microsoft/fabric-rti-mcp
        status: verified
      name: Microsoft Fabric
      slug: microsoft-fabric
      sources:
      - https://github.com/estuary/connectors/tree/main/materialize-azure-fabric-warehouse
      status: profiled
      tags:
      - Data Analytics
      - Data Engineering
      - Data Platform
      - Lakehouse
      tier: observed
      url: /providers/microsoft-fabric/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: unchecked
      name: Databend
      slug: databend
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-databend
      status: profiled
      tags:
      - Cloud
      - Company
      - Data Warehouse
      - Open Source
      tier: observed
      url: /providers/databend/
    - agent_band: human-only
      agent_readiness: 1.8
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        source: https://github.com/apache/doris-mcp-server
        status: verified
      name: Apache Doris
      slug: apache-doris
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-doris
      status: profiled
      tags:
      - Analytics
      - Apache
      - Database
      - Lakehouse
      tier: observed
      url: /providers/apache-doris/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        source: https://developer.luzmo.com/guide/mcp--introduction
        status: verified
      name: Cumul.io
      slug: cumulio
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-cumulio
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/cumulio/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        source: https://docs.starburst.io/starburst-galaxy/starburst-ai/mcp-server.html
        status: verified
      name: Starburst Galaxy
      slug: starburst
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-starburst-galaxy
      status: profiled
      tags:
      - Company
      - Data Analytics
      - Data Lakehouse
      - SQL Query Engine
      tier: observed
      url: /providers/starburst/
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: unchecked
      name: Timeplus
      slug: timeplus
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-timeplus
      status: profiled
      tags:
      - Analytics
      - Data Streaming
      - Open Source
      - Real-Time
      tier: observed
      url: /providers/timeplus/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        source: https://github.com/firebolt-db/mcp-server
        status: verified
      name: Firebolt
      slug: firebolt
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-firebolt
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Data Warehouse
      - SQL
      tier: observed
      url: /providers/firebolt/
    - agent_band: human-only
      agent_readiness: 1.3
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        status: none
      name: DuckDB
      slug: duckdb
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-duckdb
      status: profiled
      tags:
      - Analytics
      - Database
      - Embedded
      - OLAP
      tier: observed
      url: /providers/duckdb/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Airbyte
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Vertica
      slug: vertica
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-vertica
      status: profiled
      tags:
      - Analytics Database
      - Data Lakehouse
      - Data Warehouse
      - Database
      tier: observed
      url: /providers/vertica/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - Airbyte
      band: emerging
      in_catalog: true
      kin_score: 22.6
      mcp:
        status: unchecked
      name: Exasol
      slug: exasol
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-exasol
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Database
      tier: observed
      url: /providers/exasol/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Airbyte
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: unknown
      name: Rockset
      slug: rockset
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-rockset
      status: profiled
      tags:
      - Company
      - Defunct
      - Infrastructure
      tier: observed
      url: /providers/rockset/
    - agent_band: null
      agent_readiness: null
      apps:
      - Airbyte
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Yellowbrick
      slug: yellowbrick
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-yellowbrick
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 62.9
      mcp:
        status: none
      name: Azure Synapse
      slug: microsoft-azure-synapse-analytics
      sources:
      - https://fivetran.com/docs/destinations
      status: profiled
      tags:
      - Analytics
      - Apache Spark
      - Big Data
      - Data Integration
      tier: declared
      url: /providers/microsoft-azure-synapse-analytics/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        source: https://github.com/MaterializeInc/materialize-mcp-server
        status: verified
      name: Materialize
      slug: materialize
      sources:
      - https://fivetran.com/docs/destinations
      status: profiled
      tags:
      - Data Warehouse
      - Real-Time
      - SQL
      - Streaming
      tier: declared
      url: /providers/materialize/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - Hightouch
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-ads
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: observed
      url: /providers/google-ads/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - Hightouch
      - dlt (dltHub)
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook / Meta Ads
      slug: facebook
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-facebook-marketing
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - Hightouch
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        status: none
      name: LinkedIn Ads
      slug: linkedin-ads
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-linkedin-ads
      status: profiled
      tags:
      - Advertising
      - Lead Generation
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin-ads/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-appsflyer
      - https://github.com/estuary/connectors/tree/main/source-appsflyer
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 11.7
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        status: none
      name: Microsoft Advertising (Bing Ads)
      slug: microsoft-advertising
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-bing-ads
      - https://github.com/estuary/connectors/tree/main/source-bing-ads-native
      status: profiled
      tags:
      - Advertising
      - Analytics
      - Bing Ads
      - Bulk Operations
      tier: observed
      url: /providers/microsoft-advertising/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Airbyte
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Search Console
      slug: google-search-console
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-search-console
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: observed
      url: /providers/google-search-console/
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 62.2
      mcp:
        status: none
      name: Criteo
      slug: criteo
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/estuary/connectors/tree/main/source-criteo
      status: profiled
      tags:
      - Advertising
      - Agent Skills
      - Analytics
      - Audiences
      tier: observed
      url: /providers/criteo/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Airbyte
      - Estuary Flow
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok Ads
      slug: tiktok
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-tiktok-marketing
      - https://github.com/estuary/connectors/tree/main/source-tiktok-ads-native
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: observed
      url: /providers/tiktok/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Bing Webmaster Tools
      slug: microsoft
      sources:
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/bing_webmaster
      status: profiled
      tags:
      - Cloud
      - Fortune 100
      - Microsoft
      - Software
      tier: observed
      url: /providers/microsoft/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Airbyte
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Snapchat Ads
      slug: snapchat
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-snapchat-marketing
      status: profiled
      tags:
      - Advertising
      - Augmented Reality
      - Marketing
      - Messaging
      tier: observed
      url: /providers/snapchat/
    - agent_band: agent-aware
      agent_readiness: 18.2
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        source: https://advertising-ai.amazon.com/mcp
        status: verified
      name: Amazon Ads
      slug: amazon-ads
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-amazon-ads
      status: profiled
      tags:
      - Advertising
      - Amazon
      - Marketing
      - Technology
      tier: observed
      url: /providers/amazon-ads/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - Hightouch
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-zendesk-support
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - Hightouch
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-intercom
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: observed
      url: /providers/intercom/
    - agent_band: agent-ready
      agent_readiness: 43.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 59.4
      mcp:
        source: https://developers.ringcentral.com/mcp
        status: documented
      name: RingCentral
      slug: ringcentral
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-ringcentral
      - https://github.com/estuary/connectors/tree/main/source-ringcentral
      status: profiled
      tags:
      - Communications
      - UCaaS
      - Video
      - Voice
      tier: observed
      url: /providers/ringcentral/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        source: https://dev.frontapp.com/docs/mcp
        status: documented
      name: Front
      slug: front
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-front
      - https://github.com/estuary/connectors/tree/main/source-front
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Email
      - Inbox
      tier: observed
      url: /providers/front/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 30.0
      mcp:
        status: none
      name: Aircall
      slug: aircall
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-aircall
      - https://github.com/estuary/connectors/tree/main/source-aircall-native
      status: profiled
      tags:
      - CRM
      - Cloud Phone
      - Communications
      - Voice
      tier: observed
      url: /providers/aircall/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Airbyte
      - Fivetran
      - dlt (dltHub)
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-freshdesk
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/freshdesk
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: observed
      url: /providers/freshdesk/
    - agent_band: agent-native
      agent_readiness: 53.2
      apps:
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Genesys
      slug: genesys
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/estuary/connectors/tree/main/source-genesys
      status: profiled
      tags:
      - Company
      - Contact Center
      - Customer Experience
      - Software
      tier: observed
      url: /providers/genesys/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Fivetran
      - dlt (dltHub)
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/servicenow
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: observed
      url: /providers/servicenow/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Gladly
      slug: gladly
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/estuary/connectors/tree/main/source-gladly
      status: profiled
      tags:
      - AI Customer Service
      - Contact Center
      - Customer Experience
      - Customer Service
      tier: observed
      url: /providers/gladly/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - Hightouch
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-hubspot
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - Hightouch
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-salesforce
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 78.7
      mcp:
        status: none
      name: Outreach
      slug: outreach
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-outreach
      - https://github.com/estuary/connectors/tree/main/source-outreach
      status: profiled
      tags:
      - CRM
      - Sales
      - Sales Engagement
      - Sequences
      tier: observed
      url: /providers/outreach/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics 365
      slug: microsoft-dynamics-365
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-dataverse
      - https://github.com/estuary/connectors/tree/main/source-dynamics-365-finance-and-operations
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: observed
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        status: none
      name: Gong
      slug: gong
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-gong
      - https://github.com/estuary/connectors/tree/main/source-gong
      status: profiled
      tags:
      - Analytics
      - Conversations
      - Revenue Intelligence
      - Sales
      tier: observed
      url: /providers/gong/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Airbyte
      - Fivetran
      - dlt (dltHub)
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-pipedrive
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/pipedrive
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: observed
      url: /providers/pipedrive/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Airbyte
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho CRM
      slug: zoho
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-zoho-crm
      status: profiled
      tags:
      - Analytics
      - CRM
      - Collaboration
      - Customer Service
      tier: observed
      url: /providers/zoho/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: Amazon Kinesis
      slug: kinesis
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-kinesis
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/kinesis
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Apache Flink
      - Big Data
      tier: observed
      url: /providers/kinesis/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-kafka
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-kafka-bundle
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
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-amazon-sqs
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/sqs
      - https://github.com/estuary/connectors/tree/main/source-sqs
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pubsub
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/pubsub
      - https://github.com/estuary/connectors/tree/main/materialize-google-pubsub
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Apache NiFi
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 87.2
      mcp:
        source: https://github.com/confluentinc/mcp-confluent
        status: verified
      name: Confluent
      slug: confluent
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-confluent-platform-bundle
      status: profiled
      tags:
      - Apache Kafka
      - Data Streaming
      - Event Streaming
      - Stream Processing
      tier: observed
      url: /providers/confluent/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Apache NiFi
      - Estuary Flow
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/sns
      - https://github.com/estuary/connectors/tree/main/materialize-sns
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Estuary Flow
      band: exemplar
      in_catalog: true
      kin_score: 75.4
      mcp:
        status: unknown
      name: Amazon EventBridge
      slug: amazon-eventbridge
      sources:
      - https://github.com/estuary/connectors/tree/main/materialize-eventbridge
      status: profiled
      tags:
      - Amazon Web Services
      - Event
      - Event Bus
      - Event-Driven
      tier: observed
      url: /providers/amazon-eventbridge/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Apache NiFi
      band: exemplar
      in_catalog: true
      kin_score: 68.4
      mcp:
        source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-event-hubs
        status: verified
      name: Azure Event Hubs
      slug: microsoft-azure-event-hubs
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/eventhub
      status: profiled
      tags:
      - Big Data
      - Event Streaming
      - IoT
      - Message Ingestion
      tier: observed
      url: /providers/microsoft-azure-event-hubs/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        source: https://docs.redpanda.com/agentic-data-plane/connect/mcp-overview/
        status: verified
      name: Redpanda
      slug: redpanda
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-redpanda
      status: profiled
      tags:
      - Event Streaming
      - Kafka
      - Real-Time
      - Streaming
      tier: observed
      url: /providers/redpanda/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Apache Pulsar
      slug: apache-pulsar
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pulsar
      status: profiled
      tags:
      - Cloud-Native
      - Messaging
      - Multi-Tenant
      - Pub/Sub
      tier: observed
      url: /providers/apache-pulsar/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: RabbitMQ
      slug: rabbitmq
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-rabbitmq
      status: profiled
      tags:
      - AMQP
      - Distributed Systems
      - Queues
      - RabbitMQ
      tier: observed
      url: /providers/rabbitmq/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-analytics-data-api
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/google_analytics
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - Hightouch
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-mixpanel
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Airbyte
      - Fivetran
      - Hightouch
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-amplitude
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-posthog
      - https://github.com/estuary/connectors/tree/main/source-posthog
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/matomo
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/estuary/connectors/tree/main/source-pendo
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: Keen
      slug: keen
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-keen
      status: profiled
      tags:
      - Analytics
      - Custom Events
      - Data Collection
      - Embedded Analytics
      tier: observed
      url: /providers/keen/
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
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-jira
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/jira
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-asana
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/asana_dlt
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: observed
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-notion
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/notion
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-linear
      - https://github.com/estuary/connectors/tree/main/source-linear
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-monday
      - https://github.com/estuary/connectors/tree/main/source-monday
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: observed
      url: /providers/monday-com/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Airbyte
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Confluence
      slug: confluence
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-confluence
      status: profiled
      tags:
      - Collaboration
      - Content Management
      - Documentation
      - Knowledge Base
      tier: observed
      url: /providers/confluence/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-google-drive
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/drive
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft SharePoint
      slug: sharepoint
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-sharepoint
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/sharepoint
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: observed
      url: /providers/sharepoint/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Airbyte
      - Apache NiFi
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-box
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-box-bundle
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: observed
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-dropbox-bundle
      - https://github.com/estuary/connectors/tree/main/source-dropbox
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Airbyte
      - Estuary Flow
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-onedrive
      - https://github.com/estuary/connectors/tree/main/source-onedrive
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-s3
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-aws-bundle/nifi-aws-processors/src/main/java/org/apache/nifi/processors/aws/s3
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-gcs
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gcp-bundle/nifi-gcp-processors/src/main/java/org/apache/nifi/processors/gcp/storage
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-azure-blob-storage
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/storage
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Airbyte
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare R2
      slug: cloudflare
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-r2
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Apache NiFi
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        status: none
      name: Azure Data Lake Storage
      slug: microsoft-azure-data-lake
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-azure-bundle/nifi-azure-processors/src/main/java/org/apache/nifi/processors/azure/storage
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Data Lake
      - Hierarchical Storage
      tier: observed
      url: /providers/microsoft-azure-data-lake/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-airtable
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-airtable-bundle
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: observed
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-google-sheets
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/google_sheets
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Airbyte
      - Estuary Flow
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        source: https://github.com/smartsheet-platform/smar-mcp
        status: verified
      name: Smartsheet
      slug: smartsheet
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-smartsheets
      - https://github.com/estuary/connectors/tree/main/source-smartsheet
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: observed
      url: /providers/smartsheet/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Airbyte
      - Estuary Flow
      band: strong
      in_catalog: true
      kin_score: 60.1
      mcp:
        source: https://github.com/pinecone-io/pinecone-mcp
        status: verified
      name: Pinecone
      slug: pinecone
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pinecone
      - https://github.com/estuary/connectors/tree/main/materialize-pinecone
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - RAG
      - Vector Search
      tier: observed
      url: /providers/pinecone/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Airbyte
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/zilliztech/mcp-server-milvus
        status: verified
      name: Milvus
      slug: milvus
      sources:
      - https://fivetran.com/docs/destinations
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-milvus
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Open Source
      - Vector Search
      tier: observed
      url: /providers/milvus/
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Airbyte
      band: strong
      in_catalog: true
      kin_score: 59.2
      mcp:
        source: https://github.com/chroma-core/chroma-mcp
        status: verified
      name: Chroma
      slug: chroma
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-chroma
      status: profiled
      tags:
      - AI-native
      - Apache 2.0
      - Artificial Intelligence
      - Cloud
      tier: observed
      url: /providers/chroma/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 53.4
      mcp:
        source: https://github.com/vectara/vectara-mcp
        status: verified
      name: Vectara
      slug: vectara
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-vectara
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Corpora
      - Embeddings
      tier: observed
      url: /providers/vectara/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://github.com/weaviate/mcp-server-weaviate
        status: verified
      name: Weaviate
      slug: weaviate
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-weaviate
      status: profiled
      tags:
      - Artificial Intelligence
      - Machine Learning
      - Semantic Search
      - Vector Search
      tier: observed
      url: /providers/weaviate/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        source: https://github.com/deepset-ai/deepset-mcp-server
        status: verified
      name: deepset
      slug: deepset
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-deepset
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Natural Language Processing
      - Open Source
      tier: observed
      url: /providers/deepset/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 38.2
      mcp:
        source: https://github.com/ragieai/ragie-mcp-server
        status: verified
      name: Ragie
      slug: ragie-ai
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-ragie
      status: profiled
      tags:
      - Artificial Intelligence
      - RAG
      - Retrieval
      - Vector Search
      tier: observed
      url: /providers/ragie-ai/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/qdrant/mcp-server-qdrant
        status: verified
      name: Qdrant
      slug: qdrant
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-qdrant
      status: profiled
      tags:
      - Artificial Intelligence
      - Database
      - Vector Search
      tier: observed
      url: /providers/qdrant/
    - agent_band: human-only
      agent_readiness: 1.6
      apps:
      - Airbyte
      band: emerging
      in_catalog: true
      kin_score: 16.7
      mcp:
        status: unknown
      name: pgvector
      slug: pgvector
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-pgvector
      status: profiled
      tags:
      - Artificial Intelligence
      - Database
      - Open Source
      - Vector Search
      tier: observed
      url: /providers/pgvector/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 59.9
      mcp:
        source: https://www.chargebee.com/docs/billing/2.0/ai-in-chargebee/chargebee-mcp
        status: verified
      name: Chargebee
      slug: chargebee
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-chargebee
      - https://github.com/estuary/connectors/tree/main/source-chargebee-native
      status: profiled
      tags:
      - Billing
      - Recurring Billing
      - Revenue
      - Subscription
      tier: observed
      url: /providers/chargebee/
    - agent_band: agent-native
      agent_readiness: 57.0
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 36.1
      mcp:
        source: https://docs.zuora.com/en/zuora-platform/system-management/zuora-ai/zuora-mcp-server
        status: verified
      name: Zuora
      slug: zuora
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-zuora
      - https://github.com/estuary/connectors/tree/main/source-zuora
      status: profiled
      tags:
      - Billing
      - Finance
      - Payments
      - Subscription
      tier: observed
      url: /providers/zuora/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=rechargeapps
        status: verified
      name: Recharge
      slug: recharge-payments
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-recharge
      - https://github.com/estuary/connectors/tree/main/source-recharge
      status: profiled
      tags:
      - E-Commerce
      - Payments
      - Recurring Billing
      - Subscription
      tier: observed
      url: /providers/recharge-payments/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-quickbooks
      - https://github.com/estuary/connectors/tree/main/source-quickbooks
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: observed
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/estuary/connectors/tree/main/source-sage-intacct
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: observed
      url: /providers/sage-intacct/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Airbyte
      - Fivetran
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Oracle NetSuite
      slug: netsuite
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-netsuite
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: observed
      url: /providers/netsuite/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Airbyte
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-xero
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: observed
      url: /providers/xero/
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        status: none
      name: Greenhouse
      slug: greenhouse
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-greenhouse
      - https://github.com/estuary/connectors/tree/main/source-greenhouse-native
      status: profiled
      tags:
      - Applicant Tracking
      - Greenhouse
      - Human Resources
      - Recruiting
      tier: observed
      url: /providers/greenhouse/
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        status: none
      name: Ashby
      slug: ashby
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-ashby
      - https://github.com/estuary/connectors/tree/main/source-ashby
      status: profiled
      tags:
      - Analytics
      - Applicant Tracking
      - Human Resources
      - Recruiting
      tier: observed
      url: /providers/ashby/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Airbyte
      - dlt (dltHub)
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://mcp.workable.com/mcp
        status: verified
      name: Workable
      slug: workable
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-workable
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/workable
      status: profiled
      tags:
      - Applicant Tracking
      - Human Resources
      - Recruiting
      - Sourcing
      tier: observed
      url: /providers/workable/
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Airbyte
      - Apache NiFi
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-github
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-github-bundle
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Airbyte
      - Apache NiFi
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-gitlab
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-gitlab-bundle
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-shopify
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-shopify-bundle
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: observed
      url: /providers/shopify/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Airbyte
      - Fivetran
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: Adobe Commerce (Magento)
      slug: adobe-commerce
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-adobe-commerce-magento
      status: profiled
      tags:
      - Adobe
      - Commerce
      - E-Commerce
      - Magento
      tier: observed
      url: /providers/adobe-commerce/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-stripe
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/stripe_analytics
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 44.7
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-braintree
      - https://github.com/estuary/connectors/tree/main/source-braintree-native
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        source: https://apidocs.hibob.com/docs/hibob-mcp-server
        status: verified
      name: HiBob
      slug: bob
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-hibob
      - https://github.com/estuary/connectors/tree/main/source-hibob
      status: profiled
      tags:
      - Employee Management
      - HRIS
      - Human Resources
      - Time Off
      tier: observed
      url: /providers/bob/
    - agent_band: agent-ready
      agent_readiness: 41.0
      apps:
      - Fivetran
      - dlt (dltHub)
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Personio
      slug: personio
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/personio
      status: profiled
      tags:
      - Applicant Tracking
      - HRIS
      - Human Resources
      - Recruiting
      tier: observed
      url: /providers/personio/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Apache NiFi
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: Workday
      slug: workday
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-workday-bundle
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: observed
      url: /providers/workday/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-elasticsearch
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-elasticsearch-bundle
      - https://github.com/estuary/connectors/tree/main/materialize-elasticsearch
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Airbyte
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        source: https://github.com/meilisearch/meilisearch-mcp
        status: verified
      name: Meilisearch
      slug: meilisearch
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-meilisearch
      status: profiled
      tags:
      - AI Search
      - Full-Text Search
      - Hybrid Search
      - Open Source
      tier: observed
      url: /providers/meilisearch/
    - agent_band: agent-ready
      agent_readiness: 47.3
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 39.2
      mcp:
        source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
        status: verified
      name: Typesense
      slug: typesense
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-typesense
      status: profiled
      tags:
      - Full-Text Search
      - Open Source
      - Search Engines
      - Typo Tolerance
      tier: observed
      url: /providers/typesense/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.20
      key: AE-140.10.20
      name: Headless & Composable Commerce
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        source: https://github.com/commercetools/mcp-essentials
        status: verified
      name: commercetools
      slug: commercetools
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-commercetools
      - https://github.com/estuary/connectors/tree/main/source-commercetools
      status: profiled
      tags:
      - Commerce
      - Composable Commerce
      - E-Commerce
      - GraphQL
      tier: observed
      url: /providers/commercetools/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 49.9
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        source: https://help.incident.io/
        status: documented
      name: incident.io
      slug: incident-io
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-incident-io
      - https://github.com/estuary/connectors/tree/main/source-incident-io
      status: profiled
      tags:
      - AIOps
      - Incident Management
      - Incident Response
      - Monitoring
      tier: observed
      url: /providers/incident-io/
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
      - Airbyte
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-segment
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Estuary Flow
      - Fivetran
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Google Play Console
      slug: google-play
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/estuary/connectors/tree/main/source-google-play
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: Turbo EA
      id: BC-4270.80
      key: webhook-event-subscription-management
      name: Webhook & Event Subscription Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Airbyte
      band: thin
      in_catalog: true
      kin_score: 34.6
      mcp:
        status: unchecked
      name: GlassFlow
      slug: glassflow
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-glassflow
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Data Infrastructure
      - Observability
      tier: observed
      url: /providers/glassflow/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      - Hightouch
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/Iterable/mcp-server
        status: verified
      name: Iterable
      slug: iterable
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-iterable
      status: profiled
      tags:
      - Cross-Channel Messaging
      - Customer Engagement
      - Email
      - Marketing Automation
      tier: observed
      url: /providers/iterable/
    - agent_band: agent-ready
      agent_readiness: 56.4
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 81.3
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-brevo
      - https://github.com/estuary/connectors/tree/main/source-brevo
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-klaviyo
      - https://github.com/estuary/connectors/tree/main/source-klaviyo
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: observed
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-mailchimp
      - https://github.com/estuary/connectors/tree/main/source-mailchimp-native
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Airbyte
      - Fivetran
      - Hightouch
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-braze
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: observed
      url: /providers/braze/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Airbyte
      - Fivetran
      - Hightouch
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://docs.hightouch.com/destinations/overview
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-marketo
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: observed
      url: /providers/marketo/
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Airbyte
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-sendgrid
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 70.1
      apps:
      - Airbyte
      band: exemplar
      in_catalog: true
      kin_score: 85.9
      mcp:
        source: https://github.com/customerio/claude-plugin
        status: verified
      name: Customer.io
      slug: customer-io
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/destination-customer-io
      status: profiled
      tags:
      - Behavioral Data
      - Broadcast
      - CDP
      - Campaigns
      tier: observed
      url: /providers/customer-io/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-sentry
      - https://github.com/estuary/connectors/tree/main/source-sentry
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-datadog
      - https://github.com/estuary/connectors/tree/main/source-datadog
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Apache NiFi
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-splunk-bundle
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: observed
      url: /providers/splunk/
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
      - Airbyte
      - Apache NiFi
      - Estuary Flow
      - dlt (dltHub)
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-slack
      - https://github.com/apache/nifi/tree/main/nifi-extension-bundles/nifi-slack-bundle
      - https://github.com/dlt-hub/verified-sources/tree/master/sources/slack
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Airbyte
      - Fivetran
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-microsoft-teams
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Airbyte
      - Estuary Flow
      - Fivetran
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://fivetran.com/docs/connectors
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-okta
      - https://github.com/estuary/connectors/tree/main/source-okta
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Airbyte
      - Estuary Flow
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/airbytehq/airbyte/tree/master/airbyte-integrations/connectors/source-twilio
      - https://github.com/estuary/connectors/tree/main/source-twilio
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  layer: common
summary:
  coverage_pct: 99.4
  declared_only: 2
  distinct_providers: 162
  in_catalog: 161
  mcp:
    documented: 3
    none: 47
    unchecked: 7
    verified: 101
  mcp_verified: 101
  mean_kin_score: 56.2
  observed: 160
  queued: 1
  reference_apps: 6
title: 'Data Integration & ETL: application blueprint'
---
