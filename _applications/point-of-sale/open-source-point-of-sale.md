---
app: Open Source Point of Sale
app_slug: open-source-point-of-sale
app_url: https://github.com/opensourcepos/opensourcepos
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Text Marketer
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: point-of-sale
  name: Point of Sale & In-Person Payments
  url: /applications/point-of-sale/
counts:
  declared: 1
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/opensourcepos/opensourcepos/blob/master/composer.json
- route: documentation
  url: https://github.com/opensourcepos/opensourcepos/blob/master/README.md
- route: source code
  url: https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
integrations:
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id003
      status: none
    slug: mailchimp
    status: profiled
    tags: &id004
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: ships the Mailchimp SDK or integration code
  source: https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 21.8
    mcp: &id005
      status: none
    slug: textmarketer
    status: profiled
    tags: &id006
    - Business
    - Marketing
    - SMS
    - United Kingdom
    url: /providers/textmarketer/
  layer: common
  name: Text Marketer
  provider: textmarketer
  says: ships the Text Marketer SDK or integration code
  source: https://github.com/opensourcepos/opensourcepos/tree/master/app/Libraries
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id001
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id002
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: lists Google reCAPTCHA as an integration
  source: https://github.com/opensourcepos/opensourcepos/blob/master/README.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/point-of-sale/open-source-point-of-sale/
providers:
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id001
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id002
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id003
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id004
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 21.8
  mcp: *id005
  name: Text Marketer
  slug: textmarketer
  status: profiled
  tags: *id006
  url: /providers/textmarketer/
siblings:
- name: Lightspeed Restaurant
  rows: 16
  url: /applications/point-of-sale/lightspeed-restaurant/
- name: Loyverse POS
  rows: 33
  url: /applications/point-of-sale/loyverse-pos/
- name: NexoPOS
  rows: 2
  url: /applications/point-of-sale/nexopos/
- name: Odoo Point of Sale
  rows: 16
  url: /applications/point-of-sale/odoo-point-of-sale/
- name: Square Point of Sale
  rows: 28
  url: /applications/point-of-sale/square-point-of-sale/
sitemap: true
title: 'Open Source Point of Sale: Point of Sale & In-Person Payments reference app'
---
