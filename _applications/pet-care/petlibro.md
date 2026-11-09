---
app: PETLIBRO
app_slug: petlibro
app_url: https://petlibro.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: common
  name: Digital & Mobile Wallets
  providers:
  - Apple Pay
  - Google Pay
  - Venmo
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: common
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.90.20
  key: AE-140.90.20
  layer: common
  name: Order Tracking
  providers:
  - AfterShip
  url: /capabilities/post-purchase/
  via_parent: Post-Purchase
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
  - Amplitude
  - Google Firebase Analytics / Crashlytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - Judge.me
  url: /capabilities/reviews-social-proof/
  via_parent: null
category:
  id: pet-care
  name: Pet Care
  url: /applications/pet-care/
counts:
  declared: 4
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
- route: integrations page
  url: https://homey.app/en-us/app/com.petlibro.petlibro/
- route: source code
  url: https://petlibro.com/pages/app
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.90.20
    key: AE-140.90.20
    name: Order Tracking
    url: /capabilities/post-purchase/
    via_parent: Post-Purchase
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 84.1
    mcp: &id001
      source: https://github.com/AfterShip/tracking-and-returns-mcp
      status: verified
    slug: aftership
    status: profiled
    tags: &id002
    - E-Commerce
    - Post-Purchase
    - Shipping
    - Tracking
    url: /providers/aftership/
  layer: common
  name: AfterShip
  provider: aftership
  says: ships the AfterShip SDK or integration code
  source: https://petlibro.com/pages/app
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id003
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
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
    agent_band: agent-ready
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id007
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id008
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
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
    mcp: &id009
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id010
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.designlibro.petlibro/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id013
      status: none
    slug: judge-me
    status: profiled
    tags: &id014
    - E-Commerce
    - Ratings
    - Reviews
    - Shopify
    url: /providers/judge-me/
  layer: common
  name: Judge.me
  provider: judge-me
  says: ships the Judge.me SDK or integration code
  source: https://petlibro.com/pages/app
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id017
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id018
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: ships the Shopify SDK or integration code
  source: https://petlibro.com/pages/app
  tier: observed
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
    mcp: &id005
      status: none
    slug: apple-pay
    status: profiled
    tags: &id006
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
  layer: common
  name: Apple Pay
  provider: apple-pay
  says: lists Apple Pay as an integration
  source: https://petlibro.com/pages/app
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
    mcp: &id011
      status: none
    slug: google-pay
    status: profiled
    tags: &id012
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: common
  name: Google Pay
  provider: google-pay
  says: lists Google Pay as an integration
  source: https://petlibro.com/pages/app
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
    mcp: &id015
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id016
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://petlibro.com/pages/app
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
    agent_band: human-only
    agent_readiness: 3.9
    band: thin
    in_catalog: true
    kin_score: 29.9
    mcp: &id019
      status: none
    slug: venmo
    status: profiled
    tags: &id020
    - Company
    - Consumer
    - Fintech
    - Payments
    url: /providers/venmo/
  layer: common
  name: Venmo
  provider: venmo
  says: lists Venmo as an integration
  source: https://petlibro.com/pages/app
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pet-care/petlibro/
providers:
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 84.1
  mcp: *id001
  name: AfterShip
  slug: aftership
  status: profiled
  tags: *id002
  url: /providers/aftership/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id003
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id004
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id005
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id006
  url: /providers/apple-pay/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id007
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id008
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id009
  name: Google Firebase Analytics / Crashlytics
  slug: firebase
  status: profiled
  tags: *id010
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id011
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id012
  url: /providers/google-pay/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id013
  name: Judge.me
  slug: judge-me
  status: profiled
  tags: *id014
  url: /providers/judge-me/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id015
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id016
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id017
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id018
  url: /providers/shopify/
- agent_band: human-only
  agent_readiness: 3.9
  band: thin
  in_catalog: true
  kin_score: 29.9
  mcp: *id019
  name: Venmo
  slug: venmo
  status: profiled
  tags: *id020
  url: /providers/venmo/
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
- name: Rover
  rows: 10
  url: /applications/pet-care/rover/
- name: Tractive
  rows: 7
  url: /applications/pet-care/tractive/
sitemap: true
title: 'PETLIBRO: Pet Care reference app'
---
