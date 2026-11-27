---
app: GiveWP
app_slug: givewp
app_url: https://github.com/impress-org/givewp
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  - Square
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: donations-crowdfunding
  name: Donations & Crowdfunding
  url: /applications/donations-crowdfunding/
counts:
  declared: 1
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/impress-org/givewp/blob/develop/composer.json
- route: integrations page
  url: https://givewp.com/addons/
- route: source code
  url: https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
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
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id001
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id002
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
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
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/impress-org/givewp/tree/develop/src/PaymentGateways/Gateways
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
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id003
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id004
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://givewp.com/addons/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/donations-crowdfunding/givewp/
providers:
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id001
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id002
  url: /providers/paypal/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id003
  name: Square
  slug: square
  status: profiled
  tags: *id004
  url: /providers/square/
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
- name: Givebutter
  rows: 50
  url: /applications/donations-crowdfunding/givebutter/
- name: GoFundMe Pro (Classy)
  rows: 47
  url: /applications/donations-crowdfunding/gofundme-pro-classy/
- name: HCB (Hack Club Bank)
  rows: 13
  url: /applications/donations-crowdfunding/hcb-hack-club-bank/
- name: Liberapay
  rows: 4
  url: /applications/donations-crowdfunding/liberapay/
- name: Open Collective
  rows: 10
  url: /applications/donations-crowdfunding/open-collective/
- name: Patreon
  rows: 23
  url: /applications/donations-crowdfunding/patreon/
sitemap: true
title: 'GiveWP: Donations & Crowdfunding reference app'
---
