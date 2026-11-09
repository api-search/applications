---
app: Google Analytics
app_slug: google-analytics
app_url: https://analytics.google.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Google BigQuery
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3770.30
  key: content-performance-analytics
  layer: domain
  name: Content Performance Analytics
  providers:
  - Google Search Console
  url: /capabilities/content-performance-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Google Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Firebase (Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 3
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.giant/latest/
- route: documentation
  url: https://developers.google.com/analytics/devguides/MCP
- route: documentation
  url: https://support.google.com/analytics/answer/10737381
- route: documentation
  url: https://support.google.com/analytics/answer/9379420
- route: documentation
  url: https://support.google.com/analytics/answer/9823238
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id002
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: domain
  name: Firebase (Analytics)
  provider: firebase
  says: ships the Firebase (Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.giant/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id003
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id004
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://support.google.com/analytics/answer/9379420
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id005
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id006
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://support.google.com/analytics/answer/9823238
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3770.30
    key: content-performance-analytics
    name: Content Performance Analytics
    url: /capabilities/content-performance-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id007
      status: none
    slug: google-search-console
    status: profiled
    tags: &id008
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
  layer: domain
  name: Google Search Console
  provider: google-search-console
  says: lists Google Search Console as an integration
  source: https://support.google.com/analytics/answer/10737381
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/google-analytics/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id001
  name: Firebase (Analytics)
  slug: firebase
  status: profiled
  tags: *id002
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id003
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id004
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id005
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id006
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id007
  name: Google Search Console
  slug: google-search-console
  status: profiled
  tags: *id008
  url: /providers/google-search-console/
siblings:
- name: Amplitude
  rows: 50
  url: /applications/web-analytics/amplitude/
- name: Matomo
  rows: 18
  url: /applications/web-analytics/matomo/
- name: Mixpanel
  rows: 12
  url: /applications/web-analytics/mixpanel/
- name: Plausible
  rows: 16
  url: /applications/web-analytics/plausible/
- name: PostHog
  rows: 42
  url: /applications/web-analytics/posthog/
- name: Umami
  rows: 4
  url: /applications/web-analytics/umami/
sitemap: true
title: 'Google Analytics: Web & Product Analytics reference app'
---
