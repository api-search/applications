---
app: Frappe HR
app_slug: frappe-hr
app_url: https://github.com/frappe/hrms
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: payroll-hr
  name: HR, Payroll & People Ops
  url: /applications/payroll-hr/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/frappe/hrms/develop/frontend/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/frappe/hrms/develop/pyproject.toml
- route: source code
  url: https://raw.githubusercontent.com/frappe/hrms/develop/frontend/public/frappe-push-notification.js
- route: source code
  url: https://raw.githubusercontent.com/frappe/hrms/develop/hrms/hooks.py
- route: source code
  url: https://raw.githubusercontent.com/frappe/hrms/develop/hrms/telemetry.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
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
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://raw.githubusercontent.com/frappe/hrms/develop/frontend/public/frappe-push-notification.js
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/payroll-hr/frappe-hr/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id001
  name: Firebase Cloud Messaging
  slug: firebase
  status: profiled
  tags: *id002
  url: /providers/firebase/
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
title: 'Frappe HR: HR, Payroll & People Ops reference app'
---
