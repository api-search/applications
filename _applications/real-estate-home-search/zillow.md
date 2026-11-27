---
app: Zillow
app_slug: zillow
app_url: https://www.zillow.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Apptentive (Alchemer Mobile)
  url: /capabilities/customer-feedback-management/
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
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - Split (Harness FME)
  url: /capabilities/feature-flag-management/
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
  id: AE-120
  key: AE-120
  layer: common
  name: Location & Mapping
  providers:
  - Radar
  url: /capabilities/location-mapping/
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
  - Sentry
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
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Airship (Urbanairship)
  url: /capabilities/push-notifications/
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
  declared: 0
  observed: 14
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id002
      status: none
    slug: adjust
    status: profiled
    tags: &id003
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: Adjust
  provider: adjust
  says: ships the Adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id004
      source: https://github.com/urbanairship/agent-tools
      status: verified
    slug: airship
    status: profiled
    tags: &id005
    - Email
    - Mobile
    - Notification
    - Push
    url: /providers/airship/
  layer: common
  name: Airship (Urbanairship)
  provider: airship
  says: ships the Airship (Urbanairship) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.5
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id006
      status: none
    slug: apptentive
    status: profiled
    tags: &id007
    - Company
    - Customer Feedback
    - Enterprise
    - Mobile
    url: /providers/apptentive/
  layer: common
  name: Apptentive (Alchemer Mobile)
  provider: apptentive
  says: ships the Apptentive (Alchemer Mobile) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    mcp: &id008
      status: none
    slug: comscore
    status: profiled
    tags: &id009
    - Audience Analytics
    - Cloud Saas
    - Company
    - Media Measurement
    url: /providers/comscore/
  layer: common
  name: Comscore
  provider: comscore
  says: ships the Comscore SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    mcp: &id010
      status: none
    slug: facebook
    status: profiled
    tags: &id011
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    mcp: &id012
      status: none
    slug: google-admob
    status: profiled
    tags: &id013
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    mcp: &id014
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id015
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    mcp: &id016
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id017
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    mcp: &id018
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id019
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: AE-120
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id020
      source: https://mcp.radar.com/mcp
      status: verified
    slug: radar-io
    status: profiled
    tags: &id021
    - Geocoding
    - Geofencing
    - Location
    - Maps
    url: /providers/radar-io/
  layer: common
  name: Radar
  provider: radar-io
  says: ships the Radar SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
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
    kin_score: 80.7
    mcp: &id022
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id023
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id024
      status: none
    slug: split
    status: profiled
    tags: &id025
    - Experimentation
    - Feature Flags
    - Feature Management
    - Rollouts
    url: /providers/split/
  layer: common
  name: Split (Harness FME)
  provider: split
  says: ships the Split (Harness FME) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zillow.android.zillowmap/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/real-estate-home-search/zillow/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id002
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id003
  url: /providers/adjust/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id004
  name: Airship (Urbanairship)
  slug: airship
  status: profiled
  tags: *id005
  url: /providers/airship/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id006
  name: Apptentive (Alchemer Mobile)
  slug: apptentive
  status: profiled
  tags: *id007
  url: /providers/apptentive/
- agent_band: agent-aware
  agent_readiness: 12.0
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id008
  name: Comscore
  slug: comscore
  status: profiled
  tags: *id009
  url: /providers/comscore/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id010
  name: Facebook Analytics
  slug: facebook
  status: profiled
  tags: *id011
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id012
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id013
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id014
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id015
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id016
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id017
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id018
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id019
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id020
  name: Radar
  slug: radar-io
  status: profiled
  tags: *id021
  url: /providers/radar-io/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id022
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id023
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id024
  name: Split (Harness FME)
  slug: split
  status: profiled
  tags: *id025
  url: /providers/split/
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
- name: Redfin
  rows: 13
  url: /applications/real-estate-home-search/redfin/
- name: Rightmove
  rows: 6
  url: /applications/real-estate-home-search/rightmove/
sitemap: true
title: 'Zillow: Real Estate & Home Search reference app'
---
