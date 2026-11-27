---
app: Brightwheel
app_slug: brightwheel
app_url: https://mybrightwheel.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.30
  key: AE-160.30
  layer: common
  name: Identity Verification
  providers:
  - Stripe Identity
  url: /capabilities/identity-verification/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe Connect
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - Stripe Billing
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
category:
  id: kids-family-parenting
  name: Kids, Family & Parenting
  url: /applications/kids-family-parenting/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://stripe.com/customers/brightwheel
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id002
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id003
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe Billing
  provider: stripe
  says: lists Stripe Billing as an integration
  source: https://stripe.com/customers/brightwheel
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Stripe Connect
  provider: stripe
  says: lists Stripe Connect as an integration
  source: https://stripe.com/customers/brightwheel
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Stripe Identity
  provider: stripe
  says: lists Stripe Identity as an integration
  source: https://stripe.com/customers/brightwheel
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/kids-family-parenting/brightwheel/
providers:
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id002
  name: Stripe Billing
  slug: stripe
  status: profiled
  tags: *id003
  url: /providers/stripe/
siblings:
- name: Baby Buddy
  rows: 2
  url: /applications/kids-family-parenting/baby-buddy/
- name: Cozi
  rows: 9
  url: /applications/kids-family-parenting/cozi/
- name: Gramps Web
  rows: 2
  url: /applications/kids-family-parenting/gramps-web/
- name: Greenlight
  rows: 0
  url: /applications/kids-family-parenting/greenlight/
- name: Life360
  rows: 25
  url: /applications/kids-family-parenting/life360/
- name: OurFamilyWizard
  rows: 4
  url: /applications/kids-family-parenting/ourfamilywizard/
sitemap: true
title: 'Brightwheel: Kids, Family & Parenting reference app'
---
