---
access: understanding
agent_layer: []
apps:
- anchor: drip
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.drip/latest/
  - route: dependency manifest
    url: https://gitlab.com/bloodyhealth/drip/-/raw/main/package.json
  integrations: []
  kind: open-source-saas
  name: drip
  page: /applications/period-fertility-tracking/drip/
  slug: drip
  url: https://gitlab.com/bloodyhealth/drip
- anchor: euki
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/Euki-Inc/Euki-Android/blob/main/app/build.gradle
  - route: dependency manifest
    url: https://github.com/Euki-Inc/Euki-iOS/blob/main/Podfile
  integrations: []
  kind: self-hosted
  name: Euki
  page: /applications/period-fertility-tracking/euki/
  slug: euki
  url: https://github.com/Euki-Inc/Euki-Android
- anchor: mensinator
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/EmmaTellblom/Mensinator/blob/main/gradle/libs.versions.toml
  integrations: []
  kind: self-hosted
  name: Mensinator
  page: /applications/period-fertility-tracking/mensinator/
  slug: mensinator
  url: https://github.com/EmmaTellblom/Mensinator
- anchor: flo
  counts:
    declared: 2
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
  - route: documentation
    url: https://help.flo.health/hc/en-us/search?query=apple+health
  - route: documentation
    url: https://help.flo.health/hc/en-us/search?query=subscription+payment
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
    source: https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://help.flo.health/hc/en-us/search?query=apple+health
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://help.flo.health/hc/en-us/search?query=apple+health
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Google
    provider: google
    says: lists Google as an integration
    source: https://help.flo.health/hc/en-us/search?query=apple+health
    tier: declared
  kind: commercial
  name: Flo
  page: /applications/period-fertility-tracking/flo/
  slug: flo
  url: https://flo.health/
- anchor: clue
  counts:
    declared: 10
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.clue.android/latest/
  - route: documentation
    url: https://helloclue.com/
  - route: integrations page
    url: https://helloclue.com/landing/wearables
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.clue.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.clue.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://helloclue.com/
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
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://helloclue.com/landing/wearables
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
    name: Fitbit
    provider: fitbit
    says: lists Fitbit as an integration
    source: https://helloclue.com/landing/wearables
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
    source: https://helloclue.com/landing/wearables
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
    name: HUAWEI Health Kit
    provider: huawei-health-kit
    says: lists HUAWEI Health Kit as an integration
    source: https://helloclue.com/landing/wearables
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
    name: Luna Ring
    provider: luna-ring
    says: lists Luna Ring as an integration
    source: https://helloclue.com/landing/wearables
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
    name: Oura
    provider: oura-ring
    says: lists Oura as an integration
    source: https://helloclue.com/landing/wearables
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
    name: Polar
    provider: polar
    says: lists Polar as an integration
    source: https://helloclue.com/landing/wearables
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
    name: Ultrahuman
    provider: ultrahuman
    says: lists Ultrahuman as an integration
    source: https://helloclue.com/landing/wearables
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
    name: WHOOP
    provider: whoop
    says: lists WHOOP as an integration
    source: https://helloclue.com/landing/wearables
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
    name: Withings
    provider: withings
    says: lists Withings as an integration
    source: https://helloclue.com/landing/wearables
    tier: declared
  kind: commercial
  name: Clue
  page: /applications/period-fertility-tracking/clue/
  slug: clue
  url: https://helloclue.com/
- anchor: natural-cycles
  counts:
    declared: 4
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
  - route: integrations page
    url: https://www.naturalcycles.com/
  - route: integrations page
    url: https://www.naturalcycles.com/wearables
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
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
    name: MoEngage
    provider: moengage
    says: ships the MoEngage SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
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
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://www.naturalcycles.com/
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
    source: https://www.naturalcycles.com/
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
    name: Oura
    provider: oura-ring
    says: lists Oura as an integration
    source: https://www.naturalcycles.com/wearables
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
    name: WHOOP
    provider: whoop
    says: lists WHOOP as an integration
    source: https://www.naturalcycles.com/
    tier: declared
  kind: commercial
  name: Natural Cycles
  page: /applications/period-fertility-tracking/natural-cycles/
  slug: natural-cycles
  url: https://www.naturalcycles.com/
- anchor: ovia
  counts:
    declared: 2
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
  - route: documentation
    url: https://www.oviahealth.com/
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
    name: Amazon Mobile Analytics (Amplify)
    provider: amazon-web-services
    says: ships the Amazon Mobile Analytics (Amplify) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    name: Apptentive
    provider: apptentive
    says: ships the Apptentive SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Helpshift
    provider: helpshift
    says: ships the Helpshift SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://www.oviahealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Google Fit
    provider: google-fitness
    says: lists Google Fit as an integration
    source: https://www.oviahealth.com/
    tier: declared
  kind: commercial
  name: Ovia
  page: /applications/period-fertility-tracking/ovia/
  slug: ovia
  url: https://www.oviahealth.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: period-fertility-tracking
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Health & Fitness
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Medical
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Health & Fitness
  store: google-play
  url: https://play.google.com/store/apps/category/HEALTH_AND_FITNESS
- category: Parenting
  store: google-play
  url: https://play.google.com/store/apps/category/PARENTING
name: Period, Fertility & Pregnancy Tracking
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-130.60
    key: AE-130.60
    name: Women's & Reproductive Health
    url: /capabilities/women-s-reproductive-health/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the category itself: cycle, fertility-window and pregnancy tracking; every reference app computes it on-device or in its own backend, no third-party API appeared'
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: temperature, sleep and HRV from rings and watches feed fertility-window prediction (Clue, Natural Cycles)
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  fit: exact
  layer: domain
  why: Apple Health / Health Connect / Google Fit as the OS-level hub (Flo, Ovia)
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: self-serve help centers
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep-link SDKs named in Exodus reports
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app advertising SDKs named in Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app feedback SDK named in an Exodus report
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: push and in-app messaging SDK named in an Exodus report
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting SDKs named in Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: in-app usage analytics SDKs named in Exodus reports
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
      agent_readiness: 36.5
      apps:
      - Clue
      - Natural Cycles
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: &id001
        status: none
      name: Apple
      slug: apple
      sources:
      - https://helloclue.com/landing/wearables
      - https://www.naturalcycles.com/
      status: profiled
      tags: &id002
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - Clue
      - Natural Cycles
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        status: none
      name: Oura
      slug: oura-ring
      sources:
      - https://helloclue.com/landing/wearables
      - https://www.naturalcycles.com/wearables
      status: profiled
      tags:
      - Activity
      - Biometrics
      - Cardiovascular
      - Fitness
      tier: declared
      url: /providers/oura-ring/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Clue
      - Natural Cycles
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: WHOOP
      slug: whoop
      sources:
      - https://helloclue.com/landing/wearables
      - https://www.naturalcycles.com/
      status: profiled
      tags:
      - Fitness
      - Health
      - Recovery
      - Wearables
      tier: declared
      url: /providers/whoop/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clue
      - Natural Cycles
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: none
      name: Garmin
      slug: garmin
      sources:
      - https://helloclue.com/landing/wearables
      - https://www.naturalcycles.com/
      status: profiled
      tags:
      - Fitness
      - GPS
      - Outdoor
      - Wearables
      tier: declared
      url: /providers/garmin/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Clue
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Fitbit
      slug: fitbit
      sources:
      - https://helloclue.com/landing/wearables
      status: profiled
      tags:
      - Activity Tracking
      - Fitness
      - Health
      - Wearables
      tier: declared
      url: /providers/fitbit/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Clue
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        status: unknown
      name: Polar
      slug: polar
      sources:
      - https://helloclue.com/landing/wearables
      status: profiled
      tags:
      - Fitness
      - Health
      - Heart Rate
      - Wearables
      tier: declared
      url: /providers/polar/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Clue
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        status: none
      name: Withings
      slug: withings
      sources:
      - https://helloclue.com/landing/wearables
      status: profiled
      tags:
      - Body Composition
      - Connected Devices
      - Health
      - Wearables
      tier: declared
      url: /providers/withings/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Clue
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        source: https://vision.ultrahuman.com/developer-docs?type=mcp
        status: verified
      name: Ultrahuman
      slug: ultrahuman
      sources:
      - https://helloclue.com/landing/wearables
      status: profiled
      tags:
      - Health
      - Metabolic Health
      - Smart Ring
      - Wearables
      tier: declared
      url: /providers/ultrahuman/
    - agent_band: null
      agent_readiness: null
      apps:
      - Clue
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: HUAWEI Health Kit
      slug: huawei-health-kit
      sources:
      - https://helloclue.com/landing/wearables
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Clue
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Luna Ring
      slug: luna-ring
      sources:
      - https://helloclue.com/landing/wearables
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Flo
      - Ovia
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id001
      name: Apple
      slug: apple
      sources:
      - https://help.flo.health/hc/en-us/search?query=apple+health
      - https://www.oviahealth.com/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Flo
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google
      slug: google
      sources:
      - https://help.flo.health/hc/en-us/search?query=apple+health
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Ovia
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Google Fit
      slug: google-fitness
      sources:
      - https://www.oviahealth.com/
      status: profiled
      tags:
      - Activity Tracking
      - Fitness
      - Google
      - Health
      tier: declared
      url: /providers/google-fitness/
  layer: domain
- capabilities:
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
      - Flo
      - Ovia
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Clue
      - Natural Cycles
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.clue.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
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
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Clue
      - Flo
      - Ovia
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.clue.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Ovia
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Mobile Analytics (Amplify)
      slug: amazon-web-services
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Clue
      - Flo
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://helloclue.com/
      - https://help.flo.health/hc/en-us/search?query=apple+health
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: null
      agent_readiness: null
      apps:
      - Ovia
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Helpshift
      slug: helpshift
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Flo
      - Natural Cycles
      - Ovia
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.iggymedia.periodtracker/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
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
      - Ovia
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        status: none
      name: Apptentive
      slug: apptentive
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
      status: profiled
      tags:
      - Company
      - Customer Feedback
      - Enterprise
      - Mobile
      tier: observed
      url: /providers/apptentive/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 65.1
      apps:
      - Natural Cycles
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: MoEngage
      slug: moengage
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.naturalcycles.cordova/latest/
      status: profiled
      tags:
      - Customer Data Platform
      - Customer Engagement
      - Marketing Automation
      - Push Notifications
      tier: observed
      url: /providers/moengage/
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
      - Ovia
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  layer: common
summary:
  coverage_pct: 86.4
  declared_only: 12
  distinct_providers: 22
  in_catalog: 19
  mcp:
    documented: 0
    none: 12
    unchecked: 3
    verified: 6
  mcp_verified: 6
  mean_kin_score: 54.1
  observed: 10
  queued: 3
  reference_apps: 7
title: 'Period, Fertility & Pregnancy Tracking: application blueprint'
---
