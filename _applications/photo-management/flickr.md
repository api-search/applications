---
app: Flickr
app_slug: flickr
app_url: https://www.flickr.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3770.50
  key: audience-insights-research-management
  layer: common
  name: Audience Insights & Research Management
  providers:
  - google-admob
  url: /capabilities/audience-insights-research-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - firebase
  - flurry
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - facebook
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: facebook
  provider: facebook
  says: ships the facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id004
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: firebase
  provider: firebase
  says: ships the firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id005
      status: none
    slug: flurry
    status: profiled
    tags: &id006
    - Analytics
    - Company
    - Mobile
    - SDK
    url: /providers/flurry/
  layer: common
  name: flurry
  provider: flurry
  says: ships the flurry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3770.50
    key: audience-insights-research-management
    name: Audience Insights & Research Management
    url: /capabilities/audience-insights-research-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id007
      status: none
    slug: google-admob
    status: profiled
    tags: &id008
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: google-admob
  provider: google-admob
  says: ships the google-admob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/flickr/
providers:
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id001
  name: facebook
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id003
  name: firebase
  slug: firebase
  status: profiled
  tags: *id004
  url: /providers/firebase/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id005
  name: flurry
  slug: flurry
  status: profiled
  tags: *id006
  url: /providers/flurry/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id007
  name: google-admob
  slug: google-admob
  status: profiled
  tags: *id008
  url: /providers/google-admob/
siblings:
- name: Amazon Photos
  rows: 2
  url: /applications/photo-management/amazon-photos/
- name: Apple Photos
  rows: 0
  url: /applications/photo-management/apple-photos/
- name: Ente Photos
  rows: 7
  url: /applications/photo-management/ente-photos/
- name: Google Photos
  rows: 1
  url: /applications/photo-management/google-photos/
- name: Immich
  rows: 1
  url: /applications/photo-management/immich/
- name: LibrePhotos
  rows: 6
  url: /applications/photo-management/librephotos/
- name: Lychee
  rows: 19
  url: /applications/photo-management/lychee/
- name: Nextcloud Memories
  rows: 1
  url: /applications/photo-management/nextcloud-memories/
- name: PhotoPrism
  rows: 1
  url: /applications/photo-management/photoprism/
- name: Piwigo
  rows: 0
  url: /applications/photo-management/piwigo/
sitemap: true
title: 'Flickr: Photo & Video Library Management reference app'
---
