---
app: ToolJet
app_slug: tooljet
app_url: https://github.com/ToolJet/ToolJet
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Amazon Athena
  - ClickHouse
  - Databricks
  - Google BigQuery
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
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
- attribution: Turbo EA
  id: BC-600.40.20
  key: BC-600.40.20
  layer: domain
  name: IT Job Scheduling and Batch Operations
  providers:
  - Temporal
  url: /capabilities/it-operations-management/
  via_parent: IT Operations Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  - Apache CouchDB
  - Appwrite
  - Azure Cosmos DB
  - Firestore
  - Google Cloud Spanner
  - IBM Db2
  - InfluxDB
  - MariaDB
  - Microsoft SQL Server
  - MongoDB
  - MySQL
  - OracleDB
  - PostgreSQL
  - Redis
  - RethinkDB
  - SAP HANA
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320.10
  key: sales-transaction-management
  layer: domain
  name: Sales Transaction Management
  providers:
  - WooCommerce
  url: /capabilities/sales-transaction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elastic
  - Typesense
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  - Baserow
  - Google Sheets
  - NocoDB
  - Notion
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - n8n
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps Platform
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  - MinIO
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Mailgun
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: low-code-internal-tools
  name: Low-code & Internal Tools
  url: /applications/low-code-internal-tools/
counts:
  declared: 0
  observed: 48
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ToolJet/ToolJet/blob/develop/frontend/package.json
- route: dependency manifest
  url: https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
- route: source code
  url: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-athena
    status: profiled
    tags: &id004
    - Amazon Athena
    - Analytics
    - SQL
    - Serverless
    url: /providers/amazon-athena/
  layer: domain
  name: Amazon Athena
  provider: amazon-athena
  says: ships the Amazon Athena SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
  layer: domain
  name: Amazon DynamoDB
  provider: amazon-dynamodb
  says: ships the Amazon DynamoDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id009
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id011
      status: none
    slug: apache-couchdb
    status: profiled
    tags: &id012
    - Apache
    - Database
    - Document Store
    - JSON
    url: /providers/apache-couchdb/
  layer: domain
  name: Apache CouchDB
  provider: apache-couchdb
  says: ships the Apache CouchDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 57.8
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id013
      source: https://github.com/appwrite/mcp
      status: verified
    slug: appwrite
    status: profiled
    tags: &id014
    - Application
    - Backend
    - Mobile
    - Open Source
    url: /providers/appwrite/
  layer: domain
  name: Appwrite
  provider: appwrite
  says: ships the Appwrite SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id016
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id017
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-cosmos-db
    status: profiled
    tags: &id018
    - Database
    - Document Database
    - NoSQL
    - Vector Search
    url: /providers/azure-cosmos-db/
  layer: domain
  name: Azure Cosmos DB
  provider: azure-cosmos-db
  says: ships the Azure Cosmos DB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.9
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id019
      source: https://baserow.io/user-docs/mcp-server
      status: verified
    slug: baserow
    status: profiled
    tags: &id020
    - Database
    - No-Code
    - Open Source
    - REST API
    url: /providers/baserow/
  layer: domain
  name: Baserow
  provider: baserow
  says: ships the Baserow SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 77.1
    mcp: &id021
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id022
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
  layer: domain
  name: ClickHouse
  provider: clickhouse
  says: ships the ClickHouse SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id023
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id024
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
  layer: domain
  name: Databricks
  provider: databricks
  says: ships the Databricks SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id025
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id026
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elastic
  provider: elastic
  says: ships the Elastic SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id027
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id028
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: domain
  name: Firestore
  provider: firebase
  says: ships the Firestore SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id029
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id030
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
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
    mcp: &id031
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id032
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: ships the Google BigQuery SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id033
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-spanner
    status: profiled
    tags: &id034
    - Database
    - Distributed
    - Google Cloud
    - Relational
    url: /providers/google-cloud-spanner/
  layer: domain
  name: Google Cloud Spanner
  provider: google-cloud-spanner
  says: ships the Google Cloud Spanner SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
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
    mcp: &id035
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id036
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id037
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id038
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/frontend/package.json
  tier: observed
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
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id039
      status: none
    slug: google-sheets
    status: profiled
    tags: &id040
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id041
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id042
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id043
      status: none
    slug: ibm-db2
    status: profiled
    tags: &id044
    - Cloud Database
    - Database
    - Relational Database
    - SQL
    url: /providers/ibm-db2/
  layer: domain
  name: IBM Db2
  provider: ibm-db2
  says: ships the IBM Db2 SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id045
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id046
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
  layer: domain
  name: InfluxDB
  provider: influxdata
  says: ships the InfluxDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id047
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id048
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id049
      status: unchecked
    slug: mariadb
    status: profiled
    tags: &id050
    - Cloud
    - Database
    - Enterprise
    - Open Source
    url: /providers/mariadb/
  layer: domain
  name: MariaDB
  provider: mariadb
  says: ships the MariaDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id051
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id052
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: domain
  name: Microsoft SQL Server
  provider: microsoft-sql-server
  says: ships the Microsoft SQL Server SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_band: agent-aware
    agent_readiness: 25.6
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id053
      source: https://github.com/minio/mcp-server-aistor
      status: verified
    slug: minio
    status: profiled
    tags: &id054
    - Cloud-Native
    - Object Storage
    - S3 Compatible
    - Storage
    url: /providers/minio/
  layer: common
  name: MinIO
  provider: minio
  says: ships the MinIO SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id055
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id056
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: domain
  name: MongoDB
  provider: mongodb
  says: ships the MongoDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id057
      status: none
    slug: mysql
    status: profiled
    tags: &id058
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
  layer: domain
  name: MySQL
  provider: mysql
  says: ships the MySQL SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id059
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id060
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
  layer: domain
  name: n8n
  provider: n8n
  says: ships the n8n SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id061
      source: https://nocodb.com/docs/product-docs/mcp
      status: verified
    slug: nocodb
    status: profiled
    tags: &id062
    - Airtable Alternative
    - Database
    - Low-Code
    - No-Code
    url: /providers/nocodb/
  layer: domain
  name: NocoDB
  provider: nocodb
  says: ships the NocoDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id063
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id064
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: ships the Notion SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 34.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id065
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle-database
    status: profiled
    tags: &id066
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle-database/
  layer: domain
  name: OracleDB
  provider: oracle-database
  says: ships the OracleDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id067
      status: none
    slug: postgresql
    status: profiled
    tags: &id068
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: domain
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id069
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id070
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/frontend/package.json
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
    mcp: &id071
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id072
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: domain
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id073
      status: none
    slug: rethinkdb
    status: profiled
    tags: &id074
    - Database
    - Document Database
    - NoSQL
    - Real-Time
    url: /providers/rethinkdb/
  layer: domain
  name: RethinkDB
  provider: rethinkdb
  says: ships the RethinkDB SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 44.8
    mcp: &id075
      status: none
    slug: sap-hana
    status: profiled
    tags: &id076
    - Analytics
    - Cloud
    - Database
    - Enterprise
    url: /providers/sap-hana/
  layer: domain
  name: SAP HANA
  provider: sap-hana
  says: ships the SAP HANA SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id077
      status: none
    slug: sendgrid
    status: profiled
    tags: &id078
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    kin_score: 80.7
    mcp: &id079
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id080
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id081
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id082
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id083
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id084
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: ships the Snowflake SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id085
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id086
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.9
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id087
      source: https://github.com/temporalio/temporal-mcp
      status: verified
    slug: temporal-io
    status: profiled
    tags: &id088
    - Durable Execution
    - Workflow Orchestration
    - Workflows
    - gRPC
    url: /providers/temporal-io/
  layer: domain
  name: Temporal
  provider: temporal-io
  says: ships the Temporal SDK or integration code
  source: https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id089
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id090
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    agent_band: agent-ready
    agent_readiness: 47.3
    band: thin
    in_catalog: true
    kin_score: 39.2
    mcp: &id091
      source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
      status: verified
    slug: typesense
    status: profiled
    tags: &id092
    - Full-Text Search
    - Open Source
    - Search Engines
    - Typo Tolerance
    url: /providers/typesense/
  layer: domain
  name: Typesense
  provider: typesense
  says: ships the Typesense SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id093
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id094
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: ships the WooCommerce SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
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
    mcp: &id095
      status: none
    slug: zendesk
    status: profiled
    tags: &id096
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: ships the Zendesk SDK or integration code
  source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/low-code-internal-tools/tooljet/
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
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id003
  name: Amazon Athena
  slug: amazon-athena
  status: profiled
  tags: *id004
  url: /providers/amazon-athena/
- agent_band: agent-native
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id005
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id006
  url: /providers/amazon-dynamodb/
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
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id009
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id010
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id011
  name: Apache CouchDB
  slug: apache-couchdb
  status: profiled
  tags: *id012
  url: /providers/apache-couchdb/
- agent_band: agent-ready
  agent_readiness: 57.8
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id013
  name: Appwrite
  slug: appwrite
  status: profiled
  tags: *id014
  url: /providers/appwrite/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id015
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 30.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id017
  name: Azure Cosmos DB
  slug: azure-cosmos-db
  status: profiled
  tags: *id018
  url: /providers/azure-cosmos-db/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id019
  name: Baserow
  slug: baserow
  status: profiled
  tags: *id020
  url: /providers/baserow/
- agent_band: agent-ready
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 77.1
  mcp: *id021
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id022
  url: /providers/clickhouse/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id023
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id024
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id025
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id026
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id027
  name: Firestore
  slug: google-firebase
  status: profiled
  tags: *id028
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id029
  name: GitHub
  slug: github
  status: profiled
  tags: *id030
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id031
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id032
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id033
  name: Google Cloud Spanner
  slug: google-cloud-spanner
  status: profiled
  tags: *id034
  url: /providers/google-cloud-spanner/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id035
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id036
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id037
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id038
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id039
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id040
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id041
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id042
  url: /providers/hubspot/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id043
  name: IBM Db2
  slug: ibm-db2
  status: profiled
  tags: *id044
  url: /providers/ibm-db2/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id045
  name: InfluxDB
  slug: influxdata
  status: profiled
  tags: *id046
  url: /providers/influxdata/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id047
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id048
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id049
  name: MariaDB
  slug: mariadb
  status: profiled
  tags: *id050
  url: /providers/mariadb/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id051
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id052
  url: /providers/microsoft-sql-server/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id053
  name: MinIO
  slug: minio
  status: profiled
  tags: *id054
  url: /providers/minio/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id055
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id056
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id057
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id058
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id059
  name: n8n
  slug: n8n
  status: profiled
  tags: *id060
  url: /providers/n8n/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id061
  name: NocoDB
  slug: nocodb
  status: profiled
  tags: *id062
  url: /providers/nocodb/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id063
  name: Notion
  slug: notion
  status: profiled
  tags: *id064
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id065
  name: OracleDB
  slug: oracle-database
  status: profiled
  tags: *id066
  url: /providers/oracle-database/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id067
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id068
  url: /providers/postgresql/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id069
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id070
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id071
  name: Redis
  slug: redis
  status: profiled
  tags: *id072
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id073
  name: RethinkDB
  slug: rethinkdb
  status: profiled
  tags: *id074
  url: /providers/rethinkdb/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 44.8
  mcp: *id075
  name: SAP HANA
  slug: sap-hana
  status: profiled
  tags: *id076
  url: /providers/sap-hana/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id077
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id078
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id079
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id080
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id081
  name: Slack
  slug: slack
  status: profiled
  tags: *id082
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id083
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id084
  url: /providers/snowflake/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id085
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id086
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 27.9
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id087
  name: Temporal
  slug: temporal-io
  status: profiled
  tags: *id088
  url: /providers/temporal-io/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id089
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id090
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 47.3
  band: thin
  in_catalog: true
  kin_score: 39.2
  mcp: *id091
  name: Typesense
  slug: typesense
  status: profiled
  tags: *id092
  url: /providers/typesense/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id093
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id094
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id095
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id096
  url: /providers/zendesk/
siblings:
- name: Appsmith
  rows: 29
  url: /applications/low-code-internal-tools/appsmith/
- name: Baserow
  rows: 12
  url: /applications/low-code-internal-tools/baserow/
- name: Budibase
  rows: 22
  url: /applications/low-code-internal-tools/budibase/
- name: NocoDB
  rows: 41
  url: /applications/low-code-internal-tools/nocodb/
- name: Retool
  rows: 56
  url: /applications/low-code-internal-tools/retool/
sitemap: true
title: 'ToolJet: Low-code & Internal Tools reference app'
---
