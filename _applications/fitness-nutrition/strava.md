---
app: Strava
app_slug: strava
app_url: https://www.strava.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.40
  key: AE-130.10.40
  layer: domain
  name: Connected Fitness Equipment
  providers:
  - peloton
  - wahoo
  - zwift
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.10.30
  key: AE-130.10.30
  layer: domain
  name: Running & Cycling Tracking
  providers:
  - nike
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - coros
  - fitbit
  - garmin
  - oura-ring
  - polar
  - samsung
  - suunto
  - whoop
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.60
  key: advertising-revenue-reporting
  layer: common
  name: Advertising Revenue Reporting
  providers:
  - branch-io
  url: /capabilities/advertising-revenue-reporting/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - facebook
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - sentry-system
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - facebook
  - firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: fitness-nutrition
  name: Fitness & Nutrition Tracking
  url: /applications/fitness-nutrition/
counts:
  declared: 12
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
- route: documentation
  url: https://support.strava.com/hc/en-us/articles/223297187
- route: integrations page
  url: https://www.strava.com/apps
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
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id002
      status: none
    slug: branch-io
    status: profiled
    tags: &id003
    - Company
    url: /providers/branch-io/
  layer: common
  name: branch-io
  provider: branch-io
  says: ships the branch-io SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id006
      status: none
    slug: facebook
    status: profiled
    tags: &id007
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: facebook
  provider: facebook
  says: ships the facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: facebook
  provider: facebook
  says: ships the facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
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
    mcp: &id008
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id009
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: firebase
  provider: firebase
  says: ships the firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
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
    kin_score: 80.7
    mcp: &id024
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id025
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: sentry-system
  provider: sentry-system
  says: ships the sentry-system SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
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
    agent_band: agent-aware
    agent_readiness: 27.7
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id004
      source: https://github.com/coroslab/COROS-MCP
      status: verified
    slug: coros
    status: profiled
    tags: &id005
    - Company
    - Fitness
    - GPS Watches
    - Wearables
    url: /providers/coros/
  layer: domain
  name: coros
  provider: coros
  says: lists coros as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
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
    mcp: &id010
      status: none
    slug: fitbit
    status: profiled
    tags: &id011
    - Activity Tracking
    - Fitness
    - Health
    - Wearables
    url: /providers/fitbit/
  layer: domain
  name: fitbit
  provider: fitbit
  says: lists fitbit as an integration
  source: https://www.strava.com/apps
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
    mcp: &id012
      status: none
    slug: garmin
    status: profiled
    tags: &id013
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
  layer: domain
  name: garmin
  provider: garmin
  says: lists garmin as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id014
      status: none
    slug: nike
    status: profiled
    tags: &id015
    - Apparel
    - Fashion
    - Footwear
    - Fortune 500
    url: /providers/nike/
  layer: domain
  name: nike
  provider: nike
  says: lists nike as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
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
    mcp: &id016
      status: none
    slug: oura-ring
    status: profiled
    tags: &id017
    - Activity
    - Biometrics
    - Cardiovascular
    - Fitness
    url: /providers/oura-ring/
  layer: domain
  name: oura-ring
  provider: oura-ring
  says: lists oura-ring as an integration
  source: https://www.strava.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.40
    key: AE-130.10.40
    name: Connected Fitness Equipment
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.2
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id018
      status: none
    slug: peloton
    status: profiled
    tags: &id019
    - Connected Fitness
    - Fitness
    - Subscription
    - Wellness
    url: /providers/peloton/
  layer: domain
  name: peloton
  provider: peloton
  says: lists peloton as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
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
  source: https://support.strava.com/hc/en-us/articles/223297187
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
    agent_readiness: 36.6
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id022
      status: none
    slug: samsung
    status: profiled
    tags: &id023
    - Consumer Electronics
    - Developer Platform
    - IoT
    - Mobile
    url: /providers/samsung/
  layer: domain
  name: samsung
  provider: samsung
  says: lists samsung as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
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
    agent_readiness: 17.1
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id026
      status: none
    slug: suunto
    status: profiled
    tags: &id027
    - Company
    - Outdoor
    - Sports
    - Wearables
    url: /providers/suunto/
  layer: domain
  name: suunto
  provider: suunto
  says: lists suunto as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.40
    key: AE-130.10.40
    name: Connected Fitness Equipment
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id028
      status: none
    slug: wahoo
    status: profiled
    tags: &id029
    - Bike Computers
    - Cycling
    - Endurance Training
    - Fitness
    url: /providers/wahoo/
  layer: domain
  name: wahoo
  provider: wahoo
  says: lists wahoo as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
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
    mcp: &id030
      status: none
    slug: whoop
    status: profiled
    tags: &id031
    - Fitness
    - Health
    - Recovery
    - Wearables
    url: /providers/whoop/
  layer: domain
  name: whoop
  provider: whoop
  says: lists whoop as an integration
  source: https://www.strava.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.40
    key: AE-130.10.40
    name: Connected Fitness Equipment
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id032
      status: none
    slug: zwift
    status: profiled
    tags: &id033
    - Cycling
    - Indoor Cycling
    - Running
    - Smart Trainers
    url: /providers/zwift/
  layer: domain
  name: zwift
  provider: zwift
  says: lists zwift as an integration
  source: https://support.strava.com/hc/en-us/articles/223297187
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/strava/
providers:
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id002
  name: branch-io
  slug: branch-io
  status: profiled
  tags: *id003
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id004
  name: coros
  slug: coros
  status: profiled
  tags: *id005
  url: /providers/coros/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id006
  name: facebook
  slug: facebook
  status: profiled
  tags: *id007
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id008
  name: firebase
  slug: google-firebase
  status: profiled
  tags: *id009
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id010
  name: fitbit
  slug: fitbit
  status: profiled
  tags: *id011
  url: /providers/fitbit/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id012
  name: garmin
  slug: garmin
  status: profiled
  tags: *id013
  url: /providers/garmin/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id014
  name: nike
  slug: nike
  status: profiled
  tags: *id015
  url: /providers/nike/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id016
  name: oura-ring
  slug: oura-ring
  status: profiled
  tags: *id017
  url: /providers/oura-ring/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id018
  name: peloton
  slug: peloton
  status: profiled
  tags: *id019
  url: /providers/peloton/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id020
  name: polar
  slug: polar
  status: profiled
  tags: *id021
  url: /providers/polar/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id022
  name: samsung
  slug: samsung
  status: profiled
  tags: *id023
  url: /providers/samsung/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id024
  name: sentry-system
  slug: sentry-system
  status: profiled
  tags: *id025
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 17.1
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id026
  name: suunto
  slug: suunto
  status: profiled
  tags: *id027
  url: /providers/suunto/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id028
  name: wahoo
  slug: wahoo
  status: profiled
  tags: *id029
  url: /providers/wahoo/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id030
  name: whoop
  slug: whoop
  status: profiled
  tags: *id031
  url: /providers/whoop/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id032
  name: zwift
  slug: zwift
  status: profiled
  tags: *id033
  url: /providers/zwift/
siblings:
- name: Cronometer
  rows: 13
  url: /applications/fitness-nutrition/cronometer/
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
- name: Tandoor Recipes
  rows: 2
  url: /applications/fitness-nutrition/tandoor-recipes/
- name: wger
  rows: 2
  url: /applications/fitness-nutrition/wger/
sitemap: true
title: 'Strava: Fitness & Nutrition Tracking reference app'
---
