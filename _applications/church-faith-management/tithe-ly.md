---
app: Tithe.ly
app_slug: tithe-ly
app_url: https://get.tithe.ly/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - MinistrySafe
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: API Evangelist extension
  id: AE-190.30.20
  key: AE-190.30.20
  layer: domain
  name: Crypto Exchanges & Wallets
  providers:
  - Engiven
  url: /capabilities/retail-investing/
  via_parent: Retail Investing
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-943
  key: AE-943
  layer: common
  name: Church Management System Sync
  providers:
  - Church Community Builder (Pushpay)
  - Elvanto
  - FellowshipOne
  - MinistryPlatform
  - Planning Center
  - Rock RMS
  - Shelby Systems
  url: /capabilities/church-management-system-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
category:
  id: church-faith-management
  name: Church & Faith Community Management
  url: /applications/church-faith-management/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://get.tithe.ly/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.0
    band: emerging
    in_catalog: true
    kin_score: 25.8
    mcp: &id001
      status: unchecked
    slug: pushpay
    status: profiled
    tags: &id002
    - Church Giving
    - Church Management Software
    - Digital Giving
    - Mobile App
    url: /providers/pushpay/
  layer: common
  name: Church Community Builder (Pushpay)
  provider: pushpay
  says: lists Church Community Builder (Pushpay) as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id003
      status: unchecked
    slug: elvanto
    status: profiled
    tags: &id004
    - Church Management
    - Cloud
    - Software
    - Software-as-a-Service
    url: /providers/elvanto/
  layer: common
  name: Elvanto
  provider: elvanto
  says: lists Elvanto as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id005
      status: unchecked
    slug: engiven
    status: profiled
    tags: &id006
    - CryptoDonations
    - Enterprise Software
    - NonprofitTech
    - Stock Donations
    url: /providers/engiven/
  layer: domain
  name: Engiven
  provider: engiven
  says: lists Engiven as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.6
    mcp: &id007
      status: unchecked
    slug: fellowshipone
    status: profiled
    tags: &id008
    - Church
    - Cloud
    - Management
    - Software
    url: /providers/fellowshipone/
  layer: common
  name: FellowshipOne
  provider: fellowshipone
  says: lists FellowshipOne as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id009
      status: unchecked
    slug: ministryplatform
    status: profiled
    tags: &id010
    - Church
    - Company
    - Integration
    - ManagementSoftware
    url: /providers/ministryplatform/
  layer: common
  name: MinistryPlatform
  provider: ministryplatform
  says: lists MinistryPlatform as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id011
      status: unchecked
    slug: ministrysafe
    status: profiled
    tags: &id012
    - Child Safety
    - Education
    - Non-Profit
    - Training
    url: /providers/ministrysafe/
  layer: domain
  name: MinistrySafe
  provider: ministrysafe
  says: lists MinistrySafe as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id013
      source: https://mcp.planningcenteronline.com/mcp
      status: verified
    slug: planning-center
    status: profiled
    tags: &id014
    - ChMS
    - Church Management
    - Faith
    - Giving
    url: /providers/planning-center/
  layer: common
  name: Planning Center
  provider: planning-center
  says: lists Planning Center as an integration
  source: https://get.tithe.ly/integrations
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
    mcp: &id015
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id016
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id017
      status: unchecked
    slug: rock-rms
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Church Management
    - Company
    - Open Source
    url: /providers/rock-rms/
  layer: common
  name: Rock RMS
  provider: rock-rms
  says: lists Rock RMS as an integration
  source: https://get.tithe.ly/integrations
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
    mcp: &id019
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id020
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.5
    mcp: &id021
      status: unchecked
    slug: shelby-systems
    status: profiled
    tags: &id022
    - Church Accounting
    - Church Management
    - Ministry Software
    - Online Giving
    url: /providers/shelby-systems/
  layer: common
  name: Shelby Systems
  provider: shelby-systems
  says: lists Shelby Systems as an integration
  source: https://get.tithe.ly/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/church-faith-management/tithe-ly/
providers:
- agent_band: agent-aware
  agent_readiness: 21.0
  band: emerging
  in_catalog: true
  kin_score: 25.8
  mcp: *id001
  name: Church Community Builder (Pushpay)
  slug: pushpay
  status: profiled
  tags: *id002
  url: /providers/pushpay/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id003
  name: Elvanto
  slug: elvanto
  status: profiled
  tags: *id004
  url: /providers/elvanto/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id005
  name: Engiven
  slug: engiven
  status: profiled
  tags: *id006
  url: /providers/engiven/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.6
  mcp: *id007
  name: FellowshipOne
  slug: fellowshipone
  status: profiled
  tags: *id008
  url: /providers/fellowshipone/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id009
  name: MinistryPlatform
  slug: ministryplatform
  status: profiled
  tags: *id010
  url: /providers/ministryplatform/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id011
  name: MinistrySafe
  slug: ministrysafe
  status: profiled
  tags: *id012
  url: /providers/ministrysafe/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id013
  name: Planning Center
  slug: planning-center
  status: profiled
  tags: *id014
  url: /providers/planning-center/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id015
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id016
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id017
  name: Rock RMS
  slug: rock-rms
  status: profiled
  tags: *id018
  url: /providers/rock-rms/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id019
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id020
  url: /providers/salesforce/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.5
  mcp: *id021
  name: Shelby Systems
  slug: shelby-systems
  status: profiled
  tags: *id022
  url: /providers/shelby-systems/
siblings:
- name: ChurchCRM
  rows: 7
  url: /applications/church-faith-management/churchcrm/
- name: OpenLP
  rows: 6
  url: /applications/church-faith-management/openlp/
- name: Planning Center
  rows: 20
  url: /applications/church-faith-management/planning-center/
- name: Pushpay
  rows: 20
  url: /applications/church-faith-management/pushpay/
- name: Rock RMS
  rows: 21
  url: /applications/church-faith-management/rock-rms/
sitemap: true
title: 'Tithe.ly: Church & Faith Community Management reference app'
---
