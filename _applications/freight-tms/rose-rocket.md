---
app: Rose Rocket
app_slug: rose-rocket
app_url: https://www.roserocket.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-961
  key: AE-961
  layer: domain
  name: Carrier Vetting & Fraud Monitoring
  providers:
  - Highway
  - RMIS
  url: /capabilities/carrier-vetting-fraud-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2480.20
  key: customs-declaration-management
  layer: domain
  name: Customs Declaration Management
  providers:
  - BorderConnect
  url: /capabilities/customs-declaration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Geotab
  - Terminal (withterminal.com)
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2530.20
  key: freight-audit-and-payment-management
  layer: domain
  name: Freight Audit and Payment Management
  providers:
  - EpayManager
  - TriumphPay
  url: /capabilities/freight-audit-and-payment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2400
  key: freight-capacity-management
  layer: domain
  name: Freight Capacity Management
  providers:
  - DAT Freight & Analytics
  - Truckstop
  url: /capabilities/freight-capacity-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2520
  key: freight-rating-tariff-management
  layer: domain
  name: Freight Rating & Tariff Management
  providers:
  - SMC3
  url: /capabilities/freight-rating-tariff-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510
  key: shipment-visibility-tracking-management
  layer: domain
  name: Shipment Visibility & Tracking Management
  providers:
  - Chain.io
  - Descartes Systems Group
  - FourKites
  - Trucker Tools
  url: /capabilities/shipment-visibility-tracking-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2460
  key: warehousing-operations-management
  layer: domain
  name: Warehousing Operations Management
  providers:
  - CartonCloud
  url: /capabilities/warehousing-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Google BigQuery
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-919
  key: AE-919
  layer: common
  name: B2B EDI & Trading-Partner Networks
  providers:
  - Bitfreighter
  - SPS Commerce
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-940
  key: AE-940
  layer: common
  name: Fleet Fuel Cards & Fuel Transaction Data
  providers:
  - Corpay
  url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Microsoft Dynamics 365 Business Central
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Rainforest
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.30.10
  key: AE-120.30.10
  layer: common
  name: Turn-by-Turn Directions
  providers:
  - Google Maps Platform
  - Trimble
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
category:
  id: freight-tms
  name: Freight & Transportation Management
  url: /applications/freight-tms/
counts:
  declared: 28
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.roserocket.com/integrations
integrations:
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
    agent_readiness: 44.0
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id001
      status: unchecked
    slug: bitfreighter
    status: profiled
    tags: &id002
    - Company
    - EDI
    - Freight
    - Logistics
    url: /providers/bitfreighter/
  layer: common
  name: Bitfreighter
  provider: bitfreighter
  says: lists Bitfreighter as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2480.20
    key: customs-declaration-management
    name: Customs Declaration Management
    url: /capabilities/customs-declaration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.7
    mcp: &id003
      status: unchecked
    slug: borderconnect
    status: profiled
    tags: &id004
    - Company
    url: /providers/borderconnect/
  layer: domain
  name: BorderConnect
  provider: borderconnect
  says: lists BorderConnect as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2460
    key: warehousing-operations-management
    name: Warehousing Operations Management
    url: /capabilities/warehousing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id005
      status: unchecked
    slug: cartoncloud
    status: profiled
    tags: &id006
    - Logistics
    - Software
    - Transportation
    - Warehouse Management
    url: /providers/cartoncloud/
  layer: domain
  name: CartonCloud
  provider: cartoncloud
  says: lists CartonCloud as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: chain-io
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Chain.io
  provider: chain-io
  says: lists Chain.io as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id009
      status: unknown
    slug: corpay
    status: profiled
    tags: &id010
    - Accounts Payable
    - Corporate Payments
    - Cross-Border Payments
    - Payments
    url: /providers/corpay/
  layer: common
  name: Corpay
  provider: corpay
  says: lists Corpay as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id011
      source: https://developer.dat.com/mcp
      status: verified
    slug: dat-freight
    status: profiled
    tags: &id012
    - Freight
    - Load Board
    - Logistics
    - Trucking
    url: /providers/dat-freight/
  layer: domain
  name: DAT Freight & Analytics
  provider: dat-freight
  says: lists DAT Freight & Analytics as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id013
      status: unknown
    slug: descartes
    status: profiled
    tags: &id014
    - Freight Visibility
    - Logistics
    - Shipment Tracking
    - Supply Chain
    url: /providers/descartes/
  layer: domain
  name: Descartes Systems Group
  provider: descartes
  says: lists Descartes Systems Group as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id015
      status: unchecked
    slug: epaymanager
    status: profiled
    tags: &id016
    - Automation
    - Finance
    - Logistics
    - Payments
    url: /providers/epaymanager/
  layer: domain
  name: EpayManager
  provider: epaymanager
  says: lists EpayManager as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id017
      source: https://www.fourkites.ai/engineering-blog/mcp-gateway
      status: documented
    slug: fourkites
    status: profiled
    tags: &id018
    - Freight
    - Logistics
    - Supply Chain Visibility
    - Tracking
    url: /providers/fourkites/
  layer: domain
  name: FourKites
  provider: fourkites
  says: lists FourKites as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 31.4
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id019
      source: https://mcp.geotab.com/mygeotab
      status: verified
    slug: geotab
    status: profiled
    tags: &id020
    - ELD Compliance
    - Fleet Management
    - Telematics
    - Vehicle Tracking
    url: /providers/geotab/
  layer: domain
  name: Geotab
  provider: geotab
  says: lists Geotab as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id021
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id022
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id023
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id024
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: common
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id025
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id026
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: lists Google Maps Platform as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id027
      status: unchecked
    slug: highway
    status: queued for profiling
    tags: &id028 []
    url: null
  layer: domain
  name: Highway
  provider: highway
  says: lists Highway as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id029
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id030
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.roserocket.com/integrations
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id031
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id032
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: common
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id033
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id034
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: agent-native
    agent_readiness: 41.8
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id035
      status: unknown
    slug: rainforest
    status: profiled
    tags: &id036
    - Company
    - Embedded Payments
    - Payment Facilitator
    - Payments
    url: /providers/rainforest/
  layer: common
  name: Rainforest
  provider: rainforest
  says: lists Rainforest as an integration
  source: https://www.roserocket.com/integrations
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
    mcp: &id037
      status: unchecked
    slug: rmis
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: domain
  name: RMIS
  provider: rmis
  says: lists RMIS as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id039
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id040
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 17.8
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id041
      status: unchecked
    slug: smc3
    status: profiled
    tags: &id042
    - Company
    - Logistics
    - Pricing
    - Transportation
    url: /providers/smc3/
  layer: domain
  name: SMC3
  provider: smc3
  says: lists SMC3 as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id043
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id044
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: common
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
  source: https://www.roserocket.com/integrations
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
    agent_readiness: 40.4
    band: strong
    in_catalog: true
    kin_score: 59.5
    mcp: &id045
      status: none
    slug: sps-commerce
    status: profiled
    tags: &id046
    - Company
    - EDI
    - Retail
    - Supply Chain
    url: /providers/sps-commerce/
  layer: common
  name: SPS Commerce
  provider: sps-commerce
  says: lists SPS Commerce as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 47.0
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id047
      status: unchecked
    slug: terminal-telematics
    status: profiled
    tags: &id048
    - Company
    - Data
    - Fleet Management
    - Telematics
    url: /providers/terminal-telematics/
  layer: domain
  name: Terminal (withterminal.com)
  provider: terminal-telematics
  says: lists Terminal (withterminal.com) as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id049
      status: none
    slug: trimble
    status: profiled
    tags: &id050
    - Construction
    - GPS
    - Geospatial
    - Transportation
    url: /providers/trimble/
  layer: common
  name: Trimble
  provider: trimble
  says: lists Trimble as an integration
  source: https://www.roserocket.com/integrations
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
    kin_score: 12.8
    mcp: &id051
      status: unchecked
    slug: triumphpay
    status: profiled
    tags: &id052
    - Carrier Solutions
    - Equipment Financing
    - Factoring
    - Payments
    url: /providers/triumphpay/
  layer: domain
  name: TriumphPay
  provider: triumphpay
  says: lists TriumphPay as an integration
  source: https://www.roserocket.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 46.7
    band: emerging
    in_catalog: true
    kin_score: 17.1
    mcp: &id053
      status: unchecked
    slug: trucker-tools
    status: profiled
    tags: &id054
    - Company
    - Freight
    - Load Tracking
    - Logistics
    url: /providers/trucker-tools/
  layer: domain
  name: Trucker Tools
  provider: trucker-tools
  says: lists Trucker Tools as an integration
  source: https://www.roserocket.com/integrations
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
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 17.7
    mcp: &id055
      source: https://mcp.truckstop.com/mcp
      status: documented
    slug: truckstop
    status: profiled
    tags: &id056
    - Freight
    - Load Board
    - Logistics
    - Trucking
    url: /providers/truckstop/
  layer: domain
  name: Truckstop
  provider: truckstop
  says: lists Truckstop as an integration
  source: https://www.roserocket.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/freight-tms/rose-rocket/
providers:
- agent_band: agent-ready
  agent_readiness: 44.0
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id001
  name: Bitfreighter
  slug: bitfreighter
  status: profiled
  tags: *id002
  url: /providers/bitfreighter/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id003
  name: BorderConnect
  slug: borderconnect
  status: profiled
  tags: *id004
  url: /providers/borderconnect/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id005
  name: CartonCloud
  slug: cartoncloud
  status: profiled
  tags: *id006
  url: /providers/cartoncloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Chain.io
  slug: chain-io
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: human-only
  agent_readiness: 2.1
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id009
  name: Corpay
  slug: corpay
  status: profiled
  tags: *id010
  url: /providers/corpay/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id011
  name: DAT Freight & Analytics
  slug: dat-freight
  status: profiled
  tags: *id012
  url: /providers/dat-freight/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id013
  name: Descartes Systems Group
  slug: descartes
  status: profiled
  tags: *id014
  url: /providers/descartes/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id015
  name: EpayManager
  slug: epaymanager
  status: profiled
  tags: *id016
  url: /providers/epaymanager/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id017
  name: FourKites
  slug: fourkites
  status: profiled
  tags: *id018
  url: /providers/fourkites/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id019
  name: Geotab
  slug: geotab
  status: profiled
  tags: *id020
  url: /providers/geotab/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id021
  name: GitHub
  slug: github
  status: profiled
  tags: *id022
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id023
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id024
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id025
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id026
  url: /providers/google-maps/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id027
  name: Highway
  slug: highway
  status: queued for profiling
  tags: *id028
  url: null
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id029
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id030
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id031
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id032
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id033
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id034
  url: /providers/quickbooks/
- agent_band: agent-native
  agent_readiness: 41.8
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id035
  name: Rainforest
  slug: rainforest
  status: profiled
  tags: *id036
  url: /providers/rainforest/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: RMIS
  slug: rmis
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id039
  name: Slack
  slug: slack
  status: profiled
  tags: *id040
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id041
  name: SMC3
  slug: smc3
  status: profiled
  tags: *id042
  url: /providers/smc3/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id043
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id044
  url: /providers/snowflake/
- agent_band: agent-ready
  agent_readiness: 40.4
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id045
  name: SPS Commerce
  slug: sps-commerce
  status: profiled
  tags: *id046
  url: /providers/sps-commerce/
- agent_band: agent-ready
  agent_readiness: 47.0
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id047
  name: Terminal (withterminal.com)
  slug: terminal-telematics
  status: profiled
  tags: *id048
  url: /providers/terminal-telematics/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id049
  name: Trimble
  slug: trimble
  status: profiled
  tags: *id050
  url: /providers/trimble/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id051
  name: TriumphPay
  slug: triumphpay
  status: profiled
  tags: *id052
  url: /providers/triumphpay/
- agent_band: agent-ready
  agent_readiness: 46.7
  band: emerging
  in_catalog: true
  kin_score: 17.1
  mcp: *id053
  name: Trucker Tools
  slug: trucker-tools
  status: profiled
  tags: *id054
  url: /providers/trucker-tools/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 17.7
  mcp: *id055
  name: Truckstop
  slug: truckstop
  status: profiled
  tags: *id056
  url: /providers/truckstop/
siblings:
- name: 3G TMS
  rows: 4
  url: /applications/freight-tms/3g-tms/
- name: Descartes Aljex
  rows: 19
  url: /applications/freight-tms/descartes-aljex/
- name: Fleetbase
  rows: 16
  url: /applications/freight-tms/fleetbase/
- name: Revenova TMS
  rows: 5
  url: /applications/freight-tms/revenova-tms/
sitemap: true
title: 'Rose Rocket: Freight & Transportation Management reference app'
---
