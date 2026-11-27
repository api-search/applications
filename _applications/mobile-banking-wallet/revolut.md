---
app: Revolut
app_slug: revolut
app_url: https://www.revolut.com/
author: API Evangelist
capabilities:
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
  - Firebase Crashlytics
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
  id: mobile-banking-wallet
  name: Mobile Banking & Payments Wallet
  url: /applications/mobile-banking-wallet/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
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
    mcp: &id002
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id003
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
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
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id005
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-banking-wallet/revolut/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id002
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id003
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id004
  name: Firebase Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id005
  url: /providers/google-firebase/
siblings:
- name: Cash App
  rows: 7
  url: /applications/mobile-banking-wallet/cash-app/
- name: Mifos Mobile (openMF mifos-mobile)
  rows: 6
  url: /applications/mobile-banking-wallet/mifos-mobile-openmf-mifos-mobile/
- name: Mifos Pay (openMF mobile-wallet)
  rows: 5
  url: /applications/mobile-banking-wallet/mifos-pay-openmf-mobile-wallet/
- name: PayPal
  rows: 3
  url: /applications/mobile-banking-wallet/paypal/
- name: Wise
  rows: 15
  url: /applications/mobile-banking-wallet/wise/
sitemap: true
title: 'Revolut: Mobile Banking & Payments Wallet reference app'
---
