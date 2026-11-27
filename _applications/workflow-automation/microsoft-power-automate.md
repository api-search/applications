---
app: Microsoft Power Automate
app_slug: microsoft-power-automate
app_url: https://www.microsoft.com/power-platform/products/power-automate
author: API Evangelist
capabilities:
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
  id: workflow-automation
  name: Workflow Automation & iPaaS
  url: /applications/workflow-automation/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.flow/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.flow/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/workflow-automation/microsoft-power-automate/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
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
- name: IFTTT
  rows: 3
  url: /applications/workflow-automation/ifttt/
- name: n8n
  rows: 39
  url: /applications/workflow-automation/n8n/
- name: Windmill
  rows: 12
  url: /applications/workflow-automation/windmill/
sitemap: true
title: 'Microsoft Power Automate: Workflow Automation & iPaaS reference app'
---
