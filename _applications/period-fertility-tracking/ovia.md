---
app: Ovia
app_slug: ovia
app_url: https://www.oviahealth.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20.10
  key: AE-130.20.10
  layer: domain
  name: Wearable Data Aggregation
  providers:
  - Apple
  - Google Fit
  url: /capabilities/wearable-health-data-sync/
  via_parent: Wearable & Health Data Sync
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Apptentive
  url: /capabilities/customer-feedback-management/
  via_parent: null
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
  - Google AdMob
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
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amazon Mobile Analytics (Amplify)
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: period-fertility-tracking
  name: Period, Fertility & Pregnancy Tracking
  url: /applications/period-fertility-tracking/
counts:
  declared: 2
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
- route: documentation
  url: https://www.oviahealth.com/
integrations:
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Mobile Analytics (Amplify)
  provider: amazon-web-services
  says: ships the Amazon Mobile Analytics (Amplify) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    mcp: &id007
      status: none
    slug: apptentive
    status: profiled
    tags: &id008
    - Company
    - Customer Feedback
    - Enterprise
    - Mobile
    url: /providers/apptentive/
  layer: common
  name: Apptentive
  provider: apptentive
  says: ships the Apptentive SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    mcp: &id009
      status: none
    slug: google-admob
    status: profiled
    tags: &id010
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    mcp: &id015
      status: unchecked
    slug: helpshift
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: common
  name: Helpshift
  provider: helpshift
  says: ships the Helpshift SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
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
    mcp: &id017
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id018
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ovuline.fertility/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
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
  layer: domain
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://www.oviahealth.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id013
      status: none
    slug: google-fitness
    status: profiled
    tags: &id014
    - Activity Tracking
    - Fitness
    - Google
    - Health
    url: /providers/google-fitness/
  layer: domain
  name: Google Fit
  provider: google-fitness
  says: lists Google Fit as an integration
  source: https://www.oviahealth.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/period-fertility-tracking/ovia/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: Amazon Mobile Analytics (Amplify)
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id005
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id006
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id007
  name: Apptentive
  slug: apptentive
  status: profiled
  tags: *id008
  url: /providers/apptentive/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id009
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id010
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id011
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id012
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id013
  name: Google Fit
  slug: google-fitness
  status: profiled
  tags: *id014
  url: /providers/google-fitness/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Helpshift
  slug: helpshift
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id017
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id018
  url: /providers/sentry-system/
siblings:
- name: Clue
  rows: 13
  url: /applications/period-fertility-tracking/clue/
- name: drip
  rows: 0
  url: /applications/period-fertility-tracking/drip/
- name: Euki
  rows: 0
  url: /applications/period-fertility-tracking/euki/
- name: Flo
  rows: 6
  url: /applications/period-fertility-tracking/flo/
- name: Mensinator
  rows: 0
  url: /applications/period-fertility-tracking/mensinator/
- name: Natural Cycles
  rows: 7
  url: /applications/period-fertility-tracking/natural-cycles/
sitemap: true
title: 'Ovia: Period, Fertility & Pregnancy Tracking reference app'
---
