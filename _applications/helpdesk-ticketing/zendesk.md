---
app: Zendesk
app_slug: zendesk
app_url: https://www.zendesk.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics / Crashlytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: helpdesk-ticketing
  name: Help Desk & Customer Support
  url: /applications/helpdesk-ticketing/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
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
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id003
      status: none
    slug: segment
    status: profiled
    tags: &id004
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/helpdesk-ticketing/zendesk/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id001
  name: Google Firebase Analytics / Crashlytics
  slug: firebase
  status: profiled
  tags: *id002
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id003
  name: Segment
  slug: segment
  status: profiled
  tags: *id004
  url: /providers/segment/
siblings:
- name: Chatwoot
  rows: 33
  url: /applications/helpdesk-ticketing/chatwoot/
- name: FreeScout
  rows: 12
  url: /applications/helpdesk-ticketing/freescout/
- name: Freshdesk
  rows: 6
  url: /applications/helpdesk-ticketing/freshdesk/
- name: Help Scout
  rows: 24
  url: /applications/helpdesk-ticketing/help-scout/
- name: Intercom
  rows: 1
  url: /applications/helpdesk-ticketing/intercom/
- name: Zammad
  rows: 23
  url: /applications/helpdesk-ticketing/zammad/
sitemap: true
title: 'Zendesk: Help Desk & Customer Support reference app'
---
