---
app: Robinhood
app_slug: robinhood
app_url: https://robinhood.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.50
  key: AE-190.50
  layer: domain
  name: Consumer Data Access
  providers:
  - Plaid
  url: /capabilities/consumer-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Google Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.30
  key: AE-160.30
  layer: common
  name: Identity Verification
  providers:
  - Persona
  url: /capabilities/identity-verification/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  - Branch
  - Singular
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
  - Google Firebase Analytics / Crashlytics
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
  id: investing-trading
  name: Investing & Trading
  url: /applications/investing-trading/
counts:
  declared: 5
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
- route: documentation
  url: https://robinhood.com/us/en/support/articles/privacy-policy/
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: Adjust
  provider: adjust
  says: ships the Adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
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
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id003
      status: none
    slug: branch-io
    status: profiled
    tags: &id004
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
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
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
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
    mcp: &id015
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id016
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
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
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id019
      status: none
    slug: singular
    status: profiled
    tags: &id020
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: common
  name: Singular
  provider: singular
  says: ships the Singular SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id005
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id006
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: common
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://robinhood.com/us/en/support/articles/privacy-policy/
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id009
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id010
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
  source: https://robinhood.com/us/en/support/articles/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id011
      status: none
    slug: persona
    status: profiled
    tags: &id012
    - Fraud Prevention
    - Identity Verification
    - KYC
    url: /providers/persona/
  layer: common
  name: Persona
  provider: persona
  says: lists Persona as an integration
  source: https://robinhood.com/us/en/support/articles/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.1
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id013
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id014
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: lists Plaid as an integration
  source: https://robinhood.com/us/en/support/articles/privacy-policy/
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
    mcp: &id017
      status: none
    slug: apple
    status: profiled
    tags: &id018
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Sign in with Apple
  provider: apple
  says: lists Sign in with Apple as an integration
  source: https://robinhood.com/us/en/support/articles/privacy-policy/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/robinhood/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id003
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id004
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id005
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id006
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Google Firebase Analytics / Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id009
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id011
  name: Persona
  slug: persona
  status: profiled
  tags: *id012
  url: /providers/persona/
- agent_band: agent-native
  agent_readiness: 51.1
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id013
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id014
  url: /providers/plaid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id015
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id016
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id017
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id018
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id019
  name: Singular
  slug: singular
  status: profiled
  tags: *id020
  url: /providers/singular/
siblings:
- name: Freqtrade
  rows: 21
  url: /applications/investing-trading/freqtrade/
- name: Ghostfolio
  rows: 13
  url: /applications/investing-trading/ghostfolio/
- name: Kubera
  rows: 12
  url: /applications/investing-trading/kubera/
- name: Portfolio Performance
  rows: 16
  url: /applications/investing-trading/portfolio-performance/
- name: rotki
  rows: 40
  url: /applications/investing-trading/rotki/
- name: Wealthfolio
  rows: 16
  url: /applications/investing-trading/wealthfolio/
sitemap: true
title: 'Robinhood: Investing & Trading reference app'
---
