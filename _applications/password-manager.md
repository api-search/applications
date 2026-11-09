---
access: understanding
agent_layer:
- app: 1Password
  finding: first-party MCP server for 1Password Environments (beta)
  source: https://1password.dev/environments/mcp-server
  tier: declared
- app: Bitwarden
  finding: first-party Bitwarden MCP server (vault management via CLI, org admin via Public API)
  source: https://raw.githubusercontent.com/bitwarden/mcp-server/main/README.md
  tier: declared
apps:
- anchor: bitwarden
  counts:
    declared: 21
    observed: 19
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
    layer: domain
    name: Terraform
    provider: terraform
    says: lists Terraform as an integration
    source: https://bitwarden.com/integrations/
    tier: declared
  kind: open-source-saas
  name: Bitwarden
  page: /applications/password-manager/bitwarden/
  slug: bitwarden
  url: https://github.com/bitwarden/server
- anchor: vaultwarden
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/Cargo.toml
  - route: source code
    url: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
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
    name: Bitwarden
    provider: bitwarden
    says: ships the Bitwarden SDK or integration code
    source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.30
      key: AE-230.40.30
      name: Website Favicon & Logo Lookup
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: domain
    name: DuckDuckGo
    provider: duckduckgo
    says: ships the DuckDuckGo SDK or integration code
    source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Duo Security
    provider: duo-security
    says: ships the Duo Security SDK or integration code
    source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.30
      key: AE-230.40.30
      name: Website Favicon & Logo Lookup
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: domain
    name: Google
    provider: google
    says: ships the Google SDK or integration code
    source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    credit: null
    layer: domain
    name: Have I Been Pwned
    provider: have-i-been-pwned
    says: ships the Have I Been Pwned SDK or integration code
    source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Yubico
    provider: yubico
    says: ships the Yubico SDK or integration code
    source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
    tier: observed
  kind: self-hosted
  name: Vaultwarden
  page: /applications/password-manager/vaultwarden/
  slug: vaultwarden
  url: https://github.com/dani-garcia/vaultwarden
- anchor: psono
  counts:
    declared: 0
    observed: 14
  evidence:
  - route: dependency manifest
    url: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
  - route: source code
    url: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
  integrations:
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
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
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
    name: Brevo
    provider: brevo
    says: ships the Brevo SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Duo Security
    provider: duo-security
    says: ships the Duo Security SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
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
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: iVALT
    provider: ivalt
    says: ships the iVALT SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    name: Mailchimp (Mandrill)
    provider: mailchimp
    says: ships the Mailchimp (Mandrill) SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    name: Mailjet
    provider: mailjet
    says: ships the Mailjet SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
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
    name: SparkPost
    provider: sparkpost
    says: ships the SparkPost SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Yubico
    provider: yubico
    says: ships the Yubico SDK or integration code
    source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
    tier: observed
  kind: self-hosted
  name: Psono
  page: /applications/password-manager/psono/
  slug: psono
  url: https://gitlab.com/esaqa/psono/psono-server
- anchor: passbolt
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/passbolt/passbolt_api/master/composer.json
  - route: source code
    url: https://github.com/passbolt/passbolt_api/tree/master/plugins/PassboltCe/MultiFactorAuthentication/src/Utility
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Duo Security
    provider: duo-security
    says: ships the Duo Security SDK or integration code
    source: https://github.com/passbolt/passbolt_api/tree/master/plugins/PassboltCe/MultiFactorAuthentication/src/Utility
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Yubico
    provider: yubico
    says: ships the Yubico SDK or integration code
    source: https://raw.githubusercontent.com/passbolt/passbolt_api/master/composer.json
    tier: observed
  kind: self-hosted
  name: Passbolt
  page: /applications/password-manager/passbolt/
  slug: passbolt
  url: https://github.com/passbolt/passbolt_api
- anchor: keepassxc
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: source code
    url: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/core/Config.cpp
  - route: source code
    url: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/gui/IconDownloader.cpp
  - route: source code
    url: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/networking/HibpDownloader.cpp
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.30
      key: AE-230.40.30
      name: Website Favicon & Logo Lookup
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: domain
    name: DuckDuckGo
    provider: duckduckgo
    says: ships the DuckDuckGo SDK or integration code
    source: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/gui/IconDownloader.cpp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    credit: null
    layer: domain
    name: Have I Been Pwned
    provider: have-i-been-pwned
    says: ships the Have I Been Pwned SDK or integration code
    source: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/networking/HibpDownloader.cpp
    tier: observed
  kind: self-hosted
  name: KeePassXC
  page: /applications/password-manager/keepassxc/
  slug: keepassxc
  url: https://github.com/keepassxreboot/keepassxc
- anchor: 1password
  counts:
    declared: 17
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.onepassword.android/latest/
  - route: documentation
    url: https://developer.1password.com/docs/ci-cd/
  - route: documentation
    url: https://support.1password.com/events-reporting/
  - route: documentation
    url: https://support.1password.com/sso/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.onepassword.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Blumira
    provider: blumira
    says: lists Blumira as an integration
    source: https://support.1password.com/events-reporting/
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
    name: CircleCI
    provider: circleci
    says: lists CircleCI as an integration
    source: https://developer.1password.com/docs/ci-cd/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: CrowdStrike
    provider: crowdstrike
    says: lists CrowdStrike as an integration
    source: https://support.1password.com/events-reporting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://support.1password.com/events-reporting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Duo Security
    provider: duo-security
    says: lists Duo Security as an integration
    source: https://support.1password.com/sso/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Elastic
    provider: elastic
    says: lists Elastic as an integration
    source: https://support.1password.com/events-reporting/
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
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://developer.1password.com/docs/ci-cd/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: JumpCloud
    provider: jumpcloud
    says: lists JumpCloud as an integration
    source: https://support.1password.com/sso/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: lists Microsoft Entra ID as an integration
    source: https://support.1password.com/sso/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Sentinel
    provider: microsoft-sentinel
    says: lists Microsoft Sentinel as an integration
    source: https://support.1password.com/events-reporting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://support.1password.com/sso/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: OneLogin
    provider: onelogin
    says: lists OneLogin as an integration
    source: https://support.1password.com/sso/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Panther
    provider: panther
    says: lists Panther as an integration
    source: https://support.1password.com/events-reporting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rapid7
    provider: rapid7
    says: lists Rapid7 as an integration
    source: https://support.1password.com/events-reporting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Splunk
    provider: splunk
    says: lists Splunk as an integration
    source: https://support.1password.com/events-reporting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sumo Logic
    provider: sumo-logic
    says: lists Sumo Logic as an integration
    source: https://support.1password.com/events-reporting/
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
    name: Terraform
    provider: terraform
    says: lists Terraform as an integration
    source: https://developer.1password.com/docs/ci-cd/
    tier: declared
  kind: commercial
  name: 1Password
  page: /applications/password-manager/1password/
  slug: 1password
  url: https://1password.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: password-manager
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Password Managers
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#password-managers
name: Password Manager
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: subscription billing
- capability:
    attribution: API Evangelist extension
    id: AE-240.70.20
    key: AE-240.70.20
    name: Crypto Payment Acceptance
    url: /capabilities/stablecoin-payments/
    via_parent: Stablecoin Payments
  fit: exact
  layer: common
  why: BitPay for premium plans
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: iOS premium via App Store
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: every vault offers YubiKey/Duo second factors
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  fit: exact
  layer: domain
  why: breached-password checks (HIBP) are core to the category
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: invites, verification, emergency access mail
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: event queues (nearest; no message-queue node)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: attachments and file sends
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: hosted vault data store
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: vault sync and login approval push
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: server feature rollout
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: notifications into Slack/Teams
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: domain
  why: business tiers unlock vaults via the customer IdP
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: SCIM user provisioning from HRIS/IdP
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: vault event logs stream to SIEMs
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: managed client deployment
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: domain
  why: secrets delivered into CI/CD and IaC
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.30
    key: AE-230.40.30
    name: Website Favicon & Logo Lookup
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: domain
  why: vault item icons fetched from DuckDuckGo/Google/Bitwarden favicon services; no node fits
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.6
      apps:
      - 1Password
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 79.2
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - 1Password
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic
      slug: elastic
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: declared
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - 1Password
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: declared
      url: /providers/splunk/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - 1Password
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 59.7
      mcp:
        source: https://github.com/microsoft/sentinel-data-exploration-mcp
        status: verified
      name: Microsoft Sentinel
      slug: microsoft-sentinel
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Microsoft
      - SIEM
      - SOAR
      - Security
      tier: declared
      url: /providers/microsoft-sentinel/
    - agent_band: agent-ready
      agent_readiness: 34.5
      apps:
      - 1Password
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://github.com/panther-labs/mcp-panther
        status: verified
      name: Panther
      slug: panther
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Company
      - Detection and Response
      - SIEM
      - Security
      tier: declared
      url: /providers/panther/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - 1Password
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 51.7
      mcp:
        status: none
      name: Blumira
      slug: blumira
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Cloud
      - Company
      - Security
      - Software-as-a-Service
      tier: declared
      url: /providers/blumira/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - 1Password
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 47.1
      mcp:
        source: https://docs.sumologic.com/docs/search/mobot/
        status: documented
      name: Sumo Logic
      slug: sumo-logic
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Security
      tier: declared
      url: /providers/sumo-logic/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - 1Password
      - Bitwarden
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        source: https://github.com/rapid7/rapid7-bulk-export-mcp
        status: verified
      name: Rapid7
      slug: rapid7
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - SIEM
      - Security
      - Vulnerability Management
      - XDR
      tier: declared
      url: /providers/rapid7/
    - agent_band: agent-ready
      agent_readiness: 35.1
      apps:
      - 1Password
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://github.com/CrowdStrike/falcon-mcp
        status: verified
      name: CrowdStrike
      slug: crowdstrike
      sources:
      - https://support.1password.com/events-reporting/
      status: profiled
      tags:
      - Cybersecurity
      - Endpoint Detection and Response
      - Endpoint Security
      - Threat Intelligence
      tier: declared
      url: /providers/crowdstrike/
    - agent_band: agent-ready
      agent_readiness: 56.5
      apps:
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Huntress
      slug: huntress
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Managed Detection and Response
      - Security
      tier: declared
      url: /providers/huntress/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - 1Password
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 78.0
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/sso/
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - 1Password
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/sso/
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - 1Password
      - Bitwarden
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
        status: verified
      name: JumpCloud
      slug: jumpcloud
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/sso/
      status: profiled
      tags:
      - Directory Services
      - Identity
      - MFA
      - SSO
      tier: declared
      url: /providers/jumpcloud/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - 1Password
      - Bitwarden
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://bitwarden.com/integrations/
      - https://support.1password.com/sso/
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: declared
      url: /providers/onelogin/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: declared
      url: /providers/auth0/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Bitwarden
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: declared
      url: /providers/keycloak/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - 1Password
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp: &id001
        status: none
      name: Duo Security
      slug: duo-security
      sources:
      - https://support.1password.com/sso/
      status: profiled
      tags: &id002
      - Authentication
      - Identity
      - MFA
      - Zero Trust
      tier: declared
      url: /providers/duo-security/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Bitwarden
      - Passbolt
      - Psono
      - Vaultwarden
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        status: none
      name: Yubico
      slug: yubico
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      - https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
      status: profiled
      tags:
      - Authentication
      - Company
      - Enterprise
      - Security
      tier: observed
      url: /providers/yubico/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Bitwarden
      - Passbolt
      - Psono
      - Vaultwarden
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp: *id001
      name: Duo Security
      slug: duo-security
      sources:
      - https://github.com/passbolt/passbolt_api/tree/master/plugins/PassboltCe/MultiFactorAuthentication/src/Utility
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/duo-security/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Psono
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: unknown
      name: iVALT
      slug: ivalt
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Identity
      - Security
      tier: observed
      url: /providers/ivalt/
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - 1Password
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://bitwarden.com/integrations/
      - https://developer.1password.com/docs/ci-cd/
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - 1Password
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://github.com/hashicorp/terraform-mcp-server
        status: verified
      name: Terraform
      slug: terraform
      sources:
      - https://bitwarden.com/integrations/
      - https://developer.1password.com/docs/ci-cd/
      status: profiled
      tags:
      - Cloud Infrastructure
      - DevOps
      - Infrastructure as Code
      - Open Source
      tier: declared
      url: /providers/terraform/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: declared
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 56.1
      apps:
      - 1Password
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/CircleCI-Public/mcp-server-circleci
        status: verified
      name: CircleCI
      slug: circleci
      sources:
      - https://developer.1password.com/docs/ci-cd/
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/circleci/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Bitwarden
      - KeePassXC
      - Vaultwarden
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        status: none
      name: Have I Been Pwned
      slug: have-i-been-pwned
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
      - https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
      - https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/networking/HibpDownloader.cpp
      status: profiled
      tags:
      - Data Breaches
      - Identity
      - Pwned Passwords
      - Security
      tier: observed
      url: /providers/have-i-been-pwned/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.30
      key: AE-230.40.30
      name: Website Favicon & Logo Lookup
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - KeePassXC
      - Vaultwarden
      band: developing
      in_catalog: true
      kin_score: 39.8
      mcp:
        status: none
      name: DuckDuckGo
      slug: duckduckgo
      sources:
      - https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
      - https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/gui/IconDownloader.cpp
      status: profiled
      tags:
      - AI Chat
      - Browser
      - Privacy
      - Search
      tier: observed
      url: /providers/duckduckgo/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Vaultwarden
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google
      slug: google
      sources:
      - https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        status: none
      name: Microsoft Intune
      slug: microsoft-intune
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - App Protection
      - Compliance
      - Device Configuration
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-intune/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Bitwarden
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: Rippling
      slug: rippling
      sources:
      - https://bitwarden.com/integrations/
      status: profiled
      tags:
      - HCM
      - Human Resources
      - IT
      - Payroll
      tier: declared
      url: /providers/rippling/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Bitwarden
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Bitwarden
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 82.2
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp (Mandrill)
      slug: mailchimp
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Psono
      band: developing
      in_catalog: true
      kin_score: 50.1
      mcp:
        source: https://github.com/mailgun/mailjet-mcp-server
        status: verified
      name: Mailjet
      slug: mailjet
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/mailjet/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Psono
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        status: none
      name: SparkPost
      slug: sparkpost
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/sparkpost/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Psono
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.5
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Azure
      slug: microsoft-azure
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Service Bus
      slug: azure-service-bus
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Cloud
      - Enterprise
      - Message Broker
      - Microsoft Azure
      tier: observed
      url: /providers/azure-service-bus/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
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
      - 1Password
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
      - https://reports.exodus-privacy.eu.org/en/reports/com.onepassword.android/latest/
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
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.x8bit.bitwarden/latest/
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
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Bitwarden
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Psono
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
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
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        status: unknown
      name: Azure Notification Hubs
      slug: microsoft-azure-notification-hubs
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Cross-Platform
      - Messaging
      - Mobile
      - Notification
      tier: observed
      url: /providers/microsoft-azure-notification-hubs/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - Vaultwarden
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://github.com/bitwarden/mcp-server
        status: verified
      name: Bitwarden
      slug: bitwarden
      sources:
      - https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
      status: profiled
      tags:
      - Open Source
      - Password Manager
      - Security
      - Vault
      tier: observed
      url: /providers/bitwarden/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.20
      key: AE-240.70.20
      name: Crypto Payment Acceptance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Bitwarden
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: BitPay
      slug: bitpay
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Bitcoin
      - Blockchain
      - Cryptocurrency
      - Payments
      tier: observed
      url: /providers/bitpay/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.6
      apps:
      - Bitwarden
      band: exemplar
      in_catalog: true
      kin_score: 85.5
      mcp:
        source: https://launchdarkly.com/docs/home/getting-started/mcp
        status: verified
      name: LaunchDarkly
      slug: launchdarkly
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Observability
      tier: observed
      url: /providers/launchdarkly/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Bitwarden
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Settings/GlobalSettings.cs
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Bitwarden
      band: developing
      in_catalog: true
      kin_score: 40.9
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Cosmos DB
      slug: azure-cosmos-db
      sources:
      - https://raw.githubusercontent.com/bitwarden/server/main/src/Core/Core.csproj
      status: profiled
      tags:
      - Database
      - Document Database
      - NoSQL
      - Vector Search
      tier: observed
      url: /providers/azure-cosmos-db/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 23
  distinct_providers: 54
  in_catalog: 54
  mcp:
    documented: 1
    none: 19
    unchecked: 0
    verified: 32
  mcp_verified: 32
  mean_kin_score: 59.0
  observed: 31
  queued: 0
  reference_apps: 6
title: 'Password Manager: application blueprint'
---
