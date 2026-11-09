---
access: understanding
agent_layer:
- app: Outline
  finding: 'ships @modelcontextprotocol/sdk: the wiki exposes its own MCP server'
  source: https://raw.githubusercontent.com/outline/outline/main/package.json
  tier: observed
- app: AFFiNE
  finding: copilot/mcp module (controller, credential, provider) plus BYOK model providers
  source: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/copilot/mcp
  tier: observed
- app: Notion
  finding: hosted Notion MCP server
  source: https://developers.notion.com/docs/mcp
  tier: declared
apps:
- anchor: outline
  counts:
    declared: 0
    observed: 18
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/outline/outline/main/package.json
  - route: source code
    url: https://github.com/outline/outline/tree/main/plugins
  - route: source code
    url: https://raw.githubusercontent.com/outline/outline/main/.env.sample
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: common
    name: Amazon CloudFront
    provider: cloudfront
    says: ships the Amazon CloudFront SDK or integration code
    source: https://raw.githubusercontent.com/outline/outline/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://raw.githubusercontent.com/outline/outline/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Figma
    provider: figma
    says: ships the Figma SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Iframely
    provider: iframely
    says: ships the Iframely SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://raw.githubusercontent.com/outline/outline/main/package.json
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
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
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
    name: Microsoft (Azure AD)
    provider: microsoft-entra
    says: ships the Microsoft (Azure AD) SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: ships the Notion SDK or integration code
    source: https://raw.githubusercontent.com/outline/outline/main/package.json
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
    source: https://raw.githubusercontent.com/outline/outline/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slab
    provider: slab
    says: ships the Slab SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/outline/outline/main/.env.sample
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
    name: Umami
    provider: umami
    says: ships the Umami SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: ships the Zapier SDK or integration code
    source: https://github.com/outline/outline/tree/main/plugins
    tier: observed
  kind: self-hosted
  name: Outline
  page: /applications/notes-knowledge/outline/
  slug: outline
  url: https://github.com/outline/outline
- anchor: bookstack
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
  - route: source code
    url: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: diagrams.net (draw.io)
    provider: diagrams-net
    says: ships the diagrams.net (draw.io) SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
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
    name: Microsoft Azure AD
    provider: microsoft-entra
    says: ships the Microsoft Azure AD SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
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
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Twitch
    provider: twitch
    says: ships the Twitch SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Twitter / X
    provider: x
    says: ships the Twitter / X SDK or integration code
    source: https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
    tier: observed
  kind: self-hosted
  name: BookStack
  page: /applications/notes-knowledge/bookstack/
  slug: bookstack
  url: https://github.com/BookStackApp/BookStack
- anchor: joplin
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/net.cozic.joplin/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/laurent22/joplin/dev/packages/server/package.json
  - route: source code
    url: https://github.com/laurent22/joplin/tree/dev/packages/lib
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/laurent22/joplin/tree/dev/packages/lib
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/laurent22/joplin/tree/dev/packages/lib
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Nextcloud
    provider: nextcloud
    says: ships the Nextcloud SDK or integration code
    source: https://github.com/laurent22/joplin/tree/dev/packages/lib
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: OneDrive
    provider: microsoft-onedrive
    says: ships the OneDrive SDK or integration code
    source: https://github.com/laurent22/joplin/tree/dev/packages/lib
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
    source: https://raw.githubusercontent.com/laurent22/joplin/dev/packages/server/package.json
    tier: observed
  kind: self-hosted
  name: Joplin
  page: /applications/notes-knowledge/joplin/
  slug: joplin
  url: https://github.com/laurent22/joplin
- anchor: affine
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: source code
    url: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins
  - route: source code
    url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
  - route: source code
    url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
  - route: source code
    url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
  - route: source code
    url: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
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
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    name: Cloudflare (Workers AI)
    provider: cloudflare
    says: ships the Cloudflare (Workers AI) SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/captcha/config.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.20
      key: AE-230.40.20
      name: Web Search APIs
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: agent
    name: Exa
    provider: exa-ai
    says: ships the Exa SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: agent
    name: fal
    provider: fal-ai
    says: ships the fal SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/calendar/providers
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
    name: Google Cloud Logging
    provider: google-cloud-logging
    says: ships the Google Cloud Logging SDK or integration code
    source: https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/gcloud
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
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
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
    name: Google Vertex AI
    provider: google-vertex-ai
    says: ships the Google Vertex AI SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
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
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: RevenueCat
    provider: revenuecat
    says: ships the RevenueCat SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
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
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
    tier: observed
  kind: open-source-saas
  name: AFFiNE
  page: /applications/notes-knowledge/affine/
  slug: affine
  url: https://github.com/toeverything/AFFiNE
- anchor: logseq
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.logseq.app/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/logseq/logseq/master/package.json
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Cognito (via aws-amplify)
    provider: amazon-cognito
    says: ships the Amazon Cognito (via aws-amplify) SDK or integration code
    source: https://raw.githubusercontent.com/logseq/logseq/master/package.json
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
    source: https://raw.githubusercontent.com/logseq/logseq/master/package.json
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
    source: https://raw.githubusercontent.com/logseq/logseq/master/package.json
    tier: observed
  kind: open-source-saas
  name: Logseq
  page: /applications/notes-knowledge/logseq/
  slug: logseq
  url: https://github.com/logseq/logseq
- anchor: wikijs
  counts:
    declared: 0
    observed: 21
  evidence:
  - route: source code
    url: https://github.com/requarks/wiki/tree/scarlett/backend/modules
  integrations:
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
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/storage/azure
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
    name: Baidu Tongji
    provider: baidu
    says: ships the Baidu Tongji SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/baidu
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
    name: Contentsquare
    provider: contentsquare
    says: ships the Contentsquare SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/contentsquare
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/discord
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Discourse
    provider: discourse
    says: ships the Discourse SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/discourse
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Disqus
    provider: disqus
    says: ships the Disqus SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/disqus
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
    name: Elastic APM
    provider: elastic
    says: ships the Elastic APM SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/elasticapm
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
    name: Fathom Analytics
    provider: fathom
    says: ships the Fathom Analytics SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/fathom
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/github
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/google
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
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/storage/gcs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/google
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/gtm
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Hyvor Talk
    provider: hyvor-talk
    says: ships the Hyvor Talk SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/hyvortalk
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
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/matomo
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
    name: Microsoft Clarity
    provider: microsoft-clarity
    says: ships the Microsoft Clarity SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/clarity
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
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/entra
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
    name: Plausible
    provider: plausible
    says: ships the Plausible SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/plausible
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
    name: StatCounter
    provider: statcounter
    says: ships the StatCounter SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/statcounter
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
    name: Umami
    provider: umami
    says: ships the Umami SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/umami
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
    name: Yandex Metrica
    provider: yandex-metrica
    says: ships the Yandex Metrica SDK or integration code
    source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/yandex
    tier: observed
  kind: self-hosted
  name: Wiki.js
  page: /applications/notes-knowledge/wiki-js/
  slug: wiki-js
  url: https://github.com/requarks/wiki
- anchor: notion
  counts:
    declared: 11
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/notion.id/latest/
  - route: integrations page
    url: https://www.notion.com/help/notion-ai-connectors
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/notion.id/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Microsoft SharePoint
    provider: sharepoint
    says: lists Microsoft SharePoint as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.notion.com/help/notion-ai-connectors
    tier: declared
  kind: commercial
  name: Notion
  page: /applications/notes-knowledge/notion/
  slug: notion
  url: https://www.notion.com/
- anchor: obsidian
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/md.obsidian/latest/
  integrations: []
  kind: commercial
  name: Obsidian
  page: /applications/notes-knowledge/obsidian/
  slug: obsidian
  url: https://obsidian.md/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: notes-knowledge
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Note-taking & Editors
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#note-taking--editors
- category: Knowledge Management Tools
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#knowledge-management-tools
- category: Wikis
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#wikis
- category: Documentation
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Notes
  store: zapier
  url: https://zapier.com/apps
name: Notes & Personal Knowledge Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: sign-in with GitHub/Google/Discord/Slack/Apple etc. on every self-hosted wiki
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: workforce IdPs (Entra ID, Okta) for team wikis
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: domain
  why: 'rich embeds and link unfurls (gap: no link-unfurl / embed node)'
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: importing another knowledge base (Notion, Slab)
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier triggers/actions
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: pluggable page analytics in Outline and Wiki.js; PostHog in Logseq
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring and logging
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  fit: exact
  layer: common
  why: signed CDN URLs for attachments
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: 'attachment storage (nearest) and note-sync targets (gap: no cloud-drive / file-sync capability)'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: hosted-cloud subscriptions (Joplin Cloud, AFFiNE Cloud)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI writing assistants inside the editor
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.10
    key: AE-110.20.10
    name: Image Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  fit: exact
  layer: agent
  why: AI image blocks
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: agent
  why: grounding the AI assistant in web search
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: stock image picker for covers
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: calendar events alongside notes/journals
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: sign-up abuse protection
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: mobile subscriptions via RevenueCat
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  fit: exact
  layer: common
  why: hosted account sign-in for a sync service (Logseq via Cognito)
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: Google Tag Manager
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.30
    key: AE-170.50.30
    name: Embedded Comments
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: 'embedded page comments (gap: no embedded-comments node)'
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: agent
  why: Notion AI Connectors search connected work apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - AFFiNE
      - BookStack
      - Outline
      - Wiki.js
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/google
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - AFFiNE
      - BookStack
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp: &id001
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/github
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
      status: profiled
      tags: &id002
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - BookStack
      - Outline
      - Wiki.js
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/discord
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - BookStack
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp: &id007
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
      - https://raw.githubusercontent.com/outline/outline/main/.env.sample
      status: profiled
      tags: &id008
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - BookStack
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp: &id003
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
      status: profiled
      tags: &id004
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - BookStack
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter / X
      slug: x
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - AFFiNE
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/oauth/config.ts
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - BookStack
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: observed
      url: /providers/twitch/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - BookStack
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp: *id003
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 57.8
      apps:
      - Outline
      band: strong
      in_catalog: true
      kin_score: 65.6
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: observed
      url: /providers/figma/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Outline
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp: &id005
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://raw.githubusercontent.com/outline/outline/main/.env.sample
      status: profiled
      tags: &id006
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Outline
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp: &id013
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://raw.githubusercontent.com/outline/outline/main/package.json
      status: profiled
      tags: &id014
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Outline
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        status: unknown
      name: Iframely
      slug: iframely
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      status: profiled
      tags:
      - Content
      - Embed
      - Media
      - URLs
      tier: observed
      url: /providers/iframely/
    - agent_band: null
      agent_readiness: null
      apps:
      - BookStack
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: diagrams.net (draw.io)
      slug: diagrams-net
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/.env.example.complete
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Joplin
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp: &id011
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/laurent22/joplin/tree/dev/packages/lib
      status: profiled
      tags: &id012
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Joplin
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp: *id005
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/laurent22/joplin/tree/dev/packages/lib
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Joplin
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Nextcloud
      slug: nextcloud
      sources:
      - https://github.com/laurent22/joplin/tree/dev/packages/lib
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Wiki.js
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://github.com/discourse/discourse-mcp
        status: verified
      name: Discourse
      slug: discourse
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/discourse
      status: profiled
      tags:
      - Community
      - Forums
      - Open Source
      tier: observed
      url: /providers/discourse/
    - agent_band: agent-aware
      agent_readiness: 21.1
      apps:
      - Wiki.js
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        status: none
      name: Disqus
      slug: disqus
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/disqus
      status: profiled
      tags:
      - Comments
      - Community
      - Discussions
      - Publishing
      tier: observed
      url: /providers/disqus/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Wiki.js
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: none
      name: Hyvor Talk
      slug: hyvor-talk
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/hyvortalk
      status: profiled
      tags:
      - Comments
      - Engagement
      - Platform
      - Software-as-a-Service
      tier: observed
      url: /providers/hyvor-talk/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.9
      apps:
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://raw.githubusercontent.com/outline/outline/main/package.json
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - Outline
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Slab
      slug: slab
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      status: profiled
      tags:
      - Collaboration
      - Documentation
      - Knowledge Base
      - Wiki
      tier: observed
      url: /providers/slab/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - AFFiNE
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp: &id009
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/calendar/providers
      status: profiled
      tags: &id010
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - AFFiNE
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
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
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Joplin
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/laurent22/joplin/tree/dev/packages/lib
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
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
      agent_readiness: 41.8
      apps:
      - Outline
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/google
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Outline
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 73.3
      mcp:
        status: none
      name: Umami
      slug: umami
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/umami
      status: profiled
      tags:
      - Cookieless Tracking
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/umami/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Outline
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/matomo
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Wiki.js
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://github.com/microsoft/clarity-mcp-server
        status: verified
      name: Microsoft Clarity
      slug: microsoft-clarity
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/clarity
      status: profiled
      tags:
      - Analytics
      - Heatmaps
      - Session Recording
      - Web Analytics
      tier: observed
      url: /providers/microsoft-clarity/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Wiki.js
      band: strong
      in_catalog: true
      kin_score: 63.4
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/plausible
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: observed
      url: /providers/plausible/
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Logseq
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/logseq/logseq/master/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Wiki.js
      band: developing
      in_catalog: true
      kin_score: 49.7
      mcp:
        status: none
      name: Fathom Analytics
      slug: fathom
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/fathom
      status: profiled
      tags:
      - Analytics
      - GDPR
      - Privacy
      - Website Analytics
      tier: observed
      url: /providers/fathom/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Wiki.js
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Contentsquare
      slug: contentsquare
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/contentsquare
      status: profiled
      tags:
      - Digital Experience Analytics
      - Heatmaps
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/contentsquare/
    - agent_band: agent-aware
      agent_readiness: 6.0
      apps:
      - Wiki.js
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        source: https://github.com/baidu-maps/mcp
        status: verified
      name: Baidu Tongji
      slug: baidu
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/baidu
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Machine Learning
      - Technology
      tier: observed
      url: /providers/baidu/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - Wiki.js
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        source: https://statcounter.com/api/docs/mcp
        status: verified
      name: StatCounter
      slug: statcounter
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/statcounter
      status: profiled
      tags:
      - Analytics
      - Company
      - Real-Time
      - Web
      tier: observed
      url: /providers/statcounter/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Wiki.js
      band: minimal
      in_catalog: true
      kin_score: 9.6
      mcp:
        status: none
      name: Yandex Metrica
      slug: yandex-metrica
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/yandex
      status: profiled
      tags:
      - Analytics
      - Marketing
      - Web Analytics
      - Yandex
      tier: observed
      url: /providers/yandex-metrica/
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
      - Logseq
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/logseq/logseq/master/package.json
      - https://raw.githubusercontent.com/outline/outline/main/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - AFFiNE
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
        status: verified
      name: Google Cloud Logging
      slug: google-cloud-logging
      sources:
      - https://github.com/toeverything/AFFiNE/tree/canary/packages/backend/server/src/plugins/gcloud
      status: profiled
      tags:
      - Cloud
      - Logging
      - Monitoring
      - Observability
      tier: observed
      url: /providers/google-cloud-logging/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic APM
      slug: elastic
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/elasticapm
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Notion
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Crashlytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/notion.id/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - BookStack
      - Outline
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft (Azure AD)
      slug: microsoft-entra
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/entra
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - BookStack
      band: exemplar
      in_catalog: true
      kin_score: 78.0
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://raw.githubusercontent.com/BookStackApp/BookStack/development/composer.json
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - AFFiNE
      - Joplin
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/laurent22/joplin/dev/packages/server/package.json
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
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
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/storage/gcs
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Wiki.js
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/storage/azure
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - AFFiNE
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/captcha/config.ts
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        status: none
      name: Amazon CloudFront
      slug: cloudfront
      sources:
      - https://raw.githubusercontent.com/outline/outline/main/.env.sample
      status: profiled
      tags:
      - Amazon Web Services
      - CDN
      - Caching
      - Content Delivery
      tier: observed
      url: /providers/cloudfront/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Logseq
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Amazon Cognito (via aws-amplify)
      slug: amazon-cognito
      sources:
      - https://raw.githubusercontent.com/logseq/logseq/master/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Authentication
      - Identity
      - OAuth
      tier: observed
      url: /providers/amazon-cognito/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - AFFiNE
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        source: https://www.revenuecat.com/docs/tools/mcp
        status: verified
      name: RevenueCat
      slug: revenuecat
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/payment/config.ts
      status: profiled
      tags:
      - Billing
      - In-App Purchases
      - Mobile
      - Subscription
      tier: observed
      url: /providers/revenuecat/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Wiki.js
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/gtm
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - Outline
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://github.com/outline/outline/tree/main/plugins
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Notion
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 65.7
      apps:
      - Notion
      band: exemplar
      in_catalog: true
      kin_score: 82.6
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Notion
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp: *id007
      name: Slack
      slug: slack
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Notion
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Outlook
      slug: microsoft-outlook
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Notion
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Notion
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Notion
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft SharePoint
      slug: sharepoint
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: declared
      url: /providers/sharepoint/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Notion
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp: *id009
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags: *id010
      tier: declared
      url: /providers/google-calendar/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Notion
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp: *id011
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags: *id012
      tier: declared
      url: /providers/microsoft-onedrive/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Notion
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Notion
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp: *id013
      name: Linear
      slug: linear-app
      sources:
      - https://www.notion.com/help/notion-ai-connectors
      status: profiled
      tags: *id014
      tier: declared
      url: /providers/linear-app/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - AFFiNE
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - AFFiNE
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare (Workers AI)
      slug: cloudflare
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - AFFiNE
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - AFFiNE
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - AFFiNE
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Vertex AI
      slug: google-vertex-ai
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.10
      key: AE-110.20.10
      name: Image Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - AFFiNE
      band: strong
      in_catalog: true
      kin_score: 65.6
      mcp:
        source: https://docs.fal.ai/model-apis/mcp
        status: verified
      name: fal
      slug: fal-ai
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/providers/types.ts
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Generative Media
      - Image Generation
      tier: observed
      url: /providers/fal-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.20
      key: AE-230.40.20
      name: Web Search APIs
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.0
      apps:
      - AFFiNE
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        source: https://github.com/exa-labs/exa-mcp-server
        status: verified
      name: Exa
      slug: exa-ai
      sources:
      - https://raw.githubusercontent.com/toeverything/AFFiNE/canary/packages/backend/server/src/plugins/copilot/config.ts
      status: profiled
      tags:
      - Artificial Intelligence
      - Neural Search
      - Search
      - Web Search
      tier: observed
      url: /providers/exa-ai/
  layer: agent
summary:
  coverage_pct: 98.4
  declared_only: 11
  distinct_providers: 63
  in_catalog: 62
  mcp:
    documented: 0
    none: 22
    unchecked: 1
    verified: 39
  mcp_verified: 39
  mean_kin_score: 57.0
  observed: 52
  queued: 1
  reference_apps: 8
title: 'Notes & Personal Knowledge Management: application blueprint'
---
