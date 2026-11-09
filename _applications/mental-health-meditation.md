---
access: understanding
agent_layer: []
apps:
- anchor: medito
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Apple HealthKit
    provider: apple
    says: ships the Apple HealthKit SDK or integration code
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
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
    name: Facebook App Events
    provider: facebook
    says: ships the Facebook App Events SDK or integration code
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
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
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
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
    name: Google Health Connect
    provider: health-connect
    says: ships the Google Health Connect SDK or integration code
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
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
    source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
    tier: observed
  kind: self-hosted
  name: Medito
  page: /applications/mental-health-meditation/medito/
  slug: medito
  url: https://github.com/meditohq/medito-app
- anchor: heylinda
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/heylinda/heylinda-app/blob/main/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://github.com/heylinda/heylinda-app/blob/main/package.json
    tier: observed
  kind: self-hosted
  name: Heylinda
  page: /applications/mental-health-meditation/heylinda/
  slug: heylinda
  url: https://github.com/heylinda/heylinda-app
- anchor: pixy-mood-tracker
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Apple HealthKit
    provider: apple
    says: ships the Apple HealthKit SDK or integration code
    source: https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
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
    source: https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
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
    name: Superwall
    provider: superwall
    says: ships the Superwall SDK or integration code
    source: https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
    tier: observed
  kind: self-hosted
  name: Pixy Mood Tracker
  page: /applications/mental-health-meditation/pixy-mood-tracker/
  slug: pixy-mood-tracker
  url: https://github.com/mrzmyr/pixy-mood-tracker-app
- anchor: baseline
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
  - route: dependency manifest
    url: https://github.com/nkalupahana/baseline/blob/main/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Authentication
    provider: firebase
    says: ships the Firebase Authentication SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/package.json
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/package.json
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
    name: Gmail API
    provider: google-gmail
    says: ships the Gmail API SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Google Cloud Pub/Sub
    provider: google-cloud-pubsub
    says: ships the Google Cloud Pub/Sub SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
    tier: observed
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
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
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
    source: https://github.com/nkalupahana/baseline/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Spotify embeds
    provider: spotify
    says: ships the Spotify embeds SDK or integration code
    source: https://github.com/nkalupahana/baseline/blob/main/package.json
    tier: observed
  kind: self-hosted
  name: Baseline
  page: /applications/mental-health-meditation/baseline/
  slug: baseline
  url: https://github.com/nkalupahana/baseline
- anchor: sleep-as-android
  counts:
    declared: 16
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
  - route: documentation
    url: https://sleep.urbandroid.org/docs/services/
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
    name: Facebook Ads
    provider: facebook
    says: ships the Facebook Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
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
    name: Amazfit (Zepp Health)
    provider: zepp-health
    says: lists Amazfit (Zepp Health) as an integration
    source: https://sleep.urbandroid.org/docs/services/
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
    name: Automate (LlamaLab)
    provider: automate
    says: lists Automate (LlamaLab) as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Garmin
    provider: garmin
    says: lists Garmin as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10.10
      key: AE-200.10.10
      name: Voice Assistant Smart-Home Integrations
      url: /capabilities/smart-home/
      via_parent: Smart Home
    credit: null
    layer: domain
    name: Google Assistant (App Actions)
    provider: google-assistant
    says: lists Google Assistant (App Actions) as an integration
    source: https://sleep.urbandroid.org/docs/services/
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
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Fit
    provider: google-fitness
    says: lists Google Fit as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Home / Wear OS
    provider: google
    says: lists Google Home / Wear OS as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Health Connect
    provider: health-connect
    says: lists Health Connect as an integration
    source: https://sleep.urbandroid.org/docs/services/
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
    name: Home Assistant
    provider: home-assistant
    says: lists Home Assistant as an integration
    source: https://sleep.urbandroid.org/docs/services/
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
    source: https://sleep.urbandroid.org/docs/services/
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
    name: MQTT
    provider: mqtt
    says: lists MQTT as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Pebble smartwatch
    provider: repebble
    says: lists Pebble smartwatch as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Samsung Health
    provider: samsung
    says: lists Samsung Health as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: lists Spotify as an integration
    source: https://sleep.urbandroid.org/docs/services/
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
    name: Tasker
    provider: tasker
    says: lists Tasker as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Xiaomi Mi Band
    provider: xiaomi
    says: lists Xiaomi Mi Band as an integration
    source: https://sleep.urbandroid.org/docs/services/
    tier: declared
  kind: commercial
  name: Sleep as Android
  page: /applications/mental-health-meditation/sleep-as-android/
  slug: sleep-as-android
  url: https://sleep.urbandroid.org/
- anchor: headspace
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
    tier: observed
  kind: commercial
  name: Headspace
  page: /applications/mental-health-meditation/headspace/
  slug: headspace
  url: https://www.headspace.com/
- anchor: calm
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
    tier: observed
  kind: commercial
  name: Calm
  page: /applications/mental-health-meditation/calm/
  slug: calm
  url: https://www.calm.com/
- anchor: betterhelp
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
    tier: observed
  kind: commercial
  name: BetterHelp
  page: /applications/mental-health-meditation/betterhelp/
  slug: betterhelp
  url: https://www.betterhelp.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: mental-health-meditation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Health & Fitness
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Health & Fitness
  store: google-play
  url: https://play.google.com/store/apps/category/HEALTH_AND_FITNESS
- category: Medical
  store: google-play
  url: https://play.google.com/store/apps/category/MEDICAL
name: Mental Health, Meditation & Sleep
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: Mindful minutes, sleep and mood are written to HealthKit / Health Connect / wearables
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: Sleep and mood apps embed or play music
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: Sleep trackers drive lights and home automations at bedtime and wake
- capability:
    attribution: API Evangelist extension
    id: AE-200.10.10
    key: AE-200.10.10
    name: Voice Assistant Smart-Home Integrations
    url: /capabilities/smart-home/
    via_parent: Smart Home
  fit: exact
  layer: domain
  why: Start/stop sleep tracking by voice
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: Every reference app instruments funnels and retention
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: Crash and error reporting
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: Meditation reminders and streak nudges
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Donations / subscriptions
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: Subscription paywalls
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: Account sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Sleep events trigger user automations
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: Calendar-aware alarms; transactional mail via Gmail
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Backend data export/ops
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: Backend async jobs
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad monetisation
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep links
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app customer feedback
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in
stack:
- capabilities:
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
      - Medito
      - Pixy Mood Tracker
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple HealthKit
      slug: apple
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      - https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Medito
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: none
      name: Google Health Connect
      slug: health-connect
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Android
      - Company
      - Data
      - Health
      tier: observed
      url: /providers/health-connect/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Sleep as Android
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Home / Wear OS
      slug: google
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Sleep as Android
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Xiaomi Mi Band
      slug: xiaomi
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Consumer Electronics
      - IoT
      - Mobile
      - Smart Home
      tier: declared
      url: /providers/xiaomi/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Sleep as Android
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Google Fit
      slug: google-fitness
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Activity Tracking
      - Fitness
      - Google
      - Health
      tier: declared
      url: /providers/google-fitness/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Sleep as Android
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        status: none
      name: Samsung Health
      slug: samsung
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Consumer Electronics
      - Developer Platform
      - IoT
      - Mobile
      tier: declared
      url: /providers/samsung/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 21.4
      mcp:
        status: none
      name: Garmin
      slug: garmin
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Fitness
      - GPS
      - Outdoor
      - Wearables
      tier: declared
      url: /providers/garmin/
    - agent_band: agent-aware
      agent_readiness: 7.0
      apps:
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 20.3
      mcp:
        status: none
      name: Pebble smartwatch
      slug: repebble
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Company
      - IoT
      - Smartwatch
      - Wearables
      tier: declared
      url: /providers/repebble/
    - agent_band: agent-aware
      agent_readiness: 7.4
      apps:
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: unknown
      name: Amazfit (Zepp Health)
      slug: zepp-health
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Company
      - Health
      - IoT
      - Wearables
      tier: declared
      url: /providers/zepp-health/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Baseline
      - Sleep as Android
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: Spotify embeds
      slug: spotify
      sources:
      - https://github.com/nkalupahana/baseline/blob/main/package.json
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 5.0
      apps:
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 22.2
      mcp:
        source: https://www.home-assistant.io/integrations/mcp_server/
        status: verified
      name: Home Assistant
      slug: home-assistant
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Community
      - Home Automation
      - IoT
      - Open Source
      tier: declared
      url: /providers/home-assistant/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 16.0
      mcp:
        status: none
      name: MQTT
      slug: mqtt
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - IoT
      - MQTT
      - Messaging
      - Publish Subscribe
      tier: declared
      url: /providers/mqtt/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10.10
      key: AE-200.10.10
      name: Voice Assistant Smart-Home Integrations
      url: /capabilities/smart-home/
      via_parent: Smart Home
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - Sleep as Android
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        status: unknown
      name: Google Assistant (App Actions)
      slug: google-assistant
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Actions on Google
      - Conversational AI
      - Google Assistant
      - Natural-Language
      tier: declared
      url: /providers/google-assistant/
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
      - Baseline
      - BetterHelp
      - Calm
      - Medito
      - Sleep as Android
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Analytics
      slug: firebase
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      - https://github.com/nkalupahana/baseline/blob/main/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
      status: profiled
      tags: &id002
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Calm
      - Headspace
      - Heylinda
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://github.com/heylinda/heylinda-app/blob/main/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Calm
      - Medito
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: &id003
        status: none
      name: Facebook App Events
      slug: facebook
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      - https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Pixy Mood Tracker
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
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
      - Baseline
      - Headspace
      - Pixy Mood Tracker
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
      - https://github.com/nkalupahana/baseline/blob/main/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - BetterHelp
      - Calm
      - Medito
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase Crashlytics
      slug: firebase
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      - https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
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
      - BetterHelp
      - Calm
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.betterhelp/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
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
      - Headspace
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Sleep as Android
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Sleep as Android
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: Automate (LlamaLab)
      slug: automate
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: profiled
      tags:
      - Automotive
      - Company
      - Dealer Management
      - Software
      tier: declared
      url: /providers/automate/
    - agent_band: null
      agent_readiness: null
      apps:
      - Sleep as Android
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Tasker
      slug: tasker
      sources:
      - https://sleep.urbandroid.org/docs/services/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Sleep as Android
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Sleep as Android
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id003
      name: Facebook Ads
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
      status: profiled
      tags: *id004
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
      agent_readiness: 19.6
      apps:
      - Baseline
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail API
      slug: google-gmail
      sources:
      - https://github.com/nkalupahana/baseline/blob/main/backend/package.json
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Sleep as Android
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://sleep.urbandroid.org/docs/services/
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
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Baseline
      - Medito
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      - https://github.com/nkalupahana/baseline/blob/main/package.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.0
      apps:
      - Headspace
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Baseline
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase Authentication
      slug: firebase
      sources:
      - https://github.com/nkalupahana/baseline/blob/main/package.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Pixy Mood Tracker
      band: developing
      in_catalog: true
      kin_score: 53.3
      mcp:
        source: https://superwall.com/docs/agents/mcp
        status: verified
      name: Superwall
      slug: superwall
      sources:
      - https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
      status: profiled
      tags:
      - Company
      - Mobile
      - Monetization
      - SDK
      tier: observed
      url: /providers/superwall/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Baseline
      band: thin
      in_catalog: true
      kin_score: 38.7
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/nkalupahana/baseline/blob/main/backend/package.json
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
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
      - Medito
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
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
      - Calm
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id003
      name: Facebook Login
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.calm.android/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Baseline
      band: strong
      in_catalog: true
      kin_score: 64.5
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/nkalupahana/baseline/blob/main/backend/package.json
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
  layer: common
summary:
  coverage_pct: 96.8
  declared_only: 14
  distinct_providers: 31
  in_catalog: 30
  mcp:
    documented: 0
    none: 15
    unchecked: 1
    verified: 13
  mcp_verified: 13
  mean_kin_score: 42.7
  observed: 17
  queued: 1
  reference_apps: 8
title: 'Mental Health, Meditation & Sleep: application blueprint'
---
