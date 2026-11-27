---
access: understanding
agent_layer:
- app: DocuSign
  finding: integrations page lists MCP connectors for Claude Code, ChatGPT, Gemini Enterprise, Copilot Studio, GitHub Copilot, Perplexity
  source: https://www.docusign.com/integrations
  tier: declared
apps:
- anchor: documenso
  counts:
    declared: 0
    observed: 15
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
  - route: source code
    url: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Browserless
    provider: browserless
    says: ships the Browserless SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    credit: null
    layer: domain
    name: Google Cloud HSM (KMS)
    provider: google-cloud-kms
    says: ships the Google Cloud HSM (KMS) SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    name: Google Vertex AI
    provider: google-vertex-ai
    says: ships the Google Vertex AI SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.40.20
      key: BC-600.40.20
      name: IT Job Scheduling and Batch Operations
      url: /capabilities/it-operations-management/
      via_parent: IT Operations Management
    credit: null
    layer: common
    name: Inngest
    provider: inngest
    says: ships the Inngest SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    name: MailChannels
    provider: mailchannels
    says: ships the MailChannels SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    name: Microsoft sign-in
    provider: microsoft-entra
    says: ships the Microsoft sign-in SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    name: Plain
    provider: plain
    says: ships the Plain SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
    tier: observed
  kind: self-hosted
  name: Documenso
  page: /applications/e-signature-contracts/documenso/
  slug: documenso
  url: https://github.com/documenso/documenso
- anchor: docuseal
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
  - route: documentation
    url: https://github.com/docusealco/docuseal
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
    source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS Secrets Manager
    provider: amazon-secrets-manager
    says: ships the AWS Secrets Manager SDK or integration code
    source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
    source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
    source: https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
    tier: observed
  kind: self-hosted
  name: DocuSeal
  page: /applications/e-signature-contracts/docuseal/
  slug: docuseal
  url: https://github.com/docusealco/docuseal
- anchor: opensign
  counts:
    declared: 1
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
  - route: documentation
    url: https://github.com/OpenSignLabs/OpenSign
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
    source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: eID Easy
    provider: eid-easy
    says: ships the eID Easy SDK or integration code
    source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google APIs
    provider: google
    says: ships the Google APIs SDK or integration code
    source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
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
    source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
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
    source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
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
    source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
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
    says: lists Zapier as an integration
    source: https://github.com/OpenSignLabs/OpenSign
    tier: declared
  kind: self-hosted
  name: OpenSign
  page: /applications/e-signature-contracts/opensign/
  slug: opensign
  url: https://github.com/OpenSignLabs/OpenSign
- anchor: docusign
  counts:
    declared: 10
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  - route: integrations page
    url: https://www.docusign.com/integrations
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Optimizely
    provider: optimizely
    says: ships the Optimizely SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Wootric
    provider: wootric
    says: ships the Wootric SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://www.docusign.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    credit: null
    layer: domain
    name: CLEAR
    provider: clear
    says: lists CLEAR as an integration
    source: https://www.docusign.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.docusign.com/integrations
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
    source: https://www.docusign.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://www.docusign.com/integrations
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
    name: Microsoft Power Automate
    provider: microsoft-power-automate
    says: lists Microsoft Power Automate as an integration
    source: https://www.docusign.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.docusign.com/integrations
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
    source: https://www.docusign.com/integrations
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
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://www.docusign.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://www.docusign.com/integrations
    tier: declared
  kind: commercial
  name: DocuSign
  page: /applications/e-signature-contracts/docusign/
  slug: docusign
  url: https://www.docusign.com/
- anchor: dropbox-sign
  counts:
    declared: 18
    observed: 0
  evidence:
  - route: integrations page
    url: https://sign.dropbox.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: common
    name: Coda
    provider: coda
    says: lists Coda as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Docs
    provider: google-docs
    says: lists Google Docs as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: common
    name: Greenhouse
    provider: greenhouse
    says: lists Greenhouse as an integration
    source: https://sign.dropbox.com/integrations
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
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ironclad
    provider: ironclad
    says: lists Ironclad as an integration
    source: https://sign.dropbox.com/integrations
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
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Word
    provider: microsoft-word
    says: lists Microsoft Word as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: common
    name: PageUp
    provider: pageup
    says: lists PageUp as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Procore
    provider: procore
    says: lists Procore as an integration
    source: https://sign.dropbox.com/integrations
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
    name: QQ Catalyst (Vertafore)
    provider: vertafore
    says: lists QQ Catalyst (Vertafore) as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: common
    name: Recruitee
    provider: recruitee
    says: lists Recruitee as an integration
    source: https://sign.dropbox.com/integrations
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
    source: https://sign.dropbox.com/integrations
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
    source: https://sign.dropbox.com/integrations
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
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://sign.dropbox.com/integrations
    tier: declared
  kind: commercial
  name: Dropbox Sign
  page: /applications/e-signature-contracts/dropbox-sign/
  slug: dropbox-sign
  url: https://sign.dropbox.com/
- anchor: zoho-sign
  counts:
    declared: 24
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.zoho.com/sign/integrations.html
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: Aadhaar eSign (UIDAI)
    provider: uidai
    says: lists Aadhaar eSign (UIDAI) as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: eID Easy
    provider: eid-easy
    says: lists eID Easy as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: eMudhra
    provider: emudhra
    says: lists eMudhra as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    credit: null
    layer: common
    name: Formstack
    provider: formstack
    says: lists Formstack as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: InfoCert
    provider: infocert
    says: lists InfoCert as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    name: Integrately
    provider: integrately
    says: lists Integrately as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OneDrive
    provider: microsoft-onedrive
    says: lists OneDrive as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Outlook
    provider: microsoft-outlook
    says: lists Outlook as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    name: Power Automate
    provider: microsoft-power-automate
    says: lists Power Automate as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: Signicat
    provider: signicat
    says: lists Signicat as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: Singpass
    provider: singpass
    says: lists Singpass as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    credit: null
    layer: domain
    name: Uanataca
    provider: uanataca
    says: lists Uanataca as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    name: Vtiger
    provider: vtiger
    says: lists Vtiger as an integration
    source: https://www.zoho.com/sign/integrations.html
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
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.zoho.com/sign/integrations.html
    tier: declared
  kind: commercial
  name: Zoho Sign
  page: /applications/e-signature-contracts/zoho-sign/
  slug: zoho-sign
  url: https://www.zoho.com/sign/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: e-signature-contracts
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Document Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#document-management
- category: Contract Management
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Sales
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Signatures
  store: zapier
  url: https://zapier.com/apps
name: E-signature & Contract Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: used by google-identity-platform, microsoft-entra
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  fit: exact
  layer: domain
  why: used by amazon-secrets-manager, google-cloud-kms
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: used by amazon-s3, gcp-cloud-storage, microsoft-azure-blob-storage
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: used by amazon-ses, mailchannels, mailgun, resend
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by stripe
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: used by inngest, integrately, make, microsoft-power-automate, zapier
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: used by posthog
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: used by google-vertex-ai
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: used by cloudflare-turnstile
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: nearest
  layer: common
  why: used by plain, servicenow
- capability:
    attribution: Turbo EA
    id: BC-2500.50
    key: electronic-documentation-management
    name: Electronic Documentation Management
    url: /capabilities/electronic-documentation-management/
    via_parent: null
  fit: gap
  layer: domain
  why: used by browserless, formstack, google-docs, microsoft-365, microsoft-word
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: nearest
  layer: common
  why: used by box, dropbox, google, google-drive, google-workspace, microsoft-onedrive
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: used by google-tag-manager
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  fit: exact
  layer: domain
  why: used by clear, eid-easy, emudhra, infocert, signicat, singpass, uanataca, uidai
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: nearest
  layer: common
  why: used by hubspot, microsoft-dynamics-365, pipedrive, salesforce, vertafore, vtiger
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by workday
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: nearest
  layer: common
  why: used by monday-com, procore
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by activecampaign
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: common
  why: used by coda
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by greenhouse, pageup, recruitee
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  fit: exact
  layer: domain
  why: used by ironclad
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by microsoft-teams, slack
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: used by google-gmail, microsoft-outlook
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep links
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash reporting
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature experiments
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app customer feedback
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: AE-160.80
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 6.3
      apps:
      - OpenSign
      - Zoho Sign
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        source: https://github.com/eideasy/eideasy-mcp
        status: verified
      name: eID Easy
      slug: eid-easy
      sources:
      - https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Company
      - E-Signature
      - eID
      - eSealing
      tier: observed
      url: /providers/eid-easy/
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        status: none
      name: Signicat
      slug: signicat
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Authentication
      - Company
      - Digital Identity
      - E-Signature
      tier: declared
      url: /providers/signicat/
    - agent_band: agent-ready
      agent_readiness: 34.1
      apps:
      - Zoho Sign
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: unknown
      name: InfoCert
      slug: infocert
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Company
      - Digital Identity
      - Digital Trust
      - E-Signature
      tier: declared
      url: /providers/infocert/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Zoho Sign
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: none
      name: Singpass
      slug: singpass
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Authentication
      - Company
      - Government
      - Identity
      tier: declared
      url: /providers/singpass/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Zoho Sign
      band: emerging
      in_catalog: true
      kin_score: 17.6
      mcp:
        status: none
      name: eMudhra
      slug: emudhra
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Company
      - Digital Trust
      - Enterprise Software
      - PKI
      tier: declared
      url: /providers/emudhra/
    - agent_band: agent-aware
      agent_readiness: 12.2
      apps:
      - Zoho Sign
      band: emerging
      in_catalog: true
      kin_score: 13.5
      mcp:
        status: unknown
      name: Uanataca
      slug: uanataca
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Company
      - Digital Identity
      - E-Signature
      - Wallets
      tier: declared
      url: /providers/uanataca/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Zoho Sign
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: unknown
      name: Aadhaar eSign (UIDAI)
      slug: uidai
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Authentication
      - Digital Signature
      - Government
      - Identity
      tier: declared
      url: /providers/uidai/
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Dropbox Sign
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: Ironclad
      slug: ironclad
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Contract Lifecycle Management
      - Contracts
      - Legal Tech
      - LegalOps
      tier: declared
      url: /providers/ironclad/
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Documenso
      band: exemplar
      in_catalog: true
      kin_score: 70.9
      mcp:
        status: none
      name: Google Cloud HSM (KMS)
      slug: google-cloud-kms
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
      status: profiled
      tags:
      - Cryptography
      - Encryption
      - Google Cloud
      - Key Management
      tier: observed
      url: /providers/google-cloud-kms/
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.5
      apps:
      - Documenso
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://github.com/browserless/browserless-mcp
        status: verified
      name: Browserless
      slug: browserless
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
      status: profiled
      tags:
      - AI Agents
      - Browser Automation
      - Browser Infrastructure
      - Web Scraping
      tier: observed
      url: /providers/browserless/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - DocuSign
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        status: none
      name: CLEAR
      slug: clear
      sources:
      - https://www.docusign.com/integrations
      status: profiled
      tags:
      - Authentication
      - Company
      - Identity
      - Identity Verification
      tier: declared
      url: /providers/clear/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - DocuSign
      - Dropbox Sign
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://sign.dropbox.com/integrations
      - https://www.docusign.com/integrations
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - DocuSign
      - Dropbox Sign
      - Zoho Sign
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://sign.dropbox.com/integrations
      - https://www.docusign.com/integrations
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Dropbox Sign
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://sign.dropbox.com/integrations
      - https://www.zoho.com/sign/integrations.html
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
      - DocuSign
      - Zoho Sign
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://www.docusign.com/integrations
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - OpenSign
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google APIs
      slug: google
      sources:
      - https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Zoho Sign
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://www.zoho.com/sign/integrations.html
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
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - DocuSign
      - Dropbox Sign
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://sign.dropbox.com/integrations
      - https://www.docusign.com/integrations
      - https://www.zoho.com/sign/integrations.html
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
      - DocuSign
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://sign.dropbox.com/integrations
      - https://www.docusign.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics 365
      slug: microsoft-dynamics-365
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Zoho Sign
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Zoho Sign
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Vtiger
      slug: vtiger
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Artificial Intelligence
      - CRM
      - Company
      - Sales
      tier: declared
      url: /providers/vtiger/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dropbox Sign
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: none
      name: QQ Catalyst (Vertafore)
      slug: vertafore
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Agency Management
      - Insurance
      - Insurtech
      - Property and Casualty
      tier: declared
      url: /providers/vertafore/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Dropbox Sign
      - OpenSign
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://github.com/OpenSignLabs/OpenSign
      - https://sign.dropbox.com/integrations
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - DocuSign
      - Zoho Sign
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Microsoft Power Automate
      slug: microsoft-power-automate
      sources:
      - https://www.docusign.com/integrations
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Automation
      - Business Process
      - Integration
      - Low-Code
      tier: declared
      url: /providers/microsoft-power-automate/
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - Zoho Sign
      band: developing
      in_catalog: true
      kin_score: 45.4
      mcp:
        status: none
      name: Integrately
      slug: integrately
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Automation
      - Business Process Automation
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/integrately/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Zoho Sign
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
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
      - DocuSeal
      - Documenso
      - OpenSign
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      - https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
      - DocuSeal
      - Documenso
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      - https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
      - DocuSeal
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
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
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Docs
      slug: google-docs
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Google Workspace
      - Productivity
      tier: declared
      url: /providers/google-docs/
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Dropbox Sign
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        source: https://learn.microsoft.com/en-us/microsoft-agent-365/mcp-server-reference/word
        status: verified
      name: Microsoft Word
      slug: microsoft-word
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Documents
      - Microsoft 365
      - Office
      - Productivity
      tier: declared
      url: /providers/microsoft-word/
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - Zoho Sign
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        status: none
      name: Formstack
      slug: formstack
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Documents
      - E-Signature
      - Forms
      - Workflow Automation
      tier: declared
      url: /providers/formstack/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Documenso
      - OpenSign
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - DocuSign
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - DocuSign
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
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
      - Documenso
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Documenso
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Documenso
      band: developing
      in_catalog: true
      kin_score: 44.7
      mcp:
        status: none
      name: MailChannels
      slug: mailchannels
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
      status: profiled
      tags:
      - Company
      - Email
      - Platform
      - SMTP
      tier: observed
      url: /providers/mailchannels/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - OpenSign
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
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
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        status: none
      name: Greenhouse
      slug: greenhouse
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Applicant Tracking
      - Greenhouse
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/greenhouse/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Dropbox Sign
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: Recruitee
      slug: recruitee
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Applicant Tracking
      - Hiring
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/recruitee/
    - agent_band: null
      agent_readiness: null
      apps:
      - Dropbox Sign
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: PageUp
      slug: pageup
      sources:
      - https://sign.dropbox.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Documenso
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        source: https://github.com/team-plain/cursor-plugin-mcp
        status: verified
      name: Plain
      slug: plain
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      status: profiled
      tags:
      - Company
      - Customer Service
      - Help Desk
      - Support
      tier: observed
      url: /providers/plain/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - DocuSign
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://www.docusign.com/integrations
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
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
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Zoho Sign
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
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
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook
      slug: microsoft-outlook
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Zoho Sign
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.zoho.com/sign/integrations.html
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: Procore
      slug: procore
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Construction
      - Construction Management
      - Field Productivity
      - Project Management
      tier: declared
      url: /providers/procore/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - DocuSign
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://www.docusign.com/integrations
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Documenso
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft sign-in
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Documenso
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Documenso
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 39.2
      apps:
      - DocuSeal
      band: exemplar
      in_catalog: true
      kin_score: 77.5
      mcp:
        status: none
      name: AWS Secrets Manager
      slug: amazon-secrets-manager
      sources:
      - https://raw.githubusercontent.com/docusealco/docuseal/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Configuration
      - Credentials
      - Rotation
      tier: observed
      url: /providers/amazon-secrets-manager/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - DocuSign
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: Wootric
      slug: wootric
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
      status: profiled
      tags:
      - CES
      - CSAT
      - Customer Experience
      - NPS
      tier: observed
      url: /providers/wootric/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Dropbox Sign
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Documenso
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Vertex AI
      slug: google-vertex-ai
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - DocuSign
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: Workday
      slug: workday
      sources:
      - https://www.docusign.com/integrations
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: declared
      url: /providers/workday/
  - capability:
      attribution: Turbo EA
      id: BC-600.40.20
      key: BC-600.40.20
      name: IT Job Scheduling and Batch Operations
      url: /capabilities/it-operations-management/
      via_parent: IT Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Documenso
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://www.inngest.com/docs/ai-dev-tools/mcp
        status: verified
      name: Inngest
      slug: inngest
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
      status: profiled
      tags:
      - AI Agents
      - AgentKit
      - Background Jobs
      - Connect
      tier: observed
      url: /providers/inngest/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Dropbox Sign
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: Coda
      slug: coda
      sources:
      - https://sign.dropbox.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Docs
      - No-Code
      - Productivity
      tier: declared
      url: /providers/coda/
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
      - DocuSign
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
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
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - DocuSign
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
      status: profiled
      tags: *id002
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
      - Documenso
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.6
      apps:
      - DocuSign
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
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
      - OpenSign
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  layer: common
summary:
  coverage_pct: 98.5
  declared_only: 40
  distinct_providers: 66
  in_catalog: 65
  mcp:
    documented: 2
    none: 27
    unchecked: 1
    verified: 33
  mcp_verified: 33
  mean_kin_score: 57.8
  observed: 26
  queued: 1
  reference_apps: 6
title: 'E-signature & Contract Management: application blueprint'
---
