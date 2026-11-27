---
app: Frappe Education
app_slug: frappe-education
app_url: https://github.com/frappe/education
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - ERPNext
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Razorpay
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: school-admin-sis
  name: School Administration & SIS
  url: /applications/school-admin-sis/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: source code
  url: https://github.com/frappe/education/blob/develop/education/education/billing.py
- route: source code
  url: https://github.com/frappe/education/blob/develop/education/education/doctype/education_settings/education_settings.json
integrations:
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id001
      source: https://github.com/frappe/mcp
      status: verified
    slug: erpnext
    status: profiled
    tags: &id002
    - Accounting
    - ERP
    - Inventory
    - Manufacturing
    url: /providers/erpnext/
  layer: common
  name: ERPNext
  provider: erpnext
  says: ships the ERPNext SDK or integration code
  source: https://github.com/frappe/education/blob/develop/education/education/billing.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id003
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id004
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: common
  name: Razorpay
  provider: razorpay
  says: ships the Razorpay SDK or integration code
  source: https://github.com/frappe/education/blob/develop/education/education/billing.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/school-admin-sis/frappe-education/
providers:
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id001
  name: ERPNext
  slug: erpnext
  status: profiled
  tags: *id002
  url: /providers/erpnext/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id003
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id004
  url: /providers/razorpay/
siblings:
- name: Alma
  rows: 1
  url: /applications/school-admin-sis/alma/
- name: Classe365
  rows: 32
  url: /applications/school-admin-sis/classe365/
- name: Gibbon
  rows: 11
  url: /applications/school-admin-sis/gibbon/
- name: Gradelink
  rows: 11
  url: /applications/school-admin-sis/gradelink/
- name: Infinite Campus
  rows: 2
  url: /applications/school-admin-sis/infinite-campus/
- name: PowerSchool SIS
  rows: 2
  url: /applications/school-admin-sis/powerschool-sis/
- name: RosarioSIS
  rows: 1
  url: /applications/school-admin-sis/rosariosis/
- name: Veracross
  rows: 5
  url: /applications/school-admin-sis/veracross/
sitemap: true
title: 'Frappe Education: School Administration & SIS reference app'
---
