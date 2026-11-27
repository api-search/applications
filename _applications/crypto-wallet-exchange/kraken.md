---
app: Kraken
app_slug: kraken
app_url: https://www.kraken.com/
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
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - FullStory
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 2
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.kraken.invest.app/latest/
- route: documentation
  url: https://www.kraken.com/legal/privacy
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
    mcp: &id001
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id002
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kraken.invest.app/latest/
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
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kraken.invest.app/latest/
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
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id005
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id006
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
  layer: common
  name: FullStory
  provider: fullstory
  says: ships the FullStory SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kraken.invest.app/latest/
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id009
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id010
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kraken.invest.app/latest/
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
    mcp: &id007
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id008
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
  source: https://www.kraken.com/legal/privacy
  tier: declared
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id011
      status: none
    slug: apple
    status: profiled
    tags: &id012
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Sign in with Apple
  provider: apple
  says: lists Sign in with Apple as an integration
  source: https://www.kraken.com/legal/privacy
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/kraken/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id001
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id002
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id005
  name: FullStory
  slug: fullstory
  status: profiled
  tags: *id006
  url: /providers/fullstory/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id007
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id008
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id009
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id010
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id011
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id012
  url: /providers/apple/
siblings:
- name: BTCPay Server
  rows: 25
  url: /applications/crypto-wallet-exchange/btcpay-server/
- name: Coinbase
  rows: 7
  url: /applications/crypto-wallet-exchange/coinbase/
- name: Electrum
  rows: 13
  url: /applications/crypto-wallet-exchange/electrum/
- name: Ledger Live
  rows: 16
  url: /applications/crypto-wallet-exchange/ledger-live/
- name: MetaMask
  rows: 9
  url: /applications/crypto-wallet-exchange/metamask/
- name: Sparrow Wallet
  rows: 10
  url: /applications/crypto-wallet-exchange/sparrow-wallet/
- name: Unstoppable Wallet
  rows: 14
  url: /applications/crypto-wallet-exchange/unstoppable-wallet/
sitemap: true
title: 'Kraken: Crypto Wallets & Exchanges reference app'
---
