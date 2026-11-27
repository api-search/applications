---
access: understanding
agent_layer: []
apps:
- anchor: wger-(gym-module)
  counts:
    declared: 1
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/de.wger.flutter/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
  - route: source code
    url: https://github.com/wger-project/wger/tree/master/wger/gym
  - route: source code
    url: https://raw.githubusercontent.com/wger-project/docker/master/config/prod.env
  integrations:
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
    source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: Open Food Facts
    provider: open-food-facts
    says: ships the Open Food Facts SDK or integration code
    source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
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
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
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
    says: lists Cloudflare Turnstile as an integration
    source: https://raw.githubusercontent.com/wger-project/docker/master/config/prod.env
    tier: declared
  kind: self-hosted
  name: wger (gym module)
  page: /applications/gym-studio-management/wger-gym-module/
  slug: wger-gym-module
  url: https://github.com/wger-project/wger
- anchor: gym-one
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/composer.json
  - route: source code
    url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
  - route: source code
    url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/example.env
  - route: source code
    url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/index.php
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    credit: null
    layer: domain
    name: Apple Wallet
    provider: apple
    says: ships the Apple Wallet SDK or integration code
    source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/composer.json
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/index.php
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
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
    source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
    tier: observed
  kind: self-hosted
  name: GYM One
  page: /applications/gym-studio-management/gym-one/
  slug: gym-one
  url: https://github.com/mayerbalintdev/GYM-One
- anchor: mindbody
  counts:
    declared: 14
    observed: 10
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
  - route: integrations page
    url: https://integrations.mindbodyonline.com/
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Tealium
    provider: tealium
    says: ships the Tealium SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://integrations.mindbodyonline.com/
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
    name: Bench
    provider: bench
    says: lists Bench as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: ClassPass
    provider: classpass
    says: lists ClassPass as an integration
    source: https://integrations.mindbodyonline.com/
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
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.80
      key: AE-140.80
      name: Marketplaces
      url: /capabilities/marketplaces/
      via_parent: null
    credit: null
    layer: common
    name: Groupon
    provider: groupon
    says: lists Groupon as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    credit: null
    layer: common
    name: Healthdesk
    provider: healthdesk
    says: lists Healthdesk as an integration
    source: https://integrations.mindbodyonline.com/
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
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickerNotes
    provider: quickernotes
    says: lists QuickerNotes as an integration
    source: https://integrations.mindbodyonline.com/
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
    name: REACH ai
    provider: reach-ai
    says: lists REACH ai as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4050.10
      key: loyalty-programme-design
      name: Loyalty Programme Design
      url: /capabilities/loyalty-programme-design/
      via_parent: null
    credit: null
    layer: domain
    name: Referrizer
    provider: referrizer
    says: lists Referrizer as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify (ShopifyConnect)
    provider: shopify
    says: lists Shopify (ShopifyConnect) as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.30
      key: AE-140.10.30
      name: Mobile Commerce App Builders
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Studio Stack
    provider: studio-stack
    says: lists Studio Stack as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: WaiverKing
    provider: waiverking
    says: lists WaiverKing as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: sms-messaging-apps
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Weave
    provider: weave
    says: lists Weave as an integration
    source: https://integrations.mindbodyonline.com/
    tier: declared
  kind: commercial
  name: Mindbody
  page: /applications/gym-studio-management/mindbody/
  slug: mindbody
  url: https://www.mindbodyonline.com/
- anchor: wodify
  counts:
    declared: 19
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.wodify.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: AMcards
    provider: amcards
    says: lists AMcards as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: voice-telephony
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: common
    name: Callingly
    provider: callingly
    says: lists Callingly as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: ClassPass
    provider: classpass
    says: lists ClassPass as an integration
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
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
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
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
    name: Meta (Pixel, Leads)
    provider: facebook
    says: lists Meta (Pixel, Leads) as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: wearable-health-data-sync
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Myzone
    provider: myzone
    says: lists Myzone as an integration
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: SurveyMonkey
    provider: surveymonkey
    says: lists SurveyMonkey as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Thankster
    provider: thankster
    says: lists Thankster as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.50
      key: AE-140.30.50
      name: HSA/FSA Eligible Payments
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Truemed
    provider: truemed
    says: lists Truemed as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Typeform
    provider: typeform
    says: lists Typeform as an integration
    source: https://www.wodify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: Wellhub
    provider: wellhub
    says: lists Wellhub as an integration
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
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
    source: https://www.wodify.com/integrations
    tier: declared
  kind: commercial
  name: Wodify
  page: /applications/gym-studio-management/wodify/
  slug: wodify
  url: https://www.wodify.com/
- anchor: zen-planner
  counts:
    declared: 21
    observed: 0
  evidence:
  - route: integrations page
    url: https://zenplanner.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: ClassPass
    provider: classpass
    says: lists ClassPass as an integration
    source: https://zenplanner.com/integrations/
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
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
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
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.90
      key: AE-200.90
      name: Physical Access Control & Mobile Keys
      url: /capabilities/physical-access-control-mobile-keys/
      via_parent: null
    credit: null
    layer: domain
    name: HybridAF
    provider: hybridaf
    says: lists HybridAF as an integration
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
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
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: Optum
    provider: optum
    says: lists Optum as an integration
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4050.10
      key: loyalty-programme-design
      name: Loyalty Programme Design
      url: /capabilities/loyalty-programme-design/
      via_parent: null
    credit: null
    layer: domain
    name: Perkville
    provider: perkville
    says: lists Perkville as an integration
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.120
      key: AE-140.120
      name: Print-on-Demand Fulfilment
      url: /capabilities/print-on-demand-fulfilment/
      via_parent: null
    credit: null
    layer: common
    name: Printful
    provider: printful
    says: lists Printful as an integration
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.10
      key: AE-130.10.10
      name: Workout Logging
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: SugarWOD
    provider: sugarwod
    says: lists SugarWOD as an integration
    source: https://zenplanner.com/integrations/
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
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2880.20
      key: preventive-care-wellness
      name: Preventive Care & Wellness
      url: /capabilities/preventive-care-wellness/
      via_parent: null
    credit: null
    layer: domain
    name: Welld Health
    provider: welld-health
    says: lists Welld Health as an integration
    source: https://zenplanner.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: Wellhub
    provider: wellhub
    says: lists Wellhub as an integration
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
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
    source: https://zenplanner.com/integrations/
    tier: declared
  kind: commercial
  name: Zen Planner
  page: /applications/gym-studio-management/zen-planner/
  slug: zen-planner
  url: https://zenplanner.com/
- anchor: teamup
  counts:
    declared: 2
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.teamup.com/integrations/
  integrations:
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
    source: https://www.teamup.com/integrations/
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
    source: https://www.teamup.com/integrations/
    tier: declared
  kind: commercial
  name: TeamUp
  page: /applications/gym-studio-management/teamup/
  slug: teamup
  url: https://www.teamup.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: gym-studio-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Gym Management Software
  store: g2
  url: https://www.g2.com/categories/gym-management
- category: Gym Management Software
  store: capterra
  url: https://www.capterra.com/gym-management-software/
- category: Health & Fitness
  store: google-play
  url: https://play.google.com/store/apps/category/HEALTH_AND_FITNESS
- category: Health & Fitness
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
name: Gym & Fitness Studio Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-2880.20
    key: preventive-care-wellness
    name: Preventive Care & Wellness
    url: /capabilities/preventive-care-wellness/
    via_parent: null
  fit: gap
  layer: domain
  why: ClassPass, Wellhub, Optum and Welld feed members and visits into the studio; no node fits
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Physical Access Control & Mobile Keys: HybridAF'
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.10
    key: AE-130.10.10
    name: Workout Logging
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  fit: exact
  layer: domain
  why: member WOD / workout tracking (SugarWOD)
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: wearable-health-data-sync
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: heart-rate effort tracking in class (Myzone)
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  fit: exact
  layer: domain
  why: nutrition plans for members (wger)
- capability:
    attribution: Turbo EA
    id: BC-4050.10
    key: loyalty-programme-design
    name: Loyalty Programme Design
    url: /capabilities/loyalty-programme-design/
    via_parent: null
  fit: exact
  layer: domain
  why: member rewards and referrals
- capability:
    attribution: API Evangelist extension
    id: AE-210.50.10
    key: AE-210.50.10
    name: Mobile Tickets & Wallet Passes
    url: /capabilities/event-ticketing/
    via_parent: Event Ticketing
  fit: exact
  layer: domain
  why: membership card in Apple Wallet
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: trainer session notes; nearest
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: membership dues and shop payments
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: accounting sync and bookkeeping
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: member and lead email campaigns
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: ad pixels, lead ads, AI marketing
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: AE-140.80
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  fit: nearest
  layer: common
  why: deal-site acquisition (Groupon); nearest
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: mailed cards to members
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: voice-telephony
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  fit: nearest
  layer: common
  why: lead call-back; nearest
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  fit: exact
  layer: common
  why: two-way member texting
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: member messaging
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: AE-150.40
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  fit: nearest
  layer: common
  why: AI front-desk chat; nearest
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: class schedule calendar sync
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: staff notifications
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
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: surveys, intake forms and waivers
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: document storage
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: social posting
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: common
  why: website widgets
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: common
  why: retail / merchandise store
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.30
    key: AE-140.10.30
    name: Mobile Commerce App Builders
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: nearest
  layer: common
  why: branded studio website and app; nearest
- capability:
    attribution: API Evangelist extension
    id: AE-140.120
    key: AE-140.120
    name: Print-on-Demand Fulfilment
    url: /capabilities/print-on-demand-fulfilment/
    via_parent: null
  fit: exact
  layer: common
  why: 'Print-on-Demand Fulfilment: Printful'
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: web analytics
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: registration forms
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: cache and task broker
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: metrics
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.50
    key: AE-130.10.50
    name: Fitness Class Aggregators & Corporate Wellness Networks
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  fit: exact
  layer: domain
  why: ClassPass, Wellhub (Fitness Class Aggregators & Corporate Wellness Networks)
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.50
    key: AE-140.30.50
    name: HSA/FSA Eligible Payments
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: Truemed (HSA/FSA Eligible Payments)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.50
      key: AE-130.10.50
      name: Fitness Class Aggregators & Corporate Wellness Networks
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mindbody
      - Wodify
      - Zen Planner
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: none
      name: ClassPass
      slug: classpass
      sources:
      - https://integrations.mindbodyonline.com/
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Class Booking
      - Fitness
      - Marketplace
      - Wellness
      tier: declared
      url: /providers/classpass/
    - agent_band: agent-ready
      agent_readiness: 34.5
      apps:
      - Wodify
      - Zen Planner
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: unknown
      name: Wellhub
      slug: wellhub
      sources:
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Company
      - Corporate Benefits
      - Health
      - Wellbeing
      tier: declared
      url: /providers/wellhub/
    - agent_band: agent-ready
      agent_readiness: 39.8
      apps:
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 69.8
      mcp:
        status: none
      name: Optum
      slug: optum
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Claims
      - Company
      - Health Insurance
      - Healthcare
      tier: declared
      url: /providers/optum/
  - capability:
      attribution: Turbo EA
      id: BC-4050.10
      key: loyalty-programme-design
      name: Loyalty Programme Design
      url: /capabilities/loyalty-programme-design/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Zen Planner
      band: developing
      in_catalog: true
      kin_score: 44.5
      mcp:
        status: unchecked
      name: Perkville
      slug: perkville
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Customer Engagement
      - Loyalty
      - Referral Program
      - Software-as-a-Service
      tier: declared
      url: /providers/perkville/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Mindbody
      band: emerging
      in_catalog: true
      kin_score: 19.7
      mcp:
        status: unchecked
      name: Referrizer
      slug: referrizer
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - Lead Management
      - Marketing Automation
      - Referral Marketing
      - Reputation Management
      tier: declared
      url: /providers/referrizer/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - wger (gym module)
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Open Food Facts
      slug: open-food-facts
      sources:
      - https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
      status: profiled
      tags:
      - Food
      - Nutrition
      - Open Data
      - Product Data
      tier: observed
      url: /providers/open-food-facts/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - GYM One
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Wallet
      slug: apple
      sources:
      - https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/composer.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.90
      key: AE-200.90
      name: Physical Access Control & Mobile Keys
      url: /capabilities/physical-access-control-mobile-keys/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Zen Planner
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: unchecked
      name: HybridAF
      slug: hybridaf
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Access Control
      - Company
      - Fitness
      - Software-as-a-Service
      tier: declared
      url: /providers/hybridaf/
  - capability:
      attribution: Turbo EA
      id: BC-2880.20
      key: preventive-care-wellness
      name: Preventive Care & Wellness
      url: /capabilities/preventive-care-wellness/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Zen Planner
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: unchecked
      name: Welld Health
      slug: welld-health
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Company
      - Health
      - Payments
      - Platform
      tier: declared
      url: /providers/welld-health/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Mindbody
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: QuickerNotes
      slug: quickernotes
      sources:
      - https://integrations.mindbodyonline.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: wearable-health-data-sync
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Wodify
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        status: unchecked
      name: Myzone
      slug: myzone
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Fitness
      - Gym Management
      - MotivationTechnology
      - Wearables
      tier: declared
      url: /providers/myzone/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.10
      key: AE-130.10.10
      name: Workout Logging
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-aware
      agent_readiness: 6.2
      apps:
      - Zen Planner
      band: emerging
      in_catalog: true
      kin_score: 13.5
      mcp:
        status: unchecked
      name: SugarWOD
      slug: sugarwod
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Fitness
      - Gym Management
      - Software-as-a-Service
      - Workouts
      tier: declared
      url: /providers/sugarwod/
  layer: domain
- capabilities:
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
      - GYM One
      - Wodify
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/index.php
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Mindbody
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Mindbody
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Mindbody
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id001
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
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
      - Wodify
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Mindbody
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Mindbody
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Mindbody
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://integrations.mindbodyonline.com/
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
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Mindbody
      - Wodify
      - Zen Planner
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: null
      agent_readiness: null
      apps:
      - Mindbody
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: REACH ai
      slug: reach-ai
      sources:
      - https://integrations.mindbodyonline.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Mindbody
      - Wodify
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify (ShopifyConnect)
      slug: shopify
      sources:
      - https://integrations.mindbodyonline.com/
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
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
      - Wodify
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
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
      - TeamUp
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.teamup.com/integrations/
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
      agent_readiness: 44.1
      apps:
      - Wodify
      - Zen Planner
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Mindbody
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Mindbody
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - wger (gym module)
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        source: https://github.com/prometheus/prometheus-mcp
        status: verified
      name: Prometheus
      slug: prometheus-io
      sources:
      - https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
      status: profiled
      tags:
      - Metrics
      - Monitoring
      - Observability
      - Prometheus
      tier: observed
      url: /providers/prometheus-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Wodify
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Wodify
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: SurveyMonkey
      slug: surveymonkey
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: declared
      url: /providers/surveymonkey/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mindbody
      band: emerging
      in_catalog: true
      kin_score: 20.1
      mcp:
        status: unchecked
      name: WaiverKing
      slug: waiverking
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - Digital Forms
      - Fitness
      - Software-as-a-Service
      - Wellness
      tier: declared
      url: /providers/waiverking/
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
      - GYM One
      - Wodify
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - GYM One
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Zen Planner
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
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
      - TeamUp
      - Wodify
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.teamup.com/integrations/
      - https://www.wodify.com/integrations
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
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
      - wger (gym module)
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - wger (gym module)
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/wger-project/docker/master/config/prod.env
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: declared
      url: /providers/cloudflare-turnstile/
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Wodify
      band: thin
      in_catalog: true
      kin_score: 38.3
      mcp:
        status: unchecked
      name: AMcards
      slug: amcards
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Appreciation-Marketing
      - Cards
      - Company
      - Customer Engagement
      tier: declared
      url: /providers/amcards/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Wodify
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: unchecked
      name: Thankster
      slug: thankster
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Automation
      - B2B
      - Direct Mail
      - Handwritten Cards
      tier: declared
      url: /providers/thankster/
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
      - Wodify
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mindbody
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: unknown
      name: Bench
      slug: bench
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Small Business
      - Software-as-a-Service
      tier: declared
      url: /providers/bench/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Wodify
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Mindbody
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
        status: documented
      name: Tealium
      slug: tealium
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags:
      - AudienceStream
      - CDP
      - Customer Data Platform
      - Tag Management
      tier: observed
      url: /providers/tealium/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.50
      key: AE-140.30.50
      name: HSA/FSA Eligible Payments
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-native
      agent_readiness: 55.0
      apps:
      - Wodify
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: unchecked
      name: Truemed
      slug: truemed
      sources:
      - https://www.wodify.com/integrations
      status: profiled
      tags:
      - Company
      - Fintech
      - HSA
      - Health
      tier: declared
      url: /providers/truemed/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Mindbody
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Healthdesk
      slug: healthdesk
      sources:
      - https://integrations.mindbodyonline.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - wger (gym module)
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.80
      key: AE-140.80
      name: Marketplaces
      url: /capabilities/marketplaces/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 9.4
      apps:
      - Mindbody
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Groupon
      slug: groupon
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - E-Commerce
      - Fortune 1000
      - Local Commerce
      - Marketplace
      tier: declared
      url: /providers/groupon/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Mindbody
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.30
      key: AE-140.10.30
      name: Mobile Commerce App Builders
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Mindbody
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Studio Stack
      slug: studio-stack
      sources:
      - https://integrations.mindbodyonline.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.120
      key: AE-140.120
      name: Print-on-Demand Fulfilment
      url: /capabilities/print-on-demand-fulfilment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - Zen Planner
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Printful
      slug: printful
      sources:
      - https://zenplanner.com/integrations/
      status: profiled
      tags:
      - Dropshipping
      - E-Commerce
      - Fulfillment
      - Print on Demand
      tier: declared
      url: /providers/printful/
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
      - Mindbody
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
      id: AE-150.20
      key: sms-messaging-apps
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Mindbody
      band: strong
      in_catalog: true
      kin_score: 58.1
      mcp:
        status: none
      name: Weave
      slug: weave
      sources:
      - https://integrations.mindbodyonline.com/
      status: profiled
      tags:
      - Communications
      - Company
      - Messaging
      - Payments
      tier: declared
      url: /providers/weave/
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
      - Mindbody
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: voice-telephony
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Wodify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Callingly
      slug: callingly
      sources:
      - https://www.wodify.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Zen Planner
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://zenplanner.com/integrations/
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
  coverage_pct: 91.2
  declared_only: 42
  distinct_providers: 57
  in_catalog: 52
  mcp:
    documented: 4
    none: 17
    unchecked: 15
    verified: 19
  mcp_verified: 19
  mean_kin_score: 53.0
  observed: 15
  queued: 5
  reference_apps: 6
title: 'Gym & Fitness Studio Management: application blueprint'
---
