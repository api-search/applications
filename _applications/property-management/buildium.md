---
app: Buildium
app_slug: buildium
app_url: https://www.buildium.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2370.30
  key: channel-syndication-management
  layer: domain
  name: Channel Syndication Management
  providers:
  - Apartment List
  - Apartments.com
  - Dwellsy
  - HotPads
  - Lovely
  - Trulia
  - Zillow
  - Zumper
  url: /capabilities/channel-syndication-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3240.40
  key: inspection-and-compliance-verification
  layer: domain
  name: Inspection and Compliance Verification
  providers:
  - HappyCo
  url: /capabilities/inspection-and-compliance-verification/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Forte (CSG Forte)
  - PayNearMe
  - RevSpring
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.40
  key: BC-220.40
  layer: domain
  name: Tax Reporting & Compliance
  providers:
  - Nelco
  url: /capabilities/tax-reporting-compliance/
  via_parent: null
- attribution: Turbo EA
  id: BC-4950.40
  key: tenant-application-screening
  layer: domain
  name: Tenant Application & Screening
  providers:
  - Tenant Turner
  - TransUnion
  url: /capabilities/tenant-application-screening/
  via_parent: null
category:
  id: property-management
  name: Property & Rental Management
  url: /applications/property-management/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.buildium.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2370.30
    key: channel-syndication-management
    name: Channel Syndication Management
    url: /capabilities/channel-syndication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id001
      status: none
    slug: apartment-list
    status: profiled
    tags: &id002
    - Company
    - Housing
    - Real Estate
    - Rentals
    url: /providers/apartment-list/
  layer: domain
  name: Apartment List
  provider: apartment-list
  says: lists Apartment List as an integration
  source: https://www.buildium.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.6
    mcp: &id003
      status: unknown
    slug: apartments-com
    status: profiled
    tags: &id004
    - Property Listings
    - Real Estate
    - Rentals
    - United States
    url: /providers/apartments-com/
  layer: domain
  name: Apartments.com
  provider: apartments-com
  says: lists Apartments.com as an integration
  source: https://www.buildium.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 29.1
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id005
      status: none
    slug: dwellsy
    status: profiled
    tags: &id006
    - Company
    url: /providers/dwellsy/
  layer: domain
  name: Dwellsy
  provider: dwellsy
  says: lists Dwellsy as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
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
    agent_readiness: 22.3
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id007
      status: none
    slug: csg
    status: profiled
    tags: &id008
    - Billing
    - Customer Engagement
    - Payments
    - Revenue Management
    url: /providers/csg/
  layer: domain
  name: Forte (CSG Forte)
  provider: csg
  says: lists Forte (CSG Forte) as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3240.40
    key: inspection-and-compliance-verification
    name: Inspection and Compliance Verification
    url: /capabilities/inspection-and-compliance-verification/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 46.1
    mcp: &id009
      status: unknown
    slug: happyco
    status: profiled
    tags: &id010
    - Company
    - PropTech
    - Property Management
    - Real Estate
    url: /providers/happyco/
  layer: domain
  name: HappyCo
  provider: happyco
  says: lists HappyCo as an integration
  source: https://www.buildium.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: hotpads
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: HotPads
  provider: hotpads
  says: lists HotPads as an integration
  source: https://www.buildium.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: lovely
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Lovely
  provider: lovely
  says: lists Lovely as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.40
    key: BC-220.40
    name: Tax Reporting & Compliance
    url: /capabilities/tax-reporting-compliance/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id015
      status: unknown
    slug: nelco
    status: profiled
    tags: &id016
    - Compliance
    - Electronic Filing
    - Software Integration
    - Tax Forms
    url: /providers/nelco/
  layer: domain
  name: Nelco
  provider: nelco
  says: lists Nelco as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
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
    agent_readiness: 14.0
    band: thin
    in_catalog: true
    kin_score: 31.2
    mcp: &id017
      status: unknown
    slug: paynearme
    status: profiled
    tags: &id018
    - Billing
    - Company
    - Fintech
    - Payments
    url: /providers/paynearme/
  layer: domain
  name: PayNearMe
  provider: paynearme
  says: lists PayNearMe as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: revspring
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: RevSpring
  provider: revspring
  says: lists RevSpring as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4950.40
    key: tenant-application-screening
    name: Tenant Application & Screening
    url: /capabilities/tenant-application-screening/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id021
      status: unknown
    slug: tenant-turner
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Automation
    - Leasing
    - Property Management
    url: /providers/tenant-turner/
  layer: domain
  name: Tenant Turner
  provider: tenant-turner
  says: lists Tenant Turner as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4950.40
    key: tenant-application-screening
    name: Tenant Application & Screening
    url: /capabilities/tenant-application-screening/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.2
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id023
      status: unknown
    slug: transunion
    status: profiled
    tags: &id024
    - Credit Reporting
    - Finance
    - Identity
    - Risk Management
    url: /providers/transunion/
  layer: domain
  name: TransUnion
  provider: transunion
  says: lists TransUnion as an integration
  source: https://www.buildium.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 15.9
    mcp: &id025
      status: none
    slug: trulia
    status: profiled
    tags: &id026
    - Acquired
    - Historical
    - Listings
    - Neighborhoods
    url: /providers/trulia/
  layer: domain
  name: Trulia
  provider: trulia
  says: lists Trulia as an integration
  source: https://www.buildium.com/integrations/
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
    agent_readiness: 22.3
    band: thin
    in_catalog: true
    kin_score: 38.5
    mcp: &id027
      status: none
    slug: zillow-group
    status: profiled
    tags: &id028
    - MLS
    - Mortgage
    - Property Data
    - Real Estate
    url: /providers/zillow-group/
  layer: domain
  name: Zillow
  provider: zillow-group
  says: lists Zillow as an integration
  source: https://www.buildium.com/integrations/
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id029
      status: unknown
    slug: zumper
    status: profiled
    tags: &id030
    - Apartments
    - Property Management
    - Real Estate
    - Rental Listings
    url: /providers/zumper/
  layer: domain
  name: Zumper
  provider: zumper
  says: lists Zumper as an integration
  source: https://www.buildium.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/property-management/buildium/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id001
  name: Apartment List
  slug: apartment-list
  status: profiled
  tags: *id002
  url: /providers/apartment-list/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id003
  name: Apartments.com
  slug: apartments-com
  status: profiled
  tags: *id004
  url: /providers/apartments-com/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id005
  name: Dwellsy
  slug: dwellsy
  status: profiled
  tags: *id006
  url: /providers/dwellsy/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id007
  name: Forte (CSG Forte)
  slug: csg
  status: profiled
  tags: *id008
  url: /providers/csg/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id009
  name: HappyCo
  slug: happyco
  status: profiled
  tags: *id010
  url: /providers/happyco/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: HotPads
  slug: hotpads
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Lovely
  slug: lovely
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id015
  name: Nelco
  slug: nelco
  status: profiled
  tags: *id016
  url: /providers/nelco/
- agent_band: agent-aware
  agent_readiness: 14.0
  band: thin
  in_catalog: true
  kin_score: 31.2
  mcp: *id017
  name: PayNearMe
  slug: paynearme
  status: profiled
  tags: *id018
  url: /providers/paynearme/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: RevSpring
  slug: revspring
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id021
  name: Tenant Turner
  slug: tenant-turner
  status: profiled
  tags: *id022
  url: /providers/tenant-turner/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id023
  name: TransUnion
  slug: transunion
  status: profiled
  tags: *id024
  url: /providers/transunion/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 15.9
  mcp: *id025
  name: Trulia
  slug: trulia
  status: profiled
  tags: *id026
  url: /providers/trulia/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: thin
  in_catalog: true
  kin_score: 38.5
  mcp: *id027
  name: Zillow
  slug: zillow-group
  status: profiled
  tags: *id028
  url: /providers/zillow-group/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id029
  name: Zumper
  slug: zumper
  status: profiled
  tags: *id030
  url: /providers/zumper/
siblings:
- name: AppFolio
  rows: 6
  url: /applications/property-management/appfolio/
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
title: 'Buildium: Property & Rental Management reference app'
---
