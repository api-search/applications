---
app: Retool
app_slug: retool
app_url: https://retool.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Amazon Athena
  - Amazon Redshift
  - Databricks
  - Google BigQuery
  - Presto
  - Snowflake
  - Vertica
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - CircleCI
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Close
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
  - Front
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Google Search Console
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: domain
  name: Feature Flag Management
  providers:
  - LaunchDarkly
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610
  key: information-data-management
  layer: domain
  name: Information & Data Management
  providers:
  - BigID
  url: /capabilities/information-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Kafka
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  - Apache Cassandra
  - Apache CouchDB
  - Azure Cosmos DB
  - Firebase
  - Google AlloyDB
  - Google Cloud Datastore
  - Microsoft SQL Server
  - MongoDB
  - MySQL
  - Oracle Database
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
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  - Jira
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elastic
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: domain
  name: Serverless Functions
  providers:
  - AWS Lambda
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  - Notion
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - OneSignal
  url: /capabilities/push-notifications/
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
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
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
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: low-code-internal-tools
  name: Low-code & Internal Tools
  url: /applications/low-code-internal-tools/
counts:
  declared: 56
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://retool.com/integrations
integrations:
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
    agent_readiness: 35.8
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-athena
    status: profiled
    tags: &id002
    - Amazon Athena
    - Analytics
    - SQL
    - Serverless
    url: /providers/amazon-athena/
  layer: domain
  name: Amazon Athena
  provider: amazon-athena
  says: lists Amazon Athena as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: lists Amazon Bedrock as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 80.9
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
  says: lists Amazon DynamoDB as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 63.6
    mcp: &id007
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id008
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
  layer: domain
  name: Amazon Redshift
  provider: amazon-redshift
  says: lists Amazon Redshift as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id009
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: lists Amazon S3 as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id011
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id012
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: lists Anthropic as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id013
      status: none
    slug: cassandra
    status: profiled
    tags: &id014
    - Apache
    - Big Data
    - Database
    - Distributed
    url: /providers/cassandra/
  layer: domain
  name: Apache Cassandra
  provider: cassandra
  says: lists Apache Cassandra as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 33.6
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id015
      status: none
    slug: apache-couchdb
    status: profiled
    tags: &id016
    - Apache
    - Database
    - Document Store
    - JSON
    url: /providers/apache-couchdb/
  layer: domain
  name: Apache CouchDB
  provider: apache-couchdb
  says: lists Apache CouchDB as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id017
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id018
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://retool.com/integrations
  tier: declared
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
  says: lists AWS Lambda as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 19.0
    band: developing
    in_catalog: true
    kin_score: 40.9
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
  says: lists Azure Cosmos DB as an integration
  source: https://retool.com/integrations
  tier: declared
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
  says: lists Azure OpenAI as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610
    key: information-data-management
    name: Information & Data Management
    url: /capabilities/information-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id025
      status: unknown
    slug: bigid
    status: profiled
    tags: &id026
    - DLP
    - DSPM
    - Data Security
    - Privacy
    url: /providers/bigid/
  layer: domain
  name: BigID
  provider: bigid
  says: lists BigID as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 56.1
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id027
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id028
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
  layer: domain
  name: CircleCI
  provider: circleci
  says: lists CircleCI as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id029
      source: https://developer.close.com/mcp
      status: verified
    slug: close
    status: profiled
    tags: &id030
    - CRM
    - Calling
    - Inside Sales
    - Sales Engagement
    url: /providers/close/
  layer: domain
  name: Close
  provider: close
  says: lists Close as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id031
      status: none
    slug: cohere
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: agent
  name: Cohere
  provider: cohere
  says: lists Cohere as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 58.9
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id033
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id034
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
  layer: domain
  name: Databricks
  provider: databricks
  says: lists Databricks as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id035
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id036
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://retool.com/integrations
  tier: declared
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
  layer: domain
  name: Elastic
  provider: elastic
  says: lists Elastic as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id039
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id040
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: domain
  name: Firebase
  provider: firebase
  says: lists Firebase as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id041
      source: https://dev.frontapp.com/docs/mcp
      status: documented
    slug: front
    status: profiled
    tags: &id042
    - Customer Operations
    - Customer Service
    - Email
    - Inbox
    url: /providers/front/
  layer: domain
  name: Front
  provider: front
  says: lists Front as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id043
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id044
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id045
      status: unchecked
    slug: google-alloydb
    status: queued for profiling
    tags: &id046 []
    url: null
  layer: domain
  name: Google AlloyDB
  provider: google-alloydb
  says: lists Google AlloyDB as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id047
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id048
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id049
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id050
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id051
      status: none
    slug: google-cloud-datastore
    status: profiled
    tags: &id052
    - Database
    - Document Database
    - Google Cloud
    - NoSQL
    url: /providers/google-cloud-datastore/
  layer: domain
  name: Google Cloud Datastore
  provider: google-cloud-datastore
  says: lists Google Cloud Datastore as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id053
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id054
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: lists Google Cloud Storage as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id055
      status: none
    slug: google-gemini
    status: profiled
    tags: &id056
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: lists Google Gemini as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id057
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id058
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: lists Google Maps Platform as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id059
      status: none
    slug: google-search-console
    status: profiled
    tags: &id060
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
  layer: domain
  name: Google Search Console
  provider: google-search-console
  says: lists Google Search Console as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id061
      status: none
    slug: google-sheets
    status: profiled
    tags: &id062
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id063
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id064
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id065
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id066
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id067
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id068
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: domain
  name: Kafka
  provider: apache-kafka
  says: lists Kafka as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.6
    band: exemplar
    in_catalog: true
    kin_score: 85.5
    mcp: &id069
      source: https://launchdarkly.com/docs/home/getting-started/mcp
      status: verified
    slug: launchdarkly
    status: profiled
    tags: &id070
    - Experimentation
    - Feature Flags
    - Feature Management
    - Observability
    url: /providers/launchdarkly/
  layer: domain
  name: LaunchDarkly
  provider: launchdarkly
  says: lists LaunchDarkly as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id071
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id072
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: domain
  name: Microsoft SQL Server
  provider: microsoft-sql-server
  says: lists Microsoft SQL Server as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id073
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id074
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id075
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id076
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: domain
  name: MongoDB
  provider: mongodb
  says: lists MongoDB as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id077
      status: none
    slug: mysql
    status: profiled
    tags: &id078
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
  layer: domain
  name: MySQL
  provider: mysql
  says: lists MySQL as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id079
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id080
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.3
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id081
      source: https://github.com/OneSignal/onesignal-ai-skills
      status: documented
    slug: onesignal
    status: profiled
    tags: &id082
    - Email
    - Notification
    - Push
    - SMS
    url: /providers/onesignal/
  layer: common
  name: OneSignal
  provider: onesignal
  says: lists OneSignal as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id083
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id084
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id085
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle-database
    status: profiled
    tags: &id086
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle-database/
  layer: domain
  name: Oracle Database
  provider: oracle-database
  says: lists Oracle Database as an integration
  source: https://retool.com/integrations
  tier: declared
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
    kin_score: 12.2
    mcp: &id087
      status: none
    slug: postgresql
    status: profiled
    tags: &id088
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: domain
  name: PostgreSQL
  provider: postgresql
  says: lists PostgreSQL as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id089
      status: unchecked
    slug: prestodb
    status: queued for profiling
    tags: &id090 []
    url: null
  layer: domain
  name: Presto
  provider: prestodb
  says: lists Presto as an integration
  source: https://retool.com/integrations
  tier: declared
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
    mcp: &id091
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id092
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: domain
  name: Redis
  provider: redis
  says: lists Redis as an integration
  source: https://retool.com/integrations
  tier: declared
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
    kin_score: 9.1
    mcp: &id093
      status: none
    slug: rethinkdb
    status: profiled
    tags: &id094
    - Database
    - Document Database
    - NoSQL
    - Real-Time
    url: /providers/rethinkdb/
  layer: domain
  name: RethinkDB
  provider: rethinkdb
  says: lists RethinkDB as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id095
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id096
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 26.4
    band: developing
    in_catalog: true
    kin_score: 45.2
    mcp: &id097
      status: none
    slug: sap-hana
    status: profiled
    tags: &id098
    - Analytics
    - Cloud
    - Database
    - Enterprise
    url: /providers/sap-hana/
  layer: domain
  name: SAP HANA
  provider: sap-hana
  says: lists SAP HANA as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id099
      status: none
    slug: sendgrid
    status: profiled
    tags: &id100
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: lists SendGrid as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id101
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id102
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id103
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id104
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id105
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id106
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id107
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id108
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://retool.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id109
      status: none
    slug: vertica
    status: profiled
    tags: &id110
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
  layer: domain
  name: Vertica
  provider: vertica
  says: lists Vertica as an integration
  source: https://retool.com/integrations
  tier: declared
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
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id111
      status: none
    slug: zendesk
    status: profiled
    tags: &id112
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://retool.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/low-code-internal-tools/retool/
providers:
- agent_band: agent-ready
  agent_readiness: 35.8
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id001
  name: Amazon Athena
  slug: amazon-athena
  status: profiled
  tags: *id002
  url: /providers/amazon-athena/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id003
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
- agent_band: agent-native
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 80.9
  mcp: *id005
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id006
  url: /providers/amazon-dynamodb/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 63.6
  mcp: *id007
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id008
  url: /providers/amazon-redshift/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id009
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id010
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id011
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id012
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id013
  name: Apache Cassandra
  slug: cassandra
  status: profiled
  tags: *id014
  url: /providers/cassandra/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id015
  name: Apache CouchDB
  slug: apache-couchdb
  status: profiled
  tags: *id016
  url: /providers/apache-couchdb/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id017
  name: Asana
  slug: asana
  status: profiled
  tags: *id018
  url: /providers/asana/
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
  agent_readiness: 19.0
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id021
  name: Azure Cosmos DB
  slug: azure-cosmos-db
  status: profiled
  tags: *id022
  url: /providers/azure-cosmos-db/
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
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id025
  name: BigID
  slug: bigid
  status: profiled
  tags: *id026
  url: /providers/bigid/
- agent_band: agent-ready
  agent_readiness: 56.1
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id027
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id028
  url: /providers/circleci/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id029
  name: Close
  slug: close
  status: profiled
  tags: *id030
  url: /providers/close/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id031
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id032
  url: /providers/cohere/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id033
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id034
  url: /providers/databricks/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id035
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id036
  url: /providers/datadog/
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
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id039
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id040
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id041
  name: Front
  slug: front
  status: profiled
  tags: *id042
  url: /providers/front/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id043
  name: GitHub
  slug: github
  status: profiled
  tags: *id044
  url: /providers/github/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id045
  name: Google AlloyDB
  slug: google-alloydb
  status: queued for profiling
  tags: *id046
  url: null
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id047
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id048
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id049
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id050
  url: /providers/google-bigquery/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id051
  name: Google Cloud Datastore
  slug: google-cloud-datastore
  status: profiled
  tags: *id052
  url: /providers/google-cloud-datastore/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id053
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id054
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id055
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id056
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id057
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id058
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id059
  name: Google Search Console
  slug: google-search-console
  status: profiled
  tags: *id060
  url: /providers/google-search-console/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id061
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id062
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id063
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id064
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id065
  name: Jira
  slug: jira
  status: profiled
  tags: *id066
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id067
  name: Kafka
  slug: apache-kafka
  status: profiled
  tags: *id068
  url: /providers/apache-kafka/
- agent_band: agent-ready
  agent_readiness: 60.6
  band: exemplar
  in_catalog: true
  kin_score: 85.5
  mcp: *id069
  name: LaunchDarkly
  slug: launchdarkly
  status: profiled
  tags: *id070
  url: /providers/launchdarkly/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id071
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id072
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id073
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id074
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 56.0
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id075
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id076
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id077
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id078
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id079
  name: Notion
  slug: notion
  status: profiled
  tags: *id080
  url: /providers/notion/
- agent_band: agent-native
  agent_readiness: 71.3
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id081
  name: OneSignal
  slug: onesignal
  status: profiled
  tags: *id082
  url: /providers/onesignal/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id083
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id084
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id085
  name: Oracle Database
  slug: oracle-database
  status: profiled
  tags: *id086
  url: /providers/oracle-database/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id087
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id088
  url: /providers/postgresql/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id089
  name: Presto
  slug: prestodb
  status: queued for profiling
  tags: *id090
  url: null
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id091
  name: Redis
  slug: redis
  status: profiled
  tags: *id092
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id093
  name: RethinkDB
  slug: rethinkdb
  status: profiled
  tags: *id094
  url: /providers/rethinkdb/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id095
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id096
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: developing
  in_catalog: true
  kin_score: 45.2
  mcp: *id097
  name: SAP HANA
  slug: sap-hana
  status: profiled
  tags: *id098
  url: /providers/sap-hana/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id099
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id100
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id101
  name: Slack
  slug: slack
  status: profiled
  tags: *id102
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id103
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id104
  url: /providers/snowflake/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id105
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id106
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id107
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id108
  url: /providers/twilio/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id109
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id110
  url: /providers/vertica/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id111
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id112
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
- name: ToolJet
  rows: 48
  url: /applications/low-code-internal-tools/tooljet/
sitemap: true
title: 'Retool: Low-code & Internal Tools reference app'
---
