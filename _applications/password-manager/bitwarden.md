---
app: Bitwarden
app_slug: bitwarden
app_url: https://github.com/bitwarden/server
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: domain
  name: Configuration & Secrets Management
  providers:
  - GitHub
  - GitLab
  - Terraform
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.60
  key: AE-160.60
  layer: domain
  name: Credential Security
  providers:
  - Have I Been Pwned
  url: /capabilities/credential-security/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: domain
  name: End-User Computing Management
  providers:
  - Microsoft Intune
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: domain
  name: Identity & Access Management
  providers:
  - Rippling
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.20
  key: AE-160.10.20
  layer: domain
  name: Multi-Factor Authentication
  providers:
  - Duo Security
  - Yubico
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Auth0
  - Google Workspace
  - JumpCloud
  - Keycloak
  - Microsoft Entra ID
  - Okta
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - Blumira
  - Datadog
  - Elastic
  - Huntress
  - Microsoft Sentinel
  - Panther
  - Rapid7
  - Splunk
  - Sumo Logic
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-240.70.20
  key: AE-240.70.20
  layer: common
  name: Crypto Payment Acceptance
  providers:
  - BitPay
  url: /capabilities/stablecoin-payments/
  via_parent: Stablecoin Payments
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - LaunchDarkly
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Apple
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon SQS
  - Azure Service Bus
  - Microsoft Azure
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Azure Cosmos DB
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Braintree
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Azure Notification Hubs
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: password-manager
  name: Password Manager
  url: /applications/password-manager/
counts:
  declared: 21
  observed: 19
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.x8bit.bitwarden/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
- route: integrations page
  url: https://bitwarden.com/integrations/
- route: source code
  url: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
integrations:
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
    mcp: &id001
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: common
  name: Amazon SQS
  provider: amazon-sqs
  says: ships the Amazon SQS SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id005
      status: none
    slug: apple
    status: profiled
    tags: &id006
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple
  provider: apple
  says: ships the Apple SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
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
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.9
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id011
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-cosmos-db
    status: profiled
    tags: &id012
    - Database
    - Document Database
    - NoSQL
    - Vector Search
    url: /providers/azure-cosmos-db/
  layer: common
  name: Azure Cosmos DB
  provider: azure-cosmos-db
  says: ships the Azure Cosmos DB SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.5
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id013
      status: unknown
    slug: microsoft-azure-notification-hubs
    status: profiled
    tags: &id014
    - Cross-Platform
    - Messaging
    - Mobile
    - Notification
    url: /providers/microsoft-azure-notification-hubs/
  layer: common
  name: Azure Notification Hubs
  provider: microsoft-azure-notification-hubs
  says: ships the Azure Notification Hubs SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id015
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-service-bus
    status: profiled
    tags: &id016
    - Cloud
    - Enterprise
    - Message Broker
    - Microsoft Azure
    url: /providers/azure-service-bus/
  layer: common
  name: Azure Service Bus
  provider: azure-service-bus
  says: ships the Azure Service Bus SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.70.20
    key: AE-240.70.20
    name: Crypto Payment Acceptance
    url: /capabilities/stablecoin-payments/
    via_parent: Stablecoin Payments
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id017
      status: none
    slug: bitpay
    status: profiled
    tags: &id018
    - Bitcoin
    - Blockchain
    - Cryptocurrency
    - Payments
    url: /providers/bitpay/
  layer: common
  name: BitPay
  provider: bitpay
  says: ships the BitPay SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
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
    agent_band: agent-ready
    agent_readiness: 53.6
    band: developing
    in_catalog: true
    kin_score: 44.7
    mcp: &id021
      status: none
    slug: braintree
    status: profiled
    tags: &id022
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: common
  name: Braintree
  provider: braintree
  says: ships the Braintree SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id025
      status: none
    slug: duo-security
    status: profiled
    tags: &id026
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: domain
  name: Duo Security
  provider: duo-security
  says: ships the Duo Security SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id029
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id030
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.x8bit.bitwarden/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id037
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id038
    - Data Breaches
    - Identity
    - Pwned Passwords
    - Security
    url: /providers/have-i-been-pwned/
  layer: domain
  name: Have I Been Pwned
  provider: have-i-been-pwned
  says: ships the Have I Been Pwned SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.7
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id045
      source: https://launchdarkly.com/docs/home/getting-started/mcp
      status: verified
    slug: launchdarkly
    status: profiled
    tags: &id046
    - Experimentation
    - Feature Flags
    - Feature Management
    - Observability
    url: /providers/launchdarkly/
  layer: common
  name: LaunchDarkly
  provider: launchdarkly
  says: ships the LaunchDarkly SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id047
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id048
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: common
  name: Microsoft Azure
  provider: microsoft-azure
  says: ships the Microsoft Azure SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id055
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id056
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
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
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id067
      status: none
    slug: sendgrid
    status: profiled
    tags: &id068
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
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
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
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
    mcp: &id073
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id074
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.0
    band: strong
    in_catalog: true
    kin_score: 58.0
    mcp: &id079
      status: none
    slug: yubico
    status: profiled
    tags: &id080
    - Authentication
    - Company
    - Enterprise
    - Security
    url: /providers/yubico/
  layer: domain
  name: Yubico
  provider: yubico
  says: ships the Yubico SDK or integration code
  source: https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
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
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id007
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id008
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: domain
  name: Auth0
  provider: auth0
  says: lists Auth0 as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.3
    mcp: &id019
      status: none
    slug: blumira
    status: profiled
    tags: &id020
    - Cloud
    - Company
    - Security
    - Software-as-a-Service
    url: /providers/blumira/
  layer: domain
  name: Blumira
  provider: blumira
  says: lists Blumira as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id023
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id024
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id027
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id028
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elastic
  provider: elastic
  says: lists Elastic as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id031
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id032
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id033
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id034
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id035
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id036
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: domain
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id039
      status: none
    slug: huntress
    status: profiled
    tags: &id040
    - Company
    - Cybersecurity
    - Managed Detection and Response
    - Security
    url: /providers/huntress/
  layer: domain
  name: Huntress
  provider: huntress
  says: lists Huntress as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
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
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id041
      source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
      status: verified
    slug: jumpcloud
    status: profiled
    tags: &id042
    - Directory Services
    - Identity
    - MFA
    - SSO
    url: /providers/jumpcloud/
  layer: domain
  name: JumpCloud
  provider: jumpcloud
  says: lists JumpCloud as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id043
      status: none
    slug: keycloak
    status: profiled
    tags: &id044
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: domain
  name: Keycloak
  provider: keycloak
  says: lists Keycloak as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
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
    mcp: &id049
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id050
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: lists Microsoft Entra ID as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id051
      status: none
    slug: microsoft-intune
    status: profiled
    tags: &id052
    - App Protection
    - Compliance
    - Device Configuration
    - Microsoft Azure
    url: /providers/microsoft-intune/
  layer: domain
  name: Microsoft Intune
  provider: microsoft-intune
  says: lists Microsoft Intune as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id053
      source: https://github.com/microsoft/sentinel-data-exploration-mcp
      status: verified
    slug: microsoft-sentinel
    status: profiled
    tags: &id054
    - Microsoft
    - SIEM
    - SOAR
    - Security
    url: /providers/microsoft-sentinel/
  layer: domain
  name: Microsoft Sentinel
  provider: microsoft-sentinel
  says: lists Microsoft Sentinel as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id057
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id058
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id059
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id060
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: domain
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id061
      source: https://github.com/panther-labs/mcp-panther
      status: verified
    slug: panther
    status: profiled
    tags: &id062
    - Company
    - Detection and Response
    - SIEM
    - Security
    url: /providers/panther/
  layer: domain
  name: Panther
  provider: panther
  says: lists Panther as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id063
      source: https://github.com/rapid7/rapid7-bulk-export-mcp
      status: verified
    slug: rapid7
    status: profiled
    tags: &id064
    - SIEM
    - Security
    - Vulnerability Management
    - XDR
    url: /providers/rapid7/
  layer: domain
  name: Rapid7
  provider: rapid7
  says: lists Rapid7 as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id065
      status: none
    slug: rippling
    status: profiled
    tags: &id066
    - HCM
    - Human Resources
    - IT
    - Payroll
    url: /providers/rippling/
  layer: domain
  name: Rippling
  provider: rippling
  says: lists Rippling as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id071
      status: none
    slug: splunk
    status: profiled
    tags: &id072
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id075
      source: https://docs.sumologic.com/docs/search/mobot/
      status: documented
    slug: sumo-logic
    status: profiled
    tags: &id076
    - Logging
    - Monitoring
    - Observability
    - Security
    url: /providers/sumo-logic/
  layer: domain
  name: Sumo Logic
  provider: sumo-logic
  says: lists Sumo Logic as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id077
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id078
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
  layer: domain
  name: Terraform
  provider: terraform
  says: lists Terraform as an integration
  source: https://bitwarden.com/integrations/
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/password-manager/bitwarden/
providers:
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id003
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id004
  url: /providers/amazon-sqs/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id005
  name: Apple
  slug: apple
  status: profiled
  tags: *id006
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id007
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id008
  url: /providers/auth0/
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
  agent_readiness: 30.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id011
  name: Azure Cosmos DB
  slug: azure-cosmos-db
  status: profiled
  tags: *id012
  url: /providers/azure-cosmos-db/
- agent_band: agent-aware
  agent_readiness: 20.5
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id013
  name: Azure Notification Hubs
  slug: microsoft-azure-notification-hubs
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-notification-hubs/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id015
  name: Azure Service Bus
  slug: azure-service-bus
  status: profiled
  tags: *id016
  url: /providers/azure-service-bus/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id017
  name: BitPay
  slug: bitpay
  status: profiled
  tags: *id018
  url: /providers/bitpay/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.3
  mcp: *id019
  name: Blumira
  slug: blumira
  status: profiled
  tags: *id020
  url: /providers/blumira/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id021
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id022
  url: /providers/braintree/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id023
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id024
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id025
  name: Duo Security
  slug: duo-security
  status: profiled
  tags: *id026
  url: /providers/duo-security/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id027
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id028
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id029
  name: Firebase (Crashlytics)
  slug: google-firebase
  status: profiled
  tags: *id030
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id031
  name: GitHub
  slug: github
  status: profiled
  tags: *id032
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id033
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id034
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id035
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id036
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id037
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id038
  url: /providers/have-i-been-pwned/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id039
  name: Huntress
  slug: huntress
  status: profiled
  tags: *id040
  url: /providers/huntress/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id041
  name: JumpCloud
  slug: jumpcloud
  status: profiled
  tags: *id042
  url: /providers/jumpcloud/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id043
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id044
  url: /providers/keycloak/
- agent_band: agent-ready
  agent_readiness: 59.7
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id045
  name: LaunchDarkly
  slug: launchdarkly
  status: profiled
  tags: *id046
  url: /providers/launchdarkly/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id047
  name: Microsoft Azure
  slug: microsoft-azure
  status: profiled
  tags: *id048
  url: /providers/microsoft-azure/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id049
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id050
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id051
  name: Microsoft Intune
  slug: microsoft-intune
  status: profiled
  tags: *id052
  url: /providers/microsoft-intune/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id053
  name: Microsoft Sentinel
  slug: microsoft-sentinel
  status: profiled
  tags: *id054
  url: /providers/microsoft-sentinel/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id055
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id056
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id057
  name: Okta
  slug: okta
  status: profiled
  tags: *id058
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id059
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id060
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id061
  name: Panther
  slug: panther
  status: profiled
  tags: *id062
  url: /providers/panther/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id063
  name: Rapid7
  slug: rapid7
  status: profiled
  tags: *id064
  url: /providers/rapid7/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id065
  name: Rippling
  slug: rippling
  status: profiled
  tags: *id066
  url: /providers/rippling/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id067
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id068
  url: /providers/sendgrid/
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
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id071
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id072
  url: /providers/splunk/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id073
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id074
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id075
  name: Sumo Logic
  slug: sumo-logic
  status: profiled
  tags: *id076
  url: /providers/sumo-logic/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id077
  name: Terraform
  slug: terraform
  status: profiled
  tags: *id078
  url: /providers/terraform/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id079
  name: Yubico
  slug: yubico
  status: profiled
  tags: *id080
  url: /providers/yubico/
siblings:
- name: 1Password
  rows: 18
  url: /applications/password-manager/1password/
- name: KeePassXC
  rows: 2
  url: /applications/password-manager/keepassxc/
- name: Passbolt
  rows: 2
  url: /applications/password-manager/passbolt/
- name: Psono
  rows: 14
  url: /applications/password-manager/psono/
- name: Vaultwarden
  rows: 6
  url: /applications/password-manager/vaultwarden/
sitemap: true
title: 'Bitwarden: Password Manager reference app'
---
