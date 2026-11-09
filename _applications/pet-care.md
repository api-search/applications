---
access: understanding
agent_layer:
- app: oh-my-petcare
  finding: ships the app itself as agent skills (oh-my-catcare / oh-my-dogcare) for Claude Code, Codex, Cursor; local-first data in ~/.petcare/
  source: https://github.com/idonafraid-create/oh-my-petcare
  tier: declared
- app: PawSome AI
  finding: Gemini-backed pet-care chatbot with Chroma RAG; no MCP server
  source: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
  tier: observed
apps:
- anchor: rover
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Alooma
    provider: alooma
    says: ships the Alooma SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    name: Facebook Analytics / Login / Share
    provider: facebook
    says: ships the Facebook Analytics / Login / Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
    name: Splunk MINT
    provider: splunk
    says: ships the Splunk MINT SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
    tier: observed
  kind: commercial
  name: Rover
  page: /applications/pet-care/rover/
  slug: rover
  url: https://www.rover.com/
- anchor: chewy
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
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
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
    tier: observed
  kind: commercial
  name: Chewy
  page: /applications/pet-care/chewy/
  slug: chewy
  url: https://www.chewy.com/
- anchor: petlibro
  counts:
    declared: 4
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
  - route: integrations page
    url: https://homey.app/en-us/app/com.petlibro.petlibro/
  - route: source code
    url: https://petlibro.com/pages/app
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-140.90.20
      key: AE-140.90.20
      name: Order Tracking
      url: /capabilities/post-purchase/
      via_parent: Post-Purchase
    credit: null
    layer: common
    name: AfterShip
    provider: aftership
    says: ships the AfterShip SDK or integration code
    source: https://petlibro.com/pages/app
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
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
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Judge.me
    provider: judge-me
    says: ships the Judge.me SDK or integration code
    source: https://petlibro.com/pages/app
    tier: observed
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
    says: ships the Shopify SDK or integration code
    source: https://petlibro.com/pages/app
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://petlibro.com/pages/app
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://petlibro.com/pages/app
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://petlibro.com/pages/app
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Venmo
    provider: venmo
    says: lists Venmo as an integration
    source: https://petlibro.com/pages/app
    tier: declared
  kind: commercial
  name: PETLIBRO
  page: /applications/pet-care/petlibro/
  slug: petlibro
  url: https://petlibro.com/
- anchor: tractive
  counts:
    declared: 5
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.tractive.android.gps/latest/
  - route: documentation
    url: https://tractive.com/blog/en/tech/do-pet-trackers-integrate-with-smart-home-devices
  - route: source code
    url: https://tractive.com/en-us
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
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tractive.android.gps/latest/
    tier: observed
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
    says: ships the Google Tag Manager SDK or integration code
    source: https://tractive.com/en-us
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Affirm
    provider: affirm
    says: lists Affirm as an integration
    source: https://tractive.com/en-us
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://tractive.com/en-us
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://tractive.com/en-us
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    credit: null
    layer: domain
    name: Homey (Athom / LG)
    provider: homey
    says: lists Homey (Athom / LG) as an integration
    source: https://tractive.com/blog/en/tech/do-pet-trackers-integrate-with-smart-home-devices
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://tractive.com/en-us
    tier: declared
  kind: commercial
  name: Tractive
  page: /applications/pet-care/tractive/
  slug: tractive
  url: https://tractive.com/
- anchor: fi-smart-collar
  counts:
    declared: 2
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
  - route: documentation
    url: https://blog.fitracking.com/the-first-ai-smart-collar-for-your-dog/
  - route: documentation
    url: https://support.strava.com/hc/en-us/articles/24330606303501-The-Fi-Collar-and-Strava
  - route: source code
    url: https://www.tryfi.com/
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
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Apple Watch
    provider: apple
    says: lists Apple Watch as an integration
    source: https://blog.fitracking.com/the-first-ai-smart-collar-for-your-dog/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.20
      key: AE-130.10.20
      name: Activity & Step Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: Strava
    provider: strava
    says: lists Strava as an integration
    source: https://support.strava.com/hc/en-us/articles/24330606303501-The-Fi-Collar-and-Strava
    tier: declared
  kind: commercial
  name: Fi Smart Collar
  page: /applications/pet-care/fi-smart-collar/
  slug: fi-smart-collar
  url: https://tryfi.com/
- anchor: petdesk
  counts:
    declared: 10
    observed: 0
  evidence:
  - route: integrations page
    url: https://petdesk.com/compatible-pims
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: Covetrus (Pulse, AVImark, ImproMed)
    provider: covetrus
    says: lists Covetrus (Pulse, AVImark, ImproMed) as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: DaySmart Vet
    provider: daysmart-vet
    says: lists DaySmart Vet as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: ezyVet
    provider: ezyvet
    says: lists ezyVet as an integration
    source: https://petdesk.com/compatible-pims
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
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: Hippo Manager
    provider: hippo-manager
    says: lists Hippo Manager as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: IDEXX (Cornerstone, Neo)
    provider: idexx
    says: lists IDEXX (Cornerstone, Neo) as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: Provet Cloud
    provider: provet-cloud
    says: lists Provet Cloud as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: Rhapsody (veterinary PIMS)
    provider: rhapsody-vet
    says: lists Rhapsody (veterinary PIMS) as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: Shepherd Veterinary Software
    provider: shepherd-vet
    says: lists Shepherd Veterinary Software as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    credit: null
    layer: domain
    name: Vetspire
    provider: vetspire
    says: lists Vetspire as an integration
    source: https://petdesk.com/compatible-pims
    tier: declared
  kind: commercial
  name: PetDesk
  page: /applications/pet-care/petdesk/
  slug: petdesk
  url: https://petdesk.com/
- anchor: pawsome-ai
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Chroma
    provider: chroma
    says: ships the Chroma SDK or integration code
    source: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
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
    source: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
    tier: observed
  kind: self-hosted
  name: PawSome AI
  page: /applications/pet-care/pawsome-ai/
  slug: pawsome-ai
  url: https://github.com/MohammedMusharraf11/PawSome-AI
- anchor: oh-my-petcare
  counts:
    declared: 2
    observed: 0
  evidence:
  - route: documentation
    url: https://github.com/idonafraid-create/oh-my-petcare
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: lists Telegram as an integration
    source: https://github.com/idonafraid-create/oh-my-petcare
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
    name: WeChat
    provider: wechat
    says: lists WeChat as an integration
    source: https://github.com/idonafraid-create/oh-my-petcare
    tier: declared
  kind: open-source-saas
  name: oh-my-petcare
  page: /applications/pet-care/oh-my-petcare/
  slug: oh-my-petcare
  url: https://github.com/idonafraid-create/oh-my-petcare
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: pet-care
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Lifestyle
  store: google-play
  url: https://play.google.com/store/apps/category/LIFESTYLE
name: Pet Care
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-130.80
    key: AE-130.80
    name: Pet Health & Care
    url: /capabilities/pet-health-care/
    via_parent: null
  fit: nearest
  layer: domain
  why: vet records, PIMS sync, reminders, AI pet health; PIMS integrations land here as nearest
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: GPS trackers and feeders reach home automation hubs (Tractive x Homey)
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.20
    key: AE-130.10.20
    name: Activity & Step Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  fit: exact
  layer: domain
  why: dog activity collars export walks (Fi x Strava)
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: nearest
  layer: domain
  why: smartwatch companion apps for pet wearables
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: common
  why: device makers sell hardware and refills direct
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: common
  why: product reviews on storefront
- capability:
    attribution: API Evangelist extension
    id: AE-140.90.20
    key: AE-140.90.20
    name: Order Tracking
    url: /capabilities/post-purchase/
    via_parent: Post-Purchase
  fit: exact
  layer: common
  why: hardware order tracking
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: checkout
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: financing for trackers and subscriptions
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: Apple Pay, Google Pay, Venmo at checkout
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: marketing tags on storefronts
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: vet appointment calendar sync
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: care reminders pushed to messaging apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: pet-care chatbots, prescription and document analysis
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: agent
  why: RAG over pet-care documents
- capability:
    attribution: API Evangelist extension
    id: AE-100.10.20
    key: AE-100.10.20
    name: Agent Skills Packaging
    url: /capabilities/agent-tool-exposure/
    via_parent: Agent Tool Exposure
  fit: exact
  layer: agent
  why: pet-care records shipped as agent skills (oh-my-petcare)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: nearest
  layer: common
  why: customer data SDK in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution SDKs in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in SDK in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad SDK in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting in the Android apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.80.10
      key: AE-130.80.10
      name: Veterinary Practice Management Systems
      url: /capabilities/pet-health-care/
      via_parent: Pet Health & Care
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - PetDesk
      band: developing
      in_catalog: true
      kin_score: 39.8
      mcp:
        status: unknown
      name: Shepherd Veterinary Software
      slug: shepherd-vet
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Cloud
      - Practice Management
      - Software
      - Veterinary
      tier: declared
      url: /providers/shepherd-vet/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - PetDesk
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        status: unknown
      name: ezyVet
      slug: ezyvet
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Healthcare
      - PIMS
      - Practice Management
      - Veterinary
      tier: declared
      url: /providers/ezyvet/
    - agent_band: agent-ready
      agent_readiness: 32.9
      apps:
      - PetDesk
      band: thin
      in_catalog: true
      kin_score: 27.9
      mcp:
        source: https://www.provet.com/mcp-skills-library
        status: documented
      name: Provet Cloud
      slug: provet-cloud
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Healthcare
      - PIMS
      - Practice Management
      - Veterinary
      tier: declared
      url: /providers/provet-cloud/
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - PetDesk
      band: emerging
      in_catalog: true
      kin_score: 22.2
      mcp:
        status: none
      name: Vetspire
      slug: vetspire
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Healthcare
      - PIMS
      - Practice Management
      - Veterinary
      tier: declared
      url: /providers/vetspire/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - PetDesk
      band: emerging
      in_catalog: true
      kin_score: 19.9
      mcp:
        status: none
      name: DaySmart Vet
      slug: daysmart-vet
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Cloud
      - Company
      - Software
      - Veterinary
      tier: declared
      url: /providers/daysmart-vet/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - PetDesk
      band: minimal
      in_catalog: true
      kin_score: 9.6
      mcp:
        status: none
      name: Covetrus (Pulse, AVImark, ImproMed)
      slug: covetrus
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Company
      - Pharmacy
      - Software
      - Veterinary
      tier: declared
      url: /providers/covetrus/
    - agent_band: null
      agent_readiness: null
      apps:
      - PetDesk
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Hippo Manager
      slug: hippo-manager
      sources:
      - https://petdesk.com/compatible-pims
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - PetDesk
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: IDEXX (Cornerstone, Neo)
      slug: idexx
      sources:
      - https://petdesk.com/compatible-pims
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - PetDesk
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Rhapsody (veterinary PIMS)
      slug: rhapsody-vet
      sources:
      - https://petdesk.com/compatible-pims
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.20
      key: AE-130.10.20
      name: Activity & Step Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Fi Smart Collar
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp:
        status: none
      name: Strava
      slug: strava
      sources:
      - https://support.strava.com/hc/en-us/articles/24330606303501-The-Fi-Collar-and-Strava
      status: profiled
      tags:
      - Cycling
      - Fitness
      - Fitness Tracking
      - Running
      tier: declared
      url: /providers/strava/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Tractive
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Homey (Athom / LG)
      slug: homey
      sources:
      - https://tractive.com/blog/en/tech/do-pet-trackers-integrate-with-smart-home-devices
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Fi Smart Collar
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple Watch
      slug: apple
      sources:
      - https://blog.fitracking.com/the-first-ai-smart-collar-for-your-dog/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
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
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Chewy
      - Fi Smart Collar
      - PETLIBRO
      - Rover
      - Tractive
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics / Crashlytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - PETLIBRO
      - Rover
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Rover
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - PETLIBRO
      - Tractive
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://petlibro.com/pages/app
      - https://tractive.com/en-us
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - PETLIBRO
      - Tractive
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://petlibro.com/pages/app
      - https://tractive.com/en-us
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - PETLIBRO
      band: thin
      in_catalog: true
      kin_score: 29.9
      mcp:
        status: none
      name: Venmo
      slug: venmo
      sources:
      - https://petlibro.com/pages/app
      status: profiled
      tags:
      - Company
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/venmo/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Chewy
      - Fi Smart Collar
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: null
      agent_readiness: null
      apps:
      - Rover
      band: null
      in_catalog: true
      kin_score: null
      mcp:
        status: unknown
      name: Alooma
      slug: alooma
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - Company
      - Data Integration
      - Data Pipeline
      - ETL
      tier: observed
      url: /providers/alooma/
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
      - Chewy
      - PETLIBRO
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Rover
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
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
      - Rover
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
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
      - Chewy
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.chewy.android/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - Rover
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        status: none
      name: Splunk MINT
      slug: splunk
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: observed
      url: /providers/splunk/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - PETLIBRO
      - Tractive
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://petlibro.com/pages/app
      - https://tractive.com/en-us
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
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
      - Rover
      - Tractive
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      - https://tractive.com/en-us
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - oh-my-petcare
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/idonafraid-create/oh-my-petcare
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: declared
      url: /providers/telegram/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - oh-my-petcare
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        status: none
      name: WeChat
      slug: wechat
      sources:
      - https://github.com/idonafraid-create/oh-my-petcare
      status: profiled
      tags:
      - Messaging
      - Mini Programs
      - Payments
      - Social
      tier: declared
      url: /providers/wechat/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Tractive
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        status: none
      name: Affirm
      slug: affirm
      sources:
      - https://tractive.com/en-us
      status: profiled
      tags:
      - Buy Now Pay Later
      - Fintech
      - Lending
      - Payments
      tier: declared
      url: /providers/affirm/
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
      - PETLIBRO
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://petlibro.com/pages/app
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: observed
      url: /providers/shopify/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Rover
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
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
      - PetDesk
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://petdesk.com/compatible-pims
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.90.20
      key: AE-140.90.20
      name: Order Tracking
      url: /capabilities/post-purchase/
      via_parent: Post-Purchase
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - PETLIBRO
      band: exemplar
      in_catalog: true
      kin_score: 84.1
      mcp:
        source: https://github.com/AfterShip/tracking-and-returns-mcp
        status: verified
      name: AfterShip
      slug: aftership
      sources:
      - https://petlibro.com/pages/app
      status: profiled
      tags:
      - E-Commerce
      - Post-Purchase
      - Shipping
      - Tracking
      tier: observed
      url: /providers/aftership/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - PETLIBRO
      band: thin
      in_catalog: true
      kin_score: 27.2
      mcp:
        status: none
      name: Judge.me
      slug: judge-me
      sources:
      - https://petlibro.com/pages/app
      status: profiled
      tags:
      - E-Commerce
      - Ratings
      - Reviews
      - Shopify
      tier: observed
      url: /providers/judge-me/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Rover
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook Analytics / Login / Share
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rover.android/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
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
      agent_readiness: 31.3
      apps:
      - PawSome AI
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - PawSome AI
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        source: https://github.com/chroma-core/chroma-mcp
        status: verified
      name: Chroma
      slug: chroma
      sources:
      - https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
      status: profiled
      tags:
      - AI-native
      - Apache 2.0
      - Artificial Intelligence
      - Cloud
      tier: observed
      url: /providers/chroma/
  layer: agent
summary:
  coverage_pct: 89.5
  declared_only: 20
  distinct_providers: 38
  in_catalog: 34
  mcp:
    documented: 1
    none: 19
    unchecked: 4
    verified: 11
  mcp_verified: 11
  mean_kin_score: 50.7
  observed: 18
  queued: 4
  reference_apps: 8
title: 'Pet Care: application blueprint'
---
