---
access: understanding
agent_layer:
- app: NexoPOS
  finding: depends on laravel/mcp -- ships its own MCP server surface
  source: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
  tier: observed
apps:
- anchor: odoo-point-of-sale
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: source code
    url: https://github.com/odoo/odoo/tree/master/addons
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adyen
    provider: adyen
    says: ships the Adyen SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.30
      key: AE-140.30.30
      name: QR & Contactless Payments
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Bancontact Payconiq
    provider: bancontact
    says: ships the Bancontact Payconiq SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.40.10
      key: BC-2320.40.10
      name: Cash Drawer Management
      url: /capabilities/pos-cash-and-tender-handling/
      via_parent: POS Cash and Tender Handling
    credit: null
    layer: domain
    name: CashDro
    provider: cashdro
    says: ships the CashDro SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.40.10
      key: BC-2320.40.10
      name: Cash Drawer Management
      url: /capabilities/pos-cash-and-tender-handling/
      via_parent: POS Cash and Tender Handling
    credit: null
    layer: domain
    name: Cashmatic
    provider: cashmatic
    says: ships the Cashmatic SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: DPO Pay
    provider: dpo-pay
    says: ships the DPO Pay SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.40.10
      key: BC-2320.40.10
      name: Cash Drawer Management
      url: /capabilities/pos-cash-and-tender-handling/
      via_parent: POS Cash and Tender Handling
    credit: null
    layer: domain
    name: Glory (cash recyclers)
    provider: glory-global-solutions
    says: ships the Glory (cash recyclers) SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.50.40
      key: BC-2320.50.40
      name: POS Peripheral Configuration
      url: /capabilities/pos-configuration-management/
      via_parent: POS Configuration Management
    credit: null
    layer: domain
    name: iMin
    provider: imin
    says: ships the iMin SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: M-Pesa (Safaricom)
    provider: mpesa
    says: ships the M-Pesa (Safaricom) SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mercado Pago
    provider: mercado-pago
    says: ships the Mercado Pago SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mollie
    provider: mollie
    says: ships the Mollie SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pine Labs
    provider: pine-labs
    says: ships the Pine Labs SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: QFPay
    provider: qfpay
    says: ships the QFPay SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Razorpay
    provider: razorpay
    says: ships the Razorpay SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: SumUp
    provider: sumup
    says: ships the SumUp SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Viva.com (Viva Wallet)
    provider: viva-com
    says: ships the Viva.com (Viva Wallet) SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons
    tier: observed
  kind: self-hosted
  name: Odoo Point of Sale
  page: /applications/point-of-sale/odoo-point-of-sale/
  slug: odoo-point-of-sale
  url: https://github.com/odoo/odoo
- anchor: open-source-point-of-sale
  counts:
    declared: 1
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/opensourcepos/opensourcepos/blob/master/composer.json
  - route: documentation
    url: https://github.com/opensourcepos/opensourcepos/blob/master/README.md
  - route: source code
    url: https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
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
    name: Text Marketer
    provider: textmarketer
    says: ships the Text Marketer SDK or integration code
    source: https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
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
    says: lists Google reCAPTCHA as an integration
    source: https://github.com/opensourcepos/opensourcepos/blob/master/README.md
    tier: declared
  kind: self-hosted
  name: Open Source Point of Sale
  page: /applications/point-of-sale/open-source-point-of-sale/
  slug: open-source-point-of-sale
  url: https://github.com/opensourcepos/opensourcepos
- anchor: nexopos
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
  - route: source code
    url: https://github.com/Blair2004/NexoPOS/blob/master/.env.example
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
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
    source: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
    tier: observed
  kind: self-hosted
  name: NexoPOS
  page: /applications/point-of-sale/nexopos/
  slug: nexopos
  url: https://github.com/Blair2004/NexoPOS
- anchor: loyverse-pos
  counts:
    declared: 27
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
  - route: integrations page
    url: https://loyverse.com/marketplace
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
    name: FullStory
    provider: fullstory
    says: ships the FullStory SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Amaka
    provider: amaka
    says: lists Amaka as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.80
      key: AE-140.80
      name: Marketplaces
      url: /capabilities/marketplaces/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon
    provider: amazon
    says: lists Amazon as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: BigCommerce
    provider: bigcommerce
    says: lists BigCommerce as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://loyverse.com/marketplace
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
    name: Dataddo
    provider: dataddo
    says: lists Dataddo as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.80
      key: AE-140.80
      name: Marketplaces
      url: /capabilities/marketplaces/
      via_parent: null
    credit: null
    layer: domain
    name: eBay
    provider: ebay
    says: lists eBay as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: FedEx
    provider: fedex
    says: lists FedEx as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Google Wallet
    provider: google-wallet
    says: lists Google Wallet as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Grab (GrabFood)
    provider: grab
    says: lists Grab (GrabFood) as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.80
      key: AE-140.80
      name: Marketplaces
      url: /capabilities/marketplaces/
      via_parent: null
    credit: null
    layer: domain
    name: Lazada
    provider: lazada
    says: lists Lazada as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Magento
    provider: magento
    says: lists Magento as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://loyverse.com/marketplace
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
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Otter (TryOtter)
    provider: otter
    says: lists Otter (TryOtter) as an integration
    source: https://loyverse.com/marketplace
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
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: SKUPLUGS
    provider: skuplugs
    says: lists SKUPLUGS as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: UPS
    provider: ups
    says: lists UPS as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://loyverse.com/marketplace
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
    name: Workato
    provider: workato
    says: lists Workato as an integration
    source: https://loyverse.com/marketplace
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
    source: https://loyverse.com/marketplace
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
    source: https://loyverse.com/marketplace
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
    name: Zoho Books
    provider: zoho-books
    says: lists Zoho Books as an integration
    source: https://loyverse.com/marketplace
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
    name: Zoho Flow
    provider: zoho-flow
    says: lists Zoho Flow as an integration
    source: https://loyverse.com/marketplace
    tier: declared
  kind: commercial
  name: Loyverse POS
  page: /applications/point-of-sale/loyverse-pos/
  slug: loyverse-pos
  url: https://loyverse.com/
- anchor: lightspeed-restaurant
  counts:
    declared: 16
    observed: 0
  evidence:
  - route: documentation
    url: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  - route: integrations page
    url: https://www.lightspeedhq.com/pos/restaurant/accounting/
  - route: integrations page
    url: https://www.lightspeedhq.com/pos/retail/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.30
      key: AE-140.30.30
      name: QR & Contactless Payments
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Alipay (Ant Group)
    provider: ant-group
    says: lists Alipay (Ant Group) as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Deliveroo
    provider: deliveroo
    says: lists Deliveroo as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2310.30.20
      key: BC-2310.30.20
      name: Store Shift Scheduling
      url: /capabilities/store-workforce-management/
      via_parent: Store Workforce Management
    credit: null
    layer: common
    name: Deputy
    provider: deputy
    says: lists Deputy as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: DoorDash
    provider: doordash
    says: lists DoorDash as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.50.40
      key: BC-2320.50.40
      name: POS Peripheral Configuration
      url: /capabilities/pos-configuration-management/
      via_parent: POS Configuration Management
    credit: null
    layer: domain
    name: Epson (receipt/kitchen printers)
    provider: epson
    says: lists Epson (receipt/kitchen printers) as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.40
      key: loyalty-retention-management
      name: Loyalty & Retention Management
      url: /capabilities/loyalty-retention-management/
      via_parent: null
    credit: null
    layer: domain
    name: Marsello
    provider: marsello
    says: lists Marsello as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: me&u
    provider: meandu
    says: lists me&u as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: Mr Yum
    provider: mr-yum
    says: lists Mr Yum as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
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
    name: MYOB
    provider: myob
    says: lists MYOB as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
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
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.lightspeedhq.com/pos/restaurant/accounting/
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
    name: Sage
    provider: sage
    says: lists Sage as an integration
    source: https://www.lightspeedhq.com/pos/restaurant/accounting/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2310.30.20
      key: BC-2310.30.20
      name: Store Shift Scheduling
      url: /capabilities/store-workforce-management/
      via_parent: Store Workforce Management
    credit: null
    layer: common
    name: Tanda
    provider: tanda
    says: lists Tanda as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Uber Eats
    provider: uber-eats
    says: lists Uber Eats as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.30
      key: AE-140.30.30
      name: QR & Contactless Payments
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: WeChat Pay
    provider: wechat
    says: lists WeChat Pay as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Westpac Presto Smart
    provider: westpac
    says: lists Westpac Presto Smart as an integration
    source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
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
    source: https://www.lightspeedhq.com/pos/restaurant/accounting/
    tier: declared
  kind: commercial
  name: Lightspeed Restaurant
  page: /applications/point-of-sale/lightspeed-restaurant/
  slug: lightspeed-restaurant
  url: https://www.lightspeedhq.com/pos/restaurant/
- anchor: square-point-of-sale
  counts:
    declared: 25
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
  - route: integrations page
    url: https://squareup.com/au/townsquare/business-apps-integrate-square
  - route: integrations page
    url: https://squareup.com/us/en/app-marketplace
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Airtax
    provider: airtax
    says: lists Airtax as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    credit: null
    layer: domain
    name: BevSpot
    provider: bevspot
    says: lists BevSpot as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: BigCommerce
    provider: bigcommerce
    says: lists BigCommerce as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: Bushfire
    provider: bushfire
    says: lists Bushfire as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: Domo
    provider: domo
    says: lists Domo as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Easyship
    provider: easyship
    says: lists Easyship as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Ecwid
    provider: ecwid
    says: lists Ecwid as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4070.30
      key: kitchen-production-operations
      name: Kitchen Production Operations
      url: /capabilities/kitchen-production-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Fresh KDS
    provider: fresh-kds
    says: lists Fresh KDS as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: GoDaddy
    provider: godaddy
    says: lists GoDaddy as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: IFTTT
    provider: ifttt
    says: lists IFTTT as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: Intuit QuickBooks
    provider: quickbooks
    says: lists Intuit QuickBooks as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Linktree
    provider: linktree
    says: lists Linktree as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Magento
    provider: magento
    says: lists Magento as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    credit: null
    layer: domain
    name: MarketMan
    provider: marketman
    says: lists MarketMan as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: MYOB
    provider: myob
    says: lists MYOB as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: Poptin
    provider: poptin
    says: lists Poptin as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipBob
    provider: shipbob
    says: lists ShipBob as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shopventory
    provider: shopventory
    says: lists Shopventory as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: SimpleTix
    provider: simpletix
    says: lists SimpleTix as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    credit: null
    layer: domain
    name: SKU IQ
    provider: sku-iq
    says: lists SKU IQ as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.60
      key: AE-210.60
      name: Restaurant Reservations
      url: /capabilities/restaurant-reservations/
      via_parent: null
    credit: null
    layer: domain
    name: TablesReady
    provider: tablesready
    says: lists TablesReady as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    name: TicketSocket
    provider: ticketsocket
    says: lists TicketSocket as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
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
    source: https://squareup.com/au/townsquare/business-apps-integrate-square
    tier: declared
  kind: commercial
  name: Square Point of Sale
  page: /applications/point-of-sale/square-point-of-sale/
  slug: square-point-of-sale
  url: https://squareup.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: point-of-sale
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Shopping
  store: google-play
  url: https://play.google.com/store/apps/category/SHOPPING
- category: E-commerce
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#e-commerce
- category: Selling products
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Payment Processing
  store: zapier
  url: https://zapier.com/apps
name: Point of Sale & In-Person Payments
needs:
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: card-present terminals, mobile money and wallets are the core of every POS
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.30
    key: AE-140.30.30
    name: QR & Contactless Payments
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: domain
  why: Alipay / WeChat Pay / Bancontact QR at the counter
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: nearest
  layer: domain
  why: loyalty passes into Google Wallet
- capability:
    attribution: Turbo EA
    id: BC-2320.50.40
    key: BC-2320.50.40
    name: POS Peripheral Configuration
    url: /capabilities/pos-configuration-management/
    via_parent: POS Configuration Management
  fit: exact
  layer: domain
  why: POS peripherals (cash recyclers, printers, terminals) -- no node fits; see Candidate extension nodes
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: daily sales posted to accounting
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: omnichannel catalog + inventory sync with the online store
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: AE-140.80
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  fit: exact
  layer: domain
  why: marketplace listing sync
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  fit: exact
  layer: domain
  why: delivery-app orders injected into the POS
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  fit: exact
  layer: domain
  why: order-at-table / QR menus
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: shipping online orders from POS stock
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  fit: exact
  layer: domain
  why: stock and restaurant inventory
- capability:
    attribution: Turbo EA
    id: BC-4070.30
    key: kitchen-production-operations
    name: Kitchen Production Operations
    url: /capabilities/kitchen-production-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: kitchen display systems
- capability:
    attribution: Turbo EA
    id: BC-420.40
    key: loyalty-retention-management
    name: Loyalty & Retention Management
    url: /capabilities/loyalty-retention-management/
    via_parent: null
  fit: exact
  layer: domain
  why: loyalty programmes
- capability:
    attribution: Turbo EA
    id: BC-2310.30.20
    key: BC-2310.30.20
    name: Store Shift Scheduling
    url: /capabilities/store-workforce-management/
    via_parent: Store Workforce Management
  fit: exact
  layer: common
  why: staff scheduling tied to sales
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: ticketed events sold through the POS
- capability:
    attribution: API Evangelist extension
    id: AE-210.60
    key: AE-210.60
    name: Restaurant Reservations
    url: /capabilities/restaurant-reservations/
    via_parent: null
  fit: nearest
  layer: domain
  why: waitlist / table paging
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: customer list sync to email marketing
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: receipts and notifications
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS receipts/marketing
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: digital receipts by WhatsApp
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: live dashboard updates
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: login brute-force protection
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: link-in-bio storefront link
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: generic connectors
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: on-site pop-ups
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: sales analytics export
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics SDKs ship in the mobile apps (Exodus)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting SDKs ship in the mobile apps (Exodus)
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution SDK ships in the mobile app (Exodus)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Loyverse POS
      - Square Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 84.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://loyverse.com/marketplace
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Loyverse POS
      - Square Point of Sale
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://loyverse.com/marketplace
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Loyverse POS
      - Square Point of Sale
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://loyverse.com/marketplace
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - Loyverse POS
      - Square Point of Sale
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        status: none
      name: Magento
      slug: magento
      sources:
      - https://loyverse.com/marketplace
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Headless Commerce
      - Magento
      tier: declared
      url: /providers/magento/
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-native
      agent_readiness: 48.5
      apps:
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 68.7
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Square Point of Sale
      band: developing
      in_catalog: true
      kin_score: 42.2
      mcp:
        status: none
      name: Ecwid
      slug: ecwid
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - E-Commerce
      - Online Store
      - Retail
      - Storefront
      tier: declared
      url: /providers/ecwid/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Square Point of Sale
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        source: https://developer.godaddy.com/mcp
        status: verified
      name: GoDaddy
      slug: godaddy
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Aftermarket
      - Certificates
      - DNS
      - Domains
      tier: declared
      url: /providers/godaddy/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Loyverse POS
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        status: unknown
      name: SKUPLUGS
      slug: skuplugs
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - E-Commerce
      - InventorySync
      - No-Code
      - POS Integration
      tier: declared
      url: /providers/skuplugs/
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Odoo Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 42.8
      apps:
      - Odoo Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://github.com/Adyen/adyen-mcp
        status: verified
      name: Adyen
      slug: adyen
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Agentic Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/adyen/
    - agent_band: agent-native
      agent_readiness: 71.7
      apps:
      - Odoo Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Odoo Point of Sale
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://github.com/razorpay/razorpay-mcp-server
        status: verified
      name: Razorpay
      slug: razorpay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Fintech
      - India
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Odoo Point of Sale
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: M-Pesa (Safaricom)
      slug: mpesa
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Fintech
      - Kenya
      - Mobile Money
      - Payments
      tier: observed
      url: /providers/mpesa/
    - agent_band: agent-ready
      agent_readiness: 53.2
      apps:
      - Odoo Point of Sale
      band: developing
      in_catalog: true
      kin_score: 44.0
      mcp:
        source: https://github.com/sumup/sumup-mcp
        status: verified
      name: SumUp
      slug: sumup
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Card Reader
      - Checkout
      - Payments
      - Point-of-Sale
      tier: observed
      url: /providers/sumup/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Odoo Point of Sale
      band: developing
      in_catalog: true
      kin_score: 40.4
      mcp:
        source: https://www.mercadopago.com.br/developers/en/docs/mcp-server/overview
        status: verified
      name: Mercado Pago
      slug: mercado-pago
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Checkout
      - Payments
      - Point-of-Sale
      - Subscription
      tier: observed
      url: /providers/mercado-pago/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Odoo Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 22.6
      mcp:
        status: none
      name: DPO Pay
      slug: dpo-pay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Africa
      - Company
      - Fintech
      - Payments
      tier: observed
      url: /providers/dpo-pay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 11.8
      mcp:
        status: none
      name: Viva.com (Viva Wallet)
      slug: viva-com
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Banking
      - Europe
      - Fintech
      - Payments
      tier: observed
      url: /providers/viva-com/
    - agent_band: human-only
      agent_readiness: 3.4
      apps:
      - Odoo Point of Sale
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: QFPay
      slug: qfpay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Company
      - Fintech
      - Payments
      tier: observed
      url: /providers/qfpay/
    - agent_band: null
      agent_readiness: null
      apps:
      - Odoo Point of Sale
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Pine Labs
      slug: pine-labs
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - Lightspeed Restaurant
      band: strong
      in_catalog: true
      kin_score: 64.2
      mcp:
        status: none
      name: Westpac Presto Smart
      slug: westpac
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Banks
      - CDR
      - Finance
      - Open Banking
      tier: declared
      url: /providers/westpac/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Lightspeed Restaurant
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        status: none
      name: DoorDash
      slug: doordash
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Delivery
      - Last Mile Delivery
      - Logistics
      - On-Demand
      tier: declared
      url: /providers/doordash/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Lightspeed Restaurant
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: Uber Eats
      slug: uber-eats
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Food Delivery
      - Last Mile Delivery
      - Uber Direct
      - Uber Eats
      tier: declared
      url: /providers/uber-eats/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Lightspeed Restaurant
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Deliveroo
      slug: deliveroo
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Food Delivery
      - Grocery
      - Logistics
      - Marketplace
      tier: declared
      url: /providers/deliveroo/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Loyverse POS
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://help.otter.ai/api/v2/help_center/en-us/articles/35287607569687.json
        status: verified
      name: Otter (TryOtter)
      slug: otter
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Delivery
      - Online Ordering
      - Order Management
      - Restaurant
      tier: declared
      url: /providers/otter/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Loyverse POS
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Grab (GrabFood)
      slug: grab
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Digital Payments
      - Food Delivery
      - Last Mile Delivery
      - Ride Hailing
      tier: declared
      url: /providers/grab/
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: MarketMan
      slug: marketman
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Inventory
      - Purchasing
      - Restaurant
      - Supply Chain
      tier: declared
      url: /providers/marketman/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: none
      name: SKU IQ
      slug: sku-iq
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - E-Commerce
      - Inventory
      - Point-of-Sale
      - Sync
      tier: declared
      url: /providers/sku-iq/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: none
      name: Shopventory
      slug: shopventory
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Company
      - Inventory
      - Point-of-Sale
      - Retail
      tier: declared
      url: /providers/shopventory/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        status: none
      name: BevSpot
      slug: bevspot
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Ai Apps
      - Company
      - Hospitality
      - Restaurant
      tier: declared
      url: /providers/bevspot/
  - capability:
      attribution: Turbo EA
      id: BC-2320.40.10
      key: BC-2320.40.10
      name: Cash Drawer Management
      url: /capabilities/pos-cash-and-tender-handling/
      via_parent: POS Cash and Tender Handling
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unknown
      name: Glory (cash recyclers)
      slug: glory-global-solutions
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - CashAutomation
      - Company
      - Financial Services
      - Retail Tech
      tier: observed
      url: /providers/glory-global-solutions/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo Point of Sale
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unknown
      name: CashDro
      slug: cashdro
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Cash Management
      - Company
      - Fintech
      - Retail
      tier: observed
      url: /providers/cashdro/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Odoo Point of Sale
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: Cashmatic
      slug: cashmatic
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Automation
      - Company
      - Payments
      - Retail
      tier: observed
      url: /providers/cashmatic/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        status: unknown
      name: SimpleTix
      slug: simpletix
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Company
      - Event
      - Software-as-a-Service
      - Ticketing
      tier: declared
      url: /providers/simpletix/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 14.3
      mcp:
        status: unknown
      name: TicketSocket
      slug: ticketsocket
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Company
      - Event
      - Marketing
      - Ticketing
      tier: declared
      url: /providers/ticketsocket/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Square Point of Sale
      band: minimal
      in_catalog: true
      kin_score: 2.9
      mcp:
        status: unknown
      name: Bushfire
      slug: bushfire
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Australia
      - Company
      - Fire Protection
      - Sprinkler Systems
      tier: declared
      url: /providers/bushfire/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.80
      key: AE-140.80
      name: Marketplaces
      url: /capabilities/marketplaces/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Loyverse POS
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: declared
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Loyverse POS
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        source: https://github.com/eBay/npm-public-api-mcp
        status: verified
      name: eBay
      slug: ebay
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Auctions
      - Commerce
      - Marketplace
      - Product
      tier: declared
      url: /providers/ebay/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Loyverse POS
      band: emerging
      in_catalog: true
      kin_score: 13.3
      mcp:
        status: none
      name: Lazada
      slug: lazada
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Alibaba
      - E-Commerce
      - Marketplace
      - Southeast Asia
      tier: declared
      url: /providers/lazada/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.30
      key: AE-140.30.30
      name: QR & Contactless Payments
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-native
      agent_readiness: 49.8
      apps:
      - Odoo Point of Sale
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Bancontact Payconiq
      slug: bancontact
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Banking
      - Belgium
      - Debit Cards
      - E-Commerce
      tier: observed
      url: /providers/bancontact/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Lightspeed Restaurant
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: WeChat Pay
      slug: wechat
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Messaging
      - Mini Programs
      - Payments
      - Social
      tier: declared
      url: /providers/wechat/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Lightspeed Restaurant
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        source: https://github.com/alipay/global-alipayplus-mcp
        status: verified
      name: Alipay (Ant Group)
      slug: ant-group
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Company
      - Fintech
      - Payments
      - Technology
      tier: declared
      url: /providers/ant-group/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lightspeed Restaurant
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        status: unknown
      name: me&u
      slug: meandu
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Company
      - Hospitality
      - Payments
      - Software-as-a-Service
      tier: declared
      url: /providers/meandu/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lightspeed Restaurant
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        status: none
      name: Mr Yum
      slug: mr-yum
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Hospitality
      - Ordering
      - RestaurantTech
      - Software-as-a-Service
      tier: declared
      url: /providers/mr-yum/
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Square Point of Sale
      band: developing
      in_catalog: true
      kin_score: 44.2
      mcp:
        source: https://github.com/easyship/easyship-mcp-plugin
        status: verified
      name: Easyship
      slug: easyship
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - E-Commerce
      - Fulfillment
      - Logistics
      - Shipping
      tier: declared
      url: /providers/easyship/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Square Point of Sale
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp:
        source: https://developer.shipbob.com/mcp-server/overview
        status: verified
      name: ShipBob
      slug: shipbob
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - 3PL
      - E-Commerce
      - Fulfillment
      - Logistics
      tier: declared
      url: /providers/shipbob/
  - capability:
      attribution: Turbo EA
      id: BC-2320.50.40
      key: BC-2320.50.40
      name: POS Peripheral Configuration
      url: /capabilities/pos-configuration-management/
      via_parent: POS Configuration Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo Point of Sale
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: iMin
      slug: imin
      sources:
      - https://github.com/odoo/odoo/tree/master/addons
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/imin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lightspeed Restaurant
      band: emerging
      in_catalog: true
      kin_score: 11.3
      mcp:
        status: unknown
      name: Epson (receipt/kitchen printers)
      slug: epson
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Automation
      - Company
      - Imaging
      - Printing
      tier: declared
      url: /providers/epson/
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: FedEx
      slug: fedex
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Address Validation
      - Freight
      - Logistics
      - Pickup
      tier: declared
      url: /providers/fedex/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Loyverse POS
      band: thin
      in_catalog: true
      kin_score: 27.9
      mcp:
        source: https://github.com/UPS-API/ups-mcp
        status: verified
      name: UPS
      slug: ups
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Fortune 500
      - Logistics
      - Shipping
      - Supply Chain
      tier: declared
      url: /providers/ups/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.5
      apps:
      - Loyverse POS
      band: strong
      in_catalog: true
      kin_score: 61.3
      mcp:
        source: https://developers.google.com/pay-wallet/ai-tools/mcp-server/mcp-server
        status: verified
      name: Google Wallet
      slug: google-wallet
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Digital Wallet
      - Google Wallet
      - Loyalty Cards
      - Mobile Payments
      tier: declared
      url: /providers/google-wallet/
  - capability:
      attribution: Turbo EA
      id: BC-4070.30
      key: kitchen-production-operations
      name: Kitchen Production Operations
      url: /capabilities/kitchen-production-operations/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Square Point of Sale
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: unknown
      name: Fresh KDS
      slug: fresh-kds
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Enterprise
      - Kitchen Display System
      - POS Integration
      - Restaurant
      tier: declared
      url: /providers/fresh-kds/
  - capability:
      attribution: Turbo EA
      id: BC-420.40
      key: loyalty-retention-management
      name: Loyalty & Retention Management
      url: /capabilities/loyalty-retention-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 9.1
      apps:
      - Lightspeed Restaurant
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        status: unknown
      name: Marsello
      slug: marsello
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Company
      - Loyalty
      - Marketing
      - Retail
      tier: declared
      url: /providers/marsello/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.60
      key: AE-210.60
      name: Restaurant Reservations
      url: /capabilities/restaurant-reservations/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Square Point of Sale
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: TablesReady
      slug: tablesready
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Company
      - Restaurant
      - Scheduling
      - Waitlist
      tier: declared
      url: /providers/tablesready/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Lightspeed Restaurant
      - Loyverse POS
      - Square Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://loyverse.com/marketplace
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      - https://www.lightspeedhq.com/pos/restaurant/accounting/
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Lightspeed Restaurant
      - Loyverse POS
      - Square Point of Sale
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://loyverse.com/marketplace
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      - https://www.lightspeedhq.com/pos/restaurant/accounting/
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
      - Lightspeed Restaurant
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: none
      name: MYOB
      slug: myob
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Accounting
      - Bills
      - Business Management
      - Invoices
      tier: declared
      url: /providers/myob/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Loyverse POS
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: documented
      name: Zoho Books
      slug: zoho-books
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Expenses
      - Invoicing
      tier: declared
      url: /providers/zoho-books/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Lightspeed Restaurant
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: none
      name: Sage
      slug: sage
      sources:
      - https://www.lightspeedhq.com/pos/restaurant/accounting/
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Cloud Software
      - ERP
      tier: declared
      url: /providers/sage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Loyverse POS
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: unknown
      name: Amaka
      slug: amaka
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Accounting
      - Artificial Intelligence
      - Automation
      - Company
      tier: declared
      url: /providers/amaka/
    - agent_band: null
      agent_readiness: null
      apps:
      - Square Point of Sale
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Airtax
      slug: airtax
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://docs.workato.com/mcp.html
        status: verified
      name: Workato
      slug: workato
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - AI Agents
      - API Management
      - Automation
      - B2B
      tier: declared
      url: /providers/workato/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Loyverse POS
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
    - agent_band: null
      agent_readiness: null
      apps:
      - Loyverse POS
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Zoho Flow
      slug: zoho-flow
      sources:
      - https://loyverse.com/marketplace
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Loyverse POS
      - Open Source Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
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
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
      - Square Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
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
      - Loyverse POS
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google CrashLytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Loyverse POS
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Loyverse POS
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Loyverse POS
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/fullstory/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Loyverse POS
      band: developing
      in_catalog: true
      kin_score: 50.2
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=dataddo
        status: verified
      name: Dataddo
      slug: dataddo
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - API Platform
      - Artificial Intelligence
      - Data Integration
      - Real-Time
      tier: declared
      url: /providers/dataddo/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Square Point of Sale
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: Domo
      slug: domo
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Analysis
      - Business Intelligence
      - Data
      - Pipelines
      tier: declared
      url: /providers/domo/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Loyverse POS
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Square Point of Sale
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Poptin
      slug: poptin
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Company
      - Email Marketing
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/poptin/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - NexoPOS
      - Square Point of Sale
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://github.com/Blair2004/NexoPOS/blob/master/composer.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: Turbo EA
      id: BC-2310.30.20
      key: BC-2310.30.20
      name: Store Shift Scheduling
      url: /capabilities/store-workforce-management/
      via_parent: Store Workforce Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Lightspeed Restaurant
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        status: none
      name: Deputy
      slug: deputy
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Employee Scheduling
      - Time and Attendance
      - Timesheets
      - Workforce Management
      tier: declared
      url: /providers/deputy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lightspeed Restaurant
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: none
      name: Tanda
      slug: tanda
      sources:
      - https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
      status: profiled
      tags:
      - Company
      - Human Resources
      - Payroll
      - Workforce Management
      tier: declared
      url: /providers/tanda/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Open Source Point of Sale
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/opensourcepos/opensourcepos/blob/master/README.md
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: declared
      url: /providers/google-recaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - Square Point of Sale
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: Linktree
      slug: linktree
      sources:
      - https://squareup.com/au/townsquare/business-apps-integrate-square
      status: profiled
      tags:
      - Company
      - Creator Economy
      - Link-in-bio
      - Media
      tier: declared
      url: /providers/linktree/
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
      - Square Point of Sale
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
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
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Source Point of Sale
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        status: none
      name: Text Marketer
      slug: textmarketer
      sources:
      - https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
      status: profiled
      tags:
      - Business
      - Marketing
      - SMS
      - United Kingdom
      tier: observed
      url: /providers/textmarketer/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - NexoPOS
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/Blair2004/NexoPOS/blob/master/composer.json
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Loyverse POS
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://loyverse.com/marketplace
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
  layer: common
summary:
  coverage_pct: 96.5
  declared_only: 59
  distinct_providers: 86
  in_catalog: 83
  mcp:
    documented: 2
    none: 36
    unchecked: 3
    verified: 32
  mcp_verified: 32
  mean_kin_score: 42.6
  observed: 27
  queued: 3
  reference_apps: 6
title: 'Point of Sale & In-Person Payments: application blueprint'
---
