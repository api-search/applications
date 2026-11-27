---
app: Cin7
app_slug: cin7
app_url: https://www.cin7.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-410.60
  key: channel-sales-management
  layer: domain
  name: Channel Sales Management
  providers:
  - Amazon
  - BigCommerce
  - Brightpearl
  - eBay
  - Shopify
  - Walmart
  - WooCommerce
  url: /capabilities/channel-sales-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Oracle NetSuite
  - QuickBooks
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Avalara
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - EasyPost
  - ShipStation
  - Starshipit
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: inventory-warehouse
  name: Inventory & Warehouse Management
  url: /applications/inventory-warehouse/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.cin7.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon
  provider: amazon
  says: lists Amazon as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.7
    band: exemplar
    in_catalog: true
    kin_score: 69.3
    mcp: &id003
      source: https://github.com/avadev/mcp
      status: verified
    slug: avalara
    status: profiled
    tags: &id004
    - Accounting
    - Avalara
    - Tax
    url: /providers/avalara/
  layer: domain
  name: Avalara
  provider: avalara
  says: lists Avalara as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id005
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id006
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: emerging
    in_catalog: true
    kin_score: 21.7
    mcp: &id007
      status: none
    slug: brightpearl
    status: profiled
    tags: &id008
    - Company
    - E-Commerce
    - Retail
    - Software-as-a-Service
    url: /providers/brightpearl/
  layer: domain
  name: Brightpearl
  provider: brightpearl
  says: lists Brightpearl as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id009
      status: none
    slug: easypost
    status: profiled
    tags: &id010
    - Logistics
    - Multi-Carrier
    - Shipping
    - Tracking
    url: /providers/easypost/
  layer: domain
  name: EasyPost
  provider: easypost
  says: lists EasyPost as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id011
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id012
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id013
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id014
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.cin7.com/integrations/
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
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id015
      status: none
    slug: netsuite
    status: profiled
    tags: &id016
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://www.cin7.com/integrations/
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
    mcp: &id017
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id018
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id019
      status: none
    slug: shipstation
    status: profiled
    tags: &id020
    - E-Commerce
    - Labels
    - Logistics
    - ShipStation
    url: /providers/shipstation/
  layer: domain
  name: ShipStation
  provider: shipstation
  says: lists ShipStation as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id021
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id022
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id023
      status: unknown
    slug: starshipit
    status: profiled
    tags: &id024
    - Automation
    - E-Commerce
    - Fulfilment
    - Shipping
    url: /providers/starshipit/
  layer: domain
  name: Starshipit
  provider: starshipit
  says: lists Starshipit as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 63.7
    mcp: &id025
      status: none
    slug: walmart
    status: profiled
    tags: &id026
    - Commerce
    - Fortune 100
    - Retail
    - Walmart
    url: /providers/walmart/
  layer: domain
  name: Walmart
  provider: walmart
  says: lists Walmart as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id027
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id028
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.cin7.com/integrations/
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
    mcp: &id029
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id030
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.cin7.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/inventory-warehouse/cin7/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id001
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id003
  name: Avalara
  slug: avalara
  status: profiled
  tags: *id004
  url: /providers/avalara/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id005
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id006
  url: /providers/bigcommerce/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: emerging
  in_catalog: true
  kin_score: 21.7
  mcp: *id007
  name: Brightpearl
  slug: brightpearl
  status: profiled
  tags: *id008
  url: /providers/brightpearl/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id009
  name: EasyPost
  slug: easypost
  status: profiled
  tags: *id010
  url: /providers/easypost/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id011
  name: eBay
  slug: ebay
  status: profiled
  tags: *id012
  url: /providers/ebay/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id013
  name: Make
  slug: make
  status: profiled
  tags: *id014
  url: /providers/make/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id015
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id016
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id017
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id018
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 45.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id019
  name: ShipStation
  slug: shipstation
  status: profiled
  tags: *id020
  url: /providers/shipstation/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id021
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id022
  url: /providers/shopify/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id023
  name: Starshipit
  slug: starshipit
  status: profiled
  tags: *id024
  url: /providers/starshipit/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 63.7
  mcp: *id025
  name: Walmart
  slug: walmart
  status: profiled
  tags: *id026
  url: /providers/walmart/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id027
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id028
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id029
  name: Xero
  slug: xero
  status: profiled
  tags: *id030
  url: /providers/xero/
siblings:
- name: inFlow Inventory
  rows: 24
  url: /applications/inventory-warehouse/inflow-inventory/
- name: InvenTree
  rows: 8
  url: /applications/inventory-warehouse/inventree/
- name: Part-DB
  rows: 20
  url: /applications/inventory-warehouse/part-db/
- name: Shelf
  rows: 5
  url: /applications/inventory-warehouse/shelf/
- name: Snipe-IT
  rows: 5
  url: /applications/inventory-warehouse/snipe-it/
- name: Sortly
  rows: 3
  url: /applications/inventory-warehouse/sortly/
- name: Zoho Inventory
  rows: 0
  url: /applications/inventory-warehouse/zoho-inventory/
sitemap: true
title: 'Cin7: Inventory & Warehouse Management reference app'
---
