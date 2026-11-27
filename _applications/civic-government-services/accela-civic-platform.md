---
app: Accela Civic Platform
app_slug: accela-civic-platform
app_url: https://www.accela.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3220
  key: citizen-constituent-service-management
  layer: domain
  name: Citizen & Constituent Service Management
  providers:
  - buildingeye (AgencyCounter)
  url: /capabilities/citizen-constituent-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-946
  key: AE-946
  layer: domain
  name: Electronic Plan Review
  providers:
  - Avolve Software
  url: /capabilities/electronic-plan-review/
  via_parent: null
- attribution: Turbo EA
  id: BC-1130
  key: engineering-document-management
  layer: domain
  name: Engineering Document Management
  providers:
  - Adobe
  url: /capabilities/engineering-document-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - ACI Worldwide
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.accela.com/partners/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id001
      source: https://docs.aciworldwide.com/node/323
      status: verified
    slug: aci-worldwide
    status: profiled
    tags: &id002
    - Payment Gateway
    - Payment Processing
    - Payments
    - United States
    url: /providers/aci-worldwide/
  layer: domain
  name: ACI Worldwide
  provider: aci-worldwide
  says: lists ACI Worldwide as an integration
  source: https://www.accela.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1130
    key: engineering-document-management
    name: Engineering Document Management
    url: /capabilities/engineering-document-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id003
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id004
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
  layer: domain
  name: Adobe
  provider: adobe
  says: lists Adobe as an integration
  source: https://www.accela.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-946
    key: AE-946
    name: Electronic Plan Review
    url: /capabilities/electronic-plan-review/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id005
      status: unchecked
    slug: avolve-software
    status: profiled
    tags: &id006
    - GIS
    - Government
    - Infrastructure
    - Software
    url: /providers/avolve-software/
  layer: domain
  name: Avolve Software
  provider: avolve-software
  says: lists Avolve Software as an integration
  source: https://www.accela.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3220
    key: citizen-constituent-service-management
    name: Citizen & Constituent Service Management
    url: /capabilities/citizen-constituent-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id007
      status: unchecked
    slug: buildingeye
    status: profiled
    tags: &id008
    - Accessibility
    - GIS
    - GovTech
    - Public Data
    url: /providers/buildingeye/
  layer: domain
  name: buildingeye (AgencyCounter)
  provider: buildingeye
  says: lists buildingeye (AgencyCounter) as an integration
  source: https://www.accela.com/partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/accela-civic-platform/
providers:
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id001
  name: ACI Worldwide
  slug: aci-worldwide
  status: profiled
  tags: *id002
  url: /providers/aci-worldwide/
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id003
  name: Adobe
  slug: adobe
  status: profiled
  tags: *id004
  url: /providers/adobe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id005
  name: Avolve Software
  slug: avolve-software
  status: profiled
  tags: *id006
  url: /providers/avolve-software/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id007
  name: buildingeye (AgencyCounter)
  slug: buildingeye
  status: profiled
  tags: *id008
  url: /providers/buildingeye/
siblings:
- name: Alaveteli
  rows: 4
  url: /applications/civic-government-services/alaveteli/
- name: CONSUL Democracy
  rows: 5
  url: /applications/civic-government-services/consul-democracy/
- name: Decidim
  rows: 7
  url: /applications/civic-government-services/decidim/
- name: FixMyStreet
  rows: 8
  url: /applications/civic-government-services/fixmystreet/
- name: Go Vocal (CitizenLab)
  rows: 10
  url: /applications/civic-government-services/go-vocal-citizenlab/
- name: Granicus (govDelivery)
  rows: 1
  url: /applications/civic-government-services/granicus-govdelivery/
- name: SeeClickFix (CivicPlus)
  rows: 21
  url: /applications/civic-government-services/seeclickfix-civicplus/
sitemap: true
title: 'Accela Civic Platform: Civic & Government Services reference app'
---
