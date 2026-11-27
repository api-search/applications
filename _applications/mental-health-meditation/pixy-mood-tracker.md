---
app: Pixy Mood Tracker
app_slug: pixy-mood-tracker
app_url: https://github.com/mrzmyr/pixy-mood-tracker-app
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Apple HealthKit
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Superwall
  url: /capabilities/in-app-purchases-app-store-billing/
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
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: mental-health-meditation
  name: Mental Health, Meditation & Sleep
  url: /applications/mental-health-meditation/
counts:
  declared: 0
  observed: 4
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id003
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id005
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id006
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id007
      source: https://superwall.com/docs/agents/mcp
      status: verified
    slug: superwall
    status: profiled
    tags: &id008
    - Company
    - Mobile
    - Monetization
    - SDK
    url: /providers/superwall/
  layer: common
  name: Superwall
  provider: superwall
  says: ships the Superwall SDK or integration code
  source: https://github.com/mrzmyr/pixy-mood-tracker-app/blob/main/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mental-health-meditation/pixy-mood-tracker/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple HealthKit
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id003
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id004
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id007
  name: Superwall
  slug: superwall
  status: profiled
  tags: *id008
  url: /providers/superwall/
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
- name: Medito
  rows: 7
  url: /applications/mental-health-meditation/medito/
- name: Sleep as Android
  rows: 19
  url: /applications/mental-health-meditation/sleep-as-android/
sitemap: true
title: 'Pixy Mood Tracker: Mental Health, Meditation & Sleep reference app'
---
