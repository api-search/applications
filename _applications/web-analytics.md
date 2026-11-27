---
access: understanding
agent_layer:
- app: PostHog
  finding: ships a first-party MCP server; repo also carries mcp_store / mcp_analytics / webmcp products
  source: https://posthog.com/docs/model-context-protocol
  tier: declared
- app: PostHog
  finding: mcp Python SDK and anthropic/openai/mistral/gemini deps -- AI assistant built in
  source: https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
  tier: observed
- app: Umami
  finding: '@umami/mcp dependency and src/lib/mcp in repo; MCP docs page'
  source: https://umami.is/docs/mcp
  tier: declared
- app: Umami
  finding: '@umami/mcp in package.json'
  source: https://raw.githubusercontent.com/umami-software/umami/master/package.json
  tier: observed
- app: Matomo
  finding: 'AIProviders plugin: BYO LLM (Anthropic, OpenAI, Google, Bedrock, any OpenAI-compatible incl. Ollama); AIAgents plugin dir present'
  source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
  tier: observed
- app: Google Analytics
  finding: Google Analytics MCP server documented
  source: https://developers.google.com/analytics/devguides/MCP
  tier: declared
- app: Mixpanel
  finding: Mixpanel MCP server
  source: https://docs.mixpanel.com/docs/mcp
  tier: declared
- app: Amplitude
  finding: Amplitude MCP server
  source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
  tier: declared
apps:
- anchor: posthog
  counts:
    declared: 0
    observed: 42
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
    layer: common
    name: WhatsApp Business
    provider: whatsapp
    says: ships the WhatsApp Business SDK or integration code
    source: https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
    tier: observed
  kind: open-source-saas
  name: PostHog
  page: /applications/web-analytics/posthog/
  slug: posthog
  url: https://github.com/PostHog/posthog
- anchor: plausible
  counts:
    declared: 9
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
  - route: documentation
    url: https://plausible.io/docs/google-search-console-integration
  - route: documentation
    url: https://plausible.io/docs/integration-guides
  - route: source code
    url: https://github.com/plausible/analytics/blob/master/extra/lib/plausible/help_scout.ex
  - route: source code
    url: https://github.com/plausible/analytics/tree/master/lib/plausible
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
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
    source: https://github.com/plausible/analytics/tree/master/lib/plausible
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3770.30
      key: content-performance-analytics
      name: Content Performance Analytics
      url: /capabilities/content-performance-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Search Console
    provider: google-search-console
    says: ships the Google Search Console SDK or integration code
    source: https://github.com/plausible/analytics/tree/master/lib/plausible
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Help Scout
    provider: helpscout
    says: ships the Help Scout SDK or integration code
    source: https://github.com/plausible/analytics/blob/master/extra/lib/plausible/help_scout.ex
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: common
    name: Paddle
    provider: paddle
    says: ships the Paddle SDK or integration code
    source: https://github.com/plausible/analytics/tree/master/lib/plausible
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
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
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
    source: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ghost
    provider: ghost-org
    says: lists Ghost as an integration
    source: https://plausible.io/docs/integration-guides
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: domain
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://plausible.io/docs/integration-guides
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://plausible.io/docs/integration-guides
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
    name: Looker Studio (Data Studio)
    provider: looker-studio
    says: lists Looker Studio (Data Studio) as an integration
    source: https://plausible.io/docs/integration-guides
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
    source: https://plausible.io/docs/integration-guides
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://plausible.io/docs/integration-guides
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://plausible.io/docs/integration-guides
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://plausible.io/docs/integration-guides
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://plausible.io/docs/integration-guides
    tier: declared
  kind: open-source-saas
  name: Plausible
  page: /applications/web-analytics/plausible/
  slug: plausible
  url: https://github.com/plausible/analytics
- anchor: umami
  counts:
    declared: 3
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/umami-software/umami/master/package.json
  - route: documentation
    url: https://umami.is/docs/enable-cloudflare-headers
  - route: documentation
    url: https://umami.is/docs/google-tag-manager
  - route: documentation
    url: https://umami.is/docs/integrations
  - route: documentation
    url: https://umami.is/docs/mcp
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: MaxMind GeoIP2
    provider: maxmind
    says: ships the MaxMind GeoIP2 SDK or integration code
    source: https://raw.githubusercontent.com/umami-software/umami/master/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: Cloudflare
    provider: cloudflare
    says: lists Cloudflare as an integration
    source: https://umami.is/docs/enable-cloudflare-headers
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: domain
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://umami.is/docs/google-tag-manager
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://umami.is/docs/integrations
    tier: declared
  kind: open-source-saas
  name: Umami
  page: /applications/web-analytics/umami/
  slug: umami
  url: https://github.com/umami-software/umami
- anchor: matomo
  counts:
    declared: 12
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/composer.json
  - route: documentation
    url: https://matomo.org/integrations/
  - route: source code
    url: https://github.com/matomo-org/matomo/tree/5.x-dev/plugins/MobileMessaging/SMSProvider
  - route: source code
    url: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
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
    name: ASPSMS
    provider: aspsms
    says: ships the ASPSMS SDK or integration code
    source: https://github.com/matomo-org/matomo/tree/5.x-dev/plugins/MobileMessaging/SMSProvider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: MaxMind GeoIP2
    provider: maxmind
    says: ships the MaxMind GeoIP2 SDK or integration code
    source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
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
    name: Cloudflare
    provider: cloudflare
    says: lists Cloudflare as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: domain
    name: CookieYes
    provider: cookieyes
    says: lists CookieYes as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: domain
    name: Didomi
    provider: didomi
    says: lists Didomi as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: domain
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: domain
    name: OneTrust
    provider: onetrust
    says: lists OneTrust as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: domain
    name: Osano
    provider: osano
    says: lists Osano as an integration
    source: https://matomo.org/integrations/
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
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: domain
    name: Usercentrics
    provider: usercentrics
    says: lists Usercentrics as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://matomo.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://matomo.org/integrations/
    tier: declared
  kind: open-source-saas
  name: Matomo
  page: /applications/web-analytics/matomo/
  slug: matomo
  url: https://github.com/matomo-org/matomo
- anchor: google-analytics
  counts:
    declared: 3
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.giant/latest/
  - route: documentation
    url: https://developers.google.com/analytics/devguides/MCP
  - route: documentation
    url: https://support.google.com/analytics/answer/10737381
  - route: documentation
    url: https://support.google.com/analytics/answer/9379420
  - route: documentation
    url: https://support.google.com/analytics/answer/9823238
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Firebase (Analytics)
    provider: firebase
    says: ships the Firebase (Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.giant/latest/
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
    says: lists Google Ads as an integration
    source: https://support.google.com/analytics/answer/9379420
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
    source: https://support.google.com/analytics/answer/9823238
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3770.30
      key: content-performance-analytics
      name: Content Performance Analytics
      url: /capabilities/content-performance-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Search Console
    provider: google-search-console
    says: lists Google Search Console as an integration
    source: https://support.google.com/analytics/answer/10737381
    tier: declared
  kind: commercial
  name: Google Analytics
  page: /applications/web-analytics/google-analytics/
  slug: google-analytics
  url: https://analytics.google.com/
- anchor: mixpanel
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: documentation
    url: https://docs.mixpanel.com/docs/mcp
  - route: integrations page
    url: https://mixpanel.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Apphud
    provider: apphud
    says: lists Apphud as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.20.10
      key: BC-4280.20.10
      name: Telemetry Schema Governance
      url: /capabilities/telemetry-quality-governance/
      via_parent: Telemetry Quality & Governance
    credit: null
    layer: domain
    name: Avo (avo.app tracking plans)
    provider: avo-app
    says: lists Avo (avo.app tracking plans) as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1300.10
      key: customer-onboarding-management
      name: Customer Onboarding Management
      url: /capabilities/customer-onboarding-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chameleon
    provider: chameleon
    says: lists Chameleon as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: ChurnZero
    provider: churnzero
    says: lists ChurnZero as an integration
    source: https://mixpanel.com/integrations
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
    name: Databox
    provider: databox
    says: lists Databox as an integration
    source: https://mixpanel.com/integrations
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
    source: https://mixpanel.com/integrations
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
    name: Flagsmith
    provider: flagsmith
    says: lists Flagsmith as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Insider
    provider: insider
    says: lists Insider as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make (formerly Integromat)
    provider: make
    says: lists Make (formerly Integromat) as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: MoEngage
    provider: moengage
    says: lists MoEngage as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Pushwoosh
    provider: pushwoosh
    says: lists Pushwoosh as an integration
    source: https://mixpanel.com/integrations
    tier: declared
  kind: commercial
  name: Mixpanel
  page: /applications/web-analytics/mixpanel/
  slug: mixpanel
  url: https://mixpanel.com/
- anchor: amplitude
  counts:
    declared: 50
    observed: 0
  evidence:
  - route: documentation
    url: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
  - route: integrations page
    url: https://amplitude.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Adjust
    provider: adjust
    says: lists Adjust as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Airship
    provider: airship
    says: lists Airship as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Amazon Kinesis Data Firehose
    provider: amazon-kinesis-firehose
    says: lists Amazon Kinesis Data Firehose as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1300.10
      key: customer-onboarding-management
      name: Customer Onboarding Management
      url: /capabilities/customer-onboarding-management/
      via_parent: null
    credit: null
    layer: domain
    name: Appcues
    provider: appcues
    says: lists Appcues as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: lists AppsFlyer as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: lists Azure Blob Storage as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Branch (branch.io)
    provider: branch-io
    says: lists Branch (branch.io) as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1300.10
      key: customer-onboarding-management
      name: Customer Onboarding Management
      url: /capabilities/customer-onboarding-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chameleon
    provider: chameleon
    says: lists Chameleon as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Customer.io
    provider: customer-io
    says: lists Customer.io as an integration
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
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
    name: Fivetran
    provider: fivetran
    says: lists Fivetran as an integration
    source: https://amplitude.com/integrations
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
    name: Flagsmith
    provider: flagsmith
    says: lists Flagsmith as an integration
    source: https://amplitude.com/integrations
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
    name: Fullstory
    provider: fullstory
    says: lists Fullstory as an integration
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Google Cloud Pub/Sub
    provider: google-cloud-pubsub
    says: lists Google Cloud Pub/Sub as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: domain
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://amplitude.com/integrations
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
    name: Hightouch
    provider: hightouch
    says: lists Hightouch as an integration
    source: https://amplitude.com/integrations
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
    name: Hotjar
    provider: hotjar
    says: lists Hotjar as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Iterable
    provider: iterable
    says: lists Iterable as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: MoEngage
    provider: moengage
    says: lists MoEngage as an integration
    source: https://amplitude.com/integrations
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
    name: mParticle
    provider: mparticle
    says: lists mParticle as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: OneSignal
    provider: onesignal
    says: lists OneSignal as an integration
    source: https://amplitude.com/integrations
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
    name: Optimizely
    provider: optimizely
    says: lists Optimizely as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: domain
    name: Osano
    provider: osano
    says: lists Osano as an integration
    source: https://amplitude.com/integrations
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
    name: RudderStack
    provider: rudderstack
    says: lists RudderStack as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: lists Salesforce Marketing Cloud as an integration
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Singular
    provider: singular
    says: lists Singular as an integration
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://amplitude.com/integrations
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
    name: Snapchat Ads
    provider: snapchat
    says: lists Snapchat Ads as an integration
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
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
    name: Statsig
    provider: statsig
    says: lists Statsig as an integration
    source: https://amplitude.com/integrations
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
    name: Tealium
    provider: tealium
    says: lists Tealium as an integration
    source: https://amplitude.com/integrations
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
    name: TikTok Ads
    provider: tiktok-ads
    says: lists TikTok Ads as an integration
    source: https://amplitude.com/integrations
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
    source: https://amplitude.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://amplitude.com/integrations
    tier: declared
  kind: commercial
  name: Amplitude
  page: /applications/web-analytics/amplitude/
  slug: amplitude
  url: https://amplitude.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: web-analytics
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Analytics
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#analytics
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Analytics & Data
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Store management
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Analytics
  store: zapier
  url: https://zapier.com/apps
name: Web & Product Analytics
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
  why: warehouse export/import and dashboarding
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: domain
  why: tag managers deploy the tracker
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ad-spend import and conversion export to ad networks; mobile attribution
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: cohort sync to messaging and marketing automation
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the category itself: event, pageview and session collection'
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: website/CMS platforms the tracker installs into
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: CRM sync of product signals
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: domain
  why: IP geolocation of visitors
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: event export / import files
- capability:
    attribution: Turbo EA
    id: BC-1300.10
    key: customer-onboarding-management
    name: Customer Onboarding Management
    url: /capabilities/customer-onboarding-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: in-app guides triggered by cohorts
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: common
  why: LLM features (insights, assistants)
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: alerts and digests to team chat
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: common
  why: billing for the SaaS edition; revenue analytics source
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: bot protection
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring / alert routing
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: report and login email
- capability:
    attribution: Turbo EA
    id: BC-3770.30
    key: content-performance-analytics
    name: Content Performance Analytics
    url: /capabilities/content-performance-analytics/
    via_parent: null
  fit: nearest
  layer: domain
  why: search query / SEO performance joined to traffic
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support tooling
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  fit: exact
  layer: domain
  why: consent managers gating the tracker
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: domain
  why: experiments and flags joined to analytics
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: CDP / reverse-ETL in and out of the analytics store
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  fit: nearest
  layer: common
  why: issue creation from analytics events
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: subscription revenue events
- capability:
    attribution: Turbo EA
    id: BC-4280.20.10
    key: BC-4280.20.10
    name: Telemetry Schema Governance
    url: /capabilities/telemetry-quality-governance/
    via_parent: Telemetry Quality & Governance
  fit: exact
  layer: domain
  why: tracking-plan / event-schema governance
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: event streaming transports
- capability:
    attribution: Turbo EA
    id: BC-4220.30.10
    key: BC-4220.30.10
    name: On-Call Rotation Management
    url: /capabilities/incident-response-management/
    via_parent: Incident Response Management
  fit: exact
  layer: common
  why: PagerDuty (On-Call Rotation Management)
stack:
- capabilities:
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
      - Amplitude
      - Google Analytics
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://support.google.com/analytics/answer/9379420
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
      - Amplitude
      - Mixpanel
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook / Meta Ads
      slug: facebook
      sources:
      - https://amplitude.com/integrations
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Amplitude
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Snapchat Ads
      slug: snapchat
      sources:
      - https://amplitude.com/integrations
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Advertising
      - Augmented Reality
      - Marketing
      - Messaging
      tier: observed
      url: /providers/snapchat/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Amplitude
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        status: none
      name: TikTok Ads
      slug: tiktok-ads
      sources:
      - https://amplitude.com/integrations
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Ad Campaigns
      - Advertising
      - Marketing
      - Social Media
      tier: observed
      url: /providers/tiktok-ads/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        status: none
      name: LinkedIn Marketing API
      slug: linkedin-ads
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Advertising
      - Lead Generation
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin-ads/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit Ads
      slug: reddit
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest Ads
      slug: pinterest
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Image
      - Social
      - Social Media
      - Video
      tier: observed
      url: /providers/pinterest/
    - agent_band: agent-aware
      agent_readiness: 11.7
      apps:
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        status: none
      name: Microsoft Advertising
      slug: microsoft-advertising
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Advertising
      - Analytics
      - Bing Ads
      - Bulk Operations
      tier: observed
      url: /providers/microsoft-advertising/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Amplitude
      - Google Analytics
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://support.google.com/analytics/answer/9823238
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: observed
      url: /providers/google-bigquery/
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Amplitude
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
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
      - Amplitude
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Dagster+ (Dagster Cloud)
      slug: dagster
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Data Engineering
      - Data Orchestration
      - Data Pipeline
      - ETL
      tier: observed
      url: /providers/dagster/
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Plausible
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        status: none
      name: Looker Studio (Data Studio)
      slug: looker-studio
      sources:
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Visualization
      tier: declared
      url: /providers/looker-studio/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Mixpanel
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/databox/databox-mcp
        status: verified
      name: Databox
      slug: databox
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Data Integration
      tier: declared
      url: /providers/databox/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Amplitude
      - Matomo
      - Plausible
      - Umami
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://amplitude.com/integrations
      - https://matomo.org/integrations/
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-native
      agent_readiness: 48.5
      apps:
      - Matomo
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 68.7
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://matomo.org/integrations/
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 62.5
      apps:
      - Matomo
      - Plausible
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://developers.webflow.com/mcp/reference/overview
        status: verified
      name: Webflow
      slug: webflow
      sources:
      - https://matomo.org/integrations/
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - No-Code
      - Web Development
      tier: declared
      url: /providers/webflow/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Matomo
      - Plausible
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://matomo.org/integrations/
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: Ghost
      slug: ghost-org
      sources:
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - Membership
      - Newsletters
      - Publishing
      - Subscription
      tier: declared
      url: /providers/ghost-org/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 79.1
      mcp:
        source: https://github.com/rudderlabs/rudderstack-mcp
        status: verified
      name: RudderStack
      slug: rudderstack
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - CDP
      - Customer Data Platform
      - Data Pipeline
      - Open Source
      tier: declared
      url: /providers/rudderstack/
    - agent_band: agent-ready
      agent_readiness: 62.8
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://hightouch.com/docs/ai-integrations/mcp
        status: documented
      name: Hightouch
      slug: hightouch
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Audience Management
      - CDP
      - Data Activation
      - Reverse ETL
      tier: declared
      url: /providers/hightouch/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
        status: documented
      name: Tealium
      slug: tealium
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - AudienceStream
      - CDP
      - Customer Data Platform
      - Tag Management
      tier: declared
      url: /providers/tealium/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Amplitude
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: mParticle
      slug: mparticle
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Analytics
      - CDP
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/mparticle/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Amplitude
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Amplitude
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        source: https://github.com/fivetran/fivetran-mcp
        status: verified
      name: Fivetran
      slug: fivetran
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Connectors
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/fivetran/
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Amplitude
      - Matomo
      band: strong
      in_catalog: true
      kin_score: 54.3
      mcp:
        status: none
      name: Osano
      slug: osano
      sources:
      - https://amplitude.com/integrations
      - https://matomo.org/integrations/
      status: profiled
      tags:
      - Company
      - Compliance
      - Consent Management
      - Privacy
      tier: declared
      url: /providers/osano/
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - Matomo
      band: exemplar
      in_catalog: true
      kin_score: 78.8
      mcp:
        status: none
      name: Didomi
      slug: didomi
      sources:
      - https://matomo.org/integrations/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - CCPA
      - CMP
      tier: declared
      url: /providers/didomi/
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - Matomo
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: OneTrust
      slug: onetrust
      sources:
      - https://matomo.org/integrations/
      status: profiled
      tags:
      - Compliance
      - Consent
      - GRC
      - Privacy
      tier: declared
      url: /providers/onetrust/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Matomo
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        status: none
      name: Usercentrics
      slug: usercentrics
      sources:
      - https://matomo.org/integrations/
      status: profiled
      tags:
      - CMP
      - Compliance
      - Consent
      - Privacy
      tier: declared
      url: /providers/usercentrics/
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Matomo
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: none
      name: CookieYes
      slug: cookieyes
      sources:
      - https://matomo.org/integrations/
      status: profiled
      tags:
      - Company
      - Consent Management
      - GDPR
      - Privacy
      tier: declared
      url: /providers/cookieyes/
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
      - Amplitude
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://amplitude.com/integrations
      - https://github.com/plausible/analytics/tree/master/lib/plausible
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Google Analytics
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Analytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.giant/latest/
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 16.3
      apps:
      - PostHog
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Accoil
      slug: accoil
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Customer Success
      - Expansion
      - Playbooks
      - Retention
      tier: observed
      url: /providers/accoil/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Amplitude
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: Fullstory
      slug: fullstory
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/fullstory/
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - Amplitude
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Hotjar
      slug: hotjar
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Analytics
      - Personalization
      - Surveys
      - Tracking
      tier: declared
      url: /providers/hotjar/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Amplitude
      - Mixpanel
      band: exemplar
      in_catalog: true
      kin_score: 79.4
      mcp:
        source: https://github.com/Flagsmith/flagsmith-mcp
        status: verified
      name: Flagsmith
      slug: flagsmith
      sources:
      - https://amplitude.com/integrations
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - A/B Testing
      - Feature Flags
      - Release Management
      - Remote Config
      tier: declared
      url: /providers/flagsmith/
    - agent_band: agent-ready
      agent_readiness: 59.7
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 84.5
      mcp:
        source: https://launchdarkly.com/docs/home/getting-started/mcp
        status: verified
      name: LaunchDarkly
      slug: launchdarkly
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Observability
      tier: declared
      url: /providers/launchdarkly/
    - agent_band: agent-ready
      agent_readiness: 61.6
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: declared
      url: /providers/optimizely/
    - agent_band: agent-ready
      agent_readiness: 59.5
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 75.7
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=statsig
        status: verified
      name: Statsig
      slug: statsig
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - A/B Testing
      - Experimentation
      - Feature Flags
      - Product Analytics
      tier: declared
      url: /providers/statsig/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Amplitude
      - Matomo
      - Plausible
      - PostHog
      - Umami
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://amplitude.com/integrations
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      - https://matomo.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-1300.10
      key: customer-onboarding-management
      name: Customer Onboarding Management
      url: /capabilities/customer-onboarding-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Amplitude
      - PostHog
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        status: none
      name: Appcues
      slug: appcues
      sources:
      - https://amplitude.com/integrations
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Analytics
      - In-App Guidance
      - Onboarding
      - Product
      tier: observed
      url: /providers/appcues/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Amplitude
      - Mixpanel
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: none
      name: Chameleon
      slug: chameleon
      sources:
      - https://amplitude.com/integrations
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - In-App Guidance
      - Onboarding
      - Product
      - Surveys
      tier: declared
      url: /providers/chameleon/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: declared
      url: /providers/appsflyer/
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Amplitude
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: declared
      url: /providers/singular/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Amplitude
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch (branch.io)
      slug: branch-io
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/branch-io/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Amplitude
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: declared
      url: /providers/adjust/
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
      - Amplitude
      - Matomo
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://amplitude.com/integrations
      - https://matomo.org/integrations/
      - https://plausible.io/docs/integration-guides
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Matomo
      - PostHog
      - Umami
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind GeoIP2
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/composer.json
      - https://raw.githubusercontent.com/umami-software/umami/master/package.json
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: Turbo EA
      id: BC-3770.30
      key: content-performance-analytics
      name: Content Performance Analytics
      url: /capabilities/content-performance-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Google Analytics
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Search Console
      slug: google-search-console
      sources:
      - https://github.com/plausible/analytics/tree/master/lib/plausible
      - https://support.google.com/analytics/answer/10737381
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: observed
      url: /providers/google-search-console/
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Mixpanel
      band: developing
      in_catalog: true
      kin_score: 45.3
      mcp:
        status: none
      name: Apphud
      slug: apphud
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Analytics
      - Mobile
      - SDK
      - Subscription
      tier: declared
      url: /providers/apphud/
  - capability:
      attribution: Turbo EA
      id: BC-4280.20.10
      key: BC-4280.20.10
      name: Telemetry Schema Governance
      url: /capabilities/telemetry-quality-governance/
      via_parent: Telemetry Quality & Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Mixpanel
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        source: https://github.com/avohq/avo-mcp
        status: verified
      name: Avo (avo.app tracking plans)
      slug: avo-app
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Data Governance
      tier: declared
      url: /providers/avo-app/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Amplitude
      - Mixpanel
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://amplitude.com/integrations
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
    - agent_band: agent-native
      agent_readiness: 65.1
      apps:
      - Amplitude
      - Mixpanel
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: MoEngage
      slug: moengage
      sources:
      - https://amplitude.com/integrations
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Customer Data Platform
      - Customer Engagement
      - Marketing Automation
      - Push Notifications
      tier: declared
      url: /providers/moengage/
    - agent_band: agent-ready
      agent_readiness: 59.6
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        source: https://github.com/beehiiv/agents
        status: verified
      name: beehiiv
      slug: beehiiv
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Creators
      - Email
      - Newsletters
      - Subscription
      tier: observed
      url: /providers/beehiiv/
    - agent_band: agent-ready
      agent_readiness: 70.1
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 85.9
      mcp:
        source: https://github.com/customerio/claude-plugin
        status: verified
      name: Customer.io
      slug: customer-io
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Behavioral Data
      - Broadcast
      - CDP
      - Campaigns
      tier: declared
      url: /providers/customer-io/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: declared
      url: /providers/salesforce-marketing-cloud/
    - agent_band: agent-native
      agent_readiness: 70.1
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp:
        source: https://github.com/OneSignal/onesignal-ai-skills
        status: documented
      name: OneSignal
      slug: onesignal
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Email
      - Notification
      - Push
      - SMS
      tier: declared
      url: /providers/onesignal/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/Iterable/mcp-server
        status: verified
      name: Iterable
      slug: iterable
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Cross-Channel Messaging
      - Customer Engagement
      - Email
      - Marketing Automation
      tier: declared
      url: /providers/iterable/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Amplitude
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - Mixpanel
      band: strong
      in_catalog: true
      kin_score: 56.1
      mcp:
        status: none
      name: Insider
      slug: insider
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Company
      - Customer Data Platform
      - Customer Engagement
      - Personalization
      tier: declared
      url: /providers/insider/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Amplitude
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Airship
      slug: airship
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Email
      - Mobile
      - Notification
      - Push
      tier: declared
      url: /providers/airship/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Mixpanel
      band: emerging
      in_catalog: true
      kin_score: 22.0
      mcp:
        status: none
      name: Pushwoosh
      slug: pushwoosh
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Email
      - Notification
      - Push
      - SMS
      tier: declared
      url: /providers/pushwoosh/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mixpanel
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: none
      name: ChurnZero
      slug: churnzero
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Customer Success
      - Software-as-a-Service
      tier: declared
      url: /providers/churnzero/
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Matomo
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Matomo
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Matomo
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
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
      - Matomo
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
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
      - Amplitude
      - Plausible
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://amplitude.com/integrations
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      - https://plausible.io/docs/integration-guides
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
      - Amplitude
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 58.1
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://developer.close.com/mcp
        status: verified
      name: Close
      slug: close
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - CRM
      - Calling
      - Inside Sales
      - Sales Engagement
      tier: observed
      url: /providers/close/
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        status: none
      name: Unify
      slug: unify
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Go-To-Market
      - Marketing
      - Outbound
      - Sales
      tier: observed
      url: /providers/unify/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - PostHog
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: unknown
      name: Klime
      slug: klime
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Productivity
      - Software-as-a-Service
      tier: observed
      url: /providers/klime/
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
      - Amplitude
      - Plausible
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      - https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Amplitude
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: declared
      url: /providers/gcp-cloud-storage/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Amplitude
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://amplitude.com/integrations
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: observed
      url: /providers/clickup/
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Plausible
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://github.com/plausible/analytics/blob/master/extra/lib/plausible/help_scout.ex
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: observed
      url: /providers/helpscout/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Amplitude
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        status: none
      name: Amazon Kinesis Data Firehose
      slug: amazon-kinesis-firehose
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Data Delivery
      - Streaming
      tier: declared
      url: /providers/amazon-kinesis-firehose/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Amplitude
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: declared
      url: /providers/google-cloud-pubsub/
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
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Matomo
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: unknown
      name: ASPSMS
      slug: aspsms
      sources:
      - https://github.com/matomo-org/matomo/tree/5.x-dev/plugins/MobileMessaging/SMSProvider
      status: profiled
      tags:
      - Business
      - Communications
      - Messaging
      - SMS
      tier: observed
      url: /providers/aspsms/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Plausible
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        source: https://github.com/PaddleHQ/paddle-mcp-server
        status: verified
      name: Paddle
      slug: paddle
      sources:
      - https://github.com/plausible/analytics/tree/master/lib/plausible
      status: profiled
      tags:
      - Billing
      - Merchant of Record
      - Payments
      - Subscription
      tier: observed
      url: /providers/paddle/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Amplitude
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://amplitude.com/integrations
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: declared
      url: /providers/sendgrid/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.10
      key: AE-100.60.10
      name: Agent Evaluation & Testing
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.7
      apps:
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        source: https://www.braintrust.dev/docs/integrations/developer-tools/mcp
        status: verified
      name: Braintrust
      slug: braintrust
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Evaluation
      - LLM
      - Observability
      tier: observed
      url: /providers/braintrust/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id001
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/frontend/package.json
      status: profiled
      tags: &id002
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - PostHog
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        status: none
      name: Modal
      slug: modal-labs
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - AI Infrastructure
      - Compute
      - GPU
      - Serverless
      tier: observed
      url: /providers/modal-labs/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Umami
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id001
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://umami.is/docs/enable-cloudflare-headers
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/cloudflare/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Matomo
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id001
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://matomo.org/integrations/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/cloudflare/
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
      - Plausible
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30.10
      key: BC-4220.30.10
      name: On-Call Rotation Management
      url: /capabilities/incident-response-management/
      via_parent: Incident Response Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - PostHog
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: observed
      url: /providers/pagerduty/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 83.2
      mcp:
        source: https://github.com/elevenlabs/elevenlabs-mcp
        status: verified
      name: ElevenLabs
      slug: elevenlabs
      sources:
      - https://raw.githubusercontent.com/PostHog/posthog/master/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/elevenlabs/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - PostHog
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp Business
      slug: whatsapp
      sources:
      - https://github.com/PostHog/posthog/tree/master/nodejs/src/cdp/templates/_destinations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Mixpanel
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make (formerly Integromat)
      slug: make
      sources:
      - https://mixpanel.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 52
  distinct_providers: 102
  in_catalog: 102
  mcp:
    documented: 5
    none: 43
    unchecked: 0
    verified: 52
  mcp_verified: 52
  mean_kin_score: 61.4
  observed: 50
  queued: 0
  reference_apps: 7
title: 'Web & Product Analytics: application blueprint'
---
