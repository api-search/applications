---
app: Rightmove
app_slug: rightmove
app_url: https://www.rightmove.co.uk/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics)
  - Instabug (Luciq)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Comscore
  - Google Analytics
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
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
  id: real-estate-home-search
  name: Real Estate & Home Search
  url: /applications/real-estate-home-search/
counts:
  declared: 0
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
- route: documentation
  url: https://www.rightmove.co.uk/adf.html
integrations:
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
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id002
      status: none
    slug: comscore
    status: profiled
    tags: &id003
    - Audience Analytics
    - Cloud Saas
    - Company
    - Media Measurement
    url: /providers/comscore/
  layer: common
  name: Comscore
  provider: comscore
  says: ships the Comscore SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id005
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id006
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id007
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id008
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id009
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
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
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id010
      source: https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features.md
      status: documented
    slug: instabug
    status: profiled
    tags: &id011
    - AI Agents
    - APM
    - Application Performance Monitoring
    - Bug Reporting
    url: /providers/instabug/
  layer: common
  name: Instabug (Luciq)
  provider: instabug
  says: ships the Instabug (Luciq) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.rightmove.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/real-estate-home-search/rightmove/
providers:
- agent_band: agent-aware
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id002
  name: Comscore
  slug: comscore
  status: profiled
  tags: *id003
  url: /providers/comscore/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id004
  name: Firebase (Crashlytics)
  slug: firebase
  status: profiled
  tags: *id005
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id006
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id007
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id008
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id009
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id010
  name: Instabug (Luciq)
  slug: instabug
  status: profiled
  tags: *id011
  url: /providers/instabug/
siblings:
- name: Flathunter
  rows: 16
  url: /applications/real-estate-home-search/flathunter/
- name: HomeHarvest
  rows: 1
  url: /applications/real-estate-home-search/homeharvest/
- name: Real Geeks
  rows: 10
  url: /applications/real-estate-home-search/real-geeks/
- name: Realtor.com
  rows: 13
  url: /applications/real-estate-home-search/realtor-com/
- name: Redfin
  rows: 13
  url: /applications/real-estate-home-search/redfin/
- name: Zillow
  rows: 14
  url: /applications/real-estate-home-search/zillow/
sitemap: true
title: 'Rightmove: Real Estate & Home Search reference app'
---
