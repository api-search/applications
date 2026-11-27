---
app: Vinted
app_slug: vinted
app_url: https://www.vinted.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - mParticle
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - AdColony
  - Amazon
  - AppLovin
  - BidMachine
  - Chartboost
  - Digital Turbine (Fyber)
  - Facebook
  - Google AdMob
  - InMobi
  - ironSource
  - Mintegral
  - myTarget
  - Pangle
  - PubMatic
  - PubNative
  - Unity
  - Yandex Ads
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - IAB Open Measurement
  - Prebid Mobile
  url: /capabilities/programmatic-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: resale-marketplace
  name: Resale & Second-hand Marketplaces
  url: /applications/resale-marketplace/
counts:
  declared: 0
  observed: 25
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    agent_band: agent-aware
    agent_readiness: 19.4
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id003
      status: none
    slug: adcolony
    status: profiled
    tags: &id004
    - AdTech
    - Advertising
    - Company
    - Mobile Advertising
    url: /providers/adcolony/
  layer: common
  name: AdColony
  provider: adcolony
  says: ships the AdColony SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id005
      status: none
    slug: adjust
    status: profiled
    tags: &id006
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: Adjust
  provider: adjust
  says: ships the Adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id007
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id008
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: common
  name: Amazon
  provider: amazon
  says: ships the Amazon SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id009
      status: none
    slug: applovin
    status: profiled
    tags: &id010
    - AdTech
    - Advertising
    - App Monetization
    - Mobile
    url: /providers/applovin/
  layer: common
  name: AppLovin
  provider: applovin
  says: ships the AppLovin SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id011
      status: none
    slug: bidmachine-io
    status: profiled
    tags: &id012
    - Ad Exchange
    - AdTech
    - Advertising
    - Mobile Advertising
    url: /providers/bidmachine-io/
  layer: common
  name: BidMachine
  provider: bidmachine-io
  says: ships the BidMachine SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id013
      status: none
    slug: chartboost
    status: profiled
    tags: &id014
    - Company
    url: /providers/chartboost/
  layer: common
  name: Chartboost
  provider: chartboost
  says: ships the Chartboost SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id015
      status: none
    slug: digital-turbine
    status: profiled
    tags: &id016
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/digital-turbine/
  layer: common
  name: Digital Turbine (Fyber)
  provider: digital-turbine
  says: ships the Digital Turbine (Fyber) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id020
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id023
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id024
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id025
      status: none
    slug: inmobi
    status: profiled
    tags: &id026
    - AdTech
    - Advertising
    - Company
    - Enterprise
    url: /providers/inmobi/
  layer: common
  name: InMobi
  provider: inmobi
  says: ships the InMobi SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id027
      status: none
    slug: ironsource
    status: profiled
    tags: &id028
    - Advertising
    - Game Development
    - Mobile
    - Mobile Games
    url: /providers/ironsource/
  layer: common
  name: ironSource
  provider: ironsource
  says: ships the ironSource SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id029
      status: unknown
    slug: mintegral
    status: profiled
    tags: &id030
    - Advertising
    - Artificial Intelligence
    - Company
    - Mobile Marketing
    url: /providers/mintegral/
  layer: common
  name: Mintegral
  provider: mintegral
  says: ships the Mintegral SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 59.5
    mcp: &id031
      status: none
    slug: mparticle
    status: profiled
    tags: &id032
    - Analytics
    - CDP
    - Customer Data Platform
    - Identity Resolution
    url: /providers/mparticle/
  layer: common
  name: mParticle
  provider: mparticle
  says: ships the mParticle SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id033
      status: unchecked
    slug: mytarget
    status: queued for profiling
    tags: &id034 []
    url: null
  layer: common
  name: myTarget
  provider: mytarget
  says: ships the myTarget SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id035
      status: none
    slug: pangle
    status: profiled
    tags: &id036
    - Advertising
    - Mobile
    - Monetization
    - TikTok
    url: /providers/pangle/
  layer: common
  name: Pangle
  provider: pangle
  says: ships the Pangle SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: prebid
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: common
  name: Prebid Mobile
  provider: prebid
  says: ships the Prebid Mobile SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    agent_readiness: 33.5
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id039
      source: https://github.com/PubMatic/pubmatic-mcp-server
      status: verified
    slug: pubmatic
    status: profiled
    tags: &id040
    - AdTech
    - Advertising
    - Programmatic Advertising
    - Supply Side Platform
    url: /providers/pubmatic/
  layer: common
  name: PubMatic
  provider: pubmatic
  says: ships the PubMatic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    mcp: &id043
      source: https://github.com/Unity-Technologies/industry-ai-workflows
      status: verified
    slug: unity
    status: profiled
    tags: &id044
    - Game Development
    - Game Services
    - Multiplayer
    - Real-Time 3D
    url: /providers/unity/
  layer: common
  name: Unity
  provider: unity
  says: ships the Unity SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    kin_score: 13.2
    mcp: &id045
      status: none
    slug: yandex-ads
    status: profiled
    tags: &id046
    - Advertising
    - App Monetization
    - User Acquisition
    - Web Analytics
    url: /providers/yandex-ads/
  layer: common
  name: Yandex Ads
  provider: yandex-ads
  says: ships the Yandex Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/resale-marketplace/vinted/
providers:
- agent_band: agent-aware
  agent_readiness: 19.4
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id003
  name: AdColony
  slug: adcolony
  status: profiled
  tags: *id004
  url: /providers/adcolony/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id005
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id006
  url: /providers/adjust/
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id007
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id008
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id009
  name: AppLovin
  slug: applovin
  status: profiled
  tags: *id010
  url: /providers/applovin/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id011
  name: BidMachine
  slug: bidmachine-io
  status: profiled
  tags: *id012
  url: /providers/bidmachine-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.0
  mcp: *id013
  name: Chartboost
  slug: chartboost
  status: profiled
  tags: *id014
  url: /providers/chartboost/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id015
  name: Digital Turbine (Fyber)
  slug: digital-turbine
  status: profiled
  tags: *id016
  url: /providers/digital-turbine/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id019
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id020
  url: /providers/google-firebase/
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
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id023
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id024
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id025
  name: InMobi
  slug: inmobi
  status: profiled
  tags: *id026
  url: /providers/inmobi/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id027
  name: ironSource
  slug: ironsource
  status: profiled
  tags: *id028
  url: /providers/ironsource/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id029
  name: Mintegral
  slug: mintegral
  status: profiled
  tags: *id030
  url: /providers/mintegral/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id031
  name: mParticle
  slug: mparticle
  status: profiled
  tags: *id032
  url: /providers/mparticle/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id033
  name: myTarget
  slug: mytarget
  status: queued for profiling
  tags: *id034
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id035
  name: Pangle
  slug: pangle
  status: profiled
  tags: *id036
  url: /providers/pangle/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: Prebid Mobile
  slug: prebid
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-ready
  agent_readiness: 33.5
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id039
  name: PubMatic
  slug: pubmatic
  status: profiled
  tags: *id040
  url: /providers/pubmatic/
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
- agent_band: agent-aware
  agent_readiness: 25.3
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id043
  name: Unity
  slug: unity
  status: profiled
  tags: *id044
  url: /providers/unity/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id045
  name: Yandex Ads
  slug: yandex-ads
  status: profiled
  tags: *id046
  url: /providers/yandex-ads/
siblings:
- name: Cocorico
  rows: 5
  url: /applications/resale-marketplace/cocorico/
- name: Depop
  rows: 6
  url: /applications/resale-marketplace/depop/
- name: Mercari
  rows: 9
  url: /applications/resale-marketplace/mercari/
- name: Poshmark
  rows: 11
  url: /applications/resale-marketplace/poshmark/
- name: Sharetribe (hosted)
  rows: 11
  url: /applications/resale-marketplace/sharetribe-hosted/
- name: Sharetribe Go
  rows: 11
  url: /applications/resale-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 6
  url: /applications/resale-marketplace/sharetribe-web-template/
sitemap: true
title: 'Vinted: Resale & Second-hand Marketplaces reference app'
---
