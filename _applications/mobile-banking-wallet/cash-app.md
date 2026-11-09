---
app: Cash App
app_slug: cash-app
app_url: https://cash.app/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-935
  key: AE-935
  layer: domain
  name: Banking-as-a-Service & Sponsor Banks
  providers:
  - Sutton Bank
  url: /capabilities/banking-as-a-service-sponsor-banks/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.10
  key: AE-140.30.10
  layer: domain
  name: Buy Now, Pay Later
  providers:
  - Afterpay
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-1340.60
  key: card-issuance-management
  layer: domain
  name: Card Issuance Management
  providers:
  - Visa (Cash App Card)
  url: /capabilities/card-issuance-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.100
  key: AE-150.100
  layer: domain
  name: Embedded Mobile Plans & eSIM
  providers:
  - Gigs (Cash App Mobile)
  url: /capabilities/embedded-mobile-plans-esim/
  via_parent: null
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
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: mobile-banking-wallet
  name: Mobile Banking & Payments Wallet
  url: /applications/mobile-banking-wallet/
counts:
  declared: 4
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
- route: documentation
  url: https://cash.app/legal/us/en-us/privacy
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
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id003
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id004
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
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
    agent_readiness: 53.1
    band: exemplar
    in_catalog: true
    kin_score: 78.5
    mcp: &id005
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id006
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
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
    agent_band: agent-aware
    agent_readiness: 13.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id001
      status: none
    slug: afterpay
    status: profiled
    tags: &id002
    - Buy Now Pay Later
    - Consumer
    - Fintech
    - Payments
    url: /providers/afterpay/
  layer: domain
  name: Afterpay
  provider: afterpay
  says: lists Afterpay as an integration
  source: https://cash.app/legal/us/en-us/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.100
    key: AE-150.100
    name: Embedded Mobile Plans & eSIM
    url: /capabilities/embedded-mobile-plans-esim/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 44.5
    mcp: &id007
      status: none
    slug: gigs
    status: profiled
    tags: &id008
    - Company
    - Connectivity
    - Telecommunications
    - eSIM
    url: /providers/gigs/
  layer: domain
  name: Gigs (Cash App Mobile)
  provider: gigs
  says: lists Gigs (Cash App Mobile) as an integration
  source: https://cash.app/legal/us/en-us/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-935
    key: AE-935
    name: Banking-as-a-Service & Sponsor Banks
    url: /capabilities/banking-as-a-service-sponsor-banks/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id011
      status: unknown
    slug: sutton-bank
    status: profiled
    tags: &id012
    - Banking
    - Community Bank
    - Financial Services
    - Ohio
    url: /providers/sutton-bank/
  layer: domain
  name: Sutton Bank
  provider: sutton-bank
  says: lists Sutton Bank as an integration
  source: https://cash.app/legal/us/en-us/privacy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.60
    key: card-issuance-management
    name: Card Issuance Management
    url: /capabilities/card-issuance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.4
    band: developing
    in_catalog: true
    kin_score: 44.2
    mcp: &id013
      source: https://github.com/visa/ai
      status: verified
    slug: visa
    status: profiled
    tags: &id014
    - Account
    - Banking
    - Credit Cards
    - Visa
    url: /providers/visa/
  layer: domain
  name: Visa (Cash App Card)
  provider: visa
  says: lists Visa (Cash App Card) as an integration
  source: https://cash.app/legal/us/en-us/privacy
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-banking-wallet/cash-app/
providers:
- agent_band: agent-aware
  agent_readiness: 13.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id001
  name: Afterpay
  slug: afterpay
  status: profiled
  tags: *id002
  url: /providers/afterpay/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id003
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id004
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 53.1
  band: exemplar
  in_catalog: true
  kin_score: 78.5
  mcp: *id005
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id006
  url: /providers/bugsnag/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 44.5
  mcp: *id007
  name: Gigs (Cash App Mobile)
  slug: gigs
  status: profiled
  tags: *id008
  url: /providers/gigs/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id009
  name: Google Firebase Analytics
  slug: firebase
  status: profiled
  tags: *id010
  url: /providers/firebase/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id011
  name: Sutton Bank
  slug: sutton-bank
  status: profiled
  tags: *id012
  url: /providers/sutton-bank/
- agent_band: agent-ready
  agent_readiness: 45.4
  band: developing
  in_catalog: true
  kin_score: 44.2
  mcp: *id013
  name: Visa (Cash App Card)
  slug: visa
  status: profiled
  tags: *id014
  url: /providers/visa/
siblings:
- name: Mifos Mobile (openMF mifos-mobile)
  rows: 6
  url: /applications/mobile-banking-wallet/mifos-mobile-openmf-mifos-mobile/
- name: Mifos Pay (openMF mobile-wallet)
  rows: 5
  url: /applications/mobile-banking-wallet/mifos-pay-openmf-mobile-wallet/
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
title: 'Cash App: Mobile Banking & Payments Wallet reference app'
---
