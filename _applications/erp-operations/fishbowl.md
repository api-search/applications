---
app: Fishbowl
app_slug: fishbowl
app_url: https://www.fishbowlinventory.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - ConverSight
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-919
  key: AE-919
  layer: domain
  name: B2B EDI & Trading-Partner Networks
  providers:
  - SPS Commerce
  - TrueCommerce
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-920
  key: AE-920
  layer: domain
  name: Barcode, RFID & Mobile Data Capture
  providers:
  - Wasp Barcode
  - Zebra
  url: /capabilities/storage-and-inventory-operations-management/
  via_parent: Storage and Inventory Operations Management
- attribution: Turbo EA
  id: BC-410.60
  key: channel-sales-management
  layer: domain
  name: Channel Sales Management
  providers:
  - Amazon
  - eBay
  - Newegg
  - Pepperi
  - Walmart
  url: /capabilities/channel-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  - Zoho
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-520.10
  key: demand-planning-management
  layer: domain
  name: Demand Planning Management
  providers:
  - Netstock
  - StockTrim
  url: /capabilities/demand-planning-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks (Online, Canada, Payments)
  - Reckon
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Adobe Commerce
  - BigCommerce
  - Shift4Shop
  - Shopify
  - Volusion
  - Web Shop Manager
  - WooCommerce
  - Zen Cart
  - Zoey
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Avalara
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2380.20
  key: BC-2380.20
  layer: domain
  name: Lot & Batch Traceability Management
  providers:
  - Metrc
  url: /capabilities/lot-batch-traceability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - Spark Shipping
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - Endicia
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Authorize.Net
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510.20
  key: shipment-tracking-management
  layer: domain
  name: Shipment Tracking Management
  providers:
  - DHL
  - FedEx
  - OnTrac
  - ShipRush
  - ShipStation
  - ShipWorks
  - StarShip
  - UPS
  - USPS
  url: /capabilities/shipment-tracking-management/
  via_parent: null
category:
  id: erp-operations
  name: ERP & Business Operations
  url: /applications/erp-operations/
counts:
  declared: 42
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.fishbowlinventory.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id001
      status: none
    slug: adobe-commerce
    status: profiled
    tags: &id002
    - Adobe
    - Commerce
    - E-Commerce
    - Magento
    url: /providers/adobe-commerce/
  layer: domain
  name: Adobe Commerce
  provider: adobe-commerce
  says: lists Adobe Commerce as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
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
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id005
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id006
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: domain
  name: Authorize.Net
  provider: authorizenet
  says: lists Authorize.Net as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id007
      source: https://github.com/avadev/mcp
      status: verified
    slug: avalara
    status: profiled
    tags: &id008
    - Accounting
    - Avalara
    - Tax
    url: /providers/avalara/
  layer: domain
  name: Avalara
  provider: avalara
  says: lists Avalara as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id009
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id010
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: conversight
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: ConverSight
  provider: conversight
  says: lists ConverSight as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-native
    agent_readiness: 39.5
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id013
      status: none
    slug: dhl
    status: profiled
    tags: &id014
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: lists DHL as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id015
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id016
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id017
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id018
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 16.1
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id019
      status: none
    slug: stamps-com
    status: profiled
    tags: &id020
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/stamps-com/
  layer: domain
  name: Endicia
  provider: stamps-com
  says: lists Endicia as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 35.2
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id021
      status: none
    slug: fedex
    status: profiled
    tags: &id022
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id023
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id024
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2380.20
    key: BC-2380.20
    name: Lot & Batch Traceability Management
    url: /capabilities/lot-batch-traceability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id025
      status: none
    slug: metrc
    status: profiled
    tags: &id026
    - Cannabis
    - Company
    - Compliance
    - Track and Trace
    url: /providers/metrc/
  layer: domain
  name: Metrc
  provider: metrc
  says: lists Metrc as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.10
    key: demand-planning-management
    name: Demand Planning Management
    url: /capabilities/demand-planning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: emerging
    in_catalog: true
    kin_score: 25.4
    mcp: &id027
      status: none
    slug: netstock
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Demand Planning
    - Inventory
    - Supply Chain Planning
    url: /providers/netstock/
  layer: domain
  name: Netstock
  provider: netstock
  says: lists Netstock as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id029
      status: none
    slug: newegg
    status: profiled
    tags: &id030
    - Company
    - Consumer
    - E-Commerce
    - Marketplace
    url: /providers/newegg/
  layer: domain
  name: Newegg
  provider: newegg
  says: lists Newegg as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id031
      status: none
    slug: ontrac
    status: profiled
    tags: &id032
    - Delivery
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/ontrac/
  layer: domain
  name: OnTrac
  provider: ontrac
  says: lists OnTrac as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id033
      source: https://www.npmjs.com/package/@pepperi-addons/api-mcp
      status: verified
    slug: pepperi
    status: profiled
    tags: &id034
    - B2B
    - Commerce
    - Company
    - Retail
    url: /providers/pepperi/
  layer: domain
  name: Pepperi
  provider: pepperi
  says: lists Pepperi as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id035
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id036
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks (Online, Canada, Payments)
  provider: quickbooks
  says: lists QuickBooks (Online, Canada, Payments) as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id037
      status: unknown
    slug: reckon
    status: profiled
    tags: &id038
    - Accounting
    - Australia
    - Small Business
    - Software
    url: /providers/reckon/
  layer: domain
  name: Reckon
  provider: reckon
  says: lists Reckon as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id039
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id040
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id041
      status: none
    slug: shift4shop
    status: profiled
    tags: &id042
    - E-Commerce
    - Order
    - Product
    - Shopping Cart
    url: /providers/shift4shop/
  layer: domain
  name: Shift4Shop
  provider: shift4shop
  says: lists Shift4Shop as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id043
      status: unknown
    slug: shiprush
    status: profiled
    tags: &id044
    - E-Commerce
    - Multi-Carrier
    - Shipping
    - Software-as-a-Service
    url: /providers/shiprush/
  layer: domain
  name: ShipRush
  provider: shiprush
  says: lists ShipRush as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 45.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id045
      status: none
    slug: shipstation
    status: profiled
    tags: &id046
    - E-Commerce
    - Labels
    - Logistics
    - ShipStation
    url: /providers/shipstation/
  layer: domain
  name: ShipStation
  provider: shipstation
  says: lists ShipStation as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 4.9
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id047
      status: none
    slug: shipworks
    status: profiled
    tags: &id048
    - E-Commerce
    - Logistics
    - Shipping
    - Software
    url: /providers/shipworks/
  layer: domain
  name: ShipWorks
  provider: shipworks
  says: lists ShipWorks as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id049
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id050
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.1
    mcp: &id051
      status: none
    slug: spark-shipping
    status: profiled
    tags: &id052
    - Automation
    - Company
    - Dropshipping
    - E-Commerce
    url: /providers/spark-shipping/
  layer: domain
  name: Spark Shipping
  provider: spark-shipping
  says: lists Spark Shipping as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id053
      status: none
    slug: sps-commerce
    status: profiled
    tags: &id054
    - Company
    - EDI
    - Retail
    - Supply Chain
    url: /providers/sps-commerce/
  layer: domain
  name: SPS Commerce
  provider: sps-commerce
  says: lists SPS Commerce as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id055
      status: unknown
    slug: starship-shipping
    status: profiled
    tags: &id056
    - Carrier Rates
    - Discounted Shipping
    - Shipping
    url: /providers/starship-shipping/
  layer: domain
  name: StarShip
  provider: starship-shipping
  says: lists StarShip as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.10
    key: demand-planning-management
    name: Demand Planning Management
    url: /capabilities/demand-planning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id057
      status: unknown
    slug: stocktrim
    status: profiled
    tags: &id058
    - Company
    - Forecasting
    - Inventory
    - Supply Chain
    url: /providers/stocktrim/
  layer: domain
  name: StockTrim
  provider: stocktrim
  says: lists StockTrim as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 17.7
    mcp: &id059
      status: none
    slug: truecommerce
    status: profiled
    tags: &id060
    - Company
    - EDI
    - Integration
    - Supply Chain
    url: /providers/truecommerce/
  layer: domain
  name: TrueCommerce
  provider: truecommerce
  says: lists TrueCommerce as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 29.2
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id061
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id062
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-native
    agent_readiness: 51.8
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id063
      status: none
    slug: usps
    status: profiled
    tags: &id064
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: lists USPS as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: human-only
    agent_readiness: 3.8
    band: emerging
    in_catalog: true
    kin_score: 15.4
    mcp: &id065
      status: none
    slug: volusion
    status: profiled
    tags: &id066
    - E-Commerce
    - Online Store
    - Order
    - Product
    url: /providers/volusion/
  layer: domain
  name: Volusion
  provider: volusion
  says: lists Volusion as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id067
      status: none
    slug: walmart
    status: profiled
    tags: &id068
    - Commerce
    - Fortune 100
    - Retail
    - Walmart
    url: /providers/walmart/
  layer: domain
  name: Walmart
  provider: walmart
  says: lists Walmart as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-920
    key: AE-920
    name: Barcode, RFID & Mobile Data Capture
    url: /capabilities/storage-and-inventory-operations-management/
    via_parent: Storage and Inventory Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id069
      status: none
    slug: wasp-barcode
    status: profiled
    tags: &id070
    - Asset Tracking
    - Barcode Technology
    - Company
    - Inventory
    url: /providers/wasp-barcode/
  layer: domain
  name: Wasp Barcode
  provider: wasp-barcode
  says: lists Wasp Barcode as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id071
      status: none
    slug: web-shop-manager
    status: profiled
    tags: &id072
    - Automotive
    - B2B
    - E-Commerce
    - Software-as-a-Service
    url: /providers/web-shop-manager/
  layer: domain
  name: Web Shop Manager
  provider: web-shop-manager
  says: lists Web Shop Manager as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id073
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id074
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    mcp: &id075
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id076
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-920
    key: AE-920
    name: Barcode, RFID & Mobile Data Capture
    url: /capabilities/storage-and-inventory-operations-management/
    via_parent: Storage and Inventory Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id077
      status: none
    slug: zebra-technologies
    status: profiled
    tags: &id078
    - Barcodes
    - Manufacturing
    - RFID
    - Warehouse Automation
    url: /providers/zebra-technologies/
  layer: domain
  name: Zebra
  provider: zebra-technologies
  says: lists Zebra as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id079
      status: none
    slug: zen-cart
    status: profiled
    tags: &id080
    - E-Commerce
    - Open Source
    - PHP
    - Shopping Cart
    url: /providers/zen-cart/
  layer: domain
  name: Zen Cart
  provider: zen-cart
  says: lists Zen Cart as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 7.3
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id081
      status: unknown
    slug: zoey
    status: profiled
    tags: &id082
    - B2B
    - Company
    - E-Commerce
    - Wholesale
    url: /providers/zoey/
  layer: domain
  name: Zoey
  provider: zoey
  says: lists Zoey as an integration
  source: https://www.fishbowlinventory.com/integrations
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
    agent_readiness: 32.4
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id083
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id084
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: domain
  name: Zoho
  provider: zoho
  says: lists Zoho as an integration
  source: https://www.fishbowlinventory.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/erp-operations/fishbowl/
providers:
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id001
  name: Adobe Commerce
  slug: adobe-commerce
  status: profiled
  tags: *id002
  url: /providers/adobe-commerce/
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id003
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id004
  url: /providers/amazon/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id005
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id006
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id007
  name: Avalara
  slug: avalara
  status: profiled
  tags: *id008
  url: /providers/avalara/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id009
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id010
  url: /providers/bigcommerce/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: ConverSight
  slug: conversight
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-native
  agent_readiness: 39.5
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id013
  name: DHL
  slug: dhl
  status: profiled
  tags: *id014
  url: /providers/dhl/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id015
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id016
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id017
  name: eBay
  slug: ebay
  status: profiled
  tags: *id018
  url: /providers/ebay/
- agent_band: agent-aware
  agent_readiness: 16.1
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id019
  name: Endicia
  slug: stamps-com
  status: profiled
  tags: *id020
  url: /providers/stamps-com/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id021
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id022
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id023
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id024
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id025
  name: Metrc
  slug: metrc
  status: profiled
  tags: *id026
  url: /providers/metrc/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id027
  name: Netstock
  slug: netstock
  status: profiled
  tags: *id028
  url: /providers/netstock/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id029
  name: Newegg
  slug: newegg
  status: profiled
  tags: *id030
  url: /providers/newegg/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id031
  name: OnTrac
  slug: ontrac
  status: profiled
  tags: *id032
  url: /providers/ontrac/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id033
  name: Pepperi
  slug: pepperi
  status: profiled
  tags: *id034
  url: /providers/pepperi/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id035
  name: QuickBooks (Online, Canada, Payments)
  slug: quickbooks
  status: profiled
  tags: *id036
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id037
  name: Reckon
  slug: reckon
  status: profiled
  tags: *id038
  url: /providers/reckon/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id039
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id040
  url: /providers/salesforce/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id041
  name: Shift4Shop
  slug: shift4shop
  status: profiled
  tags: *id042
  url: /providers/shift4shop/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id043
  name: ShipRush
  slug: shiprush
  status: profiled
  tags: *id044
  url: /providers/shiprush/
- agent_band: agent-ready
  agent_readiness: 45.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id045
  name: ShipStation
  slug: shipstation
  status: profiled
  tags: *id046
  url: /providers/shipstation/
- agent_band: human-only
  agent_readiness: 4.9
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id047
  name: ShipWorks
  slug: shipworks
  status: profiled
  tags: *id048
  url: /providers/shipworks/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id049
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id050
  url: /providers/shopify/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.1
  mcp: *id051
  name: Spark Shipping
  slug: spark-shipping
  status: profiled
  tags: *id052
  url: /providers/spark-shipping/
- agent_band: agent-ready
  agent_readiness: 40.4
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id053
  name: SPS Commerce
  slug: sps-commerce
  status: profiled
  tags: *id054
  url: /providers/sps-commerce/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id055
  name: StarShip
  slug: starship-shipping
  status: profiled
  tags: *id056
  url: /providers/starship-shipping/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id057
  name: StockTrim
  slug: stocktrim
  status: profiled
  tags: *id058
  url: /providers/stocktrim/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 17.7
  mcp: *id059
  name: TrueCommerce
  slug: truecommerce
  status: profiled
  tags: *id060
  url: /providers/truecommerce/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id061
  name: UPS
  slug: ups
  status: profiled
  tags: *id062
  url: /providers/ups/
- agent_band: agent-native
  agent_readiness: 51.8
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id063
  name: USPS
  slug: usps
  status: profiled
  tags: *id064
  url: /providers/usps/
- agent_band: human-only
  agent_readiness: 3.8
  band: emerging
  in_catalog: true
  kin_score: 15.4
  mcp: *id065
  name: Volusion
  slug: volusion
  status: profiled
  tags: *id066
  url: /providers/volusion/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 63.7
  mcp: *id067
  name: Walmart
  slug: walmart
  status: profiled
  tags: *id068
  url: /providers/walmart/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id069
  name: Wasp Barcode
  slug: wasp-barcode
  status: profiled
  tags: *id070
  url: /providers/wasp-barcode/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id071
  name: Web Shop Manager
  slug: web-shop-manager
  status: profiled
  tags: *id072
  url: /providers/web-shop-manager/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id073
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id074
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id075
  name: Xero
  slug: xero
  status: profiled
  tags: *id076
  url: /providers/xero/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id077
  name: Zebra
  slug: zebra-technologies
  status: profiled
  tags: *id078
  url: /providers/zebra-technologies/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id079
  name: Zen Cart
  slug: zen-cart
  status: profiled
  tags: *id080
  url: /providers/zen-cart/
- agent_band: agent-aware
  agent_readiness: 7.3
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id081
  name: Zoey
  slug: zoey
  status: profiled
  tags: *id082
  url: /providers/zoey/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id083
  name: Zoho
  slug: zoho
  status: profiled
  tags: *id084
  url: /providers/zoho/
siblings:
- name: Dolibarr
  rows: 13
  url: /applications/erp-operations/dolibarr/
- name: ERPNext
  rows: 24
  url: /applications/erp-operations/erpnext/
- name: Katana
  rows: 19
  url: /applications/erp-operations/katana/
- name: Odoo
  rows: 45
  url: /applications/erp-operations/odoo/
- name: Tryton
  rows: 13
  url: /applications/erp-operations/tryton/
sitemap: true
title: 'Fishbowl: ERP & Business Operations reference app'
---
