---
app: LoyaltyLion
app_slug: loyaltylion
app_url: https://loyaltylion.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Bloomreach
  - HubSpot
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Gorgias
  - Re:amaze
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Dotdigital
  - Klaviyo
  - Listrak
  - Mailchimp
  - Ometria
  - Omnisend
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-140.10.30
  key: AE-140.10.30
  layer: domain
  name: Mobile Commerce App Builders
  providers:
  - Tapcart
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Optimizely
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.90.10
  key: AE-140.90.10
  layer: domain
  name: Returns & Exchanges
  providers:
  - Loop Returns
  url: /capabilities/post-purchase/
  via_parent: Post-Purchase
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Bazaarvoice
  - Judge.me
  - Loox
  - Okendo
  - Stamped
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Attentive
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4240
  key: subscription-lifecycle-management
  layer: domain
  name: Subscription Lifecycle Management
  providers:
  - Recharge
  - Skio
  url: /capabilities/subscription-lifecycle-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70.20
  key: AE-170.70.20
  layer: common
  name: Translation Management & Localization
  providers:
  - Weglot
  url: /capabilities/content-management/
  via_parent: Content Management
category:
  id: loyalty-rewards
  name: Loyalty, Rewards & Coupons
  url: /applications/loyalty-rewards/
counts:
  declared: 24
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://loyaltylion.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: exemplar
    in_catalog: true
    kin_score: 75.7
    mcp: &id001
      status: none
    slug: attentive
    status: profiled
    tags: &id002
    - Company
    - Email Marketing
    - MarTech
    - SMS Marketing
    url: /providers/attentive/
  layer: domain
  name: Attentive
  provider: attentive
  says: lists Attentive as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: exemplar
    in_catalog: true
    kin_score: 67.4
    mcp: &id003
      status: none
    slug: bazaarvoice
    status: profiled
    tags: &id004
    - BazaarVoice
    - Company
    - Ratings
    - Reviews
    url: /providers/bazaarvoice/
  layer: domain
  name: Bazaarvoice
  provider: bazaarvoice
  says: lists Bazaarvoice as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.1
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id005
      source: https://github.com/bloomreach/loomi-alpha-mcp-google-adk
      status: documented
    slug: bloomreach
    status: profiled
    tags: &id006
    - Digital Commerce
    - Merchandising
    - Recommendations
    - Search
    url: /providers/bloomreach/
  layer: domain
  name: Bloomreach
  provider: bloomreach
  says: lists Bloomreach as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: exemplar
    in_catalog: true
    kin_score: 69.8
    mcp: &id007
      status: none
    slug: dotdigital
    status: profiled
    tags: &id008
    - Email Marketing
    - MMS
    - Marketing Automation
    - SMS
    url: /providers/dotdigital/
  layer: domain
  name: Dotdigital
  provider: dotdigital
  says: lists Dotdigital as an integration
  source: https://loyaltylion.com/integrations
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
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 42.5
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
  layer: domain
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id011
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id012
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: emerging
    in_catalog: true
    kin_score: 26.0
    mcp: &id013
      status: none
    slug: judge-me
    status: profiled
    tags: &id014
    - E-Commerce
    - Ratings
    - Reviews
    - Shopify
    url: /providers/judge-me/
  layer: domain
  name: Judge.me
  provider: judge-me
  says: lists Judge.me as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id015
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id016
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: domain
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id017
      status: none
    slug: listrak
    status: profiled
    tags: &id018
    - Cross-Channel
    - Email Marketing
    - Marketing Automation
    - SMS Marketing
    url: /providers/listrak/
  layer: domain
  name: Listrak
  provider: listrak
  says: lists Listrak as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.90.10
    key: AE-140.90.10
    name: Returns & Exchanges
    url: /capabilities/post-purchase/
    via_parent: Post-Purchase
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.1
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id019
      status: none
    slug: loop-returns
    status: profiled
    tags: &id020
    - E-Commerce
    - Refunds
    - Returns
    - Shipping
    url: /providers/loop-returns/
  layer: domain
  name: Loop Returns
  provider: loop-returns
  says: lists Loop Returns as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.0
    mcp: &id021
      status: none
    slug: loox
    status: profiled
    tags: &id022
    - E-Commerce
    - Reviews
    - Shopify
    - Visual
    url: /providers/loox/
  layer: domain
  name: Loox
  provider: loox
  says: lists Loox as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id023
      status: none
    slug: mailchimp
    status: profiled
    tags: &id024
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id025
      status: none
    slug: okendo
    status: profiled
    tags: &id026
    - Business Applications
    - Company
    - Ratings
    - Reviews
    url: /providers/okendo/
  layer: domain
  name: Okendo
  provider: okendo
  says: lists Okendo as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.0
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id027
      status: none
    slug: ometria
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Company
    - Customer Data Platform
    - Retail
    url: /providers/ometria/
  layer: domain
  name: Ometria
  provider: ometria
  says: lists Ometria as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.0
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id029
      status: none
    slug: omnisend
    status: profiled
    tags: &id030
    - E-Commerce
    - Email Marketing
    - Marketing Automation
    - SMS Marketing
    url: /providers/omnisend/
  layer: domain
  name: Omnisend
  provider: omnisend
  says: lists Omnisend as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id031
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id032
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: domain
  name: Optimizely
  provider: optimizely
  says: lists Optimizely as an integration
  source: https://loyaltylion.com/integrations
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
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id033
      status: none
    slug: reamaze
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Customer Service
    - Help Desk
    - Live Chat
    url: /providers/reamaze/
  layer: domain
  name: Re:amaze
  provider: reamaze
  says: lists Re:amaze as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4240
    key: subscription-lifecycle-management
    name: Subscription Lifecycle Management
    url: /capabilities/subscription-lifecycle-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id035
      source: https://registry.modelcontextprotocol.io/v0/servers?search=rechargeapps
      status: verified
    slug: recharge-payments
    status: profiled
    tags: &id036
    - E-Commerce
    - Payments
    - Recurring Billing
    - Subscription
    url: /providers/recharge-payments/
  layer: domain
  name: Recharge
  provider: recharge-payments
  says: lists Recharge as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id037
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id038
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4240
    key: subscription-lifecycle-management
    name: Subscription Lifecycle Management
    url: /capabilities/subscription-lifecycle-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: emerging
    in_catalog: true
    kin_score: 19.4
    mcp: &id039
      source: https://mcp.skio.com/.well-known/oauth-protected-resource
      status: verified
    slug: skio
    status: profiled
    tags: &id040
    - Direct to Consumer
    - E-Commerce
    - Shopify
    - Subscription
    url: /providers/skio/
  layer: domain
  name: Skio
  provider: skio
  says: lists Skio as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id041
      status: none
    slug: stamped
    status: profiled
    tags: &id042
    - Company
    - Consumer
    - Ratings
    - Reviews
    url: /providers/stamped/
  layer: domain
  name: Stamped
  provider: stamped
  says: lists Stamped as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.30
    key: AE-140.10.30
    name: Mobile Commerce App Builders
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.9
    band: strong
    in_catalog: true
    kin_score: 63.9
    mcp: &id043
      source: https://registry.modelcontextprotocol.io/v0/servers?search=tapcart
      status: verified
    slug: tapcart
    status: profiled
    tags: &id044
    - Commerce
    - Company
    - Mobile
    - Shopify
    url: /providers/tapcart/
  layer: domain
  name: Tapcart
  provider: tapcart
  says: lists Tapcart as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id045
      status: none
    slug: weglot
    status: profiled
    tags: &id046
    - Internationalization
    - Localization
    - Machine Translation
    - Translation
    url: /providers/weglot/
  layer: common
  name: Weglot
  provider: weglot
  says: lists Weglot as an integration
  source: https://loyaltylion.com/integrations
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
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id047
      status: none
    slug: zendesk
    status: profiled
    tags: &id048
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://loyaltylion.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/loyalty-rewards/loyaltylion/
providers:
- agent_band: agent-ready
  agent_readiness: 35.8
  band: exemplar
  in_catalog: true
  kin_score: 75.7
  mcp: *id001
  name: Attentive
  slug: attentive
  status: profiled
  tags: *id002
  url: /providers/attentive/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: exemplar
  in_catalog: true
  kin_score: 67.4
  mcp: *id003
  name: Bazaarvoice
  slug: bazaarvoice
  status: profiled
  tags: *id004
  url: /providers/bazaarvoice/
- agent_band: agent-ready
  agent_readiness: 63.1
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id005
  name: Bloomreach
  slug: bloomreach
  status: profiled
  tags: *id006
  url: /providers/bloomreach/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: exemplar
  in_catalog: true
  kin_score: 69.8
  mcp: *id007
  name: Dotdigital
  slug: dotdigital
  status: profiled
  tags: *id008
  url: /providers/dotdigital/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id009
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id010
  url: /providers/gorgias/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id011
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id012
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: emerging
  in_catalog: true
  kin_score: 26.0
  mcp: *id013
  name: Judge.me
  slug: judge-me
  status: profiled
  tags: *id014
  url: /providers/judge-me/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id015
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id016
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id017
  name: Listrak
  slug: listrak
  status: profiled
  tags: *id018
  url: /providers/listrak/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id019
  name: Loop Returns
  slug: loop-returns
  status: profiled
  tags: *id020
  url: /providers/loop-returns/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.0
  mcp: *id021
  name: Loox
  slug: loox
  status: profiled
  tags: *id022
  url: /providers/loox/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id023
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id024
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id025
  name: Okendo
  slug: okendo
  status: profiled
  tags: *id026
  url: /providers/okendo/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id027
  name: Ometria
  slug: ometria
  status: profiled
  tags: *id028
  url: /providers/ometria/
- agent_band: agent-ready
  agent_readiness: 57.0
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id029
  name: Omnisend
  slug: omnisend
  status: profiled
  tags: *id030
  url: /providers/omnisend/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id031
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id032
  url: /providers/optimizely/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id033
  name: Re:amaze
  slug: reamaze
  status: profiled
  tags: *id034
  url: /providers/reamaze/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id035
  name: Recharge
  slug: recharge-payments
  status: profiled
  tags: *id036
  url: /providers/recharge-payments/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id037
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id038
  url: /providers/shopify/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: emerging
  in_catalog: true
  kin_score: 19.4
  mcp: *id039
  name: Skio
  slug: skio
  status: profiled
  tags: *id040
  url: /providers/skio/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id041
  name: Stamped
  slug: stamped
  status: profiled
  tags: *id042
  url: /providers/stamped/
- agent_band: agent-ready
  agent_readiness: 30.9
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id043
  name: Tapcart
  slug: tapcart
  status: profiled
  tags: *id044
  url: /providers/tapcart/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id045
  name: Weglot
  slug: weglot
  status: profiled
  tags: *id046
  url: /providers/weglot/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id047
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id048
  url: /providers/zendesk/
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
- name: Points and Rewards for WooCommerce (WP Swings)
  rows: 3
  url: /applications/loyalty-rewards/points-and-rewards-for-woocommerce-wp-swings/
- name: RefRef
  rows: 3
  url: /applications/loyalty-rewards/refref/
- name: Smile.io
  rows: 20
  url: /applications/loyalty-rewards/smile-io/
- name: Yotpo Loyalty & Referrals
  rows: 21
  url: /applications/loyalty-rewards/yotpo-loyalty-referrals/
sitemap: true
title: 'LoyaltyLion: Loyalty, Rewards & Coupons reference app'
---
