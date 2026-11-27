---
app: Splitwise
app_slug: splitwise
app_url: https://www.splitwise.com/
author: API Evangelist
capabilities:
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
  - Amazon Analytics (Amazon insights)
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: expense-management
  name: Expense & Spend Management
  url: /applications/expense-management/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
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
  name: Amazon Analytics (Amazon insights)
  provider: amazon-web-services
  says: ships the Amazon Analytics (Amazon insights) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id004
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Crashlytics
  provider: firebase
  says: ships the Google Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/expense-management/splitwise/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: Amazon Analytics (Amazon insights)
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Google Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
siblings:
- name: Brex
  rows: 82
  url: /applications/expense-management/brex/
- name: Expensify
  rows: 82
  url: /applications/expense-management/expensify/
- name: IHateMoney
  rows: 1
  url: /applications/expense-management/ihatemoney/
- name: Ramp
  rows: 62
  url: /applications/expense-management/ramp/
- name: SAP Concur
  rows: 3
  url: /applications/expense-management/sap-concur/
- name: Spliit
  rows: 4
  url: /applications/expense-management/spliit/
sitemap: true
title: 'Splitwise: Expense & Spend Management reference app'
---
