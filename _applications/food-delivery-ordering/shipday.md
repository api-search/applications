---
app: Shipday
app_slug: shipday
app_url: https://www.shipday.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.100.20
  key: AE-140.100.20
  layer: domain
  name: Food Delivery
  providers:
  - Grubhub Connect
  url: /capabilities/quick-local-commerce/
  via_parent: Quick & Local Commerce
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Odoo
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Ecwid
  - Shopify
  - Squarespace
  - Wix
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-2420.40
  key: last-mile-delivery-operations-management
  layer: domain
  name: Last-Mile Delivery Operations Management
  providers:
  - DoorDash Drive
  - SkipTheDishes
  - Stuart
  - Uber (Direct)
  - Zifty
  url: /capabilities/last-mile-delivery-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.20.20
  key: AE-140.20.20
  layer: domain
  name: Online Ordering
  providers:
  - ChowNow
  - Flipdish
  - GloriaFood
  - Otter
  - Zuppler
  url: /capabilities/cart-checkout/
  via_parent: Cart & Checkout
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Epos Now
  - Heartland
  - Lightspeed
  - Oracle (Simphony)
  - Square
  - Toast
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
category:
  id: food-delivery-ordering
  name: Food Delivery & Restaurant Ordering
  url: /applications/food-delivery-ordering/
counts:
  declared: 23
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.shipday.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id001
      status: none
    slug: chownow
    status: profiled
    tags: &id002
    - Food and Beverage
    - Online Ordering
    - Restaurant
    - Restaurant Technology
    url: /providers/chownow/
  layer: domain
  name: ChowNow
  provider: chownow
  says: lists ChowNow as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: doordash-drive
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: DoorDash Drive
  provider: doordash-drive
  says: lists DoorDash Drive as an integration
  source: https://www.shipday.com/integrations
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
    agent_readiness: 20.1
    band: developing
    in_catalog: true
    kin_score: 45.4
    mcp: &id005
      status: none
    slug: ecwid
    status: profiled
    tags: &id006
    - E-Commerce
    - Online Store
    - Retail
    - Storefront
    url: /providers/ecwid/
  layer: domain
  name: Ecwid
  provider: ecwid
  says: lists Ecwid as an integration
  source: https://www.shipday.com/integrations
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
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id007
      status: none
    slug: epos-now
    status: profiled
    tags: &id008
    - Hospitality
    - Payments
    - Point-of-Sale
    - Retail
    url: /providers/epos-now/
  layer: domain
  name: Epos Now
  provider: epos-now
  says: lists Epos Now as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.7
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id009
      status: none
    slug: flipdish
    status: profiled
    tags: &id010
    - Mobile App
    - Online Ordering
    - Point-of-Sale
    - Restaurant
    url: /providers/flipdish/
  layer: domain
  name: Flipdish
  provider: flipdish
  says: lists Flipdish as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: gloriafood
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: GloriaFood
  provider: gloriafood
  says: lists GloriaFood as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id013
      status: none
    slug: grubhub
    status: profiled
    tags: &id014
    - Food Delivery
    - Marketplace
    - Online Ordering
    - Restaurant
    url: /providers/grubhub/
  layer: domain
  name: Grubhub Connect
  provider: grubhub
  says: lists Grubhub Connect as an integration
  source: https://www.shipday.com/integrations
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
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id015
      source: https://github.com/globalpayments/mcp-server
      status: verified
    slug: heartland-payment-systems
    status: profiled
    tags: &id016
    - Bill Pay
    - Card Not Present
    - Card Present
    - E-Commerce
    url: /providers/heartland-payment-systems/
  layer: domain
  name: Heartland
  provider: heartland-payment-systems
  says: lists Heartland as an integration
  source: https://www.shipday.com/integrations
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 86.5
    mcp: &id017
      status: none
    slug: lightspeed
    status: profiled
    tags: &id018
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.shipday.com/integrations
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id019
      status: none
    slug: odoo
    status: profiled
    tags: &id020
    - Business Applications
    - CRM
    - ERP
    - Open Source
    url: /providers/odoo/
  layer: domain
  name: Odoo
  provider: odoo
  says: lists Odoo as an integration
  source: https://www.shipday.com/integrations
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
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id021
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id022
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle (Simphony)
  provider: oracle
  says: lists Oracle (Simphony) as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id023
      source: https://help.otter.ai/api/v2/help_center/en-us/articles/35287607569687.json
      status: verified
    slug: otter
    status: profiled
    tags: &id024
    - Delivery
    - Online Ordering
    - Order Management
    - Restaurant
    url: /providers/otter/
  layer: domain
  name: Otter
  provider: otter
  says: lists Otter as an integration
  source: https://www.shipday.com/integrations
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
    mcp: &id025
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id026
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id027
      status: none
    slug: skipthedishes
    status: profiled
    tags: &id028
    - Company
    - Couriers
    - Food Delivery
    - Restaurant
    url: /providers/skipthedishes/
  layer: domain
  name: SkipTheDishes
  provider: skipthedishes
  says: lists SkipTheDishes as an integration
  source: https://www.shipday.com/integrations
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
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id029
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id030
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.shipday.com/integrations
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
    mcp: &id031
      status: none
    slug: squarespace
    status: profiled
    tags: &id032
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
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
    slug: stuart
    status: queued for profiling
    tags: &id034 []
    url: null
  layer: domain
  name: Stuart
  provider: stuart
  says: lists Stuart as an integration
  source: https://www.shipday.com/integrations
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
    agent_readiness: 39.6
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id035
      status: none
    slug: toast
    status: profiled
    tags: &id036
    - Food Service
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/toast/
  layer: domain
  name: Toast
  provider: toast
  says: lists Toast as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.1
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id037
      status: none
    slug: uber-direct
    status: profiled
    tags: &id038
    - Couriers
    - Fulfillment
    - Last Mile Delivery
    - Logistics
    url: /providers/uber-direct/
  layer: domain
  name: Uber (Direct)
  provider: uber-direct
  says: lists Uber (Direct) as an integration
  source: https://www.shipday.com/integrations
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
    mcp: &id039
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id040
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://www.shipday.com/integrations
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
    mcp: &id041
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id042
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id043
      status: unknown
    slug: zifty
    status: profiled
    tags: &id044
    - Company
    - Delivery
    - Logistics
    - Software-as-a-Service
    url: /providers/zifty/
  layer: domain
  name: Zifty
  provider: zifty
  says: lists Zifty as an integration
  source: https://www.shipday.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id045
      status: unknown
    slug: zuppler
    status: profiled
    tags: &id046
    - Company
    - Online Ordering
    - RestaurantTech
    - Software-as-a-Service
    url: /providers/zuppler/
  layer: domain
  name: Zuppler
  provider: zuppler
  says: lists Zuppler as an integration
  source: https://www.shipday.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/food-delivery-ordering/shipday/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id001
  name: ChowNow
  slug: chownow
  status: profiled
  tags: *id002
  url: /providers/chownow/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: DoorDash Drive
  slug: doordash-drive
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-aware
  agent_readiness: 20.1
  band: developing
  in_catalog: true
  kin_score: 45.4
  mcp: *id005
  name: Ecwid
  slug: ecwid
  status: profiled
  tags: *id006
  url: /providers/ecwid/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id007
  name: Epos Now
  slug: epos-now
  status: profiled
  tags: *id008
  url: /providers/epos-now/
- agent_band: agent-ready
  agent_readiness: 42.7
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id009
  name: Flipdish
  slug: flipdish
  status: profiled
  tags: *id010
  url: /providers/flipdish/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: GloriaFood
  slug: gloriafood
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-ready
  agent_readiness: 47.8
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id013
  name: Grubhub Connect
  slug: grubhub
  status: profiled
  tags: *id014
  url: /providers/grubhub/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id015
  name: Heartland
  slug: heartland-payment-systems
  status: profiled
  tags: *id016
  url: /providers/heartland-payment-systems/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 86.5
  mcp: *id017
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id018
  url: /providers/lightspeed/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id019
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id020
  url: /providers/odoo/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id021
  name: Oracle (Simphony)
  slug: oracle
  status: profiled
  tags: *id022
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id023
  name: Otter
  slug: otter
  status: profiled
  tags: *id024
  url: /providers/otter/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id025
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id026
  url: /providers/shopify/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id027
  name: SkipTheDishes
  slug: skipthedishes
  status: profiled
  tags: *id028
  url: /providers/skipthedishes/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id029
  name: Square
  slug: square
  status: profiled
  tags: *id030
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 69.9
  mcp: *id031
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id032
  url: /providers/squarespace/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id033
  name: Stuart
  slug: stuart
  status: queued for profiling
  tags: *id034
  url: null
- agent_band: agent-ready
  agent_readiness: 39.6
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id035
  name: Toast
  slug: toast
  status: profiled
  tags: *id036
  url: /providers/toast/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id037
  name: Uber (Direct)
  slug: uber-direct
  status: profiled
  tags: *id038
  url: /providers/uber-direct/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id039
  name: Wix
  slug: wix
  status: profiled
  tags: *id040
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id041
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id042
  url: /providers/woocommerce/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id043
  name: Zifty
  slug: zifty
  status: profiled
  tags: *id044
  url: /providers/zifty/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id045
  name: Zuppler
  slug: zuppler
  status: profiled
  tags: *id046
  url: /providers/zuppler/
siblings:
- name: ChowNow
  rows: 12
  url: /applications/food-delivery-ordering/chownow/
- name: Enatega Multivendor
  rows: 11
  url: /applications/food-delivery-ordering/enatega-multivendor/
- name: Otter
  rows: 37
  url: /applications/food-delivery-ordering/otter/
- name: TastyIgniter
  rows: 13
  url: /applications/food-delivery-ordering/tastyigniter/
- name: UpMenu
  rows: 32
  url: /applications/food-delivery-ordering/upmenu/
sitemap: true
title: 'Shipday: Food Delivery & Restaurant Ordering reference app'
---
