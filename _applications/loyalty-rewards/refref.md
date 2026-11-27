---
app: RefRef
app_slug: refref
app_url: https://github.com/amicalhq/refref
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Resend
  url: /capabilities/email/
  via_parent: Email
category:
  id: loyalty-rewards
  name: Loyalty, Rewards & Coupons
  url: /applications/loyalty-rewards/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: source code
  url: https://github.com/amicalhq/refref/blob/main/apps/api/.env.example
- route: source code
  url: https://github.com/amicalhq/refref/blob/main/apps/webapp/.env.example
integrations:
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id001
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id002
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/amicalhq/refref/blob/main/apps/webapp/.env.example
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
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id003
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/amicalhq/refref/blob/main/apps/webapp/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id005
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id006
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/amicalhq/refref/blob/main/apps/webapp/.env.example
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/loyalty-rewards/refref/
providers:
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id001
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id002
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id003
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id004
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id005
  name: Resend
  slug: resend
  status: profiled
  tags: *id006
  url: /providers/resend/
siblings:
- name: Fetch
  rows: 8
  url: /applications/loyalty-rewards/fetch/
- name: Honey
  rows: 5
  url: /applications/loyalty-rewards/honey/
- name: Ibotta
  rows: 11
  url: /applications/loyalty-rewards/ibotta/
- name: LoyaltyLion
  rows: 24
  url: /applications/loyalty-rewards/loyaltylion/
- name: Points and Rewards for WooCommerce (WP Swings)
  rows: 3
  url: /applications/loyalty-rewards/points-and-rewards-for-woocommerce-wp-swings/
- name: Smile.io
  rows: 20
  url: /applications/loyalty-rewards/smile-io/
- name: Yotpo Loyalty & Referrals
  rows: 21
  url: /applications/loyalty-rewards/yotpo-loyalty-referrals/
sitemap: true
title: 'RefRef: Loyalty, Rewards & Coupons reference app'
---
