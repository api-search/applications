---
app: Salon Booking System
app_slug: salon-booking-system
app_url: https://wordpress.org/plugins/salon-booking-system/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Bancontact
  - Boipa
  - Cardcom
  - CardConnect
  - Iyzico
  - Mercado Pago
  - Mollie
  - PayEngine
  - PayPal
  - Paystack
  - Paytrail
  - PolyPay
  - PowerTranz
  - Przelewy24
  - RedSys
  - Square
  - Stripe
  - Swish (Sweden)
  - Takepayments
  - Upay
  - Verifone
  - Viva Wallet
  - Wallee
  - Worldpay
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - iP1 SMS
  - Plivo
  - Twilio
  - All My SMS
  - Capitole Mobile
  - OVH SMS
  - Skebby
  - SMS Hosting
  - SMS.to
  - Spryng
  - SureSMS
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook login
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 38
  observed: 6
credits: []
evidence:
- route: documentation
  url: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
- route: source code
  url: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/AI/ProxyClient.php
- route: source code
  url: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/Action/Sms/
- route: source code
  url: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/Third/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/AI/ProxyClient.php
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id017
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id018
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/Third/
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
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id021
      status: unchecked
    slug: ip1sms
    status: profiled
    tags: &id022
    - Communications
    - Company
    - Enterprise
    - SMS
    url: /providers/ip1sms/
  layer: common
  name: iP1 SMS
  provider: ip1sms
  says: ships the iP1 SMS SDK or integration code
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/Action/Sms/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id031
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/AI/ProxyClient.php
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
    agent_band: agent-aware
    agent_readiness: 25.8
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id043
      source: https://github.com/plivo/mcp
      status: verified
    slug: plivo
    status: profiled
    tags: &id044
    - CPaaS
    - Communications
    - SMS
    - Voice
    url: /providers/plivo/
  layer: common
  name: Plivo
  provider: plivo
  says: ships the Plivo SDK or integration code
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/Action/Sms/
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
    mcp: &id071
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id072
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/src/SLN/Action/Sms/
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id001
      status: unchecked
    slug: allmysms
    status: profiled
    tags: &id002
    - Communications
    - Company
    - Marketing
    - SMS
    url: /providers/allmysms/
  layer: common
  name: All My SMS
  provider: allmysms
  says: lists All My SMS as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id005
      status: none
    slug: bancontact
    status: profiled
    tags: &id006
    - Banking
    - Belgium
    - Debit Cards
    - E-Commerce
    url: /providers/bancontact/
  layer: common
  name: Bancontact
  provider: bancontact
  says: lists Bancontact as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id007
      status: unchecked
    slug: boipa
    status: profiled
    tags: &id008
    - B2B
    - Card Processing
    - Ireland
    - Payments
    url: /providers/boipa/
  layer: common
  name: Boipa
  provider: boipa
  says: lists Boipa as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: capitole-mobile
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: common
  name: Capitole Mobile
  provider: capitole-mobile
  says: lists Capitole Mobile as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    kin_score: 2.7
    mcp: &id011
      status: unchecked
    slug: cardcom
    status: profiled
    tags: &id012
    - Company
    - Fintech
    - Merchant Services
    - Payments
    url: /providers/cardcom/
  layer: common
  name: Cardcom
  provider: cardcom
  says: lists Cardcom as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    kin_score: 7.7
    mcp: &id013
      status: none
    slug: cardconnect
    status: profiled
    tags: &id014
    - Company
    url: /providers/cardconnect/
  layer: common
  name: CardConnect
  provider: cardconnect
  says: lists CardConnect as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id015
      status: none
    slug: facebook
    status: profiled
    tags: &id016
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook login
  provider: facebook
  says: lists Facebook login as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id019
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id020
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: lists Google reCAPTCHA as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id023
      status: none
    slug: iyzico
    status: profiled
    tags: &id024
    - Company
    - Fintech
    - Payment Gateway
    - Payments
    url: /providers/iyzico/
  layer: common
  name: Iyzico
  provider: iyzico
  says: lists Iyzico as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id025
      status: none
    slug: mailchimp
    status: profiled
    tags: &id026
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 24.9
    band: developing
    in_catalog: true
    kin_score: 40.4
    mcp: &id027
      source: https://www.mercadopago.com.br/developers/en/docs/mcp-server/overview
      status: verified
    slug: mercado-pago
    status: profiled
    tags: &id028
    - Checkout
    - Payments
    - Point-of-Sale
    - Subscription
    url: /providers/mercado-pago/
  layer: common
  name: Mercado Pago
  provider: mercado-pago
  says: lists Mercado Pago as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    mcp: &id029
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id030
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: common
  name: Mollie
  provider: mollie
  says: lists Mollie as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 43.2
    mcp: &id033
      source: https://mcp.eu.ovhcloud.com/mcp
      status: verified
    slug: ovh-cloud
    status: profiled
    tags: &id034
    - Cloud
    - Compute
    - Hosting
    - Servers
    url: /providers/ovh-cloud/
  layer: common
  name: OVH SMS
  provider: ovh-cloud
  says: lists OVH SMS as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id035
      status: none
    slug: payengine
    status: profiled
    tags: &id036
    - Embedded Payments
    - Merchant Onboarding
    - Payment Facilitation
    - Payments
    url: /providers/payengine/
  layer: common
  name: PayEngine
  provider: payengine
  says: lists PayEngine as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    mcp: &id037
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id038
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 29.8
    band: strong
    in_catalog: true
    kin_score: 59.4
    mcp: &id039
      source: https://github.com/PaystackOSS/paystack-mcp-server
      status: verified
    slug: paystack
    status: profiled
    tags: &id040
    - Africa
    - Fintech
    - Payments
    - Recurring Billing
    url: /providers/paystack/
  layer: common
  name: Paystack
  provider: paystack
  says: lists Paystack as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 54.0
    mcp: &id041
      status: unchecked
    slug: paytrail
    status: profiled
    tags: &id042
    - E-Commerce
    - Fintech
    - Omnichannel
    - Payments
    url: /providers/paytrail/
  layer: common
  name: Paytrail
  provider: paytrail
  says: lists Paytrail as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    kin_score: 6.8
    mcp: &id045
      status: unchecked
    slug: polypay
    status: profiled
    tags: &id046
    - Merchant Processing
    - Payment Terminals
    - Payments
    - Virtual Terminals
    url: /providers/polypay/
  layer: common
  name: PolyPay
  provider: polypay
  says: lists PolyPay as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.7
    mcp: &id047
      status: unchecked
    slug: powertranz
    status: profiled
    tags: &id048
    - Merchant Services
    - Payment Gateway
    - Payments
    - Point-of-Sale
    url: /providers/powertranz/
  layer: common
  name: PowerTranz
  provider: powertranz
  says: lists PowerTranz as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id049
      status: none
    slug: przelewy24
    status: profiled
    tags: &id050
    - BLIK
    - Bank Transfers
    - Payment Gateway
    - Payments
    url: /providers/przelewy24/
  layer: common
  name: Przelewy24
  provider: przelewy24
  says: lists Przelewy24 as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    kin_score: 19.9
    mcp: &id051
      status: none
    slug: redsys
    status: profiled
    tags: &id052
    - Acquiring
    - Company
    - Financial Services
    - Payments
    url: /providers/redsys/
  layer: common
  name: RedSys
  provider: redsys
  says: lists RedSys as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id053
      status: unchecked
    slug: skebby
    status: profiled
    tags: &id054
    - Company
    - Italy
    - Messaging
    - SMS
    url: /providers/skebby/
  layer: common
  name: Skebby
  provider: skebby
  says: lists Skebby as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id055
      status: unchecked
    slug: sms-hosting
    status: profiled
    tags: &id056
    - Communications
    - Marketing
    - Messaging
    - SMS
    url: /providers/sms-hosting/
  layer: common
  name: SMS Hosting
  provider: sms-hosting
  says: lists SMS Hosting as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id057
      status: unchecked
    slug: sms-to
    status: profiled
    tags: &id058
    - Bulk SMS
    - Messaging API
    - Omnichannel Messaging
    - SMS
    url: /providers/sms-to/
  layer: common
  name: SMS.to
  provider: sms-to
  says: lists SMS.to as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.0
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id059
      status: unchecked
    slug: spryng
    status: profiled
    tags: &id060
    - Messaging
    - RCS
    - SMS
    - WhatsApp Business
    url: /providers/spryng/
  layer: common
  name: Spryng
  provider: spryng
  says: lists Spryng as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
  says: lists Square as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
  says: lists Stripe as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id065
      status: unchecked
    slug: suresms
    status: profiled
    tags: &id066
    - Communications Platform
    - Industry Solutions
    - Integration Services
    - SMS Gateway
    url: /providers/suresms/
  layer: common
  name: SureSMS
  provider: suresms
  says: lists SureSMS as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 29.4
    mcp: &id067
      status: unchecked
    slug: swish-payments
    status: profiled
    tags: &id068
    - Fintech
    - Mobile
    - Payments
    - Sweden
    url: /providers/swish-payments/
  layer: common
  name: Swish (Sweden)
  provider: swish-payments
  says: lists Swish (Sweden) as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 7.0
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id069
      status: unknown
    slug: takepayments
    status: profiled
    tags: &id070
    - Payment Gateway
    - Payment Processing
    - Payments
    - United Kingdom
    url: /providers/takepayments/
  layer: common
  name: Takepayments
  provider: takepayments
  says: lists Takepayments as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 0.9
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id073
      status: unchecked
    slug: upay
    status: profiled
    tags: &id074
    - Company
    - Credit Cards
    - Fintech
    - Payments
    url: /providers/upay/
  layer: common
  name: Upay
  provider: upay
  says: lists Upay as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 37.3
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id075
      status: none
    slug: verifone
    status: profiled
    tags: &id076
    - E-Commerce
    - Payments
    - Point-of-Sale
    - Terminal Management
    url: /providers/verifone/
  layer: common
  name: Verifone
  provider: verifone
  says: lists Verifone as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    kin_score: 11.8
    mcp: &id077
      status: none
    slug: viva-com
    status: profiled
    tags: &id078
    - Banking
    - Europe
    - Fintech
    - Payments
    url: /providers/viva-com/
  layer: common
  name: Viva Wallet
  provider: viva-com
  says: lists Viva Wallet as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 35.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id079
      status: unchecked
    slug: wallee
    status: profiled
    tags: &id080
    - Company
    - E-Commerce
    - Fintech
    - Payments
    url: /providers/wallee/
  layer: common
  name: Wallee
  provider: wallee
  says: lists Wallee as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id081
      status: none
    slug: whatsapp
    status: profiled
    tags: &id082
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id083
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id084
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
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
    agent_readiness: 45.1
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id085
      status: none
    slug: worldpay
    status: profiled
    tags: &id086
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/worldpay/
  layer: common
  name: Worldpay
  provider: worldpay
  says: lists Worldpay as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id087
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id088
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://plugins.svn.wordpress.org/salon-booking-system/trunk/readme.txt
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/salon-booking-system/
providers:
- agent_band: agent-aware
  agent_readiness: 18.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id001
  name: All My SMS
  slug: allmysms
  status: profiled
  tags: *id002
  url: /providers/allmysms/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-native
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id005
  name: Bancontact
  slug: bancontact
  status: profiled
  tags: *id006
  url: /providers/bancontact/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id007
  name: Boipa
  slug: boipa
  status: profiled
  tags: *id008
  url: /providers/boipa/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Capitole Mobile
  slug: capitole-mobile
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.7
  mcp: *id011
  name: Cardcom
  slug: cardcom
  status: profiled
  tags: *id012
  url: /providers/cardcom/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id013
  name: CardConnect
  slug: cardconnect
  status: profiled
  tags: *id014
  url: /providers/cardconnect/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id015
  name: Facebook login
  slug: facebook
  status: profiled
  tags: *id016
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id017
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id018
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id019
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id020
  url: /providers/google-recaptcha/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id021
  name: iP1 SMS
  slug: ip1sms
  status: profiled
  tags: *id022
  url: /providers/ip1sms/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id023
  name: Iyzico
  slug: iyzico
  status: profiled
  tags: *id024
  url: /providers/iyzico/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id025
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id026
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: developing
  in_catalog: true
  kin_score: 40.4
  mcp: *id027
  name: Mercado Pago
  slug: mercado-pago
  status: profiled
  tags: *id028
  url: /providers/mercado-pago/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id029
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id030
  url: /providers/mollie/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id031
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id032
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id033
  name: OVH SMS
  slug: ovh-cloud
  status: profiled
  tags: *id034
  url: /providers/ovh-cloud/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id035
  name: PayEngine
  slug: payengine
  status: profiled
  tags: *id036
  url: /providers/payengine/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id037
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id038
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: strong
  in_catalog: true
  kin_score: 59.4
  mcp: *id039
  name: Paystack
  slug: paystack
  status: profiled
  tags: *id040
  url: /providers/paystack/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 54.0
  mcp: *id041
  name: Paytrail
  slug: paytrail
  status: profiled
  tags: *id042
  url: /providers/paytrail/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id043
  name: Plivo
  slug: plivo
  status: profiled
  tags: *id044
  url: /providers/plivo/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id045
  name: PolyPay
  slug: polypay
  status: profiled
  tags: *id046
  url: /providers/polypay/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id047
  name: PowerTranz
  slug: powertranz
  status: profiled
  tags: *id048
  url: /providers/powertranz/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id049
  name: Przelewy24
  slug: przelewy24
  status: profiled
  tags: *id050
  url: /providers/przelewy24/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id051
  name: RedSys
  slug: redsys
  status: profiled
  tags: *id052
  url: /providers/redsys/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id053
  name: Skebby
  slug: skebby
  status: profiled
  tags: *id054
  url: /providers/skebby/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id055
  name: SMS Hosting
  slug: sms-hosting
  status: profiled
  tags: *id056
  url: /providers/sms-hosting/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id057
  name: SMS.to
  slug: sms-to
  status: profiled
  tags: *id058
  url: /providers/sms-to/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id059
  name: Spryng
  slug: spryng
  status: profiled
  tags: *id060
  url: /providers/spryng/
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
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id065
  name: SureSMS
  slug: suresms
  status: profiled
  tags: *id066
  url: /providers/suresms/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 29.4
  mcp: *id067
  name: Swish (Sweden)
  slug: swish-payments
  status: profiled
  tags: *id068
  url: /providers/swish-payments/
- agent_band: agent-aware
  agent_readiness: 7.0
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id069
  name: Takepayments
  slug: takepayments
  status: profiled
  tags: *id070
  url: /providers/takepayments/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id071
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id072
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 0.9
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id073
  name: Upay
  slug: upay
  status: profiled
  tags: *id074
  url: /providers/upay/
- agent_band: agent-ready
  agent_readiness: 37.3
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id075
  name: Verifone
  slug: verifone
  status: profiled
  tags: *id076
  url: /providers/verifone/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id077
  name: Viva Wallet
  slug: viva-com
  status: profiled
  tags: *id078
  url: /providers/viva-com/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id079
  name: Wallee
  slug: wallee
  status: profiled
  tags: *id080
  url: /providers/wallee/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id081
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id082
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id083
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id084
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 45.1
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id085
  name: Worldpay
  slug: worldpay
  status: profiled
  tags: *id086
  url: /providers/worldpay/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id087
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id088
  url: /providers/zapier/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Boulevard
  rows: 16
  url: /applications/salon-spa-management/boulevard/
- name: Fresha
  rows: 6
  url: /applications/salon-spa-management/fresha/
- name: Mindbody
  rows: 22
  url: /applications/salon-spa-management/mindbody/
- name: Open Salon
  rows: 2
  url: /applications/salon-spa-management/open-salon/
- name: Square Appointments
  rows: 32
  url: /applications/salon-spa-management/square-appointments/
- name: Vagaro
  rows: 2
  url: /applications/salon-spa-management/vagaro/
sitemap: true
title: 'Salon Booking System: Salon & Spa Management reference app'
---
