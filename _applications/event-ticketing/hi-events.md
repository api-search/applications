---
app: Hi.Events
app_slug: hi-events
app_url: https://github.com/HiEventsDev/Hi.Events
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: common
  name: Address Validation & Autocomplete
  providers:
  - Google Places
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  url: /capabilities/bot-protection-captcha/
  via_parent: null
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
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Postmark
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: event-ticketing
  name: Events & Ticketing
  url: /applications/event-ticketing/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
- route: dependency manifest
  url: https://github.com/HiEventsDev/Hi.Events/blob/develop/frontend/package.json
- route: source code
  url: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id001
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id002
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
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
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id003
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id004
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id005
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-places
    status: profiled
    tags: &id006
    - Geolocation
    - Google
    - Location
    - Restaurant
    url: /providers/google-places/
  layer: common
  name: Google Places
  provider: google-places
  says: ships the Google Places SDK or integration code
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id007
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id008
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
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
    mcp: &id009
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id010
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
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
    mcp: &id011
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id012
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/event-ticketing/hi-events/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id001
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id003
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id004
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id005
  name: Google Places
  slug: google-places
  status: profiled
  tags: *id006
  url: /providers/google-places/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id007
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id008
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id009
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id010
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id011
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id012
  url: /providers/stripe/
siblings:
- name: alf.io
  rows: 13
  url: /applications/event-ticketing/alf-io/
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
title: 'Hi.Events: Events & Ticketing reference app'
---
