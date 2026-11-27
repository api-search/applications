---
app: Joy
app_slug: joy
app_url: https://withjoy.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.50.40
  key: AE-140.50.40
  layer: domain
  name: Gift & Cash-Fund Registries
  providers:
  - Amazon
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: Gift Cards, Gifting & Cashback
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  - New Relic
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Cash App
  - PayPal
  - Venmo
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Firebase
  - Google Analytics
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: wedding-event-planning
  name: Wedding & Event Planning
  url: /applications/wedding-event-planning/
counts:
  declared: 4
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
- route: documentation
  url: https://withjoy.com/registry/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id004
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id005
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id008
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id009
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id010
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id011
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id012
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id013
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id014
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id015
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id018
      status: none
    slug: segment
    status: profiled
    tags: &id019
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id020
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id021
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.withjoy.joy/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.40
    key: AE-140.50.40
    name: Gift & Cash-Fund Registries
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id002
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id003
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon
  provider: amazon
  says: lists Amazon as an integration
  source: https://withjoy.com/registry/
  tier: declared
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
    agent_readiness: 40.8
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id006
      status: none
    slug: cash-app
    status: profiled
    tags: &id007
    - Financial Services
    - Fintech
    - Payments
    - United States
    url: /providers/cash-app/
  layer: common
  name: Cash App
  provider: cash-app
  says: lists Cash App as an integration
  source: https://withjoy.com/registry/
  tier: declared
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
    mcp: &id016
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id017
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://withjoy.com/registry/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id022
      status: none
    slug: venmo
    status: profiled
    tags: &id023
    - Company
    - Consumer
    - Fintech
    - Payments
    url: /providers/venmo/
  layer: common
  name: Venmo
  provider: venmo
  says: lists Venmo as an integration
  source: https://withjoy.com/registry/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/wedding-event-planning/joy/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id002
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id003
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id004
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id005
  url: /providers/amplitude/
- agent_band: agent-native
  agent_readiness: 40.8
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id006
  name: Cash App
  slug: cash-app
  status: profiled
  tags: *id007
  url: /providers/cash-app/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id008
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id009
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id010
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id011
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id012
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id013
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id014
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id015
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id016
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id017
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id018
  name: Segment
  slug: segment
  status: profiled
  tags: *id019
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id020
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id021
  url: /providers/sentry-system/
- agent_band: human-only
  agent_readiness: 3.8
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id022
  name: Venmo
  slug: venmo
  status: profiled
  tags: *id023
  url: /providers/venmo/
siblings:
- name: Aisle Planner
  rows: 6
  url: /applications/wedding-event-planning/aisle-planner/
- name: HoneyBook
  rows: 40
  url: /applications/wedding-event-planning/honeybook/
- name: Planning Pod
  rows: 23
  url: /applications/wedding-event-planning/planning-pod/
- name: Rallly
  rows: 16
  url: /applications/wedding-event-planning/rallly/
- name: The Knot Wedding Planner
  rows: 0
  url: /applications/wedding-event-planning/the-knot-wedding-planner/
- name: WeddingShare
  rows: 2
  url: /applications/wedding-event-planning/weddingshare/
sitemap: true
title: 'Joy: Wedding & Event Planning reference app'
---
