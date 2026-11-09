---
app: Fetch
app_slug: fetch
app_url: https://fetch.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - adjoe
  url: /capabilities/in-app-ad-monetisation/
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
  - Google CrashLytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Mozilla Telemetry
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - IAB Open Measurement
  url: /capabilities/programmatic-sales-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2820.10
  key: referral-management
  layer: common
  name: Referral Management
  providers:
  - Button
  url: /capabilities/referral-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: loyalty-rewards
  name: Loyalty, Rewards & Coupons
  url: /applications/loyalty-rewards/
counts:
  declared: 0
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.5
    mcp: &id002
      status: none
    slug: adjoe
    status: profiled
    tags: &id003
    - Advertising
    - Loyalty
    - Mobile Gaming
    - Monetization
    url: /providers/adjoe/
  layer: common
  name: adjoe
  provider: adjoe
  says: ships the adjoe SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
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
    mcp: &id004
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id005
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2820.10
    key: referral-management
    name: Referral Management
    url: /capabilities/referral-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id006
      status: unknown
    slug: usebutton
    status: profiled
    tags: &id007
    - Affiliates
    - Attribution
    - Commerce
    - Mobile Commerce
    url: /providers/usebutton/
  layer: common
  name: Button
  provider: usebutton
  says: ships the Button SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id008
      status: none
    slug: facebook
    status: profiled
    tags: &id009
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Login
  provider: facebook
  says: ships the Facebook Login SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id010
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id011
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id012
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id013
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
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
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id014
      source: https://github.com/mozilla/firefox-devtools-mcp
      status: verified
    slug: mozilla
    status: profiled
    tags: &id015
    - Data Engineering
    - Open Source
    - SDK
    - Telemetry
    url: /providers/mozilla/
  layer: common
  name: Mozilla Telemetry
  provider: mozilla
  says: ships the Mozilla Telemetry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.fetchrewards.fetchrewards.hop/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/loyalty-rewards/fetch/
providers:
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id002
  name: adjoe
  slug: adjoe
  status: profiled
  tags: *id003
  url: /providers/adjoe/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id004
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id005
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id006
  name: Button
  slug: usebutton
  status: profiled
  tags: *id007
  url: /providers/usebutton/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id008
  name: Facebook Login
  slug: facebook
  status: profiled
  tags: *id009
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id010
  name: Google CrashLytics
  slug: firebase
  status: profiled
  tags: *id011
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id012
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id013
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id014
  name: Mozilla Telemetry
  slug: mozilla
  status: profiled
  tags: *id015
  url: /providers/mozilla/
siblings:
- name: Honey
  rows: 5
  url: /applications/loyalty-rewards/honey/
- name: Ibotta
  rows: 11
  url: /applications/loyalty-rewards/ibotta/
- name: LoyaltyLion
  rows: 24
  url: /applications/loyalty-rewards/loyaltylion/
- name: Points and Rewards for WooCommerce (WP Swings)
  rows: 3
  url: /applications/loyalty-rewards/points-and-rewards-for-woocommerce-wp-swings/
- name: RefRef
  rows: 3
  url: /applications/loyalty-rewards/refref/
- name: Smile.io
  rows: 20
  url: /applications/loyalty-rewards/smile-io/
- name: Yotpo Loyalty & Referrals
  rows: 21
  url: /applications/loyalty-rewards/yotpo-loyalty-referrals/
sitemap: true
title: 'Fetch: Loyalty, Rewards & Coupons reference app'
---
