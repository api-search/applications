---
app: Invoice Ninja
app_slug: invoice-ninja
app_url: https://github.com/invoiceninja/invoiceninja
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.50
  key: invoice-generation-management
  layer: domain
  name: Invoice Generation Management
  providers:
  - FreshBooks
  - Invoice2go
  - Invoicely
  - Wave Financial
  - Zoho Invoice
  url: /capabilities/invoice-generation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: domain
  name: OCR & Document AI
  providers:
  - Mindee
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Authorize.net
  - Blockonomics
  - Braintree
  - BTCPay Server
  - Checkout.com
  - CHIP (chip-in.asia)
  - Commonwealth Bank (PowerBoard)
  - CSG Forte
  - eWAY
  - GoCardless
  - Helcim
  - LawPay
  - Mollie
  - PayFast
  - PayPal
  - PayTrace
  - Razorpay
  - Rotessa
  - Square
  - Stripe
  - WePay
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1380.70
  key: reconciliation-management
  layer: domain
  name: Reconciliation Management
  providers:
  - Nordigen (GoCardless Bank Account Data)
  url: /capabilities/reconciliation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon Web Services
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Apple
  - Google Play
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google (API client)
  - Microsoft Graph
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Apple
  - Microsoft Entra ID
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Brevo
  - Mailgun
  - Postmark
  url: /capabilities/email/
  via_parent: Email
category:
  id: accounting-invoicing
  name: Accounting & Invoicing
  url: /applications/accounting-invoicing/
counts:
  declared: 0
  observed: 42
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.invoiceninja.app/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
- route: source code
  url: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
- route: source code
  url: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
- route: source code
  url: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Services
integrations:
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id002
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id003
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services
  provider: amazon-web-services
  says: ships the Amazon Web Services SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id004
      status: none
    slug: apple
    status: profiled
    tags: &id005
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple
  provider: apple
  says: ships the Apple SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Apple
  provider: apple
  says: ships the Apple SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id006
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id007
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: domain
  name: Authorize.net
  provider: authorizenet
  says: ships the Authorize.net SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id008
      status: none
    slug: blockonomics
    status: profiled
    tags: &id009
    - Bitcoin
    - Company
    - Cryptocurrency
    - Payments
    url: /providers/blockonomics/
  layer: domain
  name: Blockonomics
  provider: blockonomics
  says: ships the Blockonomics SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    mcp: &id010
      status: none
    slug: braintree
    status: profiled
    tags: &id011
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: domain
  name: Braintree
  provider: braintree
  says: ships the Braintree SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 81.3
    mcp: &id012
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id013
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
  layer: common
  name: Brevo
  provider: brevo
  says: ships the Brevo SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 28.6
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id014
      status: none
    slug: btcpay
    status: profiled
    tags: &id015
    - Bitcoin
    - Cryptocurrency
    - Lightning Network
    - Payments
    url: /providers/btcpay/
  layer: domain
  name: BTCPay Server
  provider: btcpay
  says: ships the BTCPay Server SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id016
      source: https://github.com/checkout/checkout-mcp
      status: verified
    slug: checkout-com
    status: profiled
    tags: &id017
    - Acquiring
    - Cards
    - Fintech
    - Payments
    url: /providers/checkout-com/
  layer: domain
  name: Checkout.com
  provider: checkout-com
  says: ships the Checkout.com SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id018
      status: none
    slug: chip-in-asia
    status: profiled
    tags: &id019
    - Company
    - Finance
    - Payments
    - Small Business
    url: /providers/chip-in-asia/
  layer: domain
  name: CHIP (chip-in.asia)
  provider: chip-in-asia
  says: ships the CHIP (chip-in.asia) SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    agent_readiness: 34.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id020
      status: none
    slug: commonwealth-bank
    status: profiled
    tags: &id021
    - Banks
    - Business Banking
    - Consumer Banking
    - Finance
    url: /providers/commonwealth-bank/
  layer: domain
  name: Commonwealth Bank (PowerBoard)
  provider: commonwealth-bank
  says: ships the Commonwealth Bank (PowerBoard) SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    agent_band: agent-aware
    agent_readiness: 27.2
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id022
      status: none
    slug: csg
    status: profiled
    tags: &id023
    - Billing
    - Customer Engagement
    - Payments
    - Revenue Management
    url: /providers/csg/
  layer: domain
  name: CSG Forte
  provider: csg
  says: ships the CSG Forte SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    agent_band: agent-aware
    agent_readiness: 5.3
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id024
      status: none
    slug: eway
    status: profiled
    tags: &id025
    - Australia
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/eway/
  layer: domain
  name: eWAY
  provider: eway
  says: ships the eWAY SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id026
      status: none
    slug: freshbooks
    status: profiled
    tags: &id027
    - Accounting
    - Expense Tracking
    - Invoicing
    - Time Tracking
    url: /providers/freshbooks/
  layer: domain
  name: FreshBooks
  provider: freshbooks
  says: ships the FreshBooks SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
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
    agent_readiness: 50.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id028
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id029
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: domain
  name: GoCardless
  provider: gocardless
  says: ships the GoCardless SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id030
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id031
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google (API client)
  provider: google
  says: ships the Google (API client) SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 38.7
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id032
      status: none
    slug: google-play
    status: profiled
    tags: &id033
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play
  provider: google-play
  says: ships the Google Play SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 40.4
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id034
      status: none
    slug: helcim
    status: profiled
    tags: &id035
    - Canada
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/helcim/
  layer: domain
  name: Helcim
  provider: helcim
  says: ships the Helcim SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id036
      status: none
    slug: invoice2go
    status: profiled
    tags: &id037
    - Company
    - Fintech
    - Invoicing
    - Payments
    url: /providers/invoice2go/
  layer: domain
  name: Invoice2go
  provider: invoice2go
  says: ships the Invoice2go SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.8
    mcp: &id038
      status: unknown
    slug: invoicely
    status: profiled
    tags: &id039
    - Billing
    - Company
    - Invoicing
    - Payments
    url: /providers/invoicely/
  layer: domain
  name: Invoicely
  provider: invoicely
  says: ships the Invoicely SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
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
    agent_band: agent-aware
    agent_readiness: 14.4
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id040
      status: none
    slug: lawpay
    status: profiled
    tags: &id041
    - Company
    - Fintech
    - Legal Tech
    - Payments
    url: /providers/lawpay/
  layer: domain
  name: LawPay
  provider: lawpay
  says: ships the LawPay SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id042
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id043
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    mcp: &id044
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id045
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id046
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id047
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 51.8
    mcp: &id048
      status: none
    slug: mindee
    status: profiled
    tags: &id049
    - Artificial Intelligence
    - Document Parsing
    - Intelligent Document Processing
    - OCR
    url: /providers/mindee/
  layer: domain
  name: Mindee
  provider: mindee
  says: ships the Mindee SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 71.7
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id050
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id051
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: domain
  name: Mollie
  provider: mollie
  says: ships the Mollie SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1380.70
    key: reconciliation-management
    name: Reconciliation Management
    url: /capabilities/reconciliation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.2
    mcp: &id052
      source: https://github.com/gocardless/gc-mcp
      status: verified
    slug: nordigen
    status: profiled
    tags: &id053
    - Finance
    - Public APIs
    url: /providers/nordigen/
  layer: domain
  name: Nordigen (GoCardless Bank Account Data)
  provider: nordigen
  says: ships the Nordigen (GoCardless Bank Account Data) SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 28.8
    band: thin
    in_catalog: true
    kin_score: 26.6
    mcp: &id054
      status: none
    slug: payfast
    status: profiled
    tags: &id055
    - Payment Gateway
    - Payments
    - South Africa
    - Subscription
    url: /providers/payfast/
  layer: domain
  name: PayFast
  provider: payfast
  says: ships the PayFast SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id056
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id057
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id058
      status: none
    slug: paytrace
    status: profiled
    tags: &id059
    - Company
    - Fintech
    - Merchant Services
    - Payments
    url: /providers/paytrace/
  layer: domain
  name: PayTrace
  provider: paytrace
  says: ships the PayTrace SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id060
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id061
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id062
      status: none
    slug: pusher
    status: profiled
    tags: &id063
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id064
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id065
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online
  provider: quickbooks
  says: ships the QuickBooks Online SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id066
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id067
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: domain
  name: Razorpay
  provider: razorpay
  says: ships the Razorpay SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id068
      status: none
    slug: rotessa
    status: profiled
    tags: &id069
    - ACH
    - Canada
    - Payments
    - Pre-Authorized Debit
    url: /providers/rotessa/
  layer: domain
  name: Rotessa
  provider: rotessa
  says: ships the Rotessa SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
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
    mcp: &id070
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id071
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id072
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id073
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: ships the Square SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    mcp: &id074
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id075
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id076
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id077
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.8
    band: thin
    in_catalog: true
    kin_score: 26.9
    mcp: &id078
      status: none
    slug: wave-financial
    status: profiled
    tags: &id079
    - Accounting
    - Finance
    - Invoicing
    - Small Business
    url: /providers/wave-financial/
  layer: domain
  name: Wave Financial
  provider: wave-financial
  says: ships the Wave Financial SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id080
      status: none
    slug: wepay
    status: profiled
    tags: &id081
    - Marketplace
    - Payment Processing
    - Payments
    - Platform Payments
    url: /providers/wepay/
  layer: domain
  name: WePay
  provider: wepay
  says: ships the WePay SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id082
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-invoice
    status: profiled
    tags: &id083
    - Accounting
    - Billing
    - Invoicing
    - Small Business
    url: /providers/zoho-invoice/
  layer: domain
  name: Zoho Invoice
  provider: zoho-invoice
  says: ships the Zoho Invoice SDK or integration code
  source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/accounting-invoicing/invoice-ninja/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id002
  name: Amazon Web Services
  slug: amazon-web-services
  status: profiled
  tags: *id003
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id004
  name: Apple
  slug: apple
  status: profiled
  tags: *id005
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id006
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id007
  url: /providers/authorizenet/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id008
  name: Blockonomics
  slug: blockonomics
  status: profiled
  tags: *id009
  url: /providers/blockonomics/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id010
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id011
  url: /providers/braintree/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id012
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id013
  url: /providers/brevo/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id014
  name: BTCPay Server
  slug: btcpay
  status: profiled
  tags: *id015
  url: /providers/btcpay/
- agent_band: agent-native
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id016
  name: Checkout.com
  slug: checkout-com
  status: profiled
  tags: *id017
  url: /providers/checkout-com/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id018
  name: CHIP (chip-in.asia)
  slug: chip-in-asia
  status: profiled
  tags: *id019
  url: /providers/chip-in-asia/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id020
  name: Commonwealth Bank (PowerBoard)
  slug: commonwealth-bank
  status: profiled
  tags: *id021
  url: /providers/commonwealth-bank/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id022
  name: CSG Forte
  slug: csg
  status: profiled
  tags: *id023
  url: /providers/csg/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id024
  name: eWAY
  slug: eway
  status: profiled
  tags: *id025
  url: /providers/eway/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id026
  name: FreshBooks
  slug: freshbooks
  status: profiled
  tags: *id027
  url: /providers/freshbooks/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id028
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id029
  url: /providers/gocardless/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id030
  name: Google (API client)
  slug: google
  status: profiled
  tags: *id031
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id032
  name: Google Play
  slug: google-play
  status: profiled
  tags: *id033
  url: /providers/google-play/
- agent_band: agent-native
  agent_readiness: 40.4
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id034
  name: Helcim
  slug: helcim
  status: profiled
  tags: *id035
  url: /providers/helcim/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id036
  name: Invoice2go
  slug: invoice2go
  status: profiled
  tags: *id037
  url: /providers/invoice2go/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.8
  mcp: *id038
  name: Invoicely
  slug: invoicely
  status: profiled
  tags: *id039
  url: /providers/invoicely/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id040
  name: LawPay
  slug: lawpay
  status: profiled
  tags: *id041
  url: /providers/lawpay/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id042
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id043
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id044
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id045
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id046
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id047
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 51.8
  mcp: *id048
  name: Mindee
  slug: mindee
  status: profiled
  tags: *id049
  url: /providers/mindee/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id050
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id051
  url: /providers/mollie/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id052
  name: Nordigen (GoCardless Bank Account Data)
  slug: nordigen
  status: profiled
  tags: *id053
  url: /providers/nordigen/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 26.6
  mcp: *id054
  name: PayFast
  slug: payfast
  status: profiled
  tags: *id055
  url: /providers/payfast/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id056
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id057
  url: /providers/paypal/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id058
  name: PayTrace
  slug: paytrace
  status: profiled
  tags: *id059
  url: /providers/paytrace/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id060
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id061
  url: /providers/postmark/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id062
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id063
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id064
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id065
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id066
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id067
  url: /providers/razorpay/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id068
  name: Rotessa
  slug: rotessa
  status: profiled
  tags: *id069
  url: /providers/rotessa/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id070
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id071
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id072
  name: Square
  slug: square
  status: profiled
  tags: *id073
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id074
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id075
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id076
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id077
  url: /providers/twilio/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 26.9
  mcp: *id078
  name: Wave Financial
  slug: wave-financial
  status: profiled
  tags: *id079
  url: /providers/wave-financial/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id080
  name: WePay
  slug: wepay
  status: profiled
  tags: *id081
  url: /providers/wepay/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id082
  name: Zoho Invoice
  slug: zoho-invoice
  status: profiled
  tags: *id083
  url: /providers/zoho-invoice/
siblings:
- name: Akaunting
  rows: 7
  url: /applications/accounting-invoicing/akaunting/
- name: Crater
  rows: 2
  url: /applications/accounting-invoicing/crater/
- name: ERPNext
  rows: 3
  url: /applications/accounting-invoicing/erpnext/
- name: FreshBooks
  rows: 4
  url: /applications/accounting-invoicing/freshbooks/
- name: QuickBooks
  rows: 9
  url: /applications/accounting-invoicing/quickbooks/
- name: SolidInvoice
  rows: 30
  url: /applications/accounting-invoicing/solidinvoice/
- name: Xero
  rows: 8
  url: /applications/accounting-invoicing/xero/
- name: Zoho Invoice
  rows: 14
  url: /applications/accounting-invoicing/zoho-invoice/
sitemap: true
title: 'Invoice Ninja: Accounting & Invoicing reference app'
---
