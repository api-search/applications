---
app: Paddle
app_slug: paddle
app_url: https://www.paddle.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: domain
  name: In-App Purchases & App Store Billing
  providers:
  - RevenueCat
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250.70
  key: subscription-revenue-analytics
  layer: domain
  name: Subscription Revenue Analytics
  providers:
  - Braintree
  - Chargebee
  - Maxio
  - Recharge
  - Recurly
  - Stripe
  - Uscreen
  - Zuora
  url: /capabilities/subscription-revenue-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Databox
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  url: /capabilities/customer-service-management/
  via_parent: null
category:
  id: subscription-billing
  name: Subscription Billing & Payments Ops
  url: /applications/subscription-billing/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.paddle.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id001
      status: none
    slug: braintree
    status: profiled
    tags: &id002
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: domain
  name: Braintree
  provider: braintree
  says: lists Braintree as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.1
    band: strong
    in_catalog: true
    kin_score: 62.9
    mcp: &id003
      source: https://www.chargebee.com/docs/billing/2.0/ai-in-chargebee/chargebee-mcp
      status: verified
    slug: chargebee
    status: profiled
    tags: &id004
    - Billing
    - Recurring Billing
    - Revenue
    - Subscription
    url: /providers/chargebee/
  layer: domain
  name: Chargebee
  provider: chargebee
  says: lists Chargebee as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: developing
    in_catalog: true
    kin_score: 46.1
    mcp: &id005
      source: https://github.com/databox/databox-mcp
      status: verified
    slug: databox
    status: profiled
    tags: &id006
    - Analytics
    - Artificial Intelligence
    - Company
    - Data Integration
    url: /providers/databox/
  layer: common
  name: Databox
  provider: databox
  says: lists Databox as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id007
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id008
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id009
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 24.6
    mcp: &id011
      status: none
    slug: maxio
    status: profiled
    tags: &id012
    - Billing
    - Recurring Billing
    - Revenue Recognition
    - Subscription
    url: /providers/maxio/
  layer: domain
  name: Maxio
  provider: maxio
  says: lists Maxio as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id013
      source: https://registry.modelcontextprotocol.io/v0/servers?search=rechargeapps
      status: verified
    slug: recharge-payments
    status: profiled
    tags: &id014
    - E-Commerce
    - Payments
    - Recurring Billing
    - Subscription
    url: /providers/recharge-payments/
  layer: domain
  name: Recharge
  provider: recharge-payments
  says: lists Recharge as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.3
    band: exemplar
    in_catalog: true
    kin_score: 78.8
    mcp: &id015
      status: none
    slug: recurly
    status: profiled
    tags: &id016
    - Billing
    - Payments
    - Recurring Revenue
    - Subscription
    url: /providers/recurly/
  layer: domain
  name: Recurly
  provider: recurly
  says: lists Recurly as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id017
      source: https://www.revenuecat.com/docs/tools/mcp
      status: verified
    slug: revenuecat
    status: profiled
    tags: &id018
    - Billing
    - In-App Purchases
    - Mobile
    - Subscription
    url: /providers/revenuecat/
  layer: domain
  name: RevenueCat
  provider: revenuecat
  says: lists RevenueCat as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id019
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id020
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id021
      source: https://help.uscreen.tv/en/articles/15643974-uscreen-mcp
      status: verified
    slug: uscreen
    status: profiled
    tags: &id022
    - Company
    - Membership
    - Platform
    - Video
    url: /providers/uscreen/
  layer: domain
  name: Uscreen
  provider: uscreen
  says: lists Uscreen as an integration
  source: https://www.paddle.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.8
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id023
      source: https://docs.zuora.com/en/zuora-platform/system-management/zuora-ai/zuora-mcp-server
      status: verified
    slug: zuora
    status: profiled
    tags: &id024
    - Billing
    - Finance
    - Payments
    - Subscription
    url: /providers/zuora/
  layer: domain
  name: Zuora
  provider: zuora
  says: lists Zuora as an integration
  source: https://www.paddle.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/subscription-billing/paddle/
providers:
- agent_band: agent-ready
  agent_readiness: 52.0
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id001
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id002
  url: /providers/braintree/
- agent_band: agent-ready
  agent_readiness: 54.1
  band: strong
  in_catalog: true
  kin_score: 62.9
  mcp: *id003
  name: Chargebee
  slug: chargebee
  status: profiled
  tags: *id004
  url: /providers/chargebee/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id005
  name: Databox
  slug: databox
  status: profiled
  tags: *id006
  url: /providers/databox/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id007
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id008
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id009
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id010
  url: /providers/intercom/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id011
  name: Maxio
  slug: maxio
  status: profiled
  tags: *id012
  url: /providers/maxio/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id013
  name: Recharge
  slug: recharge-payments
  status: profiled
  tags: *id014
  url: /providers/recharge-payments/
- agent_band: agent-native
  agent_readiness: 54.3
  band: exemplar
  in_catalog: true
  kin_score: 78.8
  mcp: *id015
  name: Recurly
  slug: recurly
  status: profiled
  tags: *id016
  url: /providers/recurly/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id017
  name: RevenueCat
  slug: revenuecat
  status: profiled
  tags: *id018
  url: /providers/revenuecat/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id019
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id020
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id021
  name: Uscreen
  slug: uscreen
  status: profiled
  tags: *id022
  url: /providers/uscreen/
- agent_band: agent-native
  agent_readiness: 57.8
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id023
  name: Zuora
  slug: zuora
  status: profiled
  tags: *id024
  url: /providers/zuora/
siblings:
- name: Chargebee
  rows: 44
  url: /applications/subscription-billing/chargebee/
- name: Invoice Ninja
  rows: 34
  url: /applications/subscription-billing/invoice-ninja/
- name: Kill Bill
  rows: 15
  url: /applications/subscription-billing/kill-bill/
- name: Lago
  rows: 31
  url: /applications/subscription-billing/lago/
- name: Polar
  rows: 14
  url: /applications/subscription-billing/polar/
- name: Recurly
  rows: 28
  url: /applications/subscription-billing/recurly/
sitemap: true
title: 'Paddle: Subscription Billing & Payments Ops reference app'
---
