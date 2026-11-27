---
app: Autosoft DMS
app_slug: autosoft-dms
app_url: https://autosoftdms.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4000.40
  key: ancillary-add-on-product-management
  layer: domain
  name: Ancillary & Add-On Product Management
  providers:
  - StoneEagle F&I
  - Vision Menu
  url: /capabilities/ancillary-add-on-product-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.10
  key: credit-origination-management
  layer: domain
  name: Credit Origination Management
  providers:
  - CUDL
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
  id: BC-3460.30
  key: in-vehicle-app-and-subscription-management
  layer: domain
  name: In-Vehicle App and Subscription Management
  providers:
  - SiriusXM
  url: /capabilities/in-vehicle-app-and-subscription-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.30
  key: market-intelligence-management
  layer: domain
  name: Market Intelligence Management
  providers:
  - J.D. Power
  url: /capabilities/market-intelligence-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2330.40
  key: marketplace-seller-operations-management
  layer: domain
  name: Marketplace Seller Operations Management
  providers:
  - Auction123
  url: /capabilities/marketplace-seller-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1060
  key: spare-parts-aftermarket-management
  layer: domain
  name: Spare Parts & Aftermarket Management
  providers:
  - OEConnection
  - SmartCo PartsEye
  url: /capabilities/spare-parts-aftermarket-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3450
  key: vehicle-aftersales-warranty-management
  layer: domain
  name: Vehicle Aftersales & Warranty Management
  providers:
  - Dynatron (KEEPS)
  - Recon Advisor
  - Xtime
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
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - DealerMine
  - DealerSocket
  - VinSolutions
  url: /capabilities/customer-relationship-management/
  via_parent: null
category:
  id: auto-dealership
  name: Auto Dealership Management
  url: /applications/auto-dealership/
counts:
  declared: 16
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://autosoftdms.com/meet-connect-partners/
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
  source: https://autosoftdms.com/meet-connect-partners/
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
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id003
      status: unchecked
    slug: auction123
    status: profiled
    tags: &id004
    - Automotive
    - Company
    - Dealer Solutions
    - Inventory
    url: /providers/auction123/
  layer: domain
  name: Auction123
  provider: auction123
  says: lists Auction123 as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
  source: https://autosoftdms.com/meet-connect-partners/
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
    mcp: &id007
      status: unchecked
    slug: cudl
    status: profiled
    tags: &id008
    - Auto Finance
    - Company
    - Fintech
    - Lending
    url: /providers/cudl/
  layer: domain
  name: CUDL
  provider: cudl
  says: lists CUDL as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id009
      status: unchecked
    slug: dealermine
    status: profiled
    tags: &id010
    - Automotive
    - B2B
    - Inventory
    - Marketplace
    url: /providers/dealermine/
  layer: common
  name: DealerMine
  provider: dealermine
  says: lists DealerMine as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    agent_readiness: 19.4
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id011
      status: unknown
    slug: dealersocket
    status: profiled
    tags: &id012
    - Automotive
    - CRM
    - DMS
    - Dealership
    url: /providers/dealersocket/
  layer: common
  name: DealerSocket
  provider: dealersocket
  says: lists DealerSocket as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id013
      status: unchecked
    slug: dynatron
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Automotive
    - Data Analytics
    - Fixed Ops
    url: /providers/dynatron/
  layer: domain
  name: Dynatron (KEEPS)
  provider: dynatron
  says: lists Dynatron (KEEPS) as an integration
  source: https://autosoftdms.com/meet-connect-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.30
    key: market-intelligence-management
    name: Market Intelligence Management
    url: /capabilities/market-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id015
      status: unchecked
    slug: jd-power
    status: profiled
    tags: &id016
    - Company
    url: /providers/jd-power/
  layer: domain
  name: J.D. Power
  provider: jd-power
  says: lists J.D. Power as an integration
  source: https://autosoftdms.com/meet-connect-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1060
    key: spare-parts-aftermarket-management
    name: Spare Parts & Aftermarket Management
    url: /capabilities/spare-parts-aftermarket-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id017
      status: unchecked
    slug: oeconnection
    status: profiled
    tags: &id018
    - Automotive
    - Dealership
    - Parts Management
    - Software
    url: /providers/oeconnection/
  layer: domain
  name: OEConnection
  provider: oeconnection
  says: lists OEConnection as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id019
      status: unchecked
    slug: recon-advisor
    status: profiled
    tags: &id020
    - Automotive
    - DealerTech
    - Software-as-a-Service
    - VehicleReconditioning
    url: /providers/recon-advisor/
  layer: domain
  name: Recon Advisor
  provider: recon-advisor
  says: lists Recon Advisor as an integration
  source: https://autosoftdms.com/meet-connect-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3460.30
    key: in-vehicle-app-and-subscription-management
    name: In-Vehicle App and Subscription Management
    url: /capabilities/in-vehicle-app-and-subscription-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 21.4
    mcp: &id021
      status: unknown
    slug: sirius-xm
    status: profiled
    tags: &id022
    - Audio
    - Music
    - Radio
    - Streaming
    url: /providers/sirius-xm/
  layer: domain
  name: SiriusXM
  provider: sirius-xm
  says: lists SiriusXM as an integration
  source: https://autosoftdms.com/meet-connect-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1060
    key: spare-parts-aftermarket-management
    name: Spare Parts & Aftermarket Management
    url: /capabilities/spare-parts-aftermarket-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: partseye
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: SmartCo PartsEye
  provider: partseye
  says: lists SmartCo PartsEye as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    kin_score: 7.6
    mcp: &id025
      status: unknown
    slug: stoneeagle-f-and-i
    status: profiled
    tags: &id026
    - Automotive
    - Company
    - Dealership
    - Finance and Insurance
    url: /providers/stoneeagle-f-and-i/
  layer: domain
  name: StoneEagle F&I
  provider: stoneeagle-f-and-i
  says: lists StoneEagle F&I as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    mcp: &id027
      status: unchecked
    slug: vinsolutions
    status: profiled
    tags: &id028
    - Automotive
    - CRM
    - Dealership
    - Software
    url: /providers/vinsolutions/
  layer: common
  name: VinSolutions
  provider: vinsolutions
  says: lists VinSolutions as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id029
      status: unchecked
    slug: vision-menu
    status: profiled
    tags: &id030
    - Automotive
    - Company
    - Dealership
    - DigitalMenu
    url: /providers/vision-menu/
  layer: domain
  name: Vision Menu
  provider: vision-menu
  says: lists Vision Menu as an integration
  source: https://autosoftdms.com/meet-connect-partners/
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
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id031
      status: unknown
    slug: xtime
    status: profiled
    tags: &id032
    - Automotive
    - Company
    - Dealership
    - Vertical Software
    url: /providers/xtime/
  layer: domain
  name: Xtime
  provider: xtime
  says: lists Xtime as an integration
  source: https://autosoftdms.com/meet-connect-partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/autosoft-dms/
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
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id003
  name: Auction123
  slug: auction123
  status: profiled
  tags: *id004
  url: /providers/auction123/
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
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id007
  name: CUDL
  slug: cudl
  status: profiled
  tags: *id008
  url: /providers/cudl/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id009
  name: DealerMine
  slug: dealermine
  status: profiled
  tags: *id010
  url: /providers/dealermine/
- agent_band: agent-aware
  agent_readiness: 19.4
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id011
  name: DealerSocket
  slug: dealersocket
  status: profiled
  tags: *id012
  url: /providers/dealersocket/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id013
  name: Dynatron (KEEPS)
  slug: dynatron
  status: profiled
  tags: *id014
  url: /providers/dynatron/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id015
  name: J.D. Power
  slug: jd-power
  status: profiled
  tags: *id016
  url: /providers/jd-power/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id017
  name: OEConnection
  slug: oeconnection
  status: profiled
  tags: *id018
  url: /providers/oeconnection/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id019
  name: Recon Advisor
  slug: recon-advisor
  status: profiled
  tags: *id020
  url: /providers/recon-advisor/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id021
  name: SiriusXM
  slug: sirius-xm
  status: profiled
  tags: *id022
  url: /providers/sirius-xm/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: SmartCo PartsEye
  slug: partseye
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id025
  name: StoneEagle F&I
  slug: stoneeagle-f-and-i
  status: profiled
  tags: *id026
  url: /providers/stoneeagle-f-and-i/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id027
  name: VinSolutions
  slug: vinsolutions
  status: profiled
  tags: *id028
  url: /providers/vinsolutions/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id029
  name: Vision Menu
  slug: vision-menu
  status: profiled
  tags: *id030
  url: /providers/vision-menu/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id031
  name: Xtime
  slug: xtime
  status: profiled
  tags: *id032
  url: /providers/xtime/
siblings:
- name: AutoHub
  rows: 17
  url: /applications/auto-dealership/autohub/
- name: AutoRaptor
  rows: 3
  url: /applications/auto-dealership/autoraptor/
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
title: 'Autosoft DMS: Auto Dealership Management reference app'
---
