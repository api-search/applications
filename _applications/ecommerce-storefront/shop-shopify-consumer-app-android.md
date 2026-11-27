---
app: Shop (Shopify consumer app, Android)
app_slug: shop-shopify-consumer-app-android
app_url: https://play.google.com/store/apps/details?id=com.shopify.arrive
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Google Firebase (Analytics)
  url: /capabilities/analytics-bi-management/
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
category:
  id: ecommerce-storefront
  name: E-commerce Storefront
  url: /applications/ecommerce-storefront/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
integrations:
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
    mcp: &id001
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id002
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
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
  name: Google Firebase (Analytics)
  provider: firebase
  says: ships the Google Firebase (Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ecommerce-storefront/shop-shopify-consumer-app-android/
providers:
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id001
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id002
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Google Firebase (Analytics)
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
siblings:
- name: Bagisto
  rows: 8
  url: /applications/ecommerce-storefront/bagisto/
- name: Etsy (Android)
  rows: 8
  url: /applications/ecommerce-storefront/etsy-android/
- name: Medusa
  rows: 15
  url: /applications/ecommerce-storefront/medusa/
- name: Saleor
  rows: 11
  url: /applications/ecommerce-storefront/saleor/
- name: Shopify
  rows: 9
  url: /applications/ecommerce-storefront/shopify/
- name: Sylius
  rows: 4
  url: /applications/ecommerce-storefront/sylius/
- name: Vendure
  rows: 4
  url: /applications/ecommerce-storefront/vendure/
- name: WooCommerce
  rows: 3
  url: /applications/ecommerce-storefront/woocommerce/
sitemap: true
title: 'Shop (Shopify consumer app, Android): E-commerce Storefront reference app'
---
