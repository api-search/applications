---
app: Walgreens
app_slug: walgreens
app_url: https://www.walgreens.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20.20
  key: AE-130.20.20
  layer: domain
  name: Personal Health Records
  providers:
  - Apple Health app
  url: /capabilities/wearable-health-data-sync/
  via_parent: Wearable & Health Data Sync
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
  - Branch
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
  - Adobe Experience Cloud
  - Firebase
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
  id: pharmacy-prescriptions
  name: Pharmacy & Prescriptions
  url: /applications/pharmacy-prescriptions/
counts:
  declared: 1
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
- route: store listing
  url: https://apps.apple.com/us/app/walgreens/id335364882
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.usablenet.mobile.walgreen
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
    agent_readiness: 53.0
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id002
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id003
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    mcp: &id006
      status: none
    slug: branch-io
    status: profiled
    tags: &id007
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id008
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id009
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    mcp: &id010
      status: none
    slug: google-admob
    status: profiled
    tags: &id011
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    mcp: &id012
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id013
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    mcp: &id014
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id015
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.20
    key: AE-130.20.20
    name: Personal Health Records
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id004
      status: none
    slug: apple
    status: profiled
    tags: &id005
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Health app
  provider: apple
  says: lists Apple Health app as an integration
  source: https://apps.apple.com/us/app/walgreens/id335364882
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pharmacy-prescriptions/walgreens/
providers:
- agent_band: agent-ready
  agent_readiness: 53.0
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id002
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id003
  url: /providers/adobe-experience-cloud/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id004
  name: Apple Health app
  slug: apple
  status: profiled
  tags: *id005
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id006
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id007
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id008
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id009
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id010
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id011
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id012
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id013
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id014
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id015
  url: /providers/google-tag-manager/
siblings:
- name: CVS Health
  rows: 8
  url: /applications/pharmacy-prescriptions/cvs-health/
- name: GoodRx
  rows: 8
  url: /applications/pharmacy-prescriptions/goodrx/
- name: Medisafe
  rows: 9
  url: /applications/pharmacy-prescriptions/medisafe/
- name: Medplum
  rows: 11
  url: /applications/pharmacy-prescriptions/medplum/
- name: OpenEMR
  rows: 11
  url: /applications/pharmacy-prescriptions/openemr/
sitemap: true
title: 'Walgreens: Pharmacy & Prescriptions reference app'
---
