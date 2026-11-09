---
access: understanding
agent_layer:
- app: Dolibarr
  finding: ships its own MCP server (ai/class/mcp.class.php, mcptool, mcpauth) alongside the LLM adapter
  source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/mcp.class.php
  tier: observed
- app: Katana
  finding: Katana MCP connects Katana to ChatGPT and Claude (listed on the integrations page)
  source: https://katanamrp.com/integrations/
  tier: declared
apps:
- anchor: odoo
  counts:
    declared: 0
    observed: 45
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.odoo.mobile/latest/
  - route: source code
    url: https://github.com/odoo/odoo/tree/master/addons
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
    name: Adyen
    provider: adyen
    says: ships the Adyen SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_adyen
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
    name: Adyen
    provider: adyen
    says: ships the Adyen SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/pos_adyen
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
    name: Amazon Payment Services
    provider: amazon-payment-services
    says: ships the Amazon Payment Services SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_aps
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
    name: AsiaPay
    provider: asiapay
    says: ships the AsiaPay SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_asiapay
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
    name: Authorize.Net
    provider: authorizenet
    says: ships the Authorize.Net SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_authorize
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
    source: https://github.com/odoo/odoo/tree/master/addons/cloud_storage_azure
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
    name: Buckaroo
    provider: buckaroo
    says: ships the Buckaroo SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_buckaroo
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
    provider: cloudflare
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/website_cf_turnstile
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
    name: DPO Pay
    provider: dpo
    says: ships the DPO Pay SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_dpo
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
    name: ECPay
    provider: ecpay
    says: ships the ECPay SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_ecpay
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20.30
      key: BC-220.20.30
      name: E-Invoicing and Real-Time Reporting
      url: /capabilities/indirect-tax-management/
      via_parent: Indirect Tax Management
    credit: null
    layer: domain
    name: ECPay e-invoice
    provider: ecpay
    says: ships the ECPay e-invoice SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/l10n_tw_edi_ecpay
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
    name: Flutterwave
    provider: flutterwave
    says: ships the Flutterwave SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_flutterwave
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gelato
    provider: gelato
    says: ships the Gelato SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/sale_gelato
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
    name: Gmail
    provider: google-gmail
    says: ships the Gmail SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/google_gmail
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
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/google_calendar
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
    source: https://github.com/odoo/odoo/tree/master/addons/cloud_storage_google
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
    source: https://github.com/odoo/odoo/tree/master/addons/website_google_map
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Google Places autocomplete
    provider: google-places
    says: ships the Google Places autocomplete SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/google_address_autocomplete
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
    source: https://github.com/odoo/odoo/tree/master/addons/google_recaptcha
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
    name: iyzico
    provider: iyzico
    says: ships the iyzico SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_iyzico
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_safaricom
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
    name: Mercado Pago
    provider: mercado-pago
    says: ships the Mercado Pago SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_mercado_pago
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_mercado_pago
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
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: ships the Microsoft Outlook SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/microsoft_outlook
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
    source: https://github.com/odoo/odoo/tree/master/addons/payment_mollie
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_mollie
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
    name: Nuvei
    provider: nuvei
    says: ships the Nuvei SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_nuvei
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
    name: Paymob
    provider: paymob
    says: ships the Paymob SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_paymob
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
    source: https://github.com/odoo/odoo/tree/master/addons/payment_paypal
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
    name: PayU
    provider: payu
    says: ships the PayU SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_payu
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_pine_labs
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_qfpay
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
    source: https://github.com/odoo/odoo/tree/master/addons/payment_razorpay
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_razorpay
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
    name: Redsys
    provider: redsys
    says: ships the Redsys SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_redsys
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
    source: https://github.com/odoo/odoo/tree/master/addons/payment_stripe
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_stripe
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
    source: https://github.com/odoo/odoo/tree/master/addons/pos_sumup
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
    name: Toss Payments
    provider: toss-payments
    says: ships the Toss Payments SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_toss_payments
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
    source: https://github.com/odoo/odoo/tree/master/addons/sms_twilio
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: common
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/web_unsplash
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20.30
      key: BC-220.20.30
      name: E-Invoicing and Real-Time Reporting
      url: /capabilities/indirect-tax-management/
      via_parent: Indirect Tax Management
    credit: null
    layer: domain
    name: Viettel S-Invoice
    provider: viettel
    says: ships the Viettel S-Invoice SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/l10n_vn_edi_viettel
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
    name: Viva.com
    provider: viva-com
    says: ships the Viva.com SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/pos_viva_com
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
    name: Worldline
    provider: wordline
    says: ships the Worldline SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_worldline
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
    name: Xendit
    provider: xendit
    says: ships the Xendit SDK or integration code
    source: https://github.com/odoo/odoo/tree/master/addons/payment_xendit
    tier: observed
  kind: self-hosted
  name: Odoo
  page: /applications/erp-operations/odoo/
  slug: odoo
  url: https://github.com/odoo/odoo
- anchor: erpnext
  counts:
    declared: 0
    observed: 24
  evidence:
  - route: source code
    url: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations
  - route: source code
    url: https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype
  - route: source code
    url: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype
  - route: source code
    url: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Seller Central
    provider: amazon
    says: ships the Amazon Seller Central SDK or integration code
    source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/amazon
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
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/braintree_settings
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Geoapify
    provider: geoapify
    says: ships the Geoapify SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
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
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/gocardless_settings
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
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/google_calendar
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
    name: Google Contacts
    provider: google-people
    says: ships the Google Contacts SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/google_contacts
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
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: HERE
    provider: here
    says: ships the HERE SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
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
    name: Keycloak
    provider: keycloak
    says: ships the Keycloak SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
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
    name: M-Pesa
    provider: mpesa
    says: ships the M-Pesa SDK or integration code
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/mpesa_settings
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim
    provider: nominatim
    says: ships the Nominatim SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
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
    name: Office 365 sign-in
    provider: microsoft-entra
    says: ships the Office 365 sign-in SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
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
    name: Paymob
    provider: paymob
    says: ships the Paymob SDK or integration code
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paymob_settings
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
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paypal_settings
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
    name: Paytm
    provider: paytm
    says: ships the Paytm SDK or integration code
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paytm_settings
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
    source: https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype/plaid_settings
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
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/razorpay_settings
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
    name: Salesforce sign-in
    provider: salesforce
    says: ships the Salesforce sign-in SDK or integration code
    source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
    tier: observed
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
    says: ships the Shopify SDK or integration code
    source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/shopify
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
    source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/stripe_settings
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Unicommerce
    provider: unicommerce
    says: ships the Unicommerce SDK or integration code
    source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/unicommerce
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zenoti
    provider: zenoti
    says: ships the Zenoti SDK or integration code
    source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/zenoti
    tier: observed
  kind: self-hosted
  name: ERPNext
  page: /applications/erp-operations/erpnext/
  slug: erpnext
  url: https://github.com/frappe/erpnext
- anchor: dolibarr
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: source code
    url: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs
  - route: source code
    url: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/admin/multicurrency.php
  - route: source code
    url: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
  - route: source code
    url: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: currencylayer
    provider: currencylayer
    says: ships the currencylayer SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/admin/multicurrency.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: DeepSeek
    provider: deepseek
    says: ships the DeepSeek SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
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
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
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
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
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
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/paypal
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Perplexity
    provider: perplexity
    says: ships the Perplexity SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
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
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/stripe
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
    says: ships the Zapier SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/zapier
    tier: observed
  kind: self-hosted
  name: Dolibarr
  page: /applications/erp-operations/dolibarr/
  slug: dolibarr
  url: https://github.com/Dolibarr/dolibarr
- anchor: tryton
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: source code
    url: https://github.com/tryton/tryton/tree/default/modules
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
    name: Braintree
    provider: braintree
    says: ships the Braintree SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/account_payment_braintree
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20.30
      key: BC-220.20.30
      name: E-Invoicing and Real-Time Reporting
      url: /capabilities/indirect-tax-management/
      via_parent: Indirect Tax Management
    credit: null
    layer: domain
    name: Chorus Pro
    provider: chorus-pro
    says: ships the Chorus Pro SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/account_fr_chorus
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: DPD
    provider: dpd
    says: ships the DPD SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_dpd
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
    name: Eagle Doc
    provider: eagle-doc
    says: ships the Eagle Doc SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/document_incoming_ocr_eagle_doc
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: GLS (MyGLS)
    provider: gls-group
    says: ships the GLS (MyGLS) SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_mygls
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20.30
      key: BC-220.20.30
      name: E-Invoicing and Real-Time Reporting
      url: /capabilities/indirect-tax-management/
      via_parent: Indirect Tax Management
    credit: null
    layer: domain
    name: Peppyrus
    provider: peppyrus
    says: ships the Peppyrus SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/edocument_peppol_peppyrus
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sendcloud
    provider: sendcloud
    says: ships the Sendcloud SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_sendcloud
    tier: observed
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
    says: ships the Shopify SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/web_shop_shopify
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
    source: https://github.com/tryton/tryton/tree/default/modules/account_payment_stripe
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
    name: Typless
    provider: typless
    says: ships the Typless SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/document_incoming_ocr_typless
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: UPS
    provider: ups
    says: ships the UPS SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_ups
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Vue Storefront (Alokai)
    provider: vue-storefront
    says: ships the Vue Storefront (Alokai) SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/web_shop_vue_storefront
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
    name: WinBooks
    provider: winbooks
    says: ships the WinBooks SDK or integration code
    source: https://github.com/tryton/tryton/tree/default/modules/account_export_winbooks
    tier: observed
  kind: self-hosted
  name: Tryton
  page: /applications/erp-operations/tryton/
  slug: tryton
  url: https://github.com/tryton/tryton
- anchor: katana
  counts:
    declared: 19
    observed: 0
  evidence:
  - route: integrations page
    url: https://katanamrp.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: 2Ship
    provider: 2ship
    says: lists 2Ship as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon
    provider: amazon
    says: lists Amazon as an integration
    source: https://katanamrp.com/integrations/
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
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: eBay
    provider: ebay
    says: lists eBay as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jikko
    provider: jikko
    says: lists Jikko as an integration
    source: https://katanamrp.com/integrations/
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
    name: Mintsoft
    provider: mintsoft
    says: lists Mintsoft as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Prospect CRM
    provider: prospect-crm
    says: lists Prospect CRM as an integration
    source: https://katanamrp.com/integrations/
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
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://katanamrp.com/integrations/
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
    source: https://katanamrp.com/integrations/
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
    name: ShipHero
    provider: shiphero
    says: lists ShipHero as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shippo
    provider: shippo
    says: lists Shippo as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipStation
    provider: shipstation
    says: lists ShipStation as an integration
    source: https://katanamrp.com/integrations/
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
    source: https://katanamrp.com/integrations/
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
    source: https://katanamrp.com/integrations/
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
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://katanamrp.com/integrations/
    tier: declared
  kind: commercial
  name: Katana
  page: /applications/erp-operations/katana/
  slug: katana
  url: https://katanamrp.com/
- anchor: fishbowl
  counts:
    declared: 42
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.fishbowlinventory.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Adobe Commerce
    provider: adobe-commerce
    says: lists Adobe Commerce as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon
    provider: amazon
    says: lists Amazon as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Authorize.Net
    provider: authorizenet
    says: lists Authorize.Net as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara
    provider: avalara
    says: lists Avalara as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ConverSight
    provider: conversight
    says: lists ConverSight as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: DHL
    provider: dhl
    says: lists DHL as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: eBay
    provider: ebay
    says: lists eBay as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Endicia
    provider: stamps-com
    says: lists Endicia as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: FedEx
    provider: fedex
    says: lists FedEx as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2380.20
      key: BC-2380.20
      name: Lot & Batch Traceability Management
      url: /capabilities/lot-batch-traceability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Metrc
    provider: metrc
    says: lists Metrc as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-520.10
      key: demand-planning-management
      name: Demand Planning Management
      url: /capabilities/demand-planning-management/
      via_parent: null
    credit: null
    layer: domain
    name: Netstock
    provider: netstock
    says: lists Netstock as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Newegg
    provider: newegg
    says: lists Newegg as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: OnTrac
    provider: ontrac
    says: lists OnTrac as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pepperi
    provider: pepperi
    says: lists Pepperi as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: QuickBooks (Online, Canada, Payments)
    provider: quickbooks
    says: lists QuickBooks (Online, Canada, Payments) as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Reckon
    provider: reckon
    says: lists Reckon as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Shift4Shop
    provider: shift4shop
    says: lists Shift4Shop as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipRush
    provider: shiprush
    says: lists ShipRush as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipStation
    provider: shipstation
    says: lists ShipStation as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipWorks
    provider: shipworks
    says: lists ShipWorks as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    source: https://www.fishbowlinventory.com/integrations
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
    name: Spark Shipping
    provider: spark-shipping
    says: lists Spark Shipping as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: SPS Commerce
    provider: sps-commerce
    says: lists SPS Commerce as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: StarShip
    provider: starship-shipping
    says: lists StarShip as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-520.10
      key: demand-planning-management
      name: Demand Planning Management
      url: /capabilities/demand-planning-management/
      via_parent: null
    credit: null
    layer: domain
    name: StockTrim
    provider: stocktrim
    says: lists StockTrim as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: TrueCommerce
    provider: truecommerce
    says: lists TrueCommerce as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: UPS
    provider: ups
    says: lists UPS as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: USPS
    provider: usps
    says: lists USPS as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Volusion
    provider: volusion
    says: lists Volusion as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Walmart
    provider: walmart
    says: lists Walmart as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-920
      key: AE-920
      name: Barcode, RFID & Mobile Data Capture
      url: /capabilities/storage-and-inventory-operations-management/
      via_parent: Storage and Inventory Operations Management
    credit: null
    layer: domain
    name: Wasp Barcode
    provider: wasp-barcode
    says: lists Wasp Barcode as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Web Shop Manager
    provider: web-shop-manager
    says: lists Web Shop Manager as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    source: https://www.fishbowlinventory.com/integrations
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
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-920
      key: AE-920
      name: Barcode, RFID & Mobile Data Capture
      url: /capabilities/storage-and-inventory-operations-management/
      via_parent: Storage and Inventory Operations Management
    credit: null
    layer: domain
    name: Zebra
    provider: zebra-technologies
    says: lists Zebra as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Zen Cart
    provider: zen-cart
    says: lists Zen Cart as an integration
    source: https://www.fishbowlinventory.com/integrations
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
    name: Zoey
    provider: zoey
    says: lists Zoey as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho
    provider: zoho
    says: lists Zoho as an integration
    source: https://www.fishbowlinventory.com/integrations
    tier: declared
  kind: commercial
  name: Fishbowl
  page: /applications/erp-operations/fishbowl/
  slug: fishbowl
  url: https://www.fishbowlinventory.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: erp-operations
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Resource Planning
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#resource-planning
- category: Manufacturing
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#manufacturing
- category: ERP
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Commerce
  store: zapier
  url: https://zapier.com/apps
name: ERP & Business Operations
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
  why: online payment acquirers for invoices, sale orders and web shop
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: card-present terminals in ERP point-of-sale modules
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  fit: exact
  layer: domain
  why: carrier rating, labels and tracking from delivery orders
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 3PL/WMS, dropship and print-on-demand fulfilment; EDI rows nearest
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  fit: exact
  layer: domain
  why: marketplace order sync (Amazon, eBay, Walmart, Newegg)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: storefront order/product/stock sync
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: accounting sync/export for inventory/MRP tools
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CRM to sales-order handoff
- capability:
    attribution: Turbo EA
    id: BC-220.20.30
    key: BC-220.20.30
    name: E-Invoicing and Real-Time Reporting
    url: /capabilities/indirect-tax-management/
    via_parent: Indirect Tax Management
  fit: exact
  layer: domain
  why: national e-invoicing clearance (nearest; no e-invoicing node)
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sales tax calculation
- capability:
    attribution: Turbo EA
    id: BC-520.10
    key: demand-planning-management
    name: Demand Planning Management
    url: /capabilities/demand-planning-management/
    via_parent: null
  fit: exact
  layer: domain
  why: stock forecasting add-ons
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: barcode hardware and regulated track-and-trace (nearest)
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: bank feed sync (Plaid)
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: multicurrency rate updates
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: incoming supplier invoice capture
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: AI analytics add-on
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: Gmail/Outlook/Calendar/Contacts sync
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: OAuth sign-in
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: workforce IdP sign-in
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: attachment storage on cloud buckets
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: web forms
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS notifications
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: address autocomplete and geolocation
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  fit: exact
  layer: common
  why: website maps
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: common
  why: stock images in website builder
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier connectors
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: file sync
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: Dolibarr AI module
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
      - Dolibarr
      - ERPNext
      - Odoo
      - Tryton
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: &id001
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/stripe
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/stripe_settings
      - https://github.com/odoo/odoo/tree/master/addons/payment_stripe
      status: profiled
      tags: &id002
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Dolibarr
      - ERPNext
      - Odoo
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/paypal
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paypal_settings
      - https://github.com/odoo/odoo/tree/master/addons/payment_paypal
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - ERPNext
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        source: https://github.com/PaymobAccept/Paymob-AI-Integration-Skill
        status: documented
      name: Paymob
      slug: paymob
      sources:
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paymob_settings
      - https://github.com/odoo/odoo/tree/master/addons/payment_paymob
      status: profiled
      tags:
      - Fintech
      - MENA
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/paymob/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - ERPNext
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp: &id007
        source: https://github.com/razorpay/razorpay-mcp-server
        status: verified
      name: Razorpay
      slug: razorpay
      sources:
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/razorpay_settings
      - https://github.com/odoo/odoo/tree/master/addons/payment_razorpay
      status: profiled
      tags: &id008
      - Fintech
      - India
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - ERPNext
      - Tryton
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/braintree_settings
      - https://github.com/tryton/tryton/tree/default/modules/account_payment_braintree
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Fishbowl
      - Odoo
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.Net
      slug: authorizenet
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_authorize
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: agent-native
      agent_readiness: 43.7
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp: &id003
        source: https://github.com/Adyen/adyen-mcp
        status: verified
      name: Adyen
      slug: adyen
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_adyen
      status: profiled
      tags: &id004
      - Agentic Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/adyen/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp: &id005
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_mollie
      status: profiled
      tags: &id006
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-ready
      agent_readiness: 33.4
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: Flutterwave
      slug: flutterwave
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_flutterwave
      status: profiled
      tags:
      - Cards
      - Mobile Money
      - Payments
      - Payouts
      tier: observed
      url: /providers/flutterwave/
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - ERPNext
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://developer.gocardless.com/mcp
        status: verified
      name: GoCardless
      slug: gocardless
      sources:
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/gocardless_settings
      status: profiled
      tags:
      - Bank Debit
      - Direct Debit
      - Payments
      - Recurring Payments
      tier: observed
      url: /providers/gocardless/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: Worldline
      slug: wordline
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_worldline
      status: profiled
      tags:
      - Acquiring
      - Issuing
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/wordline/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - ERPNext
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp: &id009
        status: none
      name: M-Pesa
      slug: mpesa
      sources:
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/mpesa_settings
      status: profiled
      tags: &id010
      - Fintech
      - Kenya
      - Mobile Money
      - Payments
      tier: observed
      url: /providers/mpesa/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        status: none
      name: iyzico
      slug: iyzico
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_iyzico
      status: profiled
      tags:
      - Company
      - Fintech
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/iyzico/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp: &id011
        source: https://www.mercadopago.com.br/developers/en/docs/mcp-server/overview
        status: verified
      name: Mercado Pago
      slug: mercado-pago
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_mercado_pago
      status: profiled
      tags: &id012
      - Checkout
      - Payments
      - Point-of-Sale
      - Subscription
      tier: observed
      url: /providers/mercado-pago/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/payu-intrepos/payu-developer-mcp
        status: verified
      name: PayU
      slug: payu
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_payu
      status: profiled
      tags:
      - Financial Services
      - Fintech
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/payu/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Odoo
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        status: none
      name: Amazon Payment Services
      slug: amazon-payment-services
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_aps
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Fintech
      - Payments
      tier: observed
      url: /providers/amazon-payment-services/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Odoo
      band: thin
      in_catalog: true
      kin_score: 30.2
      mcp:
        status: none
      name: Xendit
      slug: xendit
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_xendit
      status: profiled
      tags:
      - Fintech
      - Payment Gateway
      - Payments
      - Southeast Asia
      tier: observed
      url: /providers/xendit/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Odoo
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: none
      name: Toss Payments
      slug: toss-payments
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_toss_payments
      status: profiled
      tags:
      - Cards
      - Payment Gateway
      - Payments
      - South Korea
      tier: observed
      url: /providers/toss-payments/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Odoo
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Nuvei
      slug: nuvei
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_nuvei
      status: profiled
      tags:
      - Acquiring
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/nuvei/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Odoo
      band: emerging
      in_catalog: true
      kin_score: 26.0
      mcp:
        status: none
      name: Buckaroo
      slug: buckaroo
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_buckaroo
      status: profiled
      tags:
      - In-Store Payments
      - Omnichannel
      - Online Payments
      - Payments
      tier: observed
      url: /providers/buckaroo/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - ERPNext
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=paytm
        status: verified
      name: Paytm
      slug: paytm
      sources:
      - https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paytm_settings
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - Payouts
      - UPI
      tier: observed
      url: /providers/paytm/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Odoo
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: none
      name: Redsys
      slug: redsys
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_redsys
      status: profiled
      tags:
      - Acquiring
      - Company
      - Financial Services
      - Payments
      tier: observed
      url: /providers/redsys/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp: &id013
        status: none
      name: ECPay
      slug: ecpay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_ecpay
      status: profiled
      tags: &id014
      - Company
      - Fintech
      - Payments
      - Taiwan
      tier: observed
      url: /providers/ecpay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo
      band: minimal
      in_catalog: true
      kin_score: 4.7
      mcp:
        status: unknown
      name: AsiaPay
      slug: asiapay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_asiapay
      status: profiled
      tags:
      - Company
      - Digital Payments
      - Fintech
      - Payments
      tier: observed
      url: /providers/asiapay/
    - agent_band: null
      agent_readiness: null
      apps:
      - Odoo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: DPO Pay
      slug: dpo
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/payment_dpo
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Fishbowl
      - Tryton
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        source: https://github.com/UPS-API/ups-mcp
        status: verified
      name: UPS
      slug: ups
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_ups
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Fortune 500
      - Logistics
      - Shipping
      - Supply Chain
      tier: observed
      url: /providers/ups/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Fishbowl
      - Katana
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: none
      name: ShipStation
      slug: shipstation
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Labels
      - Logistics
      - ShipStation
      tier: declared
      url: /providers/shipstation/
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Tryton
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        status: none
      name: Sendcloud
      slug: sendcloud
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_sendcloud
      status: profiled
      tags:
      - Carrier
      - E-Commerce
      - Logistics
      - Shipping
      tier: observed
      url: /providers/sendcloud/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Tryton
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: none
      name: GLS (MyGLS)
      slug: gls-group
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_mygls
      status: profiled
      tags:
      - Logistics
      - Netherlands
      - Parcel
      - Supply Chain
      tier: observed
      url: /providers/gls-group/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Tryton
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: none
      name: DPD
      slug: dpd
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_dpd
      status: profiled
      tags:
      - Company
      - International Shipping
      - Logistics
      - Parcel Delivery
      tier: observed
      url: /providers/dpd/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - Fishbowl
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        status: none
      name: FedEx
      slug: fedex
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Address Validation
      - Freight
      - Logistics
      - Pickup
      tier: declared
      url: /providers/fedex/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Katana
      band: strong
      in_catalog: true
      kin_score: 55.7
      mcp:
        source: https://github.com/goshippo/ai
        status: verified
      name: Shippo
      slug: shippo
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Labels
      - Logistics
      - Returns
      tier: declared
      url: /providers/shippo/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Fishbowl
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: USPS
      slug: usps
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Government
      - Logistics
      - Postal Service
      - Shipping
      tier: declared
      url: /providers/usps/
    - agent_band: human-only
      agent_readiness: 5.0
      apps:
      - Fishbowl
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: ShipWorks
      slug: shipworks
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Logistics
      - Shipping
      - Software
      tier: declared
      url: /providers/shipworks/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: DHL
      slug: dhl
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Freight
      - Logistics
      - Shipping
      tier: declared
      url: /providers/dhl/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: unknown
      name: ShipRush
      slug: shiprush
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Multi-Carrier
      - Shipping
      - Software-as-a-Service
      tier: declared
      url: /providers/shiprush/
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - Katana
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        status: unknown
      name: 2Ship
      slug: 2ship
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - Company
      - Logistics
      - Shipping
      - Software
      tier: declared
      url: /providers/2ship/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fishbowl
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: none
      name: OnTrac
      slug: ontrac
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Delivery
      - E-Commerce
      - Logistics
      - Shipping
      tier: declared
      url: /providers/ontrac/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fishbowl
      band: minimal
      in_catalog: true
      kin_score: 7.3
      mcp:
        status: unknown
      name: StarShip
      slug: starship-shipping
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Carrier Rates
      - Discounted Shipping
      - Shipping
      tier: declared
      url: /providers/starship-shipping/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Katana
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: Jikko
      slug: jikko
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/jikko/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - ERPNext
      - Fishbowl
      - Katana
      - Tryton
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/shopify
      - https://github.com/tryton/tryton/tree/default/modules/web_shop_shopify
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: observed
      url: /providers/shopify/
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - Fishbowl
      - Katana
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Fishbowl
      - Katana
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
    - agent_band: null
      agent_readiness: null
      apps:
      - Tryton
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Vue Storefront (Alokai)
      slug: vue-storefront
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/web_shop_vue_storefront
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 18.9
      mcp:
        status: unknown
      name: Zoey
      slug: zoey
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - B2B
      - Company
      - E-Commerce
      - Wholesale
      tier: declared
      url: /providers/zoey/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: Adobe Commerce
      slug: adobe-commerce
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Adobe
      - Commerce
      - E-Commerce
      - Magento
      tier: declared
      url: /providers/adobe-commerce/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: Shift4Shop
      slug: shift4shop
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Order
      - Product
      - Shopping Cart
      tier: declared
      url: /providers/shift4shop/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: none
      name: Volusion
      slug: volusion
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Online Store
      - Order
      - Product
      tier: declared
      url: /providers/volusion/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 13.5
      mcp:
        status: none
      name: Web Shop Manager
      slug: web-shop-manager
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Automotive
      - B2B
      - E-Commerce
      - Software-as-a-Service
      tier: declared
      url: /providers/web-shop-manager/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: Zen Cart
      slug: zen-cart
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - PHP
      - Shopping Cart
      tier: declared
      url: /providers/zen-cart/
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: *id001
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_stripe
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 43.7
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp: *id003
      name: Adyen
      slug: adyen
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_adyen
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/adyen/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp: *id005
      name: Mollie
      slug: mollie
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_mollie
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp: *id007
      name: Razorpay
      slug: razorpay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_razorpay
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp: *id009
      name: M-Pesa (Safaricom)
      slug: mpesa
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_safaricom
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/mpesa/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        source: https://github.com/sumup/sumup-mcp
        status: verified
      name: SumUp
      slug: sumup
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_sumup
      status: profiled
      tags:
      - Card Reader
      - Checkout
      - Payments
      - Point-of-Sale
      tier: observed
      url: /providers/sumup/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp: *id011
      name: Mercado Pago
      slug: mercado-pago
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_mercado_pago
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/mercado-pago/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: none
      name: Viva.com
      slug: viva-com
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_viva_com
      status: profiled
      tags:
      - Banking
      - Europe
      - Fintech
      - Payments
      tier: observed
      url: /providers/viva-com/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - Odoo
      band: minimal
      in_catalog: true
      kin_score: 6.4
      mcp:
        status: none
      name: QFPay
      slug: qfpay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_qfpay
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
      - Odoo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Pine Labs
      slug: pine-labs
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/pos_pine_labs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - ERPNext
      - Fishbowl
      - Katana
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Seller Central
      slug: amazon
      sources:
      - https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/amazon
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Fishbowl
      - Katana
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://github.com/eBay/npm-public-api-mcp
        status: verified
      name: eBay
      slug: ebay
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Auctions
      - Commerce
      - Marketplace
      - Product
      tier: declared
      url: /providers/ebay/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - ERPNext
      band: developing
      in_catalog: true
      kin_score: 48.5
      mcp:
        status: none
      name: Zenoti
      slug: zenoti
      sources:
      - https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/zenoti
      status: profiled
      tags:
      - Beauty
      - Company
      - Services
      - Wellness
      tier: observed
      url: /providers/zenoti/
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Fishbowl
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Walmart
      slug: walmart
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Commerce
      - Fortune 100
      - Retail
      - Walmart
      tier: declared
      url: /providers/walmart/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Fishbowl
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Newegg
      slug: newegg
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Company
      - Consumer
      - E-Commerce
      - Marketplace
      tier: declared
      url: /providers/newegg/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 20.7
      mcp:
        source: https://www.npmjs.com/package/@pepperi-addons/api-mcp
        status: verified
      name: Pepperi
      slug: pepperi
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - B2B
      - Commerce
      - Company
      - Retail
      tier: declared
      url: /providers/pepperi/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - Fishbowl
      - Katana
      band: exemplar
      in_catalog: true
      kin_score: 94.6
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - Fishbowl
      - Katana
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp: &id015
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags: &id016
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Fishbowl
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho
      slug: zoho
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Collaboration
      - Customer Service
      tier: declared
      url: /providers/zoho/
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Katana
      band: strong
      in_catalog: true
      kin_score: 55.5
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Katana
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unknown
      name: Prospect CRM
      slug: prospect-crm
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/prospect-crm/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.3
      apps:
      - Fishbowl
      - Katana
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Fishbowl
      - Katana
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://katanamrp.com/integrations/
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: null
      agent_readiness: null
      apps:
      - Tryton
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: WinBooks
      slug: winbooks
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/account_export_winbooks
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: unknown
      name: Reckon
      slug: reckon
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Accounting
      - Australia
      - Small Business
      - Software
      tier: declared
      url: /providers/reckon/
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - Odoo
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: none
      name: Gelato
      slug: gelato
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/sale_gelato
      status: profiled
      tags:
      - Distributed Production
      - E-Commerce
      - Fulfillment
      - Print on Demand
      tier: observed
      url: /providers/gelato/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - ERPNext
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: unknown
      name: Unicommerce
      slug: unicommerce
      sources:
      - https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/unicommerce
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Order Management
      - Software-as-a-Service
      tier: observed
      url: /providers/unicommerce/
    - agent_band: agent-ready
      agent_readiness: 40.4
      apps:
      - Katana
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        source: https://developer.shipbob.com/mcp-server/overview
        status: verified
      name: ShipBob
      slug: shipbob
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - 3PL
      - E-Commerce
      - Fulfillment
      - Logistics
      tier: declared
      url: /providers/shipbob/
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Katana
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: ShipHero
      slug: shiphero
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Fulfillment
      - GraphQL
      - Warehouse Management
      tier: declared
      url: /providers/shiphero/
    - agent_band: agent-aware
      agent_readiness: 12.2
      apps:
      - Katana
      band: emerging
      in_catalog: true
      kin_score: 23.1
      mcp:
        status: unknown
      name: Mintsoft
      slug: mintsoft
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Logistics
      - Software-as-a-Service
      - Warehouse
      tier: declared
      url: /providers/mintsoft/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Spark Shipping
      slug: spark-shipping
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Automation
      - Company
      - Dropshipping
      - E-Commerce
      tier: declared
      url: /providers/spark-shipping/
  - capability:
      attribution: Turbo EA
      id: BC-220.20.30
      key: BC-220.20.30
      name: E-Invoicing and Real-Time Reporting
      url: /capabilities/indirect-tax-management/
      via_parent: Indirect Tax Management
    providers:
    - agent_band: human-only
      agent_readiness: 4.3
      apps:
      - Tryton
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: unknown
      name: Peppyrus
      slug: peppyrus
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/edocument_peppol_peppyrus
      status: profiled
      tags:
      - Company
      - E-Invoicing
      - Free
      - PEPPOL
      tier: observed
      url: /providers/peppyrus/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - Tryton
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: unknown
      name: Chorus Pro
      slug: chorus-pro
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/account_fr_chorus
      status: profiled
      tags:
      - Company
      - France
      - Payments
      - Public Sector
      tier: observed
      url: /providers/chorus-pro/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Odoo
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp: *id013
      name: ECPay e-invoice
      slug: ecpay
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/l10n_tw_edi_ecpay
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/ecpay/
    - agent_band: null
      agent_readiness: null
      apps:
      - Odoo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Viettel S-Invoice
      slug: viettel
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/l10n_vn_edi_viettel
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Fishbowl
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: SPS Commerce
      slug: sps-commerce
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Company
      - EDI
      - Retail
      - Supply Chain
      tier: declared
      url: /providers/sps-commerce/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 12.2
      mcp:
        status: none
      name: TrueCommerce
      slug: truecommerce
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Company
      - EDI
      - Integration
      - Supply Chain
      tier: declared
      url: /providers/truecommerce/
  - capability:
      attribution: API Evangelist extension
      id: AE-920
      key: AE-920
      name: Barcode, RFID & Mobile Data Capture
      url: /capabilities/storage-and-inventory-operations-management/
      via_parent: Storage and Inventory Operations Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: Zebra
      slug: zebra-technologies
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Barcodes
      - Manufacturing
      - RFID
      - Warehouse Automation
      tier: declared
      url: /providers/zebra-technologies/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 21.8
      mcp:
        status: none
      name: Wasp Barcode
      slug: wasp-barcode
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Asset Tracking
      - Barcode Technology
      - Company
      - Inventory
      tier: declared
      url: /providers/wasp-barcode/
  - capability:
      attribution: Turbo EA
      id: BC-520.10
      key: demand-planning-management
      name: Demand Planning Management
      url: /capabilities/demand-planning-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Fishbowl
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        status: unknown
      name: StockTrim
      slug: stocktrim
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Company
      - Forecasting
      - Inventory
      - Supply Chain
      tier: declared
      url: /providers/stocktrim/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Fishbowl
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: none
      name: Netstock
      slug: netstock
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Demand Planning
      - Inventory
      - Supply Chain Planning
      tier: declared
      url: /providers/netstock/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Tryton
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Eagle Doc
      slug: eagle-doc
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/document_incoming_ocr_eagle_doc
      status: profiled
      tags:
      - Artificial Intelligence
      - Bookkeeping
      - Company
      - OCR
      tier: observed
      url: /providers/eagle-doc/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Tryton
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: none
      name: Typless
      slug: typless
      sources:
      - https://github.com/tryton/tryton/tree/default/modules/document_incoming_ocr_typless
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Company
      - Document Processing
      tier: observed
      url: /providers/typless/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Fishbowl
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: ConverSight
      slug: conversight
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
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
      - https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype/plaid_settings
      status: profiled
      tags:
      - Bank Accounts
      - Finance
      - Fintech
      - Open Banking
      tier: observed
      url: /providers/plaid/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Fishbowl
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Dolibarr
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        status: none
      name: currencylayer
      slug: currencylayer
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/admin/multicurrency.php
      status: profiled
      tags:
      - Conversion
      - Foreign Exchange
      - Historical Rates
      - Time Frame
      tier: observed
      url: /providers/currencylayer/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Fishbowl
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/avadev/mcp
        status: verified
      name: Avalara
      slug: avalara
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Accounting
      - Avalara
      - Tax
      tier: declared
      url: /providers/avalara/
  - capability:
      attribution: Turbo EA
      id: BC-2380.20
      key: BC-2380.20
      name: Lot & Batch Traceability Management
      url: /capabilities/lot-batch-traceability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Fishbowl
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: none
      name: Metrc
      slug: metrc
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Cannabis
      - Company
      - Compliance
      - Track and Trace
      tier: declared
      url: /providers/metrc/
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.5
      apps:
      - Fishbowl
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: none
      name: Endicia
      slug: stamps-com
      sources:
      - https://www.fishbowlinventory.com/integrations
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Logistics
      - Shipping
      tier: declared
      url: /providers/stamps-com/
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
      - Katana
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp: &id017
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://katanamrp.com/integrations/
      status: profiled
      tags: &id018
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Dolibarr
      - ERPNext
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Dolibarr
      - ERPNext
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Office 365 sign-in
      slug: microsoft-entra
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
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
      - Dolibarr
      - ERPNext
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/core/modules/oauth
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - ERPNext
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
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
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - ERPNext
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/google_calendar
      - https://github.com/odoo/odoo/tree/master/addons/google_calendar
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
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Outlook
      slug: microsoft-outlook
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/microsoft_outlook
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: observed
      url: /providers/microsoft-outlook/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - ERPNext
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Contacts
      slug: google-people
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/google_contacts
      status: profiled
      tags:
      - Address Book
      - Contacts
      - Google
      - People
      tier: observed
      url: /providers/google-people/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/google_gmail
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-native
      agent_readiness: 55.5
      apps:
      - ERPNext
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: HERE
      slug: here
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
      status: profiled
      tags:
      - Location
      - Mapping
      - Maps
      - Spatial
      tier: observed
      url: /providers/here/
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - ERPNext
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: Geoapify
      slug: geoapify
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Location
      - Maps
      tier: observed
      url: /providers/geoapify/
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Places autocomplete
      slug: google-places
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/google_address_autocomplete
      status: profiled
      tags:
      - Geolocation
      - Google
      - Location
      - Restaurant
      tier: observed
      url: /providers/google-places/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - ERPNext
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/website_cf_turnstile
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/google_recaptcha
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
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/cloud_storage_google
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
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/cloud_storage_azure
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
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - ERPNext
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp: *id015
      name: Salesforce sign-in
      slug: salesforce
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
      status: profiled
      tags: *id016
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - ERPNext
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: observed
      url: /providers/keycloak/
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
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/website_google_map
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Odoo
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/web_unsplash
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
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
      - Odoo
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/odoo/odoo/tree/master/addons/sms_twilio
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
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
      - Dolibarr
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp: *id017
      name: Zapier
      slug: zapier
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/zapier
      status: profiled
      tags: *id018
      tier: observed
      url: /providers/zapier/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Dolibarr
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
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
      - Dolibarr
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-native
      agent_readiness: 67.7
      apps:
      - Dolibarr
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Dolibarr
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Dolibarr
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - Dolibarr
      band: developing
      in_catalog: true
      kin_score: 43.3
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/ai/class/llmadapter.class.php
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
  layer: agent
summary:
  coverage_pct: 95.0
  declared_only: 45
  distinct_providers: 120
  in_catalog: 114
  mcp:
    documented: 1
    none: 57
    unchecked: 6
    verified: 43
  mcp_verified: 43
  mean_kin_score: 42.7
  observed: 75
  queued: 6
  reference_apps: 6
title: 'ERP & Business Operations: application blueprint'
---
