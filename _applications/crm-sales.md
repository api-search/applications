---
access: understanding
agent_layer:
- app: Twenty
  finding: ships its own MCP server (packages/twenty-server/src/engine/api/mcp) plus a multi-vendor LLM layer (AI SDK) and an E2B code interpreter
  source: https://github.com/twentyhq/twenty/tree/main/packages/twenty-server/src/engine/api/mcp
  tier: observed
- app: EspoCRM
  finding: paid MCP Extension "turns EspoCRM into an MCP server for AI agents"; AI summary / email composer extensions
  source: https://www.espocrm.com/extensions/
  tier: declared
- app: Pipedrive
  finding: 'marketplace banner: "Pipedrive MCP is now available"'
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
apps:
- anchor: twenty
  counts:
    declared: 0
    observed: 20
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
  - route: source code
    url: https://github.com/twentyhq/twenty/blob/main/packages/twenty-server/src/engine/core-modules/code-interpreter/drivers/e2b.driver.ts
  - route: source code
    url: https://github.com/twentyhq/twenty/tree/main/packages/twenty-server/src/engine/api/mcp
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: AWS Lambda
    provider: aws-lambda
    says: ships the AWS Lambda SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    name: Cloudflare
    provider: cloudflare
    says: ships the Cloudflare SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: agent
    name: E2B
    provider: e2b-dev
    says: ships the E2B SDK or integration code
    source: https://github.com/twentyhq/twenty/blob/main/packages/twenty-server/src/engine/core-modules/code-interpreter/drivers/e2b.driver.ts
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
    name: Gmail
    provider: google-gmail
    says: ships the Gmail SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: TypeSafe AI
    provider: typesafe-ai
    says: ships the TypeSafe AI SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: xAI
    provider: xai
    says: ships the xAI SDK or integration code
    source: https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
    tier: observed
  kind: open-source-saas
  name: Twenty
  page: /applications/crm-sales/twenty/
  slug: twenty
  url: https://github.com/twentyhq/twenty
- anchor: espocrm
  counts:
    declared: 11
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/espocrm/espocrm/master/composer.json
  - route: integrations page
    url: https://www.espocrm.com/extensions/
  - route: source code
    url: https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/espocrm/espocrm/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
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
    source: https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: 3CX
    provider: 3cx
    says: lists 3CX as an integration
    source: https://www.espocrm.com/extensions/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Binotel
    provider: binotel
    says: lists Binotel as an integration
    source: https://www.espocrm.com/extensions/
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
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://www.espocrm.com/extensions/
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
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.espocrm.com/extensions/
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
    name: Google Contacts
    provider: google-people
    says: lists Google Contacts as an integration
    source: https://www.espocrm.com/extensions/
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
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.espocrm.com/extensions/
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
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://www.espocrm.com/extensions/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Starface
    provider: starface
    says: lists Starface as an integration
    source: https://www.espocrm.com/extensions/
    tier: declared
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
    says: lists Stripe as an integration
    source: https://www.espocrm.com/extensions/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://www.espocrm.com/extensions/
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
    source: https://www.espocrm.com/extensions/
    tier: declared
  kind: self-hosted
  name: EspoCRM
  page: /applications/crm-sales/espocrm/
  slug: espocrm
  url: https://github.com/espocrm/espocrm
- anchor: suitecrm
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
  - route: source code
    url: https://github.com/salesagility/SuiteCRM/tree/master/include/social
  - route: source code
    url: https://github.com/salesagility/SuiteCRM/tree/master/modules
  - route: source code
    url: https://github.com/salesagility/SuiteCRM/tree/master/modules/Connectors/connectors/sources/ext/rest
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
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
    source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/salesagility/SuiteCRM/tree/master/include/social
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
    name: Google APIs
    provider: google
    says: ships the Google APIs SDK or integration code
    source: https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/salesagility/SuiteCRM/tree/master/modules
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
    source: https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: InsideView
    provider: demandbase
    says: ships the InsideView SDK or integration code
    source: https://github.com/salesagility/SuiteCRM/tree/master/modules/Connectors/connectors/sources/ext/rest
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/salesagility/SuiteCRM/tree/master/include/social
    tier: observed
  kind: self-hosted
  name: SuiteCRM
  page: /applications/crm-sales/suitecrm/
  slug: suitecrm
  url: https://github.com/salesagility/SuiteCRM
- anchor: krayin-crm
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/krayin/laravel-crm/master/composer.json
  - route: source code
    url: https://github.com/krayin/laravel-crm/tree/master/packages/Webkul
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Contacts
    provider: google-people
    says: ships the Google Contacts SDK or integration code
    source: https://github.com/krayin/laravel-crm/tree/master/packages/Webkul
    tier: observed
  kind: self-hosted
  name: Krayin CRM
  page: /applications/crm-sales/krayin-crm/
  slug: krayin-crm
  url: https://github.com/krayin/laravel-crm
- anchor: salesforce
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.salesforce.chatter/latest/
  - route: integrations page
    url: https://www.salesforce.com/products/integrations/
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.salesforce.chatter/latest/
    tier: observed
  kind: commercial
  name: Salesforce
  page: /applications/crm-sales/salesforce/
  slug: salesforce
  url: https://www.salesforce.com/
- anchor: hubspot
  counts:
    declared: 2
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  - route: documentation
    url: https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Analytics)
    provider: firebase
    says: ships the Firebase (Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
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
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
    tier: declared
  kind: commercial
  name: HubSpot
  page: /applications/crm-sales/hubspot/
  slug: hubspot
  url: https://www.hubspot.com/
- anchor: pipedrive
  counts:
    declared: 12
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
  - route: integrations page
    url: https://www.pipedrive.com/en/marketplace
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
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
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Apollo.io
    provider: apollo-io
    says: lists Apollo.io as an integration
    source: https://www.pipedrive.com/en/marketplace
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
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: DocuSign
    provider: docusign
    says: lists DocuSign as an integration
    source: https://www.pipedrive.com/en/marketplace
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
    name: Google Meet
    provider: google-meet
    says: lists Google Meet as an integration
    source: https://www.pipedrive.com/en/marketplace
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
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Oneflow
    provider: oneflow
    says: lists Oneflow as an integration
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
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
    says: lists Stripe as an integration
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Surfe
    provider: surfe
    says: lists Surfe as an integration
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: WhatsApp Business
    provider: whatsapp
    says: lists WhatsApp Business as an integration
    source: https://www.pipedrive.com/en/marketplace
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
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: ''
      key: service-request-management
      name: Service Request Management
      url: null
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://www.pipedrive.com/en/marketplace
    tier: declared
  kind: commercial
  name: Pipedrive
  page: /applications/crm-sales/pipedrive/
  slug: pipedrive
  url: https://www.pipedrive.com/
- anchor: zoho-crm
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.zoho.crm/latest/
  integrations: []
  kind: commercial
  name: Zoho CRM
  page: /applications/crm-sales/zoho-crm/
  slug: zoho-crm
  url: https://www.zoho.com/crm/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: crm-sales
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Customer Relationship Management (CRM)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#customer-relationship-management-crm
- category: Sales
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Sales
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: CRM (Customer Relationship Management)
  store: zapier
  url: https://zapier.com/apps
name: CRM & Sales Pipeline
needs:
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the category itself: accounts, contacts, activities'
- capability:
    attribution: Turbo EA
    id: BC-410.30
    key: opportunity-pipeline-management
    name: Opportunity & Pipeline Management
    url: /capabilities/opportunity-pipeline-management/
    via_parent: null
  fit: exact
  layer: domain
  why: deals and pipeline stages are the core object of a sales CRM
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Stripe)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Sentry)
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: agent
  why: seen in reference apps (OpenAI)
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Amazon S3)
- capability:
    attribution: Turbo EA
    id: BC-850.20
    key: external-communications-management
    name: External Communications Management
    url: /capabilities/external-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: seen in reference apps (Amazon SES)
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: seen in reference apps (AWS Lambda)
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: seen in reference apps (Microsoft Graph)
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Microsoft Entra ID)
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Google Maps)
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Google reCAPTCHA)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: seen in reference apps (Google Contacts)
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: seen in reference apps (Zoom)
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: seen in reference apps (Mailchimp)
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: BC-430.30
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: seen in reference apps (Twilio)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Firebase (Analytics))
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Wootric)
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: seen in reference apps (Microsoft Teams)
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  fit: exact
  layer: domain
  why: seen in reference apps (DocuSign)
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: seen in reference apps (QuickBooks)
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: seen in reference apps (Asana)
- capability:
    attribution: Turbo EA
    id: ''
    key: service-request-management
    name: Service Request Management
    url: null
    via_parent: null
  fit: exact
  layer: domain
  why: seen in reference apps (Zendesk)
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: seen in reference apps (Zapier)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - EspoCRM
      - HubSpot
      - Twenty
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - EspoCRM
      - Twenty
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - EspoCRM
      - HubSpot
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Outlook
      slug: microsoft-outlook
      sources:
      - https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - SuiteCRM
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google APIs
      slug: google
      sources:
      - https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
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
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - EspoCRM
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - EspoCRM
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: 3CX
      slug: 3cx
      sources:
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Artificial Intelligence
      - Communications
      - Company
      - VoIP
      tier: declared
      url: /providers/3cx/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - EspoCRM
      band: minimal
      in_catalog: true
      kin_score: 6.7
      mcp:
        status: unknown
      name: Starface
      slug: starface
      sources:
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Communications
      - Company
      - Unified Communications
      - VoIP
      tier: declared
      url: /providers/starface/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - EspoCRM
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unknown
      name: Binotel
      slug: binotel
      sources:
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Business
      - Cloud
      - Company
      - Telephony
      tier: declared
      url: /providers/binotel/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - SuiteCRM
      band: exemplar
      in_catalog: true
      kin_score: 71.0
      mcp:
        source: https://developer.demandbase.com/docs/mcp
        status: documented
      name: InsideView
      slug: demandbase
      sources:
      - https://github.com/salesagility/SuiteCRM/tree/master/modules/Connectors/connectors/sources/ext/rest
      status: profiled
      tags:
      - AI Agents
      - Account Based Marketing
      - Advertising
      - B2B Marketing
      tier: observed
      url: /providers/demandbase/
    - agent_band: agent-ready
      agent_readiness: 53.7
      apps:
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 77.3
      mcp:
        source: https://developers.surfe.com/mcp
        status: verified
      name: Surfe
      slug: surfe
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - B2B Data
      - Contact Data
      - Data Enrichment
      - Sales Intelligence
      tier: declared
      url: /providers/surfe/
    - agent_band: agent-ready
      agent_readiness: 59.2
      apps:
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://docs.apollo.io/docs/apollo-mcp
        status: verified
      name: Apollo.io
      slug: apollo-io
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - B2B Data
      - Engagement
      - Prospecting
      - Sales Intelligence
      tier: declared
      url: /providers/apollo-io/
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: DocuSign
      slug: docusign
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Pipedrive
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Oneflow
      slug: oneflow
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Contract Lifecycle Management
      - Contract Management
      - Digital Contracts
      - E-Signature
      tier: declared
      url: /providers/oneflow/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - EspoCRM
      - Krayin CRM
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Contacts
      slug: google-people
      sources:
      - https://github.com/krayin/laravel-crm/tree/master/packages/Webkul
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Address Book
      - Contacts
      - Google
      - People
      tier: observed
      url: /providers/google-people/
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - SuiteCRM
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/salesagility/SuiteCRM/tree/master/include/social
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - SuiteCRM
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/salesagility/SuiteCRM/tree/master/include/social
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
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - EspoCRM
      band: strong
      in_catalog: true
      kin_score: 56.2
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - Pipedrive
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: none
      name: Google Meet
      slug: google-meet
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Google
      - Google Workspace
      - Meetings
      - Recording
      tier: declared
      url: /providers/google-meet/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - EspoCRM
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.espocrm.com/extensions/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Pipedrive
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.pipedrive.com/en/marketplace
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
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Pipedrive
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
  - capability:
      attribution: Turbo EA
      id: ''
      key: service-request-management
      name: Service Request Management
      url: null
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.0
      apps:
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: WhatsApp Business
      slug: whatsapp
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
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
      - Pipedrive
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - HubSpot
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - HubSpot
      - Pipedrive
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
      status: profiled
      tags: &id002
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - Salesforce
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.salesforce.chatter/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - EspoCRM
      - SuiteCRM
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/espocrm/espocrm/master/composer.json
      - https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - SuiteCRM
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
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
      - SuiteCRM
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
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
      - EspoCRM
      - Pipedrive
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      - https://www.espocrm.com/extensions/
      - https://www.pipedrive.com/en/marketplace
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
      agent_readiness: 56.7
      apps:
      - Pipedrive
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - HubSpot
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase (Analytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Pipedrive
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
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
      - EspoCRM
      - SuiteCRM
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
      - https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
      - Twenty
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - HubSpot
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Wootric
      slug: wootric
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      status: profiled
      tags:
      - CES
      - CSAT
      - Customer Experience
      - NPS
      tier: observed
      url: /providers/wootric/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - EspoCRM
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp: &id003
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
      status: profiled
      tags: &id004
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - SuiteCRM
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - SuiteCRM
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp: *id003
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/salesagility/SuiteCRM/tree/master/modules
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.7
      apps:
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
        status: verified
      name: AWS Lambda
      slug: aws-lambda
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Serverless
      tier: observed
      url: /providers/aws-lambda/
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
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
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
      - Pipedrive
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.pipedrive.com/en/marketplace
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
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
      - Twenty
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 40.4
      apps:
      - Twenty
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        status: none
      name: TypeSafe AI
      slug: typesafe-ai
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Classification
      - Content Moderation
      - Machine Learning
      tier: observed
      url: /providers/typesafe-ai/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Twenty
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Twenty
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Twenty
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 38.8
      apps:
      - Twenty
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: xAI
      slug: xai
      sources:
      - https://raw.githubusercontent.com/twentyhq/twenty/main/packages/twenty-server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: observed
      url: /providers/xai/
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-native
      agent_readiness: 39.5
      apps:
      - Twenty
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://github.com/e2b-dev/mcp-server
        status: verified
      name: E2B
      slug: e2b-dev
      sources:
      - https://github.com/twentyhq/twenty/blob/main/packages/twenty-server/src/engine/core-modules/code-interpreter/drivers/e2b.driver.ts
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Execution
      - Code Interpreter
      tier: observed
      url: /providers/e2b-dev/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 18
  distinct_providers: 54
  in_catalog: 54
  mcp:
    documented: 2
    none: 18
    unchecked: 0
    verified: 32
  mcp_verified: 32
  mean_kin_score: 60.2
  observed: 36
  queued: 0
  reference_apps: 8
title: 'CRM & Sales Pipeline: application blueprint'
---
