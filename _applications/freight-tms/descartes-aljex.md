---
app: Descartes Aljex
app_slug: descartes-aljex
app_url: https://www.aljex.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-961
  key: AE-961
  layer: domain
  name: Carrier Vetting & Fraud Monitoring
  providers:
  - Highway
  url: /capabilities/carrier-vetting-fraud-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2530.20
  key: freight-audit-and-payment-management
  layer: domain
  name: Freight Audit and Payment Management
  providers:
  - Breakthrough Fuel
  - Denim
  - EpayManager
  - HaulPay
  url: /capabilities/freight-audit-and-payment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2400
  key: freight-capacity-management
  layer: domain
  name: Freight Capacity Management
  providers:
  - 123Loadboard
  - DAT Freight & Analytics
  - Direct Freight
  - FleetWorks
  url: /capabilities/freight-capacity-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2520
  key: freight-rating-tariff-management
  layer: domain
  name: Freight Rating & Tariff Management
  providers:
  - Carrier1
  - FreightWaves
  - Logistical Labs
  url: /capabilities/freight-rating-tariff-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510
  key: shipment-visibility-tracking-management
  layer: domain
  name: Shipment Visibility & Tracking Management
  providers:
  - Descartes Systems Group
  url: /capabilities/shipment-visibility-tracking-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.20
  key: accounts-payable-management
  layer: common
  name: Accounts Payable Management
  providers:
  - BILL
  url: /capabilities/accounts-payable-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-919
  key: AE-919
  layer: common
  name: B2B EDI & Trading-Partner Networks
  providers:
  - Kleinschmidt
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-940
  key: AE-940
  layer: common
  name: Fleet Fuel Cards & Fuel Transaction Data
  providers:
  - Corpay
  - WEX
  url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Microsoft Dynamics GP
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.40
  key: tax-reporting-compliance
  layer: common
  name: Tax Reporting & Compliance
  providers:
  - 1099 Pro
  url: /capabilities/tax-reporting-compliance/
  via_parent: null
category:
  id: freight-tms
  name: Freight & Transportation Management
  url: /applications/freight-tms/
counts:
  declared: 19
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.aljex.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-220.40
    key: tax-reporting-compliance
    name: Tax Reporting & Compliance
    url: /capabilities/tax-reporting-compliance/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id001
      status: unchecked
    slug: 1099-pro
    status: profiled
    tags: &id002
    - Compliance
    - Efiling
    - Software-as-a-Service
    - Tax Software
    url: /providers/1099-pro/
  layer: common
  name: 1099 Pro
  provider: 1099-pro
  says: lists 1099 Pro as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id003
      status: unchecked
    slug: 123loadboard
    status: profiled
    tags: &id004
    - Freight
    - Load Board
    - Logistics
    - Marketplace
    url: /providers/123loadboard/
  layer: domain
  name: 123Loadboard
  provider: 123loadboard
  says: lists 123Loadboard as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.20
    key: accounts-payable-management
    name: Accounts Payable Management
    url: /capabilities/accounts-payable-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 51.7
    mcp: &id005
      source: https://developer.bill.com/docs/bill-mcp-server
      status: verified
    slug: bill
    status: profiled
    tags: &id006
    - Accounts Payable
    - Accounts Receivable
    - Expense Management
    - Spend Management
    url: /providers/bill/
  layer: common
  name: BILL
  provider: bill
  says: lists BILL as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2530.20
    key: freight-audit-and-payment-management
    name: Freight Audit and Payment Management
    url: /capabilities/freight-audit-and-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.9
    mcp: &id007
      status: unchecked
    slug: breakthrough-fuel
    status: profiled
    tags: &id008
    - Company
    - Fuel Management
    - Logistics
    - Transportation
    url: /providers/breakthrough-fuel/
  layer: domain
  name: Breakthrough Fuel
  provider: breakthrough-fuel
  says: lists Breakthrough Fuel as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2520
    key: freight-rating-tariff-management
    name: Freight Rating & Tariff Management
    url: /capabilities/freight-rating-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id009
      status: unchecked
    slug: carrier1
    status: profiled
    tags: &id010
    - Company
    - Freight
    - Logistics
    - Platform
    url: /providers/carrier1/
  layer: domain
  name: Carrier1
  provider: carrier1
  says: lists Carrier1 as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.1
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id011
      status: unknown
    slug: corpay
    status: profiled
    tags: &id012
    - Accounts Payable
    - Corporate Payments
    - Cross-Border Payments
    - Payments
    url: /providers/corpay/
  layer: common
  name: Corpay
  provider: corpay
  says: lists Corpay as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id013
      source: https://developer.dat.com/mcp
      status: verified
    slug: dat-freight
    status: profiled
    tags: &id014
    - Freight
    - Load Board
    - Logistics
    - Trucking
    url: /providers/dat-freight/
  layer: domain
  name: DAT Freight & Analytics
  provider: dat-freight
  says: lists DAT Freight & Analytics as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2530.20
    key: freight-audit-and-payment-management
    name: Freight Audit and Payment Management
    url: /capabilities/freight-audit-and-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id015
      status: unknown
    slug: denim
    status: profiled
    tags: &id016
    - Company
    - Factoring
    - Freight
    - Payments
    url: /providers/denim/
  layer: domain
  name: Denim
  provider: denim
  says: lists Denim as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2510
    key: shipment-visibility-tracking-management
    name: Shipment Visibility & Tracking Management
    url: /capabilities/shipment-visibility-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id017
      status: unknown
    slug: descartes
    status: profiled
    tags: &id018
    - Freight Visibility
    - Logistics
    - Shipment Tracking
    - Supply Chain
    url: /providers/descartes/
  layer: domain
  name: Descartes Systems Group
  provider: descartes
  says: lists Descartes Systems Group as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id019
      status: unchecked
    slug: direct-freight
    status: profiled
    tags: &id020
    - Carrier
    - Freight Brokers
    - Load Board
    - Shippers
    url: /providers/direct-freight/
  layer: domain
  name: Direct Freight
  provider: direct-freight
  says: lists Direct Freight as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2530.20
    key: freight-audit-and-payment-management
    name: Freight Audit and Payment Management
    url: /capabilities/freight-audit-and-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id021
      status: unchecked
    slug: epaymanager
    status: profiled
    tags: &id022
    - Automation
    - Finance
    - Logistics
    - Payments
    url: /providers/epaymanager/
  layer: domain
  name: EpayManager
  provider: epaymanager
  says: lists EpayManager as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 12.9
    mcp: &id023
      status: unchecked
    slug: fleetworks
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Company
    - Freight
    - Logistics
    url: /providers/fleetworks/
  layer: domain
  name: FleetWorks
  provider: fleetworks
  says: lists FleetWorks as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2520
    key: freight-rating-tariff-management
    name: Freight Rating & Tariff Management
    url: /capabilities/freight-rating-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: freightwaves
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: FreightWaves
  provider: freightwaves
  says: lists FreightWaves as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2530.20
    key: freight-audit-and-payment-management
    name: Freight Audit and Payment Management
    url: /capabilities/freight-audit-and-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id027
      status: unchecked
    slug: haulpay
    status: profiled
    tags: &id028
    - Company
    - Finance
    - Freight
    - Payments
    url: /providers/haulpay/
  layer: domain
  name: HaulPay
  provider: haulpay
  says: lists HaulPay as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-961
    key: AE-961
    name: Carrier Vetting & Fraud Monitoring
    url: /capabilities/carrier-vetting-fraud-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: highway
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: Highway
  provider: highway
  says: lists Highway as an integration
  source: https://www.aljex.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id031
      status: unchecked
    slug: kleinschmidt
    status: profiled
    tags: &id032
    - Automation
    - Company
    - Control Systems
    - Industrial
    url: /providers/kleinschmidt/
  layer: common
  name: Kleinschmidt
  provider: kleinschmidt
  says: lists Kleinschmidt as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2520
    key: freight-rating-tariff-management
    name: Freight Rating & Tariff Management
    url: /capabilities/freight-rating-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id033
      status: unchecked
    slug: logistical-labs
    status: queued for profiling
    tags: &id034 []
    url: null
  layer: domain
  name: Logistical Labs
  provider: logistical-labs
  says: lists Logistical Labs as an integration
  source: https://www.aljex.com/integrations/
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id035
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id036
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: common
  name: Microsoft Dynamics GP
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics GP as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id037
      status: none
    slug: wex
    status: profiled
    tags: &id038 []
    url: /providers/wex/
  layer: common
  name: WEX
  provider: wex
  says: lists WEX as an integration
  source: https://www.aljex.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/freight-tms/descartes-aljex/
providers:
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id001
  name: 1099 Pro
  slug: 1099-pro
  status: profiled
  tags: *id002
  url: /providers/1099-pro/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id003
  name: 123Loadboard
  slug: 123loadboard
  status: profiled
  tags: *id004
  url: /providers/123loadboard/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id005
  name: BILL
  slug: bill
  status: profiled
  tags: *id006
  url: /providers/bill/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.9
  mcp: *id007
  name: Breakthrough Fuel
  slug: breakthrough-fuel
  status: profiled
  tags: *id008
  url: /providers/breakthrough-fuel/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id009
  name: Carrier1
  slug: carrier1
  status: profiled
  tags: *id010
  url: /providers/carrier1/
- agent_band: human-only
  agent_readiness: 2.1
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id011
  name: Corpay
  slug: corpay
  status: profiled
  tags: *id012
  url: /providers/corpay/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id013
  name: DAT Freight & Analytics
  slug: dat-freight
  status: profiled
  tags: *id014
  url: /providers/dat-freight/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id015
  name: Denim
  slug: denim
  status: profiled
  tags: *id016
  url: /providers/denim/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id017
  name: Descartes Systems Group
  slug: descartes
  status: profiled
  tags: *id018
  url: /providers/descartes/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id019
  name: Direct Freight
  slug: direct-freight
  status: profiled
  tags: *id020
  url: /providers/direct-freight/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id021
  name: EpayManager
  slug: epaymanager
  status: profiled
  tags: *id022
  url: /providers/epaymanager/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 12.9
  mcp: *id023
  name: FleetWorks
  slug: fleetworks
  status: profiled
  tags: *id024
  url: /providers/fleetworks/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: FreightWaves
  slug: freightwaves
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id027
  name: HaulPay
  slug: haulpay
  status: profiled
  tags: *id028
  url: /providers/haulpay/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: Highway
  slug: highway
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id031
  name: Kleinschmidt
  slug: kleinschmidt
  status: profiled
  tags: *id032
  url: /providers/kleinschmidt/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id033
  name: Logistical Labs
  slug: logistical-labs
  status: queued for profiling
  tags: *id034
  url: null
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id035
  name: Microsoft Dynamics GP
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id036
  url: /providers/microsoft-dynamics-365/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id037
  name: WEX
  slug: wex
  status: profiled
  tags: *id038
  url: /providers/wex/
siblings:
- name: 3G TMS
  rows: 4
  url: /applications/freight-tms/3g-tms/
- name: Fleetbase
  rows: 16
  url: /applications/freight-tms/fleetbase/
- name: Revenova TMS
  rows: 5
  url: /applications/freight-tms/revenova-tms/
- name: Rose Rocket
  rows: 28
  url: /applications/freight-tms/rose-rocket/
sitemap: true
title: 'Descartes Aljex: Freight & Transportation Management reference app'
---
