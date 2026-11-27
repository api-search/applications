---
app: Poshmark
app_slug: poshmark
app_url: https://poshmark.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  - Visual Studio App Center Crashes
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook
  - Firebase
  - Google Analytics
  - Visual Studio App Center Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: resale-marketplace
  name: Resale & Second-hand Marketplaces
  url: /applications/resale-marketplace/
counts:
  declared: 0
  observed: 11
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    mcp: &id004
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id005
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
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
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id006
      status: none
    slug: branch-io
    status: profiled
    tags: &id007
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    mcp: &id008
      status: none
    slug: facebook
    status: profiled
    tags: &id009
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id010
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id011
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id012
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id013
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id014
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id015
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id003
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id016
      status: unchecked
    slug: microsoft-app-center
    status: queued for profiling
    tags: &id017 []
    url: null
  layer: common
  name: Visual Studio App Center Analytics
  provider: microsoft-app-center
  says: ships the Visual Studio App Center Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id003
  layer: common
  name: Visual Studio App Center Crashes
  provider: microsoft-app-center
  says: ships the Visual Studio App Center Crashes SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/resale-marketplace/poshmark/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id004
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id005
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id006
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id007
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id008
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id009
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id010
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id011
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id012
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id013
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id014
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id015
  url: /providers/google-tag-manager/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id016
  name: Visual Studio App Center Analytics
  slug: microsoft-app-center
  status: queued for profiling
  tags: *id017
  url: null
siblings:
- name: Cocorico
  rows: 5
  url: /applications/resale-marketplace/cocorico/
- name: Depop
  rows: 6
  url: /applications/resale-marketplace/depop/
- name: Mercari
  rows: 9
  url: /applications/resale-marketplace/mercari/
- name: Sharetribe (hosted)
  rows: 11
  url: /applications/resale-marketplace/sharetribe-hosted/
- name: Sharetribe Go
  rows: 11
  url: /applications/resale-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 6
  url: /applications/resale-marketplace/sharetribe-web-template/
- name: Vinted
  rows: 25
  url: /applications/resale-marketplace/vinted/
sitemap: true
title: 'Poshmark: Resale & Second-hand Marketplaces reference app'
---
