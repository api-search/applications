---
app: HubSpot
app_slug: hubspot
app_url: https://www.hubspot.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Wootric
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics)
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase (Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: crm-sales
  name: CRM & Sales Pipeline
  url: /applications/crm-sales/
counts:
  declared: 2
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
- route: documentation
  url: https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id003
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Analytics)
  provider: firebase
  says: ships the Firebase (Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    agent_readiness: 45.7
    band: exemplar
    in_catalog: true
    kin_score: 76.5
    mcp: &id008
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id009
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id010
      status: none
    slug: wootric
    status: profiled
    tags: &id011
    - CES
    - CSAT
    - Customer Experience
    - NPS
    url: /providers/wootric/
  layer: common
  name: Wootric
  provider: wootric
  says: ships the Wootric SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id004
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id005
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
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
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id006
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id007
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://knowledge.hubspot.com/connected-email/connect-your-inbox-to-hubspot
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crm-sales/hubspot/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id002
  name: Firebase (Analytics)
  slug: firebase
  status: profiled
  tags: *id003
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id004
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id005
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id006
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id007
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id008
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id009
  url: /providers/new-relic/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id010
  name: Wootric
  slug: wootric
  status: profiled
  tags: *id011
  url: /providers/wootric/
siblings:
- name: EspoCRM
  rows: 14
  url: /applications/crm-sales/espocrm/
- name: Krayin CRM
  rows: 1
  url: /applications/crm-sales/krayin-crm/
- name: Pipedrive
  rows: 17
  url: /applications/crm-sales/pipedrive/
- name: Salesforce
  rows: 1
  url: /applications/crm-sales/salesforce/
- name: SuiteCRM
  rows: 10
  url: /applications/crm-sales/suitecrm/
- name: Twenty
  rows: 20
  url: /applications/crm-sales/twenty/
- name: Zoho CRM
  rows: 0
  url: /applications/crm-sales/zoho-crm/
sitemap: true
title: 'HubSpot: CRM & Sales Pipeline reference app'
---
