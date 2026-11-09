---
app: TastyIgniter
app_slug: tastyigniter
app_url: https://github.com/tastyigniter/TastyIgniter
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Authorize.Net
  - Mollie
  - PayPal
  - Square
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Ably
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  - Sign in with Apple
  - Twitter / X
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 0
  observed: 11
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 48.5
    mcp: &id001
      status: none
    slug: ably
    status: profiled
    tags: &id002
    - Messaging
    - Pub/Sub
    - Real-Time
    - WebSocket
    url: /providers/ably/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id003
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id004
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id007
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id008
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: agent-native
    agent_readiness: 73.2
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id009
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id010
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id011
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id012
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id013
      status: none
    slug: pusher
    status: profiled
    tags: &id014
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id015
      status: none
    slug: apple
    status: profiled
    tags: &id016
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-native
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id017
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id018
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id019
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id020
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id021
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id022
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: Twitter / X
  provider: x
  says: ships the Twitter / X SDK or integration code
  source: https://github.com/tastyigniter/ti-ext-socialite/tree/master/src/SocialiteProviders
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hospitality-restaurant-ops/tastyigniter/
providers:
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 48.5
  mcp: *id001
  name: Ably
  slug: ably
  status: profiled
  tags: *id002
  url: /providers/ably/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id003
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id004
  url: /providers/authorizenet/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id007
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id008
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 73.2
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id009
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id010
  url: /providers/mollie/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id011
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id012
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id013
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id014
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id015
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id016
  url: /providers/apple/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id017
  name: Square
  slug: square
  status: profiled
  tags: *id018
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id019
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id020
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id021
  name: Twitter / X
  slug: x
  status: profiled
  tags: *id022
  url: /providers/x/
siblings:
- name: 7shifts
  rows: 12
  url: /applications/hospitality-restaurant-ops/7shifts/
- name: apaleo
  rows: 5
  url: /applications/hospitality-restaurant-ops/apaleo/
- name: Cloudbeds
  rows: 3
  url: /applications/hospitality-restaurant-ops/cloudbeds/
- name: MarketMan
  rows: 31
  url: /applications/hospitality-restaurant-ops/marketman/
- name: Mews
  rows: 11
  url: /applications/hospitality-restaurant-ops/mews/
- name: QloApps
  rows: 3
  url: /applications/hospitality-restaurant-ops/qloapps/
sitemap: true
title: 'TastyIgniter: Hotel & Restaurant Operations reference app'
---
