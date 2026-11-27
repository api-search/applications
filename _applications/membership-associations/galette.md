---
app: Galette
app_slug: galette
app_url: https://github.com/galette/galette
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Helloasso
  - Paypal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
category:
  id: membership-associations
  name: Membership & Association Management
  url: /applications/membership-associations/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/galette/galette/blob/develop/composer.json
- route: source code
  url: https://github.com/galette-plugins
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
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id001
      status: unchecked
    slug: helloasso
    status: profiled
    tags: &id002
    - Crowdfunding
    - E-Commerce
    url: /providers/helloasso/
  layer: domain
  name: Helloasso
  provider: helloasso
  says: ships the Helloasso SDK or integration code
  source: https://github.com/galette-plugins/plugin-helloasso
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id003
      status: none
    slug: nominatim
    status: profiled
    tags: &id004
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/galette-plugins/plugin-maps
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
  layer: domain
  name: Paypal
  provider: paypal
  says: ships the Paypal SDK or integration code
  source: https://github.com/galette-plugins/plugin-paypal
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
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/galette-plugins/plugin-stripe
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/membership-associations/galette/
providers:
- agent_band: agent-ready
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id001
  name: Helloasso
  slug: helloasso
  status: profiled
  tags: *id002
  url: /providers/helloasso/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id003
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id004
  url: /providers/nominatim/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id005
  name: Paypal
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
- name: Dolibarr (Members module)
  rows: 10
  url: /applications/membership-associations/dolibarr-members-module/
- name: Glue Up
  rows: 14
  url: /applications/membership-associations/glue-up/
- name: Novi AMS
  rows: 46
  url: /applications/membership-associations/novi-ams/
- name: Paid Memberships Pro
  rows: 29
  url: /applications/membership-associations/paid-memberships-pro/
- name: WildApricot
  rows: 8
  url: /applications/membership-associations/wildapricot/
sitemap: true
title: 'Galette: Membership & Association Management reference app'
---
