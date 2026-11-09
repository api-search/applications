---
app: Tinder
app_slug: tinder
app_url: https://tinder.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Spotify
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Instagram
  - LinkedIn
  url: /capabilities/social-networks-community/
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
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Apple
  - Google Play
  url: /capabilities/in-app-purchases-app-store-billing/
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
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
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
  - Apple
  - Facebook
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: dating
  name: Dating
  url: /applications/dating/
counts:
  declared: 8
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
- route: documentation
  url: https://policies.tinder.com/privacy/intl/en/
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
    mcp: &id005
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id006
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    mcp: &id007
      status: none
    slug: branch-io
    status: profiled
    tags: &id008
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id009
      status: none
    slug: facebook
    status: profiled
    tags: &id010
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    mcp: &id011
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id012
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    mcp: &id013
      status: none
    slug: google-admob
    status: profiled
    tags: &id014
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    mcp: &id019
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id020
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Tech Lab
  provider: iab-tech-lab
  says: ships the IAB Tech Lab SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    mcp: &id025
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id026
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
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
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://policies.tinder.com/privacy/intl/en/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://policies.tinder.com/privacy/intl/en/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: *id002
  layer: common
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://policies.tinder.com/privacy/intl/en/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id015
      status: none
    slug: google-play
    status: profiled
    tags: &id016
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play
  provider: google-play
  says: lists Google Play as an integration
  source: https://policies.tinder.com/privacy/intl/en/
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
    mcp: &id017
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id018
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
  source: https://policies.tinder.com/privacy/intl/en/
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
    mcp: &id021
      status: none
    slug: instagram
    status: profiled
    tags: &id022
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://policies.tinder.com/privacy/intl/en/
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
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id023
      status: none
    slug: linkedin
    status: profiled
    tags: &id024
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://policies.tinder.com/privacy/intl/en/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id027
      status: none
    slug: spotify
    status: profiled
    tags: &id028
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: lists Spotify as an integration
  source: https://policies.tinder.com/privacy/intl/en/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/dating/tinder/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id005
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id006
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id007
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id008
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id009
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id010
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id011
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id012
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id013
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id014
  url: /providers/google-admob/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id015
  name: Google Play
  slug: google-play
  status: profiled
  tags: *id016
  url: /providers/google-play/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id017
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id018
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id019
  name: IAB Tech Lab
  slug: iab-tech-lab
  status: profiled
  tags: *id020
  url: /providers/iab-tech-lab/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id021
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id022
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id023
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id024
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id025
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id026
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id027
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id028
  url: /providers/spotify/
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
- name: Grindr
  rows: 24
  url: /applications/dating/grindr/
- name: Hinge
  rows: 53
  url: /applications/dating/hinge/
- name: pH7Builder
  rows: 8
  url: /applications/dating/ph7builder/
sitemap: true
title: 'Tinder: Dating reference app'
---
