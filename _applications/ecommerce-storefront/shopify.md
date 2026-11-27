---
app: Shopify
app_slug: shopify
app_url: https://www.shopify.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2510.20
  key: shipment-tracking-management
  layer: domain
  name: Shipment Tracking Management
  providers:
  - Canada Post
  - DHL
  - FedEx
  - UPS
  - USPS
  url: /capabilities/shipment-tracking-management/
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
- attribution: Turbo EA
  id: BC-2320.20
  key: tender-and-payment-acceptance-management
  layer: common
  name: Tender and Payment Acceptance Management
  providers:
  - Amazon Pay
  - Apple Pay
  - Google Pay
  url: /capabilities/tender-and-payment-acceptance-management/
  via_parent: null
category:
  id: ecommerce-storefront
  name: E-commerce Storefront
  url: /applications/ecommerce-storefront/
counts:
  declared: 9
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://help.shopify.com/en/manual/payments/third-party-payment-providers
- route: integrations page
  url: https://www.shopify.com/payments
- route: integrations page
  url: https://www.shopify.com/shipping
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: amazon-pay
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: common
  name: Amazon Pay
  provider: amazon-pay
  says: lists Amazon Pay as an integration
  source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id003
      status: none
    slug: apple-pay
    status: profiled
    tags: &id004
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
  layer: common
  name: Apple Pay
  provider: apple-pay
  says: lists Apple Pay as an integration
  source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
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
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 17.1
    mcp: &id005
      status: none
    slug: canada-post
    status: profiled
    tags: &id006
    - Address Validation
    - E-Commerce
    - Labels
    - Logistics
    url: /providers/canada-post/
  layer: domain
  name: Canada Post
  provider: canada-post
  says: lists Canada Post as an integration
  source: https://www.shopify.com/shipping
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
    mcp: &id007
      status: none
    slug: dhl
    status: profiled
    tags: &id008
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: lists DHL as an integration
  source: https://www.shopify.com/shipping
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
    mcp: &id009
      status: none
    slug: fedex
    status: profiled
    tags: &id010
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://www.shopify.com/shipping
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id011
      status: none
    slug: google-pay
    status: profiled
    tags: &id012
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: common
  name: Google Pay
  provider: google-pay
  says: lists Google Pay as an integration
  source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
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
    mcp: &id013
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id014
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
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
    mcp: &id015
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id016
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://www.shopify.com/shipping
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
    mcp: &id017
      status: none
    slug: usps
    status: profiled
    tags: &id018
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: lists USPS as an integration
  source: https://www.shopify.com/shipping
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ecommerce-storefront/shopify/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Amazon Pay
  slug: amazon-pay
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id003
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id004
  url: /providers/apple-pay/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 17.1
  mcp: *id005
  name: Canada Post
  slug: canada-post
  status: profiled
  tags: *id006
  url: /providers/canada-post/
- agent_band: agent-native
  agent_readiness: 39.5
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id007
  name: DHL
  slug: dhl
  status: profiled
  tags: *id008
  url: /providers/dhl/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id009
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id010
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id011
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id012
  url: /providers/google-pay/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id013
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id014
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id015
  name: UPS
  slug: ups
  status: profiled
  tags: *id016
  url: /providers/ups/
- agent_band: agent-native
  agent_readiness: 51.8
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id017
  name: USPS
  slug: usps
  status: profiled
  tags: *id018
  url: /providers/usps/
siblings:
- name: Bagisto
  rows: 8
  url: /applications/ecommerce-storefront/bagisto/
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
title: 'Shopify: E-commerce Storefront reference app'
---
