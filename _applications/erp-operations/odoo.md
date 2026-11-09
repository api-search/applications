---
app: Odoo
app_slug: odoo
app_url: https://github.com/odoo/odoo
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-220.20.30
  key: BC-220.20.30
  layer: domain
  name: E-Invoicing and Real-Time Reporting
  providers:
  - ECPay e-invoice
  - Viettel S-Invoice
  url: /capabilities/indirect-tax-management/
  via_parent: Indirect Tax Management
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - Gelato
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Adyen
  - Amazon Payment Services
  - AsiaPay
  - Authorize.Net
  - Buckaroo
  - DPO Pay
  - ECPay
  - Flutterwave
  - iyzico
  - Mercado Pago
  - Mollie
  - Nuvei
  - Paymob
  - PayPal
  - PayU
  - Razorpay
  - Redsys
  - Stripe
  - Toss Payments
  - Worldline
  - Xendit
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320.20
  key: tender-and-payment-acceptance-management
  layer: domain
  name: Tender and Payment Acceptance Management
  providers:
  - Adyen
  - M-Pesa (Safaricom)
  - Mercado Pago
  - Mollie
  - Pine Labs
  - QFPay
  - Razorpay
  - Stripe
  - SumUp
  - Viva.com
  url: /capabilities/tender-and-payment-acceptance-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Google Places autocomplete
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Google Calendar
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20
  key: AE-120.20
  layer: common
  name: Maps & Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: common
  name: Photo & Image Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
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
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: erp-operations
  name: ERP & Business Operations
  url: /applications/erp-operations/
counts:
  declared: 0
  observed: 45
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts: &id001
    agent_band: agent-native
    agent_readiness: 43.7
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id007
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id008
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
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
  facts: *id001
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id009
      status: none
    slug: amazon-payment-services
    status: profiled
    tags: &id010
    - Company
    - E-Commerce
    - Fintech
    - Payments
    url: /providers/amazon-payment-services/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.7
    mcp: &id011
      status: unknown
    slug: asiapay
    status: profiled
    tags: &id012
    - Company
    - Digital Payments
    - Fintech
    - Payments
    url: /providers/asiapay/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id013
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id014
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id016
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 26.0
    mcp: &id017
      status: none
    slug: buckaroo
    status: profiled
    tags: &id018
    - In-Store Payments
    - Omnichannel
    - Online Payments
    - Payments
    url: /providers/buckaroo/
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
  facts:
    agent_band: agent-native
    agent_readiness: 69.6
    band: exemplar
    in_catalog: true
    kin_score: 82.8
    mcp: &id019
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id020
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: dpo
    status: queued for profiling
    tags: &id022 []
    url: null
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
  facts: &id002
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id023
      status: none
    slug: ecpay
    status: profiled
    tags: &id024
    - Company
    - Fintech
    - Payments
    - Taiwan
    url: /providers/ecpay/
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
  facts: *id002
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.4
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id025
      status: none
    slug: flutterwave
    status: profiled
    tags: &id026
    - Cards
    - Mobile Money
    - Payments
    - Payouts
    url: /providers/flutterwave/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id027
      status: none
    slug: gelato
    status: profiled
    tags: &id028
    - Distributed Production
    - E-Commerce
    - Fulfillment
    - Print on Demand
    url: /providers/gelato/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id029
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id030
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id031
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id032
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id033
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id034
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id035
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id036
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id037
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-places
    status: profiled
    tags: &id038
    - Geolocation
    - Google
    - Location
    - Restaurant
    url: /providers/google-places/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id039
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id040
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id041
      status: none
    slug: iyzico
    status: profiled
    tags: &id042
    - Company
    - Fintech
    - Payment Gateway
    - Payments
    url: /providers/iyzico/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id043
      status: none
    slug: mpesa
    status: profiled
    tags: &id044
    - Fintech
    - Kenya
    - Mobile Money
    - Payments
    url: /providers/mpesa/
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
  facts: &id003
    agent_band: agent-aware
    agent_readiness: 25.4
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id045
      source: https://www.mercadopago.com.br/developers/en/docs/mcp-server/overview
      status: verified
    slug: mercado-pago
    status: profiled
    tags: &id046
    - Checkout
    - Payments
    - Point-of-Sale
    - Subscription
    url: /providers/mercado-pago/
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
  facts: *id003
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id047
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id048
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
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
  facts: &id004
    agent_band: agent-native
    agent_readiness: 73.2
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id049
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id050
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
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
  facts: *id004
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id051
      status: none
    slug: nuvei
    status: profiled
    tags: &id052
    - Acquiring
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/nuvei/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id053
      source: https://github.com/PaymobAccept/Paymob-AI-Integration-Skill
      status: documented
    slug: paymob
    status: profiled
    tags: &id054
    - Fintech
    - MENA
    - Payment Gateway
    - Payments
    url: /providers/paymob/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id055
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id056
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id057
      source: https://github.com/payu-intrepos/payu-developer-mcp
      status: verified
    slug: payu
    status: profiled
    tags: &id058
    - Financial Services
    - Fintech
    - Payment Processing
    - Payments
    url: /providers/payu/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id059
      status: unchecked
    slug: pine-labs
    status: queued for profiling
    tags: &id060 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 3.5
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id061
      status: none
    slug: qfpay
    status: profiled
    tags: &id062
    - Company
    - Fintech
    - Payments
    url: /providers/qfpay/
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
  facts: &id005
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id063
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id064
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
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
  facts: *id005
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.0
    mcp: &id065
      status: none
    slug: redsys
    status: profiled
    tags: &id066
    - Acquiring
    - Company
    - Financial Services
    - Payments
    url: /providers/redsys/
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
  facts: &id006
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id067
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id068
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts: *id006
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
  facts:
    agent_band: agent-ready
    agent_readiness: 54.3
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id069
      source: https://github.com/sumup/sumup-mcp
      status: verified
    slug: sumup
    status: profiled
    tags: &id070
    - Card Reader
    - Checkout
    - Payments
    - Point-of-Sale
    url: /providers/sumup/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id071
      status: none
    slug: toss-payments
    status: profiled
    tags: &id072
    - Cards
    - Payment Gateway
    - Payments
    - South Korea
    url: /providers/toss-payments/
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
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id073
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id074
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 40.2
    mcp: &id075
      status: none
    slug: unsplash
    status: profiled
    tags: &id076
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id077
      status: unchecked
    slug: viettel
    status: queued for profiling
    tags: &id078 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.1
    mcp: &id079
      status: none
    slug: viva-com
    status: profiled
    tags: &id080
    - Banking
    - Europe
    - Fintech
    - Payments
    url: /providers/viva-com/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id081
      status: none
    slug: wordline
    status: profiled
    tags: &id082
    - Acquiring
    - Issuing
    - Payment Processing
    - Payments
    url: /providers/wordline/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: thin
    in_catalog: true
    kin_score: 30.2
    mcp: &id083
      status: none
    slug: xendit
    status: profiled
    tags: &id084
    - Fintech
    - Payment Gateway
    - Payments
    - Southeast Asia
    url: /providers/xendit/
  layer: domain
  name: Xendit
  provider: xendit
  says: ships the Xendit SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons/payment_xendit
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/erp-operations/odoo/
providers:
- agent_band: agent-native
  agent_readiness: 43.7
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id007
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id008
  url: /providers/adyen/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id009
  name: Amazon Payment Services
  slug: amazon-payment-services
  status: profiled
  tags: *id010
  url: /providers/amazon-payment-services/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.7
  mcp: *id011
  name: AsiaPay
  slug: asiapay
  status: profiled
  tags: *id012
  url: /providers/asiapay/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id013
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id014
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id015
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 26.0
  mcp: *id017
  name: Buckaroo
  slug: buckaroo
  status: profiled
  tags: *id018
  url: /providers/buckaroo/
- agent_band: agent-native
  agent_readiness: 69.6
  band: exemplar
  in_catalog: true
  kin_score: 82.8
  mcp: *id019
  name: Cloudflare Turnstile
  slug: cloudflare
  status: profiled
  tags: *id020
  url: /providers/cloudflare/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: DPO Pay
  slug: dpo
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id023
  name: ECPay
  slug: ecpay
  status: profiled
  tags: *id024
  url: /providers/ecpay/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id025
  name: Flutterwave
  slug: flutterwave
  status: profiled
  tags: *id026
  url: /providers/flutterwave/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id027
  name: Gelato
  slug: gelato
  status: profiled
  tags: *id028
  url: /providers/gelato/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id029
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id030
  url: /providers/google-gmail/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id031
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id032
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id033
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id034
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id035
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id036
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id037
  name: Google Places autocomplete
  slug: google-places
  status: profiled
  tags: *id038
  url: /providers/google-places/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id039
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id040
  url: /providers/google-recaptcha/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id041
  name: iyzico
  slug: iyzico
  status: profiled
  tags: *id042
  url: /providers/iyzico/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id043
  name: M-Pesa (Safaricom)
  slug: mpesa
  status: profiled
  tags: *id044
  url: /providers/mpesa/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id045
  name: Mercado Pago
  slug: mercado-pago
  status: profiled
  tags: *id046
  url: /providers/mercado-pago/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id047
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id048
  url: /providers/microsoft-outlook/
- agent_band: agent-native
  agent_readiness: 73.2
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id049
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id050
  url: /providers/mollie/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id051
  name: Nuvei
  slug: nuvei
  status: profiled
  tags: *id052
  url: /providers/nuvei/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id053
  name: Paymob
  slug: paymob
  status: profiled
  tags: *id054
  url: /providers/paymob/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id055
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id056
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id057
  name: PayU
  slug: payu
  status: profiled
  tags: *id058
  url: /providers/payu/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id059
  name: Pine Labs
  slug: pine-labs
  status: queued for profiling
  tags: *id060
  url: null
- agent_band: human-only
  agent_readiness: 3.5
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id061
  name: QFPay
  slug: qfpay
  status: profiled
  tags: *id062
  url: /providers/qfpay/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id063
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id064
  url: /providers/razorpay/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.0
  mcp: *id065
  name: Redsys
  slug: redsys
  status: profiled
  tags: *id066
  url: /providers/redsys/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id067
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id068
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 54.3
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id069
  name: SumUp
  slug: sumup
  status: profiled
  tags: *id070
  url: /providers/sumup/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id071
  name: Toss Payments
  slug: toss-payments
  status: profiled
  tags: *id072
  url: /providers/toss-payments/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id073
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id074
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 40.2
  mcp: *id075
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id076
  url: /providers/unsplash/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id077
  name: Viettel S-Invoice
  slug: viettel
  status: queued for profiling
  tags: *id078
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id079
  name: Viva.com
  slug: viva-com
  status: profiled
  tags: *id080
  url: /providers/viva-com/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id081
  name: Worldline
  slug: wordline
  status: profiled
  tags: *id082
  url: /providers/wordline/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: thin
  in_catalog: true
  kin_score: 30.2
  mcp: *id083
  name: Xendit
  slug: xendit
  status: profiled
  tags: *id084
  url: /providers/xendit/
siblings:
- name: Dolibarr
  rows: 13
  url: /applications/erp-operations/dolibarr/
- name: ERPNext
  rows: 24
  url: /applications/erp-operations/erpnext/
- name: Fishbowl
  rows: 42
  url: /applications/erp-operations/fishbowl/
- name: Katana
  rows: 19
  url: /applications/erp-operations/katana/
- name: Tryton
  rows: 13
  url: /applications/erp-operations/tryton/
sitemap: true
title: 'Odoo: ERP & Business Operations reference app'
---
