---
app: Statsig
app_slug: statsig
app_url: https://statsig.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-932
  key: AE-932
  layer: domain
  name: Edge Functions & Edge Config Stores
  providers:
  - Akamai
  - Cloudflare
  - Fastly
  - Vercel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.20.10
  key: BC-4210.20.10
  layer: domain
  name: Environment Provisioning
  providers:
  - Pulumi
  - Serverless Framework
  - Terraform
  url: /capabilities/environment-management/
  via_parent: Environment Management
- attribution: Turbo EA
  id: BC-4280.40.30
  key: BC-4280.40.30
  layer: domain
  name: Experiment Result Adjudication
  providers:
  - Amazon Redshift
  - Google BigQuery
  - Snowflake
  url: /capabilities/experimentation-programme-management/
  via_parent: Experimentation Programme Management
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Amplitude
  - Google Analytics
  - Heap
  - Mixpanel
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Braze
  - Census
  - Fivetran
  - Google Tag Manager
  - Hightouch
  - mParticle
  - RevenueCat
  - RudderStack
  - Stitch Data
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
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
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Azure AI
  - Cloudflare Workers AI
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 33
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://docs.statsig.com/integrations/introduction
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.0
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id002
      status: none
    slug: akamai
    status: profiled
    tags: &id003
    - CDN
    - Cloud
    - Edge Computing
    - Networks
    url: /providers/akamai/
  layer: domain
  name: Akamai
  provider: akamai
  says: lists Akamai as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 44.5
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id004
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id005
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
  layer: domain
  name: Amazon Redshift
  provider: amazon-redshift
  says: lists Amazon Redshift as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id006
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id007
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: domain
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://docs.statsig.com/integrations/introduction
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
    agent_readiness: 29.9
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id008
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id009
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: agent
  name: Azure AI
  provider: microsoft-azure-openai
  says: lists Azure AI as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id010
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id011
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: common
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 26.0
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id012
      status: none
    slug: getcensus
    status: profiled
    tags: &id013
    - Census
    - Data Activation
    - Reverse ETL
    - Sync
    url: /providers/getcensus/
  layer: common
  name: Census
  provider: getcensus
  says: lists Census as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id014
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id015
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: domain
  name: Cloudflare
  provider: cloudflare
  says: lists Cloudflare as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts: *id001
  layer: agent
  name: Cloudflare Workers AI
  provider: cloudflare
  says: lists Cloudflare Workers AI as an integration
  source: https://docs.statsig.com/integrations/introduction
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id016
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id017
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id018
      source: https://github.com/fastly/mcp
      status: verified
    slug: fastly
    status: profiled
    tags: &id019
    - CDN
    - Edge Cloud
    - Edge Compute
    - WebAssembly
    url: /providers/fastly/
  layer: domain
  name: Fastly
  provider: fastly
  says: lists Fastly as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id020
      source: https://github.com/fivetran/fivetran-mcp
      status: verified
    slug: fivetran
    status: profiled
    tags: &id021
    - Connectors
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/fivetran/
  layer: common
  name: Fivetran
  provider: fivetran
  says: lists Fivetran as an integration
  source: https://docs.statsig.com/integrations/introduction
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id022
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id023
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://docs.statsig.com/integrations/introduction
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
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id024
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id025
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id026
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id027
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id028
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id029
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id030
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id031
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id032
      status: unknown
    slug: heap
    status: profiled
    tags: &id033
    - Analytics
    - Autocapture
    - Digital Analytics
    - Product Analytics
    url: /providers/heap/
  layer: domain
  name: Heap
  provider: heap
  says: lists Heap as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id034
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id035
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
  layer: common
  name: Hightouch
  provider: hightouch
  says: lists Hightouch as an integration
  source: https://docs.statsig.com/integrations/introduction
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id036
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id037
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id038
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id039
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: domain
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 59.5
    mcp: &id040
      status: none
    slug: mparticle
    status: profiled
    tags: &id041
    - Analytics
    - CDP
    - Customer Data Platform
    - Identity Resolution
    url: /providers/mparticle/
  layer: common
  name: mParticle
  provider: mparticle
  says: lists mParticle as an integration
  source: https://docs.statsig.com/integrations/introduction
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
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id042
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id044
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id045
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: common
  name: PagerDuty
  provider: pagerduty
  says: lists PagerDuty as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.20.10
    key: BC-4210.20.10
    name: Environment Provisioning
    url: /capabilities/environment-management/
    via_parent: Environment Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id046
      source: https://registry.npmjs.org/@pulumi/mcp-server
      status: verified
    slug: pulumi
    status: profiled
    tags: &id047
    - Automation
    - Cloud
    - DevOps
    - Infrastructure as Code
    url: /providers/pulumi/
  layer: domain
  name: Pulumi
  provider: pulumi
  says: lists Pulumi as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id048
      source: https://www.revenuecat.com/docs/tools/mcp
      status: verified
    slug: revenuecat
    status: profiled
    tags: &id049
    - Billing
    - In-App Purchases
    - Mobile
    - Subscription
    url: /providers/revenuecat/
  layer: common
  name: RevenueCat
  provider: revenuecat
  says: lists RevenueCat as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 79.1
    mcp: &id050
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id051
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
  layer: common
  name: RudderStack
  provider: rudderstack
  says: lists RudderStack as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.20.10
    key: BC-4210.20.10
    name: Environment Provisioning
    url: /capabilities/environment-management/
    via_parent: Environment Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.1
    band: thin
    in_catalog: true
    kin_score: 36.6
    mcp: &id052
      source: https://www.serverless.com/framework/docs/guides/mcp
      status: verified
    slug: serverless
    status: profiled
    tags: &id053
    - Company
    - Developer Tools
    - Infrastructure as Code
    - Serverless
    url: /providers/serverless/
  layer: domain
  name: Serverless Framework
  provider: serverless
  says: lists Serverless Framework as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    mcp: &id054
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id055
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id056
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id057
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id058
      status: none
    slug: stitch-data
    status: profiled
    tags: &id059
    - Cloud Data
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/stitch-data/
  layer: common
  name: Stitch Data
  provider: stitch-data
  says: lists Stitch Data as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.20.10
    key: BC-4210.20.10
    name: Environment Provisioning
    url: /capabilities/environment-management/
    via_parent: Environment Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id060
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id061
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
  layer: domain
  name: Terraform
  provider: terraform
  says: lists Terraform as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
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
    mcp: &id062
      status: none
    slug: segment
    status: profiled
    tags: &id063
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Twilio Segment
  provider: segment
  says: lists Twilio Segment as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id064
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id065
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: domain
  name: Vercel
  provider: vercel
  says: lists Vercel as an integration
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/statsig/
providers:
- agent_band: agent-ready
  agent_readiness: 40.0
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id002
  name: Akamai
  slug: akamai
  status: profiled
  tags: *id003
  url: /providers/akamai/
- agent_band: agent-native
  agent_readiness: 44.5
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id004
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id005
  url: /providers/amazon-redshift/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id006
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id007
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id008
  name: Azure AI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id009
  url: /providers/microsoft-azure-openai/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id010
  name: Braze
  slug: braze
  status: profiled
  tags: *id011
  url: /providers/braze/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id012
  name: Census
  slug: getcensus
  status: profiled
  tags: *id013
  url: /providers/getcensus/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id014
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id015
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id016
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id017
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id018
  name: Fastly
  slug: fastly
  status: profiled
  tags: *id019
  url: /providers/fastly/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id020
  name: Fivetran
  slug: fivetran
  status: profiled
  tags: *id021
  url: /providers/fivetran/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id022
  name: GitHub
  slug: github
  status: profiled
  tags: *id023
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id024
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id025
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id026
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id027
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id028
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id029
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id030
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id031
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id032
  name: Heap
  slug: heap
  status: profiled
  tags: *id033
  url: /providers/heap/
- agent_band: agent-ready
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id034
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id035
  url: /providers/hightouch/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id036
  name: Jira
  slug: jira
  status: profiled
  tags: *id037
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id038
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id039
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id040
  name: mParticle
  slug: mparticle
  status: profiled
  tags: *id041
  url: /providers/mparticle/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id042
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id043
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id044
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id045
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id046
  name: Pulumi
  slug: pulumi
  status: profiled
  tags: *id047
  url: /providers/pulumi/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id048
  name: RevenueCat
  slug: revenuecat
  status: profiled
  tags: *id049
  url: /providers/revenuecat/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 79.1
  mcp: *id050
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id051
  url: /providers/rudderstack/
- agent_band: human-only
  agent_readiness: 4.1
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id052
  name: Serverless Framework
  slug: serverless
  status: profiled
  tags: *id053
  url: /providers/serverless/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id054
  name: Slack
  slug: slack
  status: profiled
  tags: *id055
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id056
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id057
  url: /providers/snowflake/
- agent_band: human-only
  agent_readiness: 3.8
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id058
  name: Stitch Data
  slug: stitch-data
  status: profiled
  tags: *id059
  url: /providers/stitch-data/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id060
  name: Terraform
  slug: terraform
  status: profiled
  tags: *id061
  url: /providers/terraform/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id062
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id063
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id064
  name: Vercel
  slug: vercel
  status: profiled
  tags: *id065
  url: /providers/vercel/
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
- name: GrowthBook
  rows: 20
  url: /applications/feature-flags-experimentation/growthbook/
- name: LaunchDarkly
  rows: 91
  url: /applications/feature-flags-experimentation/launchdarkly/
- name: Unleash
  rows: 4
  url: /applications/feature-flags-experimentation/unleash/
sitemap: true
title: 'Statsig: Feature Flags & Experimentation reference app'
---
