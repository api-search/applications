---
app: Natural Cycles
app_slug: natural-cycles
app_url: https://www.naturalcycles.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Apple
  - Garmin
  - Oura
  - WHOOP
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - MoEngage
  url: /capabilities/customer-lifecycle-engagement/
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: period-fertility-tracking
  name: Period, Fertility & Pregnancy Tracking
  url: /applications/period-fertility-tracking/
counts:
  declared: 4
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: emerging
    in_catalog: true
    kin_score: 24.9
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
  facts:
    agent_band: agent-native
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id007
      status: none
    slug: moengage
    status: profiled
    tags: &id008
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id011
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id012
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.4
    mcp: &id005
      status: none
    slug: garmin
    status: profiled
    tags: &id006
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 50.2
    mcp: &id009
      status: none
    slug: oura-ring
    status: profiled
    tags: &id010
    - Activity
    - Biometrics
    - Cardiovascular
    - Fitness
    url: /providers/oura-ring/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id013
      status: none
    slug: whoop
    status: profiled
    tags: &id014
    - Fitness
    - Health
    - Recovery
    - Wearables
    url: /providers/whoop/
  layer: domain
  name: WHOOP
  provider: whoop
  says: lists WHOOP as an integration
  source: https://www.naturalcycles.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/period-fertility-tracking/natural-cycles/
providers:
- agent_band: agent-aware
  agent_readiness: 23.8
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id005
  name: Garmin
  slug: garmin
  status: profiled
  tags: *id006
  url: /providers/garmin/
- agent_band: agent-native
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id007
  name: MoEngage
  slug: moengage
  status: profiled
  tags: *id008
  url: /providers/moengage/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 50.2
  mcp: *id009
  name: Oura
  slug: oura-ring
  status: profiled
  tags: *id010
  url: /providers/oura-ring/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id011
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id012
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id013
  name: WHOOP
  slug: whoop
  status: profiled
  tags: *id014
  url: /providers/whoop/
siblings:
- name: Clue
  rows: 13
  url: /applications/period-fertility-tracking/clue/
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
- name: Ovia
  rows: 9
  url: /applications/period-fertility-tracking/ovia/
sitemap: true
title: 'Natural Cycles: Period, Fertility & Pregnancy Tracking reference app'
---
