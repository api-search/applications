---
access: understanding
agent_layer:
- app: Xero
  finding: first-party xero-mcp-server (XeroAPI org)
  source: https://github.com/XeroAPI/xero-mcp-server
  tier: declared
- app: QuickBooks
  finding: first-party quickbooks-online-mcp-server (Intuit org)
  source: https://github.com/intuit/quickbooks-online-mcp-server
  tier: declared
- app: Zoho Invoice
  finding: Zoho MCP spans Zoho apps incl. Invoice
  source: https://www.zoho.com/mcp/
  tier: declared
apps:
- anchor: invoice-ninja
  counts:
    declared: 0
    observed: 42
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
    layer: domain
    name: Zoho Invoice
    provider: zoho-invoice
    says: ships the Zoho Invoice SDK or integration code
    source: https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
    tier: observed
  kind: open-source-saas
  name: Invoice Ninja
  page: /applications/accounting-invoicing/invoice-ninja/
  slug: invoice-ninja
  url: https://github.com/invoiceninja/invoiceninja
- anchor: akaunting
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
  - route: integrations page
    url: https://akaunting.com/apps
  integrations:
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
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
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
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
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
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
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
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
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
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
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
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
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
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
    tier: observed
  kind: self-hosted
  name: Akaunting
  page: /applications/accounting-invoicing/akaunting/
  slug: akaunting
  url: https://github.com/akaunting/akaunting
- anchor: crater
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
  - route: documentation
    url: https://docs.craterapp.com/
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
    source: https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.60
      key: tenant-backup-export-management
      name: Tenant Backup & Export Management
      url: /capabilities/tenant-backup-export-management/
      via_parent: null
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
    tier: observed
  kind: self-hosted
  name: Crater
  page: /applications/accounting-invoicing/crater/
  slug: crater
  url: https://github.com/crater-invoice/crater
- anchor: erpnext
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
  - route: documentation
    url: https://docs.frappe.io/erpnext/user/manual/en/payment-gateways
  - route: source code
    url: https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype
  integrations:
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
    source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1380.70
      key: reconciliation-management
      name: Reconciliation Management
      url: /capabilities/reconciliation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Plaid
    provider: plaid
    says: ships the Plaid SDK or integration code
    source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
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
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
    tier: observed
  kind: open-source-saas
  name: ERPNext
  page: /applications/accounting-invoicing/erpnext/
  slug: erpnext
  url: https://github.com/frappe/erpnext
- anchor: solidinvoice
  counts:
    declared: 0
    observed: 30
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Authorize.net
    provider: authorizenet
    says: ships the Authorize.net SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Be2bill (Dalenys)
    provider: payplug
    says: ships the Be2bill (Dalenys) SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Bird (MessageBird)
    provider: bird
    says: ships the Bird (MessageBird) SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Clickatell
    provider: clickatell
    says: ships the Clickatell SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Esendex
    provider: esendex
    says: ships the Esendex SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Firebase (FCM)
    provider: firebase
    says: ships the Firebase (FCM) SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Google Chat
    provider: google-chat
    says: ships the Google Chat SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Infobip
    provider: infobip
    says: ships the Infobip SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Klarna
    provider: klarna
    says: ships the Klarna SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: PayEx (Swedbank Pay)
    provider: swedbank-pay
    says: ships the PayEx (Swedbank Pay) SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Sinch
    provider: sinch
    says: ships the Sinch SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telnyx
    provider: telnyx
    says: ships the Telnyx SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
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
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Vonage
    provider: vonage
    says: ships the Vonage SDK or integration code
    source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
    tier: observed
  kind: self-hosted
  name: SolidInvoice
  page: /applications/accounting-invoicing/solidinvoice/
  slug: solidinvoice
  url: https://github.com/SolidInvoice/SolidInvoice
- anchor: xero
  counts:
    declared: 2
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
  - route: documentation
    url: https://central.xero.com/s/article/Set-up-online-invoice-payments
  - route: integrations page
    url: https://www.xero.com/us/accounting-software/accept-payments/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    name: GoCardless
    provider: gocardless
    says: lists GoCardless as an integration
    source: https://www.xero.com/us/accounting-software/accept-payments/
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
    source: https://www.xero.com/us/accounting-software/accept-payments/
    tier: declared
  kind: commercial
  name: Xero
  page: /applications/accounting-invoicing/xero/
  slug: xero
  url: https://www.xero.com/
- anchor: quickbooks
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    name: AppDynamics
    provider: appdynamics
    says: ships the AppDynamics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Braze
    provider: braze
    says: ships the Braze SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    name: Kochava
    provider: kochava
    says: ships the Kochava SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
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
    name: Splunk
    provider: splunk
    says: ships the Splunk SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
    tier: observed
  kind: commercial
  name: QuickBooks
  page: /applications/accounting-invoicing/quickbooks/
  slug: quickbooks
  url: https://quickbooks.intuit.com/
- anchor: freshbooks
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
  - route: integrations page
    url: https://www.freshbooks.com/payments
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
    name: Adjust
    provider: adjust
    says: ships the Adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
    tier: observed
  kind: commercial
  name: FreshBooks
  page: /applications/accounting-invoicing/freshbooks/
  slug: freshbooks
  url: https://www.freshbooks.com/
- anchor: zoho-invoice
  counts:
    declared: 13
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.zoho.invoice/latest/
  - route: documentation
    url: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zoho.invoice/latest/
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
    name: Authorize.net
    provider: authorizenet
    says: lists Authorize.net as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    name: Braintree
    provider: braintree
    says: lists Braintree as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    name: CSG Forte
    provider: csg
    says: lists CSG Forte as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    name: Verifone (2Checkout)
    provider: verifone
    says: lists Verifone (2Checkout) as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
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
    name: Zoho Payments
    provider: zoho-payments
    says: lists Zoho Payments as an integration
    source: https://www.zoho.com/us/invoice/help/settings/online-payments.html
    tier: declared
  kind: commercial
  name: Zoho Invoice
  page: /applications/accounting-invoicing/zoho-invoice/
  slug: zoho-invoice
  url: https://www.zoho.com/invoice/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: accounting-invoicing
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Money, Budgeting & Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#money-budgeting--management
- category: Accounting
  store: zapier
  url: https://zapier.com/apps
name: Accounting & Invoicing
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  fit: exact
  layer: common
  why: address / distance lookups; BC model has no geocoding capability (pilot finding 4)
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: mail + calendar suite integration (Google Workspace, Microsoft 365)
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: websocket push to the browser; no BC capability fits
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: iPaaS connectors (Zapier); no BC capability fits
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: receipt / expense OCR for bills
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: document + attachment storage
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: nearest
  layer: common
  why: 'transactional email + SMS: invoice delivery, reminders, engagement'
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution / tag management in the mobile apps
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sync invoices/payments into an external ledger (QuickBooks)
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'sales tax / VAT calculation (inferred only: no reference app observed a tax engine)'
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: team chat notifications (Slack, Teams, Discord ...)
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: importers from competing invoicing products (data migration)
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: nearest
  layer: common
  why: video embedding (ERPNext Video doctype)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring / APM
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: online invoice payment / card + ACH gateways
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics SDKs in the mobile apps
- capability:
    attribution: Turbo EA
    id: BC-1380.70
    key: reconciliation-management
    name: Reconciliation Management
    url: /capabilities/reconciliation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: bank feeds for matching transactions to invoices and ledger entries
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: in-app purchase billing for the hosted plan
- capability:
    attribution: Turbo EA
    id: BC-4230.60
    key: tenant-backup-export-management
    name: Tenant Backup & Export Management
    url: /capabilities/tenant-backup-export-management/
    via_parent: null
  fit: exact
  layer: common
  why: off-site backup destinations
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: social / enterprise sign-in
stack:
- capabilities:
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
      - Invoice Ninja
      - SolidInvoice
      - Xero
      - Zoho Invoice
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.xero.com/us/accounting-software/accept-payments/
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Akaunting
      - Invoice Ninja
      - SolidInvoice
      - Zoho Invoice
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Invoice Ninja
      - SolidInvoice
      - Zoho Invoice
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.net
      slug: authorizenet
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - Invoice Ninja
      - Zoho Invoice
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: observed
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - Invoice Ninja
      - Xero
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://developer.gocardless.com/mcp
        status: verified
      name: GoCardless
      slug: gocardless
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.xero.com/us/accounting-software/accept-payments/
      status: profiled
      tags:
      - Bank Debit
      - Direct Debit
      - Payments
      - Recurring Payments
      tier: observed
      url: /providers/gocardless/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Invoice Ninja
      - Zoho Invoice
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - Invoice Ninja
      - Zoho Invoice
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        status: none
      name: CSG Forte
      slug: csg
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Billing
      - Customer Engagement
      - Payments
      - Revenue Management
      tier: observed
      url: /providers/csg/
    - agent_band: agent-native
      agent_readiness: 46.0
      apps:
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        status: none
      name: Klarna
      slug: klarna
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Buy Now Pay Later
      - Cards
      - Fintech
      - Payments
      tier: observed
      url: /providers/klarna/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-native
      agent_readiness: 41.3
      apps:
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        status: none
      name: Helcim
      slug: helcim
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Canada
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/helcim/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Invoice Ninja
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        source: https://github.com/razorpay/razorpay-mcp-server
        status: verified
      name: Razorpay
      slug: razorpay
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Fintech
      - India
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Invoice Ninja
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: none
      name: eWAY
      slug: eway
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Australia
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/eway/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Invoice Ninja
      band: developing
      in_catalog: true
      kin_score: 40.9
      mcp:
        status: none
      name: Commonwealth Bank (PowerBoard)
      slug: commonwealth-bank
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Banks
      - Business Banking
      - Consumer Banking
      - Finance
      tier: observed
      url: /providers/commonwealth-bank/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 38.3
      mcp:
        status: none
      name: BTCPay Server
      slug: btcpay
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Bitcoin
      - Cryptocurrency
      - Lightning Network
      - Payments
      tier: observed
      url: /providers/btcpay/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Rotessa
      slug: rotessa
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - ACH
      - Canada
      - Payments
      - Pre-Authorized Debit
      tier: observed
      url: /providers/rotessa/
    - agent_band: agent-native
      agent_readiness: 47.5
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://github.com/checkout/checkout-mcp
        status: verified
      name: Checkout.com
      slug: checkout-com
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Acquiring
      - Cards
      - Fintech
      - Payments
      tier: observed
      url: /providers/checkout-com/
    - agent_band: agent-aware
      agent_readiness: 14.7
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: LawPay
      slug: lawpay
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Company
      - Fintech
      - Legal Tech
      - Payments
      tier: observed
      url: /providers/lawpay/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: CHIP (chip-in.asia)
      slug: chip-in-asia
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Company
      - Finance
      - Payments
      - Small Business
      tier: observed
      url: /providers/chip-in-asia/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        status: none
      name: PayFast
      slug: payfast
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - South Africa
      - Subscription
      tier: observed
      url: /providers/payfast/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - SolidInvoice
      band: thin
      in_catalog: true
      kin_score: 26.9
      mcp:
        source: https://github.com/payplug/payplug-plugin-mcp
        status: verified
      name: Be2bill (Dalenys)
      slug: payplug
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/payplug/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - SolidInvoice
      band: emerging
      in_catalog: true
      kin_score: 19.9
      mcp:
        status: none
      name: PayEx (Swedbank Pay)
      slug: swedbank-pay
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Company
      - Fintech
      - Nordic
      - Payments
      tier: observed
      url: /providers/swedbank-pay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: none
      name: Blockonomics
      slug: blockonomics
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Bitcoin
      - Company
      - Cryptocurrency
      - Payments
      tier: observed
      url: /providers/blockonomics/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: none
      name: PayTrace
      slug: paytrace
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Company
      - Fintech
      - Merchant Services
      - Payments
      tier: observed
      url: /providers/paytrace/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: WePay
      slug: wepay
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/PaymentDrivers
      status: profiled
      tags:
      - Marketplace
      - Payment Processing
      - Payments
      - Platform Payments
      tier: observed
      url: /providers/wepay/
    - agent_band: agent-ready
      agent_readiness: 38.1
      apps:
      - Zoho Invoice
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        status: none
      name: Verifone (2Checkout)
      slug: verifone
      sources:
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - E-Commerce
      - Payments
      - Point-of-Sale
      - Terminal Management
      tier: declared
      url: /providers/verifone/
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - Zoho Invoice
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        source: https://www.zoho.com/us/payments/developerdocs/mcp
        status: verified
      name: Zoho Payments
      slug: zoho-payments
      sources:
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Company
      - Fintech
      - Online Payments
      - Payments
      tier: declared
      url: /providers/zoho-payments/
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 31.2
      mcp:
        status: none
      name: FreshBooks
      slug: freshbooks
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
      status: profiled
      tags:
      - Accounting
      - Expense Tracking
      - Invoicing
      - Time Tracking
      tier: observed
      url: /providers/freshbooks/
    - agent_band: agent-aware
      agent_readiness: 18.9
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Invoice
      slug: zoho-invoice
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
      status: profiled
      tags:
      - Accounting
      - Billing
      - Invoicing
      - Small Business
      tier: observed
      url: /providers/zoho-invoice/
    - agent_band: agent-aware
      agent_readiness: 16.1
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Wave Financial
      slug: wave-financial
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
      status: profiled
      tags:
      - Accounting
      - Finance
      - Invoicing
      - Small Business
      tier: observed
      url: /providers/wave-financial/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        status: none
      name: Invoice2go
      slug: invoice2go
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
      status: profiled
      tags:
      - Company
      - Fintech
      - Invoicing
      - Payments
      tier: observed
      url: /providers/invoice2go/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: unknown
      name: Invoicely
      slug: invoicely
      sources:
      - https://github.com/invoiceninja/invoiceninja/tree/v5-stable/app/Import/Transformer
      status: profiled
      tags:
      - Billing
      - Company
      - Invoicing
      - Payments
      tier: observed
      url: /providers/invoicely/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Invoice Ninja
      - Zoho Invoice
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: observed
      url: /providers/quickbooks/
  - capability:
      attribution: Turbo EA
      id: BC-1380.70
      key: reconciliation-management
      name: Reconciliation Management
      url: /capabilities/reconciliation-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 52.1
      apps:
      - ERPNext
      band: exemplar
      in_catalog: true
      kin_score: 83.4
      mcp:
        source: https://plaid.com/docs/resources/mcp/
        status: verified
      name: Plaid
      slug: plaid
      sources:
      - https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
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
      - Invoice Ninja
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        source: https://github.com/gocardless/gc-mcp
        status: verified
      name: Nordigen (GoCardless Bank Account Data)
      slug: nordigen
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Finance
      - Public APIs
      tier: observed
      url: /providers/nordigen/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: Mindee
      slug: mindee
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Document Parsing
      - Intelligent Document Processing
      - OCR
      tier: observed
      url: /providers/mindee/
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
      agent_readiness: 41.7
      apps:
      - Akaunting
      - Invoice Ninja
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Akaunting
      - Invoice Ninja
      - SolidInvoice
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Akaunting
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - Invoice Ninja
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 82.2
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp (Mandrill)
      slug: mailchimp
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - SolidInvoice
      band: developing
      in_catalog: true
      kin_score: 50.1
      mcp:
        source: https://github.com/mailgun/mailjet-mcp-server
        status: verified
      name: Mailjet
      slug: mailjet
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/mailjet/
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
      - Invoice Ninja
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 61.3
      apps:
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://www.infobip.com/docs/mcp
        status: verified
      name: Infobip
      slug: infobip
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - CPaaS
      - Croatia
      - Messaging
      - Telecommunications
      tier: observed
      url: /providers/infobip/
    - agent_band: agent-native
      agent_readiness: 79.5
      apps:
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 79.4
      mcp:
        source: https://github.com/team-telnyx/telnyx-mcp-server
        status: verified
      name: Telnyx
      slug: telnyx
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - CPaaS
      - Communications
      - SMS
      - Voice
      tier: observed
      url: /providers/telnyx/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - SolidInvoice
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://github.com/sinch/sinch-mcp-server
        status: verified
      name: Sinch
      slug: sinch
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Communications
      - Messaging
      - SMS
      - Voice
      tier: observed
      url: /providers/sinch/
    - agent_band: agent-ready
      agent_readiness: 43.5
      apps:
      - SolidInvoice
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: observed
      url: /providers/vonage/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - SolidInvoice
      band: strong
      in_catalog: true
      kin_score: 55.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: agent-ready
      agent_readiness: 65.2
      apps:
      - SolidInvoice
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        source: https://github.com/messagebird/bird-ai
        status: verified
      name: Bird (MessageBird)
      slug: bird
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Communications
      - Email
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/bird/
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - SolidInvoice
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: Clickatell
      slug: clickatell
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Company
      - Messaging
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/clickatell/
    - agent_band: agent-aware
      agent_readiness: 18.5
      apps:
      - SolidInvoice
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        status: none
      name: Esendex
      slug: esendex
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Business
      - Communications
      - Messaging
      - SMS
      tier: observed
      url: /providers/esendex/
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
      - Akaunting
      - Invoice Ninja
      - SolidInvoice
      - Xero
      - Zoho Invoice
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - Akaunting
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Xero
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - QuickBooks
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: observed
      url: /providers/splunk/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - QuickBooks
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: AppDynamics
      slug: appdynamics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - APM
      - Application Performance Monitoring
      - Cisco
      - Cloud Observability
      tier: observed
      url: /providers/appdynamics/
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
      - FreshBooks
      - QuickBooks
      - Xero
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
      status: profiled
      tags: &id004
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - FreshBooks
      - QuickBooks
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - QuickBooks
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Xero
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - QuickBooks
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
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
      - Akaunting
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      - https://raw.githubusercontent.com/akaunting/akaunting/master/composer.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - SolidInvoice
      band: exemplar
      in_catalog: true
      kin_score: 76.4
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - SolidInvoice
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - SolidInvoice
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - SolidInvoice
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Chat
      slug: google-chat
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Google
      - Google Workspace
      tier: observed
      url: /providers/google-chat/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - SolidInvoice
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google (API client)
      slug: google
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Zoho Invoice
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Xero
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - FreshBooks
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
    - agent_band: null
      agent_readiness: null
      apps:
      - QuickBooks
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Kochava
      slug: kochava
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp: &id001
        status: none
      name: Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags: &id002
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - QuickBooks
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Crater
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Xero
      band: exemplar
      in_catalog: true
      kin_score: 80.5
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - QuickBooks
      band: exemplar
      in_catalog: true
      kin_score: 75.2
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.intuit.quickbooks/latest/
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: observed
      url: /providers/braze/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Zoho Invoice
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Zoho Invoice
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
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
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp: *id001
      name: Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
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
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - ERPNext
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - ERPNext
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://raw.githubusercontent.com/frappe/erpnext/develop/pyproject.toml
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - SolidInvoice
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id003
      name: Firebase (FCM)
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
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
      - FreshBooks
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.freshbooks.andromeda/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-4230.60
      key: tenant-backup-export-management
      name: Tenant Backup & Export Management
      url: /capabilities/tenant-backup-export-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Crater
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://raw.githubusercontent.com/crater-invoice/crater/master/composer.json
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
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
      - Zoho Invoice
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.zoho.com/us/invoice/help/settings/online-payments.html
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
summary:
  coverage_pct: 98.9
  declared_only: 6
  distinct_providers: 88
  in_catalog: 87
  mcp:
    documented: 0
    none: 41
    unchecked: 1
    verified: 45
  mcp_verified: 45
  mean_kin_score: 52.9
  observed: 82
  queued: 1
  reference_apps: 9
title: 'Accounting & Invoicing: application blueprint'
---
