---
app: Rallly
app_slug: rallly
app_url: https://github.com/lukevella/rallly
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Webex
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Upstash
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
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: common
  name: Serverless Functions
  providers:
  - Vercel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  - Microsoft sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  url: /capabilities/email/
  via_parent: Email
category:
  id: booking-scheduling
  name: Appointment Booking & Scheduling
  url: /applications/booking-scheduling/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/lukevella/rallly/main/packages/billing/package.json
- route: source code
  url: https://github.com/lukevella/rallly/tree/main/apps/web/src/features/calendars/google
- route: source code
  url: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
integrations:
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
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
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id005
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id006
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/lukevella/rallly/tree/main/apps/web/src/features/calendars/google
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id007
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id008
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id009
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id010
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft sign-in
  provider: microsoft-entra
  says: ships the Microsoft sign-in SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id011
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
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
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id013
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id014
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
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
    mcp: &id017
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id018
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/packages/billing/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.7
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id019
      source: https://github.com/upstash/mcp-server
      status: verified
    slug: upstash
    status: profiled
    tags: &id020
    - Kafka
    - Messaging
    - Redis
    - Serverless
    url: /providers/upstash/
  layer: common
  name: Upstash
  provider: upstash
  says: ships the Upstash SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id021
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id022
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: common
  name: Vercel
  provider: vercel
  says: ships the Vercel SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id023
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id024
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
    mcp: &id025
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id026
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: ships the Zoom SDK or integration code
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/booking-scheduling/rallly/
providers:
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
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
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id005
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id006
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id007
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id008
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id009
  name: Microsoft sign-in
  slug: microsoft-entra
  status: profiled
  tags: *id010
  url: /providers/microsoft-entra/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id011
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id012
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id013
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id014
  url: /providers/posthog/
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
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id017
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id018
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 46.7
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id019
  name: Upstash
  slug: upstash
  status: profiled
  tags: *id020
  url: /providers/upstash/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id021
  name: Vercel
  slug: vercel
  status: profiled
  tags: *id022
  url: /providers/vercel/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id023
  name: Webex
  slug: webex
  status: profiled
  tags: *id024
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id025
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id026
  url: /providers/zoom/
siblings:
- name: Acuity Scheduling
  rows: 38
  url: /applications/booking-scheduling/acuity-scheduling/
- name: Booksy Biz
  rows: 6
  url: /applications/booking-scheduling/booksy-biz/
- name: Cal.com
  rows: 71
  url: /applications/booking-scheduling/cal-com/
- name: Calendly
  rows: 54
  url: /applications/booking-scheduling/calendly/
- name: Easy!Appointments
  rows: 1
  url: /applications/booking-scheduling/easy-appointments/
- name: LibreBooking
  rows: 8
  url: /applications/booking-scheduling/librebooking/
sitemap: true
title: 'Rallly: Appointment Booking & Scheduling reference app'
---
