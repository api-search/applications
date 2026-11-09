---
app: Grindr
app_slug: grindr
app_url: https://www.grindr.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Instagram
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.50
  key: AE-160.50
  layer: common
  name: Consent & Preferences
  providers:
  - Ketch
  url: /capabilities/consent-preferences/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Amazon
  - AppLovin
  - Appodeal
  - BidMachine
  - Digital Turbine (Fyber)
  - Google AdMob
  - InMobi
  - ironSource
  - Mintegral
  - PubMatic
  - PubNative
  - Unity
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
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-130.50
  key: privacy-data-protection-management
  layer: common
  name: Privacy & Data Protection Management
  providers:
  - TrustArc
  url: /capabilities/privacy-data-protection-management/
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
  - IAB Tech Lab
  url: /capabilities/programmatic-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Apple
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: dating
  name: Dating
  url: /applications/dating/
counts:
  declared: 4
  observed: 20
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
- route: documentation
  url: https://trust.grindr.com/en-US/privacy
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
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
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
  name: Amazon
  provider: amazon
  says: ships the Amazon SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    mcp: &id007
      status: none
    slug: applovin
    status: profiled
    tags: &id008
    - AdTech
    - Advertising
    - App Monetization
    - Mobile
    url: /providers/applovin/
  layer: common
  name: AppLovin
  provider: applovin
  says: ships the AppLovin SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    agent_readiness: 29.1
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id009
      status: unchecked
    slug: appodeal
    status: profiled
    tags: &id010
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/appodeal/
  layer: common
  name: Appodeal
  provider: appodeal
  says: ships the Appodeal SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    mcp: &id011
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id012
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    mcp: &id013
      status: none
    slug: bidmachine-io
    status: profiled
    tags: &id014
    - Ad Exchange
    - AdTech
    - Advertising
    - Mobile Advertising
    url: /providers/bidmachine-io/
  layer: common
  name: BidMachine
  provider: bidmachine-io
  says: ships the BidMachine SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id020
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
  name: IAB Tech Lab
  provider: iab-tech-lab
  says: ships the IAB Tech Lab SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
  layer: common
  name: InMobi
  provider: inmobi
  says: ships the InMobi SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    mcp: &id031
      status: none
    slug: ironsource
    status: profiled
    tags: &id032
    - Advertising
    - Game Development
    - Mobile
    - Mobile Games
    url: /providers/ironsource/
  layer: common
  name: ironSource
  provider: ironsource
  says: ships the ironSource SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    mcp: &id035
      status: unknown
    slug: mintegral
    status: profiled
    tags: &id036
    - Advertising
    - Artificial Intelligence
    - Company
    - Mobile Marketing
    url: /providers/mintegral/
  layer: common
  name: Mintegral
  provider: mintegral
  says: ships the Mintegral SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    mcp: &id037
      source: https://github.com/PubMatic/pubmatic-mcp-server
      status: verified
    slug: pubmatic
    status: profiled
    tags: &id038
    - AdTech
    - Advertising
    - Programmatic Advertising
    - Supply Side Platform
    url: /providers/pubmatic/
  layer: common
  name: PubMatic
  provider: pubmatic
  says: ships the PubMatic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 26.0
    mcp: &id039
      status: unchecked
    slug: pubnative
    status: profiled
    tags: &id040
    - AdTech
    - Company
    - Mobile
    - Monetization
    url: /providers/pubnative/
  layer: common
  name: PubNative
  provider: pubnative
  says: ships the PubNative SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-130.50
    key: privacy-data-protection-management
    name: Privacy & Data Protection Management
    url: /capabilities/privacy-data-protection-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: strong
    in_catalog: true
    kin_score: 55.8
    mcp: &id041
      status: unknown
    slug: trustarc
    status: profiled
    tags: &id042
    - Identity
    - OAuth
    - Privacy
    - SCIM
    url: /providers/trustarc/
  layer: common
  name: TrustArc
  provider: trustarc
  says: ships the TrustArc SDK or integration code
  source: https://trust.grindr.com/en-US/privacy
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id005
      status: none
    slug: apple
    status: profiled
    tags: &id006
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://trust.grindr.com/en-US/privacy
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id023
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id024
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
  source: https://trust.grindr.com/en-US/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id029
      status: none
    slug: instagram
    status: profiled
    tags: &id030
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://trust.grindr.com/en-US/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id033
      status: none
    slug: ketch-io
    status: profiled
    tags: &id034
    - Consent
    - Ketch
    - Preference Management
    - Privacy
    url: /providers/ketch-io/
  layer: common
  name: Ketch
  provider: ketch-io
  says: lists Ketch as an integration
  source: https://trust.grindr.com/en-US/privacy
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/dating/grindr/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id003
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id004
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id005
  name: Apple
  slug: apple
  status: profiled
  tags: *id006
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 36.2
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id007
  name: AppLovin
  slug: applovin
  status: profiled
  tags: *id008
  url: /providers/applovin/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id009
  name: Appodeal
  slug: appodeal
  status: profiled
  tags: *id010
  url: /providers/appodeal/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id011
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id012
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 49.2
  mcp: *id013
  name: BidMachine
  slug: bidmachine-io
  status: profiled
  tags: *id014
  url: /providers/bidmachine-io/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id015
  name: Digital Turbine (Fyber)
  slug: digital-turbine
  status: profiled
  tags: *id016
  url: /providers/digital-turbine/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id019
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id020
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id021
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id022
  url: /providers/google-admob/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id023
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id024
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id025
  name: IAB Tech Lab
  slug: iab-tech-lab
  status: profiled
  tags: *id026
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: developing
  in_catalog: true
  kin_score: 49.9
  mcp: *id027
  name: InMobi
  slug: inmobi
  status: profiled
  tags: *id028
  url: /providers/inmobi/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id029
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id030
  url: /providers/instagram/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id031
  name: ironSource
  slug: ironsource
  status: profiled
  tags: *id032
  url: /providers/ironsource/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id033
  name: Ketch
  slug: ketch-io
  status: profiled
  tags: *id034
  url: /providers/ketch-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id035
  name: Mintegral
  slug: mintegral
  status: profiled
  tags: *id036
  url: /providers/mintegral/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: thin
  in_catalog: true
  kin_score: 26.7
  mcp: *id037
  name: PubMatic
  slug: pubmatic
  status: profiled
  tags: *id038
  url: /providers/pubmatic/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 26.0
  mcp: *id039
  name: PubNative
  slug: pubnative
  status: profiled
  tags: *id040
  url: /providers/pubnative/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: strong
  in_catalog: true
  kin_score: 55.8
  mcp: *id041
  name: TrustArc
  slug: trustarc
  status: profiled
  tags: *id042
  url: /providers/trustarc/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id043
  name: Unity
  slug: unity
  status: profiled
  tags: *id044
  url: /providers/unity/
siblings:
- name: Alovoa
  rows: 2
  url: /applications/dating/alovoa/
- name: Bumble
  rows: 23
  url: /applications/dating/bumble/
- name: Duolicious
  rows: 9
  url: /applications/dating/duolicious/
- name: Hinge
  rows: 53
  url: /applications/dating/hinge/
- name: pH7Builder
  rows: 8
  url: /applications/dating/ph7builder/
- name: Tinder
  rows: 15
  url: /applications/dating/tinder/
sitemap: true
title: 'Grindr: Dating reference app'
---
