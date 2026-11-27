---
access: understanding
agent_layer: []
apps:
- anchor: open-collective
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/opencollective/opencollective-api/blob/main/package.json
  - route: source code
    url: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
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
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: BC-3740.30
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare
    provider: cloudflare
    says: ships the Cloudflare SDK or integration code
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: GoCardless Bank Account Data (Nordigen)
    provider: nordigen
    says: ships the GoCardless Bank Account Data (Nordigen) SDK or integration code
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
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
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Plaid
    provider: plaid
    says: ships the Plaid SDK or integration code
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
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
    source: https://github.com/opencollective/opencollective-api/blob/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.40
      key: cross-border-payment-management
      name: Cross-Border Payment Management
      url: /capabilities/cross-border-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wise (TransferWise)
    provider: wise
    says: ships the Wise (TransferWise) SDK or integration code
    source: https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
    tier: observed
  kind: open-source-saas
  name: Open Collective
  page: /applications/donations-crowdfunding/open-collective/
  slug: open-collective
  url: https://github.com/opencollective/opencollective-api
- anchor: liberapay
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
  - route: source code
    url: https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
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
    name: Amazon Web Services
    provider: amazon-web-services
    says: ships the Amazon Web Services SDK or integration code
    source: https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
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
    source: https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
    tier: observed
  kind: self-hosted
  name: Liberapay
  page: /applications/donations-crowdfunding/liberapay/
  slug: liberapay
  url: https://github.com/liberapay/liberapay.com
- anchor: hcb-(hack-club-bank)
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://github.com/hackclub/hcb/blob/main/Gemfile
  - route: source code
    url: https://github.com/hackclub/hcb/tree/main/app/services
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Airtable
    provider: airtable
    says: ships the Airtable SDK or integration code
    source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    name: AppSignal
    provider: appsignal
    says: ships the AppSignal SDK or integration code
    source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    name: AWS KMS
    provider: amazon-kms
    says: ships the AWS KMS SDK or integration code
    source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.10
      key: payment-initiation-management
      name: Payment Initiation Management
      url: /capabilities/payment-initiation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Column
    provider: column
    says: ships the Column SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    name: Google Workspace
    provider: google-workspace
    says: ships the Google Workspace SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Plaid
    provider: plaid
    says: ships the Plaid SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.60
      key: card-issuance-management
      name: Card Issuance Management
      url: /capabilities/card-issuance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe Issuing
    provider: stripe
    says: ships the Stripe Issuing SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.40
      key: tax-reporting-compliance
      name: Tax Reporting & Compliance
      url: /capabilities/tax-reporting-compliance/
      via_parent: null
    credit: null
    layer: domain
    name: TaxBandits
    provider: taxbandits
    says: ships the TaxBandits SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/hackclub/hcb/tree/main/app/services
    tier: observed
  kind: open-source-saas
  name: HCB (Hack Club Bank)
  page: /applications/donations-crowdfunding/hcb-hack-club-bank/
  slug: hcb-hack-club-bank
  url: https://github.com/hackclub/hcb
- anchor: givewp
  counts:
    declared: 1
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/impress-org/givewp/blob/develop/composer.json
  - route: integrations page
    url: https://givewp.com/addons/
  - route: source code
    url: https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://givewp.com/addons/
    tier: declared
  kind: self-hosted
  name: GiveWP
  page: /applications/donations-crowdfunding/givewp/
  slug: givewp
  url: https://github.com/impress-org/givewp
- anchor: givebutter
  counts:
    declared: 50
    observed: 0
  evidence:
  - route: integrations page
    url: https://givebutter.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: AddEvent
    provider: addevent
    says: lists AddEvent as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: Amilia
    provider: amilia
    says: lists Amilia as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bloomerang
    provider: bloomerang
    says: lists Bloomerang as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Cash App
    provider: cash-app
    says: lists Cash App as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Chariot (DAFpay)
    provider: chariot
    says: lists Chariot (DAFpay) as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10
      key: AE-110.10
      name: Model Inference
      url: /capabilities/model-inference/
      via_parent: null
    credit: null
    layer: agent
    name: ChatGPT (OpenAI)
    provider: openai
    says: lists ChatGPT (OpenAI) as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10
      key: AE-110.10
      name: Model Inference
      url: /capabilities/model-inference/
      via_parent: null
    credit: null
    layer: agent
    name: Claude (Anthropic)
    provider: anthropic
    says: lists Claude (Anthropic) as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    credit: null
    layer: domain
    name: DonorSearch
    provider: donorsearch
    says: lists DonorSearch as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.30
      key: AE-230.30.30
      name: Employer Matching-Gift Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Double the Donation
    provider: double-the-donation
    says: lists Double the Donation as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Facebook / Meta fundraising
    provider: facebook
    says: lists Facebook / Meta fundraising as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: common
    name: Giphy
    provider: giphy
    says: lists Giphy as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10
      key: AE-150.10
      name: Email
      url: /capabilities/email/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: GoDaddy
    provider: godaddy
    says: lists GoDaddy as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
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
    says: lists Google Maps as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Little Green Light
    provider: little-green-light
    says: lists Little Green Light as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://givebutter.com/integrations
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
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    credit: null
    layer: domain
    name: POINT (volunteering app)
    provider: point-app
    says: lists POINT (volunteering app) as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Raiser's Edge NXT (Blackbaud)
    provider: blackbaud
    says: lists Raiser's Edge NXT (Blackbaud) as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Storyraise
    provider: storyraise
    says: lists Storyraise as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: ThankView
    provider: thankview
    says: lists ThankView as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: common
    name: Twitch
    provider: twitch
    says: lists Twitch as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Twitter
    provider: x
    says: lists Twitter as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Venmo
    provider: venmo
    says: lists Venmo as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: common
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    credit: null
    layer: domain
    name: VolunteerHub
    provider: volunteerhub
    says: lists VolunteerHub as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Weebly
    provider: weebly
    says: lists Weebly as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: common
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://givebutter.com/integrations
    tier: declared
  kind: commercial
  name: Givebutter
  page: /applications/donations-crowdfunding/givebutter/
  slug: givebutter
  url: https://givebutter.com/
- anchor: patreon
  counts:
    declared: 16
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
  - route: integrations page
    url: https://www.patreon.com/apps
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
    tier: observed
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: 99designs
    provider: 99designs
    says: lists 99designs as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: ConvertKit (Kit)
    provider: convertkit
    says: lists ConvertKit (Kit) as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Crowdcast
    provider: crowdcast
    says: lists Crowdcast as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Discourse
    provider: discourse
    says: lists Discourse as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40
      key: AE-180.40
      name: Game Publishing & Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: null
    credit: null
    layer: domain
    name: itch.io
    provider: itch-io
    says: lists itch.io as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.60
      key: card-issuance-management
      name: Card Issuance Management
      url: /capabilities/card-issuance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Karat (creator card)
    provider: karat-financial
    says: lists Karat (creator card) as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    credit: null
    layer: common
    name: Keeper
    provider: keeper-security
    says: lists Keeper as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3280.50
      key: cash-and-treasury-operations
      name: Cash and Treasury Operations
      url: /capabilities/cash-and-treasury-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Mercury
    provider: mercury
    says: lists Mercury as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10
      key: AE-140.10
      name: Storefront Platforms
      url: /capabilities/storefront-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Sellfy
    provider: sellfy
    says: lists Sellfy as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30
      key: AE-110.30
      name: Speech & Voice
      url: /capabilities/speech-voice/
      via_parent: null
    credit: null
    layer: common
    name: Sonix
    provider: sonix
    says: lists Sonix as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: ToneDen
    provider: toneden
    says: lists ToneDen as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: common
    name: TubeBuddy
    provider: tubebuddy
    says: lists TubeBuddy as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: common
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.patreon.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://www.patreon.com/apps
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
    source: https://www.patreon.com/apps
    tier: declared
  kind: commercial
  name: Patreon
  page: /applications/donations-crowdfunding/patreon/
  slug: patreon
  url: https://www.patreon.com/
- anchor: gofundme-pro-(classy)
  counts:
    declared: 47
    observed: 0
  evidence:
  - route: integrations page
    url: https://pro.gofundme.com/c/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Redshift
    provider: amazon-redshift
    says: lists Amazon Redshift as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Blackbaud CRM / Raiser's Edge NXT
    provider: blackbaud
    says: lists Blackbaud CRM / Raiser's Edge NXT as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bloomerang
    provider: bloomerang
    says: lists Bloomerang as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.70
      key: AE-140.70
      name: Social & Creator Commerce
      url: /capabilities/social-creator-commerce/
      via_parent: null
    credit: null
    layer: domain
    name: Bonfire
    provider: bonfire
    says: lists Bonfire as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    name: BrightVine
    provider: brightvine
    says: lists BrightVine as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Bytespree
    provider: bytespree
    says: lists Bytespree as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10
      key: AE-130.10
      name: Activity & Fitness Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: null
    credit: null
    layer: domain
    name: Charity Miles
    provider: charity-miles
    says: lists Charity Miles as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: CiviCRM
    provider: civicrm
    says: lists CiviCRM as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Daxko
    provider: daxko
    says: lists Daxko as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: DonorDock
    provider: donordock
    says: lists DonorDock as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: DonorDrive
    provider: donordrive
    says: lists DonorDrive as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: DonorPerfect
    provider: donorperfect
    says: lists DonorPerfect as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.30
      key: AE-230.30.30
      name: Employer Matching-Gift Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Double the Donation
    provider: double-the-donation
    says: lists Double the Donation as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: EverGiving
    provider: evergiving
    says: lists EverGiving as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: EveryAction (Bonterra)
    provider: everyaction
    says: lists EveryAction (Bonterra) as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Facebook / Meta Pixel / Meta CAPI
    provider: facebook
    says: lists Facebook / Meta Pixel / Meta CAPI as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Feathr
    provider: feathr
    says: lists Feathr as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: GivingIQ (formerly DonateStock)
    provider: givingiq
    says: lists GivingIQ (formerly DonateStock) as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: GoodUnited
    provider: goodunited
    says: lists GoodUnited as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
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
    says: lists Google Tag Manager as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: Grassroots Unwired
    provider: grassroots-unwired
    says: lists Grassroots Unwired as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Humanitru
    provider: humanitru
    says: lists Humanitru as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kindful
    provider: kindful
    says: lists Kindful as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Little Green Light
    provider: little-green-light
    says: lists Little Green Light as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    name: Microsoft Dynamics
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Mobile Commons
    provider: mobile-commons
    says: lists Mobile Commons as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Neon One
    provider: neonone
    says: lists Neon One as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: NetForum
    provider: netforum
    says: lists NetForum as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nuclavis
    provider: nuclavis
    says: lists Nuclavis as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    name: Omatic
    provider: omatic
    says: lists Omatic as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    name: Salesforce (NPSP, Nonprofit Cloud)
    provider: salesforce
    says: lists Salesforce (NPSP, Nonprofit Cloud) as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salsa Engage
    provider: salsa-labs
    says: lists Salsa Engage as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    name: SyncSmart
    provider: syncsmart
    says: lists SyncSmart as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Tatango
    provider: tatango
    says: lists Tatango as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Tealium
    provider: tealium
    says: lists Tealium as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tessitura
    provider: tessitura
    says: lists Tessitura as an integration
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Virtuous
    provider: virtuous
    says: lists Virtuous as an integration
    source: https://pro.gofundme.com/c/integrations/
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
    source: https://pro.gofundme.com/c/integrations/
    tier: declared
  kind: commercial
  name: GoFundMe Pro (Classy)
  page: /applications/donations-crowdfunding/gofundme-pro-classy/
  slug: gofundme-pro-classy
  url: https://pro.gofundme.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: donations-crowdfunding
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Social
  store: google-play
  url: https://play.google.com/store/apps/category/SOCIAL
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
- category: Nonprofit
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Fundraising
  store: zapier
  url: https://zapier.com/apps
name: Donations & Crowdfunding
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: one-time and recurring card donations
- capability:
    attribution: API Evangelist extension
    id: AE-140.30
    key: AE-140.30
    name: Consumer Payment Options
    url: /capabilities/consumer-payment-options/
    via_parent: null
  fit: exact
  layer: domain
  why: wallets, P2P apps and DAF giving at checkout
- capability:
    attribution: Turbo EA
    id: BC-1340.40
    key: cross-border-payment-management
    name: Cross-Border Payment Management
    url: /capabilities/cross-border-payment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: paying out expenses across currencies
- capability:
    attribution: Turbo EA
    id: BC-1340.10
    key: payment-initiation-management
    name: Payment Initiation Management
    url: /capabilities/payment-initiation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ACH/wire disbursement from fiscal-sponsor accounts
- capability:
    attribution: Turbo EA
    id: BC-1340.60
    key: card-issuance-management
    name: Card Issuance Management
    url: /capabilities/card-issuance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: spend cards for projects and creators
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: fiscal hosts reconcile real bank transactions
- capability:
    attribution: Turbo EA
    id: BC-3280.50
    key: cash-and-treasury-operations
    name: Cash and Treasury Operations
    url: /capabilities/cash-and-treasury-operations/
    via_parent: null
  fit: nearest
  layer: domain
  why: creator banking perks
- capability:
    attribution: Turbo EA
    id: BC-220.40
    key: tax-reporting-compliance
    name: Tax Reporting & Compliance
    url: /capabilities/tax-reporting-compliance/
    via_parent: null
  fit: exact
  layer: domain
  why: 1099s and donation receipts
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: the donor CRM is where every gift lands
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  fit: exact
  layer: domain
  why: peer-to-peer, event and face-to-face fundraising
- capability:
    attribution: API Evangelist extension
    id: AE-924
    key: AE-924
    name: Volunteer Management
    url: /capabilities/volunteer-management/
    via_parent: null
  fit: exact
  layer: domain
  why: volunteer scheduling beside donations
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: general CRMs used as donor databases
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: appeals, newsletters, ad pixels
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: impact reports
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: gift reconciliation to the ledger
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: sharing campaigns, member communities
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: common
  why: livestream fundraising and video thank-yous
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: common
  why: embedding donation forms
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: syncing gifts to other systems
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: fundraising data exports
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: conversion tracking on giving pages
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: card-testing fraud on donation forms
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  fit: exact
  layer: common
  why: social login
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  fit: exact
  layer: common
  why: key management / password manager
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  fit: exact
  layer: common
  why: text-to-give and verification
- capability:
    attribution: API Evangelist extension
    id: AE-150.10
    key: AE-150.10
    name: Email
    url: /capabilities/email/
    via_parent: null
  fit: exact
  layer: common
  why: sending receipts
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: virtual events
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: nearest
  layer: common
  why: event calendar adds
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: receipts and media
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: Workspace accounts for projects
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: spreadsheets and boards
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: gift notifications
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: campaign page analytics
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  fit: exact
  layer: common
  why: event locations
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: common
  why: campaign graphics
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: common
  why: GIFs on campaign pages
- capability:
    attribution: API Evangelist extension
    id: AE-110.10
    key: AE-110.10
    name: Model Inference
    url: /capabilities/model-inference/
    via_parent: null
  fit: exact
  layer: agent
  why: AI writing of appeals
- capability:
    attribution: API Evangelist extension
    id: AE-110.30
    key: AE-110.30
    name: Speech & Voice
    url: /capabilities/speech-voice/
    via_parent: null
  fit: exact
  layer: common
  why: transcription for creators
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: nearest
  layer: domain
  why: program registration
- capability:
    attribution: Turbo EA
    id: BC-4800.20.10
    key: BC-4800.20.10
    name: Prospect Research & Identification
    url: /capabilities/donor-relationship-management/
    via_parent: Donor Relationship Management
  fit: exact
  layer: domain
  why: donor wealth screening
- capability:
    attribution: API Evangelist extension
    id: AE-180.40
    key: AE-180.40
    name: Game Publishing & Distribution
    url: /capabilities/game-publishing-distribution/
    via_parent: null
  fit: exact
  layer: domain
  why: creator game distribution
- capability:
    attribution: API Evangelist extension
    id: AE-140.10
    key: AE-140.10
    name: Storefront Platforms
    url: /capabilities/storefront-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: creator digital-goods shops
- capability:
    attribution: API Evangelist extension
    id: AE-140.70
    key: AE-140.70
    name: Social & Creator Commerce
    url: /capabilities/social-creator-commerce/
    via_parent: null
  fit: nearest
  layer: domain
  why: merch fundraising
- capability:
    attribution: API Evangelist extension
    id: AE-130.10
    key: AE-130.10
    name: Activity & Fitness Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: null
  fit: nearest
  layer: domain
  why: fitness-based fundraising
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Raiser's Edge NXT (Blackbaud)
      slug: blackbaud
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/blackbaud/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: thin
      in_catalog: true
      kin_score: 30.0
      mcp:
        status: none
      name: Bloomerang
      slug: bloomerang
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/bloomerang/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        status: unknown
      name: Little Green Light
      slug: little-green-light
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Donor Management
      - Fundraising
      - Nonprofit Software
      - Online Donations
      tier: declared
      url: /providers/little-green-light/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - GoFundMe Pro (Classy)
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: Neon One
      slug: neonone
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/neonone/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        status: unknown
      name: DonorPerfect
      slug: donorperfect
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Company
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/donorperfect/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: unknown
      name: Tessitura
      slug: tessitura
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Arts
      - Company
      - Culture
      - Non-Profit
      tier: declared
      url: /providers/tessitura/
    - agent_band: agent-aware
      agent_readiness: 14.7
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 22.2
      mcp:
        status: unknown
      name: Virtuous
      slug: virtuous
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Company
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/virtuous/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 21.8
      mcp:
        source: https://docs.civicrm.org/
        status: verified
      name: CiviCRM
      slug: civicrm
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Community
      - Non-Profit
      - Open Source
      tier: declared
      url: /providers/civicrm/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        source: https://www.donordock.com/mcp
        status: verified
      name: DonorDock
      slug: donordock
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Donor Management
      - Fundraising
      - Non-Profit
      - Software-as-a-Service
      tier: declared
      url: /providers/donordock/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 18.2
      mcp:
        status: none
      name: Daxko
      slug: daxko
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Fitness
      - Non-Profit
      - Software
      tier: declared
      url: /providers/daxko/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Humanitru
      slug: humanitru
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - CRM
      - Company
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/humanitru/
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: EveryAction (Bonterra)
      slug: everyaction
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Kindful
      slug: kindful
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: NetForum
      slug: netforum
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Salsa Engage
      slug: salsa-labs
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - GiveWP
      - Givebutter
      - HCB (Hack Club Bank)
      - Liberapay
      - Open Collective
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: &id003
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      - https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
      - https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
      status: profiled
      tags: &id004
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - GiveWP
      - Liberapay
      - Open Collective
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp: &id001
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
      - https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
      - https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
      status: profiled
      tags: &id002
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - GiveWP
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://givewp.com/addons/
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: AE-140.30
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 40.8
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Cash App
      slug: cash-app
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Financial Services
      - Fintech
      - Payments
      - United States
      tier: declared
      url: /providers/cash-app/
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-native
      agent_readiness: 61.6
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: Chariot (DAFpay)
      slug: chariot
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Charitable Giving
      - Donor-Advised Funds
      - Non-Profit
      - Payments
      tier: declared
      url: /providers/chariot/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp: *id001
      name: PayPal
      slug: paypal
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Venmo
      slug: venmo
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/venmo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: unknown
      name: GivingIQ (formerly DonateStock)
      slug: givingiq
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Charity
      - Company
      - Donations
      - Fintech
      tier: declared
      url: /providers/givingiq/
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - GoFundMe Pro (Classy)
      band: developing
      in_catalog: true
      kin_score: 42.3
      mcp:
        status: unknown
      name: EverGiving
      slug: evergiving
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Integration
      - Non-Profit
      tier: declared
      url: /providers/evergiving/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        status: none
      name: GoodUnited
      slug: goodunited
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - Social Media
      tier: declared
      url: /providers/goodunited/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: unknown
      name: Nuclavis
      slug: nuclavis
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Fundraising
      - Mobile
      - Non-Profit
      - P2P
      tier: declared
      url: /providers/nuclavis/
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: DonorDrive
      slug: donordrive
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Donation Platform
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/donordrive/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: none
      name: Grassroots Unwired
      slug: grassroots-unwired
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - Political Campaigns
      tier: declared
      url: /providers/grassroots-unwired/
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 51.1
      apps:
      - HCB (Hack Club Bank)
      - Open Collective
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://plaid.com/docs/resources/mcp/
        status: verified
      name: Plaid
      slug: plaid
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
      status: profiled
      tags:
      - Bank Accounts
      - Finance
      - Fintech
      - Open Banking
      tier: observed
      url: /providers/plaid/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Collective
      band: minimal
      in_catalog: true
      kin_score: 4.2
      mcp:
        source: https://github.com/gocardless/gc-mcp
        status: verified
      name: GoCardless Bank Account Data (Nordigen)
      slug: nordigen
      sources:
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
      status: profiled
      tags:
      - Finance
      - Public APIs
      tier: observed
      url: /providers/nordigen/
  - capability:
      attribution: Turbo EA
      id: BC-1340.60
      key: card-issuance-management
      name: Card Issuance Management
      url: /capabilities/card-issuance-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - HCB (Hack Club Bank)
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: *id003
      name: Stripe Issuing
      slug: stripe
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/stripe/
    - agent_band: null
      agent_readiness: null
      apps:
      - Patreon
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Karat (creator card)
      slug: karat-financial
      sources:
      - https://www.patreon.com/apps
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.30
      key: AE-230.30.30
      name: Employer Matching-Gift Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: unknown
      name: Double the Donation
      slug: double-the-donation
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Matching Gifts
      - Non-Profit
      tier: declared
      url: /providers/double-the-donation/
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: none
      name: VolunteerHub
      slug: volunteerhub
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Non-Profit
      - Recruiting
      - Scheduling
      - Volunteer Management
      tier: declared
      url: /providers/volunteerhub/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Givebutter
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unknown
      name: POINT (volunteering app)
      slug: point-app
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/point-app/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10
      key: AE-130.10
      name: Activity & Fitness Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: unknown
      name: Charity Miles
      slug: charity-miles
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Charity
      - Company
      - Fitness
      - Mobile App
      tier: declared
      url: /providers/charity-miles/
  - capability:
      attribution: Turbo EA
      id: BC-3280.50
      key: cash-and-treasury-operations
      name: Cash and Treasury Operations
      url: /capabilities/cash-and-treasury-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://mercury.com/mcp
        status: verified
      name: Mercury
      slug: mercury
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Banking
      - Fintech
      - Startups
      - Treasury
      tier: declared
      url: /providers/mercury/
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 20.8
      mcp:
        status: unknown
      name: Storyraise
      slug: storyraise
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/storyraise/
  - capability:
      attribution: Turbo EA
      id: BC-1340.40
      key: cross-border-payment-management
      name: Cross-Border Payment Management
      url: /capabilities/cross-border-payment-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.7
      apps:
      - Open Collective
      band: developing
      in_catalog: true
      kin_score: 40.1
      mcp:
        status: none
      name: Wise (TransferWise)
      slug: wise
      sources:
      - https://github.com/opencollective/opencollective-api/tree/main/server/paymentProviders
      status: profiled
      tags:
      - Banking
      - Cross-Border
      - Foreign Exchange
      - Payments
      tier: observed
      url: /providers/wise/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        status: none
      name: Amilia
      slug: amilia
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Membership
      - Recreation
      - Software
      tier: declared
      url: /providers/amilia/
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40
      key: AE-180.40
      name: Game Publishing & Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        status: none
      name: itch.io
      slug: itch-io
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Game Distribution
      - Game Marketplace
      - Games
      - Indie Games
      tier: declared
      url: /providers/itch-io/
  - capability:
      attribution: Turbo EA
      id: BC-1340.10
      key: payment-initiation-management
      name: Payment Initiation Management
      url: /capabilities/payment-initiation-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - HCB (Hack Club Bank)
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp:
        status: none
      name: Column
      slug: column
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      status: profiled
      tags:
      - ACH
      - Banking
      - Banking as a Service
      - Fintech
      tier: observed
      url: /providers/column/
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        status: none
      name: DonorSearch
      slug: donorsearch
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Donor Research
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/donorsearch/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.70
      key: AE-140.70
      name: Social & Creator Commerce
      url: /capabilities/social-creator-commerce/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - GoFundMe Pro (Classy)
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        status: unknown
      name: Bonfire
      slug: bonfire
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Fundraising
      - Merchandising
      tier: declared
      url: /providers/bonfire/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10
      key: AE-140.10
      name: Storefront Platforms
      url: /capabilities/storefront-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Patreon
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        source: https://sellfy.com/mcp/
        status: verified
      name: Sellfy
      slug: sellfy
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Digital Products
      - E-Commerce
      - Payments
      - Software-as-a-Service
      tier: declared
      url: /providers/sellfy/
  - capability:
      attribution: Turbo EA
      id: BC-220.40
      key: tax-reporting-compliance
      name: Tax Reporting & Compliance
      url: /capabilities/tax-reporting-compliance/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - HCB (Hack Club Bank)
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: TaxBandits
      slug: taxbandits
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      status: profiled
      tags:
      - Automation
      - Efiling
      - IRS
      - Tax
      tier: observed
      url: /providers/taxbandits/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: unknown
      name: ThankView
      slug: thankview
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Fundraising
      - Marketing
      - Non-Profit
      - Video
      tier: declared
      url: /providers/thankview/
  layer: domain
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
      agent_readiness: 41.9
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Patreon
      band: exemplar
      in_catalog: true
      kin_score: 80.4
      mcp:
        status: none
      name: ConvertKit (Kit)
      slug: convertkit
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - GoFundMe Pro (Classy)
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id005
        status: none
      name: Facebook / Meta Pixel / Meta CAPI
      slug: facebook
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags: &id006
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - GoFundMe Pro (Classy)
      band: thin
      in_catalog: true
      kin_score: 36.7
      mcp:
        status: none
      name: Feathr
      slug: feathr
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Digital Marketing
      - Non-Profit
      tier: declared
      url: /providers/feathr/
    - agent_band: null
      agent_readiness: null
      apps:
      - Patreon
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: ToneDen
      slug: toneden
      sources:
      - https://www.patreon.com/apps
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - HCB (Hack Club Bank)
      - Patreon
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/hackclub/hcb/blob/main/Gemfile
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Givebutter
      - Patreon
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id005
      name: Facebook / Meta fundraising
      slug: facebook
      sources:
      - https://givebutter.com/integrations
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter
      slug: x
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        source: https://github.com/discourse/discourse-mcp
        status: verified
      name: Discourse
      slug: discourse
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Community
      - Forums
      - Open Source
      tier: declared
      url: /providers/discourse/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Givebutter
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://givebutter.com/integrations
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
    - agent_band: agent-native
      agent_readiness: 48.5
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 68.7
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        source: https://developer.godaddy.com/mcp
        status: verified
      name: GoDaddy
      slug: godaddy
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Aftermarket
      - Certificates
      - DNS
      - Domains
      tier: declared
      url: /providers/godaddy/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 20.3
      mcp:
        status: none
      name: Weebly
      slug: weebly
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Blogging
      - E-Commerce
      - Sites
      - Website Builder
      tier: declared
      url: /providers/weebly/
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
      - Givebutter
      - GoFundMe Pro (Classy)
      - Patreon
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - GoFundMe Pro (Classy)
      band: emerging
      in_catalog: true
      kin_score: 17.6
      mcp:
        status: unknown
      name: SyncSmart
      slug: syncsmart
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - HubSpot
      - Integration
      - Marketing
      - Sales
      tier: declared
      url: /providers/syncsmart/
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: BrightVine
      slug: brightvine
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Omatic
      slug: omatic
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Givebutter
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
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
      - Givebutter
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
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
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics
      slug: microsoft-dynamics-365
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Givebutter
      - GoFundMe Pro (Classy)
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
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
      - Liberapay
      - Open Collective
      - Patreon
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
      - Patreon
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id007
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
      status: profiled
      tags: &id008
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - HCB (Hack Club Bank)
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/appsignal/appsignal-mcp
        status: verified
      name: AppSignal
      slug: appsignal
      sources:
      - https://github.com/hackclub/hcb/blob/main/Gemfile
      status: profiled
      tags:
      - Error Tracking
      - Monitoring
      - Observability
      - Performance
      tier: observed
      url: /providers/appsignal/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Givebutter
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://givebutter.com/integrations
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: declared
      url: /providers/twitch/
    - agent_band: agent-aware
      agent_readiness: 21.5
      apps:
      - Patreon
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: unknown
      name: TubeBuddy
      slug: tubebuddy
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Company
      - SEO
      - VideoTools
      - YouTube
      tier: declared
      url: /providers/tubebuddy/
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
      - Givebutter
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://givebutter.com/integrations
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Patreon
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Patreon
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id007
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - HCB (Hack Club Bank)
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - GoFundMe Pro (Classy)
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        status: none
      name: Tatango
      slug: tatango
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - SMS
      tier: declared
      url: /providers/tatango/
    - agent_band: null
      agent_readiness: null
      apps:
      - GoFundMe Pro (Classy)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Mobile Commons
      slug: mobile-commons
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: declared
      url: /providers/snowflake/
    - agent_band: agent-native
      agent_readiness: 44.5
      apps:
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
        status: verified
      name: Amazon Redshift
      slug: amazon-redshift
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Lake
      tier: declared
      url: /providers/amazon-redshift/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GoFundMe Pro (Classy)
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: unknown
      name: Bytespree
      slug: bytespree
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Company
      - Data Platform
      - Non-Profit
      - Open Source
      tier: declared
      url: /providers/bytespree/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Open Collective
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - HCB (Hack Club Bank)
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
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
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 70.0
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - Patreon
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        status: none
      name: 99designs
      slug: 99designs
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Company
      - Design
      - Marketplace
      - Media
      tier: declared
      url: /providers/99designs/
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
      - HCB (Hack Club Bank)
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://github.com/hackclub/hcb/blob/main/Gemfile
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
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
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
      - HCB (Hack Club Bank)
      - Open Collective
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/hackclub/hcb/blob/main/Gemfile
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - GoFundMe Pro (Classy)
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
        status: documented
      name: Tealium
      slug: tealium
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - AudienceStream
      - CDP
      - Customer Data Platform
      - Tag Management
      tier: declared
      url: /providers/tealium/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - GoFundMe Pro (Classy)
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://pro.gofundme.com/c/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
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
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: unknown
      name: Crowdcast
      slug: crowdcast
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Community
      - Live Streaming
      - Video
      - Webinars
      tier: declared
      url: /providers/crowdcast/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Liberapay
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: BC-3740.30
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Open Collective
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
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
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.6
      apps:
      - Patreon
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://github.com/Keeper-Security/keeper-mcp-golang-docker
        status: verified
      name: Keeper
      slug: keeper-security
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Password Manager
      - Secrets Management
      tier: declared
      url: /providers/keeper-security/
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - HCB (Hack Club Bank)
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp:
        status: none
      name: AWS KMS
      slug: amazon-kms
      sources:
      - https://github.com/hackclub/hcb/blob/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Cryptography
      - Data Protection
      - Encryption
      tier: observed
      url: /providers/amazon-kms/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Open Collective
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/opencollective/opencollective-api/blob/main/package.json
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10
      key: AE-150.10
      name: Email
      url: /capabilities/email/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://givebutter.com/integrations
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
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - HCB (Hack Club Bank)
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://github.com/hackclub/hcb/tree/main/app/services
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: observed
      url: /providers/google-workspace/
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
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://givebutter.com/integrations
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
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: AddEvent
      slug: addevent
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Calendar
      - Integration
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/addevent/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: declared
      url: /providers/google-maps/
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
      - Patreon
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: Giphy
      slug: giphy
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: declared
      url: /providers/giphy/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Patreon
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id005
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30
      key: AE-110.30
      name: Speech & Voice
      url: /capabilities/speech-voice/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Patreon
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        status: none
      name: Sonix
      slug: sonix
      sources:
      - https://www.patreon.com/apps
      status: profiled
      tags:
      - Audio Transcription
      - Speech-to-Text
      - Subtitles
      - Transcription
      tier: declared
      url: /providers/sonix/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10
      key: AE-110.10
      name: Model Inference
      url: /capabilities/model-inference/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude (Anthropic)
      slug: anthropic
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT (OpenAI)
      slug: openai
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 92.3
  declared_only: 94
  distinct_providers: 117
  in_catalog: 108
  mcp:
    documented: 2
    none: 43
    unchecked: 9
    verified: 46
  mcp_verified: 46
  mean_kin_score: 49.8
  observed: 23
  queued: 9
  reference_apps: 7
title: 'Donations & Crowdfunding: application blueprint'
---
