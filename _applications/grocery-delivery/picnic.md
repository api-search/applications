---
app: Picnic
app_slug: picnic
app_url: https://picnic.app/
author: API Evangelist
capabilities:
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
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Snowplow
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: grocery-delivery
  name: Grocery Delivery
  url: /applications/grocery-delivery/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.picnic.android
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
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
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id004
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
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
    agent_band: agent-aware
    agent_readiness: 20.1
    band: developing
    in_catalog: true
    kin_score: 42.3
    mcp: &id007
      source: https://github.com/snowplow/snowplow-cli
      status: verified
    slug: snowplow
    status: profiled
    tags: &id008
    - Analytics Platform
    - Behavioral Data
    - Data Collection
    - Data Engineering
    url: /providers/snowplow/
  layer: common
  name: Snowplow
  provider: snowplow
  says: ships the Snowplow SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/grocery-delivery/picnic/
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
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
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
- agent_band: agent-aware
  agent_readiness: 20.1
  band: developing
  in_catalog: true
  kin_score: 42.3
  mcp: *id007
  name: Snowplow
  slug: snowplow
  status: profiled
  tags: *id008
  url: /providers/snowplow/
siblings:
- name: Ever Demand
  rows: 12
  url: /applications/grocery-delivery/ever-demand/
- name: Grocy
  rows: 1
  url: /applications/grocery-delivery/grocy/
- name: Instacart
  rows: 8
  url: /applications/grocery-delivery/instacart/
- name: Open Food Network
  rows: 8
  url: /applications/grocery-delivery/open-food-network/
- name: Shipt
  rows: 5
  url: /applications/grocery-delivery/shipt/
- name: Weee!
  rows: 7
  url: /applications/grocery-delivery/weee/
sitemap: true
title: 'Picnic: Grocery Delivery reference app'
---
