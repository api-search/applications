---
app: Salesloft
app_slug: salesloft
app_url: https://www.salesloft.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.20
  key: AE-230.30.20
  layer: domain
  name: Lead Data
  providers:
  - LinkedIn Sales Navigator
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: sales-engagement
  name: Sales Engagement & Dialers
  url: /applications/sales-engagement/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.salesloft.com/platform/integrations
integrations:
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
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id001
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id002
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.salesloft.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.20
    key: AE-230.30.20
    name: Lead Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id003
      status: none
    slug: linkedin
    status: profiled
    tags: &id004
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn Sales Navigator
  provider: linkedin
  says: lists LinkedIn Sales Navigator as an integration
  source: https://www.salesloft.com/platform/integrations
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id006
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook
  provider: microsoft-outlook
  says: lists Outlook as an integration
  source: https://www.salesloft.com/platform/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id007
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id008
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.salesloft.com/platform/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sales-engagement/salesloft/
providers:
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id001
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id002
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id003
  name: LinkedIn Sales Navigator
  slug: linkedin
  status: profiled
  tags: *id004
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id005
  name: Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id006
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id007
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id008
  url: /providers/salesforce/
siblings:
- name: Aircall
  rows: 54
  url: /applications/sales-engagement/aircall/
- name: Apollo.io
  rows: 21
  url: /applications/sales-engagement/apollo-io/
- name: Close
  rows: 34
  url: /applications/sales-engagement/close/
- name: lemlist
  rows: 43
  url: /applications/sales-engagement/lemlist/
- name: VICIdial
  rows: 1
  url: /applications/sales-engagement/vicidial/
sitemap: true
title: 'Salesloft: Sales Engagement & Dialers reference app'
---
