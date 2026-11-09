---
app: Life360
app_slug: life360
app_url: https://www.life360.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - AdColony
  - Amazon Advertisement
  - AppLovin
  - BidMachine
  - Chartboost
  - Digital Turbine (Fyber)
  - Facebook Ads
  - Google AdMob
  - IAB Open Measurement
  - InMobi
  - ironSource
  - Mintegral
  - myTarget
  - Pangle
  - PubMatic
  - Unity Ads
  - Yandex Ads
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Rollbar
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.10
  key: product-telemetry-instrumentation
  layer: common
  name: Product Telemetry Instrumentation
  providers:
  - Sentiance
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Facebook Analytics
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: kids-family-parenting
  name: Kids, Family & Parenting
  url: /applications/kids-family-parenting/
counts:
  declared: 0
  observed: 25
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 19.8
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id002
      status: none
    slug: adcolony
    status: profiled
    tags: &id003
    - AdTech
    - Advertising
    - Company
    - Mobile Advertising
    url: /providers/adcolony/
  layer: common
  name: AdColony
  provider: adcolony
  says: ships the AdColony SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id004
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id005
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: common
  name: Amazon Advertisement
  provider: amazon
  says: ships the Amazon Advertisement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    mcp: &id006
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id007
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 36.2
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id008
      status: none
    slug: applovin
    status: profiled
    tags: &id009
    - AdTech
    - Advertising
    - App Monetization
    - Mobile
    url: /providers/applovin/
  layer: common
  name: AppLovin
  provider: applovin
  says: ships the AppLovin SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    mcp: &id010
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id011
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 31.6
    band: developing
    in_catalog: true
    kin_score: 49.2
    mcp: &id012
      status: none
    slug: bidmachine-io
    status: profiled
    tags: &id013
    - Ad Exchange
    - AdTech
    - Advertising
    - Mobile Advertising
    url: /providers/bidmachine-io/
  layer: common
  name: BidMachine
  provider: bidmachine-io
  says: ships the BidMachine SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 23.0
    mcp: &id014
      status: none
    slug: branch-io
    status: profiled
    tags: &id015
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    kin_score: 2.2
    mcp: &id016
      status: none
    slug: chartboost
    status: profiled
    tags: &id017
    - Company
    url: /providers/chartboost/
  layer: common
  name: Chartboost
  provider: chartboost
  says: ships the Chartboost SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 20.8
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id018
      status: none
    slug: digital-turbine
    status: profiled
    tags: &id019
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/digital-turbine/
  layer: common
  name: Digital Turbine (Fyber)
  provider: digital-turbine
  says: ships the Digital Turbine (Fyber) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id020
      status: none
    slug: facebook
    status: profiled
    tags: &id021
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Ads
  provider: facebook
  says: ships the Facebook Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    mcp: &id022
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id023
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    mcp: &id024
      status: none
    slug: google-admob
    status: profiled
    tags: &id025
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 37.6
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id026
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id027
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 7.9
    band: developing
    in_catalog: true
    kin_score: 49.9
    mcp: &id028
      status: none
    slug: inmobi
    status: profiled
    tags: &id029
    - AdTech
    - Advertising
    - Company
    - Enterprise
    url: /providers/inmobi/
  layer: common
  name: InMobi
  provider: inmobi
  says: ships the InMobi SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id030
      status: none
    slug: ironsource
    status: profiled
    tags: &id031
    - Advertising
    - Game Development
    - Mobile
    - Mobile Games
    url: /providers/ironsource/
  layer: common
  name: ironSource
  provider: ironsource
  says: ships the ironSource SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    kin_score: 11.6
    mcp: &id032
      status: unknown
    slug: mintegral
    status: profiled
    tags: &id033
    - Advertising
    - Artificial Intelligence
    - Company
    - Mobile Marketing
    url: /providers/mintegral/
  layer: common
  name: Mintegral
  provider: mintegral
  says: ships the Mintegral SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    mcp: &id034
      status: unchecked
    slug: mytarget
    status: queued for profiling
    tags: &id035 []
    url: null
  layer: common
  name: myTarget
  provider: mytarget
  says: ships the myTarget SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    kin_score: 8.4
    mcp: &id036
      status: none
    slug: pangle
    status: profiled
    tags: &id037
    - Advertising
    - Mobile
    - Monetization
    - TikTok
    url: /providers/pangle/
  layer: common
  name: Pangle
  provider: pangle
  says: ships the Pangle SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 34.2
    band: thin
    in_catalog: true
    kin_score: 26.7
    mcp: &id038
      source: https://github.com/PubMatic/pubmatic-mcp-server
      status: verified
    slug: pubmatic
    status: profiled
    tags: &id039
    - AdTech
    - Advertising
    - Programmatic Advertising
    - Supply Side Platform
    url: /providers/pubmatic/
  layer: common
  name: PubMatic
  provider: pubmatic
  says: ships the PubMatic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 30.8
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id040
      source: https://github.com/rollbar/rollbar-mcp-server
      status: verified
    slug: rollbar
    status: profiled
    tags: &id041
    - Debugging
    - DevOps
    - Error Tracking
    - Monitoring
    url: /providers/rollbar/
  layer: common
  name: Rollbar
  provider: rollbar
  says: ships the Rollbar SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.10
    key: product-telemetry-instrumentation
    name: Product Telemetry Instrumentation
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id042
      status: unchecked
    slug: sentiance
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - Behavioral-Intelligence
    - Mobile
    - Privacy
    url: /providers/sentiance/
  layer: common
  name: Sentiance
  provider: sentiance
  says: ships the Sentiance SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    kin_score: 80.6
    mcp: &id044
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id045
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    agent_readiness: 25.8
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id046
      source: https://github.com/Unity-Technologies/industry-ai-workflows
      status: verified
    slug: unity
    status: profiled
    tags: &id047
    - Game Development
    - Game Services
    - Multiplayer
    - Real-Time 3D
    url: /providers/unity/
  layer: common
  name: Unity Ads
  provider: unity
  says: ships the Unity Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
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
    kin_score: 9.2
    mcp: &id048
      status: none
    slug: yandex-ads
    status: profiled
    tags: &id049
    - Advertising
    - App Monetization
    - User Acquisition
    - Web Analytics
    url: /providers/yandex-ads/
  layer: common
  name: Yandex Ads
  provider: yandex-ads
  says: ships the Yandex Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.life360.android.safetymapd/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/kids-family-parenting/life360/
providers:
- agent_band: agent-aware
  agent_readiness: 19.8
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id002
  name: AdColony
  slug: adcolony
  status: profiled
  tags: *id003
  url: /providers/adcolony/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id004
  name: Amazon Advertisement
  slug: amazon
  status: profiled
  tags: *id005
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id006
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id007
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 36.2
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id008
  name: AppLovin
  slug: applovin
  status: profiled
  tags: *id009
  url: /providers/applovin/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id010
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id011
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 49.2
  mcp: *id012
  name: BidMachine
  slug: bidmachine-io
  status: profiled
  tags: *id013
  url: /providers/bidmachine-io/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id014
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id015
  url: /providers/branch-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id016
  name: Chartboost
  slug: chartboost
  status: profiled
  tags: *id017
  url: /providers/chartboost/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id018
  name: Digital Turbine (Fyber)
  slug: digital-turbine
  status: profiled
  tags: *id019
  url: /providers/digital-turbine/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id020
  name: Facebook Ads
  slug: facebook
  status: profiled
  tags: *id021
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id022
  name: Firebase (Crashlytics / Analytics)
  slug: firebase
  status: profiled
  tags: *id023
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id024
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id025
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id026
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id027
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: developing
  in_catalog: true
  kin_score: 49.9
  mcp: *id028
  name: InMobi
  slug: inmobi
  status: profiled
  tags: *id029
  url: /providers/inmobi/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id030
  name: ironSource
  slug: ironsource
  status: profiled
  tags: *id031
  url: /providers/ironsource/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id032
  name: Mintegral
  slug: mintegral
  status: profiled
  tags: *id033
  url: /providers/mintegral/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id034
  name: myTarget
  slug: mytarget
  status: queued for profiling
  tags: *id035
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.4
  mcp: *id036
  name: Pangle
  slug: pangle
  status: profiled
  tags: *id037
  url: /providers/pangle/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: thin
  in_catalog: true
  kin_score: 26.7
  mcp: *id038
  name: PubMatic
  slug: pubmatic
  status: profiled
  tags: *id039
  url: /providers/pubmatic/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id040
  name: Rollbar
  slug: rollbar
  status: profiled
  tags: *id041
  url: /providers/rollbar/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id042
  name: Sentiance
  slug: sentiance
  status: profiled
  tags: *id043
  url: /providers/sentiance/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id044
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id045
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id046
  name: Unity Ads
  slug: unity
  status: profiled
  tags: *id047
  url: /providers/unity/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id048
  name: Yandex Ads
  slug: yandex-ads
  status: profiled
  tags: *id049
  url: /providers/yandex-ads/
siblings:
- name: Baby Buddy
  rows: 2
  url: /applications/kids-family-parenting/baby-buddy/
- name: Brightwheel
  rows: 3
  url: /applications/kids-family-parenting/brightwheel/
- name: Cozi
  rows: 9
  url: /applications/kids-family-parenting/cozi/
- name: Gramps Web
  rows: 2
  url: /applications/kids-family-parenting/gramps-web/
- name: Greenlight
  rows: 0
  url: /applications/kids-family-parenting/greenlight/
- name: OurFamilyWizard
  rows: 4
  url: /applications/kids-family-parenting/ourfamilywizard/
sitemap: true
title: 'Life360: Kids, Family & Parenting reference app'
---
