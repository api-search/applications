---
app: Cronometer
app_slug: cronometer
app_url: https://cronometer.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2900
  key: health-information-management
  layer: domain
  name: Health Information Management
  providers:
  - dexcom
  url: /capabilities/health-information-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - apple
  - fitbit
  - garmin
  - oura-ring
  - polar
  - whoop
  - withings
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.60
  key: advertising-revenue-reporting
  layer: common
  name: Advertising Revenue Reporting
  providers:
  - adjust
  url: /capabilities/advertising-revenue-reporting/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - amplitude
  - firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - google-admob
  url: /capabilities/programmatic-sales-management/
  via_parent: null
category:
  id: fitness-nutrition
  name: Fitness & Nutrition Tracking
  url: /applications/fitness-nutrition/
counts:
  declared: 8
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
- route: documentation
  url: https://cronometer.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3760.60
    key: advertising-revenue-reporting
    name: Advertising Revenue Reporting
    url: /capabilities/advertising-revenue-reporting/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: emerging
    in_catalog: true
    kin_score: 24.9
    mcp: &id002
      status: none
    slug: adjust
    status: profiled
    tags: &id003
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: adjust
  provider: adjust
  says: ships the adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id004
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id005
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: amplitude
  provider: amplitude
  says: ships the amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id010
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id011
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: firebase
  provider: firebase
  says: ships the firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: firebase
  provider: firebase
  says: ships the firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id016
      status: none
    slug: google-admob
    status: profiled
    tags: &id017
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: google-admob
  provider: google-admob
  says: ships the google-admob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id006
      status: none
    slug: apple
    status: profiled
    tags: &id007
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: apple
  provider: apple
  says: lists apple as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900
    key: health-information-management
    name: Health Information Management
    url: /capabilities/health-information-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id008
      status: none
    slug: dexcom
    status: profiled
    tags: &id009
    - Continuous Glucose Monitoring
    - Diabetes
    - Digital Health
    - Glucose
    url: /providers/dexcom/
  layer: domain
  name: dexcom
  provider: dexcom
  says: lists dexcom as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 61.6
    mcp: &id012
      status: none
    slug: fitbit
    status: profiled
    tags: &id013
    - Activity Tracking
    - Fitness
    - Health
    - Wearables
    url: /providers/fitbit/
  layer: domain
  name: fitbit
  provider: fitbit
  says: lists fitbit as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.4
    mcp: &id014
      status: none
    slug: garmin
    status: profiled
    tags: &id015
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
  layer: domain
  name: garmin
  provider: garmin
  says: lists garmin as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 50.2
    mcp: &id018
      status: none
    slug: oura-ring
    status: profiled
    tags: &id019
    - Activity
    - Biometrics
    - Cardiovascular
    - Fitness
    url: /providers/oura-ring/
  layer: domain
  name: oura-ring
  provider: oura-ring
  says: lists oura-ring as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id020
      status: unknown
    slug: polar
    status: profiled
    tags: &id021
    - Fitness
    - Health
    - Heart Rate
    - Wearables
    url: /providers/polar/
  layer: domain
  name: polar
  provider: polar
  says: lists polar as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id022
      status: none
    slug: whoop
    status: profiled
    tags: &id023
    - Fitness
    - Health
    - Recovery
    - Wearables
    url: /providers/whoop/
  layer: domain
  name: whoop
  provider: whoop
  says: lists whoop as an integration
  source: https://cronometer.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id024
      status: none
    slug: withings
    status: profiled
    tags: &id025
    - Body Composition
    - Connected Devices
    - Health
    - Wearables
    url: /providers/withings/
  layer: domain
  name: withings
  provider: withings
  says: lists withings as an integration
  source: https://cronometer.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/cronometer/
providers:
- agent_band: agent-aware
  agent_readiness: 23.8
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id002
  name: adjust
  slug: adjust
  status: profiled
  tags: *id003
  url: /providers/adjust/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id004
  name: amplitude
  slug: amplitude
  status: profiled
  tags: *id005
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id006
  name: apple
  slug: apple
  status: profiled
  tags: *id007
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id008
  name: dexcom
  slug: dexcom
  status: profiled
  tags: *id009
  url: /providers/dexcom/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id010
  name: firebase
  slug: firebase
  status: profiled
  tags: *id011
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 61.6
  mcp: *id012
  name: fitbit
  slug: fitbit
  status: profiled
  tags: *id013
  url: /providers/fitbit/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id014
  name: garmin
  slug: garmin
  status: profiled
  tags: *id015
  url: /providers/garmin/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id016
  name: google-admob
  slug: google-admob
  status: profiled
  tags: *id017
  url: /providers/google-admob/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 50.2
  mcp: *id018
  name: oura-ring
  slug: oura-ring
  status: profiled
  tags: *id019
  url: /providers/oura-ring/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id020
  name: polar
  slug: polar
  status: profiled
  tags: *id021
  url: /providers/polar/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id022
  name: whoop
  slug: whoop
  status: profiled
  tags: *id023
  url: /providers/whoop/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id024
  name: withings
  slug: withings
  status: profiled
  tags: *id025
  url: /providers/withings/
siblings:
- name: Endurain
  rows: 3
  url: /applications/fitness-nutrition/endurain/
- name: FitTrackee
  rows: 1
  url: /applications/fitness-nutrition/fittrackee/
- name: Lose It!
  rows: 9
  url: /applications/fitness-nutrition/lose-it/
- name: Mealie
  rows: 1
  url: /applications/fitness-nutrition/mealie/
- name: MyFitnessPal
  rows: 26
  url: /applications/fitness-nutrition/myfitnesspal/
- name: SparkyFitness
  rows: 28
  url: /applications/fitness-nutrition/sparkyfitness/
- name: Strava
  rows: 17
  url: /applications/fitness-nutrition/strava/
- name: Tandoor Recipes
  rows: 2
  url: /applications/fitness-nutrition/tandoor-recipes/
- name: wger
  rows: 2
  url: /applications/fitness-nutrition/wger/
sitemap: true
title: 'Cronometer: Fitness & Nutrition Tracking reference app'
---
