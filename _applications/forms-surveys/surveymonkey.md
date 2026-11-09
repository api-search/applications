---
app: SurveyMonkey
app_slug: surveymonkey
app_url: https://www.surveymonkey.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Microsoft Power BI
  - tableau
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Salesforce Audience Studio (Krux)
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Salesforce Marketing Cloud
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
  - Google CrashLytics
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
  id: forms-surveys
  name: Forms & Surveys
  url: /applications/forms-surveys/
counts:
  declared: 3
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
- route: integrations page
  url: https://www.surveymonkey.com/apps/
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
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id006
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 60.3
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
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id011
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id012
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce Audience Studio (Krux)
  provider: salesforce
  says: ships the Salesforce Audience Studio (Krux) SDK or integration code
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: exemplar
    in_catalog: true
    kin_score: 80.5
    mcp: &id013
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id014
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: ships the Salesforce Marketing Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id007
      source: https://github.com/microsoft/powerbi-modeling-mcp
      status: verified
    slug: power-bi
    status: profiled
    tags: &id008
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Analysis
    url: /providers/power-bi/
  layer: domain
  name: Microsoft Power BI
  provider: power-bi
  says: lists Microsoft Power BI as an integration
  source: https://www.surveymonkey.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts: *id002
  layer: domain
  name: salesforce
  provider: salesforce
  says: lists salesforce as an integration
  source: https://www.surveymonkey.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.3
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id015
      source: https://github.com/tableau/tableau-mcp
      status: verified
    slug: tableau
    status: profiled
    tags: &id016
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Visualization
    url: /providers/tableau/
  layer: domain
  name: tableau
  provider: tableau
  says: lists tableau as an integration
  source: https://www.surveymonkey.com/apps/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/forms-surveys/surveymonkey/
providers:
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id003
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id004
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id005
  name: Google CrashLytics
  slug: firebase
  status: profiled
  tags: *id006
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id007
  name: Microsoft Power BI
  slug: power-bi
  status: profiled
  tags: *id008
  url: /providers/power-bi/
- agent_band: agent-ready
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id009
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id010
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id011
  name: Salesforce Audience Studio (Krux)
  slug: salesforce
  status: profiled
  tags: *id012
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: exemplar
  in_catalog: true
  kin_score: 80.5
  mcp: *id013
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id014
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 46.3
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id015
  name: tableau
  slug: tableau
  status: profiled
  tags: *id016
  url: /providers/tableau/
siblings:
- name: Formbricks
  rows: 16
  url: /applications/forms-surveys/formbricks/
- name: HeyForm
  rows: 6
  url: /applications/forms-surveys/heyform/
- name: Jotform
  rows: 32
  url: /applications/forms-surveys/jotform/
- name: LimeSurvey
  rows: 3
  url: /applications/forms-surveys/limesurvey/
- name: Typebot
  rows: 23
  url: /applications/forms-surveys/typebot/
- name: Typeform
  rows: 18
  url: /applications/forms-surveys/typeform/
sitemap: true
title: 'SurveyMonkey: Forms & Surveys reference app'
---
