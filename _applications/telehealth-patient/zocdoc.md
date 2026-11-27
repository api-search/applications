---
app: Zocdoc
app_slug: zocdoc
app_url: https://www.zocdoc.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - Salesforce Marketing Cloud
  url: /capabilities/customer-lifecycle-engagement/
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
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: common
  name: Product Telemetry & Experimentation Management
  providers:
  - Optimizely
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: telehealth-patient
  name: Telehealth & Patient Apps
  url: /applications/telehealth-patient/
counts:
  declared: 0
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
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
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id001
      status: none
    slug: branch-io
    status: profiled
    tags: &id002
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
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
    mcp: &id003
      status: none
    slug: google-admob
    status: profiled
    tags: &id004
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
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
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id006
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id007
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id008
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: common
  name: Optimizely
  provider: optimizely
  says: ships the Optimizely SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id009
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id010
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: ships the Salesforce Marketing Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
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
    mcp: &id011
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id012
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/telehealth-patient/zocdoc/
providers:
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id001
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id002
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id003
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id004
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id007
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id008
  url: /providers/optimizely/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id009
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id010
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id011
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id012
  url: /providers/sentry-system/
siblings:
- name: Doctolib
  rows: 3
  url: /applications/telehealth-patient/doctolib/
- name: Doctor On Demand (Included Health)
  rows: 6
  url: /applications/telehealth-patient/doctor-on-demand-included-health/
- name: MDLIVE
  rows: 2
  url: /applications/telehealth-patient/mdlive/
- name: Medplum
  rows: 26
  url: /applications/telehealth-patient/medplum/
- name: MyChart (Epic)
  rows: 0
  url: /applications/telehealth-patient/mychart-epic/
- name: OpenEMR
  rows: 13
  url: /applications/telehealth-patient/openemr/
- name: Ottehr
  rows: 12
  url: /applications/telehealth-patient/ottehr/
- name: Teladoc
  rows: 8
  url: /applications/telehealth-patient/teladoc/
sitemap: true
title: 'Zocdoc: Telehealth & Patient Apps reference app'
---
