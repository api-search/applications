---
app: inFlow Inventory
app_slug: inflow-inventory
app_url: https://www.inflowinventory.com/
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
  - eBay
  - Etsy
  - Faire
  - Google Shopping
  - Lightspeed Commerce
  - Magento
  - Shopify
  - Square
  - Squarespace
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
  - QuickBooks Online
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - EasyPost
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - DHL
  - FedEx
  - UPS
  - USPS
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Okta
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: inventory-warehouse
  name: Inventory & Warehouse Management
  url: /applications/inventory-warehouse/
counts:
  declared: 24
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.inflowinventory.com/integrations
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
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id003
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id004
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://www.inflowinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 39.5
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id005
      status: none
    slug: dhl
    status: profiled
    tags: &id006
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: lists DHL as an integration
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id007
      status: none
    slug: easypost
    status: profiled
    tags: &id008
    - Logistics
    - Multi-Carrier
    - Shipping
    - Tracking
    url: /providers/easypost/
  layer: domain
  name: EasyPost
  provider: easypost
  says: lists EasyPost as an integration
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id009
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id010
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 28.7
    band: developing
    in_catalog: true
    kin_score: 53.2
    mcp: &id011
      source: https://developers.etsy.com/documentation/mcp_server/devmcpserver
      status: verified
    slug: etsy
    status: profiled
    tags: &id012
    - E-Commerce
    - Handmade
    - Listings
    - Marketplace
    url: /providers/etsy/
  layer: domain
  name: Etsy
  provider: etsy
  says: lists Etsy as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.0
    mcp: &id013
      status: none
    slug: faire
    status: profiled
    tags: &id014
    - E-Commerce
    - Marketplace
    - Retail
    - Wholesale
    url: /providers/faire/
  layer: domain
  name: Faire
  provider: faire
  says: lists Faire as an integration
  source: https://www.inflowinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id015
      status: none
    slug: fedex
    status: profiled
    tags: &id016
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 33.1
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id017
      status: none
    slug: google-shopping
    status: profiled
    tags: &id018
    - E-Commerce
    - Google Shopping
    - Merchant Center
    - Product Listings
    url: /providers/google-shopping/
  layer: domain
  name: Google Shopping
  provider: google-shopping
  says: lists Google Shopping as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id019
      status: none
    slug: lightspeed
    status: profiled
    tags: &id020
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed Commerce
  provider: lightspeed
  says: lists Lightspeed Commerce as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id021
      status: none
    slug: magento
    status: profiled
    tags: &id022
    - Catalog
    - E-Commerce
    - Headless Commerce
    - Magento
    url: /providers/magento/
  layer: domain
  name: Magento
  provider: magento
  says: lists Magento as an integration
  source: https://www.inflowinventory.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id023
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id024
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id025
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id026
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id027
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id028
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id029
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id030
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.inflowinventory.com/integrations
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
  source: https://www.inflowinventory.com/integrations
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
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id033
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id034
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id035
      status: none
    slug: squarespace
    status: profiled
    tags: &id036
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://www.inflowinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id037
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id038
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://www.inflowinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.8
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id039
      status: none
    slug: usps
    status: profiled
    tags: &id040
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: lists USPS as an integration
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id041
      status: none
    slug: walmart
    status: profiled
    tags: &id042
    - Commerce
    - Fortune 100
    - Retail
    - Walmart
    url: /providers/walmart/
  layer: domain
  name: Walmart
  provider: walmart
  says: lists Walmart as an integration
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id043
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id044
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.inflowinventory.com/integrations
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
    mcp: &id045
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id046
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.inflowinventory.com/integrations
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id047
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id048
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.inflowinventory.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/inventory-warehouse/inflow-inventory/
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
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id003
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id004
  url: /providers/bigcommerce/
- agent_band: agent-native
  agent_readiness: 39.5
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id005
  name: DHL
  slug: dhl
  status: profiled
  tags: *id006
  url: /providers/dhl/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id007
  name: EasyPost
  slug: easypost
  status: profiled
  tags: *id008
  url: /providers/easypost/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id009
  name: eBay
  slug: ebay
  status: profiled
  tags: *id010
  url: /providers/ebay/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 53.2
  mcp: *id011
  name: Etsy
  slug: etsy
  status: profiled
  tags: *id012
  url: /providers/etsy/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.0
  mcp: *id013
  name: Faire
  slug: faire
  status: profiled
  tags: *id014
  url: /providers/faire/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id015
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id016
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id017
  name: Google Shopping
  slug: google-shopping
  status: profiled
  tags: *id018
  url: /providers/google-shopping/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id019
  name: Lightspeed Commerce
  slug: lightspeed
  status: profiled
  tags: *id020
  url: /providers/lightspeed/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id021
  name: Magento
  slug: magento
  status: profiled
  tags: *id022
  url: /providers/magento/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id023
  name: Okta
  slug: okta
  status: profiled
  tags: *id024
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id025
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id026
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id027
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id028
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id029
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id030
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id031
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id032
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id033
  name: Square
  slug: square
  status: profiled
  tags: *id034
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id035
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id036
  url: /providers/squarespace/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id037
  name: UPS
  slug: ups
  status: profiled
  tags: *id038
  url: /providers/ups/
- agent_band: agent-native
  agent_readiness: 51.8
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id039
  name: USPS
  slug: usps
  status: profiled
  tags: *id040
  url: /providers/usps/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 63.7
  mcp: *id041
  name: Walmart
  slug: walmart
  status: profiled
  tags: *id042
  url: /providers/walmart/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id043
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id044
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id045
  name: Xero
  slug: xero
  status: profiled
  tags: *id046
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id047
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id048
  url: /providers/zapier/
siblings:
- name: Cin7
  rows: 15
  url: /applications/inventory-warehouse/cin7/
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
title: 'inFlow Inventory: Inventory & Warehouse Management reference app'
---
