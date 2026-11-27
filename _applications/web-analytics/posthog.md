---
app: PostHog
app_slug: posthog
app_url: https://github.com/PostHog/posthog
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Dagster+ (Dagster Cloud)
  - Databricks
  - Google BigQuery
  - Google Sheets
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1300.10
  key: customer-onboarding-management
  layer: domain
  name: Customer Onboarding Management
  providers:
  - Appcues
  url: /capabilities/customer-onboarding-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook / Meta Ads
  - Google Ads
  - LinkedIn Marketing API
  - Microsoft Advertising
  - Pinterest Ads
  - Reddit Ads
  - Snapchat Ads
  - TikTok Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - MaxMind GeoIP2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Accoil
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: domain
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-100.60.10
  key: AE-100.60.10
  layer: common
  name: Agent Evaluation & Testing
  providers:
  - Braintrust
  url: /capabilities/agent-quality-operations/
  via_parent: Agent Quality & Operations
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: common
  name: Artificial Intelligence Management
  providers:
  - Anthropic
  - Google Gemini
  - Mistral AI
  - OpenAI
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  - Azure Blob Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-906
  key: AE-906
  layer: common
  name: Code Execution Sandboxes
  providers:
  - Modal
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - beehiiv
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Close
  - HubSpot
  - Klime
  - Salesforce
  - Unify
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - ClickUp
  - Slack
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30.10
  key: BC-4220.30.10
  layer: common
  name: On-Call Rotation Management
  providers:
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: Incident Response Management
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
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - GitHub
  - GitLab
  - Linear
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - Stripe
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.20
  key: AE-110.30.20
  layer: common
  name: Text-to-Speech
  providers:
  - ElevenLabs
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp Business
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 0
  observed: 42
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/PostHog/posthog/master/frontend/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
- route: documentation
  url: https://posthog.com/docs/model-context-protocol
- route: source code
  url: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
integrations:
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
    agent_readiness: 16.3
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id001
      status: none
    slug: accoil
    status: profiled
    tags: &id002
    - Customer Success
    - Expansion
    - Playbooks
    - Retention
    url: /providers/accoil/
  layer: domain
  name: Accoil
  provider: accoil
  says: ships the Accoil SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: common
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1300.10
    key: customer-onboarding-management
    name: Customer Onboarding Management
    url: /capabilities/customer-onboarding-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id007
      status: none
    slug: appcues
    status: profiled
    tags: &id008
    - Analytics
    - In-App Guidance
    - Onboarding
    - Product
    url: /providers/appcues/
  layer: domain
  name: Appcues
  provider: appcues
  says: ships the Appcues SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.6
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id011
      source: https://github.com/beehiiv/agents
      status: verified
    slug: beehiiv
    status: profiled
    tags: &id012
    - Creators
    - Email
    - Newsletters
    - Subscription
    url: /providers/beehiiv/
  layer: common
  name: beehiiv
  provider: beehiiv
  says: ships the beehiiv SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.60.10
    key: AE-100.60.10
    name: Agent Evaluation & Testing
    url: /capabilities/agent-quality-operations/
    via_parent: Agent Quality & Operations
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.7
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id013
      source: https://www.braintrust.dev/docs/integrations/developer-tools/mcp
      status: verified
    slug: braintrust
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Evaluation
    - LLM
    - Observability
    url: /providers/braintrust/
  layer: common
  name: Braintrust
  provider: braintrust
  says: ships the Braintrust SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id015
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id016
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: common
  name: ClickUp
  provider: clickup
  says: ships the ClickUp SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    agent_readiness: 58.1
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id017
      source: https://developer.close.com/mcp
      status: verified
    slug: close
    status: profiled
    tags: &id018
    - CRM
    - Calling
    - Inside Sales
    - Sales Engagement
    url: /providers/close/
  layer: common
  name: Close
  provider: close
  says: ships the Close SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id019
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id020
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: ships the Cloudflare SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/frontend/package.json
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
    agent_band: agent-aware
    agent_readiness: 17.5
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id021
      status: none
    slug: dagster
    status: profiled
    tags: &id022
    - Data Engineering
    - Data Orchestration
    - Data Pipeline
    - ETL
    url: /providers/dagster/
  layer: domain
  name: Dagster+ (Dagster Cloud)
  provider: dagster
  says: ships the Dagster+ (Dagster Cloud) SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
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
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 83.2
    mcp: &id025
      source: https://github.com/elevenlabs/elevenlabs-mcp
      status: verified
    slug: elevenlabs
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Voice
    url: /providers/elevenlabs/
  layer: common
  name: ElevenLabs
  provider: elevenlabs
  says: ships the ElevenLabs SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id027
      status: none
    slug: facebook
    status: profiled
    tags: &id028
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook / Meta Ads
  provider: facebook
  says: ships the Facebook / Meta Ads SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
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
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id031
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id032
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id033
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id034
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: ships the Google Ads SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
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
    mcp: &id035
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id036
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: ships the Google BigQuery SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id037
      status: none
    slug: google-gemini
    status: profiled
    tags: &id038
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: common
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
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
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id041
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id042
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: domain
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    mcp: &id043
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id044
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id045
      status: unknown
    slug: klime
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Automation
    - Productivity
    - Software-as-a-Service
    url: /providers/klime/
  layer: common
  name: Klime
  provider: klime
  says: ships the Klime SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id047
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id048
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: common
  name: Linear
  provider: linear-app
  says: ships the Linear SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
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
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id049
      status: none
    slug: linkedin-ads
    status: profiled
    tags: &id050
    - Advertising
    - Lead Generation
    - LinkedIn
    - Marketing
    url: /providers/linkedin-ads/
  layer: domain
  name: LinkedIn Marketing API
  provider: linkedin-ads
  says: ships the LinkedIn Marketing API SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id051
      status: none
    slug: maxmind
    status: profiled
    tags: &id052
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
  name: MaxMind GeoIP2
  provider: maxmind
  says: ships the MaxMind GeoIP2 SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 11.7
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id053
      status: none
    slug: microsoft-advertising
    status: profiled
    tags: &id054
    - Advertising
    - Analytics
    - Bing Ads
    - Bulk Operations
    url: /providers/microsoft-advertising/
  layer: domain
  name: Microsoft Advertising
  provider: microsoft-advertising
  says: ships the Microsoft Advertising SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id055
      status: none
    slug: mistral
    status: profiled
    tags: &id056
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: common
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-906
    key: AE-906
    name: Code Execution Sandboxes
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id057
      status: none
    slug: modal-labs
    status: profiled
    tags: &id058
    - AI Infrastructure
    - Compute
    - GPU
    - Serverless
    url: /providers/modal-labs/
  layer: common
  name: Modal
  provider: modal-labs
  says: ships the Modal SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id059
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30.10
    key: BC-4220.30.10
    name: On-Call Rotation Management
    url: /capabilities/incident-response-management/
    via_parent: Incident Response Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id061
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id062
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: common
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
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
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id063
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id064
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: domain
  name: Pinterest Ads
  provider: pinterest
  says: ships the Pinterest Ads SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
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
    agent_readiness: 43.0
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id065
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id066
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit Ads
  provider: reddit
  says: ships the Reddit Ads SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    mcp: &id067
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id068
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: ships the Salesforce SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id069
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id070
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
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
    agent_readiness: 47.1
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id071
      status: none
    slug: snapchat
    status: profiled
    tags: &id072
    - Advertising
    - Augmented Reality
    - Marketing
    - Messaging
    url: /providers/snapchat/
  layer: domain
  name: Snapchat Ads
  provider: snapchat
  says: ships the Snapchat Ads SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    mcp: &id073
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id074
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: ships the Snowflake SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id075
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id076
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id077
      status: none
    slug: tiktok-ads
    status: profiled
    tags: &id078
    - Ad Campaigns
    - Advertising
    - Marketing
    - Social Media
    url: /providers/tiktok-ads/
  layer: domain
  name: TikTok Ads
  provider: tiktok-ads
  says: ships the TikTok Ads SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    mcp: &id079
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id080
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
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
    agent_readiness: 60.5
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id081
      status: none
    slug: unify
    status: profiled
    tags: &id082
    - Go-To-Market
    - Marketing
    - Outbound
    - Sales
    url: /providers/unify/
  layer: common
  name: Unify
  provider: unify
  says: ships the Unify SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id083
      status: none
    slug: whatsapp
    status: profiled
    tags: &id084
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp Business
  provider: whatsapp
  says: ships the WhatsApp Business SDK or integration code
  source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/posthog/
providers:
- agent_band: agent-aware
  agent_readiness: 16.3
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id001
  name: Accoil
  slug: accoil
  status: profiled
  tags: *id002
  url: /providers/accoil/
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
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id007
  name: Appcues
  slug: appcues
  status: profiled
  tags: *id008
  url: /providers/appcues/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id009
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id011
  name: beehiiv
  slug: beehiiv
  status: profiled
  tags: *id012
  url: /providers/beehiiv/
- agent_band: agent-ready
  agent_readiness: 51.7
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id013
  name: Braintrust
  slug: braintrust
  status: profiled
  tags: *id014
  url: /providers/braintrust/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id015
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id016
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 58.1
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id017
  name: Close
  slug: close
  status: profiled
  tags: *id018
  url: /providers/close/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id019
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id020
  url: /providers/cloudflare/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id021
  name: Dagster+ (Dagster Cloud)
  slug: dagster
  status: profiled
  tags: *id022
  url: /providers/dagster/
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
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 83.2
  mcp: *id025
  name: ElevenLabs
  slug: elevenlabs
  status: profiled
  tags: *id026
  url: /providers/elevenlabs/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id027
  name: Facebook / Meta Ads
  slug: facebook
  status: profiled
  tags: *id028
  url: /providers/facebook/
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
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id031
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id032
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id033
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id034
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id035
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id036
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id037
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id038
  url: /providers/google-gemini/
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
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id041
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id042
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id043
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id044
  url: /providers/hubspot/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id045
  name: Klime
  slug: klime
  status: profiled
  tags: *id046
  url: /providers/klime/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id047
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id048
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id049
  name: LinkedIn Marketing API
  slug: linkedin-ads
  status: profiled
  tags: *id050
  url: /providers/linkedin-ads/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id051
  name: MaxMind GeoIP2
  slug: maxmind
  status: profiled
  tags: *id052
  url: /providers/maxmind/
- agent_band: agent-aware
  agent_readiness: 11.7
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id053
  name: Microsoft Advertising
  slug: microsoft-advertising
  status: profiled
  tags: *id054
  url: /providers/microsoft-advertising/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id055
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id056
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id057
  name: Modal
  slug: modal-labs
  status: profiled
  tags: *id058
  url: /providers/modal-labs/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id059
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id060
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id061
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id062
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id063
  name: Pinterest Ads
  slug: pinterest
  status: profiled
  tags: *id064
  url: /providers/pinterest/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id065
  name: Reddit Ads
  slug: reddit
  status: profiled
  tags: *id066
  url: /providers/reddit/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id067
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id068
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id069
  name: Slack
  slug: slack
  status: profiled
  tags: *id070
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id071
  name: Snapchat Ads
  slug: snapchat
  status: profiled
  tags: *id072
  url: /providers/snapchat/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id073
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id074
  url: /providers/snowflake/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id075
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id076
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id077
  name: TikTok Ads
  slug: tiktok-ads
  status: profiled
  tags: *id078
  url: /providers/tiktok-ads/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id079
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id080
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 60.5
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id081
  name: Unify
  slug: unify
  status: profiled
  tags: *id082
  url: /providers/unify/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id083
  name: WhatsApp Business
  slug: whatsapp
  status: profiled
  tags: *id084
  url: /providers/whatsapp/
siblings:
- name: Amplitude
  rows: 50
  url: /applications/web-analytics/amplitude/
- name: Google Analytics
  rows: 4
  url: /applications/web-analytics/google-analytics/
- name: Matomo
  rows: 18
  url: /applications/web-analytics/matomo/
- name: Mixpanel
  rows: 12
  url: /applications/web-analytics/mixpanel/
- name: Plausible
  rows: 16
  url: /applications/web-analytics/plausible/
- name: Umami
  rows: 4
  url: /applications/web-analytics/umami/
sitemap: true
title: 'PostHog: Web & Product Analytics reference app'
---
