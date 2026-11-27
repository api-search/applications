---
app: Dialpad
app_slug: dialpad
app_url: https://www.dialpad.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: voip-call-center
  name: VoIP, Phone & Contact Center
  url: /applications/voip-call-center/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.dialpad.com/integrations/
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
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.dialpad.com/integrations/
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id004
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.dialpad.com/integrations/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id005
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id006
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.dialpad.com/integrations/
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
  source: https://www.dialpad.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id009
      status: none
    slug: zendesk
    status: profiled
    tags: &id010
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.dialpad.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/voip-call-center/dialpad/
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
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id003
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id004
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id005
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id006
  url: /providers/hubspot/
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
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id009
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id010
  url: /providers/zendesk/
siblings:
- name: Aircall
  rows: 42
  url: /applications/voip-call-center/aircall/
- name: Fonoster
  rows: 14
  url: /applications/voip-call-center/fonoster/
- name: jambonz
  rows: 36
  url: /applications/voip-call-center/jambonz/
- name: JustCall
  rows: 36
  url: /applications/voip-call-center/justcall/
- name: Talkdesk
  rows: 25
  url: /applications/voip-call-center/talkdesk/
sitemap: true
title: 'Dialpad: VoIP, Phone & Contact Center reference app'
---
