---
app: Sendcloud
app_slug: sendcloud
app_url: https://www.sendcloud.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-410.60
  key: channel-sales-management
  layer: domain
  name: Channel Sales Management
  providers:
  - Amazon
  - Bol
  - ChannelEngine
  - eBay
  - Etsy
  - Kaufland
  - Mirakl
  - TikTok Shop
  url: /capabilities/channel-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Lightspeed
  - Magento 2
  - PrestaShop
  - Shopify
  - Shopware
  - Squarespace
  - Wix
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - Brightpearl
  - Exact Online
  - Linnworks
  - Microsoft Dynamics 365 Business Central
  - Odoo
  - SAP Business One
  - Xentral
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - Austrian Post (Post AG)
  - Bring
  - Chronopost
  - Colissimo
  - Correos
  - DB Schenker
  - Deutsche Post
  - DHL
  - DPD
  - FedEx
  - GLS
  - InPost
  - Landmark Global
  - Maersk
  - Mondial Relay
  - Poste Italiane
  - PostNL
  - PostNord
  - Spring GDS
  - Swiss Post
  - UPS
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: API Evangelist extension
  id: AE-140.90.10
  key: AE-140.90.10
  layer: domain
  name: Returns & Exchanges
  providers:
  - Loop Returns
  - ReturnGO
  url: /capabilities/post-purchase/
  via_parent: Post-Purchase
- attribution: Turbo EA
  id: BC-2460.60
  key: warehouse-resource-management
  layer: domain
  name: Warehouse Resource Management
  providers:
  - ShipHero
  url: /capabilities/warehouse-resource-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Freshdesk
  - Gorgias
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Klaviyo
  url: /capabilities/digital-marketing-management/
  via_parent: null
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
  id: shipping-fulfillment
  name: Shipping, Fulfillment & Returns
  url: /applications/shipping-fulfillment/
counts:
  declared: 53
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.sendcloud.com/carriers/
- route: integrations page
  url: https://www.sendcloud.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
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
  source: https://www.sendcloud.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.0
    mcp: &id003
      status: unknown
    slug: austrian-post
    status: profiled
    tags: &id004
    - Austria
    - Company
    - Logistics
    - Postal
    url: /providers/austrian-post/
  layer: domain
  name: Austrian Post (Post AG)
  provider: austrian-post
  says: lists Austrian Post (Post AG) as an integration
  source: https://www.sendcloud.com/carriers/
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
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 34.4
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id007
      status: none
    slug: bol-com
    status: profiled
    tags: &id008
    - E-Commerce
    - Marketplace
    - Netherlands
    - Retail
    url: /providers/bol-com/
  layer: domain
  name: Bol
  provider: bol-com
  says: lists Bol as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 14.6
    mcp: &id009
      status: none
    slug: brightpearl
    status: profiled
    tags: &id010
    - Company
    - E-Commerce
    - Retail
    - Software-as-a-Service
    url: /providers/brightpearl/
  layer: domain
  name: Brightpearl
  provider: brightpearl
  says: lists Brightpearl as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 17.2
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id011
      status: none
    slug: bring
    status: profiled
    tags: &id012
    - E-Commerce
    - Logistics
    - Norway
    - Shipping
    url: /providers/bring/
  layer: domain
  name: Bring
  provider: bring
  says: lists Bring as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 37.6
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id013
      status: none
    slug: channelengine
    status: profiled
    tags: &id014
    - Company
    - E-Commerce
    - Marketplace Integration
    - Multi-Channel Commerce
    url: /providers/channelengine/
  layer: domain
  name: ChannelEngine
  provider: channelengine
  says: lists ChannelEngine as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id015
      status: none
    slug: chronopost
    status: profiled
    tags: &id016
    - Company
    - Logistics
    - Parcel Delivery
    - Shipping
    url: /providers/chronopost/
  layer: domain
  name: Chronopost
  provider: chronopost
  says: lists Chronopost as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 18.1
    band: thin
    in_catalog: true
    kin_score: 30.0
    mcp: &id017
      status: none
    slug: colissimo
    status: profiled
    tags: &id018
    - Company
    - Logistics
    - Parcel
    - Shipping
    url: /providers/colissimo/
  layer: domain
  name: Colissimo
  provider: colissimo
  says: lists Colissimo as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 15.1
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id019
      status: none
    slug: correos
    status: profiled
    tags: &id020
    - Company
    - Logistics
    - Postal
    - Spain
    url: /providers/correos/
  layer: domain
  name: Correos
  provider: correos
  says: lists Correos as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 16.7
    band: emerging
    in_catalog: true
    kin_score: 23.2
    mcp: &id021
      status: unknown
    slug: db-schenker
    status: profiled
    tags: &id022
    - Freight Forwarding
    - Germany
    - Logistics
    - Supply Chain
    url: /providers/db-schenker/
  layer: domain
  name: DB Schenker
  provider: db-schenker
  says: lists DB Schenker as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id023
      source: https://developer.dhl.com/dhl-api-assistant-mcp-server-integration-visual-studio-code
      status: verified
    slug: deutsche-post
    status: profiled
    tags: &id024
    - Company
    - Logistics
    - Postal
    - Shipping
    url: /providers/deutsche-post/
  layer: domain
  name: Deutsche Post
  provider: deutsche-post
  says: lists Deutsche Post as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id025
      status: none
    slug: dhl
    status: profiled
    tags: &id026
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: lists DHL as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id027
      status: none
    slug: dpd
    status: profiled
    tags: &id028
    - Company
    - International Shipping
    - Logistics
    - Parcel Delivery
    url: /providers/dpd/
  layer: domain
  name: DPD
  provider: dpd
  says: lists DPD as an integration
  source: https://www.sendcloud.com/carriers/
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
    mcp: &id029
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id030
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 34.0
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id031
      source: https://developers.etsy.com/documentation/mcp_server/devmcpserver
      status: verified
    slug: etsy
    status: profiled
    tags: &id032
    - E-Commerce
    - Handmade
    - Listings
    - Marketplace
    url: /providers/etsy/
  layer: domain
  name: Etsy
  provider: etsy
  says: lists Etsy as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id033
      status: none
    slug: exact-online
    status: profiled
    tags: &id034
    - Accounting
    - Business Software
    - ERP
    - Invoicing
    url: /providers/exact-online/
  layer: domain
  name: Exact Online
  provider: exact-online
  says: lists Exact Online as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 35.9
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id035
      status: none
    slug: fedex
    status: profiled
    tags: &id036
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://www.sendcloud.com/carriers/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id037
      status: none
    slug: freshdesk
    status: profiled
    tags: &id038
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: common
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://www.sendcloud.com/integrations/
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
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id039
      status: none
    slug: gls-group
    status: profiled
    tags: &id040
    - Logistics
    - Netherlands
    - Parcel
    - Supply Chain
    url: /providers/gls-group/
  layer: domain
  name: GLS
  provider: gls-group
  says: lists GLS as an integration
  source: https://www.sendcloud.com/carriers/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id041
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id042
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: common
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.6
    mcp: &id043
      status: none
    slug: inpost
    status: profiled
    tags: &id044
    - Company
    url: /providers/inpost/
  layer: domain
  name: InPost
  provider: inpost
  says: lists InPost as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.6
    mcp: &id045
      status: unknown
    slug: kaufland
    status: profiled
    tags: &id046
    - Company
    - E-Commerce
    - Grocery
    - Retail
    url: /providers/kaufland/
  layer: domain
  name: Kaufland
  provider: kaufland
  says: lists Kaufland as an integration
  source: https://www.sendcloud.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id047
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id048
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: common
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id049
      status: none
    slug: landmark-global
    status: profiled
    tags: &id050
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/landmark-global/
  layer: domain
  name: Landmark Global
  provider: landmark-global
  says: lists Landmark Global as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 86.5
    mcp: &id051
      status: none
    slug: lightspeed
    status: profiled
    tags: &id052
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 14.3
    mcp: &id053
      status: none
    slug: linnworks
    status: profiled
    tags: &id054
    - Company
    - E-Commerce
    - Inventory
    - Software-as-a-Service
    url: /providers/linnworks/
  layer: domain
  name: Linnworks
  provider: linnworks
  says: lists Linnworks as an integration
  source: https://www.sendcloud.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.90.10
    key: AE-140.90.10
    name: Returns & Exchanges
    url: /capabilities/post-purchase/
    via_parent: Post-Purchase
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id055
      status: none
    slug: loop-returns
    status: profiled
    tags: &id056
    - E-Commerce
    - Refunds
    - Returns
    - Shipping
    url: /providers/loop-returns/
  layer: domain
  name: Loop Returns
  provider: loop-returns
  says: lists Loop Returns as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 44.7
    mcp: &id057
      status: none
    slug: maersk-line
    status: profiled
    tags: &id058
    - Container Shipping
    - Logistics
    - Ocean Freight
    - Shipping
    url: /providers/maersk-line/
  layer: domain
  name: Maersk
  provider: maersk-line
  says: lists Maersk as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 24.0
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id059
      status: none
    slug: magento
    status: profiled
    tags: &id060
    - Catalog
    - E-Commerce
    - Headless Commerce
    - Magento
    url: /providers/magento/
  layer: domain
  name: Magento 2
  provider: magento
  says: lists Magento 2 as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 43.9
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id061
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id062
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 36.1
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id063
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id064
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: domain
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 55.2
    band: exemplar
    in_catalog: true
    kin_score: 75.9
    mcp: &id065
      status: none
    slug: mirakl
    status: profiled
    tags: &id066
    - Commerce
    - Company
    - E-Commerce
    - Marketplace
    url: /providers/mirakl/
  layer: domain
  name: Mirakl
  provider: mirakl
  says: lists Mirakl as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id067
      status: none
    slug: mondial-relay
    status: profiled
    tags: &id068
    - Company
    - E-Commerce
    - Logistics
    - Parcel Delivery
    url: /providers/mondial-relay/
  layer: domain
  name: Mondial Relay
  provider: mondial-relay
  says: lists Mondial Relay as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id069
      status: none
    slug: odoo
    status: profiled
    tags: &id070
    - Business Applications
    - CRM
    - ERP
    - Open Source
    url: /providers/odoo/
  layer: domain
  name: Odoo
  provider: odoo
  says: lists Odoo as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 10.8
    band: minimal
    in_catalog: true
    kin_score: 9.5
    mcp: &id071
      status: unknown
    slug: poste-italiane
    status: profiled
    tags: &id072
    - Company
    - Logistics
    - Postal Services
    - Shipping
    url: /providers/poste-italiane/
  layer: domain
  name: Poste Italiane
  provider: poste-italiane
  says: lists Poste Italiane as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id073
      status: unchecked
    slug: postnl
    status: queued for profiling
    tags: &id074 []
    url: null
  layer: domain
  name: PostNL
  provider: postnl
  says: lists PostNL as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id075
      status: none
    slug: postnord
    status: profiled
    tags: &id076
    - Postal
    - Public APIs
    - Shipping
    - Tracking
    url: /providers/postnord/
  layer: domain
  name: PostNord
  provider: postnord
  says: lists PostNord as an integration
  source: https://www.sendcloud.com/carriers/
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
    kin_score: 21.7
    mcp: &id077
      status: none
    slug: prestashop
    status: profiled
    tags: &id078
    - E-Commerce
    - Open Source
    - Order
    - Product
    url: /providers/prestashop/
  layer: domain
  name: PrestaShop
  provider: prestashop
  says: lists PrestaShop as an integration
  source: https://www.sendcloud.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.90.10
    key: AE-140.90.10
    name: Returns & Exchanges
    url: /capabilities/post-purchase/
    via_parent: Post-Purchase
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 17.6
    mcp: &id079
      status: unknown
    slug: returngo
    status: profiled
    tags: &id080
    - Company
    - E-Commerce
    - Returns
    - Sustainability
    url: /providers/returngo/
  layer: domain
  name: ReturnGO
  provider: returngo
  says: lists ReturnGO as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id081
      status: none
    slug: sap-business-one
    status: profiled
    tags: &id082
    - Accounting
    - CRM
    - ERP
    - Inventory
    url: /providers/sap-business-one/
  layer: domain
  name: SAP Business One
  provider: sap-business-one
  says: lists SAP Business One as an integration
  source: https://www.sendcloud.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2460.60
    key: warehouse-resource-management
    name: Warehouse Resource Management
    url: /capabilities/warehouse-resource-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id083
      status: none
    slug: shiphero
    status: profiled
    tags: &id084
    - E-Commerce
    - Fulfillment
    - GraphQL
    - Warehouse Management
    url: /providers/shiphero/
  layer: domain
  name: ShipHero
  provider: shiphero
  says: lists ShipHero as an integration
  source: https://www.sendcloud.com/integrations/
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
    mcp: &id085
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id086
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id087
      status: unchecked
    slug: shopware-com
    status: queued for profiling
    tags: &id088 []
    url: null
  layer: domain
  name: Shopware
  provider: shopware-com
  says: lists Shopware as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 6.5
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id089
      status: unknown
    slug: spring-gds
    status: profiled
    tags: &id090
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/spring-gds/
  layer: domain
  name: Spring GDS
  provider: spring-gds
  says: lists Spring GDS as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_band: agent-native
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 69.9
    mcp: &id091
      status: none
    slug: squarespace
    status: profiled
    tags: &id092
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 25.4
    band: emerging
    in_catalog: true
    kin_score: 21.1
    mcp: &id093
      status: none
    slug: swiss-post
    status: profiled
    tags: &id094
    - Company
    - Finance
    - Logistics
    - Postal Service
    url: /providers/swiss-post/
  layer: domain
  name: Swiss Post
  provider: swiss-post
  says: lists Swiss Post as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id095
      status: none
    slug: tiktok-shop
    status: profiled
    tags: &id096
    - E-Commerce
    - Marketplace
    - Order Management
    - Social Commerce
    url: /providers/tiktok-shop/
  layer: domain
  name: TikTok Shop
  provider: tiktok-shop
  says: lists TikTok Shop as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id097
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id098
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://www.sendcloud.com/carriers/
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
    agent_readiness: 48.2
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id099
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id100
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://www.sendcloud.com/integrations/
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
    mcp: &id101
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id102
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.sendcloud.com/integrations/
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
    agent_readiness: 46.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id103
      source: https://github.com/xentral/shiplabel-mcp
      status: verified
    slug: xentral
    status: profiled
    tags: &id104
    - Company
    - E-Commerce
    - ERP
    - Fulfillment
    url: /providers/xentral/
  layer: domain
  name: Xentral
  provider: xentral
  says: lists Xentral as an integration
  source: https://www.sendcloud.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id105
      status: none
    slug: zendesk
    status: profiled
    tags: &id106
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.sendcloud.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/shipping-fulfillment/sendcloud/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.0
  mcp: *id003
  name: Austrian Post (Post AG)
  slug: austrian-post
  status: profiled
  tags: *id004
  url: /providers/austrian-post/
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
  agent_readiness: 34.4
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id007
  name: Bol
  slug: bol-com
  status: profiled
  tags: *id008
  url: /providers/bol-com/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id009
  name: Brightpearl
  slug: brightpearl
  status: profiled
  tags: *id010
  url: /providers/brightpearl/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id011
  name: Bring
  slug: bring
  status: profiled
  tags: *id012
  url: /providers/bring/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id013
  name: ChannelEngine
  slug: channelengine
  status: profiled
  tags: *id014
  url: /providers/channelengine/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id015
  name: Chronopost
  slug: chronopost
  status: profiled
  tags: *id016
  url: /providers/chronopost/
- agent_band: agent-aware
  agent_readiness: 18.1
  band: thin
  in_catalog: true
  kin_score: 30.0
  mcp: *id017
  name: Colissimo
  slug: colissimo
  status: profiled
  tags: *id018
  url: /providers/colissimo/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id019
  name: Correos
  slug: correos
  status: profiled
  tags: *id020
  url: /providers/correos/
- agent_band: agent-aware
  agent_readiness: 16.7
  band: emerging
  in_catalog: true
  kin_score: 23.2
  mcp: *id021
  name: DB Schenker
  slug: db-schenker
  status: profiled
  tags: *id022
  url: /providers/db-schenker/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id023
  name: Deutsche Post
  slug: deutsche-post
  status: profiled
  tags: *id024
  url: /providers/deutsche-post/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id025
  name: DHL
  slug: dhl
  status: profiled
  tags: *id026
  url: /providers/dhl/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id027
  name: DPD
  slug: dpd
  status: profiled
  tags: *id028
  url: /providers/dpd/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id029
  name: eBay
  slug: ebay
  status: profiled
  tags: *id030
  url: /providers/ebay/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id031
  name: Etsy
  slug: etsy
  status: profiled
  tags: *id032
  url: /providers/etsy/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id033
  name: Exact Online
  slug: exact-online
  status: profiled
  tags: *id034
  url: /providers/exact-online/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id035
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id036
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id037
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id038
  url: /providers/freshdesk/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id039
  name: GLS
  slug: gls-group
  status: profiled
  tags: *id040
  url: /providers/gls-group/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id041
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id042
  url: /providers/gorgias/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.6
  mcp: *id043
  name: InPost
  slug: inpost
  status: profiled
  tags: *id044
  url: /providers/inpost/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id045
  name: Kaufland
  slug: kaufland
  status: profiled
  tags: *id046
  url: /providers/kaufland/
- agent_band: agent-native
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id047
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id048
  url: /providers/klaviyo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id049
  name: Landmark Global
  slug: landmark-global
  status: profiled
  tags: *id050
  url: /providers/landmark-global/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 86.5
  mcp: *id051
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id052
  url: /providers/lightspeed/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 14.3
  mcp: *id053
  name: Linnworks
  slug: linnworks
  status: profiled
  tags: *id054
  url: /providers/linnworks/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id055
  name: Loop Returns
  slug: loop-returns
  status: profiled
  tags: *id056
  url: /providers/loop-returns/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id057
  name: Maersk
  slug: maersk-line
  status: profiled
  tags: *id058
  url: /providers/maersk-line/
- agent_band: agent-aware
  agent_readiness: 24.0
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id059
  name: Magento 2
  slug: magento
  status: profiled
  tags: *id060
  url: /providers/magento/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id061
  name: Make
  slug: make
  status: profiled
  tags: *id062
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id063
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id064
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: exemplar
  in_catalog: true
  kin_score: 75.9
  mcp: *id065
  name: Mirakl
  slug: mirakl
  status: profiled
  tags: *id066
  url: /providers/mirakl/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id067
  name: Mondial Relay
  slug: mondial-relay
  status: profiled
  tags: *id068
  url: /providers/mondial-relay/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id069
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id070
  url: /providers/odoo/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id071
  name: Poste Italiane
  slug: poste-italiane
  status: profiled
  tags: *id072
  url: /providers/poste-italiane/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id073
  name: PostNL
  slug: postnl
  status: queued for profiling
  tags: *id074
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id075
  name: PostNord
  slug: postnord
  status: profiled
  tags: *id076
  url: /providers/postnord/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 21.7
  mcp: *id077
  name: PrestaShop
  slug: prestashop
  status: profiled
  tags: *id078
  url: /providers/prestashop/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id079
  name: ReturnGO
  slug: returngo
  status: profiled
  tags: *id080
  url: /providers/returngo/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id081
  name: SAP Business One
  slug: sap-business-one
  status: profiled
  tags: *id082
  url: /providers/sap-business-one/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id083
  name: ShipHero
  slug: shiphero
  status: profiled
  tags: *id084
  url: /providers/shiphero/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id085
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id086
  url: /providers/shopify/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id087
  name: Shopware
  slug: shopware-com
  status: queued for profiling
  tags: *id088
  url: null
- agent_band: agent-aware
  agent_readiness: 6.5
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id089
  name: Spring GDS
  slug: spring-gds
  status: profiled
  tags: *id090
  url: /providers/spring-gds/
- agent_band: agent-native
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 69.9
  mcp: *id091
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id092
  url: /providers/squarespace/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: emerging
  in_catalog: true
  kin_score: 21.1
  mcp: *id093
  name: Swiss Post
  slug: swiss-post
  status: profiled
  tags: *id094
  url: /providers/swiss-post/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id095
  name: TikTok Shop
  slug: tiktok-shop
  status: profiled
  tags: *id096
  url: /providers/tiktok-shop/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id097
  name: UPS
  slug: ups
  status: profiled
  tags: *id098
  url: /providers/ups/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id099
  name: Wix
  slug: wix
  status: profiled
  tags: *id100
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id101
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id102
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 46.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id103
  name: Xentral
  slug: xentral
  status: profiled
  tags: *id104
  url: /providers/xentral/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id105
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id106
  url: /providers/zendesk/
siblings:
- name: ERPNext Shipping
  rows: 2
  url: /applications/shipping-fulfillment/erpnext-shipping/
- name: Karrio
  rows: 24
  url: /applications/shipping-fulfillment/karrio/
- name: Loop Returns
  rows: 9
  url: /applications/shipping-fulfillment/loop-returns/
- name: Odoo Inventory (delivery connectors)
  rows: 11
  url: /applications/shipping-fulfillment/odoo-inventory-delivery-connectors/
- name: Shippo
  rows: 33
  url: /applications/shipping-fulfillment/shippo/
sitemap: true
title: 'Sendcloud: Shipping, Fulfillment & Returns reference app'
---
