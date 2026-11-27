---
app: Redfin
app_slug: redfin
app_url: https://www.redfin.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4960.30
  key: listing-data-mls-management
  layer: domain
  name: Listing Data & MLS Management
  providers:
  - Fizber.com
  - FSBO.com
  url: /capabilities/listing-data-mls-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4980.10
  key: real-estate-debt-origination
  layer: domain
  name: Real Estate Debt Origination
  providers:
  - Rocket Mortgage (Rocket Companies)
  url: /capabilities/real-estate-debt-origination/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook Share
  url: /capabilities/digital-marketing-management/
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
  - Firebase (Crashlytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Comscore
  - Facebook Analytics
  - Google Analytics
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
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
  id: real-estate-home-search
  name: Real Estate & Home Search
  url: /applications/real-estate-home-search/
counts:
  declared: 3
  observed: 10
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
- route: documentation
  url: https://www.redfin.com/about/data-quality-on-redfin
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
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id003
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id004
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id005
      status: none
    slug: branch-io
    status: profiled
    tags: &id006
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    agent_readiness: 12.0
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id007
      status: none
    slug: comscore
    status: profiled
    tags: &id008
    - Audience Analytics
    - Cloud Saas
    - Company
    - Media Measurement
    url: /providers/comscore/
  layer: common
  name: Comscore
  provider: comscore
  says: ships the Comscore SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
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
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
  name: Facebook Login
  provider: facebook
  says: ships the Facebook Login SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
  name: Facebook Share
  provider: facebook
  says: ships the Facebook Share SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    mcp: &id011
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id012
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id017
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id018
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id019
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id020
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.redfin.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id013
      status: unknown
    slug: fizber
    status: profiled
    tags: &id014
    - FSBO
    - Free Listings
    - Marketplace
    - Real Estate
    url: /providers/fizber/
  layer: domain
  name: Fizber.com
  provider: fizber
  says: lists Fizber.com as an integration
  source: https://www.redfin.com/about/data-quality-on-redfin
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4960.30
    key: listing-data-mls-management
    name: Listing Data & MLS Management
    url: /capabilities/listing-data-mls-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id015
      status: unknown
    slug: fsbo-com
    status: profiled
    tags: &id016
    - Home Selling
    - Marketplace
    - Real Estate
    - Software-as-a-Service
    url: /providers/fsbo-com/
  layer: domain
  name: FSBO.com
  provider: fsbo-com
  says: lists FSBO.com as an integration
  source: https://www.redfin.com/about/data-quality-on-redfin
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4980.10
    key: real-estate-debt-origination
    name: Real Estate Debt Origination
    url: /capabilities/real-estate-debt-origination/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.7
    mcp: &id021
      status: unknown
    slug: rocket-companies
    status: profiled
    tags: &id022
    - Financial Services
    - Mortgage
    - Personal Finance
    - Real Estate
    url: /providers/rocket-companies/
  layer: domain
  name: Rocket Mortgage (Rocket Companies)
  provider: rocket-companies
  says: lists Rocket Mortgage (Rocket Companies) as an integration
  source: https://www.redfin.com/about/data-quality-on-redfin
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/real-estate-home-search/redfin/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id003
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id004
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id005
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id006
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 12.0
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id007
  name: Comscore
  slug: comscore
  status: profiled
  tags: *id008
  url: /providers/comscore/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id009
  name: Facebook Analytics
  slug: facebook
  status: profiled
  tags: *id010
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id011
  name: Firebase (Crashlytics)
  slug: google-firebase
  status: profiled
  tags: *id012
  url: /providers/google-firebase/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id013
  name: Fizber.com
  slug: fizber
  status: profiled
  tags: *id014
  url: /providers/fizber/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id015
  name: FSBO.com
  slug: fsbo-com
  status: profiled
  tags: *id016
  url: /providers/fsbo-com/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id017
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id018
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id019
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id020
  url: /providers/google-tag-manager/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.7
  mcp: *id021
  name: Rocket Mortgage (Rocket Companies)
  slug: rocket-companies
  status: profiled
  tags: *id022
  url: /providers/rocket-companies/
siblings:
- name: Flathunter
  rows: 14
  url: /applications/real-estate-home-search/flathunter/
- name: HomeHarvest
  rows: 1
  url: /applications/real-estate-home-search/homeharvest/
- name: Real Geeks
  rows: 10
  url: /applications/real-estate-home-search/real-geeks/
- name: Realtor.com
  rows: 13
  url: /applications/real-estate-home-search/realtor-com/
- name: Rightmove
  rows: 6
  url: /applications/real-estate-home-search/rightmove/
- name: Zillow
  rows: 14
  url: /applications/real-estate-home-search/zillow/
sitemap: true
title: 'Redfin: Real Estate & Home Search reference app'
---
