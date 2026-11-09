---
app: Real Geeks
app_slug: real-geeks
app_url: https://www.realgeeks.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - BoomTown
  - kvCORE (BoldTrail)
  - KW Command
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60.10
  key: AE-150.60.10
  layer: common
  name: Async Video Messaging
  providers:
  - Dubb
  url: /capabilities/video-calling/
  via_parent: Video Calling
- attribution: API Evangelist extension
  id: AE-912
  key: AE-912
  layer: common
  name: Direct Mail APIs
  providers:
  - Thanks.io
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Constant Contact
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Apple Contacts
  - Google Contacts
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: real-estate-home-search
  name: Real Estate & Home Search
  url: /applications/real-estate-home-search/
counts:
  declared: 10
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.realgeeks.com/integrations/
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple Contacts
  provider: apple
  says: lists Apple Contacts as an integration
  source: https://www.realgeeks.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: boomtown
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: BoomTown
  provider: boomtown
  says: lists BoomTown as an integration
  source: https://www.realgeeks.com/integrations/
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id005
      status: none
    slug: constant-contact
    status: profiled
    tags: &id006
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://www.realgeeks.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60.10
    key: AE-150.60.10
    name: Async Video Messaging
    url: /capabilities/video-calling/
    via_parent: Video Calling
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id007
      status: unknown
    slug: dubb
    status: profiled
    tags: &id008
    - Company
    url: /providers/dubb/
  layer: common
  name: Dubb
  provider: dubb
  says: lists Dubb as an integration
  source: https://www.realgeeks.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id009
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id010
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: common
  name: Google Contacts
  provider: google-people
  says: lists Google Contacts as an integration
  source: https://www.realgeeks.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id011
      status: none
    slug: google-sheets
    status: profiled
    tags: &id012
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://www.realgeeks.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id013
      status: unknown
    slug: kvcore
    status: profiled
    tags: &id014
    - CRM
    - Company
    - Real Estate
    - Software-as-a-Service
    url: /providers/kvcore/
  layer: domain
  name: kvCORE (BoldTrail)
  provider: kvcore
  says: lists kvCORE (BoldTrail) as an integration
  source: https://www.realgeeks.com/integrations/
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
    agent_readiness: 35.0
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id015
      status: unknown
    slug: keller-williams
    status: profiled
    tags: &id016
    - Brokerage
    - Real Estate
    - Residential Real Estate
    - United States
    url: /providers/keller-williams/
  layer: domain
  name: KW Command
  provider: keller-williams
  says: lists KW Command as an integration
  source: https://www.realgeeks.com/integrations/
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id017
      status: none
    slug: mailchimp
    status: profiled
    tags: &id018
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.realgeeks.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.1
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id019
      source: https://docs.thanks.io/thanks-io-mcp-server
      status: verified
    slug: thanks-io
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Automation
    - Company
    - Direct Mail
    url: /providers/thanks-io/
  layer: common
  name: Thanks.io
  provider: thanks-io
  says: lists Thanks.io as an integration
  source: https://www.realgeeks.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/real-estate-home-search/real-geeks/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id001
  name: Apple Contacts
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: BoomTown
  slug: boomtown
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id005
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id006
  url: /providers/constant-contact/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id007
  name: Dubb
  slug: dubb
  status: profiled
  tags: *id008
  url: /providers/dubb/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id009
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id010
  url: /providers/google-people/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id011
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id012
  url: /providers/google-sheets/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id013
  name: kvCORE (BoldTrail)
  slug: kvcore
  status: profiled
  tags: *id014
  url: /providers/kvcore/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id015
  name: KW Command
  slug: keller-williams
  status: profiled
  tags: *id016
  url: /providers/keller-williams/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id017
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id018
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 49.1
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id019
  name: Thanks.io
  slug: thanks-io
  status: profiled
  tags: *id020
  url: /providers/thanks-io/
siblings:
- name: Flathunter
  rows: 16
  url: /applications/real-estate-home-search/flathunter/
- name: HomeHarvest
  rows: 1
  url: /applications/real-estate-home-search/homeharvest/
- name: Realtor.com
  rows: 13
  url: /applications/real-estate-home-search/realtor-com/
- name: Redfin
  rows: 13
  url: /applications/real-estate-home-search/redfin/
- name: Rightmove
  rows: 6
  url: /applications/real-estate-home-search/rightmove/
- name: Zillow
  rows: 14
  url: /applications/real-estate-home-search/zillow/
sitemap: true
title: 'Real Geeks: Real Estate & Home Search reference app'
---
