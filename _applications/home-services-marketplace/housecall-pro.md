---
app: Housecall Pro
app_slug: housecall-pro
app_url: https://www.housecallpro.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.50.10
  key: AE-200.50.10
  layer: domain
  name: Home-Services Lead Marketplaces
  providers:
  - Angi
  - Google Local Services
  - Thumbtack
  - Yelp
  url: /capabilities/home-services/
  via_parent: Home Services
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - CompanyCam
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.40
  key: AE-140.30.40
  layer: domain
  name: Point-of-Service Consumer Financing
  providers:
  - Fundbox
  - Wisetack
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Broadly
  - NiceJob
  - Podium
  url: /capabilities/reviews-social-proof/
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
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Intuit QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - Gusto
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - CallRail
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
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
  id: home-services-marketplace
  name: Home Services Marketplaces
  url: /applications/home-services-marketplace/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.housecallpro.com/features/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.10
    key: AE-200.50.10
    name: Home-Services Lead Marketplaces
    url: /capabilities/home-services/
    via_parent: Home Services
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id001
      status: none
    slug: angi
    status: profiled
    tags: &id002
    - Angie's List
    - Home Services
    - Leads
    - Marketplace
    url: /providers/angi/
  layer: domain
  name: Angi
  provider: angi
  says: lists Angi as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.2
    mcp: &id003
      status: none
    slug: broadly
    status: profiled
    tags: &id004
    - AI Workforce
    - CRM
    - Local SEO
    - Reputation Management
    url: /providers/broadly/
  layer: domain
  name: Broadly
  provider: broadly
  says: lists Broadly as an integration
  source: https://www.housecallpro.com/features/integrations/
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id005
      status: none
    slug: callrail
    status: profiled
    tags: &id006
    - Call Tracking
    - Conversation Intelligence
    - Lead Tracking
    - Marketing Attribution
    url: /providers/callrail/
  layer: common
  name: CallRail
  provider: callrail
  says: lists CallRail as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id007
      status: none
    slug: companycam
    status: profiled
    tags: &id008
    - Company
    - Construction
    - Field Service Management
    - Photos
    url: /providers/companycam/
  layer: domain
  name: CompanyCam
  provider: companycam
  says: lists CompanyCam as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.40
    key: AE-140.30.40
    name: Point-of-Service Consumer Financing
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id009
      status: none
    slug: fundbox
    status: profiled
    tags: &id010
    - B2B Credit
    - Embedded Finance
    - Fintech
    - Net Terms
    url: /providers/fundbox/
  layer: domain
  name: Fundbox
  provider: fundbox
  says: lists Fundbox as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.10
    key: AE-200.50.10
    name: Home-Services Lead Marketplaces
    url: /capabilities/home-services/
    via_parent: Home Services
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: google-local-services
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: Google Local Services
  provider: google-local-services
  says: lists Google Local Services as an integration
  source: https://www.housecallpro.com/features/integrations/
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
  layer: common
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://www.housecallpro.com/features/integrations/
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
  layer: common
  name: Intuit QuickBooks
  provider: quickbooks
  says: lists Intuit QuickBooks as an integration
  source: https://www.housecallpro.com/features/integrations/
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
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id019
      status: none
    slug: nicejob
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Reputation Marketing
    - Service Business
    - Software-as-a-Service
    url: /providers/nicejob/
  layer: domain
  name: NiceJob
  provider: nicejob
  says: lists NiceJob as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id021
      status: none
    slug: podium
    status: profiled
    tags: &id022
    - Customer Communication
    - Messaging
    - Payments
    - Reviews
    url: /providers/podium/
  layer: domain
  name: Podium
  provider: podium
  says: lists Podium as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.10
    key: AE-200.50.10
    name: Home-Services Lead Marketplaces
    url: /capabilities/home-services/
    via_parent: Home Services
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id023
      status: none
    slug: thumbtack
    status: profiled
    tags: &id024
    - Home Services
    - Leads
    - Local Services
    - Marketplace
    url: /providers/thumbtack/
  layer: domain
  name: Thumbtack
  provider: thumbtack
  says: lists Thumbtack as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.40
    key: AE-140.30.40
    name: Point-of-Service Consumer Financing
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id025
      status: none
    slug: wisetack
    status: profiled
    tags: &id026
    - Company
    - Consumer Financing
    - Fintech
    - Lending
    url: /providers/wisetack/
  layer: domain
  name: Wisetack
  provider: wisetack
  says: lists Wisetack as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.10
    key: AE-200.50.10
    name: Home-Services Lead Marketplaces
    url: /capabilities/home-services/
    via_parent: Home Services
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 46.7
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id027
      source: https://github.com/Yelp/yelp-mcp
      status: verified
    slug: yelp
    status: profiled
    tags: &id028
    - Business Data
    - Local Search
    - Restaurant
    - Reviews
    url: /providers/yelp/
  layer: domain
  name: Yelp
  provider: yelp
  says: lists Yelp as an integration
  source: https://www.housecallpro.com/features/integrations/
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
    mcp: &id029
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id030
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/home-services-marketplace/housecall-pro/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id001
  name: Angi
  slug: angi
  status: profiled
  tags: *id002
  url: /providers/angi/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.2
  mcp: *id003
  name: Broadly
  slug: broadly
  status: profiled
  tags: *id004
  url: /providers/broadly/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id005
  name: CallRail
  slug: callrail
  status: profiled
  tags: *id006
  url: /providers/callrail/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id007
  name: CompanyCam
  slug: companycam
  status: profiled
  tags: *id008
  url: /providers/companycam/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id009
  name: Fundbox
  slug: fundbox
  status: profiled
  tags: *id010
  url: /providers/fundbox/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Google Local Services
  slug: google-local-services
  status: queued for profiling
  tags: *id012
  url: null
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
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id015
  name: Intuit QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id016
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id017
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id018
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id019
  name: NiceJob
  slug: nicejob
  status: profiled
  tags: *id020
  url: /providers/nicejob/
- agent_band: agent-native
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id021
  name: Podium
  slug: podium
  status: profiled
  tags: *id022
  url: /providers/podium/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id023
  name: Thumbtack
  slug: thumbtack
  status: profiled
  tags: *id024
  url: /providers/thumbtack/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id025
  name: Wisetack
  slug: wisetack
  status: profiled
  tags: *id026
  url: /providers/wisetack/
- agent_band: agent-native
  agent_readiness: 46.7
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id027
  name: Yelp
  slug: yelp
  status: profiled
  tags: *id028
  url: /providers/yelp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id029
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id030
  url: /providers/zapier/
siblings:
- name: Angi
  rows: 0
  url: /applications/home-services-marketplace/angi/
- name: Cocorico
  rows: 7
  url: /applications/home-services-marketplace/cocorico/
- name: Sharetribe Go
  rows: 13
  url: /applications/home-services-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 5
  url: /applications/home-services-marketplace/sharetribe-web-template/
- name: Taskrabbit
  rows: 4
  url: /applications/home-services-marketplace/taskrabbit/
- name: Thumbtack
  rows: 6
  url: /applications/home-services-marketplace/thumbtack/
sitemap: true
title: 'Housecall Pro: Home Services Marketplaces reference app'
---
