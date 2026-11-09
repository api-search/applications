---
app: Bagisto
app_slug: bagisto
app_url: https://github.com/bagisto/bagisto
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.40
  key: cross-border-payment-management
  layer: common
  name: Cross-Border Payment Management
  providers:
  - PayGlocal
  url: /capabilities/cross-border-payment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Pusher
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - PayU
  - PhonePe
  - Razorpay
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: ecommerce-storefront
  name: E-commerce Storefront
  url: /applications/ecommerce-storefront/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
- route: source code
  url: https://github.com/bagisto/bagisto/tree/master/packages/Webkul
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.40
    key: cross-border-payment-management
    name: Cross-Border Payment Management
    url: /capabilities/cross-border-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id003
      status: unknown
    slug: payglocal
    status: profiled
    tags: &id004
    - Company
    - Cross-Border
    - Fintech
    - Payments
    url: /providers/payglocal/
  layer: common
  name: PayGlocal
  provider: payglocal
  says: ships the PayGlocal SDK or integration code
  source: https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PayGlocal
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
    mcp: &id005
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id006
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
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
    agent_readiness: 30.8
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id007
      source: https://github.com/payu-intrepos/payu-developer-mcp
      status: verified
    slug: payu
    status: profiled
    tags: &id008
    - Financial Services
    - Fintech
    - Payment Processing
    - Payments
    url: /providers/payu/
  layer: common
  name: PayU
  provider: payu
  says: ships the PayU SDK or integration code
  source: https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PayU
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
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id009
      source: https://github.com/PhonePe/phonepe-pg-docs-mcp
      status: verified
    slug: phonepe
    status: profiled
    tags: &id010
    - Payment Gateway
    - Payments
    - QR
    - UPI
    url: /providers/phonepe/
  layer: common
  name: PhonePe
  provider: phonepe
  says: ships the PhonePe SDK or integration code
  source: https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PhonePe
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id011
      status: none
    slug: pusher
    status: profiled
    tags: &id012
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
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
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id013
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id014
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: common
  name: Razorpay
  provider: razorpay
  says: ships the Razorpay SDK or integration code
  source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
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
    mcp: &id015
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id016
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ecommerce-storefront/bagisto/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id003
  name: PayGlocal
  slug: payglocal
  status: profiled
  tags: *id004
  url: /providers/payglocal/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id005
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id006
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id007
  name: PayU
  slug: payu
  status: profiled
  tags: *id008
  url: /providers/payu/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id009
  name: PhonePe
  slug: phonepe
  status: profiled
  tags: *id010
  url: /providers/phonepe/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id011
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id012
  url: /providers/pusher/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id013
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id014
  url: /providers/razorpay/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id015
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id016
  url: /providers/stripe/
siblings:
- name: Etsy (Android)
  rows: 8
  url: /applications/ecommerce-storefront/etsy-android/
- name: Medusa
  rows: 15
  url: /applications/ecommerce-storefront/medusa/
- name: Saleor
  rows: 11
  url: /applications/ecommerce-storefront/saleor/
- name: Shop (Shopify consumer app, Android)
  rows: 2
  url: /applications/ecommerce-storefront/shop-shopify-consumer-app-android/
- name: Shopify
  rows: 9
  url: /applications/ecommerce-storefront/shopify/
- name: Sylius
  rows: 4
  url: /applications/ecommerce-storefront/sylius/
- name: Vendure
  rows: 4
  url: /applications/ecommerce-storefront/vendure/
- name: WooCommerce
  rows: 3
  url: /applications/ecommerce-storefront/woocommerce/
sitemap: true
title: 'Bagisto: E-commerce Storefront reference app'
---
