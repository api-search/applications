---
app: Keila
app_slug: keila
app_url: https://github.com/pentacent/keila
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Amazon SES
  - Mailgun
  - Postmark
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: domain
  name: Subscription Billing & Revenue Management
  providers:
  - Paddle
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Friendly Captcha
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
category:
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/pentacent/keila/main/mix.exs
- route: source code
  url: https://github.com/pentacent/keila/tree/main/extra/keila_cloud/paddle
- route: source code
  url: https://github.com/pentacent/keila/tree/main/lib/keila/mailings/sender_adapters
- route: source code
  url: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
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
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id001
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: domain
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/pentacent/keila/main/mix.exs
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id003
      status: none
    slug: friendly-captcha
    status: profiled
    tags: &id004
    - Bot Defense
    - CAPTCHA
    - Privacy
    - Proof of Work
    url: /providers/friendly-captcha/
  layer: common
  name: Friendly Captcha
  provider: friendly-captcha
  says: ships the Friendly Captcha SDK or integration code
  source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id005
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id006
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id007
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id008
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: domain
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/mailgun.ex
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.5
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id009
      source: https://github.com/PaddleHQ/paddle-mcp-server
      status: verified
    slug: paddle
    status: profiled
    tags: &id010
    - Billing
    - Merchant of Record
    - Payments
    - Subscription
    url: /providers/paddle/
  layer: domain
  name: Paddle
  provider: paddle
  says: ships the Paddle SDK or integration code
  source: https://github.com/pentacent/keila/tree/main/extra/keila_cloud/paddle
  tier: observed
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
    agent_readiness: 41.7
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id011
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id012
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: domain
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/postmark.ex
  tier: observed
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
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id013
      status: none
    slug: sendgrid
    status: profiled
    tags: &id014
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: domain
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/sendgrid.ex
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/keila/
providers:
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id003
  name: Friendly Captcha
  slug: friendly-captcha
  status: profiled
  tags: *id004
  url: /providers/friendly-captcha/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id005
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id006
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id007
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id008
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 47.5
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id009
  name: Paddle
  slug: paddle
  status: profiled
  tags: *id010
  url: /providers/paddle/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id011
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id012
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id013
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id014
  url: /providers/sendgrid/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Ghost
  rows: 17
  url: /applications/email-marketing-newsletter/ghost/
- name: Klaviyo
  rows: 15
  url: /applications/email-marketing-newsletter/klaviyo/
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
title: 'Keila: Email Marketing & Newsletters reference app'
---
