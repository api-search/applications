---
app: Katana
app_slug: katana
app_url: https://katanamrp.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-410.60
  key: channel-sales-management
  layer: domain
  name: Channel Sales Management
  providers:
  - Amazon
  - eBay
  url: /capabilities/channel-sales-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Pipedrive
  - Prospect CRM
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks Online
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Shopify
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - Mintsoft
  - ShipBob
  - ShipHero
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510.20
  key: shipment-tracking-management
  layer: domain
  name: Shipment Tracking Management
  providers:
  - 2Ship
  - Jikko
  - Shippo
  - ShipStation
  url: /capabilities/shipment-tracking-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: erp-operations
  name: ERP & Business Operations
  url: /applications/erp-operations/
counts:
  declared: 19
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://katanamrp.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.8
    band: emerging
    in_catalog: true
    kin_score: 14.6
    mcp: &id001
      status: unknown
    slug: 2ship
    status: profiled
    tags: &id002
    - Company
    - Logistics
    - Shipping
    - Software
    url: /providers/2ship/
  layer: domain
  name: 2Ship
  provider: 2ship
  says: lists 2Ship as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id003
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id004
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon
  provider: amazon
  says: lists Amazon as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.5
    band: exemplar
    in_catalog: true
    kin_score: 70.3
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
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id007
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id008
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id009
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id010
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id011
      status: unknown
    slug: jikko
    status: profiled
    tags: &id012
    - Company
    url: /providers/jikko/
  layer: domain
  name: Jikko
  provider: jikko
  says: lists Jikko as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 23.1
    mcp: &id013
      status: unknown
    slug: mintsoft
    status: profiled
    tags: &id014
    - E-Commerce
    - Logistics
    - Software-as-a-Service
    - Warehouse
    url: /providers/mintsoft/
  layer: domain
  name: Mintsoft
  provider: mintsoft
  says: lists Mintsoft as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 29.3
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id015
      status: none
    slug: pipedrive
    status: profiled
    tags: &id016
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 12.7
    band: emerging
    in_catalog: true
    kin_score: 15.2
    mcp: &id017
      status: unknown
    slug: prospect-crm
    status: profiled
    tags: &id018
    - Company
    url: /providers/prospect-crm/
  layer: domain
  name: Prospect CRM
  provider: prospect-crm
  says: lists Prospect CRM as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id019
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id020
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id021
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id022
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.4
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id023
      source: https://developer.shipbob.com/mcp-server/overview
      status: verified
    slug: shipbob
    status: profiled
    tags: &id024
    - 3PL
    - E-Commerce
    - Fulfillment
    - Logistics
    url: /providers/shipbob/
  layer: domain
  name: ShipBob
  provider: shipbob
  says: lists ShipBob as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id025
      status: none
    slug: shiphero
    status: profiled
    tags: &id026
    - E-Commerce
    - Fulfillment
    - GraphQL
    - Warehouse Management
    url: /providers/shiphero/
  layer: domain
  name: ShipHero
  provider: shiphero
  says: lists ShipHero as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id027
      source: https://github.com/goshippo/ai
      status: verified
    slug: shippo
    status: profiled
    tags: &id028
    - E-Commerce
    - Labels
    - Logistics
    - Returns
    url: /providers/shippo/
  layer: domain
  name: Shippo
  provider: shippo
  says: lists Shippo as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id029
      status: none
    slug: shipstation
    status: profiled
    tags: &id030
    - E-Commerce
    - Labels
    - Logistics
    - ShipStation
    url: /providers/shipstation/
  layer: domain
  name: ShipStation
  provider: shipstation
  says: lists ShipStation as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id031
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id032
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.4
    band: developing
    in_catalog: true
    kin_score: 50.4
    mcp: &id033
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id034
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id035
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id036
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://katanamrp.com/integrations/
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id037
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id038
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: domain
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://katanamrp.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/erp-operations/katana/
providers:
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id001
  name: 2Ship
  slug: 2ship
  status: profiled
  tags: *id002
  url: /providers/2ship/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id003
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id004
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 60.5
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id005
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id006
  url: /providers/bigcommerce/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id007
  name: eBay
  slug: ebay
  status: profiled
  tags: *id008
  url: /providers/ebay/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id009
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id010
  url: /providers/hubspot/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id011
  name: Jikko
  slug: jikko
  status: profiled
  tags: *id012
  url: /providers/jikko/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 23.1
  mcp: *id013
  name: Mintsoft
  slug: mintsoft
  status: profiled
  tags: *id014
  url: /providers/mintsoft/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id015
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id016
  url: /providers/pipedrive/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id017
  name: Prospect CRM
  slug: prospect-crm
  status: profiled
  tags: *id018
  url: /providers/prospect-crm/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id019
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id020
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id021
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id022
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 40.4
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id023
  name: ShipBob
  slug: shipbob
  status: profiled
  tags: *id024
  url: /providers/shipbob/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id025
  name: ShipHero
  slug: shiphero
  status: profiled
  tags: *id026
  url: /providers/shiphero/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id027
  name: Shippo
  slug: shippo
  status: profiled
  tags: *id028
  url: /providers/shippo/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id029
  name: ShipStation
  slug: shipstation
  status: profiled
  tags: *id030
  url: /providers/shipstation/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id031
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id032
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id033
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id034
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id035
  name: Xero
  slug: xero
  status: profiled
  tags: *id036
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id037
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id038
  url: /providers/zapier/
siblings:
- name: Dolibarr
  rows: 13
  url: /applications/erp-operations/dolibarr/
- name: ERPNext
  rows: 24
  url: /applications/erp-operations/erpnext/
- name: Fishbowl
  rows: 42
  url: /applications/erp-operations/fishbowl/
- name: Odoo
  rows: 45
  url: /applications/erp-operations/odoo/
- name: Tryton
  rows: 13
  url: /applications/erp-operations/tryton/
sitemap: true
title: 'Katana: ERP & Business Operations reference app'
---
