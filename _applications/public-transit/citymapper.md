---
app: Citymapper
app_slug: citymapper
app_url: https://citymapper.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.30.50
  key: AE-210.30.50
  layer: domain
  name: Micromobility & Bike Share
  providers:
  - BCycle
  - Bird
  - Lime
  - Lyft bikeshare systems
  - Skip
  - Spin
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-210.30.10
  key: AE-210.30.10
  layer: domain
  name: Ride Hailing
  providers:
  - Lyft
  - Uber
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: Turbo EA
  id: BC-2120.40
  key: customer-information-consent-management
  layer: common
  name: Customer Information & Consent Management
  providers:
  - Didomi
  url: /capabilities/customer-information-consent-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Amazon
  - AppLovin
  - Facebook
  - Google AdMob
  - InMobi
  - PubMatic
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
- attribution: API Evangelist extension
  id: AE-210.50.10
  key: AE-210.50.10
  layer: common
  name: Mobile Tickets & Wallet Passes
  providers:
  - Apple Wallet
  url: /capabilities/event-ticketing/
  via_parent: Event Ticketing
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
  - Mixpanel
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
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: public-transit
  name: Public Transit
  url: /applications/public-transit/
counts:
  declared: 9
  observed: 14
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
- route: integrations page
  url: https://citymapper.com/partners
- route: store listing
  url: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
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
  name: Amazon
  provider: amazon
  says: ships the Amazon SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: exemplar
    in_catalog: true
    kin_score: 78.8
    mcp: &id016
      status: none
    slug: didomi
    status: profiled
    tags: &id017
    - AdTech
    - Advertising
    - CCPA
    - CMP
    url: /providers/didomi/
  layer: common
  name: Didomi
  provider: didomi
  says: ships the Didomi SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    mcp: &id018
      status: none
    slug: facebook
    status: profiled
    tags: &id019
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    mcp: &id020
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id021
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    mcp: &id022
      status: none
    slug: google-admob
    status: profiled
    tags: &id023
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    mcp: &id024
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id025
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    mcp: &id026
      status: none
    slug: inmobi
    status: profiled
    tags: &id027
    - AdTech
    - Advertising
    - Company
    - Enterprise
    url: /providers/inmobi/
  layer: common
  name: InMobi
  provider: inmobi
  says: ships the InMobi SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id032
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id033
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    mcp: &id034
      source: https://github.com/PubMatic/pubmatic-mcp-server
      status: verified
    slug: pubmatic
    status: profiled
    tags: &id035
    - AdTech
    - Advertising
    - Programmatic Advertising
    - Supply Side Platform
    url: /providers/pubmatic/
  layer: common
  name: PubMatic
  provider: pubmatic
  says: ships the PubMatic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.50.10
    key: AE-210.50.10
    name: Mobile Tickets & Wallet Passes
    url: /capabilities/event-ticketing/
    via_parent: Event Ticketing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id006
      status: none
    slug: apple
    status: profiled
    tags: &id007
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple Wallet
  provider: apple
  says: lists Apple Wallet as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.1
    mcp: &id012
      status: unchecked
    slug: bcycle
    status: profiled
    tags: &id013
    - Bike Share
    - Docked Systems
    - Operator Tools
    url: /providers/bcycle/
  layer: domain
  name: BCycle
  provider: bcycle
  says: lists BCycle as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id014
      status: unknown
    slug: bird-rides
    status: profiled
    tags: &id015
    - E-Scooter
    - Electric Scooters
    - Micromobility
    - Shared Mobility
    url: /providers/bird-rides/
  layer: domain
  name: Bird
  provider: bird-rides
  says: lists Bird as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.7
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id028
      status: none
    slug: lime
    status: profiled
    tags: &id029
    - Electric Bikes
    - Electric Scooters
    - Micromobility
    - Shared Mobility
    url: /providers/lime/
  layer: domain
  name: Lime
  provider: lime
  says: lists Lime as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts: &id003
    agent_band: agent-ready
    agent_readiness: 36.3
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id030
      status: none
    slug: lyft
    status: profiled
    tags: &id031
    - Micromobility
    - Mobility
    - Ride Hailing
    - Transportation
    url: /providers/lyft/
  layer: domain
  name: Lyft
  provider: lyft
  says: lists Lyft as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts: *id003
  layer: domain
  name: Lyft bikeshare systems
  provider: lyft
  says: lists Lyft bikeshare systems as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id036
      status: unknown
    slug: skip-scooters
    status: profiled
    tags: &id037
    - Company
    - Micromobility
    - Scooters
    - Transportation
    url: /providers/skip-scooters/
  layer: domain
  name: Skip
  provider: skip-scooters
  says: lists Skip as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.1
    mcp: &id038
      status: unchecked
    slug: spin-scooters
    status: profiled
    tags: &id039
    - Company
    - Micromobility
    - Software-as-a-Service
    - Transportation
    url: /providers/spin-scooters/
  layer: domain
  name: Spin
  provider: spin-scooters
  says: lists Spin as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id040
      status: none
    slug: uber
    status: profiled
    tags: &id041
    - Food Delivery
    - Ride Hailing
    - Taxis
    - Transportation
    url: /providers/uber/
  layer: domain
  name: Uber
  provider: uber
  says: lists Uber as an integration
  source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/public-transit/citymapper/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id004
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id005
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id006
  name: Apple Wallet
  slug: apple
  status: profiled
  tags: *id007
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id008
  name: AppLovin
  slug: applovin
  status: profiled
  tags: *id009
  url: /providers/applovin/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id010
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id011
  url: /providers/appsflyer/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id012
  name: BCycle
  slug: bcycle
  status: profiled
  tags: *id013
  url: /providers/bcycle/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id014
  name: Bird
  slug: bird-rides
  status: profiled
  tags: *id015
  url: /providers/bird-rides/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: exemplar
  in_catalog: true
  kin_score: 78.8
  mcp: *id016
  name: Didomi
  slug: didomi
  status: profiled
  tags: *id017
  url: /providers/didomi/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id018
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id019
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id020
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id021
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id022
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id023
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id024
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id025
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id026
  name: InMobi
  slug: inmobi
  status: profiled
  tags: *id027
  url: /providers/inmobi/
- agent_band: agent-aware
  agent_readiness: 16.7
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id028
  name: Lime
  slug: lime
  status: profiled
  tags: *id029
  url: /providers/lime/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id030
  name: Lyft
  slug: lyft
  status: profiled
  tags: *id031
  url: /providers/lyft/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id032
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id033
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id034
  name: PubMatic
  slug: pubmatic
  status: profiled
  tags: *id035
  url: /providers/pubmatic/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id036
  name: Skip
  slug: skip-scooters
  status: profiled
  tags: *id037
  url: /providers/skip-scooters/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id038
  name: Spin
  slug: spin-scooters
  status: profiled
  tags: *id039
  url: /providers/spin-scooters/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id040
  name: Uber
  slug: uber
  status: profiled
  tags: *id041
  url: /providers/uber/
siblings:
- name: Moovit
  rows: 17
  url: /applications/public-transit/moovit/
- name: MOTIS (Transitous)
  rows: 7
  url: /applications/public-transit/motis-transitous/
- name: OneBusAway Android
  rows: 8
  url: /applications/public-transit/onebusaway-android/
- name: OpenTripPlanner
  rows: 9
  url: /applications/public-transit/opentripplanner/
- name: Transit
  rows: 9
  url: /applications/public-transit/transit/
sitemap: true
title: 'Citymapper: Public Transit reference app'
---
