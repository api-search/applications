---
app: Formbricks
app_slug: formbricks
app_url: https://github.com/formbricks/formbricks
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Cube
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: domain
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Notion
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.20
  key: AE-160.20
  layer: common
  name: Authorization for Apps
  providers:
  - AuthZed
  url: /capabilities/authorization-for-apps/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Brevo
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Azure AI / Microsoft Foundry
  - Google Gemini
  url: /capabilities/model-inference/
  via_parent: Model Inference
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
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
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-170.30.40
  key: AE-170.30.40
  layer: common
  name: Stock Media & Royalty-Free Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Azure AD / Entra ID
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-170.70.20
  key: AE-170.70.20
  layer: common
  name: Translation Management & Localization
  providers:
  - Lingo.dev
  url: /capabilities/content-management/
  via_parent: Content Management
category:
  id: customer-feedback-nps
  name: Customer Feedback & NPS
  url: /applications/customer-feedback-nps/
counts:
  declared: 0
  observed: 22
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
- route: source code
  url: https://github.com/formbricks/formbricks/blob/main/.env.example
- route: source code
  url: https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
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
  source: https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
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
  layer: common
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
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
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
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
    mcp: &id007
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.20
    key: AE-160.20
    name: Authorization for Apps
    url: /capabilities/authorization-for-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id009
      source: https://github.com/authzed/mcp-server-reference
      status: verified
    slug: authzed
    status: profiled
    tags: &id010
    - Access Control
    - Authorization
    - Permissions
    - Zanzibar
    url: /providers/authzed/
  layer: common
  name: AuthZed
  provider: authzed
  says: ships the AuthZed SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id011
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id012
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Azure AD / Entra ID
  provider: microsoft-entra
  says: ships the Azure AD / Entra ID SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
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
    agent_readiness: 29.9
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: common
  name: Azure AI / Microsoft Foundry
  provider: microsoft-azure-openai
  says: ships the Azure AI / Microsoft Foundry SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 81.3
    mcp: &id015
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id016
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
  layer: common
  name: Brevo
  provider: brevo
  says: ships the Brevo SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
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
    agent_band: agent-aware
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id017
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id018
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
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
    agent_readiness: 15.7
    band: emerging
    in_catalog: true
    kin_score: 20.9
    mcp: &id019
      source: https://cube.dev/docs/product/apis-integrations/mcp-server
      status: verified
    slug: cube
    status: profiled
    tags: &id020
    - Business Intelligence
    - Embedded Analytics
    - GraphQL
    - Semantic Layer
    url: /providers/cube/
  layer: domain
  name: Cube
  provider: cube
  says: ships the Cube SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id021
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id022
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
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
  layer: common
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
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
    mcp: &id025
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id026
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
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
    mcp: &id027
      status: none
    slug: google-sheets
    status: profiled
    tags: &id028
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id029
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id030
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id031
      source: https://lingo.dev/en/docs/mcp
      status: verified
    slug: lingo-dev
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Localization
    - Translation
    - i18n
    url: /providers/lingo-dev/
  layer: common
  name: Lingo.dev
  provider: lingo-dev
  says: ships the Lingo.dev SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id033
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id034
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: ships the Notion SDK or integration code
  source: https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
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
    mcp: &id035
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id036
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
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
    mcp: &id037
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id038
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
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
    mcp: &id039
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id040
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
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
    mcp: &id041
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id042
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id043
      status: none
    slug: unsplash
    status: profiled
    tags: &id044
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: common
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://github.com/formbricks/formbricks/blob/main/.env.example
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/customer-feedback-nps/formbricks/
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
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id003
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
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
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id007
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id008
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id009
  name: AuthZed
  slug: authzed
  status: profiled
  tags: *id010
  url: /providers/authzed/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id011
  name: Azure AD / Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id012
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id013
  name: Azure AI / Microsoft Foundry
  slug: microsoft-azure-openai
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-openai/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id015
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id016
  url: /providers/brevo/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id017
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id018
  url: /providers/cloudflare-turnstile/
- agent_band: agent-aware
  agent_readiness: 15.7
  band: emerging
  in_catalog: true
  kin_score: 20.9
  mcp: *id019
  name: Cube
  slug: cube
  status: profiled
  tags: *id020
  url: /providers/cube/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id021
  name: GitHub
  slug: github
  status: profiled
  tags: *id022
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id023
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id024
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id025
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id026
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id027
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id028
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id029
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id030
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id031
  name: Lingo.dev
  slug: lingo-dev
  status: profiled
  tags: *id032
  url: /providers/lingo-dev/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id033
  name: Notion
  slug: notion
  status: profiled
  tags: *id034
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id035
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id036
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id037
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id038
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id039
  name: Slack
  slug: slack
  status: profiled
  tags: *id040
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id041
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id042
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id043
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id044
  url: /providers/unsplash/
siblings:
- name: Canny
  rows: 18
  url: /applications/customer-feedback-nps/canny/
- name: ClearFlask
  rows: 15
  url: /applications/customer-feedback-nps/clearflask/
- name: Fider
  rows: 8
  url: /applications/customer-feedback-nps/fider/
- name: Retently
  rows: 17
  url: /applications/customer-feedback-nps/retently/
- name: SurveyMonkey
  rows: 6
  url: /applications/customer-feedback-nps/surveymonkey/
- name: Survicate
  rows: 25
  url: /applications/customer-feedback-nps/survicate/
sitemap: true
title: 'Formbricks: Customer Feedback & NPS reference app'
---
