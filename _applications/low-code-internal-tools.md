---
access: understanding
agent_layer:
- app: NocoDB
  finding: ships its own MCP server (@modelcontextprotocol/server, @modelcontextprotocol/node) and bring-your-own LLM across 7 model providers via the AI SDK
  source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
  tier: observed
- app: Baserow
  finding: depends on the mcp Python SDK and pydantic-ai with six model-provider extras (BYO LLM)
  source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
  tier: observed
- app: Budibase
  finding: AI SDK + OpenAI client for AI agents, and Slack/Teams chat adapters for agents in chat
  source: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
  tier: observed
- app: Appsmith
  finding: OpenAI, Anthropic and Google AI query plugins plus a first-party appsmithAiPlugin
  source: https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
  tier: observed
- app: Retool
  finding: lists Claude Code and Cursor as integrations, plus a custom AI provider and Retool Vector
  source: https://retool.com/integrations
  tier: declared
apps:
- anchor: appsmith
  counts:
    declared: 0
    observed: 29
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
    layer: common
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
    tier: observed
  kind: self-hosted
  name: Appsmith
  page: /applications/low-code-internal-tools/appsmith/
  slug: appsmith
  url: https://github.com/appsmithorg/appsmith
- anchor: budibase
  counts:
    declared: 0
    observed: 22
  evidence:
  - route: dependency manifest
    url: https://github.com/Budibase/budibase/blob/master/packages/backend-core/package.json
  - route: dependency manifest
    url: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
  - route: source code
    url: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    name: Apache CouchDB
    provider: apache-couchdb
    says: ships the Apache CouchDB SDK or integration code
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    name: ArangoDB
    provider: arangodb
    says: ships the ArangoDB SDK or integration code
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    source: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
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
    name: Elastic
    provider: elastic
    says: ships the Elastic SDK or integration code
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    name: Firestore
    provider: firebase
    says: ships the Firestore SDK or integration code
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google Identity Platform
    provider: google-identity-platform
    says: ships the Google Identity Platform SDK or integration code
    source: https://github.com/Budibase/budibase/blob/master/packages/backend-core/package.json
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Microsoft Entra
    provider: microsoft-entra
    says: ships the Microsoft Entra SDK or integration code
    source: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
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
    provider: oracle-database
    says: ships the Oracle Database SDK or integration code
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/Budibase/budibase/blob/master/packages/backend-core/package.json
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/Budibase/budibase/blob/master/packages/server/package.json
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
    source: https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
    tier: observed
  kind: self-hosted
  name: Budibase
  page: /applications/low-code-internal-tools/budibase/
  slug: budibase
  url: https://github.com/Budibase/budibase
- anchor: nocodb
  counts:
    declared: 0
    observed: 41
  evidence:
  - route: dependency manifest
    url: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
  - route: source code
    url: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
    name: Amazon Cognito
    provider: amazon-cognito
    says: ships the Amazon Cognito SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
    name: AWS Kinesis
    provider: kinesis
    says: ships the AWS Kinesis SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Backblaze
    provider: backblaze
    says: ships the Backblaze SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare R2
    provider: cloudflare-r2
    says: ships the Cloudflare R2 SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: DeepSeek
    provider: deepseek
    says: ships the DeepSeek SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: DigitalOcean Spaces
    provider: digital-ocean
    says: ships the DigitalOcean Spaces SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google (@ai-sdk/google)
    provider: google-gemini
    says: ships the Google (@ai-sdk/google) SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Linode
    provider: linode
    says: ships the Linode SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: MailerSend
    provider: mailersend
    says: ships the MailerSend SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MinIO
    provider: minio
    says: ships the MinIO SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OVHcloud
    provider: ovh-cloud
    says: ships the OVHcloud SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Scaleway
    provider: scaleway
    says: ships the Scaleway SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: agent
    name: Unstructured
    provider: unstructured
    says: ships the Unstructured SDK or integration code
    source: https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: UpCloud
    provider: upcloud
    says: ships the UpCloud SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Vultr
    provider: vultr
    says: ships the Vultr SDK or integration code
    source: https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
    tier: observed
  kind: self-hosted
  name: NocoDB
  page: /applications/low-code-internal-tools/nocodb/
  slug: nocodb
  url: https://github.com/nocodb/nocodb
- anchor: tooljet
  counts:
    declared: 0
    observed: 48
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
    layer: domain
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
    tier: observed
  kind: self-hosted
  name: ToolJet
  page: /applications/low-code-internal-tools/tooljet/
  slug: tooljet
  url: https://github.com/ToolJet/ToolJet
- anchor: baserow
  counts:
    declared: 0
    observed: 12
  evidence:
  - route: dependency manifest
    url: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
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
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
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
    source: https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
    tier: observed
  kind: self-hosted
  name: Baserow
  page: /applications/low-code-internal-tools/baserow/
  slug: baserow
  url: https://github.com/baserow/baserow
- anchor: retool
  counts:
    declared: 56
    observed: 0
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
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://retool.com/integrations
    tier: declared
  kind: commercial
  name: Retool
  page: /applications/low-code-internal-tools/retool/
  slug: retool
  url: https://retool.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: low-code-internal-tools
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Software Development - Low Code
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---low-code
- category: IT & Administration
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
name: Low-code & Internal Tools
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: 'the data-source connector is the product: every builder queries operational databases directly'
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: warehouse and query-engine connectors for internal dashboards
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: full-text search engines as data sources; no search-engine node
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object-storage data sources and file-upload backends
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: invoke serverless functions as a query
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI query / AI field / agent builders call hosted model APIs
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: spreadsheet and no-code database sources (and the reference apps themselves)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: event collection / CDP
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and performance monitoring of the builder itself
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics in the builder
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: map widget
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: file pickers that import from cloud drives
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: CAPTCHA widget
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: post to team chat from apps and automations
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: sign in with Google / Microsoft
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: user pool / directory
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: event streams as data sources; no message-broker node
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: send email from an app action / notification
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: push / fan-out notifications
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'git hosting: app source control and repository data sources'
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: issue / project trackers as data sources or import targets
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: payments data source / billing
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: send SMS from an app action / notification
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: agent
  why: document parsing for AI ingestion
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: support-desk data sources for support ops tools
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: e-commerce store as a data source
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: workflow engine as a data source / orchestration backend
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CRM data sources for sales ops tools
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CI pipelines as a data source
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: search-performance data source
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: domain
  why: feature-flag service as a data source
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
    - agent_band: agent-native
      agent_readiness: 41.0
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon DynamoDB
      slug: amazon-dynamodb
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - Document Store
      - Key-Value Store
      tier: observed
      url: /providers/amazon-dynamodb/
    - agent_band: agent-ready
      agent_readiness: 59.1
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: observed
      url: /providers/mongodb/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 67.0
      mcp:
        source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
        status: verified
      name: Microsoft SQL Server
      slug: microsoft-sql-server
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firestore
      slug: google-firebase
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Database
      slug: oracle-database
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: observed
      url: /providers/oracle-database/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: MySQL
      slug: mysql
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Database
      - Open Source
      - RDBMS
      - Relational Database
      tier: observed
      url: /providers/mysql/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: PostgreSQL
      slug: postgresql
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Database
      - Open Source
      - Relational Database
      - SQL
      tier: observed
      url: /providers/postgresql/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Budibase
      - Retool
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 40.9
      mcp:
        status: none
      name: Apache CouchDB
      slug: apache-couchdb
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Apache
      - Database
      - Document Store
      - JSON
      tier: observed
      url: /providers/apache-couchdb/
    - agent_band: agent-ready
      agent_readiness: 30.9
      apps:
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Cosmos DB
      slug: azure-cosmos-db
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Database
      - Document Database
      - NoSQL
      - Vector Search
      tier: observed
      url: /providers/azure-cosmos-db/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Appsmith
      - Budibase
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: ArangoDB
      slug: arangodb
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Company
      - Database
      - Graph Database
      - Multi-Model Database
      tier: observed
      url: /providers/arangodb/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Retool
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 44.8
      mcp:
        status: none
      name: SAP HANA
      slug: sap-hana
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Database
      - Enterprise
      tier: observed
      url: /providers/sap-hana/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Retool
      - ToolJet
      band: minimal
      in_catalog: true
      kin_score: 10.3
      mcp:
        status: none
      name: RethinkDB
      slug: rethinkdb
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Database
      - Document Database
      - NoSQL
      - Real-Time
      tier: observed
      url: /providers/rethinkdb/
    - agent_band: agent-ready
      agent_readiness: 57.8
      apps:
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://github.com/appwrite/mcp
        status: verified
      name: Appwrite
      slug: appwrite
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Application
      - Backend
      - Mobile
      - Open Source
      tier: observed
      url: /providers/appwrite/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud Spanner
      slug: google-cloud-spanner
      sources:
      - https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
      status: profiled
      tags:
      - Database
      - Distributed
      - Google Cloud
      - Relational
      tier: observed
      url: /providers/google-cloud-spanner/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        source: https://github.com/influxdata/influxdb3_mcp_server
        status: verified
      name: InfluxDB
      slug: influxdata
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Database
      - Monitoring
      - Observability
      - Time Series Database
      tier: observed
      url: /providers/influxdata/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: unchecked
      name: MariaDB
      slug: mariadb
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Open Source
      tier: observed
      url: /providers/mariadb/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ToolJet
      band: emerging
      in_catalog: true
      kin_score: 14.0
      mcp:
        status: none
      name: IBM Db2
      slug: ibm-db2
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Relational Database
      - SQL
      tier: observed
      url: /providers/ibm-db2/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Retool
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        status: none
      name: Google Cloud Datastore
      slug: google-cloud-datastore
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Database
      - Document Database
      - Google Cloud
      - NoSQL
      tier: declared
      url: /providers/google-cloud-datastore/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Retool
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Apache Cassandra
      slug: cassandra
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Apache
      - Big Data
      - Database
      - Distributed
      tier: declared
      url: /providers/cassandra/
    - agent_band: null
      agent_readiness: null
      apps:
      - Retool
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Google AlloyDB
      slug: google-alloydb
      sources:
      - https://retool.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Appsmith
      - Budibase
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: observed
      url: /providers/snowflake/
    - agent_band: agent-native
      agent_readiness: 65.5
      apps:
      - Appsmith
      - NocoDB
      - Retool
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 58.5
      apps:
      - NocoDB
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 77.1
      mcp:
        source: https://github.com/ClickHouse/mcp-clickhouse
        status: verified
      name: ClickHouse
      slug: clickhouse
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
      - Appsmith
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
        status: verified
      name: Amazon Redshift
      slug: amazon-redshift
      sources:
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Lake
      tier: observed
      url: /providers/amazon-redshift/
    - agent_band: agent-native
      agent_readiness: 44.8
      apps:
      - Retool
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Athena
      slug: amazon-athena
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Amazon Athena
      - Analytics
      - SQL
      - Serverless
      tier: observed
      url: /providers/amazon-athena/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Retool
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: observed
      url: /providers/google-bigquery/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Retool
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Vertica
      slug: vertica
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics Database
      - Data Lakehouse
      - Data Warehouse
      - Database
      tier: declared
      url: /providers/vertica/
    - agent_band: null
      agent_readiness: null
      apps:
      - Retool
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Presto
      slug: prestodb
      sources:
      - https://retool.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Budibase
      - NocoDB
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: observed
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Retool
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
    - agent_band: agent-aware
      agent_readiness: 26.9
      apps:
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        source: https://baserow.io/user-docs/mcp-server
        status: verified
      name: Baserow
      slug: baserow
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Database
      - No-Code
      - Open Source
      - REST API
      tier: observed
      url: /providers/baserow/
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - ToolJet
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://nocodb.com/docs/product-docs/mcp
        status: verified
      name: NocoDB
      slug: nocodb
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Airtable Alternative
      - Database
      - Low-Code
      - No-Code
      tier: observed
      url: /providers/nocodb/
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
      - Baserow
      - NocoDB
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
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
      - Appsmith
      - Budibase
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic
      slug: elastic
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 47.3
      apps:
      - ToolJet
      band: thin
      in_catalog: true
      kin_score: 39.2
      mcp:
        source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
        status: verified
      name: Typesense
      slug: typesense
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Full-Text Search
      - Open Source
      - Search Engines
      - Typo Tolerance
      tier: observed
      url: /providers/typesense/
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
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
      - https://retool.com/integrations
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
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 58.1
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://developer.close.com/mcp
        status: verified
      name: Close
      slug: close
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - CRM
      - Calling
      - Inside Sales
      - Sales Engagement
      tier: declared
      url: /providers/close/
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
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Retool
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        source: https://dev.frontapp.com/docs/mcp
        status: documented
      name: Front
      slug: front
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Email
      - Inbox
      tier: declared
      url: /providers/front/
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
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
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
      - NocoDB
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: AWS Kinesis
      slug: kinesis
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
      - Retool
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Kafka
      slug: apache-kafka
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: declared
      url: /providers/apache-kafka/
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Appsmith
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 74.9
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
        status: verified
      name: AWS Lambda
      slug: aws-lambda
      sources:
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      - https://retool.com/integrations
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Serverless
      tier: observed
      url: /providers/aws-lambda/
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 73.5
      mcp:
        source: https://github.com/CircleCI-Public/mcp-server-circleci
        status: verified
      name: CircleCI
      slug: circleci
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/circleci/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Search Console
      slug: google-search-console
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: declared
      url: /providers/google-search-console/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.7
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 84.5
      mcp:
        source: https://launchdarkly.com/docs/home/getting-started/mcp
        status: verified
      name: LaunchDarkly
      slug: launchdarkly
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Observability
      tier: declared
      url: /providers/launchdarkly/
  - capability:
      attribution: Turbo EA
      id: BC-600.40.20
      key: BC-600.40.20
      name: IT Job Scheduling and Batch Operations
      url: /capabilities/it-operations-management/
      via_parent: IT Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - ToolJet
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        source: https://github.com/temporalio/temporal-mcp
        status: verified
      name: Temporal
      slug: temporal-io
      sources:
      - https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
      status: profiled
      tags:
      - Durable Execution
      - Workflow Orchestration
      - Workflows
      - gRPC
      tier: observed
      url: /providers/temporal-io/
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Retool
      band: developing
      in_catalog: true
      kin_score: 53.5
      mcp:
        status: unknown
      name: BigID
      slug: bigid
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - DLP
      - DSPM
      - Data Security
      - Privacy
      tier: declared
      url: /providers/bigid/
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: observed
      url: /providers/woocommerce/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: observed
      url: /providers/n8n/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Appsmith
      - Baserow
      - Budibase
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/Budibase/budibase/tree/master/packages/server/src/integrations
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
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
      - Baserow
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
      - Baserow
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - NocoDB
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        source: https://github.com/minio/mcp-server-aistor
        status: verified
      name: MinIO
      slug: minio
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Cloud-Native
      - Object Storage
      - S3 Compatible
      - Storage
      tier: observed
      url: /providers/minio/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - NocoDB
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        source: https://github.com/linode/mcp-cluster-api
        status: verified
      name: Linode
      slug: linode
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Cloud Computing
      - Infrastructure-as-a-Service
      - Kubernetes
      - Virtual Machines
      tier: observed
      url: /providers/linode/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - NocoDB
      band: strong
      in_catalog: true
      kin_score: 63.4
      mcp:
        status: none
      name: UpCloud
      slug: upcloud
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Cloud
      - Company
      - Infrastructure
      - Object Storage
      tier: observed
      url: /providers/upcloud/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/scaleway/scaleway-cli
        status: verified
      name: Scaleway
      slug: scaleway
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud Computing
      - Containers
      - Database
      tier: observed
      url: /providers/scaleway/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 49.6
      mcp:
        source: https://github.com/backblaze-labs/b2-mcp
        status: verified
      name: Backblaze
      slug: backblaze
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Object Storage
      - Storage
      tier: observed
      url: /providers/backblaze/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean Spaces
      slug: digital-ocean
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 43.3
      mcp:
        source: https://github.com/vultr/vultr-mcp
        status: verified
      name: Vultr
      slug: vultr
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Cloud
      - Company
      - Compute
      - Infrastructure
      tier: observed
      url: /providers/vultr/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 43.2
      mcp:
        source: https://mcp.eu.ovhcloud.com/mcp
        status: verified
      name: OVHcloud
      slug: ovh-cloud
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Cloud
      - Compute
      - Hosting
      - Servers
      tier: observed
      url: /providers/ovh-cloud/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - NocoDB
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/cloudflare-r2/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Budibase
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/server/package.json
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
      - Budibase
      - NocoDB
      - Retool
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/server/package.json
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      - https://retool.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - NocoDB
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/nocodb/nocodb/tree/develop/packages/nocodb/src/plugins
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
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
      - Appsmith
      - Baserow
      - NocoDB
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
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
      - Budibase
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/server/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - Appsmith
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana Faro
      slug: grafana-com
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Appsmith
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        source: https://github.com/betterbugs/mcp
        status: verified
      name: BetterBugs
      slug: betterbugs
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Bug Tracking
      - Collaboration
      - Company
      - Software-as-a-Service
      tier: observed
      url: /providers/betterbugs/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Baserow
      - Budibase
      - NocoDB
      - ToolJet
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/backend-core/package.json
      - https://github.com/ToolJet/ToolJet/blob/develop/frontend/package.json
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Appsmith
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 19.1
      apps:
      - Appsmith
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        source: https://help.smartlook.com/mcp
        status: verified
      name: Smartlook
      slug: smartlook
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Funnels
      - Heatmaps
      - Product Analytics
      - Session Recording
      tier: observed
      url: /providers/smartlook/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://retool.com/integrations
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - NocoDB
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 56.5
      apps:
      - NocoDB
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp:
        source: https://developers.mailersend.com/mcp-server.html
        status: verified
      name: MailerSend
      slug: mailersend
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Email
      - Marketing
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailersend/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - ToolJet
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/ToolJet/ToolJet/blob/develop/server/package.json
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      - https://retool.com/integrations
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
      - NocoDB
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
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
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Appsmith
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://github.com/ToolJet/ToolJet/blob/develop/frontend/package.json
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
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
      - Appsmith
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - NocoDB
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Appsmith
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - NocoDB
      - Retool
      - ToolJet
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/ToolJet/ToolJet/tree/develop/plugins/packages
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - NocoDB
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: agent-native
      agent_readiness: 70.1
      apps:
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp:
        source: https://github.com/OneSignal/onesignal-ai-skills
        status: documented
      name: OneSignal
      slug: onesignal
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Email
      - Notification
      - Push
      - SMS
      tier: declared
      url: /providers/onesignal/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Budibase
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra
      slug: microsoft-entra
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/server/package.json
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Budibase
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google Identity Platform
      slug: google-identity-platform
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/backend-core/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Appsmith
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
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
      - Appsmith
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://github.com/appsmithorg/appsmith/blob/release/app/client/package.json
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - NocoDB
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: Amazon Cognito
      slug: amazon-cognito
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Authentication
      - Identity
      - OpenID Connect
      tier: observed
      url: /providers/amazon-cognito/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Appsmith
      - Baserow
      - Budibase
      - NocoDB
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/Budibase/budibase/blob/master/packages/server/package.json
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Appsmith
      - Baserow
      - NocoDB
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Appsmith
      - Baserow
      - NocoDB
      - Retool
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google AI (googleAiPlugin)
      slug: google-gemini
      sources:
      - https://github.com/appsmithorg/appsmith/tree/release/app/server/appsmith-plugins
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - Baserow
      - NocoDB
      - Retool
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - NocoDB
      - Retool
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      - https://retool.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - Baserow
      - NocoDB
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Baserow
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/baserow/baserow/blob/develop/backend/pyproject.toml
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - NocoDB
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Retool
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://retool.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: declared
      url: /providers/cohere/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - NocoDB
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        source: https://github.com/Unstructured-IO/UNS-MCP
        status: verified
      name: Unstructured
      slug: unstructured
      sources:
      - https://github.com/nocodb/nocodb/blob/develop/packages/nocodb/package.json
      status: profiled
      tags:
      - Document Processing
      - ETL
      - LLM
      - RAG
      tier: observed
      url: /providers/unstructured/
  layer: agent
summary:
  coverage_pct: 98.1
  declared_only: 17
  distinct_providers: 107
  in_catalog: 105
  mcp:
    documented: 2
    none: 30
    unchecked: 3
    verified: 71
  mcp_verified: 71
  mean_kin_score: 60.3
  observed: 90
  queued: 2
  reference_apps: 6
title: 'Low-code & Internal Tools: application blueprint'
---
