---
app: Neon CRM
app_slug: neon-crm
app_url: https://neonone.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.90
  key: AE-150.90
  layer: domain
  name: Advocacy & Legislator Outreach
  providers:
  - Ujoin Advocacy
  url: /capabilities/advocacy-legislator-outreach/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.30
  key: AE-230.30.30
  layer: domain
  name: Employer Matching-Gift Data
  providers:
  - Double the Donation
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - Eventbrite
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.30
  key: fundraising-campaign-management
  layer: domain
  name: Fundraising Campaign Management
  providers:
  - ClickBid
  - GivBee
  - Grassroots Unwired
  - Nuclavis
  url: /capabilities/fundraising-campaign-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.40.10
  key: BC-4800.40.10
  layer: domain
  name: Gift Receipt & Processing
  providers:
  - Chariot
  url: /capabilities/gift-pledge-administration/
  via_parent: Gift & Pledge Administration
- attribution: API Evangelist extension
  id: AE-140.40.20
  key: AE-140.40.20
  layer: domain
  name: Memberships
  providers:
  - Cuseum
  url: /capabilities/d2c-subscriptions/
  via_parent: D2C Subscriptions
- attribution: Turbo EA
  id: BC-4800.20.10
  key: BC-4800.20.10
  layer: domain
  name: Prospect Research & Identification
  providers:
  - Windfall Data
  url: /capabilities/donor-relationship-management/
  via_parent: Donor Relationship Management
- attribution: API Evangelist extension
  id: AE-924
  key: AE-924
  layer: domain
  name: Volunteer Management
  providers:
  - VolunteerLocal
  url: /capabilities/volunteer-management/
  via_parent: null
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
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Cougar Mountain Software
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: common
  name: Indirect Tax Management
  providers:
  - TaxJar
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50.10
  key: AE-170.50.10
  layer: common
  name: Online Communities
  providers:
  - Higher Logic
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: nonprofit-crm-fundraising
  name: Nonprofit CRM & Fundraising
  url: /applications/nonprofit-crm-fundraising/
counts:
  declared: 18
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.neonone.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4800.40.10
    key: BC-4800.40.10
    name: Gift Receipt & Processing
    url: /capabilities/gift-pledge-administration/
    via_parent: Gift & Pledge Administration
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.6
    band: strong
    in_catalog: true
    kin_score: 59.5
    mcp: &id001
      status: none
    slug: chariot
    status: profiled
    tags: &id002
    - Charitable Giving
    - Donor-Advised Funds
    - Non-Profit
    - Payments
    url: /providers/chariot/
  layer: domain
  name: Chariot
  provider: chariot
  says: lists Chariot as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.1
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id003
      status: none
    slug: clickbid
    status: profiled
    tags: &id004
    - Company
    - Gaming
    - Mobile
    - Payments
    url: /providers/clickbid/
  layer: domain
  name: ClickBid
  provider: clickbid
  says: lists ClickBid as an integration
  source: https://www.neonone.com/integrations/
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
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
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
  source: https://www.neonone.com/integrations/
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id007
      status: unknown
    slug: cougar-mountain-software
    status: profiled
    tags: &id008
    - Accounting
    - Non-Profit
    - Small Business
    - Software
    url: /providers/cougar-mountain-software/
  layer: common
  name: Cougar Mountain Software
  provider: cougar-mountain-software
  says: lists Cougar Mountain Software as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.40.20
    key: AE-140.40.20
    name: Memberships
    url: /capabilities/d2c-subscriptions/
    via_parent: D2C Subscriptions
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id009
      status: none
    slug: cuseum
    status: profiled
    tags: &id010
    - Company
    - Cultural Institutions
    - Museums
    - Non-Profit
    url: /providers/cuseum/
  layer: domain
  name: Cuseum
  provider: cuseum
  says: lists Cuseum as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.30
    key: AE-230.30.30
    name: Employer Matching-Gift Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id011
      status: unknown
    slug: double-the-donation
    status: profiled
    tags: &id012
    - Company
    - Fundraising
    - Matching Gifts
    - Non-Profit
    url: /providers/double-the-donation/
  layer: domain
  name: Double the Donation
  provider: double-the-donation
  says: lists Double the Donation as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id013
      status: none
    slug: eventbrite
    status: profiled
    tags: &id014
    - Event
    - Event Technology
    - Marketplace
    - Ticketing
    url: /providers/eventbrite/
  layer: domain
  name: Eventbrite
  provider: eventbrite
  says: lists Eventbrite as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id015
      status: unknown
    slug: givbee
    status: profiled
    tags: &id016
    - Company
    - Messaging
    - Non-Profit
    - SMS
    url: /providers/givbee/
  layer: domain
  name: GivBee
  provider: givbee
  says: lists GivBee as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id017
      status: none
    slug: grassroots-unwired
    status: profiled
    tags: &id018
    - Company
    - Fundraising
    - Non-Profit
    - Political Campaigns
    url: /providers/grassroots-unwired/
  layer: domain
  name: Grassroots Unwired
  provider: grassroots-unwired
  says: lists Grassroots Unwired as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 14.2
    mcp: &id019
      status: none
    slug: higher-logic
    status: profiled
    tags: &id020
    - Associations
    - Customer Retention
    - Member Engagement
    - Online Community Software
    url: /providers/higher-logic/
  layer: common
  name: Higher Logic
  provider: higher-logic
  says: lists Higher Logic as an integration
  source: https://www.neonone.com/integrations/
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
    mcp: &id021
      status: none
    slug: mailchimp
    status: profiled
    tags: &id022
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id023
      status: unknown
    slug: nuclavis
    status: profiled
    tags: &id024
    - Fundraising
    - Mobile
    - Non-Profit
    - P2P
    url: /providers/nuclavis/
  layer: domain
  name: Nuclavis
  provider: nuclavis
  says: lists Nuclavis as an integration
  source: https://www.neonone.com/integrations/
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
    mcp: &id025
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id026
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id027
      status: none
    slug: taxjar
    status: profiled
    tags: &id028
    - E-Commerce
    - Sales Tax
    - Tax Calculation
    - Tax Compliance
    url: /providers/taxjar/
  layer: common
  name: TaxJar
  provider: taxjar
  says: lists TaxJar as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.90
    key: AE-150.90
    name: Advocacy & Legislator Outreach
    url: /capabilities/advocacy-legislator-outreach/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.2
    mcp: &id029
      status: unknown
    slug: ujoin
    status: profiled
    tags: &id030
    - Advocacy
    - Company
    - Grassroots
    - Policy
    url: /providers/ujoin/
  layer: domain
  name: Ujoin Advocacy
  provider: ujoin
  says: lists Ujoin Advocacy as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-924
    key: AE-924
    name: Volunteer Management
    url: /capabilities/volunteer-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id031
      status: unknown
    slug: volunteerlocal
    status: profiled
    tags: &id032
    - Communications
    - Scheduling
    - Tracking
    - Volunteer Management
    url: /providers/volunteerlocal/
  layer: domain
  name: VolunteerLocal
  provider: volunteerlocal
  says: lists VolunteerLocal as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20.10
    key: BC-4800.20.10
    name: Prospect Research & Identification
    url: /capabilities/donor-relationship-management/
    via_parent: Donor Relationship Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id033
      status: none
    slug: windfall
    status: profiled
    tags: &id034
    - Company
    - Data Enrichment
    - Fintech
    - Wealth Data
    url: /providers/windfall/
  layer: domain
  name: Windfall Data
  provider: windfall
  says: lists Windfall Data as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id035
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id036
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.neonone.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/nonprofit-crm-fundraising/neon-crm/
providers:
- agent_band: agent-native
  agent_readiness: 61.6
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id001
  name: Chariot
  slug: chariot
  status: profiled
  tags: *id002
  url: /providers/chariot/
- agent_band: human-only
  agent_readiness: 1.1
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id003
  name: ClickBid
  slug: clickbid
  status: profiled
  tags: *id004
  url: /providers/clickbid/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
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
  kin_score: 12.8
  mcp: *id007
  name: Cougar Mountain Software
  slug: cougar-mountain-software
  status: profiled
  tags: *id008
  url: /providers/cougar-mountain-software/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id009
  name: Cuseum
  slug: cuseum
  status: profiled
  tags: *id010
  url: /providers/cuseum/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id011
  name: Double the Donation
  slug: double-the-donation
  status: profiled
  tags: *id012
  url: /providers/double-the-donation/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id013
  name: Eventbrite
  slug: eventbrite
  status: profiled
  tags: *id014
  url: /providers/eventbrite/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id015
  name: GivBee
  slug: givbee
  status: profiled
  tags: *id016
  url: /providers/givbee/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id017
  name: Grassroots Unwired
  slug: grassroots-unwired
  status: profiled
  tags: *id018
  url: /providers/grassroots-unwired/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 14.2
  mcp: *id019
  name: Higher Logic
  slug: higher-logic
  status: profiled
  tags: *id020
  url: /providers/higher-logic/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id021
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id022
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id023
  name: Nuclavis
  slug: nuclavis
  status: profiled
  tags: *id024
  url: /providers/nuclavis/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id025
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id026
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id027
  name: TaxJar
  slug: taxjar
  status: profiled
  tags: *id028
  url: /providers/taxjar/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.2
  mcp: *id029
  name: Ujoin Advocacy
  slug: ujoin
  status: profiled
  tags: *id030
  url: /providers/ujoin/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id031
  name: VolunteerLocal
  slug: volunteerlocal
  status: profiled
  tags: *id032
  url: /providers/volunteerlocal/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id033
  name: Windfall Data
  slug: windfall
  status: profiled
  tags: *id034
  url: /providers/windfall/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id035
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id036
  url: /providers/zapier/
siblings:
- name: Bloomerang
  rows: 29
  url: /applications/nonprofit-crm-fundraising/bloomerang/
- name: CiviCRM
  rows: 10
  url: /applications/nonprofit-crm-fundraising/civicrm/
- name: DonorPerfect
  rows: 27
  url: /applications/nonprofit-crm-fundraising/donorperfect/
- name: Givebutter
  rows: 53
  url: /applications/nonprofit-crm-fundraising/givebutter/
- name: Little Green Light
  rows: 28
  url: /applications/nonprofit-crm-fundraising/little-green-light/
sitemap: true
title: 'Neon CRM: Nonprofit CRM & Fundraising reference app'
---
