---
app: Medisafe
app_slug: medisafe
app_url: https://www.medisafe.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.20.20
  key: AE-130.20.20
  layer: domain
  name: Personal Health Records
  providers:
  - Apple HealthKit
  url: /capabilities/wearable-health-data-sync/
  via_parent: Wearable & Health Data Sync
- attribution: API Evangelist extension
  id: AE-920
  key: AE-920
  layer: common
  name: Barcode, RFID & Mobile Data Capture
  providers:
  - Scandit
  url: /capabilities/storage-and-inventory-operations-management/
  via_parent: Storage and Inventory Operations Management
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - AppNexus
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
  - Bugsnag
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amazon Web Services (Mobile Analytics / Amplify)
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - IAB Tech Lab (Open Measurement)
  url: /capabilities/programmatic-sales-management/
  via_parent: null
category:
  id: pharmacy-prescriptions
  name: Pharmacy & Prescriptions
  url: /applications/pharmacy-prescriptions/
counts:
  declared: 1
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
- route: store listing
  url: https://apps.apple.com/us/app/medisafe-medication-management/id573916946
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.medisafe.android.client
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
    mcp: &id002
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id003
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services (Mobile Analytics / Amplify)
  provider: amazon-web-services
  says: ships the Amazon Web Services (Mobile Analytics / Amplify) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    agent_readiness: 8.4
    band: thin
    in_catalog: true
    kin_score: 38.5
    mcp: &id006
      status: unchecked
    slug: appnexus
    status: profiled
    tags: &id007
    - AdTech
    - Advertising
    - Company
    - Programmatic
    url: /providers/appnexus/
  layer: common
  name: AppNexus
  provider: appnexus
  says: ships the AppNexus SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    mcp: &id008
      status: none
    slug: branch-io
    status: profiled
    tags: &id009
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id010
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id011
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    mcp: &id012
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id013
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    mcp: &id014
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id015
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Tech Lab (Open Measurement)
  provider: iab-tech-lab
  says: ships the IAB Tech Lab (Open Measurement) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-920
    key: AE-920
    name: Barcode, RFID & Mobile Data Capture
    url: /capabilities/storage-and-inventory-operations-management/
    via_parent: Storage and Inventory Operations Management
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 7.0
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id016
      source: https://ssl.scandit.com/mcp
      status: verified
    slug: scandit
    status: profiled
    tags: &id017
    - Barcode Scanning
    - Company
    - Data Capture
    - Frontier Tech
    url: /providers/scandit/
  layer: common
  name: Scandit
  provider: scandit
  says: ships the Scandit SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
  name: Apple HealthKit
  provider: apple
  says: lists Apple HealthKit as an integration
  source: https://apps.apple.com/us/app/medisafe-medication-management/id573916946
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pharmacy-prescriptions/medisafe/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id002
  name: Amazon Web Services (Mobile Analytics / Amplify)
  slug: amazon-web-services
  status: profiled
  tags: *id003
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id004
  name: Apple HealthKit
  slug: apple
  status: profiled
  tags: *id005
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 8.4
  band: thin
  in_catalog: true
  kin_score: 38.5
  mcp: *id006
  name: AppNexus
  slug: appnexus
  status: profiled
  tags: *id007
  url: /providers/appnexus/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id008
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id009
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id010
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id011
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id012
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id013
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id014
  name: IAB Tech Lab (Open Measurement)
  slug: iab-tech-lab
  status: profiled
  tags: *id015
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 7.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id016
  name: Scandit
  slug: scandit
  status: profiled
  tags: *id017
  url: /providers/scandit/
siblings:
- name: CVS Health
  rows: 8
  url: /applications/pharmacy-prescriptions/cvs-health/
- name: GoodRx
  rows: 8
  url: /applications/pharmacy-prescriptions/goodrx/
- name: Medplum
  rows: 11
  url: /applications/pharmacy-prescriptions/medplum/
- name: OpenEMR
  rows: 11
  url: /applications/pharmacy-prescriptions/openemr/
- name: Walgreens
  rows: 8
  url: /applications/pharmacy-prescriptions/walgreens/
sitemap: true
title: 'Medisafe: Pharmacy & Prescriptions reference app'
---
