---
app: Clue
app_slug: clue
app_url: https://helloclue.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Apple
  - Fitbit
  - Garmin
  - HUAWEI Health Kit
  - Luna Ring
  - Oura
  - Polar
  - Ultrahuman
  - WHOOP
  - Withings
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: period-fertility-tracking
  name: Period, Fertility & Pregnancy Tracking
  url: /applications/period-fertility-tracking/
counts:
  declared: 10
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id009
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id010
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id025
      status: none
    slug: zendesk
    status: profiled
    tags: &id026
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id005
      status: none
    slug: fitbit
    status: profiled
    tags: &id006
    - Activity Tracking
    - Fitness
    - Health
    - Wearables
    url: /providers/fitbit/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id007
      status: none
    slug: garmin
    status: profiled
    tags: &id008
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: huawei-health-kit
    status: queued for profiling
    tags: &id012 []
    url: null
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: luna-ring
    status: queued for profiling
    tags: &id014 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 50.4
    mcp: &id015
      status: none
    slug: oura-ring
    status: profiled
    tags: &id016
    - Activity
    - Biometrics
    - Cardiovascular
    - Fitness
    url: /providers/oura-ring/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: developing
    in_catalog: true
    kin_score: 43.9
    mcp: &id017
      status: unknown
    slug: polar
    status: profiled
    tags: &id018
    - Fitness
    - Health
    - Heart Rate
    - Wearables
    url: /providers/polar/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id019
      source: https://vision.ultrahuman.com/developer-docs?type=mcp
      status: verified
    slug: ultrahuman
    status: profiled
    tags: &id020
    - Health
    - Metabolic Health
    - Smart Ring
    - Wearables
    url: /providers/ultrahuman/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.3
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id021
      status: none
    slug: whoop
    status: profiled
    tags: &id022
    - Fitness
    - Health
    - Recovery
    - Wearables
    url: /providers/whoop/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id023
      status: none
    slug: withings
    status: profiled
    tags: &id024
    - Body Composition
    - Connected Devices
    - Health
    - Wearables
    url: /providers/withings/
  layer: domain
  name: Withings
  provider: withings
  says: lists Withings as an integration
  source: https://helloclue.com/landing/wearables
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/period-fertility-tracking/clue/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id005
  name: Fitbit
  slug: fitbit
  status: profiled
  tags: *id006
  url: /providers/fitbit/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id007
  name: Garmin
  slug: garmin
  status: profiled
  tags: *id008
  url: /providers/garmin/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id009
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id010
  url: /providers/google-firebase/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: HUAWEI Health Kit
  slug: huawei-health-kit
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Luna Ring
  slug: luna-ring
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id015
  name: Oura
  slug: oura-ring
  status: profiled
  tags: *id016
  url: /providers/oura-ring/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id017
  name: Polar
  slug: polar
  status: profiled
  tags: *id018
  url: /providers/polar/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id019
  name: Ultrahuman
  slug: ultrahuman
  status: profiled
  tags: *id020
  url: /providers/ultrahuman/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id021
  name: WHOOP
  slug: whoop
  status: profiled
  tags: *id022
  url: /providers/whoop/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id023
  name: Withings
  slug: withings
  status: profiled
  tags: *id024
  url: /providers/withings/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id025
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id026
  url: /providers/zendesk/
siblings:
- name: drip
  rows: 0
  url: /applications/period-fertility-tracking/drip/
- name: Euki
  rows: 0
  url: /applications/period-fertility-tracking/euki/
- name: Flo
  rows: 6
  url: /applications/period-fertility-tracking/flo/
- name: Mensinator
  rows: 0
  url: /applications/period-fertility-tracking/mensinator/
- name: Natural Cycles
  rows: 7
  url: /applications/period-fertility-tracking/natural-cycles/
- name: Ovia
  rows: 9
  url: /applications/period-fertility-tracking/ovia/
sitemap: true
title: 'Clue: Period, Fertility & Pregnancy Tracking reference app'
---
