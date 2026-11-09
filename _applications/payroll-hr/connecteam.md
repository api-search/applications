---
app: Connecteam
app_slug: connecteam
app_url: https://connecteam.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: payroll-hr
  name: HR, Payroll & People Ops
  url: /applications/payroll-hr/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
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
    agent_readiness: 53.1
    band: exemplar
    in_catalog: true
    kin_score: 78.5
    mcp: &id001
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id002
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id004
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
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
    kin_score: 80.6
    mcp: &id005
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id006
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/payroll-hr/connecteam/
providers:
- agent_band: agent-ready
  agent_readiness: 53.1
  band: exemplar
  in_catalog: true
  kin_score: 78.5
  mcp: *id001
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id002
  url: /providers/bugsnag/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id003
  name: Firebase (Crashlytics / Analytics)
  slug: firebase
  status: profiled
  tags: *id004
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
siblings:
- name: ADP Mobile Solutions
  rows: 5
  url: /applications/payroll-hr/adp-mobile-solutions/
- name: Deel
  rows: 35
  url: /applications/payroll-hr/deel/
- name: Frappe HR
  rows: 1
  url: /applications/payroll-hr/frappe-hr/
- name: Homebase
  rows: 19
  url: /applications/payroll-hr/homebase/
- name: Horilla
  rows: 7
  url: /applications/payroll-hr/horilla/
- name: OrangeHRM
  rows: 0
  url: /applications/payroll-hr/orangehrm/
- name: Paylocity
  rows: 4
  url: /applications/payroll-hr/paylocity/
- name: Workday
  rows: 2
  url: /applications/payroll-hr/workday/
sitemap: true
title: 'Connecteam: HR, Payroll & People Ops reference app'
---
