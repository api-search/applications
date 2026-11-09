---
app: Liberapay
app_slug: liberapay
app_url: https://github.com/liberapay/liberapay.com
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
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon Web Services
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: donations-crowdfunding
  name: Donations & Crowdfunding
  url: /applications/donations-crowdfunding/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
- route: source code
  url: https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services
  provider: amazon-web-services
  says: ships the Amazon Web Services SDK or integration code
  source: https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
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
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id005
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id006
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/liberapay/liberapay.com/blob/master/requirements_base.txt
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
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/liberapay/liberapay.com/tree/master/liberapay/payin
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/donations-crowdfunding/liberapay/
providers:
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id001
  name: Amazon Web Services
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id003
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id004
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id007
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id008
  url: /providers/stripe/
siblings:
- name: Givebutter
  rows: 50
  url: /applications/donations-crowdfunding/givebutter/
- name: GiveWP
  rows: 3
  url: /applications/donations-crowdfunding/givewp/
- name: GoFundMe Pro (Classy)
  rows: 47
  url: /applications/donations-crowdfunding/gofundme-pro-classy/
- name: HCB (Hack Club Bank)
  rows: 13
  url: /applications/donations-crowdfunding/hcb-hack-club-bank/
- name: Open Collective
  rows: 10
  url: /applications/donations-crowdfunding/open-collective/
- name: Patreon
  rows: 23
  url: /applications/donations-crowdfunding/patreon/
sitemap: true
title: 'Liberapay: Donations & Crowdfunding reference app'
---
