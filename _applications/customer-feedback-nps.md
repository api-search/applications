---
access: understanding
agent_layer:
- app: Formbricks
  finding: ships its own MCP server in the web app (@modelcontextprotocol/server, mcp-handler) and @posthog/mcp
  source: https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
  tier: observed
- app: ClearFlask
  finding: bring-your-own OpenAI key through langchain4j for AI features
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
apps:
- anchor: formbricks
  counts:
    declared: 0
    observed: 22
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
    layer: common
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/formbricks/formbricks/blob/main/.env.example
    tier: observed
  kind: open-source-saas
  name: Formbricks
  page: /applications/customer-feedback-nps/formbricks/
  slug: formbricks
  url: https://github.com/formbricks/formbricks
- anchor: fider
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/getfider/fider/blob/main/go.mod
  - route: source code
    url: https://github.com/getfider/fider/blob/main/.example.env
  - route: source code
    url: https://github.com/getfider/fider/tree/main/app/services
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
    source: https://github.com/getfider/fider/tree/main/app/services
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
    source: https://github.com/getfider/fider/tree/main/app/services
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/getfider/fider/blob/main/.example.env
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/getfider/fider/blob/main/.example.env
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
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/getfider/fider/blob/main/.example.env
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
    source: https://github.com/getfider/fider/tree/main/app/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/getfider/fider/blob/main/go.mod
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
    name: Userlist
    provider: userlist
    says: ships the Userlist SDK or integration code
    source: https://github.com/getfider/fider/tree/main/app/services
    tier: observed
  kind: self-hosted
  name: Fider
  page: /applications/customer-feedback-nps/fider/
  slug: fider
  url: https://github.com/getfider/fider
- anchor: clearflask
  counts:
    declared: 0
    observed: 15
  evidence:
  - route: dependency manifest
    url: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  - route: source code
    url: https://github.com/clearflask/clearflask/tree/master/clearflask-server
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: ships the Amazon DynamoDB SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon Route 53
    provider: amazon-route-53
    says: ships the Amazon Route 53 SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
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
    source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
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
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    credit: null
    layer: common
    name: Castle
    provider: castle
    says: ships the Castle SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
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
    name: Kill Bill
    provider: killbill
    says: ships the Kill Bill SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    credit: null
    layer: common
    name: Let's Encrypt
    provider: lets-encrypt
    says: ships the Let's Encrypt SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
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
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
    tier: observed
  kind: self-hosted
  name: ClearFlask
  page: /applications/customer-feedback-nps/clearflask/
  slug: clearflask
  url: https://github.com/clearflask/clearflask
- anchor: canny
  counts:
    declared: 18
    observed: 0
  evidence:
  - route: integrations page
    url: https://canny.io/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: lists Azure DevOps as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://canny.io/integrations
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
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://canny.io/integrations
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
    source: https://canny.io/integrations
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
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: lists Microsoft Entra ID as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: OneLogin
    provider: onelogin
    says: lists OneLogin as an integration
    source: https://canny.io/integrations
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
    source: https://canny.io/integrations
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
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://canny.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://canny.io/integrations
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
    source: https://canny.io/integrations
    tier: declared
  kind: commercial
  name: Canny
  page: /applications/customer-feedback-nps/canny/
  slug: canny
  url: https://canny.io
- anchor: survicate
  counts:
    declared: 25
    observed: 0
  evidence:
  - route: integrations page
    url: https://survicate.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://survicate.com/integrations/
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
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Customer.io
    provider: customer-io
    says: lists Customer.io as an integration
    source: https://survicate.com/integrations/
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
    name: Fullstory
    provider: fullstory
    says: lists Fullstory as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Gong
    provider: gong
    says: lists Gong as an integration
    source: https://survicate.com/integrations/
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
    source: https://survicate.com/integrations/
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
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Google Reviews
    provider: google-business-profile
    says: lists Google Reviews as an integration
    source: https://survicate.com/integrations/
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
    source: https://survicate.com/integrations/
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
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Iterable
    provider: iterable
    says: lists Iterable as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://survicate.com/integrations/
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
    name: LiveChat
    provider: livechat
    says: lists LiveChat as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://survicate.com/integrations/
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
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    credit: null
    layer: domain
    name: Productboard
    provider: productboard
    says: lists Productboard as an integration
    source: https://survicate.com/integrations/
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
    source: https://survicate.com/integrations/
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
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://survicate.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: tl;dv
    provider: tldv
    says: lists tl;dv as an integration
    source: https://survicate.com/integrations/
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
    name: UXCam
    provider: uxcam
    says: lists UXCam as an integration
    source: https://survicate.com/integrations/
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
    source: https://survicate.com/integrations/
    tier: declared
  kind: commercial
  name: Survicate
  page: /applications/customer-feedback-nps/survicate/
  slug: survicate
  url: https://survicate.com
- anchor: retently
  counts:
    declared: 17
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.retently.com/integrations/
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
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
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
    name: Gorgias
    provider: gorgias
    says: lists Gorgias as an integration
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://www.retently.com/integrations/
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
    name: Kustomer
    provider: kustomer
    says: lists Kustomer as an integration
    source: https://www.retently.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.retently.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Okendo
    provider: okendo
    says: lists Okendo as an integration
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
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
    name: Richpanel
    provider: richpanel
    says: lists Richpanel as an integration
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
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
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.retently.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Yotpo
    provider: yotpo
    says: lists Yotpo as an integration
    source: https://www.retently.com/integrations/
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
    source: https://www.retently.com/integrations/
    tier: declared
  kind: commercial
  name: Retently
  page: /applications/customer-feedback-nps/retently/
  slug: retently
  url: https://www.retently.com
- anchor: surveymonkey
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Audience Studio (Krux)
    provider: salesforce-marketing-cloud
    says: ships the Audience Studio (Krux) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Crashlytics
    provider: firebase
    says: ships the Google Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  kind: commercial
  name: SurveyMonkey
  page: /applications/customer-feedback-nps/surveymonkey/
  slug: surveymonkey
  url: https://www.surveymonkey.com
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: customer-feedback-nps
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Customer Feedback Software
  store: g2
  url: https://www.g2.com/categories/customer-feedback
- category: Net Promoter Score (NPS) Software
  store: g2
  url: https://www.g2.com/categories/net-promoter-score-nps
- category: Customer Feedback Software
  store: capterra
  url: https://www.capterra.com/customer-feedback-software/
- category: Polls and Events
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#polls-and-events
- category: Surveys
  store: shopify-app-store
  url: https://apps.shopify.com/categories/store-management-support-surveys
- category: Surveys & Feedback
  store: zendesk-marketplace
  url: https://www.zendesk.com/marketplace/apps/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
name: Customer Feedback & NPS
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: domain
  why: new-response and NPS alerts into Slack, Teams and Discord channels (6 of 7 apps)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: in-app survey targeting by product events, and the apps own telemetry
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: SaaS billing for hosted editions
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring and crash reporting
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: object storage for uploads; no generic object-storage capability
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: transactional email for survey invitations and notifications
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  fit: exact
  layer: domain
  why: feedback boards push requests into issue trackers and roadmaps (Jira, GitHub, Linear, Productboard)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: Segment as the identity and event pipe for targeting surveys
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: NPS scores and feedback written onto CRM contacts and deals
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ticket-triggered CSAT/NPS and feedback captured from helpdesk conversations
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: domain
  why: survey triggers and NPS segments sent to lifecycle-messaging platforms
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in for respondents and admins
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: workforce SSO for admin teams
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: response analytics and warehouse export (Cube, BigQuery)
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: lifecycle/marketing email lists fed from product signups
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: LLM sentiment, emotion, theme and translation enrichment of open-text responses
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: domain
  why: promoters routed to public review platforms (Google Reviews, Okendo, Yotpo)
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: response sync to spreadsheets and no-code databases (Formbricks)
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: response sync to Notion
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: bot protection on public survey and feedback forms
- capability:
    attribution: API Evangelist extension
    id: AE-160.20
    key: AE-160.20
    name: Authorization for Apps
    url: /capabilities/authorization-for-apps/
    via_parent: null
  fit: exact
  layer: common
  why: fine-grained permissions (AuthZed)
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: stock imagery for survey backgrounds
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: common
  why: UI localization pipeline
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: full-text search over ideas and comments
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: managed operational database
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: custom-domain DNS for hosted feedback portals
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: common
  why: self-hosted subscription billing engine (Kill Bill)
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  fit: exact
  layer: common
  why: account-abuse checks on public feedback portals (Castle)
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  fit: exact
  layer: common
  why: TLS certificates for custom domains
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: call and meeting recordings mined as feedback (Gong, tl;dv)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: post-purchase NPS triggered from storefront orders
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile install attribution
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: audience data management (DMP) in the mobile app
stack:
- capabilities:
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
      - Canny
      - Retently
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Canny
      - Retently
      - Survicate
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Retently
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Gladly
      slug: gladly
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - AI Customer Service
      - Contact Center
      - Customer Experience
      - Customer Service
      tier: declared
      url: /providers/gladly/
    - agent_band: agent-aware
      agent_readiness: 25.0
      apps:
      - Retently
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        status: unchecked
      name: Richpanel
      slug: richpanel
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - AI Support
      - Automation
      - E-Commerce
      - Help Desk
      tier: declared
      url: /providers/richpanel/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Retently
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/gorgias/mcp-cookbook
        status: verified
      name: Gorgias
      slug: gorgias
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Customer Service
      - E-Commerce
      - Help Desk
      - Shopify
      tier: declared
      url: /providers/gorgias/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Survicate
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        status: none
      name: LiveChat
      slug: livechat
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Customer Service
      - Live Chat
      - Messaging
      - Sales
      tier: declared
      url: /providers/livechat/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Retently
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: declared
      url: /providers/freshdesk/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Retently
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: none
      name: Kustomer
      slug: kustomer
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - CRM
      - Customer Service
      - Help Desk
      - Messaging
      tier: declared
      url: /providers/kustomer/
  - capability:
      attribution: Turbo EA
      id: BC-4200.10
      key: product-discovery-backlog-management
      name: Product Discovery & Backlog Management
      url: /capabilities/product-discovery-backlog-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Canny
      - ClearFlask
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://canny.io/integrations
      - https://github.com/clearflask/clearflask/tree/master/clearflask-server
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Canny
      - ClearFlask
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id001
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://canny.io/integrations
      - https://github.com/clearflask/clearflask/tree/master/clearflask-server
      status: profiled
      tags: &id002
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Canny
      - Survicate
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: declared
      url: /providers/linear-app/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - ClearFlask
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/clearflask/clearflask/tree/master/clearflask-server
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Canny
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: declared
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Canny
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Canny
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Survicate
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        source: https://mcp.productboard.com/mcp
        status: verified
      name: Productboard
      slug: productboard
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Customer Feedback
      - Prioritization
      - Product Management
      - Roadmapping
      tier: declared
      url: /providers/productboard/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Retently
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://survicate.com/integrations/
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp: &id005
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: &id006
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
    - agent_band: agent-ready
      agent_readiness: 70.1
      apps:
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 85.9
      mcp:
        source: https://github.com/customerio/claude-plugin
        status: verified
      name: Customer.io
      slug: customer-io
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Behavioral Data
      - Broadcast
      - CDP
      - Campaigns
      tier: declared
      url: /providers/customer-io/
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/Iterable/mcp-server
        status: verified
      name: Iterable
      slug: iterable
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Cross-Channel Messaging
      - Customer Engagement
      - Email
      - Marketing Automation
      tier: declared
      url: /providers/iterable/
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
      - Canny
      - Retently
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Canny
      - Retently
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Retently
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
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
      - Canny
      - ClearFlask
      - Formbricks
      - Retently
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://canny.io/integrations
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      - https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
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
      - Retently
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Canny
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: declared
      url: /providers/discord/
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
      - Canny
      - Retently
      - Survicate
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/segment/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Survicate
      band: strong
      in_catalog: true
      kin_score: 56.9
      mcp:
        status: none
      name: Google Reviews
      slug: google-business-profile
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Business Profiles
      - Google
      - Local Business
      - Location
      tier: declared
      url: /providers/google-business-profile/
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - Retently
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: Okendo
      slug: okendo
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Business Applications
      - Company
      - Ratings
      - Reviews
      tier: declared
      url: /providers/okendo/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Retently
      band: thin
      in_catalog: true
      kin_score: 33.5
      mcp:
        source: https://core-api.yotpo.com/docs/connect-to-yotpo-mcp
        status: verified
      name: Yotpo
      slug: yotpo
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Loyalty
      - Retention Marketing
      - Reviews
      tier: declared
      url: /providers/yotpo/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.7
      apps:
      - Formbricks
      band: emerging
      in_catalog: true
      kin_score: 20.9
      mcp:
        source: https://cube.dev/docs/product/apis-integrations/mcp-server
        status: verified
      name: Cube
      slug: cube
      sources:
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Business Intelligence
      - Embedded Analytics
      - GraphQL
      - Semantic Layer
      tier: observed
      url: /providers/cube/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Survicate
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: declared
      url: /providers/google-bigquery/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        status: none
      name: Gong
      slug: gong
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversations
      - Revenue Intelligence
      - Sales
      tier: declared
      url: /providers/gong/
    - agent_band: null
      agent_readiness: null
      apps:
      - Survicate
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: tl;dv
      slug: tldv
      sources:
      - https://survicate.com/integrations/
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
      agent_readiness: 52.3
      apps:
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
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
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
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
      - Retently
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://www.retently.com/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://github.com/formbricks/formbricks/tree/main/apps/web/app/(app)/workspaces/[workspaceId]/settings/workspace/integrations
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - SurveyMonkey
      - Survicate
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Canny
      - Survicate
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://canny.io/integrations
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - SurveyMonkey
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Survicate
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: declared
      url: /providers/amplitude/
    - agent_band: agent-native
      agent_readiness: 39.2
      apps:
      - Survicate
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        source: https://www.uxcam.com/mcp/
        status: verified
      name: UXCam
      slug: uxcam
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Company
      - Mobile Analytics
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/uxcam/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Survicate
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: Fullstory
      slug: fullstory
      sources:
      - https://survicate.com/integrations/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/fullstory/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Fider
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      - https://github.com/getfider/fider/blob/main/.example.env
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Fider
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      - https://github.com/getfider/fider/blob/main/.example.env
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Fider
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/getfider/fider/blob/main/.example.env
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Canny
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Azure AD / Entra ID
      slug: microsoft-entra
      sources:
      - https://canny.io/integrations
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Canny
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Canny
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Canny
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://canny.io/integrations
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: declared
      url: /providers/onelogin/
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
      - ClearFlask
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure AI / Microsoft Foundry
      slug: microsoft-azure-openai
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - ClearFlask
      - Fider
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      - https://github.com/getfider/fider/tree/main/app/services
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Fider
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/getfider/fider/tree/main/app/services
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
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - ClearFlask
      - Fider
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/clearflask/clearflask/tree/master/clearflask-server
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      - https://github.com/getfider/fider/tree/main/app/services
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
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
      - ClearFlask
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - SurveyMonkey
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Google Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
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
      - ClearFlask
      - Fider
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      - https://github.com/getfider/fider/blob/main/go.mod
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
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
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Formbricks
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.4
      apps:
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 81.3
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Fider
      band: thin
      in_catalog: true
      kin_score: 29.9
      mcp:
        status: unchecked
      name: Userlist
      slug: userlist
      sources:
      - https://github.com/getfider/fider/tree/main/app/services
      status: profiled
      tags:
      - Automation
      - Email Marketing
      - Segmentation
      - Software-as-a-Service
      tier: observed
      url: /providers/userlist/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - Formbricks
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        source: https://github.com/authzed/mcp-server-reference
        status: verified
      name: AuthZed
      slug: authzed
      sources:
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Access Control
      - Authorization
      - Permissions
      - Zanzibar
      tier: observed
      url: /providers/authzed/
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - ClearFlask
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        status: none
      name: Let's Encrypt
      slug: lets-encrypt
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Certificates
      - Linux Foundation
      - Security
      - TLS
      tier: observed
      url: /providers/lets-encrypt/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp: *id005
      name: Audience Studio (Krux)
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/salesforce-marketing-cloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - ClearFlask
      band: exemplar
      in_catalog: true
      kin_score: 69.6
      mcp:
        status: none
      name: Amazon Route 53
      slug: amazon-route-53
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Amazon Web Services
      - DNS
      - Domain Registration
      - Health Checks
      tier: observed
      url: /providers/amazon-route-53/
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - ClearFlask
      band: developing
      in_catalog: true
      kin_score: 51.8
      mcp:
        status: none
      name: Castle
      slug: castle
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Bot Detection
      - Company
      - Fraud Prevention
      - Security
      tier: observed
      url: /providers/castle/
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
      - ClearFlask
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon DynamoDB
      slug: amazon-dynamodb
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - Document Store
      - Key-Value Store
      tier: observed
      url: /providers/amazon-dynamodb/
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
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
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
      - ClearFlask
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.6
      apps:
      - Formbricks
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://github.com/formbricks/formbricks/blob/main/.env.example
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - ClearFlask
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        status: unchecked
      name: Kill Bill
      slug: killbill
      sources:
      - https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
      status: profiled
      tags:
      - Billing
      - Payments
      - Subscription Billing
      - Usage Metering
      tier: observed
      url: /providers/killbill/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Formbricks
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://lingo.dev/en/docs/mcp
        status: verified
      name: Lingo.dev
      slug: lingo-dev
      sources:
      - https://github.com/formbricks/formbricks/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Localization
      - Translation
      - i18n
      tier: observed
      url: /providers/lingo-dev/
  layer: common
summary:
  coverage_pct: 98.7
  declared_only: 39
  distinct_providers: 77
  in_catalog: 76
  mcp:
    documented: 2
    none: 25
    unchecked: 4
    verified: 46
  mcp_verified: 46
  mean_kin_score: 60.8
  observed: 38
  queued: 1
  reference_apps: 7
title: 'Customer Feedback & NPS: application blueprint'
---
