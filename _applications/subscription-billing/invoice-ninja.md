---
app: Invoice Ninja
app_slug: invoice-ninja
app_url: https://github.com/invoiceninja/invoiceninja
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1300.50
  key: banking-channels-management
  layer: domain
  name: Banking Channels Management
  providers:
  - Nordigen (GoCardless Bank Account Data)
  url: /capabilities/banking-channels-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-240.70.20
  key: AE-240.70.20
  layer: common
  name: Crypto Payment Acceptance
  providers:
  - Blockonomics
  - BTCPay Server
  url: /capabilities/stablecoin-payments/
  via_parent: Stablecoin Payments
- attribution: Turbo EA
  id: BC-2510.40
  key: exception-and-alert-management
  layer: common
  name: Exception and Alert Management
  providers:
  - Slack
  url: /capabilities/exception-and-alert-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Apple
  - Microsoft Entra ID
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Microsoft Graph
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: common
  name: OCR & Document AI
  providers:
  - Mindee
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Authorize.net
  - Braintree
  - CBA PowerBoard
  - Checkout.com
  - CHIP (Chip In Asia)
  - eWAY
  - Forte
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
  id: subscription-billing
  name: Subscription Billing & Payments Ops
  url: /applications/subscription-billing/
counts:
  declared: 0
  observed: 34
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.invoiceninja.app/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
- route: source code
  url: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
integrations:
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
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
    mcp: &id003
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id004
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: common
  name: Authorize.net
  provider: authorizenet
  says: ships the Authorize.net SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id005
      status: none
    slug: blockonomics
    status: profiled
    tags: &id006
    - Bitcoin
    - Company
    - Cryptocurrency
    - Payments
    url: /providers/blockonomics/
  layer: common
  name: Blockonomics
  provider: blockonomics
  says: ships the Blockonomics SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id007
      status: none
    slug: braintree
    status: profiled
    tags: &id008
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: common
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
    mcp: &id009
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id010
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
    attribution: API Evangelist extension
    id: AE-240.70.20
    key: AE-240.70.20
    name: Crypto Payment Acceptance
    url: /capabilities/stablecoin-payments/
    via_parent: Stablecoin Payments
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id011
      status: none
    slug: btcpay
    status: profiled
    tags: &id012
    - Bitcoin
    - Cryptocurrency
    - Lightning Network
    - Payments
    url: /providers/btcpay/
  layer: common
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id013
      status: unknown
    slug: cba-powerboard
    status: profiled
    tags: &id014
    - Australia
    - Banking
    - Company
    - Fintech
    url: /providers/cba-powerboard/
  layer: common
  name: CBA PowerBoard
  provider: cba-powerboard
  says: ships the CBA PowerBoard SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id015
      source: https://github.com/checkout/checkout-mcp
      status: verified
    slug: checkout-com
    status: profiled
    tags: &id016
    - Acquiring
    - Cards
    - Fintech
    - Payments
    url: /providers/checkout-com/
  layer: common
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
    mcp: &id017
      status: none
    slug: chip-in-asia
    status: profiled
    tags: &id018
    - Company
    - Finance
    - Payments
    - Small Business
    url: /providers/chip-in-asia/
  layer: common
  name: CHIP (Chip In Asia)
  provider: chip-in-asia
  says: ships the CHIP (Chip In Asia) SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id019
      status: none
    slug: eway
    status: profiled
    tags: &id020
    - Australia
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/eway/
  layer: common
  name: eWAY
  provider: eway
  says: ships the eWAY SDK or integration code
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
    agent_readiness: 27.2
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id021
      status: none
    slug: csg
    status: profiled
    tags: &id022
    - Billing
    - Customer Engagement
    - Payments
    - Revenue Management
    url: /providers/csg/
  layer: common
  name: Forte
  provider: csg
  says: ships the Forte SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id023
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id024
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: common
  name: GoCardless
  provider: gocardless
  says: ships the GoCardless SDK or integration code
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
    mcp: &id025
      status: none
    slug: helcim
    status: profiled
    tags: &id026
    - Canada
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/helcim/
  layer: common
  name: Helcim
  provider: helcim
  says: ships the Helcim SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id027
      status: none
    slug: lawpay
    status: profiled
    tags: &id028
    - Company
    - Fintech
    - Legal Tech
    - Payments
    url: /providers/lawpay/
  layer: common
  name: LawPay
  provider: lawpay
  says: ships the LawPay SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id029
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id030
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
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id031
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id032
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
    mcp: &id033
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id034
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
    mcp: &id035
      status: none
    slug: mindee
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - Document Parsing
    - Intelligent Document Processing
    - OCR
    url: /providers/mindee/
  layer: common
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
    mcp: &id037
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id038
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: common
  name: Mollie
  provider: mollie
  says: ships the Mollie SDK or integration code
  source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1300.50
    key: banking-channels-management
    name: Banking Channels Management
    url: /capabilities/banking-channels-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.2
    mcp: &id039
      source: https://github.com/gocardless/gc-mcp
      status: verified
    slug: nordigen
    status: profiled
    tags: &id040
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
    mcp: &id041
      status: none
    slug: payfast
    status: profiled
    tags: &id042
    - Payment Gateway
    - Payments
    - South Africa
    - Subscription
    url: /providers/payfast/
  layer: common
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
    mcp: &id043
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id044
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id045
      status: none
    slug: paytrace
    status: profiled
    tags: &id046
    - Company
    - Fintech
    - Merchant Services
    - Payments
    url: /providers/paytrace/
  layer: common
  name: PayTrace
  provider: paytrace
  says: ships the PayTrace SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id047
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id048
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
    mcp: &id049
      status: none
    slug: pusher
    status: profiled
    tags: &id050
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
    mcp: &id051
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id052
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: ships the QuickBooks SDK or integration code
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
    mcp: &id053
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id054
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: common
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
    mcp: &id055
      status: none
    slug: rotessa
    status: profiled
    tags: &id056
    - ACH
    - Canada
    - Payments
    - Pre-Authorized Debit
    url: /providers/rotessa/
  layer: common
  name: Rotessa
  provider: rotessa
  says: ships the Rotessa SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
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
    mcp: &id057
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id058
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
    id: BC-2510.40
    key: exception-and-alert-management
    name: Exception and Alert Management
    url: /capabilities/exception-and-alert-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id059
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id060
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
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
    mcp: &id061
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id062
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: common
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
    mcp: &id063
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id064
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
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
    mcp: &id065
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id066
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
    mcp: &id067
      status: none
    slug: wepay
    status: profiled
    tags: &id068
    - Marketplace
    - Payment Processing
    - Payments
    - Platform Payments
    url: /providers/wepay/
  layer: common
  name: WePay
  provider: wepay
  says: ships the WePay SDK or integration code
  source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/subscription-billing/invoice-ninja/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id003
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id004
  url: /providers/authorizenet/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id005
  name: Blockonomics
  slug: blockonomics
  status: profiled
  tags: *id006
  url: /providers/blockonomics/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id007
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id008
  url: /providers/braintree/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id009
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id010
  url: /providers/brevo/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id011
  name: BTCPay Server
  slug: btcpay
  status: profiled
  tags: *id012
  url: /providers/btcpay/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id013
  name: CBA PowerBoard
  slug: cba-powerboard
  status: profiled
  tags: *id014
  url: /providers/cba-powerboard/
- agent_band: agent-native
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id015
  name: Checkout.com
  slug: checkout-com
  status: profiled
  tags: *id016
  url: /providers/checkout-com/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id017
  name: CHIP (Chip In Asia)
  slug: chip-in-asia
  status: profiled
  tags: *id018
  url: /providers/chip-in-asia/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id019
  name: eWAY
  slug: eway
  status: profiled
  tags: *id020
  url: /providers/eway/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id021
  name: Forte
  slug: csg
  status: profiled
  tags: *id022
  url: /providers/csg/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id023
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id024
  url: /providers/gocardless/
- agent_band: agent-native
  agent_readiness: 40.4
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id025
  name: Helcim
  slug: helcim
  status: profiled
  tags: *id026
  url: /providers/helcim/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id027
  name: LawPay
  slug: lawpay
  status: profiled
  tags: *id028
  url: /providers/lawpay/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id029
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id030
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id031
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id032
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id033
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id034
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 51.8
  mcp: *id035
  name: Mindee
  slug: mindee
  status: profiled
  tags: *id036
  url: /providers/mindee/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id037
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id038
  url: /providers/mollie/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id039
  name: Nordigen (GoCardless Bank Account Data)
  slug: nordigen
  status: profiled
  tags: *id040
  url: /providers/nordigen/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 26.6
  mcp: *id041
  name: PayFast
  slug: payfast
  status: profiled
  tags: *id042
  url: /providers/payfast/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id043
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id044
  url: /providers/paypal/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id045
  name: PayTrace
  slug: paytrace
  status: profiled
  tags: *id046
  url: /providers/paytrace/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id047
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id048
  url: /providers/postmark/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id049
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id050
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id051
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id052
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id053
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id054
  url: /providers/razorpay/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id055
  name: Rotessa
  slug: rotessa
  status: profiled
  tags: *id056
  url: /providers/rotessa/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id057
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id058
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id059
  name: Slack
  slug: slack
  status: profiled
  tags: *id060
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id061
  name: Square
  slug: square
  status: profiled
  tags: *id062
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id063
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id064
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id065
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id066
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id067
  name: WePay
  slug: wepay
  status: profiled
  tags: *id068
  url: /providers/wepay/
siblings:
- name: Chargebee
  rows: 44
  url: /applications/subscription-billing/chargebee/
- name: Kill Bill
  rows: 15
  url: /applications/subscription-billing/kill-bill/
- name: Lago
  rows: 31
  url: /applications/subscription-billing/lago/
- name: Paddle
  rows: 12
  url: /applications/subscription-billing/paddle/
- name: Polar
  rows: 14
  url: /applications/subscription-billing/polar/
- name: Recurly
  rows: 28
  url: /applications/subscription-billing/recurly/
sitemap: true
title: 'Invoice Ninja: Subscription Billing & Payments Ops reference app'
---
