---
app: SurveyMonkey
app_slug: surveymonkey
app_url: https://www.surveymonkey.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Salesforce Marketing Cloud
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Audience Studio (Krux)
  url: /capabilities/digital-marketing-management/
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
  - Google Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: customer-feedback-nps
  name: Customer Feedback & NPS
  url: /applications/customer-feedback-nps/
counts:
  declared: 0
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
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
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id005
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id006
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Audience Studio (Krux)
  provider: salesforce-marketing-cloud
  says: ships the Audience Studio (Krux) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
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
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Crashlytics
  provider: firebase
  says: ships the Google Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
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
    mcp: &id009
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id010
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: domain
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: ships the Salesforce Marketing Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/customer-feedback-nps/surveymonkey/
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
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id005
  name: Audience Studio (Krux)
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id006
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Google Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id009
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id010
  url: /providers/mixpanel/
siblings:
- name: Canny
  rows: 18
  url: /applications/customer-feedback-nps/canny/
- name: ClearFlask
  rows: 15
  url: /applications/customer-feedback-nps/clearflask/
- name: Fider
  rows: 8
  url: /applications/customer-feedback-nps/fider/
- name: Formbricks
  rows: 22
  url: /applications/customer-feedback-nps/formbricks/
- name: Retently
  rows: 17
  url: /applications/customer-feedback-nps/retently/
- name: Survicate
  rows: 25
  url: /applications/customer-feedback-nps/survicate/
sitemap: true
title: 'SurveyMonkey: Customer Feedback & NPS reference app'
---
