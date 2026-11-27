---
app: Krayin CRM
app_slug: krayin-crm
app_url: https://github.com/krayin/laravel-crm
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Google Contacts
  url: /capabilities/customer-data-management/
  via_parent: null
category:
  id: crm-sales
  name: CRM & Sales Pipeline
  url: /applications/crm-sales/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/krayin/laravel-crm/master/composer.json
- route: source code
  url: https://github.com/krayin/laravel-crm/tree/master/packages/Webkul
integrations:
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id001
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id002
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: domain
  name: Google Contacts
  provider: google-people
  says: ships the Google Contacts SDK or integration code
  source: https://github.com/krayin/laravel-crm/tree/master/packages/Webkul
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crm-sales/krayin-crm/
providers:
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id001
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id002
  url: /providers/google-people/
siblings:
- name: EspoCRM
  rows: 14
  url: /applications/crm-sales/espocrm/
- name: HubSpot
  rows: 6
  url: /applications/crm-sales/hubspot/
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
title: 'Krayin CRM: CRM & Sales Pipeline reference app'
---
