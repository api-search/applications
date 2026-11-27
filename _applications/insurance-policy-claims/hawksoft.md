---
app: HawkSoft
app_slug: hawksoft
app_url: https://www.hawksoft.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: domain
  name: Contract Execution Management
  providers:
  - Formstack
  - RPost
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - AgencyZoom
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Agency Revolution
  url: /capabilities/digital-marketing-management/
  via_parent: null
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
  id: AE-958
  key: AE-958
  layer: domain
  name: Insurance Comparative Rating & Quote Aggregation
  providers:
  - Vertafore
  - Zywave
  url: /capabilities/insurance-comparative-rating-quote-aggregation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-959
  key: AE-959
  layer: domain
  name: Insurance Data Prefill & Prior-Coverage Verification
  providers:
  - Canopy Connect
  url: /capabilities/underwriting-risk-intake/
  via_parent: Underwriting Risk Intake
- attribution: Turbo EA
  id: BC-2110
  key: insurance-distribution-management
  layer: domain
  name: Insurance Distribution Management
  providers:
  - EZLynx
  url: /capabilities/insurance-distribution-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2150.20
  key: premium-collection-management
  layer: domain
  name: Premium Collection Management
  providers:
  - ePayPolicy
  url: /capabilities/premium-collection-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Podium
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - RingCentral
  url: /capabilities/voice-telephony/
  via_parent: null
category:
  id: insurance-policy-claims
  name: Insurance Policy & Claims
  url: /applications/insurance-policy-claims/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.hawksoft.com/partners/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id001
      status: unchecked
    slug: agency-revolution
    status: profiled
    tags: &id002
    - Automation
    - Company
    - Insurance
    - Marketing
    url: /providers/agency-revolution/
  layer: domain
  name: Agency Revolution
  provider: agency-revolution
  says: lists Agency Revolution as an integration
  source: https://www.hawksoft.com/partners/
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
    agent_readiness: 22.3
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id003
      status: unknown
    slug: agencyzoom
    status: profiled
    tags: &id004
    - CRM
    - Insurance
    - Insurtech
    - Sales Automation
    url: /providers/agencyzoom/
  layer: domain
  name: AgencyZoom
  provider: agencyzoom
  says: lists AgencyZoom as an integration
  source: https://www.hawksoft.com/partners/
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
    mcp: &id005
      status: unchecked
    slug: canopy-connect
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: Canopy Connect
  provider: canopy-connect
  says: lists Canopy Connect as an integration
  source: https://www.hawksoft.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2150.20
    key: premium-collection-management
    name: Premium Collection Management
    url: /capabilities/premium-collection-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id007
      status: unchecked
    slug: epaypolicy
    status: profiled
    tags: &id008
    - Company
    - Fintech
    - Insurance
    - Payments
    url: /providers/epaypolicy/
  layer: domain
  name: ePayPolicy
  provider: epaypolicy
  says: lists ePayPolicy as an integration
  source: https://www.hawksoft.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2110
    key: insurance-distribution-management
    name: Insurance Distribution Management
    url: /capabilities/insurance-distribution-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id009
      status: none
    slug: ezlynx
    status: profiled
    tags: &id010
    - Agency Management System
    - Comparative Rating
    - Insurance
    - Insurtech
    url: /providers/ezlynx/
  layer: domain
  name: EZLynx
  provider: ezlynx
  says: lists EZLynx as an integration
  source: https://www.hawksoft.com/partners/
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
    agent_band: agent-ready
    agent_readiness: 33.2
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id011
      status: none
    slug: formstack
    status: profiled
    tags: &id012
    - Documents
    - E-Signature
    - Forms
    - Workflow Automation
    url: /providers/formstack/
  layer: domain
  name: Formstack
  provider: formstack
  says: lists Formstack as an integration
  source: https://www.hawksoft.com/partners/
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
    mcp: &id013
      status: none
    slug: podium
    status: profiled
    tags: &id014
    - Customer Communication
    - Messaging
    - Payments
    - Reviews
    url: /providers/podium/
  layer: domain
  name: Podium
  provider: podium
  says: lists Podium as an integration
  source: https://www.hawksoft.com/partners/
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
  source: https://www.hawksoft.com/partners/
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
    agent_readiness: 43.6
    band: strong
    in_catalog: true
    kin_score: 59.4
    mcp: &id017
      source: https://developers.ringcentral.com/mcp
      status: documented
    slug: ringcentral
    status: profiled
    tags: &id018
    - Communications
    - UCaaS
    - Video
    - Voice
    url: /providers/ringcentral/
  layer: common
  name: RingCentral
  provider: ringcentral
  says: lists RingCentral as an integration
  source: https://www.hawksoft.com/partners/
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
    agent_band: agent-aware
    agent_readiness: 7.4
    band: emerging
    in_catalog: true
    kin_score: 23.9
    mcp: &id019
      status: unchecked
    slug: rpost
    status: profiled
    tags: &id020
    - Compliance
    - Document Security
    - E-Signature
    - Email Security
    url: /providers/rpost/
  layer: domain
  name: RPost
  provider: rpost
  says: lists RPost as an integration
  source: https://www.hawksoft.com/partners/
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id021
      status: none
    slug: vertafore
    status: profiled
    tags: &id022
    - Agency Management
    - Insurance
    - Insurtech
    - Property and Casualty
    url: /providers/vertafore/
  layer: domain
  name: Vertafore
  provider: vertafore
  says: lists Vertafore as an integration
  source: https://www.hawksoft.com/partners/
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
    agent_band: agent-native
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 50.8
    mcp: &id023
      status: none
    slug: zywave
    status: profiled
    tags: &id024
    - Brokerage
    - Company
    - Insurance
    - Insurance Agencies
    url: /providers/zywave/
  layer: domain
  name: Zywave
  provider: zywave
  says: lists Zywave as an integration
  source: https://www.hawksoft.com/partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/insurance-policy-claims/hawksoft/
providers:
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id001
  name: Agency Revolution
  slug: agency-revolution
  status: profiled
  tags: *id002
  url: /providers/agency-revolution/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id003
  name: AgencyZoom
  slug: agencyzoom
  status: profiled
  tags: *id004
  url: /providers/agencyzoom/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: Canopy Connect
  slug: canopy-connect
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id007
  name: ePayPolicy
  slug: epaypolicy
  status: profiled
  tags: *id008
  url: /providers/epaypolicy/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id009
  name: EZLynx
  slug: ezlynx
  status: profiled
  tags: *id010
  url: /providers/ezlynx/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id011
  name: Formstack
  slug: formstack
  status: profiled
  tags: *id012
  url: /providers/formstack/
- agent_band: agent-native
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id013
  name: Podium
  slug: podium
  status: profiled
  tags: *id014
  url: /providers/podium/
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
- agent_band: agent-ready
  agent_readiness: 43.6
  band: strong
  in_catalog: true
  kin_score: 59.4
  mcp: *id017
  name: RingCentral
  slug: ringcentral
  status: profiled
  tags: *id018
  url: /providers/ringcentral/
- agent_band: agent-aware
  agent_readiness: 7.4
  band: emerging
  in_catalog: true
  kin_score: 23.9
  mcp: *id019
  name: RPost
  slug: rpost
  status: profiled
  tags: *id020
  url: /providers/rpost/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id021
  name: Vertafore
  slug: vertafore
  status: profiled
  tags: *id022
  url: /providers/vertafore/
- agent_band: agent-native
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 50.8
  mcp: *id023
  name: Zywave
  slug: zywave
  status: profiled
  tags: *id024
  url: /providers/zywave/
siblings:
- name: Duck Creek
  rows: 11
  url: /applications/insurance-policy-claims/duck-creek/
- name: EZLynx
  rows: 13
  url: /applications/insurance-policy-claims/ezlynx/
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
title: 'HawkSoft: Insurance Policy & Claims reference app'
---
