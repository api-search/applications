---
app: Lose It!
app_slug: lose-it
app_url: https://www.loseit.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - apple
  - google
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.60
  key: advertising-revenue-reporting
  layer: common
  name: Advertising Revenue Reporting
  providers:
  - singular
  url: /capabilities/advertising-revenue-reporting/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - firebase
  - rollbar
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
  - amazon
  - google-admob
  url: /capabilities/programmatic-sales-management/
  via_parent: null
category:
  id: fitness-nutrition
  name: Fitness & Nutrition Tracking
  url: /applications/fitness-nutrition/
counts:
  declared: 2
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
- route: documentation
  url: https://www.loseit.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id002
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id003
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: common
  name: amazon
  provider: amazon
  says: ships the amazon SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id012
      status: none
    slug: google-admob
    status: profiled
    tags: &id013
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: google-admob
  provider: google-admob
  says: ships the google-admob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id014
      source: https://github.com/rollbar/rollbar-mcp-server
      status: verified
    slug: rollbar
    status: profiled
    tags: &id015
    - Debugging
    - DevOps
    - Error Tracking
    - Monitoring
    url: /providers/rollbar/
  layer: common
  name: rollbar
  provider: rollbar
  says: ships the rollbar SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.60
    key: advertising-revenue-reporting
    name: Advertising Revenue Reporting
    url: /capabilities/advertising-revenue-reporting/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id016
      status: none
    slug: singular
    status: profiled
    tags: &id017
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: common
  name: singular
  provider: singular
  says: ships the singular SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
  source: https://www.loseit.com/
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
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id010
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id011
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: google
  provider: google
  says: lists google as an integration
  source: https://www.loseit.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/lose-it/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id002
  name: amazon
  slug: amazon
  status: profiled
  tags: *id003
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id004
  name: amplitude
  slug: amplitude
  status: profiled
  tags: *id005
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id006
  name: apple
  slug: apple
  status: profiled
  tags: *id007
  url: /providers/apple/
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
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id010
  name: google
  slug: google
  status: profiled
  tags: *id011
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id012
  name: google-admob
  slug: google-admob
  status: profiled
  tags: *id013
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id014
  name: rollbar
  slug: rollbar
  status: profiled
  tags: *id015
  url: /providers/rollbar/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id016
  name: singular
  slug: singular
  status: profiled
  tags: *id017
  url: /providers/singular/
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
title: 'Lose It!: Fitness & Nutrition Tracking reference app'
---
