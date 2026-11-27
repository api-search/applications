---
app: GYM One
app_slug: gym-one
app_url: https://github.com/mayerbalintdev/GYM-One
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.50.10
  key: AE-210.50.10
  layer: domain
  name: Mobile Tickets & Wallet Passes
  providers:
  - Apple Wallet
  url: /capabilities/event-ticketing/
  via_parent: Event Ticketing
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
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: gym-studio-management
  name: Gym & Fitness Studio Management
  url: /applications/gym-studio-management/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/composer.json
- route: source code
  url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
- route: source code
  url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/example.env
- route: source code
  url: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/index.php
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-210.50.10
    key: AE-210.50.10
    name: Mobile Tickets & Wallet Passes
    url: /capabilities/event-ticketing/
    via_parent: Event Ticketing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Wallet
  provider: apple
  says: ships the Apple Wallet SDK or integration code
  source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id003
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/index.php
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
  source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
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
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/mayerbalintdev/GYM-One/main/admin/shop/gateway/index.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/gym-studio-management/gym-one/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple Wallet
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
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
- name: Mindbody
  rows: 24
  url: /applications/gym-studio-management/mindbody/
- name: TeamUp
  rows: 2
  url: /applications/gym-studio-management/teamup/
- name: wger (gym module)
  rows: 5
  url: /applications/gym-studio-management/wger-gym-module/
- name: Wodify
  rows: 19
  url: /applications/gym-studio-management/wodify/
- name: Zen Planner
  rows: 21
  url: /applications/gym-studio-management/zen-planner/
sitemap: true
title: 'GYM One: Gym & Fitness Studio Management reference app'
---
