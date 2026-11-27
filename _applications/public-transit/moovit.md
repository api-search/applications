---
app: Moovit
app_slug: moovit
app_url: https://moovit.com/
author: API Evangelist
capabilities:
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
  - Appodeal
  - BidMachine
  - Digital Turbine (Fyber)
  - Facebook
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120
  key: location-mapping
  layer: common
  name: Location & Mapping
  providers:
  - Carto
  url: /capabilities/location-mapping/
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
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: public-transit
  name: Public Transit
  url: /applications/public-transit/
counts:
  declared: 3
  observed: 14
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
- route: integrations page
  url: https://moovit.com/partners/
- route: store listing
  url: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
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
    agent_readiness: 28.5
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id005
      status: none
    slug: appodeal
    status: profiled
    tags: &id006
    - Advertising
    - Company
    - Mobile
    - Monetization
    url: /providers/appodeal/
  layer: common
  name: Appodeal
  provider: appodeal
  says: ships the Appodeal SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    mcp: &id007
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id008
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    agent_band: agent-aware
    agent_readiness: 28.2
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id011
      status: unknown
    slug: usebutton
    status: profiled
    tags: &id012
    - Affiliates
    - Attribution
    - Commerce
    - Mobile Commerce
    url: /providers/usebutton/
  layer: common
  name: Button
  provider: usebutton
  says: ships the Button SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: location-mapping
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id013
      status: unchecked
    slug: carto
    status: profiled
    tags: &id014
    - GIS
    - Geospatial
    - Location Intelligence
    - Mapping
    url: /providers/carto/
  layer: common
  name: Carto
  provider: carto
  says: ships the Carto SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple Wallet
  provider: apple
  says: lists Apple Wallet as an integration
  source: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
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
    agent_band: agent-ready
    agent_readiness: 36.3
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id025
      status: none
    slug: lyft
    status: profiled
    tags: &id026
    - Micromobility
    - Mobility
    - Ride Hailing
    - Transportation
    url: /providers/lyft/
  layer: domain
  name: Lyft
  provider: lyft
  says: lists Lyft as an integration
  source: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
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
    mcp: &id027
      status: none
    slug: uber
    status: profiled
    tags: &id028
    - Food Delivery
    - Ride Hailing
    - Taxis
    - Transportation
    url: /providers/uber/
  layer: domain
  name: Uber
  provider: uber
  says: lists Uber as an integration
  source: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/public-transit/moovit/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple Wallet
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id005
  name: Appodeal
  slug: appodeal
  status: profiled
  tags: *id006
  url: /providers/appodeal/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id007
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id008
  url: /providers/appsflyer/
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
- agent_band: agent-aware
  agent_readiness: 28.2
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id011
  name: Button
  slug: usebutton
  status: profiled
  tags: *id012
  url: /providers/usebutton/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id013
  name: Carto
  slug: carto
  status: profiled
  tags: *id014
  url: /providers/carto/
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
- agent_band: agent-ready
  agent_readiness: 36.3
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id025
  name: Lyft
  slug: lyft
  status: profiled
  tags: *id026
  url: /providers/lyft/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id027
  name: Uber
  slug: uber
  status: profiled
  tags: *id028
  url: /providers/uber/
siblings:
- name: Citymapper
  rows: 23
  url: /applications/public-transit/citymapper/
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
title: 'Moovit: Public Transit reference app'
---
