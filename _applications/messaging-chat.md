---
access: understanding
agent_layer:
- app: Mattermost
  finding: 'Mattermost Agents plugin: BYO-LLM across 11 service types, plus its own mcp/ and mcpserver/ packages'
  source: https://github.com/mattermost/mattermost-plugin-agents
  tier: observed
- app: Slack
  finding: Slack runs an MCP Registry for Slackbot and hosts third-party agents (Claude, ChatGPT, Agentforce, Writer)
  source: https://slack.com/integrations
  tier: declared
- app: Zulip
  finding: openai SDK in core dependencies (AI features)
  source: https://github.com/zulip/zulip/blob/main/pyproject.toml
  tier: observed
apps:
- anchor: mattermost
  counts:
    declared: 7
    observed: 18
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.mattermost.rn/latest/
  - route: dependency manifest
    url: https://github.com/mattermost/mattermost/blob/master/server/go.mod
  - route: integrations page
    url: https://docs.mattermost.com/integrations-guide/popular-integrations.html
  - route: source code
    url: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
  - route: source code
    url: https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
  - route: source code
    url: https://github.com/mattermost/mattermost/tree/master/server/einterfaces
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    name: AWS Marketplace metering
    provider: amazon-web-services
    says: ships the AWS Marketplace metering SDK or integration code
    source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
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
    source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    name: Cohere
    provider: cohere
    says: ships the Cohere SDK or integration code
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    source: https://github.com/mattermost/mattermost/tree/master/server/channels/app/oauthproviders
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mattermost.rn/latest/
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    name: Google SSO
    provider: google-identity-platform
    says: ships the Google SSO SDK or integration code
    source: https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft Intune
    provider: microsoft-intune
    says: ships the Microsoft Intune SDK or integration code
    source: https://github.com/mattermost/mattermost/tree/master/server/einterfaces
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    name: Office 365 / Entra ID SSO
    provider: microsoft-entra
    says: ships the Office 365 / Entra ID SSO SDK or integration code
    source: https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
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
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    name: Scale AI
    provider: scale-ai
    says: ships the Scale AI SDK or integration code
    source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: common
    name: Split (Harness FME)
    provider: split
    says: ships the Split (Harness FME) SDK or integration code
    source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
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
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Calendar / Outlook
    provider: microsoft-outlook
    says: lists Microsoft Calendar / Outlook as an integration
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Pexip
    provider: pexip
    says: lists Pexip as an integration
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Splunk
    provider: splunk
    says: lists Splunk as an integration
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
    tier: declared
  kind: self-hosted
  name: Mattermost
  page: /applications/messaging-chat/mattermost/
  slug: mattermost
  url: https://github.com/mattermost/mattermost
- anchor: rocketchat
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/chat.rocket.android/latest/
  - route: dependency manifest
    url: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
  - route: source code
    url: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/server/services/omnichannel-integrations/providers/twilio.ts
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    name: Apple (APNs, Sign in with Apple)
    provider: apple
    says: ships the Apple (APNs, Sign in with Apple) SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    name: Firebase (Crashlytics, Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics, Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/chat.rocket.android/latest/
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
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: LiveKit
    provider: livekit
    says: ships the LiveKit SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/server/services/omnichannel-integrations/providers/twilio.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
    tier: observed
  kind: self-hosted
  name: Rocket.Chat
  page: /applications/messaging-chat/rocket-chat/
  slug: rocket-chat
  url: https://github.com/RocketChat/Rocket.Chat
- anchor: zulip
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/zulip/zulip/blob/main/pyproject.toml
  - route: source code
    url: https://github.com/zulip/zulip/blob/main/zproject/backends.py
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/zulip/zulip/blob/main/pyproject.toml
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
    name: Apple (APNs, Sign in with Apple)
    provider: apple
    says: ships the Apple (APNs, Sign in with Apple) SDK or integration code
    source: https://github.com/zulip/zulip/blob/main/pyproject.toml
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
    name: Azure AD
    provider: microsoft-entra
    says: ships the Azure AD SDK or integration code
    source: https://github.com/zulip/zulip/blob/main/zproject/backends.py
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
    source: https://github.com/zulip/zulip/blob/main/zproject/backends.py
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://github.com/zulip/zulip/blob/main/pyproject.toml
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
    source: https://github.com/zulip/zulip/blob/main/zproject/backends.py
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
    source: https://github.com/zulip/zulip/blob/main/zproject/backends.py
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
    source: https://github.com/zulip/zulip/blob/main/zproject/backends.py
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
    source: https://github.com/zulip/zulip/blob/main/pyproject.toml
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
    source: https://github.com/zulip/zulip/blob/main/pyproject.toml
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
    source: https://github.com/zulip/zulip/blob/main/pyproject.toml
    tier: observed
  kind: open-source-saas
  name: Zulip
  page: /applications/messaging-chat/zulip/
  slug: zulip
  url: https://github.com/zulip/zulip
- anchor: element-/-matrix-(synapse)
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/im.vector.app/latest/
  - route: dependency manifest
    url: https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
  - route: dependency manifest
    url: https://github.com/element-hq/synapse/blob/develop/pyproject.toml
  - route: source code
    url: https://github.com/element-hq/element-web/blob/develop/apps/web/config.sample.json
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/im.vector.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Jitsi
    provider: jitsi-org
    says: ships the Jitsi SDK or integration code
    source: https://github.com/element-hq/element-web/blob/develop/apps/web/config.sample.json
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
    source: https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
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
    source: https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
    tier: observed
  kind: self-hosted
  name: Element / Matrix (Synapse)
  page: /applications/messaging-chat/element-matrix-synapse/
  slug: element-matrix-synapse
  url: https://github.com/element-hq/element-web
- anchor: signal
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.thoughtcrime.securesms/latest/
  - route: dependency manifest
    url: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
  - route: source code
    url: https://github.com/signalapp/Signal-Android/blob/main/app/build.gradle.kts
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
    name: Google ID / Credential Manager
    provider: google-identity-platform
    says: ships the Google ID / Credential Manager SDK or integration code
    source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Google Pay
    provider: google-pay
    says: ships the Google Pay SDK or integration code
    source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.40
      key: AE-190.40
      name: Remittances & P2P
      url: /capabilities/remittances-p2p/
      via_parent: null
    credit: null
    layer: domain
    name: MobileCoin
    provider: mobilecoin
    says: ships the MobileCoin SDK or integration code
    source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
    source: https://github.com/signalapp/Signal-Android/blob/main/app/build.gradle.kts
    tier: observed
  kind: open-source-saas
  name: Signal
  page: /applications/messaging-chat/signal/
  slug: signal
  url: https://github.com/signalapp/Signal-Android
- anchor: slack
  counts:
    declared: 23
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.Slack/latest/
  - route: integrations page
    url: https://slack.com/integrations
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.Slack/latest/
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
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS Chatbot
    provider: amazon-q
    says: lists AWS Chatbot as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: ChatGPT / Codex
    provider: openai
    says: lists ChatGPT / Codex as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Claude
    provider: anthropic
    says: lists Claude as an integration
    source: https://slack.com/integrations
    tier: declared
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
    says: lists Dropbox as an integration
    source: https://slack.com/integrations
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
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://slack.com/integrations
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
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Highspot
    provider: highspot
    says: lists Highspot as an integration
    source: https://slack.com/integrations
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
    source: https://slack.com/integrations
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
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Miro
    provider: miro
    says: lists Miro as an integration
    source: https://slack.com/integrations
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
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: PagerDuty
    provider: pagerduty
    says: lists PagerDuty as an integration
    source: https://slack.com/integrations
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
    name: Salesforce Sales Cloud
    provider: salesforce
    says: lists Salesforce Sales Cloud as an integration
    source: https://slack.com/integrations
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
    name: Salesforce Service Cloud
    provider: service-cloud
    says: lists Salesforce Service Cloud as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Writer
    provider: writer
    says: lists Writer as an integration
    source: https://slack.com/integrations
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
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://slack.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: ZoomInfo
    provider: zoominfo
    says: lists ZoomInfo as an integration
    source: https://slack.com/integrations
    tier: declared
  kind: commercial
  name: Slack
  page: /applications/messaging-chat/slack/
  slug: slack
  url: https://slack.com/
- anchor: discord
  counts:
    declared: 20
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
  - route: documentation
    url: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Amazon Music
    provider: amazon-music
    says: lists Amazon Music as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Bluesky
    provider: bluesky
    says: lists Bluesky as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Bungie.net
    provider: bungie
    says: lists Bungie.net as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Crunchyroll
    provider: crunchyroll
    says: lists Crunchyroll as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: eBay
    provider: ebay
    says: lists eBay as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Epic Games
    provider: epic-games
    says: lists Epic Games as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Mastodon
    provider: mastodon
    says: lists Mastodon as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: PlayStation Network
    provider: playstation
    says: lists PlayStation Network as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Reddit
    provider: reddit
    says: lists Reddit as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Roblox
    provider: roblox
    says: lists Roblox as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: lists Spotify as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Steam
    provider: steam
    says: lists Steam as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Twitch
    provider: twitch
    says: lists Twitch as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Xbox
    provider: microsoft-xbox
    says: lists Xbox as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
    tier: declared
  kind: commercial
  name: Discord
  page: /applications/messaging-chat/discord/
  slug: discord
  url: https://discord.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: messaging-chat
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Social Networking
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Communication
  store: google-play
  url: https://play.google.com/store/apps/category/COMMUNICATION
- category: Communication - Custom Communication Systems
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---custom-communication-systems
- category: Communication - XMPP - Servers
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---xmpp---servers
- category: Communication
  store: slack-marketplace
  url: https://slack.com/apps
- category: Team Chat
  store: zapier
  url: https://zapier.com/apps
name: Messaging & Team Chat
needs:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: crash and error reporting (Sentry, Bugsnag, Crashlytics) in every app; Splunk and AWS chat-ops alerts
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: calls and meetings inside chat (LiveKit, Jitsi, Zoom, Pexip)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: login with GitHub/GitLab/Google/Entra/Apple/Discord; Discord account connections recorded as nearest
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: BYO-LLM in Mattermost Agents and Zulip; AI agents named by Slack
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: mobile push (FCM, APNs) is how a chat app delivers messages to a phone
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: attachment / file stores; no generic object-storage capability exists
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: ad SDK trackers reported by Exodus
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: domain
  why: bridges to other team-chat systems (Slack, Teams)
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: billing (Zulip Cloud) and donations (Signal)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics trackers (PostHog, Google Analytics)
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: work tools surfaced in chat
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: code hosting notifications in channels
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: location-sharing maps
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: Google Pay donations
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: SMS omnichannel (Rocket.Chat)
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: calendar reminders in chat
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Google credential manager sign-in (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-190.40
    key: AE-190.40
    name: Remittances & P2P
    url: /capabilities/remittances-p2p/
    via_parent: null
  fit: exact
  layer: domain
  why: P2P in-app payments (MobileCoin)
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.20
    key: AE-230.30.20
    name: Lead Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: domain
  why: lead data app
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution (AppsFlyer)
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: store billing (Signal backups)
- capability:
    attribution: Turbo EA
    id: BC-410.50.30
    key: BC-410.50.30
    name: Sales Enablement
    url: /capabilities/sales-operations-management/
    via_parent: Sales Operations Management
  fit: exact
  layer: domain
  why: 'Sales Enablement: Highspot'
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CRM records surfaced in chat
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: support desks surfaced in chat
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature flags (Split)
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: mobile app management via Intune (nearest)
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: on-call alerts
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: file stores surfaced in chat (nearest)
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: nearest
  layer: common
  why: AWS Marketplace metering (nearest)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Discord
      - Rocket.Chat
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Discord
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id001
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags: &id002
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Discord
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-aware
      agent_readiness: 8.9
      apps:
      - Discord
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Xbox
      slug: microsoft-xbox
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Gaming
      - Microsoft
      - PlayFab
      - Xbox
      tier: declared
      url: /providers/microsoft-xbox/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Discord
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: declared
      url: /providers/reddit/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Discord
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: declared
      url: /providers/spotify/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        source: https://github.com/eBay/npm-public-api-mcp
        status: verified
      name: eBay
      slug: ebay
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Auctions
      - Commerce
      - Marketplace
      - Product
      tier: declared
      url: /providers/ebay/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: declared
      url: /providers/twitch/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        status: none
      name: Bluesky
      slug: bluesky
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - At-Protocol
      - Decentralized
      - Federated
      - Open Source
      tier: declared
      url: /providers/bluesky/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Epic Games
      slug: epic-games
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Achievements
      - Anti-Cheat
      - Cross-Platform
      - EOS
      tier: declared
      url: /providers/epic-games/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Discord
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Discord
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        status: none
      name: Steam
      slug: steam
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Distribution
      - Gaming
      - Steamworks
      - Valve
      tier: declared
      url: /providers/steam/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Discord
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        source: https://github.com/Roblox/studio-rust-mcp-server
        status: verified
      name: Roblox
      slug: roblox
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Assets
      - Datastores
      - Game Development
      - Games
      tier: declared
      url: /providers/roblox/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Discord
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: declared
      url: /providers/mastodon/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Discord
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Amazon Music
      slug: amazon-music
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Audio
      - Company
      - Music
      - Streaming
      tier: declared
      url: /providers/amazon-music/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Discord
      band: emerging
      in_catalog: true
      kin_score: 21.9
      mcp:
        status: none
      name: PlayStation Network
      slug: playstation
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Company
      - Console
      - Entertainment
      - Gaming
      tier: declared
      url: /providers/playstation/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Discord
      band: minimal
      in_catalog: true
      kin_score: 7.6
      mcp:
        status: none
      name: Crunchyroll
      slug: crunchyroll
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/crunchyroll/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Discord
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        status: none
      name: Bungie.net
      slug: bungie
      sources:
      - https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
      status: profiled
      tags:
      - Community
      - Company
      - Gaming
      - Video Games
      tier: declared
      url: /providers/bungie/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Mattermost
      - Rocket.Chat
      - Zulip
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp: &id007
        status: none
      name: Google SSO
      slug: google-identity-platform
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      - https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
      - https://github.com/zulip/zulip/blob/main/zproject/backends.py
      status: profiled
      tags: &id008
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Mattermost
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: &id003
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/mattermost/mattermost/tree/master/server/channels/app/oauthproviders
      - https://github.com/zulip/zulip/blob/main/zproject/backends.py
      status: profiled
      tags: &id004
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Rocket.Chat
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      - https://github.com/zulip/zulip/blob/main/zproject/backends.py
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Mattermost
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Office 365 / Entra ID SSO
      slug: microsoft-entra
      sources:
      - https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
      - https://github.com/zulip/zulip/blob/main/zproject/backends.py
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Zulip
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/zulip/zulip/blob/main/zproject/backends.py
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Mattermost
      - Slack
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      - https://slack.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Rocket.Chat
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: LiveKit
      slug: livekit
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      status: profiled
      tags:
      - Audio
      - Real-Time
      - Video
      - WebRTC
      tier: observed
      url: /providers/livekit/
    - agent_band: human-only
      agent_readiness: 3.7
      apps:
      - Element / Matrix (Synapse)
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: Jitsi
      slug: jitsi-org
      sources:
      - https://github.com/element-hq/element-web/blob/develop/apps/web/config.sample.json
      status: profiled
      tags:
      - Open Source
      - Real-Time Communication
      - Video Conferencing
      - WebRTC
      tier: observed
      url: /providers/jitsi-org/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mattermost
      band: thin
      in_catalog: true
      kin_score: 31.7
      mcp:
        status: none
      name: Pexip
      slug: pexip
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      status: profiled
      tags:
      - Cloud
      - Communications
      - Security
      - Video
      tier: declared
      url: /providers/pexip/
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
      - Mattermost
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      - https://slack.com/integrations
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Slack
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
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
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Slack
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Slack
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
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
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-native
      agent_readiness: 50.0
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Salesforce Service Cloud
      slug: service-cloud
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - CRM
      - Cloud
      - Customer Service
      - Enterprise
      tier: declared
      url: /providers/service-cloud/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Slack
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: declared
      url: /providers/freshdesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp: &id011
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude
      slug: anthropic
      sources:
      - https://slack.com/integrations
      status: profiled
      tags: &id012
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id009
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT / Codex
      slug: openai
      sources:
      - https://slack.com/integrations
      status: profiled
      tags: &id010
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - Slack
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        source: https://github.com/writer/writer-mcp
        status: verified
      name: Writer
      slug: writer
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Content Generation
      - Enterprise
      - LLM
      tier: declared
      url: /providers/writer/
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
      - Mattermost
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      - https://slack.com/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: *id003
      name: GitLab
      slug: gitlab
      sources:
      - https://slack.com/integrations
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/gitlab/
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
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://slack.com/integrations
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
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce Sales Cloud
      slug: salesforce
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Rocket.Chat
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.1
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        status: none
      name: AWS Chatbot
      slug: amazon-q
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Assistant
      - Enterprise
      tier: declared
      url: /providers/amazon-q/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: declared
      url: /providers/splunk/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.9
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://developers.miro.com/docs/miro-mcp
        status: verified
      name: Miro
      slug: miro
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Diagramming
      - Productivity
      - Visual Collaboration
      - Whiteboard
      tier: declared
      url: /providers/miro/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Slack
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: declared
      url: /providers/pagerduty/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.0
      apps:
      - Slack
      band: exemplar
      in_catalog: true
      kin_score: 86.8
      mcp:
        source: https://github.com/Zoominfo/zoominfo-mcp-plugin
        status: verified
      name: ZoomInfo
      slug: zoominfo
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - B2B
      - B2B Data
      - Company Data
      - Contact Database
      tier: declared
      url: /providers/zoominfo/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Mattermost
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Calendar / Outlook
      slug: microsoft-outlook
      sources:
      - https://docs.mattermost.com/integrations-guide/popular-integrations.html
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.40
      key: AE-190.40
      name: Remittances & P2P
      url: /capabilities/remittances-p2p/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 6.2
      apps:
      - Signal
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: MobileCoin
      slug: mobilecoin
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Blockchain
      - Company
      - Cryptocurrency
      - Payments
      tier: observed
      url: /providers/mobilecoin/
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
      - Rocket.Chat
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/server/services/omnichannel-integrations/providers/twilio.ts
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Slack
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        source: https://mcp.highspot.com/mcp
        status: verified
      name: Highspot
      slug: highspot
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - CRM Integration
      - Content Management
      - Pitch Analytics
      - Sales Enablement
      tier: declared
      url: /providers/highspot/
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
      - Slack
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://slack.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
  layer: domain
- capabilities:
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
      - Discord
      - Element / Matrix (Synapse)
      - Mattermost
      - Slack
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
      - https://github.com/mattermost/mattermost/blob/master/server/go.mod
      - https://github.com/zulip/zulip/blob/main/pyproject.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Rocket.Chat
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Rocket.Chat
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics, Analytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/chat.rocket.android/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Signal
      - Zulip
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase Cloud Messaging
      slug: google-firebase
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
      - https://github.com/zulip/zulip/blob/main/pyproject.toml
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Rocket.Chat
      - Zulip
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple (APNs, Sign in with Apple)
      slug: apple
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      - https://github.com/zulip/zulip/blob/main/pyproject.toml
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
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
      - Rocket.Chat
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
      - https://github.com/zulip/zulip/blob/main/pyproject.toml
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
      - Rocket.Chat
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/mattermost/mattermost/blob/master/server/go.mod
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
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Element / Matrix (Synapse)
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mattermost.rn/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/im.vector.app/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
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
      - Signal
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/app/build.gradle.kts
      - https://github.com/zulip/zulip/blob/main/pyproject.toml
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
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Discord
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Element / Matrix (Synapse)
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
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
      - Signal
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Signal
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: observed
      url: /providers/google-pay/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - Mattermost
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        status: none
      name: Microsoft Intune
      slug: microsoft-intune
      sources:
      - https://github.com/mattermost/mattermost/tree/master/server/einterfaces
      status: profiled
      tags:
      - App Protection
      - Compliance
      - Device Configuration
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-intune/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Mattermost
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: none
      name: Split (Harness FME)
      slug: split
      sources:
      - https://github.com/mattermost/mattermost/blob/master/server/go.mod
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Signal
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
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
      - Discord
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Signal
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp: *id007
      name: Google ID / Credential Manager
      slug: google-identity-platform
      sources:
      - https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Mattermost
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS Marketplace metering
      slug: amazon-web-services
      sources:
      - https://github.com/mattermost/mattermost/blob/master/server/go.mod
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
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
      - Mattermost
      - Zulip
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id009
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      - https://github.com/zulip/zulip/blob/main/pyproject.toml
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Mattermost
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp: *id011
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 42.8
      apps:
      - Mattermost
      band: exemplar
      in_catalog: true
      kin_score: 71.1
      mcp:
        status: none
      name: Scale AI
      slug: scale-ai
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags:
      - Data Engine
      - GenAI Platform
      - Labeling
      - RLHF
      tier: observed
      url: /providers/scale-ai/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Mattermost
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Vertex AI
      slug: google-vertex-ai
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Mattermost
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Mattermost
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Mattermost
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: observed
      url: /providers/cohere/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 43
  distinct_providers: 79
  in_catalog: 79
  mcp:
    documented: 0
    none: 38
    unchecked: 0
    verified: 41
  mcp_verified: 41
  mean_kin_score: 59.1
  observed: 36
  queued: 0
  reference_apps: 7
title: 'Messaging & Team Chat: application blueprint'
---
