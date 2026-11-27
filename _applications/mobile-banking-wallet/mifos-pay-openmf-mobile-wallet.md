---
app: Mifos Pay (openMF mobile-wallet)
app_slug: mifos-pay-openmf-mobile-wallet
app_url: https://github.com/openMF/mobile-wallet
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-936
  key: AE-936
  layer: domain
  name: Core Banking Platforms
  providers:
  - Apache Fineract (Mifos platform)
  url: /capabilities/core-banking-platforms/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics + Performance
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4270.70
  key: software-marketplace-listing-management
  layer: common
  name: Software Marketplace Listing Management
  providers:
  - Google Play (Integrity, In-App Review, In-App Update)
  url: /capabilities/software-marketplace-listing-management/
  via_parent: null
category:
  id: mobile-banking-wallet
  name: Mobile Banking & Payments Wallet
  url: /applications/mobile-banking-wallet/
counts:
  declared: 1
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
- route: documentation
  url: https://github.com/openMF/mobile-wallet
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
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
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Crashlytics + Performance
  provider: firebase
  says: ships the Firebase Crashlytics + Performance SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id006
      status: none
    slug: google-play
    status: profiled
    tags: &id007
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play (Integrity, In-App Review, In-App Update)
  provider: google-play
  says: ships the Google Play (Integrity, In-App Review, In-App Update) SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id008
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id009
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-936
    key: AE-936
    name: Core Banking Platforms
    url: /capabilities/core-banking-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.1
    mcp: &id002
      status: none
    slug: apache-fineract
    status: profiled
    tags: &id003
    - Banking
    - Company
    - Fintech
    - Open Source
    url: /providers/apache-fineract/
  layer: domain
  name: Apache Fineract (Mifos platform)
  provider: apache-fineract
  says: lists Apache Fineract (Mifos platform) as an integration
  source: https://github.com/openMF/mobile-wallet
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-banking-wallet/mifos-pay-openmf-mobile-wallet/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.1
  mcp: *id002
  name: Apache Fineract (Mifos platform)
  slug: apache-fineract
  status: profiled
  tags: *id003
  url: /providers/apache-fineract/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id004
  name: Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id005
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id006
  name: Google Play (Integrity, In-App Review, In-App Update)
  slug: google-play
  status: profiled
  tags: *id007
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id008
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id009
  url: /providers/google-identity-platform/
siblings:
- name: Cash App
  rows: 7
  url: /applications/mobile-banking-wallet/cash-app/
- name: Mifos Mobile (openMF mifos-mobile)
  rows: 6
  url: /applications/mobile-banking-wallet/mifos-mobile-openmf-mifos-mobile/
- name: PayPal
  rows: 3
  url: /applications/mobile-banking-wallet/paypal/
- name: Revolut
  rows: 3
  url: /applications/mobile-banking-wallet/revolut/
- name: Wise
  rows: 15
  url: /applications/mobile-banking-wallet/wise/
sitemap: true
title: 'Mifos Pay (openMF mobile-wallet): Mobile Banking & Payments Wallet reference app'
---
