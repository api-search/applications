---
app: Subway Surfers
app_slug: subway-surfers
app_url: https://sybogames.com/games/subway-surfers/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Facebook login
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Helpshift
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
  - Appodeal Stack
  - BidMachine
  - Chartboost
  - Facebook Ads
  - Fyber
  - Google AdMob
  - InMobi
  - ironSource LevelPlay (mediation)
  - Mintegral
  - Pangle (ByteDance)
  - PubNative
  - SuperAwesome
  - Unity3d Ads
  - Google Ad Manager (mediation)
  - maio
  - Moloco
  - myTarget
  - Smaato
  - Tapjoy
  - Yandex Ads
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Singular
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
  - Facebook Analytics
  - Firebase Analytics
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
  declared: 7
  observed: 22
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
- route: documentation
  url: https://sybogames.com/privacy-policy/
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
    mcp: &id003
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id004
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: common
  name: Amazon Advertisement
  provider: amazon
  says: ships the Amazon Advertisement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id005
      status: none
    slug: applovin
    status: profiled
    tags: &id006
    - AdTech
    - Advertising
    - App Monetization
    - Mobile
    url: /providers/applovin/
  layer: common
  name: AppLovin (MAX and SparkLabs)
  provider: applovin
  says: ships the AppLovin (MAX and SparkLabs) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    agent_readiness: 28.5
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id007
      status: none
    slug: appodeal
    status: profiled
    tags: &id008
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/appodeal/
  layer: common
  name: Appodeal Stack
  provider: appodeal
  says: ships the Appodeal Stack SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    agent_readiness: 31.0
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id009
      status: none
    slug: bidmachine-io
    status: profiled
    tags: &id010
    - Ad Exchange
    - AdTech
    - Advertising
    - Mobile Advertising
    url: /providers/bidmachine-io/
  layer: common
  name: BidMachine
  provider: bidmachine-io
  says: ships the BidMachine SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id011
      status: none
    slug: chartboost
    status: profiled
    tags: &id012
    - Company
    url: /providers/chartboost/
  layer: common
  name: Chartboost
  provider: chartboost
  says: ships the Chartboost SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id013
      status: none
    slug: facebook
    status: profiled
    tags: &id014
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Ads
  provider: facebook
  says: ships the Facebook Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
  name: Facebook login
  provider: facebook
  says: ships the Facebook login SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id015
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id016
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id017
      status: unchecked
    slug: fyber
    status: queued for profiling
    tags: &id018 []
    url: null
  layer: domain
  name: Fyber
  provider: fyber
  says: ships the Fyber SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id021
      status: none
    slug: google-admob
    status: profiled
    tags: &id022
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: helpshift
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: common
  name: Helpshift
  provider: helpshift
  says: ships the Helpshift SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id025
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id026
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    agent_readiness: 7.7
    band: developing
    in_catalog: true
    kin_score: 46.1
    mcp: &id027
      status: none
    slug: inmobi
    status: profiled
    tags: &id028
    - AdTech
    - Advertising
    - Company
    - Enterprise
    url: /providers/inmobi/
  layer: domain
  name: InMobi
  provider: inmobi
  says: ships the InMobi SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id029
      status: none
    slug: ironsource
    status: profiled
    tags: &id030
    - Advertising
    - Game Development
    - Mobile
    - Mobile Games
    url: /providers/ironsource/
  layer: domain
  name: ironSource LevelPlay (mediation)
  provider: ironsource
  says: ships the ironSource LevelPlay (mediation) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    band: emerging
    in_catalog: true
    kin_score: 16.2
    mcp: &id033
      status: unknown
    slug: mintegral
    status: profiled
    tags: &id034
    - Advertising
    - Artificial Intelligence
    - Company
    - Mobile Marketing
    url: /providers/mintegral/
  layer: domain
  name: Mintegral
  provider: mintegral
  says: ships the Mintegral SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id039
      status: none
    slug: pangle
    status: profiled
    tags: &id040
    - Advertising
    - Mobile
    - Monetization
    - TikTok
    url: /providers/pangle/
  layer: domain
  name: Pangle (ByteDance)
  provider: pangle
  says: ships the Pangle (ByteDance) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id041
      status: unknown
    slug: pubnative
    status: profiled
    tags: &id042
    - AdTech
    - Company
    - Mobile
    - Monetization
    url: /providers/pubnative/
  layer: common
  name: PubNative
  provider: pubnative
  says: ships the PubNative SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id043
      status: none
    slug: singular
    status: profiled
    tags: &id044
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: common
  name: Singular
  provider: singular
  says: ships the Singular SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id047
      status: unchecked
    slug: superawesome
    status: queued for profiling
    tags: &id048 []
    url: null
  layer: common
  name: SuperAwesome
  provider: superawesome
  says: ships the SuperAwesome SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    mcp: &id051
      source: https://github.com/Unity-Technologies/industry-ai-workflows
      status: verified
    slug: unity
    status: profiled
    tags: &id052
    - Game Development
    - Game Services
    - Multiplayer
    - Real-Time 3D
    url: /providers/unity/
  layer: common
  name: Unity3d Ads
  provider: unity
  says: ships the Unity3d Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 56.4
    mcp: &id019
      source: https://developers.google.com/ad-manager/api/beta/mcp-server
      status: verified
    slug: google-ad-manager
    status: profiled
    tags: &id020
    - Ad Manager
    - Ad Operations
    - Ad Serving
    - Creative
    url: /providers/google-ad-manager/
  layer: domain
  name: Google Ad Manager (mediation)
  provider: google-ad-manager
  says: lists Google Ad Manager (mediation) as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.7
    mcp: &id031
      status: none
    slug: maio
    status: profiled
    tags: &id032
    - Company
    url: /providers/maio/
  layer: domain
  name: maio
  provider: maio
  says: lists maio as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.8
    band: exemplar
    in_catalog: true
    kin_score: 71.5
    mcp: &id035
      source: https://developer.moloco.cloud/docs/mcp-getting-started
      status: verified
    slug: moloco
    status: profiled
    tags: &id036
    - AdTech
    - Advertising
    - DSP
    - Retail Media
    url: /providers/moloco/
  layer: domain
  name: Moloco
  provider: moloco
  says: lists Moloco as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: mytarget
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: domain
  name: myTarget
  provider: mytarget
  says: lists myTarget as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id045
      status: unchecked
    slug: smaato
    status: queued for profiling
    tags: &id046 []
    url: null
  layer: domain
  name: Smaato
  provider: smaato
  says: lists Smaato as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id049
      status: unchecked
    slug: tapjoy
    status: queued for profiling
    tags: &id050 []
    url: null
  layer: domain
  name: Tapjoy
  provider: tapjoy
  says: lists Tapjoy as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id053
      status: none
    slug: yandex-ads
    status: profiled
    tags: &id054
    - Advertising
    - App Monetization
    - User Acquisition
    - Web Analytics
    url: /providers/yandex-ads/
  layer: domain
  name: Yandex Ads
  provider: yandex-ads
  says: lists Yandex Ads as an integration
  source: https://sybogames.com/privacy-policy/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/subway-surfers/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id003
  name: Amazon Advertisement
  slug: amazon
  status: profiled
  tags: *id004
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id005
  name: AppLovin (MAX and SparkLabs)
  slug: applovin
  status: profiled
  tags: *id006
  url: /providers/applovin/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id007
  name: Appodeal Stack
  slug: appodeal
  status: profiled
  tags: *id008
  url: /providers/appodeal/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id009
  name: BidMachine
  slug: bidmachine-io
  status: profiled
  tags: *id010
  url: /providers/bidmachine-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.0
  mcp: *id011
  name: Chartboost
  slug: chartboost
  status: profiled
  tags: *id012
  url: /providers/chartboost/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id013
  name: Facebook Ads
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id015
  name: Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id016
  url: /providers/google-firebase/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id017
  name: Fyber
  slug: fyber
  status: queued for profiling
  tags: *id018
  url: null
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 56.4
  mcp: *id019
  name: Google Ad Manager (mediation)
  slug: google-ad-manager
  status: profiled
  tags: *id020
  url: /providers/google-ad-manager/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id021
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id022
  url: /providers/google-admob/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: Helpshift
  slug: helpshift
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id025
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id026
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id027
  name: InMobi
  slug: inmobi
  status: profiled
  tags: *id028
  url: /providers/inmobi/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id029
  name: ironSource LevelPlay (mediation)
  slug: ironsource
  status: profiled
  tags: *id030
  url: /providers/ironsource/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.7
  mcp: *id031
  name: maio
  slug: maio
  status: profiled
  tags: *id032
  url: /providers/maio/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id033
  name: Mintegral
  slug: mintegral
  status: profiled
  tags: *id034
  url: /providers/mintegral/
- agent_band: agent-native
  agent_readiness: 57.8
  band: exemplar
  in_catalog: true
  kin_score: 71.5
  mcp: *id035
  name: Moloco
  slug: moloco
  status: profiled
  tags: *id036
  url: /providers/moloco/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: myTarget
  slug: mytarget
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id039
  name: Pangle (ByteDance)
  slug: pangle
  status: profiled
  tags: *id040
  url: /providers/pangle/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: thin
  in_catalog: true
  kin_score: 32.1
  mcp: *id041
  name: PubNative
  slug: pubnative
  status: profiled
  tags: *id042
  url: /providers/pubnative/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id043
  name: Singular
  slug: singular
  status: profiled
  tags: *id044
  url: /providers/singular/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id045
  name: Smaato
  slug: smaato
  status: queued for profiling
  tags: *id046
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id047
  name: SuperAwesome
  slug: superawesome
  status: queued for profiling
  tags: *id048
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id049
  name: Tapjoy
  slug: tapjoy
  status: queued for profiling
  tags: *id050
  url: null
- agent_band: agent-aware
  agent_readiness: 25.3
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id051
  name: Unity3d Ads
  slug: unity
  status: profiled
  tags: *id052
  url: /providers/unity/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id053
  name: Yandex Ads
  slug: yandex-ads
  status: profiled
  tags: *id054
  url: /providers/yandex-ads/
siblings:
- name: Candy Crush Saga
  rows: 15
  url: /applications/mobile-games/candy-crush-saga/
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
- name: Talo
  rows: 7
  url: /applications/mobile-games/talo/
- name: Unciv
  rows: 3
  url: /applications/mobile-games/unciv/
sitemap: true
title: 'Subway Surfers: Mobile & Casual Games (live-ops backend) reference app'
---
