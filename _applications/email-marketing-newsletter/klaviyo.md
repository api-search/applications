---
app: Klaviyo
app_slug: klaviyo
app_url: https://www.klaviyo.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Squarespace
  - Wix
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - Judge.me
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Google Ads
  - Meta Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.30
  key: AE-150.10.30
  layer: domain
  name: Email Deliverability & Verification
  providers:
  - GlockApps
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - ShipStation
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: Turbo EA
  id: BC-4030.50
  key: promotion-discount-management
  layer: domain
  name: Promotion & Discount Management
  providers:
  - Talon.One
  url: /capabilities/promotion-discount-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320.10
  key: sales-transaction-management
  layer: domain
  name: Sales Transaction Management
  providers:
  - BigCommerce
  - Shopify
  - WooCommerce
  url: /capabilities/sales-transaction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Triple Whale
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Gorgias
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://marketplace.klaviyo.com/en-us/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.5
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id001
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id002
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.4
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id003
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id004
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: common
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.30
    key: AE-150.10.30
    name: Email Deliverability & Verification
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id005
      status: none
    slug: glockapps-com
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: GlockApps
  provider: glockapps-com
  says: lists GlockApps as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id007
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id008
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://marketplace.klaviyo.com/en-us/
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
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id009
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id010
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: common
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id011
      status: none
    slug: judge-me
    status: profiled
    tags: &id012
    - E-Commerce
    - Ratings
    - Reviews
    - Shopify
    url: /providers/judge-me/
  layer: domain
  name: Judge.me
  provider: judge-me
  says: lists Judge.me as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id013
      status: none
    slug: facebook
    status: profiled
    tags: &id014
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Meta Ads
  provider: facebook
  says: lists Meta Ads as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id015
      status: none
    slug: shipstation
    status: profiled
    tags: &id016
    - E-Commerce
    - Labels
    - Logistics
    - ShipStation
    url: /providers/shipstation/
  layer: domain
  name: ShipStation
  provider: shipstation
  says: lists ShipStation as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id017
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id018
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 69.9
    mcp: &id019
      status: none
    slug: squarespace
    status: profiled
    tags: &id020
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4030.50
    key: promotion-discount-management
    name: Promotion & Discount Management
    url: /capabilities/promotion-discount-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.8
    band: exemplar
    in_catalog: true
    kin_score: 75.5
    mcp: &id021
      source: https://docs.talon.one/docs/dev/mcp
      status: verified
    slug: talon-one
    status: profiled
    tags: &id022
    - Coupons
    - Incentives
    - Loyalty
    - Promotions
    url: /providers/talon-one/
  layer: domain
  name: Talon.One
  provider: talon-one
  says: lists Talon.One as an integration
  source: https://marketplace.klaviyo.com/en-us/
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
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id023
      status: none
    slug: triple-whale
    status: profiled
    tags: &id024
    - Analytics
    - Attribution
    - E-Commerce
    - Shopify
    url: /providers/triple-whale/
  layer: common
  name: Triple Whale
  provider: triple-whale
  says: lists Triple Whale as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.2
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id025
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id026
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.4
    band: developing
    in_catalog: true
    kin_score: 50.4
    mcp: &id027
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id028
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id029
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id030
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/klaviyo/
providers:
- agent_band: agent-ready
  agent_readiness: 60.5
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id001
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id002
  url: /providers/bigcommerce/
- agent_band: agent-native
  agent_readiness: 71.4
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id003
  name: Canva
  slug: canva
  status: profiled
  tags: *id004
  url: /providers/canva/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: GlockApps
  slug: glockapps-com
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-ready
  agent_readiness: 47.7
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id007
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id008
  url: /providers/google-ads/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id009
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id010
  url: /providers/gorgias/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id011
  name: Judge.me
  slug: judge-me
  status: profiled
  tags: *id012
  url: /providers/judge-me/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id013
  name: Meta Ads
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id015
  name: ShipStation
  slug: shipstation
  status: profiled
  tags: *id016
  url: /providers/shipstation/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id017
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id018
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 69.9
  mcp: *id019
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id020
  url: /providers/squarespace/
- agent_band: agent-native
  agent_readiness: 49.8
  band: exemplar
  in_catalog: true
  kin_score: 75.5
  mcp: *id021
  name: Talon.One
  slug: talon-one
  status: profiled
  tags: *id022
  url: /providers/talon-one/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id023
  name: Triple Whale
  slug: triple-whale
  status: profiled
  tags: *id024
  url: /providers/triple-whale/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id025
  name: Wix
  slug: wix
  status: profiled
  tags: *id026
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id027
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id028
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id029
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id030
  url: /providers/zapier/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Ghost
  rows: 17
  url: /applications/email-marketing-newsletter/ghost/
- name: Keila
  rows: 7
  url: /applications/email-marketing-newsletter/keila/
- name: listmonk
  rows: 13
  url: /applications/email-marketing-newsletter/listmonk/
- name: Mailchimp
  rows: 17
  url: /applications/email-marketing-newsletter/mailchimp/
- name: Mautic
  rows: 25
  url: /applications/email-marketing-newsletter/mautic/
- name: Substack
  rows: 4
  url: /applications/email-marketing-newsletter/substack/
sitemap: true
title: 'Klaviyo: Email Marketing & Newsletters reference app'
---
