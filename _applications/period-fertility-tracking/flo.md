---
app: Flo
app_slug: flo
app_url: https://flo.health/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20.10
  key: AE-130.20.10
  layer: domain
  name: Wearable Data Aggregation
  providers:
  - Apple
  - Google
  url: /capabilities/wearable-health-data-sync/
  via_parent: Wearable & Health Data Sync
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
  - AppsFlyer
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
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: period-fertility-tracking
  name: Period, Fertility & Pregnancy Tracking
  url: /applications/period-fertility-tracking/
counts:
  declared: 2
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id003
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id004
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id009
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id010
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id011
      status: none
    slug: zendesk
    status: profiled
    tags: &id012
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id005
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id006
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google
  provider: google
  says: lists Google as an integration
  source: https://help.flo.health/hc/en-us/search?query=apple+health
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/period-fertility-tracking/flo/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id003
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id004
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id005
  name: Google
  slug: google
  status: profiled
  tags: *id006
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id009
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id010
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id011
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id012
  url: /providers/zendesk/
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
title: 'Flo: Period, Fertility & Pregnancy Tracking reference app'
---
