---
app: Indico
app_slug: indico
app_url: https://github.com/indico/indico
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.50.10
  key: AE-210.50.10
  layer: domain
  name: Mobile Tickets & Wallet Passes
  providers:
  - Apple Wallet
  - Google Wallet
  url: /capabilities/event-ticketing/
  via_parent: Event Ticketing
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha
  - reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - ownCloud
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - SIXPay Saferpay
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Matomo (Piwik)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
category:
  id: event-ticketing
  name: Events & Ticketing
  url: /applications/event-ticketing/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/indico/indico/blob/master/requirements.in
- route: source code
  url: https://github.com/indico/indico-plugins
- route: source code
  url: https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-210.50.10
    key: AE-210.50.10
    name: Mobile Tickets & Wallet Passes
    url: /capabilities/event-ticketing/
    via_parent: Event Ticketing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Wallet
  provider: apple
  says: ships the Apple Wallet SDK or integration code
  source: https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.50.10
    key: AE-210.50.10
    name: Mobile Tickets & Wallet Passes
    url: /capabilities/event-ticketing/
    via_parent: Event Ticketing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.5
    band: strong
    in_catalog: true
    kin_score: 61.3
    mcp: &id003
      source: https://developers.google.com/pay-wallet/ai-tools/mcp-server/mcp-server
      status: verified
    slug: google-wallet
    status: profiled
    tags: &id004
    - Digital Wallet
    - Google Wallet
    - Loyalty Cards
    - Mobile Payments
    url: /providers/google-wallet/
  layer: domain
  name: Google Wallet
  provider: google-wallet
  says: ships the Google Wallet SDK or integration code
  source: https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
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
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
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
  source: https://github.com/indico/indico-plugins/tree/master/cloud_captchas
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
    agent_readiness: 41.3
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id007
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id008
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo (Piwik)
  provider: matomo
  says: ships the Matomo (Piwik) SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/piwik
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id009
      source: https://github.com/owncloud/ocis-mcp-server
      status: verified
    slug: owncloud
    status: profiled
    tags: &id010
    - Cloud Storage
    - Data Sovereignty
    - File Sharing
    - Secure Collaboration
    url: /providers/owncloud/
  layer: common
  name: ownCloud
  provider: owncloud
  says: ships the ownCloud SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/owncloud
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
    mcp: &id011
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id012
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/payment_paypal
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
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id013
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id014
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: reCAPTCHA
  provider: google-recaptcha
  says: ships the reCAPTCHA SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/cloud_captchas
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id015
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id016
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/indico/indico/blob/master/requirements.in
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
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 54.0
    mcp: &id017
      status: none
    slug: wordline
    status: profiled
    tags: &id018
    - Acquiring
    - Issuing
    - Payment Processing
    - Payments
    url: /providers/wordline/
  layer: common
  name: SIXPay Saferpay
  provider: wordline
  says: ships the SIXPay Saferpay SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/payment_sixpay
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
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/payment_stripe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id021
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id022
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: ships the Zoom SDK or integration code
  source: https://github.com/indico/indico-plugins/tree/master/vc_zoom
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/event-ticketing/indico/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple Wallet
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 40.5
  band: strong
  in_catalog: true
  kin_score: 61.3
  mcp: *id003
  name: Google Wallet
  slug: google-wallet
  status: profiled
  tags: *id004
  url: /providers/google-wallet/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id005
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id006
  url: /providers/hcaptcha/
- agent_band: agent-ready
  agent_readiness: 41.3
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id007
  name: Matomo (Piwik)
  slug: matomo
  status: profiled
  tags: *id008
  url: /providers/matomo/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id009
  name: ownCloud
  slug: owncloud
  status: profiled
  tags: *id010
  url: /providers/owncloud/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id011
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id012
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id013
  name: reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id014
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id015
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id016
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 54.0
  mcp: *id017
  name: SIXPay Saferpay
  slug: wordline
  status: profiled
  tags: *id018
  url: /providers/wordline/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id019
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id020
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id021
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id022
  url: /providers/zoom/
siblings:
- name: alf.io
  rows: 13
  url: /applications/event-ticketing/alf-io/
- name: Hi.Events
  rows: 6
  url: /applications/event-ticketing/hi-events/
- name: Luma
  rows: 3
  url: /applications/event-ticketing/luma/
- name: pretalx
  rows: 4
  url: /applications/event-ticketing/pretalx/
- name: pretix
  rows: 23
  url: /applications/event-ticketing/pretix/
- name: Ticketmaster
  rows: 4
  url: /applications/event-ticketing/ticketmaster/
- name: Tito
  rows: 3
  url: /applications/event-ticketing/tito/
sitemap: true
title: 'Indico: Events & Ticketing reference app'
---
