---
app: Workiz
app_slug: workiz
app_url: https://www.workiz.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2420.10
  key: dispatch-management
  layer: domain
  name: Dispatch Management
  providers:
  - Dispatch.me
  url: /capabilities/dispatch-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Linxup
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.50.10
  key: AE-200.50.10
  layer: domain
  name: Home-Services Lead Marketplaces
  providers:
  - Angi Leads
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
  - Sunbit
  - Wisetack
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Reserve with Google
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - SearchKings
  url: /capabilities/digital-marketing-management/
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
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - NiceJob
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: common
  name: Virtual Receptionists & Answering Services
  providers:
  - AnswerConnect
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
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 16
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.workiz.com/integrations/
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
    kin_score: 11.5
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
  name: Angi Leads
  provider: angi
  says: lists Angi Leads as an integration
  source: https://www.workiz.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.9
    band: minimal
    in_catalog: true
    kin_score: 9.2
    mcp: &id003
      status: unknown
    slug: answerconnect
    status: profiled
    tags: &id004
    - Appointment Scheduling
    - Call Answering
    - Company
    - Live Chat
    url: /providers/answerconnect/
  layer: common
  name: AnswerConnect
  provider: answerconnect
  says: lists AnswerConnect as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id005
      status: none
    slug: companycam
    status: profiled
    tags: &id006
    - Company
    - Construction
    - Field Service Management
    - Photos
    url: /providers/companycam/
  layer: domain
  name: CompanyCam
  provider: companycam
  says: lists CompanyCam as an integration
  source: https://www.workiz.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.10
    key: dispatch-management
    name: Dispatch Management
    url: /capabilities/dispatch-management/
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
    slug: dispatch-me
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Dispatch.me
  provider: dispatch-me
  says: lists Dispatch.me as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id010
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.workiz.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id011
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id012
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: Intuit QuickBooks
  provider: quickbooks
  says: lists Intuit QuickBooks as an integration
  source: https://www.workiz.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.0
    mcp: &id013
      status: none
    slug: linxup
    status: profiled
    tags: &id014
    - Asset Management
    - Dash Cams
    - Fleet Tracking
    - GPS
    url: /providers/linxup/
  layer: domain
  name: Linxup
  provider: linxup
  says: lists Linxup as an integration
  source: https://www.workiz.com/integrations/
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
  source: https://www.workiz.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id017
      status: none
    slug: nicejob
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Reputation Marketing
    - Service Business
    - Software-as-a-Service
    url: /providers/nicejob/
  layer: common
  name: NiceJob
  provider: nicejob
  says: lists NiceJob as an integration
  source: https://www.workiz.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id019
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id020
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Reserve with Google
  provider: google
  says: lists Reserve with Google as an integration
  source: https://www.workiz.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.8
    mcp: &id021
      status: none
    slug: searchkings
    status: profiled
    tags: &id022
    - Advertising
    - Artificial Intelligence
    - Company
    - Marketing
    url: /providers/searchkings/
  layer: common
  name: SearchKings
  provider: searchkings
  says: lists SearchKings as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id023
      status: none
    slug: sunbit
    status: profiled
    tags: &id024
    - Buy Now Pay Later
    - Consumer Lending
    - Payments
    - Point of Sale Financing
    url: /providers/sunbit/
  layer: domain
  name: Sunbit
  provider: sunbit
  says: lists Sunbit as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id025
      status: none
    slug: thumbtack
    status: profiled
    tags: &id026
    - Home Services
    - Leads
    - Local Services
    - Marketplace
    url: /providers/thumbtack/
  layer: domain
  name: Thumbtack
  provider: thumbtack
  says: lists Thumbtack as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id027
      status: none
    slug: wisetack
    status: profiled
    tags: &id028
    - Company
    - Consumer Financing
    - Fintech
    - Lending
    url: /providers/wisetack/
  layer: domain
  name: Wisetack
  provider: wisetack
  says: lists Wisetack as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 53.4
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id029
      source: https://github.com/Yelp/yelp-mcp
      status: verified
    slug: yelp
    status: profiled
    tags: &id030
    - Business Data
    - Local Search
    - Restaurant
    - Reviews
    url: /providers/yelp/
  layer: domain
  name: Yelp
  provider: yelp
  says: lists Yelp as an integration
  source: https://www.workiz.com/integrations/
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id031
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id032
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.workiz.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/workiz/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id001
  name: Angi Leads
  slug: angi
  status: profiled
  tags: *id002
  url: /providers/angi/
- agent_band: human-only
  agent_readiness: 3.9
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id003
  name: AnswerConnect
  slug: answerconnect
  status: profiled
  tags: *id004
  url: /providers/answerconnect/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id005
  name: CompanyCam
  slug: companycam
  status: profiled
  tags: *id006
  url: /providers/companycam/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Dispatch.me
  slug: dispatch-me
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id009
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id010
  url: /providers/google-calendar/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id011
  name: Intuit QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id012
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.0
  mcp: *id013
  name: Linxup
  slug: linxup
  status: profiled
  tags: *id014
  url: /providers/linxup/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id015
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id016
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id017
  name: NiceJob
  slug: nicejob
  status: profiled
  tags: *id018
  url: /providers/nicejob/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id019
  name: Reserve with Google
  slug: google
  status: profiled
  tags: *id020
  url: /providers/google/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id021
  name: SearchKings
  slug: searchkings
  status: profiled
  tags: *id022
  url: /providers/searchkings/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id023
  name: Sunbit
  slug: sunbit
  status: profiled
  tags: *id024
  url: /providers/sunbit/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id025
  name: Thumbtack
  slug: thumbtack
  status: profiled
  tags: *id026
  url: /providers/thumbtack/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id027
  name: Wisetack
  slug: wisetack
  status: profiled
  tags: *id028
  url: /providers/wisetack/
- agent_band: agent-native
  agent_readiness: 53.4
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id029
  name: Yelp
  slug: yelp
  status: profiled
  tags: *id030
  url: /providers/yelp/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id031
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id032
  url: /providers/zapier/
siblings:
- name: Housecall Pro
  rows: 26
  url: /applications/field-service/housecall-pro/
- name: Jobber
  rows: 34
  url: /applications/field-service/jobber/
- name: OCA Field Service (Odoo)
  rows: 1
  url: /applications/field-service/oca-field-service-odoo/
- name: ServiceM8
  rows: 8
  url: /applications/field-service/servicem8/
- name: ServiceTitan
  rows: 3
  url: /applications/field-service/servicetitan/
- name: Tradify
  rows: 4
  url: /applications/field-service/tradify/
sitemap: true
title: 'Workiz: Field Service & Dispatch reference app'
---
