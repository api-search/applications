---
app: Appsmith
app_slug: appsmith
app_url: https://github.com/appsmithorg/appsmith
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Amazon Redshift
  - Databricks
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  - ArangoDB
  - Firestore
  - Microsoft SQL Server
  - MongoDB
  - MySQL
  - Oracle Database
  - PostgreSQL
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  - Microsoft OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - BetterBugs
  - Grafana Faro
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Mixpanel
  - Smartlook
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google AI (googleAiPlugin)
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: low-code-internal-tools
  name: Low-code & Internal Tools
  url: /applications/low-code-internal-tools/
counts:
  declared: 0
  observed: 29
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
- route: source code
  url: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
integrations:
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
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
  layer: domain
  name: Amazon DynamoDB
  provider: amazon-dynamodb
  says: ships the Amazon DynamoDB SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 44.5
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id003
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id004
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
  layer: domain
  name: Amazon Redshift
  provider: amazon-redshift
  says: ships the Amazon Redshift SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id009
      status: none
    slug: arangodb
    status: profiled
    tags: &id010
    - Company
    - Database
    - Graph Database
    - Multi-Model Database
    url: /providers/arangodb/
  layer: domain
  name: ArangoDB
  provider: arangodb
  says: ships the ArangoDB SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id011
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id012
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
  layer: domain
  name: AWS Lambda
  provider: aws-lambda
  says: ships the AWS Lambda SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 2.8
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id013
      source: https://github.com/betterbugs/mcp
      status: verified
    slug: betterbugs
    status: profiled
    tags: &id014
    - Bug Tracking
    - Collaboration
    - Company
    - Software-as-a-Service
    url: /providers/betterbugs/
  layer: common
  name: BetterBugs
  provider: betterbugs
  says: ships the BetterBugs SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    mcp: &id015
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id016
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
  layer: domain
  name: Databricks
  provider: databricks
  says: ships the Databricks SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id017
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id018
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elastic
  provider: elastic
  says: ships the Elastic SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id020
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: domain
  name: Firestore
  provider: firebase
  says: ships the Firestore SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id021
      status: none
    slug: google-gemini
    status: profiled
    tags: &id022
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google AI (googleAiPlugin)
  provider: google-gemini
  says: ships the Google AI (googleAiPlugin) SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id023
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id024
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    mcp: &id025
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id026
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id027
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id028
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    mcp: &id029
      status: none
    slug: google-sheets
    status: profiled
    tags: &id030
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 27.6
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id031
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id032
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: common
  name: Grafana Faro
  provider: grafana-com
  says: ships the Grafana Faro SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id033
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id034
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: ships the Microsoft OneDrive SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    mcp: &id035
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id036
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: domain
  name: Microsoft SQL Server
  provider: microsoft-sql-server
  says: ships the Microsoft SQL Server SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id037
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id038
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    mcp: &id039
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id040
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: domain
  name: MongoDB
  provider: mongodb
  says: ships the MongoDB SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id041
      status: none
    slug: mysql
    status: profiled
    tags: &id042
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
  layer: domain
  name: MySQL
  provider: mysql
  says: ships the MySQL SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id043
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id045
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle-database
    status: profiled
    tags: &id046
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle-database/
  layer: domain
  name: Oracle Database
  provider: oracle-database
  says: ships the Oracle Database SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id047
      status: none
    slug: postgresql
    status: profiled
    tags: &id048
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: domain
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id049
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id050
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: domain
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    mcp: &id051
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id052
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    agent_band: agent-aware
    agent_readiness: 19.1
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id053
      source: https://help.smartlook.com/mcp
      status: verified
    slug: smartlook
    status: profiled
    tags: &id054
    - Funnels
    - Heatmaps
    - Product Analytics
    - Session Recording
    url: /providers/smartlook/
  layer: common
  name: Smartlook
  provider: smartlook
  says: ships the Smartlook SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
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
    mcp: &id055
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id056
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: ships the Snowflake SDK or integration code
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id057
      status: none
    slug: segment
    status: profiled
    tags: &id058
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/low-code-internal-tools/appsmith/
providers:
- agent_band: agent-native
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id001
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id002
  url: /providers/amazon-dynamodb/
- agent_band: agent-native
  agent_readiness: 44.5
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id003
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id004
  url: /providers/amazon-redshift/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id009
  name: ArangoDB
  slug: arangodb
  status: profiled
  tags: *id010
  url: /providers/arangodb/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 74.9
  mcp: *id011
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id012
  url: /providers/aws-lambda/
- agent_band: human-only
  agent_readiness: 2.8
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id013
  name: BetterBugs
  slug: betterbugs
  status: profiled
  tags: *id014
  url: /providers/betterbugs/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id015
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id016
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id017
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id018
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id019
  name: Firestore
  slug: google-firebase
  status: profiled
  tags: *id020
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id021
  name: Google AI (googleAiPlugin)
  slug: google-gemini
  status: profiled
  tags: *id022
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id023
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id024
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id025
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id026
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id027
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id028
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id029
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id030
  url: /providers/google-sheets/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id031
  name: Grafana Faro
  slug: grafana-com
  status: profiled
  tags: *id032
  url: /providers/grafana-com/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id033
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id034
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id035
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id036
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id037
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id038
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id039
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id040
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id041
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id042
  url: /providers/mysql/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id043
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id044
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id045
  name: Oracle Database
  slug: oracle-database
  status: profiled
  tags: *id046
  url: /providers/oracle-database/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id047
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id048
  url: /providers/postgresql/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id049
  name: Redis
  slug: redis
  status: profiled
  tags: *id050
  url: /providers/redis/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id051
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id052
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 19.1
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id053
  name: Smartlook
  slug: smartlook
  status: profiled
  tags: *id054
  url: /providers/smartlook/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id055
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id056
  url: /providers/snowflake/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id057
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id058
  url: /providers/segment/
siblings:
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
- name: ToolJet
  rows: 48
  url: /applications/low-code-internal-tools/tooljet/
sitemap: true
title: 'Appsmith: Low-code & Internal Tools reference app'
---
