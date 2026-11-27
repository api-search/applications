---
app: DealersCloud
app_slug: dealerscloud
app_url: https://www.dealerscloud.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1320.10
  key: credit-origination-management
  layer: domain
  name: Credit Origination Management
  providers:
  - Credit Acceptance
  - CUDL
  - Dealertrack
  - RouteOne
  url: /capabilities/credit-origination-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.20
  key: credit-underwriting-decisioning-management
  layer: domain
  name: Credit Underwriting & Decisioning Management
  providers:
  - 700Credit
  url: /capabilities/credit-underwriting-decisioning-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2330.40
  key: marketplace-seller-operations-management
  layer: domain
  name: Marketplace Seller Operations Management
  providers:
  - Facebook
  - Google
  url: /capabilities/marketplace-seller-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3450
  key: vehicle-aftersales-warranty-management
  layer: domain
  name: Vehicle Aftersales & Warranty Management
  providers:
  - Carketa
  url: /capabilities/vehicle-aftersales-warranty-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-949
  key: AE-949
  layer: domain
  name: Vehicle History Reports
  providers:
  - CARFAX
  url: /capabilities/vehicle-history-reports/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-951
  key: AE-951
  layer: domain
  name: Vehicle Inventory Listing Syndication
  providers:
  - Autotrader
  - CarGurus
  - Cars.com
  - Edmunds
  - KSL Cars
  - TrueCar
  url: /capabilities/vehicle-inventory-listing-syndication/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-952
  key: AE-952
  layer: domain
  name: Vehicle Transport & Car Shipping
  providers:
  - DriveDrop
  url: /capabilities/vehicle-transport-car-shipping/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-948
  key: AE-948
  layer: domain
  name: Vehicle Valuation & Appraisal Guides
  providers:
  - J.D. Power
  - vAuto
  url: /capabilities/vehicle-valuation-appraisal-guides/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Xplor Pay
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: auto-dealership
  name: Auto Dealership Management
  url: /applications/auto-dealership/
counts:
  declared: 19
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.dealerscloud.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1320.20
    key: credit-underwriting-decisioning-management
    name: Credit Underwriting & Decisioning Management
    url: /capabilities/credit-underwriting-decisioning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id001
      status: unchecked
    slug: 700credit
    status: profiled
    tags: &id002
    - Automotive
    - Compliance
    - Credit
    - Identity Verification
    url: /providers/700credit/
  layer: domain
  name: 700Credit
  provider: 700credit
  says: lists 700Credit as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.0
    mcp: &id003
      status: unknown
    slug: autotradercom
    status: profiled
    tags: &id004
    - Automotive
    - Company
    - Consumer
    - Marketplace
    url: /providers/autotradercom/
  layer: domain
  name: Autotrader
  provider: autotradercom
  says: lists Autotrader as an integration
  source: https://www.dealerscloud.com/integrations
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
    mcp: &id005
      status: none
    slug: carfax
    status: profiled
    tags: &id006
    - Automotive
    - Used Cars
    - VIN Lookup
    - Vehicle History
    url: /providers/carfax/
  layer: domain
  name: CARFAX
  provider: carfax
  says: lists CARFAX as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id007
      source: https://cargurus.helpscoutdocs.com/article/599-connect-ai-assistants-to-cargurus-with-the-mcp-connector
      status: verified
    slug: cargurus-dealer
    status: profiled
    tags: &id008
    - Automotive
    - Car Listings
    - Dealers
    - Marketplace
    url: /providers/cargurus-dealer/
  layer: domain
  name: CarGurus
  provider: cargurus-dealer
  says: lists CarGurus as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3450
    key: vehicle-aftersales-warranty-management
    name: Vehicle Aftersales & Warranty Management
    url: /capabilities/vehicle-aftersales-warranty-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id009
      status: unknown
    slug: carketa
    status: profiled
    tags: &id010
    - Company
    url: /providers/carketa/
  layer: domain
  name: Carketa
  provider: carketa
  says: lists Carketa as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id011
      status: unchecked
    slug: cars-com
    status: profiled
    tags: &id012
    - Car Buying
    - Car Selling
    - Vehicle Research
    url: /providers/cars-com/
  layer: domain
  name: Cars.com
  provider: cars-com
  says: lists Cars.com as an integration
  source: https://www.dealerscloud.com/integrations
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
    kin_score: 7.6
    mcp: &id013
      status: unchecked
    slug: credit-acceptance
    status: profiled
    tags: &id014
    - Auto
    - Finance
    - Lending
    - Subprime
    url: /providers/credit-acceptance/
  layer: domain
  name: Credit Acceptance
  provider: credit-acceptance
  says: lists Credit Acceptance as an integration
  source: https://www.dealerscloud.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id015
      status: unchecked
    slug: cudl
    status: profiled
    tags: &id016
    - Auto Finance
    - Company
    - Fintech
    - Lending
    url: /providers/cudl/
  layer: domain
  name: CUDL
  provider: cudl
  says: lists CUDL as an integration
  source: https://www.dealerscloud.com/integrations
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
    mcp: &id017
      status: unknown
    slug: dealertrack
    status: profiled
    tags: &id018
    - Automotive
    - DMS
    - Dealer Management System
    - Dealership
    url: /providers/dealertrack/
  layer: domain
  name: Dealertrack
  provider: dealertrack
  says: lists Dealertrack as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-952
    key: AE-952
    name: Vehicle Transport & Car Shipping
    url: /capabilities/vehicle-transport-car-shipping/
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
    slug: drivedrop
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: DriveDrop
  provider: drivedrop
  says: lists DriveDrop as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id021
      status: none
    slug: edmunds
    status: profiled
    tags: &id022
    - Automobiles
    - Cars
    - Vehicle Data
    - Vehicles
    url: /providers/edmunds/
  layer: domain
  name: Edmunds
  provider: edmunds
  says: lists Edmunds as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2330.40
    key: marketplace-seller-operations-management
    name: Marketplace Seller Operations Management
    url: /capabilities/marketplace-seller-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id023
      status: none
    slug: facebook
    status: profiled
    tags: &id024
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2330.40
    key: marketplace-seller-operations-management
    name: Marketplace Seller Operations Management
    url: /capabilities/marketplace-seller-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id025
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id026
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google
  provider: google
  says: lists Google as an integration
  source: https://www.dealerscloud.com/integrations
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
    mcp: &id027
      status: unchecked
    slug: jd-power
    status: profiled
    tags: &id028
    - Company
    url: /providers/jd-power/
  layer: domain
  name: J.D. Power
  provider: jd-power
  says: lists J.D. Power as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.8
    mcp: &id029
      status: unchecked
    slug: ksl
    status: profiled
    tags: &id030
    - New Cars
    - Used Cars
    - Utah
    - Vehicle Listings
    url: /providers/ksl/
  layer: domain
  name: KSL Cars
  provider: ksl
  says: lists KSL Cars as an integration
  source: https://www.dealerscloud.com/integrations
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
    mcp: &id031
      status: unchecked
    slug: routeone
    status: profiled
    tags: &id032
    - Automotive
    - Finance
    - Fintech
    - Insurance
    url: /providers/routeone/
  layer: domain
  name: RouteOne
  provider: routeone
  says: lists RouteOne as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id033
      status: none
    slug: truecar
    status: profiled
    tags: &id034
    - Automotive
    - Car Buying
    - Company
    - Marketplace
    url: /providers/truecar/
  layer: domain
  name: TrueCar
  provider: truecar
  says: lists TrueCar as an integration
  source: https://www.dealerscloud.com/integrations
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
    mcp: &id035
      status: unknown
    slug: vauto
    status: profiled
    tags: &id036
    - Appraisal
    - Automotive
    - Dealership
    - Inventory
    url: /providers/vauto/
  layer: domain
  name: vAuto
  provider: vauto
  says: lists vAuto as an integration
  source: https://www.dealerscloud.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 33.1
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id037
      status: unchecked
    slug: xplor-pay
    status: profiled
    tags: &id038
    - Embedded Payments
    - Merchant Solutions
    - PayFac as a Service
    - Vertical SaaS
    url: /providers/xplor-pay/
  layer: common
  name: Xplor Pay
  provider: xplor-pay
  says: lists Xplor Pay as an integration
  source: https://www.dealerscloud.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/dealerscloud/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id001
  name: 700Credit
  slug: 700credit
  status: profiled
  tags: *id002
  url: /providers/700credit/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.0
  mcp: *id003
  name: Autotrader
  slug: autotradercom
  status: profiled
  tags: *id004
  url: /providers/autotradercom/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id005
  name: CARFAX
  slug: carfax
  status: profiled
  tags: *id006
  url: /providers/carfax/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id007
  name: CarGurus
  slug: cargurus-dealer
  status: profiled
  tags: *id008
  url: /providers/cargurus-dealer/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id009
  name: Carketa
  slug: carketa
  status: profiled
  tags: *id010
  url: /providers/carketa/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id011
  name: Cars.com
  slug: cars-com
  status: profiled
  tags: *id012
  url: /providers/cars-com/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id013
  name: Credit Acceptance
  slug: credit-acceptance
  status: profiled
  tags: *id014
  url: /providers/credit-acceptance/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id015
  name: CUDL
  slug: cudl
  status: profiled
  tags: *id016
  url: /providers/cudl/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id017
  name: Dealertrack
  slug: dealertrack
  status: profiled
  tags: *id018
  url: /providers/dealertrack/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: DriveDrop
  slug: drivedrop
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-aware
  agent_readiness: 28.4
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id021
  name: Edmunds
  slug: edmunds
  status: profiled
  tags: *id022
  url: /providers/edmunds/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id023
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id024
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id025
  name: Google
  slug: google
  status: profiled
  tags: *id026
  url: /providers/google/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id027
  name: J.D. Power
  slug: jd-power
  status: profiled
  tags: *id028
  url: /providers/jd-power/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id029
  name: KSL Cars
  slug: ksl
  status: profiled
  tags: *id030
  url: /providers/ksl/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id031
  name: RouteOne
  slug: routeone
  status: profiled
  tags: *id032
  url: /providers/routeone/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id033
  name: TrueCar
  slug: truecar
  status: profiled
  tags: *id034
  url: /providers/truecar/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id035
  name: vAuto
  slug: vauto
  status: profiled
  tags: *id036
  url: /providers/vauto/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id037
  name: Xplor Pay
  slug: xplor-pay
  status: profiled
  tags: *id038
  url: /providers/xplor-pay/
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
- name: Cox Automotive Deal Central
  rows: 11
  url: /applications/auto-dealership/cox-automotive-deal-central/
- name: DealerBuilt (LightYear DMS)
  rows: 36
  url: /applications/auto-dealership/dealerbuilt-lightyear-dms/
- name: DealerSocket
  rows: 1
  url: /applications/auto-dealership/dealersocket/
- name: GetMyAuto
  rows: 36
  url: /applications/auto-dealership/getmyauto/
sitemap: true
title: 'DealersCloud: Auto Dealership Management reference app'
---
