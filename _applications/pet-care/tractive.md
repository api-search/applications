---
app: Tractive
app_slug: tractive
app_url: https://tractive.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Homey (Athom / LG)
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.10
  key: AE-140.30.10
  layer: common
  name: Buy Now, Pay Later
  providers:
  - Affirm
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: common
  name: Digital & Mobile Wallets
  providers:
  - Apple Pay
  - Google Pay
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics / Crashlytics
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
  id: pet-care
  name: Pet Care
  url: /applications/pet-care/
counts:
  declared: 5
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.tractive.android.gps/latest/
- route: documentation
  url: https://tractive.com/blog/en/tech/do-pet-trackers-integrate-with-smart-home-devices
- route: source code
  url: https://tractive.com/en-us
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
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id006
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tractive.android.gps/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id009
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id010
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://tractive.com/en-us
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id001
      status: none
    slug: affirm
    status: profiled
    tags: &id002
    - Buy Now Pay Later
    - Fintech
    - Lending
    - Payments
    url: /providers/affirm/
  layer: common
  name: Affirm
  provider: affirm
  says: lists Affirm as an integration
  source: https://tractive.com/en-us
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id003
      status: none
    slug: apple-pay
    status: profiled
    tags: &id004
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
  layer: common
  name: Apple Pay
  provider: apple-pay
  says: lists Apple Pay as an integration
  source: https://tractive.com/en-us
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 66.2
    mcp: &id007
      status: none
    slug: google-pay
    status: profiled
    tags: &id008
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: common
  name: Google Pay
  provider: google-pay
  says: lists Google Pay as an integration
  source: https://tractive.com/en-us
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: homey
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: Homey (Athom / LG)
  provider: homey
  says: lists Homey (Athom / LG) as an integration
  source: https://tractive.com/blog/en/tech/do-pet-trackers-integrate-with-smart-home-devices
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id013
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id014
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://tractive.com/en-us
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pet-care/tractive/
providers:
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id001
  name: Affirm
  slug: affirm
  status: profiled
  tags: *id002
  url: /providers/affirm/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id003
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id004
  url: /providers/apple-pay/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id005
  name: Google Firebase Analytics / Crashlytics
  slug: firebase
  status: profiled
  tags: *id006
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id007
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id008
  url: /providers/google-pay/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id009
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id010
  url: /providers/google-tag-manager/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Homey (Athom / LG)
  slug: homey
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id013
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id014
  url: /providers/paypal/
siblings:
- name: Chewy
  rows: 4
  url: /applications/pet-care/chewy/
- name: Fi Smart Collar
  rows: 4
  url: /applications/pet-care/fi-smart-collar/
- name: oh-my-petcare
  rows: 2
  url: /applications/pet-care/oh-my-petcare/
- name: PawSome AI
  rows: 2
  url: /applications/pet-care/pawsome-ai/
- name: PetDesk
  rows: 10
  url: /applications/pet-care/petdesk/
- name: PETLIBRO
  rows: 10
  url: /applications/pet-care/petlibro/
- name: Rover
  rows: 10
  url: /applications/pet-care/rover/
sitemap: true
title: 'Tractive: Pet Care reference app'
---
