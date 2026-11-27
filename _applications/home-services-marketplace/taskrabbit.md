---
app: Taskrabbit
app_slug: taskrabbit
app_url: https://www.taskrabbit.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.50.20
  key: AE-200.50.20
  layer: domain
  name: Retail-Partner Installation & Assembly
  providers:
  - IKEA
  url: /capabilities/home-services/
  via_parent: Home Services
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
  - Bugsnag
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: home-services-marketplace
  name: Home Services Marketplaces
  url: /applications/home-services-marketplace/
counts:
  declared: 1
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
- route: documentation
  url: https://support.taskrabbit.com/hc/en-us/articles/360008913792-Taskrabbit-s-Terms-of-Service
- route: integrations page
  url: https://www.taskrabbit.com/ikea
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
    mcp: &id001
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id002
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id003
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id004
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
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
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id006
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.20
    key: AE-200.50.20
    name: Retail-Partner Installation & Assembly
    url: /capabilities/home-services/
    via_parent: Home Services
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.0
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id007
      status: none
    slug: ikea
    status: profiled
    tags: &id008
    - Consumer Products
    - Home Furnishings
    - Open Source
    - Retail
    url: /providers/ikea/
  layer: domain
  name: IKEA
  provider: ikea
  says: lists IKEA as an integration
  source: https://www.taskrabbit.com/ikea
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/home-services-marketplace/taskrabbit/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id001
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id002
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id003
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id004
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id007
  name: IKEA
  slug: ikea
  status: profiled
  tags: *id008
  url: /providers/ikea/
siblings:
- name: Angi
  rows: 0
  url: /applications/home-services-marketplace/angi/
- name: Cocorico
  rows: 7
  url: /applications/home-services-marketplace/cocorico/
- name: Housecall Pro
  rows: 15
  url: /applications/home-services-marketplace/housecall-pro/
- name: Sharetribe Go
  rows: 13
  url: /applications/home-services-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 5
  url: /applications/home-services-marketplace/sharetribe-web-template/
- name: Thumbtack
  rows: 6
  url: /applications/home-services-marketplace/thumbtack/
sitemap: true
title: 'Taskrabbit: Home Services Marketplaces reference app'
---
