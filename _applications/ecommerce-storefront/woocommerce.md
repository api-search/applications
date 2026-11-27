---
app: WooCommerce
app_slug: woocommerce
app_url: https://github.com/woocommerce/woocommerce
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2320.20
  key: tender-and-payment-acceptance-management
  layer: domain
  name: Tender and Payment Acceptance Management
  providers:
  - Afterpay
  url: /capabilities/tender-and-payment-acceptance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: ecommerce-storefront
  name: E-commerce Storefront
  url: /applications/ecommerce-storefront/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/woocommerce/woocommerce/trunk/plugins/woocommerce/composer.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/woocommerce/woocommerce/trunk/plugins/woocommerce/package.json
- route: integrations page
  url: https://woocommerce.com/payments/
- route: integrations page
  url: https://woocommerce.com/product-category/woocommerce-extensions/payment-gateways/
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
    agent_band: agent-aware
    agent_readiness: 12.8
    band: minimal
    in_catalog: true
    kin_score: 9.2
    mcp: &id001
      status: none
    slug: afterpay
    status: profiled
    tags: &id002
    - Buy Now Pay Later
    - Consumer
    - Fintech
    - Payments
    url: /providers/afterpay/
  layer: domain
  name: Afterpay
  provider: afterpay
  says: lists Afterpay as an integration
  source: https://woocommerce.com/payments/
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
    mcp: &id003
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id004
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://woocommerce.com/payments/
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
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id005
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id006
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://woocommerce.com/payments/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ecommerce-storefront/woocommerce/
providers:
- agent_band: agent-aware
  agent_readiness: 12.8
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id001
  name: Afterpay
  slug: afterpay
  status: profiled
  tags: *id002
  url: /providers/afterpay/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id003
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id004
  url: /providers/paypal/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id005
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id006
  url: /providers/stripe/
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
- name: Shopify
  rows: 9
  url: /applications/ecommerce-storefront/shopify/
- name: Sylius
  rows: 4
  url: /applications/ecommerce-storefront/sylius/
- name: Vendure
  rows: 4
  url: /applications/ecommerce-storefront/vendure/
sitemap: true
title: 'WooCommerce: E-commerce Storefront reference app'
---
