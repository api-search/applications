---
app: Clash of Clans
app_slug: clash-of-clans
app_url: https://supercell.com/en/games/clashofclans/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-180.40
  key: AE-180.40
  layer: domain
  name: Game Publishing & Distribution
  providers:
  - Supersonic (Unity/ironSource publishing)
  url: /capabilities/game-publishing-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: domain
  name: In-App Ad Monetisation
  providers:
  - AppLovin
  - Fyber (Digital Turbine)
  - Google (ads partner, product unnamed)
  - Google AdSense
  - ironSource
  - Mintegral
  - Tapjoy (offerwall)
  - Unity Technologies / Unity Ads
  - Vungle
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: domain
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer (attribution, processor)
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50.10
  key: AE-170.50.10
  layer: domain
  name: Online Communities
  providers:
  - Discord
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: Turbo EA
  id: BC-400.60.30
  key: BC-400.60.30
  layer: domain
  name: Paid Media Management
  providers:
  - AdAction
  - Adikteev (retargeting)
  - adjoe (playtime rewards)
  - Amazon Ads
  - AMoAd (CyberAgent)
  - Apple Search Ads
  - DirecTV (advertising)
  - Dynalyst (CyberAgent retargeting DSP)
  - Facebook (ads / pixel)
  - Influence Mobile
  - Liftoff (mobile app marketing)
  - Mistplay (rewarded play UA)
  - Moloco
  - Naver (ads)
  - Reddit
  - remerge (retargeting DSP)
  - Skyflag (offerwall)
  - SmartNews (ads)
  - Snap
  - Spotify (ads)
  - TikTok
  - tvScientific (CTV)
  - Twitter
  - Vibe (vibe.co, streaming TV ads)
  - Zucks
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Kakao (account linking + partner)
  - LINE (account linking + partner)
  - QQ (Tencent)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: domain
  name: Social Media Management
  providers:
  - StreamElements (creator sponsorships)
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.50
  key: AE-160.50
  layer: common
  name: Consent & Preferences
  providers:
  - Usercentrics (CMP)
  url: /capabilities/consent-preferences/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Helpshift (in-game support)
  url: /capabilities/customer-service-management/
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
  - Google Firebase
  - Snowplow
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 44
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
- route: documentation
  url: https://supercell.com/en/partner-opt-out/
- route: documentation
  url: https://supercell.com/en/privacy-policy/
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
    mcp: &id015
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id016
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: domain
  name: AppsFlyer (attribution, processor)
  provider: appsflyer
  says: ships the AppsFlyer (attribution, processor) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    mcp: &id033
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id034
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase
  provider: firebase
  says: ships the Google Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    mcp: &id039
      status: unchecked
    slug: helpshift
    status: queued for profiling
    tags: &id040 []
    url: null
  layer: common
  name: Helpshift (in-game support)
  provider: helpshift
  says: ships the Helpshift (in-game support) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    mcp: &id065
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id066
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    agent_readiness: 19.0
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id073
      source: https://github.com/snowplow/snowplow-cli
      status: verified
    slug: snowplow
    status: profiled
    tags: &id074
    - Analytics Platform
    - Behavioral Data
    - Data Collection
    - Data Engineering
    url: /providers/snowplow/
  layer: common
  name: Snowplow
  provider: snowplow
  says: ships the Snowplow SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id001
      status: none
    slug: adaction
    status: profiled
    tags: &id002
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/adaction/
  layer: domain
  name: AdAction
  provider: adaction
  says: lists AdAction as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.4
    mcp: &id003
      status: none
    slug: adikteev
    status: profiled
    tags: &id004
    - Advertising
    - Company
    - Mobile
    - Retargeting
    url: /providers/adikteev/
  layer: domain
  name: Adikteev (retargeting)
  provider: adikteev
  says: lists Adikteev (retargeting) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.5
    mcp: &id005
      status: none
    slug: adjoe
    status: profiled
    tags: &id006
    - Advertising
    - Loyalty
    - Mobile Gaming
    - Monetization
    url: /providers/adjoe/
  layer: domain
  name: adjoe (playtime rewards)
  provider: adjoe
  says: lists adjoe (playtime rewards) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
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
  layer: domain
  name: Amazon Ads
  provider: amazon
  says: lists Amazon Ads as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id009
      status: none
    slug: amoad
    status: profiled
    tags: &id010
    - Company
    url: /providers/amoad/
  layer: domain
  name: AMoAd (CyberAgent)
  provider: amoad
  says: lists AMoAd (CyberAgent) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
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
  layer: domain
  name: Apple Search Ads
  provider: apple
  says: lists Apple Search Ads as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: agent-ready
    agent_readiness: 36.2
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id013
      status: none
    slug: applovin
    status: profiled
    tags: &id014
    - AdTech
    - Advertising
    - App Monetization
    - Mobile
    url: /providers/applovin/
  layer: domain
  name: AppLovin
  provider: applovin
  says: lists AppLovin as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.2
    mcp: &id017
      status: none
    slug: directv
    status: profiled
    tags: &id018
    - Entertainment
    - Media
    - Satellite
    - Television
    url: /providers/directv/
  layer: domain
  name: DirecTV (advertising)
  provider: directv
  says: lists DirecTV (advertising) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id019
      status: none
    slug: discord
    status: profiled
    tags: &id020
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.9
    mcp: &id021
      status: none
    slug: dynalyst
    status: profiled
    tags: &id022
    - Advertising
    - Company
    - DSP
    - Mobile
    url: /providers/dynalyst/
  layer: domain
  name: Dynalyst (CyberAgent retargeting DSP)
  provider: dynalyst
  says: lists Dynalyst (CyberAgent retargeting DSP) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id023
      status: none
    slug: facebook
    status: profiled
    tags: &id024
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook (ads / pixel)
  provider: facebook
  says: lists Facebook (ads / pixel) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    mcp: &id025
      status: unchecked
    slug: fyber
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: Fyber (Digital Turbine)
  provider: fyber
  says: lists Fyber (Digital Turbine) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: agent-ready
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id027
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id028
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google (ads partner, product unnamed)
  provider: google
  says: lists Google (ads partner, product unnamed) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: agent-aware
    agent_readiness: 25.5
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id029
      status: none
    slug: google-adsense
    status: profiled
    tags: &id030
    - Ad Units
    - AdSense
    - Advertising
    - Monetization
    url: /providers/google-adsense/
  layer: domain
  name: Google AdSense
  provider: google-adsense
  says: lists Google AdSense as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id031
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id032
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id035
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id036
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: lists Google reCAPTCHA as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id037
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id038
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id041
      status: unknown
    slug: influence-mobile
    status: profiled
    tags: &id042
    - Advertising
    - Data Platform
    - Mobile Gaming
    - Player Acquisition
    url: /providers/influence-mobile/
  layer: domain
  name: Influence Mobile
  provider: influence-mobile
  says: lists Influence Mobile as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id043
      status: none
    slug: ironsource
    status: profiled
    tags: &id044
    - Advertising
    - Game Development
    - Mobile
    - Mobile Games
    url: /providers/ironsource/
  layer: domain
  name: ironSource
  provider: ironsource
  says: lists ironSource as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    kin_score: 27.2
    mcp: &id045
      status: none
    slug: kakao
    status: profiled
    tags: &id046
    - Maps
    - Messaging
    - Navigation
    - Payments
    url: /providers/kakao/
  layer: domain
  name: Kakao (account linking + partner)
  provider: kakao
  says: lists Kakao (account linking + partner) as an integration
  source: https://supercell.com/en/privacy-policy/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id047
      status: none
    slug: liftoff-io
    status: profiled
    tags: &id048
    - Advertising
    - Artificial Intelligence
    - Company
    - Mobile
    url: /providers/liftoff-io/
  layer: domain
  name: Liftoff (mobile app marketing)
  provider: liftoff-io
  says: lists Liftoff (mobile app marketing) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: agent-native
    agent_readiness: 47.9
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id049
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id050
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE (account linking + partner)
  provider: line
  says: lists LINE (account linking + partner) as an integration
  source: https://supercell.com/en/privacy-policy/
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
    kin_score: 11.6
    mcp: &id051
      status: unknown
    slug: mintegral
    status: profiled
    tags: &id052
    - Advertising
    - Artificial Intelligence
    - Company
    - Mobile Marketing
    url: /providers/mintegral/
  layer: domain
  name: Mintegral
  provider: mintegral
  says: lists Mintegral as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id053
      status: none
    slug: mistplay
    status: profiled
    tags: &id054
    - Gaming
    - Gift Cards
    - Mobile
    - Rewards
    url: /providers/mistplay/
  layer: domain
  name: Mistplay (rewarded play UA)
  provider: mistplay
  says: lists Mistplay (rewarded play UA) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id055
      source: https://developer.moloco.cloud/docs/mcp-getting-started
      status: verified
    slug: moloco
    status: profiled
    tags: &id056
    - AdTech
    - Advertising
    - DSP
    - Retail Media
    url: /providers/moloco/
  layer: domain
  name: Moloco
  provider: moloco
  says: lists Moloco as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id057
      status: none
    slug: naver
    status: profiled
    tags: &id058
    - Cloud Platform
    - Maps
    - Search
    - Translation
    url: /providers/naver/
  layer: domain
  name: Naver (ads)
  provider: naver
  says: lists Naver (ads) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id059
      status: unchecked
    slug: tencent
    status: queued for profiling
    tags: &id060 []
    url: null
  layer: domain
  name: QQ (Tencent)
  provider: tencent
  says: lists QQ (Tencent) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id061
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id062
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: lists Reddit as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 46.8
    mcp: &id063
      status: none
    slug: remerge
    status: profiled
    tags: &id064
    - AdTech
    - Advertising
    - Company
    - Mobile
    url: /providers/remerge/
  layer: domain
  name: remerge (retargeting DSP)
  provider: remerge
  says: lists remerge (retargeting DSP) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id067
      status: unchecked
    slug: skyflag
    status: queued for profiling
    tags: &id068 []
    url: null
  layer: domain
  name: Skyflag (offerwall)
  provider: skyflag
  says: lists Skyflag (offerwall) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 52.7
    mcp: &id069
      status: none
    slug: smartnews
    status: profiled
    tags: &id070
    - Advertising
    - Company
    - Consumer
    - News
    url: /providers/smartnews/
  layer: domain
  name: SmartNews (ads)
  provider: smartnews
  says: lists SmartNews (ads) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.1
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id071
      status: none
    slug: snapchat
    status: profiled
    tags: &id072
    - Advertising
    - Augmented Reality
    - Marketing
    - Messaging
    url: /providers/snapchat/
  layer: domain
  name: Snap
  provider: snapchat
  says: lists Snap as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id075
      status: none
    slug: spotify
    status: profiled
    tags: &id076
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify (ads)
  provider: spotify
  says: lists Spotify (ads) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.1
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id077
      status: none
    slug: streamelements
    status: profiled
    tags: &id078
    - Company
    - Consumer
    - Creator Economy
    - Live Streaming
    url: /providers/streamelements/
  layer: domain
  name: StreamElements (creator sponsorships)
  provider: streamelements
  says: lists StreamElements (creator sponsorships) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-180.40
    key: AE-180.40
    name: Game Publishing & Distribution
    url: /capabilities/game-publishing-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id079
      status: unchecked
    slug: supersonic
    status: queued for profiling
    tags: &id080 []
    url: null
  layer: domain
  name: Supersonic (Unity/ironSource publishing)
  provider: supersonic
  says: lists Supersonic (Unity/ironSource publishing) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    mcp: &id081
      status: unchecked
    slug: tapjoy
    status: queued for profiling
    tags: &id082 []
    url: null
  layer: domain
  name: Tapjoy (offerwall)
  provider: tapjoy
  says: lists Tapjoy (offerwall) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id083
      status: none
    slug: tiktok
    status: profiled
    tags: &id084
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id085
      status: none
    slug: tvscientific
    status: profiled
    tags: &id086
    - Advertising
    - CTV
    - Company
    - Connected TV
    url: /providers/tvscientific/
  layer: domain
  name: tvScientific (CTV)
  provider: tvscientific
  says: lists tvScientific (CTV) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id087
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id088
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter
  provider: x
  says: lists Twitter as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: agent-aware
    agent_readiness: 25.8
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id089
      source: https://github.com/Unity-Technologies/industry-ai-workflows
      status: verified
    slug: unity
    status: profiled
    tags: &id090
    - Game Development
    - Game Services
    - Multiplayer
    - Real-Time 3D
    url: /providers/unity/
  layer: domain
  name: Unity Technologies / Unity Ads
  provider: unity
  says: lists Unity Technologies / Unity Ads as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_readiness: 18.9
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id091
      status: none
    slug: usercentrics
    status: profiled
    tags: &id092
    - CMP
    - Compliance
    - Consent
    - Privacy
    url: /providers/usercentrics/
  layer: common
  name: Usercentrics (CMP)
  provider: usercentrics
  says: lists Usercentrics (CMP) as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id093
      status: unchecked
    slug: vibe-co
    status: queued for profiling
    tags: &id094 []
    url: null
  layer: domain
  name: Vibe (vibe.co, streaming TV ads)
  provider: vibe-co
  says: lists Vibe (vibe.co, streaming TV ads) as an integration
  source: https://supercell.com/en/partner-opt-out/
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
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id095
      status: none
    slug: vungle
    status: profiled
    tags: &id096
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/vungle/
  layer: domain
  name: Vungle
  provider: vungle
  says: lists Vungle as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id097
      status: none
    slug: zucks
    status: profiled
    tags: &id098
    - Company
    url: /providers/zucks/
  layer: domain
  name: Zucks
  provider: zucks
  says: lists Zucks as an integration
  source: https://supercell.com/en/partner-opt-out/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/clash-of-clans/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id001
  name: AdAction
  slug: adaction
  status: profiled
  tags: *id002
  url: /providers/adaction/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.4
  mcp: *id003
  name: Adikteev (retargeting)
  slug: adikteev
  status: profiled
  tags: *id004
  url: /providers/adikteev/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id005
  name: adjoe (playtime rewards)
  slug: adjoe
  status: profiled
  tags: *id006
  url: /providers/adjoe/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id007
  name: Amazon Ads
  slug: amazon
  status: profiled
  tags: *id008
  url: /providers/amazon/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id009
  name: AMoAd (CyberAgent)
  slug: amoad
  status: profiled
  tags: *id010
  url: /providers/amoad/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id011
  name: Apple Search Ads
  slug: apple
  status: profiled
  tags: *id012
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 36.2
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id013
  name: AppLovin
  slug: applovin
  status: profiled
  tags: *id014
  url: /providers/applovin/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id015
  name: AppsFlyer (attribution, processor)
  slug: appsflyer
  status: profiled
  tags: *id016
  url: /providers/appsflyer/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id017
  name: DirecTV (advertising)
  slug: directv
  status: profiled
  tags: *id018
  url: /providers/directv/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id019
  name: Discord
  slug: discord
  status: profiled
  tags: *id020
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.9
  mcp: *id021
  name: Dynalyst (CyberAgent retargeting DSP)
  slug: dynalyst
  status: profiled
  tags: *id022
  url: /providers/dynalyst/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id023
  name: Facebook (ads / pixel)
  slug: facebook
  status: profiled
  tags: *id024
  url: /providers/facebook/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: Fyber (Digital Turbine)
  slug: fyber
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id027
  name: Google (ads partner, product unnamed)
  slug: google
  status: profiled
  tags: *id028
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id029
  name: Google AdSense
  slug: google-adsense
  status: profiled
  tags: *id030
  url: /providers/google-adsense/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id031
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id032
  url: /providers/google-analytics/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id033
  name: Google Firebase
  slug: firebase
  status: profiled
  tags: *id034
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id035
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id036
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id037
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id038
  url: /providers/google-tag-manager/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id039
  name: Helpshift (in-game support)
  slug: helpshift
  status: queued for profiling
  tags: *id040
  url: null
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id041
  name: Influence Mobile
  slug: influence-mobile
  status: profiled
  tags: *id042
  url: /providers/influence-mobile/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id043
  name: ironSource
  slug: ironsource
  status: profiled
  tags: *id044
  url: /providers/ironsource/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id045
  name: Kakao (account linking + partner)
  slug: kakao
  status: profiled
  tags: *id046
  url: /providers/kakao/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id047
  name: Liftoff (mobile app marketing)
  slug: liftoff-io
  status: profiled
  tags: *id048
  url: /providers/liftoff-io/
- agent_band: agent-native
  agent_readiness: 47.9
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id049
  name: LINE (account linking + partner)
  slug: line
  status: profiled
  tags: *id050
  url: /providers/line/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id051
  name: Mintegral
  slug: mintegral
  status: profiled
  tags: *id052
  url: /providers/mintegral/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id053
  name: Mistplay (rewarded play UA)
  slug: mistplay
  status: profiled
  tags: *id054
  url: /providers/mistplay/
- agent_band: agent-native
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id055
  name: Moloco
  slug: moloco
  status: profiled
  tags: *id056
  url: /providers/moloco/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id057
  name: Naver (ads)
  slug: naver
  status: profiled
  tags: *id058
  url: /providers/naver/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id059
  name: QQ (Tencent)
  slug: tencent
  status: queued for profiling
  tags: *id060
  url: null
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id061
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id062
  url: /providers/reddit/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 46.8
  mcp: *id063
  name: remerge (retargeting DSP)
  slug: remerge
  status: profiled
  tags: *id064
  url: /providers/remerge/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id065
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id066
  url: /providers/sentry-system/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id067
  name: Skyflag (offerwall)
  slug: skyflag
  status: queued for profiling
  tags: *id068
  url: null
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 52.7
  mcp: *id069
  name: SmartNews (ads)
  slug: smartnews
  status: profiled
  tags: *id070
  url: /providers/smartnews/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id071
  name: Snap
  slug: snapchat
  status: profiled
  tags: *id072
  url: /providers/snapchat/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id073
  name: Snowplow
  slug: snowplow
  status: profiled
  tags: *id074
  url: /providers/snowplow/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id075
  name: Spotify (ads)
  slug: spotify
  status: profiled
  tags: *id076
  url: /providers/spotify/
- agent_band: agent-ready
  agent_readiness: 35.1
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id077
  name: StreamElements (creator sponsorships)
  slug: streamelements
  status: profiled
  tags: *id078
  url: /providers/streamelements/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id079
  name: Supersonic (Unity/ironSource publishing)
  slug: supersonic
  status: queued for profiling
  tags: *id080
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id081
  name: Tapjoy (offerwall)
  slug: tapjoy
  status: queued for profiling
  tags: *id082
  url: null
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id083
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id084
  url: /providers/tiktok/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id085
  name: tvScientific (CTV)
  slug: tvscientific
  status: profiled
  tags: *id086
  url: /providers/tvscientific/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id087
  name: Twitter
  slug: x
  status: profiled
  tags: *id088
  url: /providers/x/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id089
  name: Unity Technologies / Unity Ads
  slug: unity
  status: profiled
  tags: *id090
  url: /providers/unity/
- agent_band: agent-aware
  agent_readiness: 18.9
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id091
  name: Usercentrics (CMP)
  slug: usercentrics
  status: profiled
  tags: *id092
  url: /providers/usercentrics/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id093
  name: Vibe (vibe.co, streaming TV ads)
  slug: vibe-co
  status: queued for profiling
  tags: *id094
  url: null
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id095
  name: Vungle
  slug: vungle
  status: profiled
  tags: *id096
  url: /providers/vungle/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id097
  name: Zucks
  slug: zucks
  status: profiled
  tags: *id098
  url: /providers/zucks/
siblings:
- name: Candy Crush Saga
  rows: 15
  url: /applications/mobile-games/candy-crush-saga/
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
title: 'Clash of Clans: Mobile & Casual Games (live-ops backend) reference app'
---
