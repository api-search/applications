---
app: GrowthBook
app_slug: growthbook
app_url: https://github.com/growthbook/growthbook
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4280.40.30
  key: BC-4280.40.30
  layer: domain
  name: Experiment Result Adjudication
  providers:
  - Adobe Experience Platform Query Service
  - Amazon Athena
  - Amazon Redshift
  - ClickHouse
  - Databricks
  - Google BigQuery
  - Snowflake
  - Vertica
  url: /capabilities/experimentation-programme-management/
  via_parent: Experimentation Programme Management
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Google Analytics
  - Mixpanel
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Amazon CloudWatch
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
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
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google Gemini
  - Mistral
  - OpenAI
  - xAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 0
  observed: 20
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
- route: source code
  url: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.9
    band: exemplar
    in_catalog: true
    kin_score: 76.2
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
  layer: domain
  name: Adobe Experience Platform Query Service
  provider: adobe
  says: ships the Adobe Experience Platform Query Service SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: thin
    in_catalog: true
    kin_score: 34.1
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
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    agent_readiness: 28.0
    band: exemplar
    in_catalog: true
    kin_score: 71.0
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id006
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: common
  name: Amazon CloudWatch
  provider: amazon-cloudwatch
  says: ships the Amazon CloudWatch SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
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
  says: ships the Amazon Redshift SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
  says: ships the Anthropic SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 76.9
    mcp: &id013
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id014
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
  layer: domain
  name: ClickHouse
  provider: clickhouse
  says: ships the ClickHouse SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: strong
    in_catalog: true
    kin_score: 57.1
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
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id017
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id018
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id019
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id020
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: ships the Google BigQuery SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id021
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id022
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id023
      status: none
    slug: google-gemini
    status: profiled
    tags: &id024
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id025
      status: none
    slug: mistral
    status: profiled
    tags: &id026
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: agent
  name: Mistral
  provider: mistral
  says: ships the Mistral SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id027
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id028
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: domain
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id029
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    mcp: &id031
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id032
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id033
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id034
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: ships the Snowflake SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id035
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id036
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id037
      status: none
    slug: vertica
    status: profiled
    tags: &id038
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
  layer: domain
  name: Vertica
  provider: vertica
  says: ships the Vertica SDK or integration code
  source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    agent_readiness: 38.8
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id039
      status: none
    slug: xai
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
  layer: agent
  name: xAI
  provider: xai
  says: ships the xAI SDK or integration code
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/growthbook/
providers:
- agent_band: agent-ready
  agent_readiness: 65.9
  band: exemplar
  in_catalog: true
  kin_score: 76.2
  mcp: *id001
  name: Adobe Experience Platform Query Service
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id003
  name: Amazon Athena
  slug: amazon-athena
  status: profiled
  tags: *id004
  url: /providers/amazon-athena/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: exemplar
  in_catalog: true
  kin_score: 71.0
  mcp: *id005
  name: Amazon CloudWatch
  slug: amazon-cloudwatch
  status: profiled
  tags: *id006
  url: /providers/amazon-cloudwatch/
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
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 76.9
  mcp: *id013
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id014
  url: /providers/clickhouse/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id015
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id016
  url: /providers/databricks/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id017
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id018
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id019
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id020
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id021
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id022
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id023
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id024
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id025
  name: Mistral
  slug: mistral
  status: profiled
  tags: *id026
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id027
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id028
  url: /providers/mixpanel/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id029
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id030
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id031
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id032
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id033
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id034
  url: /providers/snowflake/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id035
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id036
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id037
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id038
  url: /providers/vertica/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id039
  name: xAI
  slug: xai
  status: profiled
  tags: *id040
  url: /providers/xai/
siblings:
- name: ConfigCat
  rows: 18
  url: /applications/feature-flags-experimentation/configcat/
- name: Flagsmith
  rows: 16
  url: /applications/feature-flags-experimentation/flagsmith/
- name: Flipt
  rows: 7
  url: /applications/feature-flags-experimentation/flipt/
- name: LaunchDarkly
  rows: 91
  url: /applications/feature-flags-experimentation/launchdarkly/
- name: Statsig
  rows: 33
  url: /applications/feature-flags-experimentation/statsig/
- name: Unleash
  rows: 4
  url: /applications/feature-flags-experimentation/unleash/
sitemap: true
title: 'GrowthBook: Feature Flags & Experimentation reference app'
---
