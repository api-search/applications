---
app: Workday
app_slug: workday
app_url: https://www.workday.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.60
  key: employee-experience-management
  layer: common
  name: Employee Experience Management
  providers:
  - Qualtrics
  url: /capabilities/employee-experience-management/
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
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id002
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-300.60
    key: employee-experience-management
    name: Employee Experience Management
    url: /capabilities/employee-experience-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 20.0
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id003
      status: none
    slug: qualtrics
    status: profiled
    tags: &id004
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: common
  name: Qualtrics
  provider: qualtrics
  says: ships the Qualtrics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/payroll-hr/workday/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id001
  name: Firebase (Crashlytics / Analytics)
  slug: firebase
  status: profiled
  tags: *id002
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 20.0
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id003
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id004
  url: /providers/qualtrics/
siblings:
- name: ADP Mobile Solutions
  rows: 5
  url: /applications/payroll-hr/adp-mobile-solutions/
- name: Connecteam
  rows: 3
  url: /applications/payroll-hr/connecteam/
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
sitemap: true
title: 'Workday: HR, Payroll & People Ops reference app'
---
