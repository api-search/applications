---
app: Yotpo Loyalty & Referrals
app_slug: yotpo-loyalty-referrals
app_url: https://www.yotpo.com/platform/loyalty/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Triple Whale
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Braze
  - Insider
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Dixa
  - Gladly
  - Gorgias
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Klaviyo
  - Mailchimp
  - Omnisend
  - Salesforce Marketing Cloud
  - SAP Emarsys
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Adobe Commerce
  - BigCommerce
  - Salesforce Commerce Cloud
  - Shopify
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-2820.10
  key: referral-management
  layer: domain
  name: Referral Management
  providers:
  - Refersion
  url: /capabilities/referral-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Bazaarvoice
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Attentive
  - Postscript
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: loyalty-rewards
  name: Loyalty, Rewards & Coupons
  url: /applications/loyalty-rewards/
counts:
  declared: 21
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.yotpo.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id001
      status: none
    slug: adobe-commerce
    status: profiled
    tags: &id002
    - Adobe
    - Commerce
    - E-Commerce
    - Magento
    url: /providers/adobe-commerce/
  layer: domain
  name: Adobe Commerce
  provider: adobe-commerce
  says: lists Adobe Commerce as an integration
  source: https://www.yotpo.com/integrations/
  tier: declared
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
    mcp: &id003
      status: none
    slug: attentive
    status: profiled
    tags: &id004
    - Company
    - Email Marketing
    - MarTech
    - SMS Marketing
    url: /providers/attentive/
  layer: domain
  name: Attentive
  provider: attentive
  says: lists Attentive as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id005
      status: none
    slug: bazaarvoice
    status: profiled
    tags: &id006
    - BazaarVoice
    - Company
    - Ratings
    - Reviews
    url: /providers/bazaarvoice/
  layer: domain
  name: Bazaarvoice
  provider: bazaarvoice
  says: lists Bazaarvoice as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id007
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id008
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id009
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id010
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: domain
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 30.3
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id011
      status: none
    slug: dixa
    status: profiled
    tags: &id012
    - Conversational AI
    - Customer Experience
    - Customer Service
    - Omnichannel
    url: /providers/dixa/
  layer: domain
  name: Dixa
  provider: dixa
  says: lists Dixa as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 34.3
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id013
      status: none
    slug: gladly
    status: profiled
    tags: &id014
    - AI Customer Service
    - Contact Center
    - Customer Experience
    - Customer Service
    url: /providers/gladly/
  layer: domain
  name: Gladly
  provider: gladly
  says: lists Gladly as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id015
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id016
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: domain
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 54.3
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id017
      status: none
    slug: insider
    status: profiled
    tags: &id018
    - Company
    - Customer Data Platform
    - Customer Engagement
    - Personalization
    url: /providers/insider/
  layer: domain
  name: Insider
  provider: insider
  says: lists Insider as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id019
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id020
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: domain
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id021
      status: none
    slug: mailchimp
    status: profiled
    tags: &id022
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id023
      status: none
    slug: omnisend
    status: profiled
    tags: &id024
    - E-Commerce
    - Email Marketing
    - Marketing Automation
    - SMS Marketing
    url: /providers/omnisend/
  layer: domain
  name: Omnisend
  provider: omnisend
  says: lists Omnisend as an integration
  source: https://www.yotpo.com/integrations/
  tier: declared
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id025
      status: unknown
    slug: postscript
    status: profiled
    tags: &id026
    - E-Commerce
    - Marketing
    - Messaging
    - SMS
    url: /providers/postscript/
  layer: domain
  name: Postscript
  provider: postscript
  says: lists Postscript as an integration
  source: https://www.yotpo.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2820.10
    key: referral-management
    name: Referral Management
    url: /capabilities/referral-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id027
      status: none
    slug: refersion
    status: profiled
    tags: &id028
    - Affiliate Marketing
    - E-Commerce
    - Influencer Marketing
    - Referral Tracking
    url: /providers/refersion/
  layer: domain
  name: Refersion
  provider: refersion
  says: lists Refersion as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 21.7
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id029
      source: https://github.com/SalesforceCommerceCloud/b2c-developer-tooling
      status: verified
    slug: salesforce-commerce-cloud
    status: profiled
    tags: &id030
    - Commerce
    - E-Commerce
    - Headless Commerce
    - Salesforce
    url: /providers/salesforce-commerce-cloud/
  layer: domain
  name: Salesforce Commerce Cloud
  provider: salesforce-commerce-cloud
  says: lists Salesforce Commerce Cloud as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id031
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id032
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: domain
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: lists Salesforce Marketing Cloud as an integration
  source: https://www.yotpo.com/integrations/
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
    kin_score: 69.3
    mcp: &id033
      status: none
    slug: emarsys
    status: profiled
    tags: &id034
    - Customer Engagement
    - Email Marketing
    - Marketing Automation
    - Omnichannel
    url: /providers/emarsys/
  layer: domain
  name: SAP Emarsys
  provider: emarsys
  says: lists SAP Emarsys as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id035
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id036
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 58.8
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id037
      status: none
    slug: triple-whale
    status: profiled
    tags: &id038
    - Analytics
    - Attribution
    - E-Commerce
    - Shopify
    url: /providers/triple-whale/
  layer: domain
  name: Triple Whale
  provider: triple-whale
  says: lists Triple Whale as an integration
  source: https://www.yotpo.com/integrations/
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id039
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id040
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.yotpo.com/integrations/
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
    mcp: &id041
      status: none
    slug: zendesk
    status: profiled
    tags: &id042
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.yotpo.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/loyalty-rewards/yotpo-loyalty-referrals/
providers:
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id001
  name: Adobe Commerce
  slug: adobe-commerce
  status: profiled
  tags: *id002
  url: /providers/adobe-commerce/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: exemplar
  in_catalog: true
  kin_score: 75.7
  mcp: *id003
  name: Attentive
  slug: attentive
  status: profiled
  tags: *id004
  url: /providers/attentive/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: exemplar
  in_catalog: true
  kin_score: 67.4
  mcp: *id005
  name: Bazaarvoice
  slug: bazaarvoice
  status: profiled
  tags: *id006
  url: /providers/bazaarvoice/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id007
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id008
  url: /providers/bigcommerce/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id009
  name: Braze
  slug: braze
  status: profiled
  tags: *id010
  url: /providers/braze/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id011
  name: Dixa
  slug: dixa
  status: profiled
  tags: *id012
  url: /providers/dixa/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id013
  name: Gladly
  slug: gladly
  status: profiled
  tags: *id014
  url: /providers/gladly/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id015
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id016
  url: /providers/gorgias/
- agent_band: agent-ready
  agent_readiness: 54.3
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id017
  name: Insider
  slug: insider
  status: profiled
  tags: *id018
  url: /providers/insider/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id019
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id020
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id021
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id022
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 57.0
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id023
  name: Omnisend
  slug: omnisend
  status: profiled
  tags: *id024
  url: /providers/omnisend/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id025
  name: Postscript
  slug: postscript
  status: profiled
  tags: *id026
  url: /providers/postscript/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id027
  name: Refersion
  slug: refersion
  status: profiled
  tags: *id028
  url: /providers/refersion/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id029
  name: Salesforce Commerce Cloud
  slug: salesforce-commerce-cloud
  status: profiled
  tags: *id030
  url: /providers/salesforce-commerce-cloud/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id031
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id032
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id033
  name: SAP Emarsys
  slug: emarsys
  status: profiled
  tags: *id034
  url: /providers/emarsys/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id035
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id036
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 58.8
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id037
  name: Triple Whale
  slug: triple-whale
  status: profiled
  tags: *id038
  url: /providers/triple-whale/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id039
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id040
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id041
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id042
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
- name: LoyaltyLion
  rows: 24
  url: /applications/loyalty-rewards/loyaltylion/
- name: Points and Rewards for WooCommerce (WP Swings)
  rows: 3
  url: /applications/loyalty-rewards/points-and-rewards-for-woocommerce-wp-swings/
- name: RefRef
  rows: 3
  url: /applications/loyalty-rewards/refref/
- name: Smile.io
  rows: 20
  url: /applications/loyalty-rewards/smile-io/
sitemap: true
title: 'Yotpo Loyalty & Referrals: Loyalty, Rewards & Coupons reference app'
---
