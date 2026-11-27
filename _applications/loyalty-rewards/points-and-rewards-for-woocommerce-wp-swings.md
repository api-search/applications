---
app: Points and Rewards for WooCommerce (WP Swings)
app_slug: points-and-rewards-for-woocommerce-wp-swings
app_url: https://github.com/wpswings/points-and-rewards-for-woocommerce
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: loyalty-rewards
  name: Loyalty, Rewards & Coupons
  url: /applications/loyalty-rewards/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: documentation
  url: https://github.com/wpswings/points-and-rewards-for-woocommerce
- route: source code
  url: https://github.com/wpswings/points-and-rewards-for-woocommerce/blob/master/admin/partials/templates/wps-wpr-sms-integration-settings.php
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
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id001
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id002
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/wpswings/points-and-rewards-for-woocommerce/blob/master/admin/partials/templates/wps-wpr-sms-integration-settings.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id003
      status: none
    slug: whatsapp
    status: profiled
    tags: &id004
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: ships the WhatsApp SDK or integration code
  source: https://github.com/wpswings/points-and-rewards-for-woocommerce/blob/master/admin/partials/templates/wps-wpr-sms-integration-settings.php
  tier: observed
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
    mcp: &id005
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id006
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: ships the WooCommerce SDK or integration code
  source: https://github.com/wpswings/points-and-rewards-for-woocommerce
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/loyalty-rewards/points-and-rewards-for-woocommerce-wp-swings/
providers:
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id001
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id002
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id003
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id004
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id005
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id006
  url: /providers/woocommerce/
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
title: 'Points and Rewards for WooCommerce (WP Swings): Loyalty, Rewards & Coupons reference app'
---
