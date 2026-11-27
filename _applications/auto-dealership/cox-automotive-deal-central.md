---
app: Cox Automotive Deal Central
app_slug: cox-automotive-deal-central
app_url: https://www.coxautoinc.com/deal-central/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4000.40
  key: ancillary-add-on-product-management
  layer: domain
  name: Ancillary & Add-On Product Management
  providers:
  - Darwin Automotive
  url: /capabilities/ancillary-add-on-product-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.10
  key: credit-origination-management
  layer: domain
  name: Credit Origination Management
  providers:
  - Dealertrack F&I
  - RouteOne
  url: /capabilities/credit-origination-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-950
  key: AE-950
  layer: domain
  name: Dealer Management System Data Access
  providers:
  - CDK
  - Reynolds & Reynolds
  - Tekion
  url: /capabilities/dealer-management-system-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-3430
  key: dealer-network-management
  layer: domain
  name: Dealer Network Management
  providers:
  - Hyundai
  - Mazda
  url: /capabilities/dealer-network-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-948
  key: AE-948
  layer: domain
  name: Vehicle Valuation & Appraisal Guides
  providers:
  - vAuto
  url: /capabilities/vehicle-valuation-appraisal-guides/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - VinSolutions
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Dealer.com
  url: /capabilities/digital-marketing-management/
  via_parent: null
category:
  id: auto-dealership
  name: Auto Dealership Management
  url: /applications/auto-dealership/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.coxautoinc.com/deal-central/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-950
    key: AE-950
    name: Dealer Management System Data Access
    url: /capabilities/dealer-management-system-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id001
      source: https://www.cdkglobal.com/
      status: documented
    slug: cdk-global
    status: profiled
    tags: &id002
    - Auto Retail
    - Automotive
    - DMS
    - Dealer Management
    url: /providers/cdk-global/
  layer: domain
  name: CDK
  provider: cdk-global
  says: lists CDK as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4000.40
    key: ancillary-add-on-product-management
    name: Ancillary & Add-On Product Management
    url: /capabilities/ancillary-add-on-product-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id003
      status: unchecked
    slug: darwin-automotive
    status: profiled
    tags: &id004
    - Company
    url: /providers/darwin-automotive/
  layer: domain
  name: Darwin Automotive
  provider: darwin-automotive
  says: lists Darwin Automotive as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
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
    agent_band: agent-aware
    agent_readiness: 9.9
    band: developing
    in_catalog: true
    kin_score: 46.8
    mcp: &id005
      status: none
    slug: dealer-com
    status: profiled
    tags: &id006
    - Automotive
    - Dealership
    - Digital Marketing
    - Website Platform
    url: /providers/dealer-com/
  layer: common
  name: Dealer.com
  provider: dealer-com
  says: lists Dealer.com as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.10
    key: credit-origination-management
    name: Credit Origination Management
    url: /capabilities/credit-origination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id007
      status: unknown
    slug: dealertrack
    status: profiled
    tags: &id008
    - Automotive
    - DMS
    - Dealer Management System
    - Dealership
    url: /providers/dealertrack/
  layer: domain
  name: Dealertrack F&I
  provider: dealertrack
  says: lists Dealertrack F&I as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3430
    key: dealer-network-management
    name: Dealer Network Management
    url: /capabilities/dealer-network-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id009
      status: none
    slug: hyundai
    status: profiled
    tags: &id010
    - Automobiles
    - Cars
    - Connected Vehicles
    - Mobility
    url: /providers/hyundai/
  layer: domain
  name: Hyundai
  provider: hyundai
  says: lists Hyundai as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3430
    key: dealer-network-management
    name: Dealer Network Management
    url: /capabilities/dealer-network-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.1
    mcp: &id011
      status: unknown
    slug: mazda
    status: profiled
    tags: &id012
    - Company
    url: /providers/mazda/
  layer: domain
  name: Mazda
  provider: mazda
  says: lists Mazda as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-950
    key: AE-950
    name: Dealer Management System Data Access
    url: /capabilities/dealer-management-system-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id013
      status: unknown
    slug: reynolds-reynolds
    status: profiled
    tags: &id014
    - Automotive
    - DMS
    - Dealership Management System
    - Reynolds Certified Interface
    url: /providers/reynolds-reynolds/
  layer: domain
  name: Reynolds & Reynolds
  provider: reynolds-reynolds
  says: lists Reynolds & Reynolds as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.10
    key: credit-origination-management
    name: Credit Origination Management
    url: /capabilities/credit-origination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id015
      status: unchecked
    slug: routeone
    status: profiled
    tags: &id016
    - Automotive
    - Finance
    - Fintech
    - Insurance
    url: /providers/routeone/
  layer: domain
  name: RouteOne
  provider: routeone
  says: lists RouteOne as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-950
    key: AE-950
    name: Dealer Management System Data Access
    url: /capabilities/dealer-management-system-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id017
      status: unknown
    slug: tekion
    status: profiled
    tags: &id018
    - Automotive
    - Automotive Retail Cloud
    - DMS
    - Dealership
    url: /providers/tekion/
  layer: domain
  name: Tekion
  provider: tekion
  says: lists Tekion as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-948
    key: AE-948
    name: Vehicle Valuation & Appraisal Guides
    url: /capabilities/vehicle-valuation-appraisal-guides/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id019
      status: unknown
    slug: vauto
    status: profiled
    tags: &id020
    - Appraisal
    - Automotive
    - Dealership
    - Inventory
    url: /providers/vauto/
  layer: domain
  name: vAuto
  provider: vauto
  says: lists vAuto as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
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
    kin_score: 12.2
    mcp: &id021
      status: unchecked
    slug: vinsolutions
    status: profiled
    tags: &id022
    - Automotive
    - CRM
    - Dealership
    - Software
    url: /providers/vinsolutions/
  layer: common
  name: VinSolutions
  provider: vinsolutions
  says: lists VinSolutions as an integration
  source: https://www.coxautoinc.com/deal-central/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/cox-automotive-deal-central/
providers:
- agent_band: agent-aware
  agent_readiness: 26.5
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id001
  name: CDK
  slug: cdk-global
  status: profiled
  tags: *id002
  url: /providers/cdk-global/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id003
  name: Darwin Automotive
  slug: darwin-automotive
  status: profiled
  tags: *id004
  url: /providers/darwin-automotive/
- agent_band: agent-aware
  agent_readiness: 9.9
  band: developing
  in_catalog: true
  kin_score: 46.8
  mcp: *id005
  name: Dealer.com
  slug: dealer-com
  status: profiled
  tags: *id006
  url: /providers/dealer-com/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id007
  name: Dealertrack F&I
  slug: dealertrack
  status: profiled
  tags: *id008
  url: /providers/dealertrack/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id009
  name: Hyundai
  slug: hyundai
  status: profiled
  tags: *id010
  url: /providers/hyundai/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id011
  name: Mazda
  slug: mazda
  status: profiled
  tags: *id012
  url: /providers/mazda/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id013
  name: Reynolds & Reynolds
  slug: reynolds-reynolds
  status: profiled
  tags: *id014
  url: /providers/reynolds-reynolds/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id015
  name: RouteOne
  slug: routeone
  status: profiled
  tags: *id016
  url: /providers/routeone/
- agent_band: human-only
  agent_readiness: 0.6
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id017
  name: Tekion
  slug: tekion
  status: profiled
  tags: *id018
  url: /providers/tekion/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id019
  name: vAuto
  slug: vauto
  status: profiled
  tags: *id020
  url: /providers/vauto/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id021
  name: VinSolutions
  slug: vinsolutions
  status: profiled
  tags: *id022
  url: /providers/vinsolutions/
siblings:
- name: AutoHub
  rows: 17
  url: /applications/auto-dealership/autohub/
- name: AutoRaptor
  rows: 3
  url: /applications/auto-dealership/autoraptor/
- name: Autosoft DMS
  rows: 16
  url: /applications/auto-dealership/autosoft-dms/
- name: DealerBuilt (LightYear DMS)
  rows: 36
  url: /applications/auto-dealership/dealerbuilt-lightyear-dms/
- name: DealersCloud
  rows: 19
  url: /applications/auto-dealership/dealerscloud/
- name: DealerSocket
  rows: 1
  url: /applications/auto-dealership/dealersocket/
- name: GetMyAuto
  rows: 36
  url: /applications/auto-dealership/getmyauto/
sitemap: true
title: 'Cox Automotive Deal Central: Auto Dealership Management reference app'
---
