---
app: alf.io
app_slug: alf-io
app_url: https://github.com/alfio-event/alf.io
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - EU VIES VAT validation
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps
  - HERE
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Mollie
  - PayPal
  - Revolut Business
  - Saferpay
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  - Mailjet
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: event-ticketing
  name: Events & Ticketing
  url: /applications/event-ticketing/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: source code
  url: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
- route: source code
  url: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
- route: source code
  url: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
integrations:
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: eu-vies
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: EU VIES VAT validation
  provider: eu-vies
  says: ships the EU VIES VAT validation SDK or integration code
  source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id003
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id005
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id006
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 55.5
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id007
      status: none
    slug: here
    status: profiled
    tags: &id008
    - Location
    - Mapping
    - Maps
    - Spatial
    url: /providers/here/
  layer: common
  name: HERE
  provider: here
  says: ships the HERE SDK or integration code
  source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
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
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id009
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id010
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
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
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 50.1
    mcp: &id011
      source: https://github.com/mailgun/mailjet-mcp-server
      status: verified
    slug: mailjet
    status: profiled
    tags: &id012
    - Email
    - Email Delivery
    - Marketing Email
    - SMTP
    url: /providers/mailjet/
  layer: common
  name: Mailjet
  provider: mailjet
  says: ships the Mailjet SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
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
    agent_readiness: 73.2
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id013
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id014
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: common
  name: Mollie
  provider: mollie
  says: ships the Mollie SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id015
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id016
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    mcp: &id017
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id018
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: reCAPTCHA
  provider: google-recaptcha
  says: ships the reCAPTCHA SDK or integration code
  source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id019
      status: none
    slug: revolut
    status: profiled
    tags: &id020
    - Banking
    - Company
    - Fintech
    - Payments
    url: /providers/revolut/
  layer: common
  name: Revolut Business
  provider: revolut
  says: ships the Revolut Business SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    agent_readiness: 42.3
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id021
      status: none
    slug: wordline
    status: profiled
    tags: &id022
    - Acquiring
    - Issuing
    - Payment Processing
    - Payments
    url: /providers/wordline/
  layer: common
  name: Saferpay
  provider: wordline
  says: ships the Saferpay SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id023
      status: none
    slug: sendgrid
    status: profiled
    tags: &id024
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id025
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id026
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/event-ticketing/alf-io/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: EU VIES VAT validation
  slug: eu-vies
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id005
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id006
  url: /providers/google-maps/
- agent_band: agent-native
  agent_readiness: 55.5
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id007
  name: HERE
  slug: here
  status: profiled
  tags: *id008
  url: /providers/here/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id009
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id010
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 50.1
  mcp: *id011
  name: Mailjet
  slug: mailjet
  status: profiled
  tags: *id012
  url: /providers/mailjet/
- agent_band: agent-native
  agent_readiness: 73.2
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id013
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id014
  url: /providers/mollie/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id015
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id016
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id017
  name: reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id018
  url: /providers/google-recaptcha/
- agent_band: agent-native
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id019
  name: Revolut Business
  slug: revolut
  status: profiled
  tags: *id020
  url: /providers/revolut/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id021
  name: Saferpay
  slug: wordline
  status: profiled
  tags: *id022
  url: /providers/wordline/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id023
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id024
  url: /providers/sendgrid/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id025
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id026
  url: /providers/stripe/
siblings:
- name: Hi.Events
  rows: 6
  url: /applications/event-ticketing/hi-events/
- name: Indico
  rows: 11
  url: /applications/event-ticketing/indico/
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
title: 'alf.io: Events & Ticketing reference app'
---
