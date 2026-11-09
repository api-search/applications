---
access: understanding
agent_layer:
- app: TastyIgniter
  finding: '"APIs for TastyIgniter" and "Webhooks" extensions expose orders to external automation; no own MCP server observed'
  source: https://tastyigniter.com/marketplace/extensions
  tier: declared
apps:
- anchor: tastyigniter
  counts:
    declared: 6
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
  - route: integrations page
    url: https://tastyigniter.com/marketplace/extensions
  - route: source code
    url: https://github.com/tastyigniter/core/tree/master/src/Flame/Geolite/Provider
  - route: source code
    url: https://github.com/tastyigniter/ti-ext-payregister/tree/master/src/Payments
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Authorize.Net
    provider: authorizenet
    says: ships the Authorize.Net SDK or integration code
    source: https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://github.com/tastyigniter/core/tree/master/src/Flame/Geolite/Provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mollie
    provider: mollie
    says: ships the Mollie SDK or integration code
    source: https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    credit: null
    layer: common
    name: Nominatim
    provider: nominatim
    says: ships the Nominatim SDK or integration code
    source: https://github.com/tastyigniter/core/tree/master/src/Flame/Geolite/Provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-payregister/tree/master/src/Payments
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Square
    provider: square
    says: ships the Square SDK or integration code
    source: https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.10
      key: AE-140.50.10
      name: Gift Cards
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    credit: null
    layer: domain
    name: Gift Up!
    provider: gift-up
    says: lists Gift Up! as an integration
    source: https://tastyigniter.com/marketplace/extensions
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shipday
    provider: shipday
    says: lists Shipday as an integration
    source: https://tastyigniter.com/marketplace/extensions
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square POS
    provider: square
    says: lists Square POS as an integration
    source: https://tastyigniter.com/marketplace/extensions
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.50.40
      key: BC-2320.50.40
      name: POS Peripheral Configuration
      url: /capabilities/pos-configuration-management/
      via_parent: POS Configuration Management
    credit: null
    layer: domain
    name: Star Micronics CloudPRNT
    provider: star-micronics
    says: lists Star Micronics CloudPRNT as an integration
    source: https://tastyigniter.com/marketplace/extensions
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: SumUp
    provider: sumup
    says: lists SumUp as an integration
    source: https://tastyigniter.com/marketplace/extensions
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Uber Direct
    provider: uber-direct
    says: lists Uber Direct as an integration
    source: https://tastyigniter.com/marketplace/extensions
    tier: declared
  kind: self-hosted
  name: TastyIgniter
  page: /applications/food-delivery-ordering/tastyigniter/
  slug: tastyigniter
  url: https://github.com/tastyigniter/TastyIgniter
- anchor: enatega-multivendor
  counts:
    declared: 3
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
  - route: documentation
    url: https://github.com/enatega/food-delivery-multivendor
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: common
    name: Google Maps / Places
    provider: google-maps
    says: ships the Google Maps / Places SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Clarity
    provider: microsoft-clarity
    says: ships the Microsoft Clarity SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook login
    provider: facebook
    says: lists Facebook login as an integration
    source: https://github.com/enatega/food-delivery-multivendor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://github.com/enatega/food-delivery-multivendor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://github.com/enatega/food-delivery-multivendor
    tier: declared
  kind: open-source-saas
  name: Enatega Multivendor
  page: /applications/food-delivery-ordering/enatega-multivendor/
  slug: enatega-multivendor
  url: https://github.com/enatega/food-delivery-multivendor
- anchor: chownow
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://get.chownow.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40
      key: AE-120.40
      name: Places & Points of Interest
      url: /capabilities/places-points-of-interest/
      via_parent: null
    credit: null
    layer: domain
    name: Apple Maps
    provider: apple-maps
    says: lists Apple Maps as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clover
    provider: clover
    says: lists Clover as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: DoorDash
    provider: doordash
    says: lists DoorDash as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40
      key: AE-120.40
      name: Places & Points of Interest
      url: /capabilities/places-points-of-interest/
      via_parent: null
    credit: null
    layer: domain
    name: Google (Order with Google)
    provider: google
    says: lists Google (Order with Google) as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Grubhub
    provider: grubhub
    says: lists Grubhub as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Heartland Genius
    provider: heartland-payment-systems
    says: lists Heartland Genius as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Revel
    provider: revel-systems
    says: lists Revel as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: SkyTab (Shift4)
    provider: skytab
    says: lists SkyTab (Shift4) as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Toast
    provider: toast
    says: lists Toast as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Uber Eats
    provider: uber-eats
    says: lists Uber Eats as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40
      key: AE-120.40
      name: Places & Points of Interest
      url: /capabilities/places-points-of-interest/
      via_parent: null
    credit: null
    layer: domain
    name: Yelp
    provider: yelp
    says: lists Yelp as an integration
    source: https://get.chownow.com/integrations/
    tier: declared
  kind: commercial
  name: ChowNow
  page: /applications/food-delivery-ordering/chownow/
  slug: chownow
  url: https://www.chownow.com/
- anchor: shipday
  counts:
    declared: 23
    observed: 0
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
    layer: domain
    name: Zuppler
    provider: zuppler
    says: lists Zuppler as an integration
    source: https://www.shipday.com/integrations
    tier: declared
  kind: commercial
  name: Shipday
  page: /applications/food-delivery-ordering/shipday/
  slug: shipday
  url: https://www.shipday.com/
- anchor: otter
  counts:
    declared: 37
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.tryotter.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    credit: null
    layer: common
    name: 7shifts
    provider: 7shifts
    says: lists 7shifts as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: BentoBox
    provider: bentobox
    says: lists BentoBox as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Caviar
    provider: caviar
    says: lists Caviar as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: ChowNow
    provider: chownow
    says: lists ChowNow as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: ClassPass
    provider: classpass
    says: lists ClassPass as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clover
    provider: clover
    says: lists Clover as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    credit: null
    layer: common
    name: Deputy
    provider: deputy
    says: lists Deputy as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: DoorDash
    provider: doordash
    says: lists DoorDash as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: DoorDash Drive
    provider: doordash-drive
    says: lists DoorDash Drive as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Epos Now
    provider: epos-now
    says: lists Epos Now as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: ezCater
    provider: ezcater
    says: lists ezCater as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Fantuan
    provider: fantuan
    says: lists Fantuan as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: Flipdish
    provider: flipdish
    says: lists Flipdish as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Grubhub
    provider: grubhub
    says: lists Grubhub as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    credit: null
    layer: common
    name: Homebase
    provider: homebase
    says: lists Homebase as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: HungryPanda
    provider: hungrypanda
    says: lists HungryPanda as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: Incentivio
    provider: incentivio
    says: lists Incentivio as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lavu
    provider: lavu
    says: lists Lavu as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lightspeed
    provider: lightspeed
    says: lists Lightspeed as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Loyverse
    provider: loyverse
    says: lists Loyverse as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: Lunchbox
    provider: lunchbox
    says: lists Lunchbox as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    credit: null
    layer: domain
    name: MarketMan
    provider: marketman
    says: lists MarketMan as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nash
    provider: nash
    says: lists Nash as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle Micros
    provider: oracle
    says: lists Oracle Micros as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Postmates
    provider: postmates
    says: lists Postmates as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    credit: null
    layer: domain
    name: Restaurant365
    provider: restaurant365
    says: lists Restaurant365 as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Revel
    provider: revel-systems
    says: lists Revel as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: Ritual
    provider: ritual-co
    says: lists Ritual as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shift4
    provider: shift4
    says: lists Shift4 as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shipday
    provider: shipday
    says: lists Shipday as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Skip the Dishes
    provider: skipthedishes
    says: lists Skip the Dishes as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    credit: null
    layer: domain
    name: Slice
    provider: slice
    says: lists Slice as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Toast
    provider: toast
    says: lists Toast as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Uber Eats
    provider: uber-eats
    says: lists Uber Eats as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    credit: null
    layer: common
    name: When I Work
    provider: when-i-work
    says: lists When I Work as an integration
    source: https://www.tryotter.com/integrations
    tier: declared
  kind: commercial
  name: Otter
  page: /applications/food-delivery-ordering/otter/
  slug: otter
  url: https://www.tryotter.com/
- anchor: upmenu
  counts:
    declared: 32
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.upmenu.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Adyen
    provider: adyen
    says: lists Adyen as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Affirm
    provider: affirm
    says: lists Affirm as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Afterpay
    provider: afterpay
    says: lists Afterpay as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Bancontact
    provider: bancontact
    says: lists Bancontact as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clover
    provider: clover
    says: lists Clover as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: null
    layer: common
    name: CookieYes
    provider: cookieyes
    says: lists CookieYes as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: DoorDash Drive
    provider: doordash-drive
    says: lists DoorDash Drive as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Duda
    provider: duda
    says: lists Duda as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Glovo on Demand
    provider: glovo
    says: lists Glovo on Demand as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Klarna
    provider: klarna
    says: lists Klarna as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lightspeed
    provider: lightspeed
    says: lists Lightspeed as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Meta
    provider: facebook
    says: lists Meta as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: NCR Aloha
    provider: ncr
    says: lists NCR Aloha as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle Simphony
    provider: oracle
    says: lists Oracle Simphony as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayU
    provider: payu
    says: lists PayU as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Przelewy24
    provider: przelewy24
    says: lists Przelewy24 as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Relay
    provider: relay-delivery
    says: lists Relay as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipDay
    provider: shipday
    says: lists ShipDay as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stuart
    provider: stuart
    says: lists Stuart as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Toast
    provider: toast
    says: lists Toast as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Uber Direct
    provider: uber-direct
    says: lists Uber Direct as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wolt Drive
    provider: wolt
    says: lists Wolt Drive as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://www.upmenu.com/integrations/
    tier: declared
  kind: commercial
  name: UpMenu
  page: /applications/food-delivery-ordering/upmenu/
  slug: upmenu
  url: https://www.upmenu.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: food-delivery-ordering
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Food & Drink
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Food & Drink
  store: google-play
  url: https://play.google.com/store/apps/category/FOOD_AND_DRINK
- category: Orders and shipping
  store: shopify-app-store
  url: https://apps.shopify.com/categories
name: Food Delivery & Restaurant Ordering
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: card/online payment gateways at checkout
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: order injection into restaurant POS (Toast, Square, Clover...) is the core integration of every ordering platform
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: on-demand courier dispatch (Uber Direct, DoorDash Drive, Shipday...)
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.10
    key: AE-140.50.10
    name: Gift Cards
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  fit: exact
  layer: domain
  why: restaurant gift cards
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  fit: exact
  layer: common
  why: delivery-zone and address geocoding
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: order status pushes
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: customer sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  fit: exact
  layer: common
  why: address autocomplete via Places
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app analytics / session replay
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error monitoring
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: order alert emails
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  fit: exact
  layer: domain
  why: third-party delivery marketplaces as order channels
- capability:
    attribution: API Evangelist extension
    id: AE-120.40
    key: AE-120.40
    name: Places & Points of Interest
    url: /capabilities/places-points-of-interest/
    via_parent: null
  fit: exact
  layer: domain
  why: restaurant listings on discovery networks (Google, Apple Maps, Yelp)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: general e-commerce storefronts used as order sources
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  fit: exact
  layer: domain
  why: first-party restaurant ordering platforms as order sources
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: ERP order source / accounting
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  fit: exact
  layer: common
  why: staff scheduling fed by order volume
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  fit: exact
  layer: domain
  why: restaurant inventory/purchasing
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: Apple Pay / Google Pay at checkout
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: BNPL at checkout
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: marketing tag management
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: ad pixels
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  fit: exact
  layer: common
  why: cookie consent
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: restaurant website builders embedding ordering
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - ChowNow
      - Otter
      - Shipday
      - TastyIgniter
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp: &id003
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square POS
      slug: square
      sources:
      - https://get.chownow.com/integrations/
      - https://tastyigniter.com/marketplace/extensions
      - https://www.shipday.com/integrations
      status: profiled
      tags: &id004
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - ChowNow
      - Otter
      - Shipday
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: Toast
      slug: toast
      sources:
      - https://get.chownow.com/integrations/
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Food Service
      - Hospitality
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/toast/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Otter
      - Shipday
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 86.5
      mcp:
        status: none
      name: Lightspeed
      slug: lightspeed
      sources:
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Commerce
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/lightspeed/
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Otter
      - Shipday
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle (Simphony)
      slug: oracle
      sources:
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - ChowNow
      - Otter
      - UpMenu
      band: developing
      in_catalog: true
      kin_score: 39.9
      mcp:
        status: none
      name: Clover
      slug: clover
      sources:
      - https://get.chownow.com/integrations/
      - https://www.tryotter.com/integrations
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Payments
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/clover/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Otter
      - Shipday
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Epos Now
      slug: epos-now
      sources:
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Hospitality
      - Payments
      - Point-of-Sale
      - Retail
      tier: declared
      url: /providers/epos-now/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - ChowNow
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: none
      name: Revel
      slug: revel-systems
      sources:
      - https://get.chownow.com/integrations/
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Point-of-Sale
      - Restaurant
      - Retail
      - iPad
      tier: declared
      url: /providers/revel-systems/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - ChowNow
      - Shipday
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        source: https://github.com/globalpayments/mcp-server
        status: verified
      name: Heartland Genius
      slug: heartland-payment-systems
      sources:
      - https://get.chownow.com/integrations/
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - Bill Pay
      - Card Not Present
      - Card Present
      - E-Commerce
      tier: declared
      url: /providers/heartland-payment-systems/
    - agent_band: agent-native
      agent_readiness: 52.4
      apps:
      - Otter
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Shift4
      slug: shift4
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - United States
      tier: declared
      url: /providers/shift4/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Otter
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: none
      name: Loyverse
      slug: loyverse
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Cafe and Restaurant
      - Inventory
      - Point-of-Sale
      - Retail
      tier: declared
      url: /providers/loyverse/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        status: none
      name: NCR Aloha
      slug: ncr
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Banking
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/ncr/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: Lavu
      slug: lavu
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Inventory
      - Payments
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/lavu/
    - agent_band: null
      agent_readiness: null
      apps:
      - ChowNow
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SkyTab (Shift4)
      slug: skytab
      sources:
      - https://get.chownow.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2420.40
      key: last-mile-delivery-operations-management
      name: Last-Mile Delivery Operations Management
      url: /capabilities/last-mile-delivery-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Otter
      - TastyIgniter
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=com.shipday&limit=3
        status: verified
      name: Shipday
      slug: shipday
      sources:
      - https://tastyigniter.com/marketplace/extensions
      - https://www.tryotter.com/integrations
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Delivery
      - Last Mile Delivery
      - Local Delivery
      - Logistics
      tier: declared
      url: /providers/shipday/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Shipday
      - TastyIgniter
      - UpMenu
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        status: none
      name: Uber Direct
      slug: uber-direct
      sources:
      - https://tastyigniter.com/marketplace/extensions
      - https://www.shipday.com/integrations
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Couriers
      - Fulfillment
      - Last Mile Delivery
      - Logistics
      tier: declared
      url: /providers/uber-direct/
    - agent_band: null
      agent_readiness: null
      apps:
      - Otter
      - Shipday
      - UpMenu
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: DoorDash Drive
      slug: doordash-drive
      sources:
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      - https://www.upmenu.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Shipday
      - UpMenu
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Stuart
      slug: stuart
      sources:
      - https://www.shipday.com/integrations
      - https://www.upmenu.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-native
      agent_readiness: 41.8
      apps:
      - Otter
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Nash
      slug: nash
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Company
      - Delivery
      - Last Mile Delivery
      - Logistics
      tier: declared
      url: /providers/nash/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Wolt Drive
      slug: wolt
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Company
      - Food Delivery
      - Last Mile Delivery
      - Marketplace
      tier: declared
      url: /providers/wolt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Shipday
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp: &id001
        status: none
      name: SkipTheDishes
      slug: skipthedishes
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags: &id002
      - Company
      - Couriers
      - Food Delivery
      - Restaurant
      tier: declared
      url: /providers/skipthedishes/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Shipday
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: Zifty
      slug: zifty
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - Company
      - Delivery
      - Logistics
      - Software-as-a-Service
      tier: declared
      url: /providers/zifty/
    - agent_band: null
      agent_readiness: null
      apps:
      - UpMenu
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Glovo on Demand
      slug: glovo
      sources:
      - https://www.upmenu.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - UpMenu
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Relay
      slug: relay-delivery
      sources:
      - https://www.upmenu.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - ChowNow
      - Otter
      - Shipday
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Grubhub
      slug: grubhub
      sources:
      - https://get.chownow.com/integrations/
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Food Delivery
      - Marketplace
      - Online Ordering
      - Restaurant
      tier: declared
      url: /providers/grubhub/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - ChowNow
      - Otter
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: DoorDash
      slug: doordash
      sources:
      - https://get.chownow.com/integrations/
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Delivery
      - Last Mile Delivery
      - Logistics
      - On-Demand
      tier: declared
      url: /providers/doordash/
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - ChowNow
      - Otter
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Uber Eats
      slug: uber-eats
      sources:
      - https://get.chownow.com/integrations/
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Food Delivery
      - Last Mile Delivery
      - Uber Direct
      - Uber Eats
      tier: declared
      url: /providers/uber-eats/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 20.2
      mcp:
        status: none
      name: Postmates
      slug: postmates
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Acquired
      - Couriers
      - Delivery
      - Food Delivery
      tier: declared
      url: /providers/postmates/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 15.9
      mcp:
        status: none
      name: HungryPanda
      slug: hungrypanda
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Company
      - Delivery
      - Food Delivery
      - Marketplace
      tier: declared
      url: /providers/hungrypanda/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 12.1
      mcp:
        status: none
      name: ClassPass
      slug: classpass
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Class Booking
      - Fitness
      - Marketplace
      - Wellness
      tier: declared
      url: /providers/classpass/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: none
      name: ezCater
      slug: ezcater
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Catering
      - Company
      - Food
      - Marketplace
      tier: declared
      url: /providers/ezcater/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: none
      name: Caviar
      slug: caviar
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Company
      - Food Delivery
      - Marketplace
      - Restaurant
      tier: declared
      url: /providers/caviar/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Fantuan
      slug: fantuan
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Food Delivery
      - Mobile App
      - Restaurant Partnerships
      - Takeout
      tier: declared
      url: /providers/fantuan/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp: *id001
      name: Skip the Dishes
      slug: skipthedishes
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/skipthedishes/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.20.20
      key: AE-140.20.20
      name: Online Ordering
      url: /capabilities/cart-checkout/
      via_parent: Cart & Checkout
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.7
      apps:
      - Otter
      - Shipday
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        status: none
      name: Flipdish
      slug: flipdish
      sources:
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Mobile App
      - Online Ordering
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/flipdish/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      - Shipday
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: none
      name: ChowNow
      slug: chownow
      sources:
      - https://www.shipday.com/integrations
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Food and Beverage
      - Online Ordering
      - Restaurant
      - Restaurant Technology
      tier: declared
      url: /providers/chownow/
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - Otter
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        status: none
      name: Incentivio
      slug: incentivio
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Guest Engagement
      - Loyalty
      - Online Ordering
      - Restaurant
      tier: declared
      url: /providers/incentivio/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Otter
      band: thin
      in_catalog: true
      kin_score: 36.7
      mcp:
        status: none
      name: Lunchbox
      slug: lunchbox
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Catering
      - Guest Engagement
      - Online Ordering
      - Restaurant
      tier: declared
      url: /providers/lunchbox/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Shipday
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        source: https://help.otter.ai/api/v2/help_center/en-us/articles/35287607569687.json
        status: verified
      name: Otter
      slug: otter
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - Delivery
      - Online Ordering
      - Order Management
      - Restaurant
      tier: declared
      url: /providers/otter/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Otter
      band: thin
      in_catalog: true
      kin_score: 31.7
      mcp:
        status: none
      name: Slice
      slug: slice
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Local Commerce
      - Online Ordering
      - Pizza
      - Restaurant
      tier: declared
      url: /providers/slice/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Shipday
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: unknown
      name: Zuppler
      slug: zuppler
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - Company
      - Online Ordering
      - RestaurantTech
      - Software-as-a-Service
      tier: declared
      url: /providers/zuppler/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Otter
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: none
      name: BentoBox
      slug: bentobox
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Commerce
      - Online Ordering
      - Restaurant
      - Websites
      tier: declared
      url: /providers/bentobox/
    - agent_band: null
      agent_readiness: null
      apps:
      - Shipday
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: GloriaFood
      slug: gloriafood
      sources:
      - https://www.shipday.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Otter
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Ritual
      slug: ritual-co
      sources:
      - https://www.tryotter.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - Shipday
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-native
      agent_readiness: 49.5
      apps:
      - Shipday
      band: exemplar
      in_catalog: true
      kin_score: 69.9
      mcp: &id005
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags: &id006
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Shipday
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Shipday
      band: developing
      in_catalog: true
      kin_score: 45.4
      mcp:
        status: none
      name: Ecwid
      slug: ecwid
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Online Store
      - Retail
      - Storefront
      tier: declared
      url: /providers/ecwid/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Shipday
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp: &id007
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags: &id008
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40
      key: AE-120.40
      name: Places & Points of Interest
      url: /capabilities/places-points-of-interest/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - ChowNow
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google (Order with Google)
      slug: google
      sources:
      - https://get.chownow.com/integrations/
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-native
      agent_readiness: 53.4
      apps:
      - ChowNow
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://github.com/Yelp/yelp-mcp
        status: verified
      name: Yelp
      slug: yelp
      sources:
      - https://get.chownow.com/integrations/
      status: profiled
      tags:
      - Business Data
      - Local Search
      - Restaurant
      - Reviews
      tier: declared
      url: /providers/yelp/
    - agent_band: null
      agent_readiness: null
      apps:
      - ChowNow
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Apple Maps
      slug: apple-maps
      sources:
      - https://get.chownow.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-530
      key: inventory-management
      name: Inventory Management
      url: /capabilities/inventory-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Otter
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        status: none
      name: Restaurant365
      slug: restaurant365
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Accounting
      - Inventory
      - Invoices
      - Restaurant
      tier: declared
      url: /providers/restaurant365/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: none
      name: MarketMan
      slug: marketman
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Inventory
      - Purchasing
      - Restaurant
      - Supply Chain
      tier: declared
      url: /providers/marketman/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Shipday
      band: thin
      in_catalog: true
      kin_score: 27.9
      mcp:
        status: none
      name: Odoo
      slug: odoo
      sources:
      - https://www.shipday.com/integrations
      status: profiled
      tags:
      - Business Applications
      - CRM
      - ERP
      - Open Source
      tier: declared
      url: /providers/odoo/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.10
      key: AE-140.50.10
      name: Gift Cards
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - TastyIgniter
      band: emerging
      in_catalog: true
      kin_score: 25.4
      mcp:
        status: unknown
      name: Gift Up!
      slug: gift-up
      sources:
      - https://tastyigniter.com/marketplace/extensions
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Gift Cards
      - Payments
      tier: declared
      url: /providers/gift-up/
  - capability:
      attribution: Turbo EA
      id: BC-2320.50.40
      key: BC-2320.50.40
      name: POS Peripheral Configuration
      url: /capabilities/pos-configuration-management/
      via_parent: POS Configuration Management
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - TastyIgniter
      band: emerging
      in_catalog: true
      kin_score: 12.2
      mcp:
        status: none
      name: Star Micronics CloudPRNT
      slug: star-micronics
      sources:
      - https://tastyigniter.com/marketplace/extensions
      status: profiled
      tags:
      - Company
      - Hardware
      - Point-of-Sale
      - Printing
      tier: declared
      url: /providers/star-micronics/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Enatega Multivendor
      - Otter
      - TastyIgniter
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      - https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Enatega Multivendor
      - TastyIgniter
      - UpMenu
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/enatega/food-delivery-multivendor
      - https://github.com/tastyigniter/ti-ext-payregister/tree/master/src/Payments
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - TastyIgniter
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp: *id003
      name: Square
      slug: square
      sources:
      - https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/square/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - TastyIgniter
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - TastyIgniter
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.Net
      slug: authorizenet
      sources:
      - https://raw.githubusercontent.com/tastyigniter/ti-ext-payregister/master/composer.json
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: agent-native
      agent_readiness: 43.7
      apps:
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Adyen/adyen-mcp
        status: verified
      name: Adyen
      slug: adyen
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Agentic Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/adyen/
    - agent_band: agent-native
      agent_readiness: 50.8
      apps:
      - UpMenu
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        status: none
      name: Bancontact
      slug: bancontact
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Banking
      - Belgium
      - Debit Cards
      - E-Commerce
      tier: declared
      url: /providers/bancontact/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - TastyIgniter
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        source: https://github.com/sumup/sumup-mcp
        status: verified
      name: SumUp
      slug: sumup
      sources:
      - https://tastyigniter.com/marketplace/extensions
      status: profiled
      tags:
      - Card Reader
      - Checkout
      - Payments
      - Point-of-Sale
      tier: declared
      url: /providers/sumup/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - UpMenu
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/payu-intrepos/payu-developer-mcp
        status: verified
      name: PayU
      slug: payu
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Financial Services
      - Fintech
      - Payment Processing
      - Payments
      tier: declared
      url: /providers/payu/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: none
      name: Przelewy24
      slug: przelewy24
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - BLIK
      - Bank Transfers
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/przelewy24/
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 49.5
      apps:
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 69.9
      mcp: *id005
      name: Squarespace
      slug: squarespace
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - UpMenu
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        source: https://developer.duda.co/docs/duda-mcp-server
        status: documented
      name: Duda
      slug: duda
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Agencies
      - Software-as-a-Service
      - Website Builder
      - White Label
      tier: declared
      url: /providers/duda/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp: *id007
      name: Wix
      slug: wix
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/wix/
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Otter
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Deputy
      slug: deputy
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Employee Scheduling
      - Time and Attendance
      - Timesheets
      - Workforce Management
      tier: declared
      url: /providers/deputy/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Otter
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        status: none
      name: 7shifts
      slug: 7shifts
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Employee Scheduling
      - Restaurant
      - Scheduling
      - Workforce Management
      tier: declared
      url: /providers/7shifts/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Otter
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: When I Work
      slug: when-i-work
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Employee Scheduling
      - Time Clock
      - Time Tracking
      - Workforce Management
      tier: declared
      url: /providers/when-i-work/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Otter
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: none
      name: Homebase
      slug: homebase
      sources:
      - https://www.tryotter.com/integrations
      status: profiled
      tags:
      - Human Resources
      - Payroll
      - Scheduling
      - Time Tracking
      tier: declared
      url: /providers/homebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-native
      agent_readiness: 46.0
      apps:
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        status: none
      name: Klarna
      slug: klarna
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Cards
      - Fintech
      - Payments
      tier: declared
      url: /providers/klarna/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        status: none
      name: Affirm
      slug: affirm
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Fintech
      - Lending
      - Payments
      tier: declared
      url: /providers/affirm/
    - agent_band: agent-aware
      agent_readiness: 13.0
      apps:
      - UpMenu
      band: minimal
      in_catalog: true
      kin_score: 9.3
      mcp:
        status: none
      name: Afterpay
      slug: afterpay
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/afterpay/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Enatega Multivendor
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://github.com/microsoft/clarity-mcp-server
        status: verified
      name: Microsoft Clarity
      slug: microsoft-clarity
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags:
      - Analytics
      - Heatmaps
      - Session Recording
      - Web Analytics
      tier: observed
      url: /providers/microsoft-clarity/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Enatega Multivendor
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - UpMenu
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Enatega Multivendor
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Enatega Multivendor
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Enatega Multivendor
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: &id009
        status: none
      name: Facebook login
      slug: facebook
      sources:
      - https://github.com/enatega/food-delivery-multivendor
      status: profiled
      tags: &id010
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - UpMenu
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - UpMenu
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - TastyIgniter
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp: &id011
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://github.com/tastyigniter/core/tree/master/src/Flame/Geolite/Provider
      status: profiled
      tags: &id012
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - TastyIgniter
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/tastyigniter/core/tree/master/src/Flame/Geolite/Provider
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - UpMenu
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: CookieYes
      slug: cookieyes
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Company
      - Consent Management
      - GDPR
      - Privacy
      tier: declared
      url: /providers/cookieyes/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - UpMenu
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id009
      name: Meta
      slug: facebook
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags: *id010
      tier: declared
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Enatega Multivendor
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Enatega Multivendor
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp: *id011
      name: Google Maps / Places
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Enatega Multivendor
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/enatega/food-delivery-multivendor/main/enatega-multivendor-app/package.json
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - UpMenu
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://www.upmenu.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Enatega Multivendor
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/enatega/food-delivery-multivendor
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
  layer: common
summary:
  coverage_pct: 90.9
  declared_only: 75
  distinct_providers: 88
  in_catalog: 80
  mcp:
    documented: 1
    none: 50
    unchecked: 8
    verified: 25
  mcp_verified: 25
  mean_kin_score: 42.9
  observed: 13
  queued: 8
  reference_apps: 6
title: 'Food Delivery & Restaurant Ordering: application blueprint'
---
