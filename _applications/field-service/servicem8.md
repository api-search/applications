---
app: ServiceM8
app_slug: servicem8
app_url: https://www.servicem8.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - MailChimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - MYOB
  - QuickBooks Online
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Office 365
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe Payments
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2440.20
  key: rostering-and-scheduling-management
  layer: common
  name: Rostering and Scheduling Management
  providers:
  - Deputy
  url: /capabilities/rostering-and-scheduling-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 8
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.servicem8.com/addons
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id001
      status: none
    slug: deputy
    status: profiled
    tags: &id002
    - Employee Scheduling
    - Time and Attendance
    - Timesheets
    - Workforce Management
    url: /providers/deputy/
  layer: common
  name: Deputy
  provider: deputy
  says: lists Deputy as an integration
  source: https://www.servicem8.com/addons
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id003
      status: none
    slug: mailchimp
    status: profiled
    tags: &id004
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: MailChimp
  provider: mailchimp
  says: lists MailChimp as an integration
  source: https://www.servicem8.com/addons
  tier: declared
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id005
      status: none
    slug: myob
    status: profiled
    tags: &id006
    - Accounting
    - Bills
    - Business Management
    - Invoices
    url: /providers/myob/
  layer: common
  name: MYOB
  provider: myob
  says: lists MYOB as an integration
  source: https://www.servicem8.com/addons
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id008
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: common
  name: Office 365
  provider: microsoft-365
  says: lists Office 365 as an integration
  source: https://www.servicem8.com/addons
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id009
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id010
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.servicem8.com/addons
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id011
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id012
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe Payments
  provider: stripe
  says: lists Stripe Payments as an integration
  source: https://www.servicem8.com/addons
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id013
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id014
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.servicem8.com/addons
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id015
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id016
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.servicem8.com/addons
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/servicem8/
providers:
- agent_band: agent-ready
  agent_readiness: 30.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id001
  name: Deputy
  slug: deputy
  status: profiled
  tags: *id002
  url: /providers/deputy/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id003
  name: MailChimp
  slug: mailchimp
  status: profiled
  tags: *id004
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id005
  name: MYOB
  slug: myob
  status: profiled
  tags: *id006
  url: /providers/myob/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id007
  name: Office 365
  slug: microsoft-365
  status: profiled
  tags: *id008
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id009
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id010
  url: /providers/quickbooks/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id011
  name: Stripe Payments
  slug: stripe
  status: profiled
  tags: *id012
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id013
  name: Xero
  slug: xero
  status: profiled
  tags: *id014
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id015
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id016
  url: /providers/zapier/
siblings:
- name: Housecall Pro
  rows: 26
  url: /applications/field-service/housecall-pro/
- name: Jobber
  rows: 34
  url: /applications/field-service/jobber/
- name: OCA Field Service (Odoo)
  rows: 1
  url: /applications/field-service/oca-field-service-odoo/
- name: ServiceTitan
  rows: 3
  url: /applications/field-service/servicetitan/
- name: Tradify
  rows: 4
  url: /applications/field-service/tradify/
- name: Workiz
  rows: 16
  url: /applications/field-service/workiz/
sitemap: true
title: 'ServiceM8: Field Service & Dispatch reference app'
---
