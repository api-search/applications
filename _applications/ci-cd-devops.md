---
access: understanding
agent_layer:
- app: Coolify
  finding: ships its own MCP server (laravel/mcp in composer.json)
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
  tier: observed
- app: CircleCI
  finding: CircleCI MCP server listed in product nav
  source: https://circleci.com/integrations/
  tier: declared
- app: GitHub
  finding: Copilot routes to hosted models from four vendors
  source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
  tier: declared
apps:
- anchor: github
  counts:
    declared: 4
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
  - route: documentation
    url: https://docs.github.com/en/copilot/reference/ai-models/supported-models
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
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
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.40
      key: AE-110.20.40
      name: Code Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: agent
    name: Anthropic (Claude models in Copilot)
    provider: anthropic
    says: lists Anthropic (Claude models in Copilot) as an integration
    source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.40
      key: AE-110.20.40
      name: Code Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: agent
    name: Google Gemini (in Copilot)
    provider: google-gemini
    says: lists Google Gemini (in Copilot) as an integration
    source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.40
      key: AE-110.20.40
      name: Code Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: agent
    name: OpenAI (GPT models in Copilot)
    provider: openai
    says: lists OpenAI (GPT models in Copilot) as an integration
    source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.40
      key: AE-110.20.40
      name: Code Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: agent
    name: xAI Grok (in Copilot)
    provider: xai
    says: lists xAI Grok (in Copilot) as an integration
    source: https://docs.github.com/en/copilot/reference/ai-models/supported-models
    tier: declared
  kind: commercial
  name: GitHub
  page: /applications/ci-cd-devops/github/
  slug: github
  url: https://github.com/
- anchor: gitlab
  counts:
    declared: 28
    observed: 26
  evidence:
  - route: dependency manifest
    url: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  - route: integrations page
    url: https://docs.gitlab.com/user/project/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: akismet
    provider: akismet
    says: ships the akismet SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: aws-actionmailer-ses
    provider: amazon-ses
    says: ships the aws-actionmailer-ses SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: aws-sdk-cloudformation
    provider: amazon-cloudformation
    says: ships the aws-sdk-cloudformation SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: duo_api
    provider: duo-security
    says: ships the duo_api SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: fog-aliyun
    provider: alibabacloud
    says: ships the fog-aliyun SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: fog-aws / aws-sdk-s3
    provider: amazon-s3
    says: ships the fog-aws / aws-sdk-s3 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: fog-google / google-cloud-storage
    provider: gcp-cloud-storage
    says: ships the fog-google / google-cloud-storage SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: gitlab-fog-azure-rm
    provider: microsoft-azure-blob-storage
    says: ships the gitlab-fog-azure-rm SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: common
    name: google-apis-androidpublisher_v3
    provider: google-play
    says: ships the google-apis-androidpublisher_v3 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin
    provider: google-cloud-platform
    says: ships the google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: google-apis-container_v1
    provider: google-kubernetes-engine
    says: ships the google-apis-container_v1 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: google-apis-iam_v1
    provider: google-cloud-iam
    says: ships the google-apis-iam_v1 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: google-cloud-artifact_registry-v1
    provider: google-artifact-registry
    says: ships the google-cloud-artifact_registry-v1 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: jira-ruby
    provider: jira
    says: ships the jira-ruby SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-alicloud
    provider: alibabacloud
    says: ships the omniauth-alicloud SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-atlassian-oauth2 / atlassian-jwt
    provider: atlassian
    says: ships the omniauth-atlassian-oauth2 / atlassian-jwt SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-auth0
    provider: auth0
    says: ships the omniauth-auth0 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-azure-activedirectory-v2
    provider: microsoft-entra
    says: ships the omniauth-azure-activedirectory-v2 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-github
    provider: github
    says: ships the omniauth-github SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-google-oauth2
    provider: google-identity-platform
    says: ships the omniauth-google-oauth2 SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: omniauth-salesforce
    provider: salesforce
    says: ships the omniauth-salesforce SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: recaptcha
    provider: google-recaptcha
    says: ships the recaptcha SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: sentry-ruby / sentry-rails
    provider: sentry-system
    says: ships the sentry-ruby / sentry-rails SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: slack-messenger
    provider: slack
    says: ships the slack-messenger SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    name: snowplow-tracker
    provider: snowplow
    says: ships the snowplow-tracker SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.20
      key: AE-150.50.20
      name: Number Verification
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: telesignenterprise
    provider: telesign
    says: ships the telesignenterprise SDK or integration code
    source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apple App Store Connect
    provider: apple
    says: lists Apple App Store Connect as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Assembla
    provider: assembla
    says: lists Assembla as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Atlassian Bamboo
    provider: atlassian
    says: lists Atlassian Bamboo as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Beyond Identity
    provider: beyond-identity
    says: lists Beyond Identity as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Buildkite
    provider: buildkite-com
    says: lists Buildkite as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Campfire (37signals)
    provider: campfire-37signals
    says: lists Campfire (37signals) as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://docs.gitlab.com/user/project/integrations/
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
    name: Confluence Cloud
    provider: confluence
    says: lists Confluence Cloud as an integration
    source: https://docs.gitlab.com/user/project/integrations/
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
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: Diffblue Cover
    provider: diffblue
    says: lists Diffblue Cover as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitGuardian
    provider: gitguardian
    says: lists GitGuardian as an integration
    source: https://docs.gitlab.com/user/project/integrations/
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
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Chat
    provider: google-chat
    says: lists Google Chat as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: IBM Engineering Workflow Management
    provider: ibm
    says: lists IBM Engineering Workflow Management as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: JetBrains TeamCity
    provider: teamcity
    says: lists JetBrains TeamCity as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: JetBrains YouTrack
    provider: youtrack
    says: lists JetBrains YouTrack as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Mattermost
    provider: mattermost
    says: lists Mattermost as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Packagist
    provider: packagist
    says: lists Packagist as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pivotal Tracker
    provider: pivotal-tracker
    says: lists Pivotal Tracker as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Pumble
    provider: pumble
    says: lists Pumble as an integration
    source: https://docs.gitlab.com/user/project/integrations/
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
    name: Pushover
    provider: pushover
    says: lists Pushover as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: lists Telegram as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Unify Circuit
    provider: unify-circuit
    says: lists Unify Circuit as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Webex Teams
    provider: webex
    says: lists Webex Teams as an integration
    source: https://docs.gitlab.com/user/project/integrations/
    tier: declared
  kind: open-source-saas
  name: GitLab
  page: /applications/ci-cd-devops/gitlab/
  slug: gitlab
  url: https://gitlab.com/gitlab-org/gitlab
- anchor: gitea
  counts:
    declared: 0
    observed: 24
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/go-gitea/gitea/main/go.mod
  - route: source code
    url: https://github.com/go-gitea/gitea/tree/main/services/migrations
  - route: source code
    url: https://github.com/go-gitea/gitea/tree/main/services/webhook
  - route: source code
    url: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
  - route: source code
    url: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS CodeCommit (migrations/codecommit.go)
    provider: amazon-codecommit
    says: ships the AWS CodeCommit (migrations/codecommit.go) SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/migrations
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
    name: Bitbucket Server (migrations/bitbucketserver.go)
    provider: bitbucket
    says: ships the Bitbucket Server (migrations/bitbucketserver.go) SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/migrations
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
    name: Codebase (migrations/codebase.go)
    provider: codebasehq
    says: ships the Codebase (migrations/codebase.go) SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/migrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: DingTalk webhook
    provider: dingtalk
    says: ships the DingTalk webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord webhook
    provider: discord
    says: ships the Discord webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Feishu webhook
    provider: feishu
    says: ships the Feishu webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
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
    name: GitHub (go-github, migrations/github.go)
    provider: github
    says: ships the GitHub (go-github, migrations/github.go) SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/migrations
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
    name: GitLab (migrations/gitlab.go)
    provider: gitlab
    says: ships the GitLab (migrations/gitlab.go) SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/migrations
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
    name: goth azuread / microsoftonline
    provider: microsoft-entra
    says: ships the goth azuread / microsoftonline SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth bitbucket
    provider: bitbucket
    says: ships the goth bitbucket SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth discord
    provider: discord
    says: ships the goth discord SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth dropbox
    provider: dropbox
    says: ships the goth dropbox SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth facebook
    provider: facebook
    says: ships the goth facebook SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth github
    provider: github
    says: ships the goth github SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
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
    name: goth gitlab
    provider: gitlab
    says: ships the goth gitlab SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
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
    name: goth google
    provider: google-identity-platform
    says: ships the goth google SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth twitter
    provider: x
    says: ships the goth twitter SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    name: goth yandex
    provider: yandex
    says: ships the goth yandex SDK or integration code
    source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: MS Teams webhook
    provider: microsoft-teams
    says: ships the MS Teams webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
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
    name: OneDev (migrations/onedev.go)
    provider: onedev
    says: ships the OneDev (migrations/onedev.go) SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/migrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Packagist webhook
    provider: packagist
    says: ships the Packagist webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack webhook
    provider: slack
    says: ships the Slack webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Telegram webhook
    provider: telegram
    says: ships the Telegram webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: WeChat Work (WeCom) webhook
    provider: wecom
    says: ships the WeChat Work (WeCom) webhook SDK or integration code
    source: https://github.com/go-gitea/gitea/tree/main/services/webhook
    tier: observed
  kind: self-hosted
  name: Gitea
  page: /applications/ci-cd-devops/gitea/
  slug: gitea
  url: https://github.com/go-gitea/gitea
- anchor: woodpecker-ci
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
  - route: source code
    url: https://github.com/woodpecker-ci/woodpecker/tree/main/server/forge
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket Cloud + Data Center forges
    provider: bitbucket
    says: ships the Bitbucket Cloud + Data Center forges SDK or integration code
    source: https://github.com/woodpecker-ci/woodpecker/tree/main/server/forge
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
    name: GitHub forge (go-github)
    provider: github
    says: ships the GitHub forge (go-github) SDK or integration code
    source: https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
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
    name: GitLab forge (gitlab client-go)
    provider: gitlab
    says: ships the GitLab forge (gitlab client-go) SDK or integration code
    source: https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
    tier: observed
  kind: self-hosted
  name: Woodpecker CI
  page: /applications/ci-cd-devops/woodpecker-ci/
  slug: woodpecker-ci
  url: https://github.com/woodpecker-ci/woodpecker
- anchor: coolify
  counts:
    declared: 0
    observed: 21
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
  - route: source code
    url: https://github.com/coollabsio/coolify/tree/main/app/Models
  - route: source code
    url: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
  - route: source code
    url: https://github.com/coollabsio/coolify/tree/main/app/Services
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2600.20
      key: network-configuration-management
      name: Network Configuration Management
      url: /capabilities/network-configuration-management/
      via_parent: null
    credit: null
    layer: common
    name: CloudflareTunnelService / CloudflareTokenValidator
    provider: cloudflare
    says: ships the CloudflareTunnelService / CloudflareTokenValidator SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: DigitalOceanService
    provider: digital-ocean
    says: ships the DigitalOceanService SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: DiscordChannel
    provider: discord
    says: ships the DiscordChannel SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: domain
    name: DopplerService
    provider: doppler
    says: ships the DopplerService SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
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
    name: GithubApp / GithubRunner
    provider: github
    says: ships the GithubApp / GithubRunner SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Models
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
    name: GitlabApp
    provider: gitlab
    says: ships the GitlabApp SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Models
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: HetznerService
    provider: hetzner
    says: ships the HetznerService SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: HostingerService
    provider: hostinger
    says: ships the HostingerService SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: domain
    name: InfisicalService
    provider: infisical
    says: ships the InfisicalService SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
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
    name: PushoverChannel
    provider: pushover
    says: ships the PushoverChannel SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
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
    name: resend/resend-laravel
    provider: resend
    says: ships the resend/resend-laravel SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: SlackChannel
    provider: slack
    says: ships the SlackChannel SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
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
    name: socialiteproviders/clerk
    provider: clerk-com
    says: ships the socialiteproviders/clerk SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    name: socialiteproviders/discord
    provider: discord
    says: ships the socialiteproviders/discord SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    name: socialiteproviders/google
    provider: google-identity-platform
    says: ships the socialiteproviders/google SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    name: socialiteproviders/infomaniak
    provider: infomaniak
    says: ships the socialiteproviders/infomaniak SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    name: socialiteproviders/microsoft-azure
    provider: microsoft-entra
    says: ships the socialiteproviders/microsoft-azure SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    name: socialiteproviders/zitadel
    provider: zitadel
    says: ships the socialiteproviders/zitadel SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    name: stripe/stripe-php
    provider: stripe
    says: ships the stripe/stripe-php SDK or integration code
    source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: TelegramChannel
    provider: telegram
    says: ships the TelegramChannel SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: VultrService
    provider: vultr
    says: ships the VultrService SDK or integration code
    source: https://github.com/coollabsio/coolify/tree/main/app/Services
    tier: observed
  kind: self-hosted
  name: Coolify
  page: /applications/ci-cd-devops/coolify/
  slug: coolify
  url: https://github.com/coollabsio/coolify
- anchor: circleci
  counts:
    declared: 54
    observed: 0
  evidence:
  - route: integrations page
    url: https://circleci.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alcide.io
    provider: alcide
    says: lists Alcide.io as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon ECR
    provider: amazon-ecr
    says: lists Amazon ECR as an integration
    source: https://circleci.com/integrations/
    tier: declared
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
    says: lists Amazon S3 as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Anchore
    provider: anchore
    says: lists Anchore as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-130.10
      key: regulatory-compliance-management
      name: Regulatory Compliance Management
      url: /capabilities/regulatory-compliance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Anecdotes
    provider: anecdotes
    says: lists Anecdotes as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aqua Security
    provider: aqua-security
    says: lists Aqua Security as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: CheckMarx
    provider: checkmarx
    says: lists CheckMarx as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cloudsmith
    provider: cloudsmith
    says: lists Cloudsmith as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: Codecov
    provider: codecov
    says: lists Codecov as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: CodeScene
    provider: codescene
    says: lists CodeScene as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: BC-4210.50
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: domain
    name: ConfigCat
    provider: configcat
    says: lists ConfigCat as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contrast
    provider: contrast-security
    says: lists Contrast as an integration
    source: https://circleci.com/integrations/
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
    name: Coralogix
    provider: coralogix
    says: lists Coralogix as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: Coveralls
    provider: coveralls
    says: lists Coveralls as an integration
    source: https://circleci.com/integrations/
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
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: datree policy
    provider: datree
    says: lists datree policy as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: DeepFactor
    provider: deepfactor
    says: lists DeepFactor as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fortanix
    provider: fortanix
    says: lists Fortanix as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fossa
    provider: fossa
    says: lists Fossa as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitGuardian
    provider: gitguardian
    says: lists GitGuardian as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud GCR
    provider: google-artifact-registry
    says: lists Google Cloud GCR as an integration
    source: https://circleci.com/integrations/
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
    name: Honeybadger
    provider: honeybadger
    says: lists Honeybadger as an integration
    source: https://circleci.com/integrations/
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
    name: Honeycomb
    provider: honeycomb
    says: lists Honeycomb as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Indeni
    provider: indeni
    says: lists Indeni as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lacework
    provider: lacework
    says: lists Lacework as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lightspin
    provider: lightspin
    says: lists Lightspin as an integration
    source: https://circleci.com/integrations/
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
    name: LogDNA (now Mezmo)
    provider: mezmo
    says: lists LogDNA (now Mezmo) as an integration
    source: https://circleci.com/integrations/
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
    name: Logz.io
    provider: logz-io
    says: lists Logz.io as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: NeuVector
    provider: neuvector
    says: lists NeuVector as an integration
    source: https://circleci.com/integrations/
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
    name: New Relic
    provider: new-relic
    says: lists New Relic as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nightfall
    provider: nightfall-ai
    says: lists Nightfall as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: OpsGenie
    provider: opsgenie
    says: lists OpsGenie as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: packagecloud
    provider: packagecloud
    says: lists packagecloud as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: Packtracker
    provider: packtracker
    says: lists Packtracker as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Prisma Cloud
    provider: prisma-cloud
    says: lists Prisma Cloud as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Probely
    provider: probely
    says: lists Probely as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: realMethods
    provider: realmethods
    says: lists realMethods as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rezilion
    provider: rezilion
    says: lists Rezilion as an integration
    source: https://circleci.com/integrations/
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
    name: Rollbar
    provider: rollbar
    says: lists Rollbar as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shiftleft (now Qwiet AI)
    provider: qwiet-ai
    says: lists Shiftleft (now Qwiet AI) as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sken.ai
    provider: sken-ai
    says: lists Sken.ai as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snyk
    provider: snyk
    says: lists Snyk as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: domain
    name: SonarSource
    provider: sonarsource
    says: lists SonarSource as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sonatype
    provider: sonatype
    says: lists Sonatype as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: SOOS
    provider: soos
    says: lists SOOS as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Spectral (SpectralOps, Check Point)
    provider: spectralops
    says: lists Spectral (SpectralOps, Check Point) as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: Squadcast
    provider: squadcast
    says: lists Squadcast as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: StackHawk
    provider: stackhawk
    says: lists StackHawk as an integration
    source: https://circleci.com/integrations/
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
    name: Thundra
    provider: thundra
    says: lists Thundra as an integration
    source: https://circleci.com/integrations/
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
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wallarm
    provider: wallarm
    says: lists Wallarm as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: WhiteSource (now Mend)
    provider: mend
    says: lists WhiteSource (now Mend) as an integration
    source: https://circleci.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: xMatters
    provider: xmatters
    says: lists xMatters as an integration
    source: https://circleci.com/integrations/
    tier: declared
  kind: commercial
  name: CircleCI
  page: /applications/ci-cd-devops/circleci/
  slug: circleci
  url: https://circleci.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: ci-cd-devops
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Software Development - Continuous Integration & Deployment
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---continuous-integration--deployment
- category: Software Development - IDE & Tools
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---ide--tools
- category: Continuous Integration
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Code Quality
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Developer Tools
  store: slack-marketplace
  url: https://slack.com/apps
- category: Developer Tools
  store: zapier
  url: https://zapier.com/apps
name: Code Hosting, CI/CD & DevOps
needs:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring and pipeline tracing
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics in the app
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.40
    key: AE-110.20.40
    name: Code Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  fit: exact
  layer: agent
  why: 'AI coding assistants on hosted models. Gap: AE extension node AE-110.20.40 (Code Generation) fits exactly; slug carries the nearest BC capability because validate.py rejects dotted AE ids'
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: sign in with an external identity provider
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: spam and abuse protection (nearest)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: 'object storage for artifacts, LFS and backups (nearest: no artifact-storage capability)'
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: common
  why: provisioning servers and clusters to deploy to
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  fit: exact
  layer: common
  why: package and container registries
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: MFA, cloud IAM, key authorization
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  fit: exact
  layer: common
  why: publishing builds to app stores
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  fit: exact
  layer: domain
  why: external issue trackers linked to commits and MRs
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: build/deploy event notifications to team chat
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: 'transactional email (notifications, sign-up). Gap: AE extension node AE-150.10.10 (Transactional Email) fits exactly; slug carries the nearest BC capability because validate.py rejects dotted AE ids'
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.20
    key: AE-150.50.20
    name: Number Verification
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: common
  why: 'phone verification at sign-up. Gap: AE extension node AE-150.50.20 (Number Verification) fits exactly; slug carries the nearest BC capability because validate.py rejects dotted AE ids'
- capability:
    attribution: Turbo EA
    id: BC-4210
    key: software-release-deployment-management
    name: Software Release & Deployment Management
    url: /capabilities/software-release-deployment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: external CI servers wired into the forge
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: 'push notifications to devices. Gap: AE extension node AE-150.30 (Push Notifications) fits exactly; slug carries the nearest BC capability because validate.py rejects dotted AE ids'
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: external wiki
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  fit: exact
  layer: domain
  why: coverage, code quality and generated tests
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: security scanning in the pipeline (SAST/SCA/secrets/containers)
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'code hosting / forges: where source lives and CI reads from'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: billing for the hosted edition
- capability:
    attribution: Turbo EA
    id: BC-2600.20
    key: network-configuration-management
    name: Network Configuration Management
    url: /capabilities/network-configuration-management/
    via_parent: null
  fit: nearest
  layer: common
  why: DNS and tunnels for deployed apps (nearest)
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: domain
  why: secrets managers feeding deployments
- capability:
    attribution: Turbo EA
    id: BC-130.10
    key: regulatory-compliance-management
    name: Regulatory Compliance Management
    url: /capabilities/regulatory-compliance-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: compliance evidence collection (nearest)
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: on-call alerting from pipelines
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: 'SMS alerts from pipelines. Gap: AE extension node AE-150.20.10 (SMS) fits exactly; slug carries the nearest BC capability because validate.py rejects dotted AE ids'
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: BC-4210.50
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'feature flags (nearest: no feature-flag capability)'
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 12.2
      apps:
      - CircleCI
      - GitLab
      band: minimal
      in_catalog: true
      kin_score: 6.4
      mcp:
        source: https://github.com/GitGuardian/ggmcp
        status: verified
      name: GitGuardian
      slug: gitguardian
      sources:
      - https://circleci.com/integrations/
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Public APIs
      - Security
      tier: declared
      url: /providers/gitguardian/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - CircleCI
      band: exemplar
      in_catalog: true
      kin_score: 80.5
      mcp:
        source: https://github.com/snyk/studio-mcp
        status: verified
      name: Snyk
      slug: snyk
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Application Security
      - DevSecOps
      - Security
      - Vulnerability Management
      tier: declared
      url: /providers/snyk/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        status: none
      name: WhiteSource (now Mend)
      slug: mend
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Application Security
      - Container Security
      - SAST
      - Software Composition Analysis
      tier: declared
      url: /providers/mend/
    - agent_band: agent-ready
      agent_readiness: 32.9
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 60.7
      mcp:
        status: none
      name: Shiftleft (now Qwiet AI)
      slug: qwiet-ai
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Application Security
      - Company
      - SAST
      - Security
      tier: declared
      url: /providers/qwiet-ai/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 58.2
      mcp:
        source: https://github.com/Checkmarx/cx-agentic-ai
        status: verified
      name: CheckMarx
      slug: checkmarx
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Application Security
      - Code Analysis
      - DevSecOps
      - SAST
      tier: declared
      url: /providers/checkmarx/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 57.6
      mcp:
        status: none
      name: Fossa
      slug: fossa
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Company
      - Open Source
      - Security
      - Software Supply Chain
      tier: declared
      url: /providers/fossa/
    - agent_band: agent-ready
      agent_readiness: 55.1
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        source: https://github.com/Contrast-Security-OSS/mcp-contrast
        status: verified
      name: Contrast
      slug: contrast-security
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - AppSec
      - Application Security
      - IAST
      - RASP
      tier: declared
      url: /providers/contrast-security/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 46.8
      mcp:
        source: https://github.com/stackhawk/stackhawk-mcp
        status: verified
      name: StackHawk
      slug: stackhawk
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - API Security
      - Application Security
      - DAST
      - Security Testing
      tier: declared
      url: /providers/stackhawk/
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 40.8
      mcp:
        source: https://github.com/aquasecurity/trivy-mcp
        status: verified
      name: Aqua Security
      slug: aqua-security
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Cloud-Native
      - Containers
      - Kubernetes
      - Runtime Protection
      tier: declared
      url: /providers/aqua-security/
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        status: none
      name: Nightfall
      slug: nightfall-ai
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Privacy
      - Sensitive Data
      tier: declared
      url: /providers/nightfall-ai/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 38.9
      mcp:
        status: none
      name: Wallarm
      slug: wallarm
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - API Security
      - Cybersecurity
      - Security Testing
      - WAF
      tier: declared
      url: /providers/wallarm/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        source: https://github.com/anchore/grype-mcp
        status: verified
      name: Anchore
      slug: anchore
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Container Security
      - Containers
      - SBOM
      - Software Supply Chain
      tier: declared
      url: /providers/anchore/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: Prisma Cloud
      slug: prisma-cloud
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Cloud Security
      - Cloud-Native
      - Compliance
      - Containers
      tier: declared
      url: /providers/prisma-cloud/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: NeuVector
      slug: neuvector
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Compliance
      - Containers
      - Kubernetes
      - Open Source
      tier: declared
      url: /providers/neuvector/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 22.7
      mcp:
        status: none
      name: Lacework
      slug: lacework
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - CNAPP
      - Cloud Security
      - Compliance
      - Threat Detection
      tier: declared
      url: /providers/lacework/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        source: https://developers.probely.com/mcp/mcp-server-overview
        status: verified
      name: Probely
      slug: probely
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/probely/
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Alcide.io
      slug: alcide
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CircleCI
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: DeepFactor
      slug: deepfactor
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Application Security
      - Company
      - Cybersecurity
      - DevSecOps
      tier: declared
      url: /providers/deepfactor/
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Indeni
      slug: indeni
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Lightspin
      slug: lightspin
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Rezilion
      slug: rezilion
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Sken.ai
      slug: sken-ai
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SOOS
      slug: soos
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Spectral (SpectralOps, Check Point)
      slug: spectralops
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Coolify
      - GitLab
      - Gitea
      - Woodpecker CI
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp: &id001
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      - https://github.com/coollabsio/coolify/tree/main/app/Models
      - https://github.com/go-gitea/gitea/tree/main/services/migrations
      status: profiled
      tags: &id002
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Coolify
      - Gitea
      - Woodpecker CI
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp: &id005
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab (migrations/gitlab.go)
      slug: gitlab
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Models
      - https://github.com/go-gitea/gitea/tree/main/services/migrations
      - https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
      status: profiled
      tags: &id006
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Gitea
      - Woodpecker CI
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp: &id007
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket Server (migrations/bitbucketserver.go)
      slug: bitbucket
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/migrations
      - https://github.com/woodpecker-ci/woodpecker/tree/main/server/forge
      status: profiled
      tags: &id008
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Gitea
      band: developing
      in_catalog: true
      kin_score: 42.2
      mcp:
        status: none
      name: AWS CodeCommit (migrations/codecommit.go)
      slug: amazon-codecommit
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/migrations
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Company
      - Version Control
      tier: observed
      url: /providers/amazon-codecommit/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Gitea
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: unknown
      name: Codebase (migrations/codebase.go)
      slug: codebasehq
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/migrations
      status: profiled
      tags:
      - Company
      - Mercurial
      - Subversion
      - Version Control
      tier: observed
      url: /providers/codebasehq/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Gitea
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        source: https://docs.onedev.io/tutorials/ai/working-with-mcp
        status: documented
      name: OneDev (migrations/onedev.go)
      slug: onedev
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/migrations
      status: profiled
      tags:
      - CI/CD
      - Company
      - Development
      - Version Control
      tier: observed
      url: /providers/onedev/
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 65.7
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 82.6
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: jira-ruby
      slug: jira
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 53.7
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 57.0
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - GitLab
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        source: https://github.com/IBM/mcp
        status: verified
      name: IBM Engineering Workflow Management
      slug: ibm
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - API Management
      - Artificial Intelligence
      - Database
      - IBM
      tier: declared
      url: /providers/ibm/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - GitLab
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: declared
      url: /providers/linear-app/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - GitLab
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Assembla
      slug: assembla
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Cloud Hosting
      - DevOps
      - Project Management
      - Version Control
      tier: declared
      url: /providers/assembla/
    - agent_band: null
      agent_readiness: null
      apps:
      - GitLab
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Pivotal Tracker
      slug: pivotal-tracker
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - GitLab
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: JetBrains YouTrack
      slug: youtrack
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 55.0
      mcp:
        source: https://github.com/SonarSource/sonarqube-mcp-server
        status: verified
      name: SonarSource
      slug: sonarsource
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Code Quality
      - Code Security
      - Company
      - Static Analysis
      tier: declared
      url: /providers/sonarsource/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Codecov
      slug: codecov
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - CI/CD
      - Code Coverage
      - Company
      - DevOps
      tier: declared
      url: /providers/codecov/
    - agent_band: agent-aware
      agent_readiness: 17.1
      apps:
      - GitLab
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        source: https://github.com/diffblue/cover-mcp
        status: verified
      name: Diffblue Cover
      slug: diffblue
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Enterprise
      - Testing
      tier: declared
      url: /providers/diffblue/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 23.6
      mcp:
        status: unknown
      name: Coveralls
      slug: coveralls
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - CI Integration
      - Code Coverage
      - Company
      - Open Source
      tier: declared
      url: /providers/coveralls/
    - agent_band: human-only
      agent_readiness: 1.8
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        source: https://github.com/codescene-oss/codescene-mcp-server
        status: verified
      name: CodeScene
      slug: codescene
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Code Analysis
      - Company
      - Technical Debt
      tier: declared
      url: /providers/codescene/
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: datree policy
      slug: datree
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Packtracker
      slug: packtracker
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - CircleCI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: realMethods
      slug: realmethods
      sources:
      - https://circleci.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - GitLab
      - Gitea
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        status: none
      name: Packagist
      slug: packagist
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: profiled
      tags:
      - Composer
      - Dependency Management
      - PHP
      - Package Registry
      tier: observed
      url: /providers/packagist/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon ECR
      slug: amazon-ecr
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Amazon Web Services
      - Container Images
      - Container Registry
      - Containers
      tier: declared
      url: /providers/amazon-ecr/
    - agent_band: agent-ready
      agent_readiness: 34.1
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 56.9
      mcp:
        source: https://github.com/sonatype/dependency-management-mcp-server
        status: verified
      name: Sonatype
      slug: sonatype
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - SBOM
      - Security
      - Software Supply Chain
      - Vulnerability Management
      tier: declared
      url: /providers/sonatype/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp: &id017
        status: none
      name: Google Cloud GCR
      slug: google-artifact-registry
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags: &id018
      - Artifacts
      - Containers
      - Google Cloud
      - Packages
      tier: declared
      url: /providers/google-artifact-registry/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://docs.cloudsmith.com/integrations/integrating-with-mcp
        status: verified
      name: Cloudsmith
      slug: cloudsmith
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Artifact Management
      - DevOps
      - DevSecOps
      - Developer Tools
      tier: declared
      url: /providers/cloudsmith/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 19.5
      mcp:
        status: none
      name: packagecloud
      slug: packagecloud
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Debian
      - DevOps
      - Package Management
      - Repository Hosting
      tier: declared
      url: /providers/packagecloud/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Coolify
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        source: https://github.com/hostinger/api-mcp-server
        status: verified
      name: HostingerService
      slug: hostinger
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - Cloud
      - Company
      - Domains
      - Hosting
      tier: observed
      url: /providers/hostinger/
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Coolify
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOceanService
      slug: digital-ocean
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Coolify
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        source: https://github.com/vultr/vultr-mcp
        status: verified
      name: VultrService
      slug: vultr
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - Cloud
      - Company
      - Compute
      - Infrastructure
      tier: observed
      url: /providers/vultr/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Coolify
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        status: none
      name: HetznerService
      slug: hetzner
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - Cloud Hosting
      - DNS
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/hetzner/
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Coolify
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://github.com/Infisical/infisical-mcp-server
        status: verified
      name: InfisicalService
      slug: infisical
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - DevOps
      - Developer Tools
      - Secrets Management
      - Security
      tier: observed
      url: /providers/infisical/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Coolify
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://github.com/DopplerHQ/mcp-server
        status: verified
      name: DopplerService
      slug: doppler
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - Configuration Management
      - DevOps
      - SecretOps
      - Secrets Management
      tier: observed
      url: /providers/doppler/
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Fortanix
      slug: fortanix
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Company
      - Encryption
      - Key Management
      - Security
      tier: declared
      url: /providers/fortanix/
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp: &id003
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Atlassian Bamboo
      slug: atlassian
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags: &id004
      - Code
      - Collaboration
      - Platform
      - Productivity
      tier: declared
      url: /providers/atlassian/
    - agent_band: agent-ready
      agent_readiness: 50.6
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/buildkite/buildkite-mcp-server
        status: verified
      name: Buildkite
      slug: buildkite-com
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - CI/CD
      - Continuous Delivery
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/buildkite-com/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - GitLab
      band: developing
      in_catalog: true
      kin_score: 47.0
      mcp:
        source: https://github.com/JetBrains/teamcity-mcp
        status: verified
      name: JetBrains TeamCity
      slug: teamcity
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Build Automation
      - CI/CD
      - Continuous Integration
      - Deployment
      tier: declared
      url: /providers/teamcity/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: BC-4210.50
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        source: https://github.com/configcat/mcp-server
        status: verified
      name: ConfigCat
      slug: configcat
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Cloud
      - Developer Tools
      - Feature Flag
      - Software-as-a-Service
      tier: declared
      url: /providers/configcat/
  - capability:
      attribution: Turbo EA
      id: BC-130.10
      key: regulatory-compliance-management
      name: Regulatory Compliance Management
      url: /capabilities/regulatory-compliance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.8
      apps:
      - CircleCI
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        status: none
      name: Anecdotes
      slug: anecdotes
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Company
      - Compliance
      - Governance
      - Risk Management
      tier: declared
      url: /providers/anecdotes/
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - GitLab
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple App Store Connect
      slug: apple
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
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
      - CircleCI
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp: &id011
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags: &id012
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: declared
      url: /providers/amazon-s3/
  layer: domain
- capabilities:
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
      - Coolify
      - GitLab
      - Gitea
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: omniauth-azure-activedirectory-v2
      slug: microsoft-entra
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Coolify
      - GitLab
      - Gitea
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: omniauth-google-oauth2
      slug: google-identity-platform
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
      - GitLab
      - Gitea
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp: *id001
      name: omniauth-github
      slug: github
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Coolify
      - Gitea
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp: &id009
        status: none
      name: goth discord
      slug: discord
      sources:
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: profiled
      tags: &id010
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: omniauth-salesforce
      slug: salesforce
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp: *id003
      name: omniauth-atlassian-oauth2 / atlassian-jwt
      slug: atlassian
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/atlassian/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Gitea
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp: *id005
      name: goth gitlab
      slug: gitlab
      sources:
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Gitea
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: goth twitter
      slug: x
      sources:
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 46.1
      apps:
      - Coolify
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/clerk/mcp-tools
        status: verified
      name: socialiteproviders/clerk
      slug: clerk-com
      sources:
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - B2B SaaS
      - CIAM
      tier: observed
      url: /providers/clerk-com/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: omniauth-auth0
      slug: auth0
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: observed
      url: /providers/auth0/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Gitea
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp: *id007
      name: goth bitbucket
      slug: bitbucket
      sources:
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Coolify
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: socialiteproviders/zitadel
      slug: zitadel
      sources:
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - Open Source
      tier: observed
      url: /providers/zitadel/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Gitea
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: goth dropbox
      slug: dropbox
      sources:
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Gitea
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: goth facebook
      slug: facebook
      sources:
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - Coolify
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        source: https://github.com/Infomaniak/mcp-server-kdrive
        status: verified
      name: socialiteproviders/infomaniak
      slug: infomaniak
      sources:
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      status: profiled
      tags:
      - Cloud
      - Company
      - Email
      - Hosting
      tier: observed
      url: /providers/infomaniak/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GitLab
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp: &id013
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: omniauth-alicloud
      slug: alibabacloud
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags: &id014
      - Company
      tier: observed
      url: /providers/alibabacloud/
    - agent_band: null
      agent_readiness: null
      apps:
      - Gitea
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: goth yandex
      slug: yandex
      sources:
      - https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - CircleCI
      - Coolify
      - GitLab
      - Gitea
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: slack-messenger
      slug: slack
      sources:
      - https://circleci.com/integrations/
      - https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Coolify
      - GitLab
      - Gitea
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      - https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Coolify
      - GitLab
      - Gitea
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp: *id009
      name: Discord
      slug: discord
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      - https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - GitLab
      - Gitea
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Gitea
      band: minimal
      in_catalog: true
      kin_score: 6.1
      mcp:
        source: https://github.com/open-dingtalk/dingtalk-mcp
        status: verified
      name: DingTalk webhook
      slug: dingtalk
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Enterprise
      tier: observed
      url: /providers/dingtalk/
    - agent_band: null
      agent_readiness: null
      apps:
      - Gitea
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Feishu webhook
      slug: feishu
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Gitea
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: WeChat Work (WeCom) webhook
      slug: wecom
      sources:
      - https://github.com/go-gitea/gitea/tree/main/services/webhook
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 61.1
      apps:
      - GitLab
      band: strong
      in_catalog: true
      kin_score: 64.2
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex Teams
      slug: webex
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: declared
      url: /providers/webex/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - GitLab
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Chat
      slug: google-chat
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Google
      - Google Workspace
      tier: declared
      url: /providers/google-chat/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - GitLab
      band: thin
      in_catalog: true
      kin_score: 37.2
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: declared
      url: /providers/mattermost/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GitLab
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        source: https://pumble.com/help/integrations/automation-workflow-integrations/how-to-use-the-pumble-mcp-server/
        status: verified
      name: Pumble
      slug: pumble
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/pumble/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GitLab
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: unknown
      name: Campfire (37signals)
      slug: campfire-37signals
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Open Source
      - Self-Hosted
      tier: declared
      url: /providers/campfire-37signals/
    - agent_band: null
      agent_readiness: null
      apps:
      - GitLab
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Unify Circuit
      slug: unify-circuit
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.6
      apps:
      - CircleCI
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 79.2
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://circleci.com/integrations/
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: sentry-ruby / sentry-rails
      slug: sentry-system
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - GitHub
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id015
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
      status: profiled
      tags: &id016
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - CircleCI
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: declared
      url: /providers/new-relic/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 64.5
      mcp:
        status: none
      name: Logz.io
      slug: logz-io
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Logging
      - Metrics
      - Observability
      - Tracing
      tier: declared
      url: /providers/logz-io/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 59.9
      mcp:
        source: https://docs.honeycomb.io/integrations/mcp/
        status: verified
      name: Honeycomb
      slug: honeycomb
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data Management
      - Observability
      - Telemetry
      tier: declared
      url: /providers/honeycomb/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - CircleCI
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://coralogix.com/docs/user-guides/mcp-server/overview/
        status: verified
      name: Coralogix
      slug: coralogix
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - AIOps
      - Cloud
      - Monitoring
      - Observability
      tier: declared
      url: /providers/coralogix/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/rollbar/rollbar-mcp-server
        status: verified
      name: Rollbar
      slug: rollbar
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Debugging
      - DevOps
      - Error Tracking
      - Monitoring
      tier: declared
      url: /providers/rollbar/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 44.0
      mcp:
        source: https://github.com/mezmo/mezmo-mcp
        status: verified
      name: LogDNA (now Mezmo)
      slug: mezmo
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Logs
      - Observability
      - Telemetry
      - Telemetry Pipeline
      tier: declared
      url: /providers/mezmo/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://github.com/honeybadger-io/honeybadger-mcp-server
        status: verified
      name: Honeybadger
      slug: honeybadger
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Exception Tracking
      - Uptime Monitoring
      tier: declared
      url: /providers/honeybadger/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CircleCI
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: Thundra
      slug: thundra
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - APM
      - Company
      - Observability
      - Serverless
      tier: declared
      url: /providers/thundra/
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
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: fog-google / google-cloud-storage
      slug: gcp-cloud-storage
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp: *id011
      name: fog-aws / aws-sdk-s3
      slug: amazon-s3
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: gitlab-fog-azure-rm
      slug: microsoft-azure-blob-storage
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GitLab
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp: *id013
      name: fog-aliyun
      slug: alibabacloud
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/alibabacloud/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.5
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: aws-sdk-cloudformation
      slug: amazon-cloudformation
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - CloudFormation
      - DevOps
      - Infrastructure as Code
      tier: observed
      url: /providers/amazon-cloudformation/
    - agent_band: agent-ready
      agent_readiness: 50.7
      apps:
      - GitLab
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin
      slug: google-cloud-platform
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: observed
      url: /providers/google-cloud-platform/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - GitLab
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        source: https://github.com/GoogleCloudPlatform/gke-mcp
        status: verified
      name: google-apis-container_v1
      slug: google-kubernetes-engine
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Cloud-Native
      - Containers
      - Google Cloud
      - Kubernetes
      tier: observed
      url: /providers/google-kubernetes-engine/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - GitLab
      band: developing
      in_catalog: true
      kin_score: 48.5
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: google-apis-iam_v1
      slug: google-cloud-iam
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Google Cloud
      - Identity
      - Identity and Access Management
      - Permissions
      tier: observed
      url: /providers/google-cloud-iam/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - GitLab
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp:
        status: none
      name: duo_api
      slug: duo-security
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Authentication
      - Identity
      - MFA
      - Zero Trust
      tier: observed
      url: /providers/duo-security/
    - agent_band: agent-ready
      agent_readiness: 34.5
      apps:
      - GitLab
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        source: https://github.com/gobeyondidentity/bi-mcp
        status: verified
      name: Beyond Identity
      slug: beyond-identity
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Authentication
      - Identity
      - Passwordless
      - Zero Trust
      tier: declared
      url: /providers/beyond-identity/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - CircleCI
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        status: none
      name: OpsGenie
      slug: opsgenie
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Alerts
      - Incident Management
      - Monitoring
      - On-Call
      tier: declared
      url: /providers/opsgenie/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - CircleCI
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Squadcast
      slug: squadcast
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - DevOps
      - Incident Response
      - On-Call Management
      - SRE
      tier: declared
      url: /providers/squadcast/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - CircleCI
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        status: none
      name: xMatters
      slug: xmatters
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Alerting
      - Incident Management
      - On-Call
      - Service Reliability
      tier: declared
      url: /providers/xmatters/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - GitLab
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        status: none
      name: recaptcha
      slug: google-recaptcha
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: null
      agent_readiness: null
      apps:
      - GitLab
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: akismet
      slug: akismet
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - GitHub
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id015
      name: Firebase Analytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.github.android/latest/
      status: profiled
      tags: *id016
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - GitLab
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://github.com/snowplow/snowplow-cli
        status: verified
      name: snowplow-tracker
      slug: snowplow
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Analytics Platform
      - Behavioral Data
      - Data Collection
      - Data Engineering
      tier: observed
      url: /providers/snowplow/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Coolify
      - GitLab
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      - https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: aws-actionmailer-ses
      slug: amazon-ses
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - Coolify
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: resend/resend-laravel
      slug: resend
      sources:
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 78.0
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Confluence Cloud
      slug: confluence
      sources:
      - https://docs.gitlab.com/user/project/integrations/
      status: profiled
      tags:
      - Collaboration
      - Content Management
      - Documentation
      - Knowledge Base
      tier: declared
      url: /providers/confluence/
  - capability:
      attribution: Turbo EA
      id: BC-2600.20
      key: network-configuration-management
      name: Network Configuration Management
      url: /capabilities/network-configuration-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Coolify
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: CloudflareTunnelService / CloudflareTokenValidator
      slug: cloudflare
      sources:
      - https://github.com/coollabsio/coolify/tree/main/app/Services
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.20
      key: AE-150.50.20
      name: Number Verification
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - GitLab
      band: exemplar
      in_catalog: true
      kin_score: 76.9
      mcp:
        status: none
      name: telesignenterprise
      slug: telesign
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Authentication
      - Communications
      - Fraud Prevention
      - Phone Intelligence
      tier: observed
      url: /providers/telesign/
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
      - Coolify
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: stripe/stripe-php
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
      id: BC-4210.30
      key: release-engineering-management
      name: Release Engineering Management
      url: /capabilities/release-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - GitLab
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp: *id017
      name: google-cloud-artifact_registry-v1
      slug: google-artifact-registry
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags: *id018
      tier: observed
      url: /providers/google-artifact-registry/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - CircleCI
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://circleci.com/integrations/
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - GitLab
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: google-apis-androidpublisher_v3
      slug: google-play
      sources:
      - https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.40
      key: AE-110.20.40
      name: Code Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - GitHub
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic (Claude models in Copilot)
      slug: anthropic
      sources:
      - https://docs.github.com/en/copilot/reference/ai-models/supported-models
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - GitHub
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI (GPT models in Copilot)
      slug: openai
      sources:
      - https://docs.github.com/en/copilot/reference/ai-models/supported-models
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - GitHub
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini (in Copilot)
      slug: google-gemini
      sources:
      - https://docs.github.com/en/copilot/reference/ai-models/supported-models
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: declared
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 38.8
      apps:
      - GitHub
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: xAI Grok (in Copilot)
      slug: xai
      sources:
      - https://docs.github.com/en/copilot/reference/ai-models/supported-models
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: declared
      url: /providers/xai/
  layer: agent
summary:
  coverage_pct: 86.8
  declared_only: 74
  distinct_providers: 129
  in_catalog: 112
  mcp:
    documented: 1
    none: 39
    unchecked: 17
    verified: 69
  mcp_verified: 69
  mean_kin_score: 50.4
  observed: 55
  queued: 17
  reference_apps: 6
title: 'Code Hosting, CI/CD & DevOps: application blueprint'
---
