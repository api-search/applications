---
app: Sylius
app_slug: sylius
app_url: https://github.com/Sylius/Sylius
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Adyen
  - Mollie
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: ecommerce-storefront
  name: E-commerce Storefront
  url: /applications/ecommerce-storefront/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/Sylius/Sylius/2.1/composer.json
- route: integrations page
  url: https://sylius.com/plugins/
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
    agent_band: agent-native
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id001
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id002
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
  layer: common
  name: Adyen
  provider: adyen
  says: lists Adyen as an integration
  source: https://sylius.com/plugins/
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
    agent_readiness: 71.7
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id003
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id004
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: common
  name: Mollie
  provider: mollie
  says: lists Mollie as an integration
  source: https://sylius.com/plugins/
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
  says: lists PayPal as an integration
  source: https://sylius.com/plugins/
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
    mcp: &id007
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id008
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://sylius.com/plugins/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ecommerce-storefront/sylius/
providers:
- agent_band: agent-native
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id001
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id002
  url: /providers/adyen/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id003
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id004
  url: /providers/mollie/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id005
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id006
  url: /providers/paypal/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id007
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id008
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
- name: Vendure
  rows: 4
  url: /applications/ecommerce-storefront/vendure/
- name: WooCommerce
  rows: 3
  url: /applications/ecommerce-storefront/woocommerce/
sitemap: true
title: 'Sylius: E-commerce Storefront reference app'
---
