---
app: IFTTT
app_slug: ifttt
app_url: https://ifttt.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google Firebase (Crashlytics + Analytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Mixpanel
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: workflow-automation
  name: Workflow Automation & iPaaS
  url: /applications/workflow-automation/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
integrations:
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id002
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase (Crashlytics + Analytics)
  provider: firebase
  says: ships the Google Firebase (Crashlytics + Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
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
    mcp: &id003
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id004
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id005
      status: none
    slug: segment
    status: profiled
    tags: &id006
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/workflow-automation/ifttt/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Google Firebase (Crashlytics + Analytics)
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id003
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id004
  url: /providers/mixpanel/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id005
  name: Segment
  slug: segment
  status: profiled
  tags: *id006
  url: /providers/segment/
siblings:
- name: Activepieces
  rows: 15
  url: /applications/workflow-automation/activepieces/
- name: Automatisch
  rows: 76
  url: /applications/workflow-automation/automatisch/
- name: Huginn
  rows: 25
  url: /applications/workflow-automation/huginn/
- name: Microsoft Power Automate
  rows: 1
  url: /applications/workflow-automation/microsoft-power-automate/
- name: n8n
  rows: 39
  url: /applications/workflow-automation/n8n/
- name: Windmill
  rows: 12
  url: /applications/workflow-automation/windmill/
sitemap: true
title: 'IFTTT: Workflow Automation & iPaaS reference app'
---
