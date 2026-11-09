---
app: Ibotta
app_slug: ibotta
app_url: https://home.ibotta.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-920
  key: AE-920
  layer: common
  name: Barcode, RFID & Mobile Data Capture
  providers:
  - Scandit
  url: /capabilities/storage-and-inventory-operations-management/
  via_parent: Storage and Inventory Operations Management
- attribution: API Evangelist extension
  id: AE-120.50
  key: AE-120.50
  layer: common
  name: Device & IP Location
  providers:
  - Radar
  url: /capabilities/device-ip-location/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  - Tapjoy
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook Analytics
  - Google Firebase Analytics
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
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Huawei Mobile Services (HMS) Core
  url: /capabilities/push-notifications/
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
  - Facebook Login / Share
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: loyalty-rewards
  name: Loyalty, Rewards & Coupons
  url: /applications/loyalty-rewards/
counts:
  declared: 0
  observed: 11
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
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
    mcp: &id004
      status: unknown
    slug: usebutton
    status: profiled
    tags: &id005
    - Affiliates
    - Attribution
    - Commerce
    - Mobile Commerce
    url: /providers/usebutton/
  layer: common
  name: Button
  provider: usebutton
  says: ships the Button SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id006
      status: none
    slug: facebook
    status: profiled
    tags: &id007
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook Login / Share
  provider: facebook
  says: ships the Facebook Login / Share SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id008
      status: none
    slug: google-admob
    status: profiled
    tags: &id009
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id012
      status: unchecked
    slug: huawei-mobile-services
    status: queued for profiling
    tags: &id013 []
    url: null
  layer: common
  name: Huawei Mobile Services (HMS) Core
  provider: huawei-mobile-services
  says: ships the Huawei Mobile Services (HMS) Core SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
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
    mcp: &id014
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id015
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50
    key: AE-120.50
    name: Device & IP Location
    url: /capabilities/device-ip-location/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id016
      status: unchecked
    slug: radar-io
    status: profiled
    tags: &id017
    - Geocoding
    - Geofencing
    - Location
    - Maps
    url: /providers/radar-io/
  layer: common
  name: Radar
  provider: radar-io
  says: ships the Radar SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-920
    key: AE-920
    name: Barcode, RFID & Mobile Data Capture
    url: /capabilities/storage-and-inventory-operations-management/
    via_parent: Storage and Inventory Operations Management
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 6.1
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id018
      source: https://ssl.scandit.com/mcp
      status: verified
    slug: scandit
    status: profiled
    tags: &id019
    - Barcode Scanning
    - Company
    - Data Capture
    - Frontier Tech
    url: /providers/scandit/
  layer: common
  name: Scandit
  provider: scandit
  says: ships the Scandit SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id020
      status: unchecked
    slug: tapjoy
    status: queued for profiling
    tags: &id021 []
    url: null
  layer: common
  name: Tapjoy
  provider: tapjoy
  says: ships the Tapjoy SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ibotta.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/loyalty-rewards/ibotta/
providers:
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id002
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id003
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id004
  name: Button
  slug: usebutton
  status: profiled
  tags: *id005
  url: /providers/usebutton/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id006
  name: Facebook Analytics
  slug: facebook
  status: profiled
  tags: *id007
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id008
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id009
  url: /providers/google-admob/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id010
  name: Google Firebase Analytics
  slug: firebase
  status: profiled
  tags: *id011
  url: /providers/firebase/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id012
  name: Huawei Mobile Services (HMS) Core
  slug: huawei-mobile-services
  status: queued for profiling
  tags: *id013
  url: null
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id014
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id015
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id016
  name: Radar
  slug: radar-io
  status: profiled
  tags: *id017
  url: /providers/radar-io/
- agent_band: agent-aware
  agent_readiness: 6.1
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id018
  name: Scandit
  slug: scandit
  status: profiled
  tags: *id019
  url: /providers/scandit/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id020
  name: Tapjoy
  slug: tapjoy
  status: queued for profiling
  tags: *id021
  url: null
siblings:
- name: Fetch
  rows: 8
  url: /applications/loyalty-rewards/fetch/
- name: Honey
  rows: 5
  url: /applications/loyalty-rewards/honey/
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
title: 'Ibotta: Loyalty, Rewards & Coupons reference app'
---
