---
app: AppFolio
app_slug: appfolio
app_url: https://www.appfolio.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.20
  key: accounts-payable-management
  layer: domain
  name: Accounts Payable Management
  providers:
  - AvidXchange
  url: /capabilities/accounts-payable-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2370.30
  key: channel-syndication-management
  layer: domain
  name: Channel Syndication Management
  providers:
  - Zillow
  url: /capabilities/channel-syndication-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1330.10
  key: deposit-account-management
  layer: domain
  name: Deposit Account Management
  providers:
  - Column N.A.
  url: /capabilities/deposit-account-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4940.20
  key: property-maintenance-work-order-management
  layer: domain
  name: Property Maintenance & Work Order Management
  providers:
  - Lula (maintenance)
  - Property Meld
  url: /capabilities/property-maintenance-work-order-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - SimpleVoIP
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
category:
  id: property-management
  name: Property & Rental Management
  url: /applications/property-management/
counts:
  declared: 6
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.appfolio.com/stack
- route: integrations page
  url: https://www.appfolio.com/stack/partners
integrations:
- capability:
    attribution: Turbo EA
    id: BC-200.20
    key: accounts-payable-management
    name: Accounts Payable Management
    url: /capabilities/accounts-payable-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.3
    mcp: &id001
      status: none
    slug: avidxchange
    status: profiled
    tags: &id002
    - Accounts Payable
    - Company
    - Fintech
    - Payments
    url: /providers/avidxchange/
  layer: domain
  name: AvidXchange
  provider: avidxchange
  says: lists AvidXchange as an integration
  source: https://www.appfolio.com/stack
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1330.10
    key: deposit-account-management
    name: Deposit Account Management
    url: /capabilities/deposit-account-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.5
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id003
      status: none
    slug: column
    status: profiled
    tags: &id004
    - ACH
    - Banking
    - Banking as a Service
    - Fintech
    url: /providers/column/
  layer: domain
  name: Column N.A.
  provider: column
  says: lists Column N.A. as an integration
  source: https://www.appfolio.com/stack
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4940.20
    key: property-maintenance-work-order-management
    name: Property Maintenance & Work Order Management
    url: /capabilities/property-maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 23.6
    mcp: &id005
      status: unknown
    slug: lula-life
    status: profiled
    tags: &id006
    - Company
    - Maintenance
    - Property Management
    - Real Estate
    url: /providers/lula-life/
  layer: domain
  name: Lula (maintenance)
  provider: lula-life
  says: lists Lula (maintenance) as an integration
  source: https://www.appfolio.com/stack
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4940.20
    key: property-maintenance-work-order-management
    name: Property Maintenance & Work Order Management
    url: /capabilities/property-maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: property-meld
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Property Meld
  provider: property-meld
  says: lists Property Meld as an integration
  source: https://www.appfolio.com/stack/partners
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: strong
    in_catalog: true
    kin_score: 54.3
    mcp: &id009
      status: unknown
    slug: simplevoip
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Communications
    - UCaaS
    - VoIP
    url: /providers/simplevoip/
  layer: common
  name: SimpleVoIP
  provider: simplevoip
  says: lists SimpleVoIP as an integration
  source: https://www.appfolio.com/stack
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2370.30
    key: channel-syndication-management
    name: Channel Syndication Management
    url: /capabilities/channel-syndication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id011
      status: none
    slug: zillow-group
    status: profiled
    tags: &id012
    - MLS
    - Mortgage
    - Property Data
    - Real Estate
    url: /providers/zillow-group/
  layer: domain
  name: Zillow
  provider: zillow-group
  says: lists Zillow as an integration
  source: https://www.appfolio.com/stack
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/property-management/appfolio/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.3
  mcp: *id001
  name: AvidXchange
  slug: avidxchange
  status: profiled
  tags: *id002
  url: /providers/avidxchange/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id003
  name: Column N.A.
  slug: column
  status: profiled
  tags: *id004
  url: /providers/column/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 23.6
  mcp: *id005
  name: Lula (maintenance)
  slug: lula-life
  status: profiled
  tags: *id006
  url: /providers/lula-life/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Property Meld
  slug: property-meld
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-ready
  agent_readiness: 31.4
  band: strong
  in_catalog: true
  kin_score: 54.3
  mcp: *id009
  name: SimpleVoIP
  slug: simplevoip
  status: profiled
  tags: *id010
  url: /providers/simplevoip/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id011
  name: Zillow
  slug: zillow-group
  status: profiled
  tags: *id012
  url: /providers/zillow-group/
siblings:
- name: Buildium
  rows: 15
  url: /applications/property-management/buildium/
- name: DoorLoop
  rows: 15
  url: /applications/property-management/doorloop/
- name: Guesty
  rows: 12
  url: /applications/property-management/guesty/
- name: Hostaway
  rows: 17
  url: /applications/property-management/hostaway/
- name: Open Condo
  rows: 18
  url: /applications/property-management/open-condo/
sitemap: true
title: 'AppFolio: Property & Rental Management reference app'
---
