---
access: understanding
agent_layer: []
apps:
- anchor: qloapps
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: source code
    url: https://github.com/Qloapps/QloApps/tree/develop/modules
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Duitku
    provider: duitku
    says: ships the Duitku SDK or integration code
    source: https://github.com/Qloapps/QloApps/tree/develop/modules/qloduitkupayment
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Hotel Center
    provider: google
    says: ships the Google Hotel Center SDK or integration code
    source: https://github.com/Qloapps/QloApps/tree/develop/modules/qlogooglehotelconnector
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/Qloapps/QloApps/tree/develop/modules/qlopaypalcommerce
    tier: observed
  kind: self-hosted
  name: QloApps
  page: /applications/hospitality-restaurant-ops/qloapps/
  slug: qloapps
  url: https://github.com/Qloapps/QloApps
- anchor: tastyigniter
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/tastyigniter/ti-ext-broadcast/blob/master/composer.json
  - route: dependency manifest
    url: https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
  - route: dependency manifest
    url: https://github.com/tastyigniter/ti-ext-socialite/blob/master/composer.json
  - route: source code
    url: https://github.com/tastyigniter/ti-ext-payregister/tree/master/src/Payments
  - route: source code
    url: https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Ably
    provider: ably
    says: ships the Ably SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-broadcast/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Authorize.Net
    provider: authorizenet
    says: ships the Authorize.Net SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
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
    source: https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mollie
    provider: mollie
    says: ships the Mollie SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-payregister/tree/master/src/Payments/PaypalExpress.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-broadcast/blob/master/composer.json
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
    source: https://github.com/tastyigniter/ti-ext-socialite/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: ships the Square SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
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
    name: Twitter / X
    provider: x
    says: ships the Twitter / X SDK or integration code
    source: https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
    tier: observed
  kind: self-hosted
  name: TastyIgniter
  page: /applications/hospitality-restaurant-ops/tastyigniter/
  slug: tastyigniter
  url: https://github.com/tastyigniter/TastyIgniter
- anchor: 7shifts
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.7shifts.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aloha (NCR Voyix)
    provider: ncr
    says: lists Aloha (NCR Voyix) as an integration
    source: https://www.7shifts.com/integrations/
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
    name: Bypass
    provider: bypass
    says: lists Bypass as an integration
    source: https://www.7shifts.com/integrations/
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
    name: CAKE POS
    provider: cake-pos
    says: lists CAKE POS as an integration
    source: https://www.7shifts.com/integrations/
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
    source: https://www.7shifts.com/integrations/
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
    name: GoTab
    provider: gotab
    says: lists GoTab as an integration
    source: https://www.7shifts.com/integrations/
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
    source: https://www.7shifts.com/integrations/
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
    name: Oracle MICROS 3700
    provider: oracle
    says: lists Oracle MICROS 3700 as an integration
    source: https://www.7shifts.com/integrations/
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
    name: Qu POS
    provider: qu
    says: lists Qu POS as an integration
    source: https://www.7shifts.com/integrations/
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
    name: Revel Systems
    provider: revel-systems
    says: lists Revel Systems as an integration
    source: https://www.7shifts.com/integrations/
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
    source: https://www.7shifts.com/integrations/
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
    source: https://www.7shifts.com/integrations/
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
    name: TouchBistro
    provider: touchbistro
    says: lists TouchBistro as an integration
    source: https://www.7shifts.com/integrations/
    tier: declared
  kind: commercial
  name: 7shifts
  page: /applications/hospitality-restaurant-ops/7shifts/
  slug: 7shifts
  url: https://www.7shifts.com/
- anchor: marketman
  counts:
    declared: 31
    observed: 0
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
    layer: domain
    name: Zenchef
    provider: zenchef
    says: lists Zenchef as an integration
    source: https://www.marketman.com/integrations
    tier: declared
  kind: commercial
  name: MarketMan
  page: /applications/hospitality-restaurant-ops/marketman/
  slug: marketman
  url: https://www.marketman.com/
- anchor: mews
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.mews.com/en/marketplace
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Abacus (Swiss ERP)
    provider: abacus-ch
    says: lists Abacus (Swiss ERP) as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4040.10
      key: guest-profile-identity-management
      name: Guest Profile & Identity Management
      url: /capabilities/guest-profile-identity-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alliants
    provider: alliants
    says: lists Alliants as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amadeus iHotelier
    provider: amadeus
    says: lists Amadeus iHotelier as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: BEONX
    provider: beonx
    says: lists BEONX as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Booking.com
    provider: booking-com
    says: lists Booking.com as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4060.10.20
      key: BC-4060.10.20
      name: Check-In Operations
      url: /capabilities/front-office-operations/
      via_parent: Front Office Operations
    credit: null
    layer: domain
    name: Chekin
    provider: chekin
    says: lists Chekin as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Expedia
    provider: expedia-group
    says: lists Expedia as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: profitize
    provider: profitize
    says: lists profitize as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: SiteMinder
    provider: siteminder
    says: lists SiteMinder as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4020
      key: reservation-booking-management
      name: Reservation & Booking Management
      url: /capabilities/reservation-booking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Spalopia
    provider: spalopia
    says: lists Spalopia as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tripadvisor
    provider: tripadvisor
    says: lists Tripadvisor as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  kind: commercial
  name: Mews
  page: /applications/hospitality-restaurant-ops/mews/
  slug: mews
  url: https://www.mews.com/
- anchor: cloudbeds
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.cloudbeds.com/integrations/
  - route: integrations page
    url: https://www.cloudbeds.com/marketplace/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Airbnb
    provider: airbnb
    says: lists Airbnb as an integration
    source: https://www.cloudbeds.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Booking.com
    provider: booking-com
    says: lists Booking.com as an integration
    source: https://www.cloudbeds.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Expedia
    provider: expedia-group
    says: lists Expedia as an integration
    source: https://www.cloudbeds.com/marketplace/
    tier: declared
  kind: commercial
  name: Cloudbeds
  page: /applications/hospitality-restaurant-ops/cloudbeds/
  slug: cloudbeds
  url: https://www.cloudbeds.com/
- anchor: apaleo
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: integrations page
    url: https://store.apaleo.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: Customer Alliance
    provider: customer-alliance
    says: lists Customer Alliance as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: FLYR Hospitality
    provider: flyr
    says: lists FLYR Hospitality as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: happyhotel
    provider: happyhotel
    says: lists happyhotel as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4060.10.20
      key: BC-4060.10.20
      name: Check-In Operations
      url: /capabilities/front-office-operations/
      via_parent: Front Office Operations
    credit: null
    layer: domain
    name: LIKE MAGIC
    provider: like-magic
    says: lists LIKE MAGIC as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4040.10
      key: guest-profile-identity-management
      name: Guest Profile & Identity Management
      url: /capabilities/guest-profile-identity-management/
      via_parent: null
    credit: null
    layer: domain
    name: umnify
    provider: umnify
    says: lists umnify as an integration
    source: https://store.apaleo.com/
    tier: declared
  kind: commercial
  name: apaleo
  page: /applications/hospitality-restaurant-ops/apaleo/
  slug: apaleo
  url: https://apaleo.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: hospitality-restaurant-ops
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Food & Drink
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: All apps
  store: mews-marketplace
  url: https://www.mews.com/en/marketplace
- category: All apps
  store: apaleo-store
  url: https://store.apaleo.com/
name: Hotel & Restaurant Operations
needs:
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: restaurant POS feeds labour, inventory and costing tools
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: online ordering and hotel booking payments
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: OTA connectivity for hotel PMS
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  fit: exact
  layer: domain
  why: metasearch and GDS/CRS distribution
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  fit: exact
  layer: domain
  why: hotel revenue management systems
- capability:
    attribution: Turbo EA
    id: BC-4070.20
    key: f-b-procurement-inventory
    name: F&B Procurement & Inventory
    url: /capabilities/f-b-procurement-inventory/
    via_parent: null
  fit: exact
  layer: domain
  why: foodservice distributor ordering
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: accounting sync
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reviews and guest feedback
- capability:
    attribution: Turbo EA
    id: BC-4040.10
    key: guest-profile-identity-management
    name: Guest Profile & Identity Management
    url: /capabilities/guest-profile-identity-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: guest engagement and CRM (check-in rows are gap)
- capability:
    attribution: Turbo EA
    id: BC-4020
    key: reservation-booking-management
    name: Reservation & Booking Management
    url: /capabilities/reservation-booking-management/
    via_parent: null
  fit: exact
  layer: domain
  why: table and spa reservations
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  fit: exact
  layer: domain
  why: staff scheduling
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: restaurant analytics
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: guest sign-in for online ordering
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: live order/kitchen updates over websockets
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
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - 7shifts
      - MarketMan
      band: exemplar
      in_catalog: true
      kin_score: 86.5
      mcp:
        status: none
      name: Lightspeed
      slug: lightspeed
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Commerce
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/lightspeed/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - 7shifts
      - MarketMan
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp: &id001
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags: &id002
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - 7shifts
      - MarketMan
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle MICROS 3700
      slug: oracle
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - 7shifts
      - MarketMan
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: Toast
      slug: toast
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Food Service
      - Hospitality
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/toast/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - 7shifts
      - MarketMan
      band: developing
      in_catalog: true
      kin_score: 39.9
      mcp:
        status: none
      name: Clover
      slug: clover
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Payments
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/clover/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - 7shifts
      - MarketMan
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        status: none
      name: Aloha (NCR Voyix)
      slug: ncr
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Banking
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/ncr/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - 7shifts
      - MarketMan
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: none
      name: Revel Systems
      slug: revel-systems
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
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
      - 7shifts
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: none
      name: TouchBistro
      slug: touchbistro
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Hospitality
      - Payments
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/touchbistro/
    - agent_band: null
      agent_readiness: null
      apps:
      - 7shifts
      - MarketMan
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Qu POS
      slug: qu
      sources:
      - https://www.7shifts.com/integrations/
      - https://www.marketman.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-native
      agent_readiness: 52.0
      apps:
      - MarketMan
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        status: none
      name: Revolut POS
      slug: revolut
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Banking
      - Company
      - Fintech
      - Payments
      tier: declared
      url: /providers/revolut/
    - agent_band: agent-native
      agent_readiness: 52.4
      apps:
      - MarketMan
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Shift4
      slug: shift4
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - United States
      tier: declared
      url: /providers/shift4/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - MarketMan
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        source: https://github.com/sumup/sumup-mcp
        status: verified
      name: SumUp
      slug: sumup
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Card Reader
      - Checkout
      - Payments
      - Point-of-Sale
      tier: declared
      url: /providers/sumup/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - MarketMan
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        source: https://help.otter.ai/api/v2/help_center/en-us/articles/35287607569687.json
        status: verified
      name: Otter
      slug: otter
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Delivery
      - Online Ordering
      - Order Management
      - Restaurant
      tier: declared
      url: /providers/otter/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - MarketMan
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: Lavu
      slug: lavu
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Inventory
      - Payments
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/lavu/
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - MarketMan
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: unknown
      name: Tabit
      slug: tabit
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Hospitality
      - Ordering
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/tabit/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - 7shifts
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: unknown
      name: CAKE POS
      slug: cake-pos
      sources:
      - https://www.7shifts.com/integrations/
      status: profiled
      tags:
      - Company
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/cake-pos/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 8.8
      mcp:
        status: unknown
      name: Squirrel Systems
      slug: squirrel-systems
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Digital Ordering
      - Hospitality
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/squirrel-systems/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp:
        status: unknown
      name: Silverware
      slug: silverware
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Hospitality
      - Hotels
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/silverware/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unknown
      name: Redcat
      slug: redcat
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Hospitality
      - Loyalty
      - Ordering
      - RestaurantTech
      tier: declared
      url: /providers/redcat/
    - agent_band: null
      agent_readiness: null
      apps:
      - 7shifts
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Bypass
      slug: bypass
      sources:
      - https://www.7shifts.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - 7shifts
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: GoTab
      slug: gotab
      sources:
      - https://www.7shifts.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - QloApps
      - TastyIgniter
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/Qloapps/QloApps/tree/develop/modules/qlopaypalcommerce
      - https://github.com/tastyigniter/ti-ext-payregister/tree/master/src/Payments/PaypalExpress.php
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - TastyIgniter
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - TastyIgniter
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp: *id001
      name: Square
      slug: square
      sources:
      - https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
      status: profiled
      tags: *id002
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
      - https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
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
      - https://github.com/tastyigniter/ti-ext-payregister/blob/master/composer.json
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - QloApps
      band: emerging
      in_catalog: true
      kin_score: 19.8
      mcp:
        status: unknown
      name: Duitku
      slug: duitku
      sources:
      - https://github.com/Qloapps/QloApps/tree/develop/modules/qloduitkupayment
      status: profiled
      tags:
      - Company
      - Fintech
      - Indonesia
      - Payments
      tier: observed
      url: /providers/duitku/
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Cloudbeds
      - Mews
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        status: none
      name: Booking.com
      slug: booking-com
      sources:
      - https://www.cloudbeds.com/marketplace/
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Accommodation
      - Booking
      - Hospitality
      - Travel
      tier: declared
      url: /providers/booking-com/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Cloudbeds
      - Mews
      band: thin
      in_catalog: true
      kin_score: 34.8
      mcp:
        source: https://github.com/ExpediaGroup/expedia-travel-recommendations-mcp
        status: verified
      name: Expedia
      slug: expedia-group
      sources:
      - https://www.cloudbeds.com/marketplace/
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Flights
      - Hotels
      - Lodging
      - Travel
      tier: declared
      url: /providers/expedia-group/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Cloudbeds
      band: developing
      in_catalog: true
      kin_score: 44.8
      mcp:
        status: none
      name: Airbnb
      slug: airbnb
      sources:
      - https://www.cloudbeds.com/marketplace/
      status: profiled
      tags:
      - Airbnb
      - Hospitality
      - Reservations
      - Travel
      tier: declared
      url: /providers/airbnb/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Mews
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp:
        status: none
      name: SiteMinder
      slug: siteminder
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Booking Engine
      - Channel Manager
      - Hospitality
      - Hotel Distribution
      tier: declared
      url: /providers/siteminder/
  - capability:
      attribution: Turbo EA
      id: BC-4070.20
      key: f-b-procurement-inventory
      name: F&B Procurement & Inventory
      url: /capabilities/f-b-procurement-inventory/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - MarketMan
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        status: unknown
      name: Sysco
      slug: sysco
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Food Distribution
      - Food Service
      - Fortune 100
      - Supply Chain
      tier: declared
      url: /providers/sysco/
    - agent_band: agent-aware
      agent_readiness: 6.5
      apps:
      - MarketMan
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: none
      name: Gordon Food Service
      slug: gordon-food-service
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - B2B
      - Company
      - Food Distribution
      - Logistics
      tier: declared
      url: /providers/gordon-food-service/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - MarketMan
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: unknown
      name: US Foods
      slug: us-foods
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Distribution
      - Food Service
      - Fortune 500
      - Supply Chain
      tier: declared
      url: /providers/us-foods/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: unknown
      name: WebstaurantStore
      slug: webstaurantstore
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Food Service
      - Restaurant Supplies
      tier: declared
      url: /providers/webstaurantstore/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unknown
      name: Shamrock Foods
      slug: shamrock-foods
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Company
      - Dairy
      - Distributor
      - Food Service
      tier: declared
      url: /providers/shamrock-foods/
    - agent_band: null
      agent_readiness: null
      apps:
      - MarketMan
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Performance Foodservice
      slug: performance-food-group
      sources:
      - https://www.marketman.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.3
      apps:
      - MarketMan
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - MarketMan
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mews
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: Abacus (Swiss ERP)
      slug: abacus-ch
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Company
      - ERP
      - Finance
      - Human Resources
      tier: declared
      url: /providers/abacus-ch/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 2.8
      mcp:
        status: unknown
      name: Paperchase
      slug: paperchase
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/paperchase/
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - apaleo
      band: emerging
      in_catalog: true
      kin_score: 18.9
      mcp:
        status: none
      name: happyhotel
      slug: happyhotel
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Hospitality
      - Hotels
      - Revenue Management
      - Software-as-a-Service
      tier: declared
      url: /providers/happyhotel/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - Mews
      band: emerging
      in_catalog: true
      kin_score: 11.9
      mcp:
        source: https://beonx.com
        status: documented
      name: BEONX
      slug: beonx
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Hospitality
      - Revenue Management
      tier: declared
      url: /providers/beonx/
    - agent_band: null
      agent_readiness: null
      apps:
      - apaleo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: FLYR Hospitality
      slug: flyr
      sources:
      - https://store.apaleo.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Mews
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: profitize
      slug: profitize
      sources:
      - https://www.mews.com/en/marketplace
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - MarketMan
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Tenzo
      slug: tenzo
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Company
      - Restaurant
      tier: declared
      url: /providers/tenzo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MarketMan
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: unknown
      name: Wenodo
      slug: wenodo
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Accounting
      - Hospitality
      - Payroll
      - Workforce
      tier: declared
      url: /providers/wenodo/
  - capability:
      attribution: Turbo EA
      id: BC-4060.10.20
      key: BC-4060.10.20
      name: Check-In Operations
      url: /capabilities/front-office-operations/
      via_parent: Front Office Operations
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - apaleo
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        status: unknown
      name: LIKE MAGIC
      slug: like-magic
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Company
      - Guest Experience
      - Hospitality
      - Technology
      tier: declared
      url: /providers/like-magic/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Mews
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: unknown
      name: Chekin
      slug: chekin
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Check-in
      - Compliance
      - Hospitality
      - SDK
      tier: declared
      url: /providers/chekin/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.0
      apps:
      - apaleo
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        status: none
      name: Customer Alliance
      slug: customer-alliance
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Company
      - Hospitality
      - Review Management
      - Software-as-a-Service
      tier: declared
      url: /providers/customer-alliance/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Mews
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: none
      name: Tripadvisor
      slug: tripadvisor
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Attractions
      - Hospitality
      - Hotels
      - Restaurant
      tier: declared
      url: /providers/tripadvisor/
  - capability:
      attribution: Turbo EA
      id: BC-4040.10
      key: guest-profile-identity-management
      name: Guest Profile & Identity Management
      url: /capabilities/guest-profile-identity-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mews
      band: minimal
      in_catalog: true
      kin_score: 10.4
      mcp:
        status: none
      name: Alliants
      slug: alliants
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Company
      - DigitalKeys
      - Hospitality
      - Software-as-a-Service
      tier: declared
      url: /providers/alliants/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - apaleo
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unknown
      name: umnify
      slug: umnify
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - German Market
      - Hospitality
      - Hotel Management
      - Software
      tier: declared
      url: /providers/umnify/
  - capability:
      attribution: Turbo EA
      id: BC-4020
      key: reservation-booking-management
      name: Reservation & Booking Management
      url: /capabilities/reservation-booking-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - MarketMan
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        status: none
      name: Zenchef
      slug: zenchef
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Payments
      - Reservations
      - Restaurant
      - Software-as-a-Service
      tier: declared
      url: /providers/zenchef/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mews
      band: minimal
      in_catalog: true
      kin_score: 5.7
      mcp:
        status: unknown
      name: Spalopia
      slug: spalopia
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Booking
      - Company
      - Spa
      - Wellness
      tier: declared
      url: /providers/spalopia/
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - QloApps
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Hotel Center
      slug: google
      sources:
      - https://github.com/Qloapps/QloApps/tree/develop/modules/qlogooglehotelconnector
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Mews
      band: developing
      in_catalog: true
      kin_score: 41.1
      mcp:
        status: none
      name: Amadeus iHotelier
      slug: amadeus
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Flights
      - Reservations
      - Travel
      - Travel Technology
      tier: declared
      url: /providers/amadeus/
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - MarketMan
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Push Operations
      slug: push-operations
      sources:
      - https://www.marketman.com/integrations
      status: profiled
      tags:
      - Human Resources
      - Payroll
      - Software-as-a-Service
      - Workforce Management
      tier: declared
      url: /providers/push-operations/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - TastyIgniter
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter / X
      slug: x
      sources:
      - https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - TastyIgniter
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://github.com/tastyigniter/ti-ext-socialite/blob/master/composer.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - TastyIgniter
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - TastyIgniter
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - TastyIgniter
      band: developing
      in_catalog: true
      kin_score: 48.5
      mcp:
        status: none
      name: Ably
      slug: ably
      sources:
      - https://github.com/tastyigniter/ti-ext-broadcast/blob/master/composer.json
      status: profiled
      tags:
      - Messaging
      - Pub/Sub
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/ably/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - TastyIgniter
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://github.com/tastyigniter/ti-ext-broadcast/blob/master/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  layer: common
summary:
  coverage_pct: 90.5
  declared_only: 50
  distinct_providers: 63
  in_catalog: 57
  mcp:
    documented: 1
    none: 27
    unchecked: 6
    verified: 13
  mcp_verified: 13
  mean_kin_score: 35.3
  observed: 13
  queued: 6
  reference_apps: 7
title: 'Hotel & Restaurant Operations: application blueprint'
---
