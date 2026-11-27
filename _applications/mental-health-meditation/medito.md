---
app: Medito
app_slug: medito
app_url: https://github.com/meditohq/medito-app
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Apple HealthKit
  - Google Health Connect
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook App Events
  - Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: mental-health-meditation
  name: Mental Health, Meditation & Sleep
  url: /applications/mental-health-meditation/
counts:
  declared: 0
  observed: 7
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id002
      status: none
    slug: apple
    status: profiled
    tags: &id003
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id004
      status: none
    slug: facebook
    status: profiled
    tags: &id005
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id006
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id007
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
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
  facts: *id001
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
  facts: *id001
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
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id008
      status: none
    slug: health-connect
    status: profiled
    tags: &id009
    - Android
    - Company
    - Data
    - Health
    url: /providers/health-connect/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id010
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id011
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/meditohq/medito-app/blob/main/pubspec.yaml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mental-health-meditation/medito/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id002
  name: Apple HealthKit
  slug: apple
  status: profiled
  tags: *id003
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id004
  name: Facebook App Events
  slug: facebook
  status: profiled
  tags: *id005
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id006
  name: Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id007
  url: /providers/google-firebase/
- agent_band: human-only
  agent_readiness: 0.7
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id008
  name: Google Health Connect
  slug: health-connect
  status: profiled
  tags: *id009
  url: /providers/health-connect/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id010
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id011
  url: /providers/stripe/
siblings:
- name: Baseline
  rows: 8
  url: /applications/mental-health-meditation/baseline/
- name: BetterHelp
  rows: 3
  url: /applications/mental-health-meditation/betterhelp/
- name: Calm
  rows: 6
  url: /applications/mental-health-meditation/calm/
- name: Headspace
  rows: 4
  url: /applications/mental-health-meditation/headspace/
- name: Heylinda
  rows: 1
  url: /applications/mental-health-meditation/heylinda/
- name: Pixy Mood Tracker
  rows: 4
  url: /applications/mental-health-meditation/pixy-mood-tracker/
- name: Sleep as Android
  rows: 19
  url: /applications/mental-health-meditation/sleep-as-android/
sitemap: true
title: 'Medito: Mental Health, Meditation & Sleep reference app'
---
