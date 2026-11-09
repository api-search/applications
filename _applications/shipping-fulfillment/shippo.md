---
app: Shippo
app_slug: shippo
app_url: https://goshippo.com/
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
  - Etsy
  - TikTok Shop
  - Walmart
  url: /capabilities/channel-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Magento 2
  - Shopify
  - Square
  - Webflow
  - Wix
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - Aramex
  - Australia Post
  - Canada Post
  - Chronopost
  - Colissimo
  - Correos
  - Deutsche Post
  - DHL
  - DPD
  - Evri
  - FedEx
  - GLS
  - Mondial Relay
  - OnTrac
  - Pitney Bowes
  - Poste Italiane
  - Purolator
  - Royal Mail
  - UPS
  - USPS
  - Veho
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
category:
  id: shipping-fulfillment
  name: Shipping, Fulfillment & Returns
  url: /applications/shipping-fulfillment/
counts:
  declared: 33
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://goshippo.com/carriers
- route: integrations page
  url: https://goshippo.com/integrations
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
  source: https://goshippo.com/integrations
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
    kin_score: 12.4
    mcp: &id003
      status: unknown
    slug: aramex
    status: profiled
    tags: &id004
    - Company
    - Logistics
    - Shipping
    - Tracking
    url: /providers/aramex/
  layer: domain
  name: Aramex
  provider: aramex
  says: lists Aramex as an integration
  source: https://goshippo.com/carriers
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
    agent_readiness: 31.5
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id005
      status: none
    slug: australia-post
    status: profiled
    tags: &id006
    - Address Validation
    - Click and Collect
    - Delivery
    - E-Commerce
    url: /providers/australia-post/
  layer: domain
  name: Australia Post
  provider: australia-post
  says: lists Australia Post as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id007
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id008
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://goshippo.com/integrations
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
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id009
      status: none
    slug: canada-post
    status: profiled
    tags: &id010
    - Address Validation
    - E-Commerce
    - Labels
    - Logistics
    url: /providers/canada-post/
  layer: domain
  name: Canada Post
  provider: canada-post
  says: lists Canada Post as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id011
      status: none
    slug: chronopost
    status: profiled
    tags: &id012
    - Company
    - Logistics
    - Parcel Delivery
    - Shipping
    url: /providers/chronopost/
  layer: domain
  name: Chronopost
  provider: chronopost
  says: lists Chronopost as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id013
      status: none
    slug: colissimo
    status: profiled
    tags: &id014
    - Company
    - Logistics
    - Parcel
    - Shipping
    url: /providers/colissimo/
  layer: domain
  name: Colissimo
  provider: colissimo
  says: lists Colissimo as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id015
      status: none
    slug: correos
    status: profiled
    tags: &id016
    - Company
    - Logistics
    - Postal
    - Spain
    url: /providers/correos/
  layer: domain
  name: Correos
  provider: correos
  says: lists Correos as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id017
      source: https://developer.dhl.com/dhl-api-assistant-mcp-server-integration-visual-studio-code
      status: verified
    slug: deutsche-post
    status: profiled
    tags: &id018
    - Company
    - Logistics
    - Postal
    - Shipping
    url: /providers/deutsche-post/
  layer: domain
  name: Deutsche Post
  provider: deutsche-post
  says: lists Deutsche Post as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id019
      status: none
    slug: dhl
    status: profiled
    tags: &id020
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: lists DHL as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id021
      status: none
    slug: dpd
    status: profiled
    tags: &id022
    - Company
    - International Shipping
    - Logistics
    - Parcel Delivery
    url: /providers/dpd/
  layer: domain
  name: DPD
  provider: dpd
  says: lists DPD as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id023
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id024
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://goshippo.com/integrations
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
    mcp: &id025
      source: https://developers.etsy.com/documentation/mcp_server/devmcpserver
      status: verified
    slug: etsy
    status: profiled
    tags: &id026
    - E-Commerce
    - Handmade
    - Listings
    - Marketplace
    url: /providers/etsy/
  layer: domain
  name: Etsy
  provider: etsy
  says: lists Etsy as an integration
  source: https://goshippo.com/integrations
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
    kin_score: 5.6
    mcp: &id027
      status: unknown
    slug: evri
    status: profiled
    tags: &id028
    - Logistics
    - Parcel
    - Supply Chain
    - United Kingdom
    url: /providers/evri/
  layer: domain
  name: Evri
  provider: evri
  says: lists Evri as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id029
      status: none
    slug: fedex
    status: profiled
    tags: &id030
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id031
      status: none
    slug: gls-group
    status: profiled
    tags: &id032
    - Logistics
    - Netherlands
    - Parcel
    - Supply Chain
    url: /providers/gls-group/
  layer: domain
  name: GLS
  provider: gls-group
  says: lists GLS as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id033
      status: none
    slug: magento
    status: profiled
    tags: &id034
    - Catalog
    - E-Commerce
    - Headless Commerce
    - Magento
    url: /providers/magento/
  layer: domain
  name: Magento 2
  provider: magento
  says: lists Magento 2 as an integration
  source: https://goshippo.com/integrations
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
    mcp: &id035
      status: none
    slug: mondial-relay
    status: profiled
    tags: &id036
    - Company
    - E-Commerce
    - Logistics
    - Parcel Delivery
    url: /providers/mondial-relay/
  layer: domain
  name: Mondial Relay
  provider: mondial-relay
  says: lists Mondial Relay as an integration
  source: https://goshippo.com/carriers
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
    kin_score: 9.8
    mcp: &id037
      status: none
    slug: ontrac
    status: profiled
    tags: &id038
    - Delivery
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/ontrac/
  layer: domain
  name: OnTrac
  provider: ontrac
  says: lists OnTrac as an integration
  source: https://goshippo.com/carriers
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
    kin_score: 25.1
    mcp: &id039
      status: none
    slug: pitney-bowes
    status: profiled
    tags: &id040
    - Fortune 1000
    - Mailing
    - Shipping
    url: /providers/pitney-bowes/
  layer: domain
  name: Pitney Bowes
  provider: pitney-bowes
  says: lists Pitney Bowes as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id041
      status: unknown
    slug: poste-italiane
    status: profiled
    tags: &id042
    - Company
    - Logistics
    - Postal Services
    - Shipping
    url: /providers/poste-italiane/
  layer: domain
  name: Poste Italiane
  provider: poste-italiane
  says: lists Poste Italiane as an integration
  source: https://goshippo.com/carriers
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
    agent_readiness: 3.5
    band: emerging
    in_catalog: true
    kin_score: 17.8
    mcp: &id043
      status: none
    slug: purolator
    status: profiled
    tags: &id044
    - Company
    - Couriers
    - Logistics
    - Shipping
    url: /providers/purolator/
  layer: domain
  name: Purolator
  provider: purolator
  says: lists Purolator as an integration
  source: https://goshippo.com/carriers
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
    agent_readiness: 26.2
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id045
      status: none
    slug: royal-mail
    status: profiled
    tags: &id046
    - Labels
    - Postal Services
    - Shipping
    - Tracking
    url: /providers/royal-mail/
  layer: domain
  name: Royal Mail
  provider: royal-mail
  says: lists Royal Mail as an integration
  source: https://goshippo.com/carriers
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
    mcp: &id047
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id048
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://goshippo.com/integrations
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
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id049
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id050
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://goshippo.com/integrations
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
    mcp: &id051
      status: none
    slug: tiktok-shop
    status: profiled
    tags: &id052
    - E-Commerce
    - Marketplace
    - Order Management
    - Social Commerce
    url: /providers/tiktok-shop/
  layer: domain
  name: TikTok Shop
  provider: tiktok-shop
  says: lists TikTok Shop as an integration
  source: https://goshippo.com/integrations
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
    mcp: &id053
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id054
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://goshippo.com/carriers
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
    agent_readiness: 31.9
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id055
      status: none
    slug: usps
    status: profiled
    tags: &id056
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: lists USPS as an integration
  source: https://goshippo.com/carriers
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
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 57.8
    mcp: &id057
      status: none
    slug: veho
    status: profiled
    tags: &id058
    - Company
    - Last Mile Delivery
    - Logistics
    - Shipping
    url: /providers/veho/
  layer: domain
  name: Veho
  provider: veho
  says: lists Veho as an integration
  source: https://goshippo.com/carriers
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
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id059
      status: none
    slug: walmart
    status: profiled
    tags: &id060
    - Commerce
    - Fortune 100
    - Retail
    - Walmart
    url: /providers/walmart/
  layer: domain
  name: Walmart
  provider: walmart
  says: lists Walmart as an integration
  source: https://goshippo.com/integrations
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
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id061
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id062
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://goshippo.com/integrations
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
    mcp: &id063
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id064
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://goshippo.com/integrations
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
    mcp: &id065
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id066
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://goshippo.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/shipping-fulfillment/shippo/
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
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id003
  name: Aramex
  slug: aramex
  status: profiled
  tags: *id004
  url: /providers/aramex/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id005
  name: Australia Post
  slug: australia-post
  status: profiled
  tags: *id006
  url: /providers/australia-post/
- agent_band: agent-ready
  agent_readiness: 60.5
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id007
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id008
  url: /providers/bigcommerce/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id009
  name: Canada Post
  slug: canada-post
  status: profiled
  tags: *id010
  url: /providers/canada-post/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id011
  name: Chronopost
  slug: chronopost
  status: profiled
  tags: *id012
  url: /providers/chronopost/
- agent_band: agent-aware
  agent_readiness: 18.1
  band: thin
  in_catalog: true
  kin_score: 30.0
  mcp: *id013
  name: Colissimo
  slug: colissimo
  status: profiled
  tags: *id014
  url: /providers/colissimo/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id015
  name: Correos
  slug: correos
  status: profiled
  tags: *id016
  url: /providers/correos/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id017
  name: Deutsche Post
  slug: deutsche-post
  status: profiled
  tags: *id018
  url: /providers/deutsche-post/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id019
  name: DHL
  slug: dhl
  status: profiled
  tags: *id020
  url: /providers/dhl/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id021
  name: DPD
  slug: dpd
  status: profiled
  tags: *id022
  url: /providers/dpd/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id023
  name: eBay
  slug: ebay
  status: profiled
  tags: *id024
  url: /providers/ebay/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id025
  name: Etsy
  slug: etsy
  status: profiled
  tags: *id026
  url: /providers/etsy/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id027
  name: Evri
  slug: evri
  status: profiled
  tags: *id028
  url: /providers/evri/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id029
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id030
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id031
  name: GLS
  slug: gls-group
  status: profiled
  tags: *id032
  url: /providers/gls-group/
- agent_band: agent-aware
  agent_readiness: 24.0
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id033
  name: Magento 2
  slug: magento
  status: profiled
  tags: *id034
  url: /providers/magento/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id035
  name: Mondial Relay
  slug: mondial-relay
  status: profiled
  tags: *id036
  url: /providers/mondial-relay/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id037
  name: OnTrac
  slug: ontrac
  status: profiled
  tags: *id038
  url: /providers/ontrac/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id039
  name: Pitney Bowes
  slug: pitney-bowes
  status: profiled
  tags: *id040
  url: /providers/pitney-bowes/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id041
  name: Poste Italiane
  slug: poste-italiane
  status: profiled
  tags: *id042
  url: /providers/poste-italiane/
- agent_band: human-only
  agent_readiness: 3.5
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id043
  name: Purolator
  slug: purolator
  status: profiled
  tags: *id044
  url: /providers/purolator/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id045
  name: Royal Mail
  slug: royal-mail
  status: profiled
  tags: *id046
  url: /providers/royal-mail/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id047
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id048
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id049
  name: Square
  slug: square
  status: profiled
  tags: *id050
  url: /providers/square/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id051
  name: TikTok Shop
  slug: tiktok-shop
  status: profiled
  tags: *id052
  url: /providers/tiktok-shop/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id053
  name: UPS
  slug: ups
  status: profiled
  tags: *id054
  url: /providers/ups/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id055
  name: USPS
  slug: usps
  status: profiled
  tags: *id056
  url: /providers/usps/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 57.8
  mcp: *id057
  name: Veho
  slug: veho
  status: profiled
  tags: *id058
  url: /providers/veho/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id059
  name: Walmart
  slug: walmart
  status: profiled
  tags: *id060
  url: /providers/walmart/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id061
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id062
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id063
  name: Wix
  slug: wix
  status: profiled
  tags: *id064
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id065
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id066
  url: /providers/woocommerce/
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
- name: Sendcloud
  rows: 53
  url: /applications/shipping-fulfillment/sendcloud/
sitemap: true
title: 'Shippo: Shipping, Fulfillment & Returns reference app'
---
