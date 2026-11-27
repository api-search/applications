---
app: Pushpay
app_slug: pushpay
app_url: https://pushpay.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Checkr
  - MinistrySafe
  - Protect My Ministry
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
  - Aplos
  - QuickBooks
  - Sage Intacct
  - Shelby Systems
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - Gusto
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3740.20
  key: ott-streaming-delivery
  layer: domain
  name: OTT & Streaming Delivery
  providers:
  - PRAY.COM
  - Resi
  url: /capabilities/ott-streaming-delivery/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60.10
  key: AE-150.60.10
  layer: common
  name: Async Video Messaging
  providers:
  - BombBomb
  url: /capabilities/video-calling/
  via_parent: Video Calling
- attribution: API Evangelist extension
  id: AE-943
  key: AE-943
  layer: common
  name: Church Management System Sync
  providers:
  - FellowshipOne
  - MinistryPlatform
  - Planning Center
  - Rock RMS
  url: /capabilities/church-management-system-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Subsplash
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Clearstream (church texting)
  - Text-Em-All
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: church-faith-management
  name: Church & Faith Community Management
  url: /applications/church-faith-management/
counts:
  declared: 20
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://pushpay.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id001
      status: none
    slug: aplos
    status: profiled
    tags: &id002
    - Accounting
    - Company
    - Non-Profit
    - Software
    url: /providers/aplos/
  layer: domain
  name: Aplos
  provider: aplos
  says: lists Aplos as an integration
  source: https://pushpay.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 33.7
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id003
      status: unchecked
    slug: bombbomb
    status: profiled
    tags: &id004
    - Company
    - Marketing
    - Sales
    - Video Messaging
    url: /providers/bombbomb/
  layer: common
  name: BombBomb
  provider: bombbomb
  says: lists BombBomb as an integration
  source: https://pushpay.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 52.8
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id005
      status: none
    slug: checkr
    status: profiled
    tags: &id006
    - Background Checks
    - Compliance
    - Employment Screening
    - Human Resources
    url: /providers/checkr/
  layer: domain
  name: Checkr
  provider: checkr
  says: lists Checkr as an integration
  source: https://pushpay.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id007
      status: unchecked
    slug: clearstream-io
    status: profiled
    tags: &id008
    - Church
    - Company
    - Messaging
    - SMS
    url: /providers/clearstream-io/
  layer: common
  name: Clearstream (church texting)
  provider: clearstream-io
  says: lists Clearstream (church texting) as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id009
      status: unchecked
    slug: engiven
    status: profiled
    tags: &id010
    - CryptoDonations
    - Enterprise Software
    - NonprofitTech
    - Stock Donations
    url: /providers/engiven/
  layer: domain
  name: Engiven
  provider: engiven
  says: lists Engiven as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id011
      status: unchecked
    slug: fellowshipone
    status: profiled
    tags: &id012
    - Church
    - Cloud
    - Management
    - Software
    url: /providers/fellowshipone/
  layer: common
  name: FellowshipOne
  provider: fellowshipone
  says: lists FellowshipOne as an integration
  source: https://pushpay.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id013
      status: none
    slug: gusto
    status: profiled
    tags: &id014
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: domain
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://pushpay.com/integrations/
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id015
      status: none
    slug: mailchimp
    status: profiled
    tags: &id016
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id017
      status: unchecked
    slug: ministryplatform
    status: profiled
    tags: &id018
    - Church
    - Company
    - Integration
    - ManagementSoftware
    url: /providers/ministryplatform/
  layer: common
  name: MinistryPlatform
  provider: ministryplatform
  says: lists MinistryPlatform as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id019
      status: unchecked
    slug: ministrysafe
    status: profiled
    tags: &id020
    - Child Safety
    - Education
    - Non-Profit
    - Training
    url: /providers/ministrysafe/
  layer: domain
  name: MinistrySafe
  provider: ministrysafe
  says: lists MinistrySafe as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id021
      source: https://mcp.planningcenteronline.com/mcp
      status: verified
    slug: planning-center
    status: profiled
    tags: &id022
    - ChMS
    - Church Management
    - Faith
    - Giving
    url: /providers/planning-center/
  layer: common
  name: Planning Center
  provider: planning-center
  says: lists Planning Center as an integration
  source: https://pushpay.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3740.20
    key: ott-streaming-delivery
    name: OTT & Streaming Delivery
    url: /capabilities/ott-streaming-delivery/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 15.6
    mcp: &id023
      status: unchecked
    slug: pray-com
    status: profiled
    tags: &id024
    - Bible
    - Company
    - Faith
    - Prayer
    url: /providers/pray-com/
  layer: domain
  name: PRAY.COM
  provider: pray-com
  says: lists PRAY.COM as an integration
  source: https://pushpay.com/integrations/
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
    kin_score: 8.0
    mcp: &id025
      status: unchecked
    slug: protect-my-ministry
    status: profiled
    tags: &id026
    - Background Checks
    - Child Safety Training
    - Church Screening
    - Volunteer Screening
    url: /providers/protect-my-ministry/
  layer: domain
  name: Protect My Ministry
  provider: protect-my-ministry
  says: lists Protect My Ministry as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id027
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id028
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://pushpay.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3740.20
    key: ott-streaming-delivery
    name: OTT & Streaming Delivery
    url: /capabilities/ott-streaming-delivery/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: resi
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: Resi
  provider: resi
  says: lists Resi as an integration
  source: https://pushpay.com/integrations/
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
    mcp: &id031
      status: unchecked
    slug: rock-rms
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Church Management
    - Company
    - Open Source
    url: /providers/rock-rms/
  layer: common
  name: Rock RMS
  provider: rock-rms
  says: lists Rock RMS as an integration
  source: https://pushpay.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id033
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id034
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://pushpay.com/integrations/
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
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.5
    mcp: &id035
      status: unchecked
    slug: shelby-systems
    status: profiled
    tags: &id036
    - Church Accounting
    - Church Management
    - Ministry Software
    - Online Giving
    url: /providers/shelby-systems/
  layer: domain
  name: Shelby Systems
  provider: shelby-systems
  says: lists Shelby Systems as an integration
  source: https://pushpay.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id037
      status: none
    slug: subsplash
    status: profiled
    tags: &id038
    - Church
    - Giving
    - Ministry
    - Non-Profit
    url: /providers/subsplash/
  layer: common
  name: Subsplash
  provider: subsplash
  says: lists Subsplash as an integration
  source: https://pushpay.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id039
      status: unchecked
    slug: text-em-all
    status: profiled
    tags: &id040
    - Communications
    - Employee-Owned
    - Marketing
    - SMS
    url: /providers/text-em-all/
  layer: common
  name: Text-Em-All
  provider: text-em-all
  says: lists Text-Em-All as an integration
  source: https://pushpay.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/church-faith-management/pushpay/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id001
  name: Aplos
  slug: aplos
  status: profiled
  tags: *id002
  url: /providers/aplos/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id003
  name: BombBomb
  slug: bombbomb
  status: profiled
  tags: *id004
  url: /providers/bombbomb/
- agent_band: agent-ready
  agent_readiness: 52.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id005
  name: Checkr
  slug: checkr
  status: profiled
  tags: *id006
  url: /providers/checkr/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id007
  name: Clearstream (church texting)
  slug: clearstream-io
  status: profiled
  tags: *id008
  url: /providers/clearstream-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id009
  name: Engiven
  slug: engiven
  status: profiled
  tags: *id010
  url: /providers/engiven/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.6
  mcp: *id011
  name: FellowshipOne
  slug: fellowshipone
  status: profiled
  tags: *id012
  url: /providers/fellowshipone/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id013
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id014
  url: /providers/gusto/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id015
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id016
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id017
  name: MinistryPlatform
  slug: ministryplatform
  status: profiled
  tags: *id018
  url: /providers/ministryplatform/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id019
  name: MinistrySafe
  slug: ministrysafe
  status: profiled
  tags: *id020
  url: /providers/ministrysafe/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id021
  name: Planning Center
  slug: planning-center
  status: profiled
  tags: *id022
  url: /providers/planning-center/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 15.6
  mcp: *id023
  name: PRAY.COM
  slug: pray-com
  status: profiled
  tags: *id024
  url: /providers/pray-com/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id025
  name: Protect My Ministry
  slug: protect-my-ministry
  status: profiled
  tags: *id026
  url: /providers/protect-my-ministry/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id027
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id028
  url: /providers/quickbooks/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: Resi
  slug: resi
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id031
  name: Rock RMS
  slug: rock-rms
  status: profiled
  tags: *id032
  url: /providers/rock-rms/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id033
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id034
  url: /providers/sage-intacct/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.5
  mcp: *id035
  name: Shelby Systems
  slug: shelby-systems
  status: profiled
  tags: *id036
  url: /providers/shelby-systems/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id037
  name: Subsplash
  slug: subsplash
  status: profiled
  tags: *id038
  url: /providers/subsplash/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id039
  name: Text-Em-All
  slug: text-em-all
  status: profiled
  tags: *id040
  url: /providers/text-em-all/
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
- name: Rock RMS
  rows: 21
  url: /applications/church-faith-management/rock-rms/
- name: Tithe.ly
  rows: 11
  url: /applications/church-faith-management/tithe-ly/
sitemap: true
title: 'Pushpay: Church & Faith Community Management reference app'
---
