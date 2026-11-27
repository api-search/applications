---
app: Salesforce
app_slug: salesforce
app_url: https://www.salesforce.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: crm-sales
  name: CRM & Sales Pipeline
  url: /applications/crm-sales/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.salesforce.chatter/latest/
- route: integrations page
  url: https://www.salesforce.com/products/integrations/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.salesforce.chatter/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crm-sales/salesforce/
providers:
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id001
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id002
  url: /providers/bugsnag/
siblings:
- name: EspoCRM
  rows: 14
  url: /applications/crm-sales/espocrm/
- name: HubSpot
  rows: 6
  url: /applications/crm-sales/hubspot/
- name: Krayin CRM
  rows: 1
  url: /applications/crm-sales/krayin-crm/
- name: Pipedrive
  rows: 17
  url: /applications/crm-sales/pipedrive/
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
title: 'Salesforce: CRM & Sales Pipeline reference app'
---
