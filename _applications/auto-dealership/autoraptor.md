---
app: AutoRaptor
app_slug: autoraptor
app_url: https://www.autoraptor.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1320.10
  key: credit-origination-management
  layer: domain
  name: Credit Origination Management
  providers:
  - Dealertrack
  - RouteOne
  url: /capabilities/credit-origination-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: mailbox-calendar-sync
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: auto-dealership
  name: Auto Dealership Management
  url: /applications/auto-dealership/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.autoraptor.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1320.10
    key: credit-origination-management
    name: Credit Origination Management
    url: /capabilities/credit-origination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id001
      status: unknown
    slug: dealertrack
    status: profiled
    tags: &id002
    - Automotive
    - DMS
    - Dealer Management System
    - Dealership
    url: /providers/dealertrack/
  layer: domain
  name: Dealertrack
  provider: dealertrack
  says: lists Dealertrack as an integration
  source: https://www.autoraptor.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: mailbox-calendar-sync
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
  source: https://www.autoraptor.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.10
    key: credit-origination-management
    name: Credit Origination Management
    url: /capabilities/credit-origination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id005
      status: unchecked
    slug: routeone
    status: profiled
    tags: &id006
    - Automotive
    - Finance
    - Fintech
    - Insurance
    url: /providers/routeone/
  layer: domain
  name: RouteOne
  provider: routeone
  says: lists RouteOne as an integration
  source: https://www.autoraptor.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/autoraptor/
providers:
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id001
  name: Dealertrack
  slug: dealertrack
  status: profiled
  tags: *id002
  url: /providers/dealertrack/
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
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id005
  name: RouteOne
  slug: routeone
  status: profiled
  tags: *id006
  url: /providers/routeone/
siblings:
- name: AutoHub
  rows: 17
  url: /applications/auto-dealership/autohub/
- name: Autosoft DMS
  rows: 16
  url: /applications/auto-dealership/autosoft-dms/
- name: Cox Automotive Deal Central
  rows: 11
  url: /applications/auto-dealership/cox-automotive-deal-central/
- name: DealerBuilt (LightYear DMS)
  rows: 36
  url: /applications/auto-dealership/dealerbuilt-lightyear-dms/
- name: DealersCloud
  rows: 19
  url: /applications/auto-dealership/dealerscloud/
- name: DealerSocket
  rows: 1
  url: /applications/auto-dealership/dealersocket/
- name: GetMyAuto
  rows: 36
  url: /applications/auto-dealership/getmyauto/
sitemap: true
title: 'AutoRaptor: Auto Dealership Management reference app'
---
