---
app: AutoHub
app_slug: autohub
app_url: https://www.autohub.io/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-950
  key: AE-950
  layer: domain
  name: Dealer Management System Data Access
  providers:
  - Auto/Mate
  - Autosoft
  - CDK
  - Dealertrack DMS
  - Dominion DMS
  - PBS Systems
  - Reynolds & Reynolds
  - Tekion
  url: /capabilities/dealer-management-system-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-4970.30
  key: market-data-comparable-curation
  layer: domain
  name: Market Data & Comparable Curation
  providers:
  - ACV MAX
  - DealersLink
  url: /capabilities/market-data-comparable-curation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-949
  key: AE-949
  layer: domain
  name: Vehicle History Reports
  providers:
  - AutoCheck (Experian)
  - CARFAX
  url: /capabilities/vehicle-history-reports/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-948
  key: AE-948
  layer: domain
  name: Vehicle Valuation & Appraisal Guides
  providers:
  - FirstLook
  - Kelley Blue Book
  - Manheim Market Report
  - vAuto
  - VinCue
  url: /capabilities/vehicle-valuation-appraisal-guides/
  via_parent: null
category:
  id: auto-dealership
  name: Auto Dealership Management
  url: /applications/auto-dealership/
counts:
  declared: 17
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.autohub.io/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4970.30
    key: market-data-comparable-curation
    name: Market Data & Comparable Curation
    url: /capabilities/market-data-comparable-curation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id001
      status: none
    slug: acv-auctions
    status: profiled
    tags: &id002
    - Automotive
    - Company
    - Marketplace
    - Vertical Software
    url: /providers/acv-auctions/
  layer: domain
  name: ACV MAX
  provider: acv-auctions
  says: lists ACV MAX as an integration
  source: https://www.autohub.io/integrations/
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
    kin_score: 5.7
    mcp: &id003
      status: none
    slug: automate
    status: profiled
    tags: &id004
    - Automotive
    - Company
    - Dealer Management
    - Software
    url: /providers/automate/
  layer: domain
  name: Auto/Mate
  provider: automate
  says: lists Auto/Mate as an integration
  source: https://www.autohub.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-949
    key: AE-949
    name: Vehicle History Reports
    url: /capabilities/vehicle-history-reports/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id005
      status: none
    slug: experian
    status: profiled
    tags: &id006
    - Company
    - Credit Bureau
    - Credit Reporting
    - Identity Verification
    url: /providers/experian/
  layer: domain
  name: AutoCheck (Experian)
  provider: experian
  says: lists AutoCheck (Experian) as an integration
  source: https://www.autohub.io/integrations/
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id007
      status: unchecked
    slug: autosoft
    status: profiled
    tags: &id008
    - Automotive
    - Company
    - Dealership
    - ManagementSoftware
    url: /providers/autosoft/
  layer: domain
  name: Autosoft
  provider: autosoft
  says: lists Autosoft as an integration
  source: https://www.autohub.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-949
    key: AE-949
    name: Vehicle History Reports
    url: /capabilities/vehicle-history-reports/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 18.2
    mcp: &id009
      status: none
    slug: carfax
    status: profiled
    tags: &id010
    - Automotive
    - Used Cars
    - VIN Lookup
    - Vehicle History
    url: /providers/carfax/
  layer: domain
  name: CARFAX
  provider: carfax
  says: lists CARFAX as an integration
  source: https://www.autohub.io/integrations/
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
    agent_band: agent-aware
    agent_readiness: 26.5
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id011
      source: https://www.cdkglobal.com/
      status: documented
    slug: cdk-global
    status: profiled
    tags: &id012
    - Auto Retail
    - Automotive
    - DMS
    - Dealer Management
    url: /providers/cdk-global/
  layer: domain
  name: CDK
  provider: cdk-global
  says: lists CDK as an integration
  source: https://www.autohub.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4970.30
    key: market-data-comparable-curation
    name: Market Data & Comparable Curation
    url: /capabilities/market-data-comparable-curation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id013
      status: unchecked
    slug: dealerslink
    status: profiled
    tags: &id014
    - Auto
    - Company
    - Dealership
    - Inventory
    url: /providers/dealerslink/
  layer: domain
  name: DealersLink
  provider: dealerslink
  says: lists DealersLink as an integration
  source: https://www.autohub.io/integrations/
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
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id015
      status: unknown
    slug: dealertrack
    status: profiled
    tags: &id016
    - Automotive
    - DMS
    - Dealer Management System
    - Dealership
    url: /providers/dealertrack/
  layer: domain
  name: Dealertrack DMS
  provider: dealertrack
  says: lists Dealertrack DMS as an integration
  source: https://www.autohub.io/integrations/
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id017
      status: unchecked
    slug: dominion-dms
    status: profiled
    tags: &id018
    - Automotive
    - CRM
    - Dealer Management
    - Software
    url: /providers/dominion-dms/
  layer: domain
  name: Dominion DMS
  provider: dominion-dms
  says: lists Dominion DMS as an integration
  source: https://www.autohub.io/integrations/
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
    kin_score: 0.4
    mcp: &id019
      status: unchecked
    slug: firstlook
    status: profiled
    tags: &id020
    - Company
    url: /providers/firstlook/
  layer: domain
  name: FirstLook
  provider: firstlook
  says: lists FirstLook as an integration
  source: https://www.autohub.io/integrations/
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
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 13.3
    mcp: &id021
      status: unknown
    slug: kbb
    status: profiled
    tags: &id022
    - Automotive
    - Car Pricing
    - Trade-In
    - Vehicle Valuation
    url: /providers/kbb/
  layer: domain
  name: Kelley Blue Book
  provider: kbb
  says: lists Kelley Blue Book as an integration
  source: https://www.autohub.io/integrations/
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 12.9
    mcp: &id023
      status: unchecked
    slug: manheim
    status: profiled
    tags: &id024
    - Automotive
    - Marketplace
    - Vehicles
    - Wholesale
    url: /providers/manheim/
  layer: domain
  name: Manheim Market Report
  provider: manheim
  says: lists Manheim Market Report as an integration
  source: https://www.autohub.io/integrations/
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
    agent_readiness: 3.9
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id025
      status: unchecked
    slug: pbs-systems
    status: profiled
    tags: &id026
    - Automotive
    - DMS
    - Dealer Management
    - Software
    url: /providers/pbs-systems/
  layer: domain
  name: PBS Systems
  provider: pbs-systems
  says: lists PBS Systems as an integration
  source: https://www.autohub.io/integrations/
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
    mcp: &id027
      status: unknown
    slug: reynolds-reynolds
    status: profiled
    tags: &id028
    - Automotive
    - DMS
    - Dealership Management System
    - Reynolds Certified Interface
    url: /providers/reynolds-reynolds/
  layer: domain
  name: Reynolds & Reynolds
  provider: reynolds-reynolds
  says: lists Reynolds & Reynolds as an integration
  source: https://www.autohub.io/integrations/
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
    mcp: &id029
      status: unknown
    slug: tekion
    status: profiled
    tags: &id030
    - Automotive
    - Automotive Retail Cloud
    - DMS
    - Dealership
    url: /providers/tekion/
  layer: domain
  name: Tekion
  provider: tekion
  says: lists Tekion as an integration
  source: https://www.autohub.io/integrations/
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
    mcp: &id031
      status: unknown
    slug: vauto
    status: profiled
    tags: &id032
    - Appraisal
    - Automotive
    - Dealership
    - Inventory
    url: /providers/vauto/
  layer: domain
  name: vAuto
  provider: vauto
  says: lists vAuto as an integration
  source: https://www.autohub.io/integrations/
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id033
      status: unchecked
    slug: vincue
    status: profiled
    tags: &id034
    - Automotive
    - Dealership
    - Inventory
    - Software-as-a-Service
    url: /providers/vincue/
  layer: domain
  name: VinCue
  provider: vincue
  says: lists VinCue as an integration
  source: https://www.autohub.io/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/autohub/
providers:
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id001
  name: ACV MAX
  slug: acv-auctions
  status: profiled
  tags: *id002
  url: /providers/acv-auctions/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id003
  name: Auto/Mate
  slug: automate
  status: profiled
  tags: *id004
  url: /providers/automate/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id005
  name: AutoCheck (Experian)
  slug: experian
  status: profiled
  tags: *id006
  url: /providers/experian/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id007
  name: Autosoft
  slug: autosoft
  status: profiled
  tags: *id008
  url: /providers/autosoft/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id009
  name: CARFAX
  slug: carfax
  status: profiled
  tags: *id010
  url: /providers/carfax/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id011
  name: CDK
  slug: cdk-global
  status: profiled
  tags: *id012
  url: /providers/cdk-global/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id013
  name: DealersLink
  slug: dealerslink
  status: profiled
  tags: *id014
  url: /providers/dealerslink/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id015
  name: Dealertrack DMS
  slug: dealertrack
  status: profiled
  tags: *id016
  url: /providers/dealertrack/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id017
  name: Dominion DMS
  slug: dominion-dms
  status: profiled
  tags: *id018
  url: /providers/dominion-dms/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id019
  name: FirstLook
  slug: firstlook
  status: profiled
  tags: *id020
  url: /providers/firstlook/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 13.3
  mcp: *id021
  name: Kelley Blue Book
  slug: kbb
  status: profiled
  tags: *id022
  url: /providers/kbb/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 12.9
  mcp: *id023
  name: Manheim Market Report
  slug: manheim
  status: profiled
  tags: *id024
  url: /providers/manheim/
- agent_band: human-only
  agent_readiness: 3.9
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id025
  name: PBS Systems
  slug: pbs-systems
  status: profiled
  tags: *id026
  url: /providers/pbs-systems/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id027
  name: Reynolds & Reynolds
  slug: reynolds-reynolds
  status: profiled
  tags: *id028
  url: /providers/reynolds-reynolds/
- agent_band: human-only
  agent_readiness: 0.6
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id029
  name: Tekion
  slug: tekion
  status: profiled
  tags: *id030
  url: /providers/tekion/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id031
  name: vAuto
  slug: vauto
  status: profiled
  tags: *id032
  url: /providers/vauto/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id033
  name: VinCue
  slug: vincue
  status: profiled
  tags: *id034
  url: /providers/vincue/
siblings:
- name: AutoRaptor
  rows: 3
  url: /applications/auto-dealership/autoraptor/
- name: Autosoft DMS
  rows: 16
  url: /applications/auto-dealership/autosoft-dms/
- name: Cox Automotive Deal Central
  rows: 11
  url: /applications/auto-dealership/cox-automotive-deal-central/
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
title: 'AutoHub: Auto Dealership Management reference app'
---
