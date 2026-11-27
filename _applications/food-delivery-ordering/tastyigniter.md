---
app: TastyIgniter
app_slug: tastyigniter
app_url: https://github.com/tastyigniter/TastyIgniter
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.50.10
  key: AE-140.50.10
  layer: domain
  name: Gift Cards
  providers:
  - Gift Up!
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: Gift Cards, Gifting & Cashback
- attribution: Turbo EA
  id: BC-2420.40
  key: last-mile-delivery-operations-management
  layer: domain
  name: Last-Mile Delivery Operations Management
  providers:
  - Shipday
  - Uber Direct
  url: /capabilities/last-mile-delivery-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320.50.40
  key: BC-2320.50.40
  layer: domain
  name: POS Peripheral Configuration
  providers:
  - Star Micronics CloudPRNT
  url: /capabilities/pos-configuration-management/
  via_parent: POS Configuration Management
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Square POS
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10
  key: AE-120.10
  layer: common
  name: Geocoding
  providers:
  - Google Maps Platform
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Authorize.Net
  - Mollie
  - PayPal
  - Square
  - Stripe
  - SumUp
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: food-delivery-ordering
  name: Food Delivery & Restaurant Ordering
  url: /applications/food-delivery-ordering/
counts:
  declared: 6
  observed: 7
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id002
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id003
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id006
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id007
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
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
  facts:
    agent_band: agent-native
    agent_readiness: 71.7
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id008
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id009
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id010
      status: none
    slug: nominatim
    status: profiled
    tags: &id011
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id012
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id013
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts: &id001
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id016
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id017
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id020
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id021
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id004
      status: unknown
    slug: gift-up
    status: profiled
    tags: &id005
    - Company
    - E-Commerce
    - Gift Cards
    - Payments
    url: /providers/gift-up/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id014
      source: https://registry.modelcontextprotocol.io/v0/servers?search=com.shipday&limit=3
      status: verified
    slug: shipday
    status: profiled
    tags: &id015
    - Delivery
    - Last Mile Delivery
    - Local Delivery
    - Logistics
    url: /providers/shipday/
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
  facts: *id001
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
  facts:
    agent_band: human-only
    agent_readiness: 1.7
    band: emerging
    in_catalog: true
    kin_score: 18.6
    mcp: &id018
      status: none
    slug: star-micronics
    status: profiled
    tags: &id019
    - Company
    - Hardware
    - Point-of-Sale
    - Printing
    url: /providers/star-micronics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.2
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id022
      source: https://github.com/sumup/sumup-mcp
      status: verified
    slug: sumup
    status: profiled
    tags: &id023
    - Card Reader
    - Checkout
    - Payments
    - Point-of-Sale
    url: /providers/sumup/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id024
      status: none
    slug: uber-direct
    status: profiled
    tags: &id025
    - Couriers
    - Fulfillment
    - Last Mile Delivery
    - Logistics
    url: /providers/uber-direct/
  layer: domain
  name: Uber Direct
  provider: uber-direct
  says: lists Uber Direct as an integration
  source: https://tastyigniter.com/marketplace/extensions
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/food-delivery-ordering/tastyigniter/
providers:
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id002
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id003
  url: /providers/authorizenet/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id004
  name: Gift Up!
  slug: gift-up
  status: profiled
  tags: *id005
  url: /providers/gift-up/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id006
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id007
  url: /providers/google-maps/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id008
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id009
  url: /providers/mollie/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id010
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id011
  url: /providers/nominatim/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id012
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id013
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id014
  name: Shipday
  slug: shipday
  status: profiled
  tags: *id015
  url: /providers/shipday/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id016
  name: Square
  slug: square
  status: profiled
  tags: *id017
  url: /providers/square/
- agent_band: human-only
  agent_readiness: 1.7
  band: emerging
  in_catalog: true
  kin_score: 18.6
  mcp: *id018
  name: Star Micronics CloudPRNT
  slug: star-micronics
  status: profiled
  tags: *id019
  url: /providers/star-micronics/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id020
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id021
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 53.2
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id022
  name: SumUp
  slug: sumup
  status: profiled
  tags: *id023
  url: /providers/sumup/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id024
  name: Uber Direct
  slug: uber-direct
  status: profiled
  tags: *id025
  url: /providers/uber-direct/
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
- name: Shipday
  rows: 23
  url: /applications/food-delivery-ordering/shipday/
- name: UpMenu
  rows: 32
  url: /applications/food-delivery-ordering/upmenu/
sitemap: true
title: 'TastyIgniter: Food Delivery & Restaurant Ordering reference app'
---
