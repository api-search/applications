---
app: EZLynx
app_slug: ezlynx
app_url: https://www.ezlynx.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: domain
  name: Contract Execution Management
  providers:
  - AssureSign
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Intuit QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-958
  key: AE-958
  layer: domain
  name: Insurance Comparative Rating & Quote Aggregation
  providers:
  - EverQuote
  - QuinStreet
  url: /capabilities/insurance-comparative-rating-quote-aggregation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-959
  key: AE-959
  layer: domain
  name: Insurance Data Prefill & Prior-Coverage Verification
  providers:
  - Canopy Connect
  - Fenris
  - LexisNexis Risk Solutions
  url: /capabilities/underwriting-risk-intake/
  via_parent: Underwriting Risk Intake
- attribution: Turbo EA
  id: BC-2150.20
  key: premium-collection-management
  layer: domain
  name: Premium Collection Management
  providers:
  - Applied Pay (Applied Systems)
  url: /capabilities/premium-collection-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.60
  key: property-data
  layer: domain
  name: Property Data
  providers:
  - CoreLogic
  url: /capabilities/property-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Calendly
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-919
  key: AE-919
  layer: common
  name: B2B EDI & Trading-Partner Networks
  providers:
  - IVANS
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - Vonage
  url: /capabilities/voice-telephony/
  via_parent: null
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
  id: insurance-policy-claims
  name: Insurance Policy & Claims
  url: /applications/insurance-policy-claims/
counts:
  declared: 13
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.ezlynx.com/partners/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2150.20
    key: premium-collection-management
    name: Premium Collection Management
    url: /capabilities/premium-collection-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.3
    band: minimal
    in_catalog: true
    kin_score: 10.7
    mcp: &id001
      status: unknown
    slug: applied-systems
    status: profiled
    tags: &id002
    - Agency Management
    - Applied Epic
    - Insurance
    - Insurtech
    url: /providers/applied-systems/
  layer: domain
  name: Applied Pay (Applied Systems)
  provider: applied-systems
  says: lists Applied Pay (Applied Systems) as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: assuresign
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: AssureSign
  provider: assuresign
  says: lists AssureSign as an integration
  source: https://www.ezlynx.com/partners/
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
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id005
      source: https://developer.calendly.com/calendly-mcp-server
      status: documented
    slug: calendly
    status: profiled
    tags: &id006
    - Appointments
    - Automation
    - Booking
    - Calendar
    url: /providers/calendly/
  layer: domain
  name: Calendly
  provider: calendly
  says: lists Calendly as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-959
    key: AE-959
    name: Insurance Data Prefill & Prior-Coverage Verification
    url: /capabilities/underwriting-risk-intake/
    via_parent: Underwriting Risk Intake
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: canopy-connect
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Canopy Connect
  provider: canopy-connect
  says: lists Canopy Connect as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.60
    key: property-data
    name: Property Data
    url: /capabilities/property-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id009
      source: https://www.cotality.com/platforms/mcp-server
      status: verified
    slug: corelogic
    status: profiled
    tags: &id010
    - Climate Risk
    - CoreLogic
    - Cotality
    - Direct Web API
    url: /providers/corelogic/
  layer: domain
  name: CoreLogic
  provider: corelogic
  says: lists CoreLogic as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-958
    key: AE-958
    name: Insurance Comparative Rating & Quote Aggregation
    url: /capabilities/insurance-comparative-rating-quote-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id011
      status: unchecked
    slug: everquote
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Data
    - Insurance
    - Marketplace
    url: /providers/everquote/
  layer: domain
  name: EverQuote
  provider: everquote
  says: lists EverQuote as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-959
    key: AE-959
    name: Insurance Data Prefill & Prior-Coverage Verification
    url: /capabilities/underwriting-risk-intake/
    via_parent: Underwriting Risk Intake
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: fenris
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Fenris
  provider: fenris
  says: lists Fenris as an integration
  source: https://www.ezlynx.com/partners/
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
  name: Intuit QuickBooks
  provider: quickbooks
  says: lists Intuit QuickBooks as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-919
    key: AE-919
    name: B2B EDI & Trading-Partner Networks
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id017
      status: unknown
    slug: ivans
    status: profiled
    tags: &id018
    - Company
    - Data Exchange
    - Insurance
    - Insurance Distribution
    url: /providers/ivans/
  layer: common
  name: IVANS
  provider: ivans
  says: lists IVANS as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-959
    key: AE-959
    name: Insurance Data Prefill & Prior-Coverage Verification
    url: /capabilities/underwriting-risk-intake/
    via_parent: Underwriting Risk Intake
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id019
      status: unknown
    slug: lexisnexis-risk-solutions
    status: profiled
    tags: &id020
    - Insurance
    - Property and Casualty
    - Risk Data
    - United States
    url: /providers/lexisnexis-risk-solutions/
  layer: domain
  name: LexisNexis Risk Solutions
  provider: lexisnexis-risk-solutions
  says: lists LexisNexis Risk Solutions as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-958
    key: AE-958
    name: Insurance Comparative Rating & Quote Aggregation
    url: /capabilities/insurance-comparative-rating-quote-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id021
      status: unchecked
    slug: quinstreet
    status: profiled
    tags: &id022
    - Advertising
    - Company
    - Financial Services
    - Marketing
    url: /providers/quinstreet/
  layer: domain
  name: QuinStreet
  provider: quinstreet
  says: lists QuinStreet as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id023
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id024
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
  layer: common
  name: Vonage
  provider: vonage
  says: lists Vonage as an integration
  source: https://www.ezlynx.com/partners/
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
    mcp: &id025
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id026
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.ezlynx.com/partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/insurance-policy-claims/ezlynx/
providers:
- agent_band: human-only
  agent_readiness: 1.3
  band: minimal
  in_catalog: true
  kin_score: 10.7
  mcp: *id001
  name: Applied Pay (Applied Systems)
  slug: applied-systems
  status: profiled
  tags: *id002
  url: /providers/applied-systems/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: AssureSign
  slug: assuresign
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id005
  name: Calendly
  slug: calendly
  status: profiled
  tags: *id006
  url: /providers/calendly/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Canopy Connect
  slug: canopy-connect
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-ready
  agent_readiness: 28.6
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id009
  name: CoreLogic
  slug: corelogic
  status: profiled
  tags: *id010
  url: /providers/corelogic/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id011
  name: EverQuote
  slug: everquote
  status: profiled
  tags: *id012
  url: /providers/everquote/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Fenris
  slug: fenris
  status: queued for profiling
  tags: *id014
  url: null
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
  agent_readiness: 35.7
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id017
  name: IVANS
  slug: ivans
  status: profiled
  tags: *id018
  url: /providers/ivans/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id019
  name: LexisNexis Risk Solutions
  slug: lexisnexis-risk-solutions
  status: profiled
  tags: *id020
  url: /providers/lexisnexis-risk-solutions/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id021
  name: QuinStreet
  slug: quinstreet
  status: profiled
  tags: *id022
  url: /providers/quinstreet/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id023
  name: Vonage
  slug: vonage
  status: profiled
  tags: *id024
  url: /providers/vonage/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id025
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id026
  url: /providers/zapier/
siblings:
- name: Duck Creek
  rows: 11
  url: /applications/insurance-policy-claims/duck-creek/
- name: HawkSoft
  rows: 12
  url: /applications/insurance-policy-claims/hawksoft/
- name: Lemonade
  rows: 0
  url: /applications/insurance-policy-claims/lemonade/
- name: openIMIS
  rows: 6
  url: /applications/insurance-policy-claims/openimis/
- name: Socotra
  rows: 12
  url: /applications/insurance-policy-claims/socotra/
sitemap: true
title: 'EZLynx: Insurance Policy & Claims reference app'
---
