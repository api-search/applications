---
app: SAP Concur
app_slug: sap-concur
app_url: https://www.concur.com/
author: API Evangelist
capabilities:
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Dynatrace
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Adobe Experience Cloud
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: expense-management
  name: Expense & Spend Management
  url: /applications/expense-management/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
- route: integrations page
  url: https://www.concur.com/app-center
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
    agent_readiness: 54.1
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id002
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
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
    agent_readiness: 26.0
    band: developing
    in_catalog: true
    kin_score: 40.4
    mcp: &id003
      status: none
    slug: apptentive
    status: profiled
    tags: &id004
    - Company
    - Customer Feedback
    - Enterprise
    - Mobile
    url: /providers/apptentive/
  layer: common
  name: Apptentive
  provider: apptentive
  says: ships the Apptentive SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
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
    agent_readiness: 44.7
    band: exemplar
    in_catalog: true
    kin_score: 84.1
    mcp: &id005
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id006
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
  layer: common
  name: Dynatrace
  provider: dynatrace
  says: ships the Dynatrace SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/expense-management/sap-concur/
providers:
- agent_band: agent-ready
  agent_readiness: 54.1
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id001
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id002
  url: /providers/adobe-experience-cloud/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: developing
  in_catalog: true
  kin_score: 40.4
  mcp: *id003
  name: Apptentive
  slug: apptentive
  status: profiled
  tags: *id004
  url: /providers/apptentive/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 84.1
  mcp: *id005
  name: Dynatrace
  slug: dynatrace
  status: profiled
  tags: *id006
  url: /providers/dynatrace/
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
- name: Spliit
  rows: 4
  url: /applications/expense-management/spliit/
- name: Splitwise
  rows: 2
  url: /applications/expense-management/splitwise/
sitemap: true
title: 'SAP Concur: Expense & Spend Management reference app'
---
