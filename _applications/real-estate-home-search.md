---
access: understanding
agent_layer: []
apps:
- anchor: flathunter
  counts:
    declared: 1
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/flathunters/flathunter/main/Pipfile
  - route: source code
    url: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
  - route: source code
    url: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
  - route: source code
    url: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
  - route: source code
    url: https://raw.githubusercontent.com/flathunters/flathunter/main/config.yaml.dist
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Firestore
    provider: google-cloud-firestore
    says: ships the Google Cloud Firestore SDK or integration code
    source: https://raw.githubusercontent.com/flathunters/flathunter/main/Pipfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: idealista
    provider: idealista
    says: ships the idealista SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: common
    name: ImageTyperz
    provider: imagetyperz
    says: ships the ImageTyperz SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: Immobiliare.it
    provider: immobiliare
    says: ships the Immobiliare.it SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: ImmobilienScout24
    provider: immobilienscout24
    says: ships the ImmobilienScout24 SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: Immowelt
    provider: immowelt
    says: ships the Immowelt SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kleinanzeigen
    provider: kleinanzeigen
    says: ships the Kleinanzeigen SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: Subito.it
    provider: subito
    says: ships the Subito.it SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram Bot API
    provider: telegram
    says: ships the Telegram Bot API SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: VRM Immo
    provider: vrm-immo
    says: ships the VRM Immo SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: WG-Gesucht
    provider: wg-gesucht
    says: ships the WG-Gesucht SDK or integration code
    source: https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30
      key: AE-120.30
      name: Routing & Navigation
      url: /capabilities/routing-navigation/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps Distance Matrix API
    provider: google-maps
    says: lists Google Maps Distance Matrix API as an integration
    source: https://raw.githubusercontent.com/flathunters/flathunter/main/config.yaml.dist
    tier: declared
  kind: self-hosted
  name: Flathunter
  page: /applications/real-estate-home-search/flathunter/
  slug: flathunter
  url: https://github.com/flathunters/flathunter
- anchor: homeharvest
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/pyproject.toml
  - route: documentation
    url: https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: Realtor.com
    provider: realtor-com
    says: ships the Realtor.com SDK or integration code
    source: https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/README.md
    tier: observed
  kind: open-source-saas
  name: HomeHarvest
  page: /applications/real-estate-home-search/homeharvest/
  slug: homeharvest
  url: https://github.com/Bunsly/HomeHarvest
- anchor: redfin
  counts:
    declared: 3
    observed: 10
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
  - route: documentation
    url: https://www.redfin.com/about/data-quality-on-redfin
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    name: Facebook Share
    provider: facebook
    says: ships the Facebook Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fizber.com
    provider: fizber
    says: lists Fizber.com as an integration
    source: https://www.redfin.com/about/data-quality-on-redfin
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    credit: null
    layer: domain
    name: FSBO.com
    provider: fsbo-com
    says: lists FSBO.com as an integration
    source: https://www.redfin.com/about/data-quality-on-redfin
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4980.10
      key: real-estate-debt-origination
      name: Real Estate Debt Origination
      url: /capabilities/real-estate-debt-origination/
      via_parent: null
    credit: null
    layer: domain
    name: Rocket Mortgage (Rocket Companies)
    provider: rocket-companies
    says: lists Rocket Mortgage (Rocket Companies) as an integration
    source: https://www.redfin.com/about/data-quality-on-redfin
    tier: declared
  kind: commercial
  name: Redfin
  page: /applications/real-estate-home-search/redfin/
  slug: redfin
  url: https://www.redfin.com/
- anchor: real-geeks
  counts:
    declared: 10
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.realgeeks.com/integrations/
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
    name: Apple Contacts
    provider: apple
    says: lists Apple Contacts as an integration
    source: https://www.realgeeks.com/integrations/
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
    name: BoomTown
    provider: boomtown
    says: lists BoomTown as an integration
    source: https://www.realgeeks.com/integrations/
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
    source: https://www.realgeeks.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    credit: null
    layer: common
    name: Dubb
    provider: dubb
    says: lists Dubb as an integration
    source: https://www.realgeeks.com/integrations/
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
    name: Google Contacts
    provider: google-people
    says: lists Google Contacts as an integration
    source: https://www.realgeeks.com/integrations/
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
    source: https://www.realgeeks.com/integrations/
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
    name: kvCORE (BoldTrail)
    provider: kvcore
    says: lists kvCORE (BoldTrail) as an integration
    source: https://www.realgeeks.com/integrations/
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
    name: KW Command
    provider: keller-williams
    says: lists KW Command as an integration
    source: https://www.realgeeks.com/integrations/
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
    source: https://www.realgeeks.com/integrations/
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
    name: Thanks.io
    provider: thanks-io
    says: lists Thanks.io as an integration
    source: https://www.realgeeks.com/integrations/
    tier: declared
  kind: commercial
  name: Real Geeks
  page: /applications/real-estate-home-search/real-geeks/
  slug: real-geeks
  url: https://www.realgeeks.com/
- anchor: zillow
  counts:
    declared: 0
    observed: 14
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Airship (Urbanairship)
    provider: airship
    says: ships the Airship (Urbanairship) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Apptentive (Alchemer Mobile)
    provider: apptentive
    says: ships the Apptentive (Alchemer Mobile) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    name: Facebook Share
    provider: facebook
    says: ships the Facebook Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: AE-120
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Radar
    provider: radar-io
    says: ships the Radar SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Split (Harness FME)
    provider: split
    says: ships the Split (Harness FME) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
    tier: observed
  kind: commercial
  name: Zillow
  page: /applications/real-estate-home-search/zillow/
  slug: zillow
  url: https://www.zillow.com/
- anchor: rightmove
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
  - route: documentation
    url: https://www.rightmove.co.uk/adf.html
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    name: Instabug (Luciq)
    provider: instabug
    says: ships the Instabug (Luciq) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
    tier: observed
  kind: commercial
  name: Rightmove
  page: /applications/real-estate-home-search/rightmove/
  slug: rightmove
  url: https://www.rightmove.co.uk/
- anchor: realtorcom
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon Advertisement
    provider: amazon
    says: ships the Amazon Advertisement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    name: Facebook Share
    provider: facebook
    says: ships the Facebook Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
    tier: observed
  kind: commercial
  name: Realtor.com
  page: /applications/real-estate-home-search/realtor-com/
  slug: realtor-com
  url: https://www.realtor.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: real-estate-home-search
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: House & Home
  store: google-play
  url: https://play.google.com/store/apps/category/HOUSE_AND_HOME
- category: Real Estate
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
name: Real Estate & Home Search
needs:
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  fit: exact
  layer: domain
  why: listing portals, MLS and FSBO feeds are the inventory every home-search app searches
- capability:
    attribution: Turbo EA
    id: BC-4980.10
    key: real-estate-debt-origination
    name: Real Estate Debt Origination
    url: /capabilities/real-estate-debt-origination/
    via_parent: null
  fit: exact
  layer: domain
  why: mortgage pre-approval alongside search
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: agent IDX sites sync leads into real-estate CRMs
- capability:
    attribution: API Evangelist extension
    id: AE-120.30
    key: AE-120.30
    name: Routing & Navigation
    url: /capabilities/routing-navigation/
    via_parent: null
  fit: exact
  layer: common
  why: commute time from a listing to work/school
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: new-listing alerts
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: new-listing alerts to team chat
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: agent drip campaigns to searchers
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: contact sync for agents
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: lead export
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: postcards to leads
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: seen-listing state
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: common
  why: scrapers must solve portal CAPTCHAs; solver side has no node
- capability:
    attribution: API Evangelist extension
    id: AE-150.60.10
    key: AE-150.60.10
    name: Async Video Messaging
    url: /capabilities/video-calling/
    via_parent: Video Calling
  fit: exact
  layer: common
  why: async video messaging has no node
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution and deep linking SDKs in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: nearest
  layer: common
  why: usage and audience analytics SDKs in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in SDK in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: common
  why: social sharing and marketing SDKs in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and performance reporting SDKs in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag management SDK in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app feedback SDK in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app advertising SDKs in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: AE-120
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: exact
  layer: common
  why: location SDK in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature flag SDK in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: push notification SDK in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: ad viewability measurement SDK in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: experimentation SDK in the shipped Android app
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4960.30
      key: listing-data-mls-management
      name: Listing Data & MLS Management
      url: /capabilities/listing-data-mls-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Flathunter
      band: strong
      in_catalog: true
      kin_score: 57.8
      mcp:
        status: none
      name: ImmobilienScout24
      slug: immobilienscout24
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Company
      - Germany
      - Marketplace
      - Real Estate
      tier: observed
      url: /providers/immobilienscout24/
    - agent_band: agent-aware
      agent_readiness: 20.4
      apps:
      - Flathunter
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Kleinanzeigen
      slug: kleinanzeigen
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Classifieds
      - FreeAds
      - Germany
      - Marketplace
      tier: observed
      url: /providers/kleinanzeigen/
    - agent_band: agent-aware
      agent_readiness: 15.7
      apps:
      - Flathunter
      band: emerging
      in_catalog: true
      kin_score: 23.9
      mcp:
        status: unknown
      name: Immowelt
      slug: immowelt
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Austria
      - Germany
      - Marketplace
      - Real Estate
      tier: observed
      url: /providers/immowelt/
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - Flathunter
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: none
      name: Immobiliare.it
      slug: immobiliare
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Company
      - Italy
      - Property Listings
      - Real Estate
      tier: observed
      url: /providers/immobiliare/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Flathunter
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: unknown
      name: Subito.it
      slug: subito
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Classifieds
      - E-Commerce
      - Italy
      - Marketplace
      tier: observed
      url: /providers/subito/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Flathunter
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: VRM Immo
      slug: vrm-immo
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Company
      - Germany
      - Marketplace
      - Real Estate
      tier: observed
      url: /providers/vrm-immo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - HomeHarvest
      band: minimal
      in_catalog: true
      kin_score: 3.0
      mcp:
        status: unknown
      name: Realtor.com
      slug: realtor-com
      sources:
      - https://raw.githubusercontent.com/Bunsly/HomeHarvest/master/README.md
      status: profiled
      tags:
      - Housing
      - MLS
      - Property Listings
      - Real Estate
      tier: observed
      url: /providers/realtor-com/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Flathunter
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp:
        status: unknown
      name: WG-Gesucht
      slug: wg-gesucht
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: profiled
      tags:
      - Germany
      - Housing
      - Marketplace
      - Rentals
      tier: observed
      url: /providers/wg-gesucht/
    - agent_band: null
      agent_readiness: null
      apps:
      - Flathunter
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: idealista
      slug: idealista
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/crawler
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: human-only
      agent_readiness: 4.4
      apps:
      - Redfin
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        status: unknown
      name: FSBO.com
      slug: fsbo-com
      sources:
      - https://www.redfin.com/about/data-quality-on-redfin
      status: profiled
      tags:
      - Home Selling
      - Marketplace
      - Real Estate
      - Software-as-a-Service
      tier: declared
      url: /providers/fsbo-com/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Redfin
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: unknown
      name: Fizber.com
      slug: fizber
      sources:
      - https://www.redfin.com/about/data-quality-on-redfin
      status: profiled
      tags:
      - FSBO
      - Free Listings
      - Marketplace
      - Real Estate
      tier: declared
      url: /providers/fizber/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Real Geeks
      band: thin
      in_catalog: true
      kin_score: 38.9
      mcp:
        status: unknown
      name: kvCORE (BoldTrail)
      slug: kvcore
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - CRM
      - Company
      - Real Estate
      - Software-as-a-Service
      tier: declared
      url: /providers/kvcore/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Real Geeks
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: unknown
      name: KW Command
      slug: keller-williams
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Brokerage
      - Real Estate
      - Residential Real Estate
      - United States
      tier: declared
      url: /providers/keller-williams/
    - agent_band: null
      agent_readiness: null
      apps:
      - Real Geeks
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: BoomTown
      slug: boomtown
      sources:
      - https://www.realgeeks.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4980.10
      key: real-estate-debt-origination
      name: Real Estate Debt Origination
      url: /capabilities/real-estate-debt-origination/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Redfin
      band: minimal
      in_catalog: true
      kin_score: 1.7
      mcp:
        status: unknown
      name: Rocket Mortgage (Rocket Companies)
      slug: rocket-companies
      sources:
      - https://www.redfin.com/about/data-quality-on-redfin
      status: profiled
      tags:
      - Financial Services
      - Mortgage
      - Personal Finance
      - Real Estate
      tier: declared
      url: /providers/rocket-companies/
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
      agent_readiness: 39.9
      apps:
      - Realtor.com
      - Redfin
      - Rightmove
      - Zillow
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - Realtor.com
      - Redfin
      - Rightmove
      - Zillow
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        status: none
      name: Comscore
      slug: comscore
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
      status: profiled
      tags:
      - Audience Analytics
      - Cloud Saas
      - Company
      - Media Measurement
      tier: observed
      url: /providers/comscore/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Redfin
      - Rightmove
      - Zillow
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Realtor.com
      - Redfin
      - Zillow
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Realtor.com
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
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
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Realtor.com
      - Redfin
      - Rightmove
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase (Crashlytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Zillow
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Realtor.com
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Rightmove
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        source: https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features.md
        status: documented
      name: Instabug (Luciq)
      slug: instabug
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
      status: profiled
      tags:
      - AI Agents
      - APM
      - Application Performance Monitoring
      - Bug Reporting
      tier: observed
      url: /providers/instabug/
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
      - Realtor.com
      - Redfin
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Redfin
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Zillow
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
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
      - Realtor.com
      - Redfin
      - Zillow
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook Share
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Realtor.com
      - Zillow
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Realtor.com
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Advertisement
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
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
      - Realtor.com
      - Redfin
      - Zillow
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook Login
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Redfin
      - Rightmove
      - Zillow
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Real Geeks
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.realgeeks.com/integrations/
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
      - Real Geeks
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Real Geeks
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Contacts
      slug: google-people
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Address Book
      - Contacts
      - Google
      - People
      tier: declared
      url: /providers/google-people/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Real Geeks
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Contacts
      slug: apple
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Flathunter
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Flathunter
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Real Geeks
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: unknown
      name: Dubb
      slug: dubb
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/dubb/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - Zillow
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        status: none
      name: Apptentive (Alchemer Mobile)
      slug: apptentive
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Company
      - Customer Feedback
      - Enterprise
      - Mobile
      tier: observed
      url: /providers/apptentive/
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.0
      apps:
      - Real Geeks
      band: strong
      in_catalog: true
      kin_score: 65.6
      mcp:
        source: https://docs.thanks.io/thanks-io-mcp-server
        status: verified
      name: Thanks.io
      slug: thanks-io
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Company
      - Direct Mail
      tier: declared
      url: /providers/thanks-io/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Zillow
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: none
      name: Split (Harness FME)
      slug: split
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: AE-120
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Zillow
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://mcp.radar.com/mcp
        status: verified
      name: Radar
      slug: radar-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Geocoding
      - Geofencing
      - Location
      - Maps
      tier: observed
      url: /providers/radar-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Flathunter
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://firebase.google.com/docs/cli/mcp-server
        status: verified
      name: Google Cloud Firestore
      slug: google-cloud-firestore
      sources:
      - https://raw.githubusercontent.com/flathunters/flathunter/main/Pipfile
      status: profiled
      tags:
      - Database
      - Documents
      - Google Cloud
      - NoSQL
      tier: observed
      url: /providers/google-cloud-firestore/
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
      - Realtor.com
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Realtor.com
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.move.realtor/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Zillow
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Airship (Urbanairship)
      slug: airship
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
      status: profiled
      tags:
      - Email
      - Mobile
      - Notification
      - Push
      tier: observed
      url: /providers/airship/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30
      key: AE-120.30
      name: Routing & Navigation
      url: /capabilities/routing-navigation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Flathunter
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Distance Matrix API
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/flathunters/flathunter/main/config.yaml.dist
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
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Real Geeks
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://www.realgeeks.com/integrations/
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Flathunter
      band: emerging
      in_catalog: true
      kin_score: 13.6
      mcp:
        status: unknown
      name: ImageTyperz
      slug: imagetyperz
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/captcha
      status: profiled
      tags:
      - Automation
      - CAPTCHA
      - Company
      - Services
      tier: observed
      url: /providers/imagetyperz/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Flathunter
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram Bot API
      slug: telegram
      sources:
      - https://api.github.com/repos/flathunters/flathunter/contents/flathunter/notifiers
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  layer: common
summary:
  coverage_pct: 95.8
  declared_only: 14
  distinct_providers: 48
  in_catalog: 46
  mcp:
    documented: 2
    none: 17
    unchecked: 2
    verified: 15
  mcp_verified: 15
  mean_kin_score: 44.0
  observed: 34
  queued: 2
  reference_apps: 7
title: 'Real Estate & Home Search: application blueprint'
---
