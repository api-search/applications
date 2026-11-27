---
app: MarketMan
app_slug: marketman
app_url: https://www.marketman.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Tenzo
  - Wenodo
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4070.20
  key: f-b-procurement-inventory
  layer: domain
  name: F&B Procurement & Inventory
  providers:
  - Gordon Food Service
  - Performance Foodservice
  - Shamrock Foods
  - Sysco
  - US Foods
  - WebstaurantStore
  url: /capabilities/f-b-procurement-inventory/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Paperchase
  - QuickBooks
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Aloha (NCR Voyix)
  - Clover
  - Lavu
  - Lightspeed
  - Oracle MICROS
  - Otter
  - Qu POS
  - Redcat
  - Revel Systems
  - Revolut POS
  - Shift4
  - Silverware
  - Square
  - Squirrel Systems
  - SumUp
  - Tabit
  - Toast
  - TouchBistro
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4020
  key: reservation-booking-management
  layer: domain
  name: Reservation & Booking Management
  providers:
  - Zenchef
  url: /capabilities/reservation-booking-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2440.20
  key: rostering-and-scheduling-management
  layer: domain
  name: Rostering and Scheduling Management
  providers:
  - Push Operations
  url: /capabilities/rostering-and-scheduling-management/
  via_parent: null
category:
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 31
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.marketman.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id001
      status: none
    slug: ncr
    status: profiled
    tags: &id002
    - Banking
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/ncr/
  layer: domain
  name: Aloha (NCR Voyix)
  provider: ncr
  says: lists Aloha (NCR Voyix) as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 41.3
    mcp: &id003
      status: none
    slug: clover
    status: profiled
    tags: &id004
    - Payments
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/clover/
  layer: domain
  name: Clover
  provider: clover
  says: lists Clover as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 24.6
    mcp: &id005
      status: none
    slug: gordon-food-service
    status: profiled
    tags: &id006
    - B2B
    - Company
    - Food Distribution
    - Logistics
    url: /providers/gordon-food-service/
  layer: domain
  name: Gordon Food Service
  provider: gordon-food-service
  says: lists Gordon Food Service as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: emerging
    in_catalog: true
    kin_score: 18.2
    mcp: &id007
      status: none
    slug: lavu
    status: profiled
    tags: &id008
    - Inventory
    - Payments
    - Point-of-Sale
    - Restaurant
    url: /providers/lavu/
  layer: domain
  name: Lavu
  provider: lavu
  says: lists Lavu as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id009
      status: none
    slug: lightspeed
    status: profiled
    tags: &id010
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id011
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id012
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle MICROS
  provider: oracle
  says: lists Oracle MICROS as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id013
      source: https://help.otter.ai/api/v2/help_center/en-us/articles/35287607569687.json
      status: verified
    slug: otter
    status: profiled
    tags: &id014
    - Delivery
    - Online Ordering
    - Order Management
    - Restaurant
    url: /providers/otter/
  layer: domain
  name: Otter
  provider: otter
  says: lists Otter as an integration
  source: https://www.marketman.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.9
    mcp: &id015
      status: unknown
    slug: paperchase
    status: profiled
    tags: &id016
    - Company
    url: /providers/paperchase/
  layer: domain
  name: Paperchase
  provider: paperchase
  says: lists Paperchase as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id017
      status: unchecked
    slug: performance-food-group
    status: queued for profiling
    tags: &id018 []
    url: null
  layer: domain
  name: Performance Foodservice
  provider: performance-food-group
  says: lists Performance Foodservice as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id019
      status: none
    slug: push-operations
    status: profiled
    tags: &id020
    - Human Resources
    - Payroll
    - Software-as-a-Service
    - Workforce Management
    url: /providers/push-operations/
  layer: domain
  name: Push Operations
  provider: push-operations
  says: lists Push Operations as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: qu
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Qu POS
  provider: qu
  says: lists Qu POS as an integration
  source: https://www.marketman.com/integrations
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
    mcp: &id023
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id024
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id025
      status: unknown
    slug: redcat
    status: profiled
    tags: &id026
    - Hospitality
    - Loyalty
    - Ordering
    - RestaurantTech
    url: /providers/redcat/
  layer: domain
  name: Redcat
  provider: redcat
  says: lists Redcat as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id027
      status: none
    slug: revel-systems
    status: profiled
    tags: &id028
    - Point-of-Sale
    - Restaurant
    - Retail
    - iPad
    url: /providers/revel-systems/
  layer: domain
  name: Revel Systems
  provider: revel-systems
  says: lists Revel Systems as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 50.9
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id029
      status: none
    slug: revolut
    status: profiled
    tags: &id030
    - Banking
    - Company
    - Fintech
    - Payments
    url: /providers/revolut/
  layer: domain
  name: Revolut POS
  provider: revolut
  says: lists Revolut POS as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.7
    mcp: &id031
      status: unknown
    slug: shamrock-foods
    status: profiled
    tags: &id032
    - Company
    - Dairy
    - Distributor
    - Food Service
    url: /providers/shamrock-foods/
  layer: domain
  name: Shamrock Foods
  provider: shamrock-foods
  says: lists Shamrock Foods as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.1
    band: developing
    in_catalog: true
    kin_score: 50.8
    mcp: &id033
      status: none
    slug: shift4
    status: profiled
    tags: &id034
    - Payment Gateway
    - Payment Processing
    - Payments
    - United States
    url: /providers/shift4/
  layer: domain
  name: Shift4
  provider: shift4
  says: lists Shift4 as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id035
      status: unknown
    slug: silverware
    status: profiled
    tags: &id036
    - Hospitality
    - Hotels
    - Point-of-Sale
    - Restaurant
    url: /providers/silverware/
  layer: domain
  name: Silverware
  provider: silverware
  says: lists Silverware as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id037
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id038
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id039
      status: unknown
    slug: squirrel-systems
    status: profiled
    tags: &id040
    - Digital Ordering
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/squirrel-systems/
  layer: domain
  name: Squirrel Systems
  provider: squirrel-systems
  says: lists Squirrel Systems as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.2
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id041
      source: https://github.com/sumup/sumup-mcp
      status: verified
    slug: sumup
    status: profiled
    tags: &id042
    - Card Reader
    - Checkout
    - Payments
    - Point-of-Sale
    url: /providers/sumup/
  layer: domain
  name: SumUp
  provider: sumup
  says: lists SumUp as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id043
      status: unknown
    slug: sysco
    status: profiled
    tags: &id044
    - Food Distribution
    - Food Service
    - Fortune 100
    - Supply Chain
    url: /providers/sysco/
  layer: domain
  name: Sysco
  provider: sysco
  says: lists Sysco as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id045
      status: unknown
    slug: tabit
    status: profiled
    tags: &id046
    - Hospitality
    - Ordering
    - Point-of-Sale
    - Restaurant
    url: /providers/tabit/
  layer: domain
  name: Tabit
  provider: tabit
  says: lists Tabit as an integration
  source: https://www.marketman.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 26.8
    band: thin
    in_catalog: true
    kin_score: 30.0
    mcp: &id047
      status: none
    slug: tenzo
    status: profiled
    tags: &id048
    - Analytics
    - Business Intelligence
    - Company
    - Restaurant
    url: /providers/tenzo/
  layer: domain
  name: Tenzo
  provider: tenzo
  says: lists Tenzo as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id049
      status: none
    slug: toast
    status: profiled
    tags: &id050
    - Food Service
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/toast/
  layer: domain
  name: Toast
  provider: toast
  says: lists Toast as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id051
      status: none
    slug: touchbistro
    status: profiled
    tags: &id052
    - Hospitality
    - Payments
    - Point-of-Sale
    - Restaurant
    url: /providers/touchbistro/
  layer: domain
  name: TouchBistro
  provider: touchbistro
  says: lists TouchBistro as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.1
    mcp: &id053
      status: unknown
    slug: us-foods
    status: profiled
    tags: &id054
    - Distribution
    - Food Service
    - Fortune 500
    - Supply Chain
    url: /providers/us-foods/
  layer: domain
  name: US Foods
  provider: us-foods
  says: lists US Foods as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id055
      status: unknown
    slug: webstaurantstore
    status: profiled
    tags: &id056
    - Company
    - E-Commerce
    - Food Service
    - Restaurant Supplies
    url: /providers/webstaurantstore/
  layer: domain
  name: WebstaurantStore
  provider: webstaurantstore
  says: lists WebstaurantStore as an integration
  source: https://www.marketman.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id057
      status: unknown
    slug: wenodo
    status: profiled
    tags: &id058
    - Accounting
    - Hospitality
    - Payroll
    - Workforce
    url: /providers/wenodo/
  layer: domain
  name: Wenodo
  provider: wenodo
  says: lists Wenodo as an integration
  source: https://www.marketman.com/integrations
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
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id059
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id060
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.marketman.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4020
    key: reservation-booking-management
    name: Reservation & Booking Management
    url: /capabilities/reservation-booking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.8
    mcp: &id061
      status: none
    slug: zenchef
    status: profiled
    tags: &id062
    - Payments
    - Reservations
    - Restaurant
    - Software-as-a-Service
    url: /providers/zenchef/
  layer: domain
  name: Zenchef
  provider: zenchef
  says: lists Zenchef as an integration
  source: https://www.marketman.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hospitality-restaurant-ops/marketman/
providers:
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id001
  name: Aloha (NCR Voyix)
  slug: ncr
  status: profiled
  tags: *id002
  url: /providers/ncr/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 41.3
  mcp: *id003
  name: Clover
  slug: clover
  status: profiled
  tags: *id004
  url: /providers/clover/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id005
  name: Gordon Food Service
  slug: gordon-food-service
  status: profiled
  tags: *id006
  url: /providers/gordon-food-service/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id007
  name: Lavu
  slug: lavu
  status: profiled
  tags: *id008
  url: /providers/lavu/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id009
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id010
  url: /providers/lightspeed/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id011
  name: Oracle MICROS
  slug: oracle
  status: profiled
  tags: *id012
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id013
  name: Otter
  slug: otter
  status: profiled
  tags: *id014
  url: /providers/otter/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.9
  mcp: *id015
  name: Paperchase
  slug: paperchase
  status: profiled
  tags: *id016
  url: /providers/paperchase/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id017
  name: Performance Foodservice
  slug: performance-food-group
  status: queued for profiling
  tags: *id018
  url: null
- agent_band: agent-aware
  agent_readiness: 17.6
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id019
  name: Push Operations
  slug: push-operations
  status: profiled
  tags: *id020
  url: /providers/push-operations/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Qu POS
  slug: qu
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id023
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id024
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id025
  name: Redcat
  slug: redcat
  status: profiled
  tags: *id026
  url: /providers/redcat/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id027
  name: Revel Systems
  slug: revel-systems
  status: profiled
  tags: *id028
  url: /providers/revel-systems/
- agent_band: agent-native
  agent_readiness: 50.9
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id029
  name: Revolut POS
  slug: revolut
  status: profiled
  tags: *id030
  url: /providers/revolut/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id031
  name: Shamrock Foods
  slug: shamrock-foods
  status: profiled
  tags: *id032
  url: /providers/shamrock-foods/
- agent_band: agent-native
  agent_readiness: 54.1
  band: developing
  in_catalog: true
  kin_score: 50.8
  mcp: *id033
  name: Shift4
  slug: shift4
  status: profiled
  tags: *id034
  url: /providers/shift4/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id035
  name: Silverware
  slug: silverware
  status: profiled
  tags: *id036
  url: /providers/silverware/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id037
  name: Square
  slug: square
  status: profiled
  tags: *id038
  url: /providers/square/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id039
  name: Squirrel Systems
  slug: squirrel-systems
  status: profiled
  tags: *id040
  url: /providers/squirrel-systems/
- agent_band: agent-ready
  agent_readiness: 53.2
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id041
  name: SumUp
  slug: sumup
  status: profiled
  tags: *id042
  url: /providers/sumup/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id043
  name: Sysco
  slug: sysco
  status: profiled
  tags: *id044
  url: /providers/sysco/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id045
  name: Tabit
  slug: tabit
  status: profiled
  tags: *id046
  url: /providers/tabit/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: thin
  in_catalog: true
  kin_score: 30.0
  mcp: *id047
  name: Tenzo
  slug: tenzo
  status: profiled
  tags: *id048
  url: /providers/tenzo/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id049
  name: Toast
  slug: toast
  status: profiled
  tags: *id050
  url: /providers/toast/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id051
  name: TouchBistro
  slug: touchbistro
  status: profiled
  tags: *id052
  url: /providers/touchbistro/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.1
  mcp: *id053
  name: US Foods
  slug: us-foods
  status: profiled
  tags: *id054
  url: /providers/us-foods/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id055
  name: WebstaurantStore
  slug: webstaurantstore
  status: profiled
  tags: *id056
  url: /providers/webstaurantstore/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id057
  name: Wenodo
  slug: wenodo
  status: profiled
  tags: *id058
  url: /providers/wenodo/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id059
  name: Xero
  slug: xero
  status: profiled
  tags: *id060
  url: /providers/xero/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.8
  mcp: *id061
  name: Zenchef
  slug: zenchef
  status: profiled
  tags: *id062
  url: /providers/zenchef/
siblings:
- name: 7shifts
  rows: 12
  url: /applications/hospitality-restaurant-ops/7shifts/
- name: apaleo
  rows: 5
  url: /applications/hospitality-restaurant-ops/apaleo/
- name: Cloudbeds
  rows: 3
  url: /applications/hospitality-restaurant-ops/cloudbeds/
- name: Mews
  rows: 11
  url: /applications/hospitality-restaurant-ops/mews/
- name: QloApps
  rows: 3
  url: /applications/hospitality-restaurant-ops/qloapps/
- name: TastyIgniter
  rows: 11
  url: /applications/hospitality-restaurant-ops/tastyigniter/
sitemap: true
title: 'MarketMan: Hotel & Restaurant Operations reference app'
---
