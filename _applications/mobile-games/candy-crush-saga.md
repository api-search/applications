---
app: Candy Crush Saga
app_slug: candy-crush-saga
app_url: https://www.king.com/game/candycrush
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Facebook login + social play
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk (King Care help centre, kingcare.zendesk.com)
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Amazon Advertisement
  - AppLovin (MAX and SparkLabs)
  - Chartboost
  - Facebook Ads
  - Google AdMob
  - ironSource
  - PubNative
  - Unity3d Ads
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook Analytics
  - Google Firebase Analytics
  - Google Analytics (websites)
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
category:
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 3
  observed: 12
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
- route: documentation
  url: https://www.king.com/cookies/
- route: documentation
  url: https://www.king.com/privacyPolicy
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
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id002
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id003
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: common
  name: Amazon Advertisement
  provider: amazon
  says: ships the Amazon Advertisement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id004
      status: none
    slug: applovin
    status: profiled
    tags: &id005
    - AdTech
    - Advertising
    - App Monetization
    - Mobile
    url: /providers/applovin/
  layer: common
  name: AppLovin (MAX and SparkLabs)
  provider: applovin
  says: ships the AppLovin (MAX and SparkLabs) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.0
    mcp: &id006
      status: none
    slug: chartboost
    status: profiled
    tags: &id007
    - Company
    url: /providers/chartboost/
  layer: common
  name: Chartboost
  provider: chartboost
  says: ships the Chartboost SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
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
  name: Facebook Ads
  provider: facebook
  says: ships the Facebook Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
  layer: domain
  name: Facebook login + social play
  provider: facebook
  says: ships the Facebook login + social play SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id010
      status: none
    slug: google-admob
    status: profiled
    tags: &id011
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    mcp: &id014
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id015
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_readiness: 36.9
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id016
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id017
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id018
      status: none
    slug: ironsource
    status: profiled
    tags: &id019
    - Advertising
    - Game Development
    - Mobile
    - Mobile Games
    url: /providers/ironsource/
  layer: common
  name: ironSource
  provider: ironsource
  says: ships the ironSource SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.8
    band: thin
    in_catalog: true
    kin_score: 32.1
    mcp: &id020
      status: unknown
    slug: pubnative
    status: profiled
    tags: &id021
    - AdTech
    - Company
    - Mobile
    - Monetization
    url: /providers/pubnative/
  layer: common
  name: PubNative
  provider: pubnative
  says: ships the PubNative SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    agent_band: agent-aware
    agent_readiness: 25.3
    band: exemplar
    in_catalog: true
    kin_score: 66.5
    mcp: &id024
      source: https://github.com/Unity-Technologies/industry-ai-workflows
      status: verified
    slug: unity
    status: profiled
    tags: &id025
    - Game Development
    - Game Services
    - Multiplayer
    - Real-Time 3D
    url: /providers/unity/
  layer: common
  name: Unity3d Ads
  provider: unity
  says: ships the Unity3d Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id012
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id013
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics (websites)
  provider: google-analytics
  says: lists Google Analytics (websites) as an integration
  source: https://www.king.com/privacyPolicy
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
    mcp: &id022
      status: none
    slug: apple
    status: profiled
    tags: &id023
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: lists Sign in with Apple as an integration
  source: https://www.king.com/privacyPolicy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id026
      status: none
    slug: zendesk
    status: profiled
    tags: &id027
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk (King Care help centre, kingcare.zendesk.com)
  provider: zendesk
  says: lists Zendesk (King Care help centre, kingcare.zendesk.com) as an integration
  source: https://www.king.com/privacyPolicy
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/candy-crush-saga/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id002
  name: Amazon Advertisement
  slug: amazon
  status: profiled
  tags: *id003
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id004
  name: AppLovin (MAX and SparkLabs)
  slug: applovin
  status: profiled
  tags: *id005
  url: /providers/applovin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.0
  mcp: *id006
  name: Chartboost
  slug: chartboost
  status: profiled
  tags: *id007
  url: /providers/chartboost/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id008
  name: Facebook Ads
  slug: facebook
  status: profiled
  tags: *id009
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id010
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id011
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id012
  name: Google Analytics (websites)
  slug: google-analytics
  status: profiled
  tags: *id013
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id014
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id015
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id016
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id017
  url: /providers/iab-tech-lab/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id018
  name: ironSource
  slug: ironsource
  status: profiled
  tags: *id019
  url: /providers/ironsource/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: thin
  in_catalog: true
  kin_score: 32.1
  mcp: *id020
  name: PubNative
  slug: pubnative
  status: profiled
  tags: *id021
  url: /providers/pubnative/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id022
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id023
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id024
  name: Unity3d Ads
  slug: unity
  status: profiled
  tags: *id025
  url: /providers/unity/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id026
  name: Zendesk (King Care help centre, kingcare.zendesk.com)
  slug: zendesk
  status: profiled
  tags: *id027
  url: /providers/zendesk/
siblings:
- name: Clash of Clans
  rows: 49
  url: /applications/mobile-games/clash-of-clans/
- name: Lichess mobile
  rows: 2
  url: /applications/mobile-games/lichess-mobile/
- name: Mindustry
  rows: 4
  url: /applications/mobile-games/mindustry/
- name: Nakama
  rows: 10
  url: /applications/mobile-games/nakama/
- name: Subway Surfers
  rows: 29
  url: /applications/mobile-games/subway-surfers/
- name: Talo
  rows: 7
  url: /applications/mobile-games/talo/
- name: Unciv
  rows: 3
  url: /applications/mobile-games/unciv/
sitemap: true
title: 'Candy Crush Saga: Mobile & Casual Games (live-ops backend) reference app'
---
