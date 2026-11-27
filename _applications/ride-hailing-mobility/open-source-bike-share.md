---
app: Open Source Bike Share
app_slug: open-source-bike-share
app_url: https://github.com/cyklokoalicia/OpenSourceBikeShare
author: API Evangelist
capabilities:
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - EuroSms
  - Textmagic
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: ride-hailing-mobility
  name: Ride-Hailing & Micromobility
  url: /applications/ride-hailing-mobility/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/composer.json
- route: source code
  url: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/.env.dist
- route: source code
  url: https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.5
    mcp: &id001
      status: unknown
    slug: eurosms
    status: profiled
    tags: &id002
    - Bulk Messaging
    - Company
    - SMS
    - Slovakia
    url: /providers/eurosms/
  layer: common
  name: EuroSms
  provider: eurosms
  says: ships the EuroSms SDK or integration code
  source: https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
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
  source: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/.env.dist
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
    mcp: &id005
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id006
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/composer.json
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
    agent_band: agent-ready
    agent_readiness: 52.6
    band: thin
    in_catalog: true
    kin_score: 27.5
    mcp: &id007
      source: https://www.textmagic.com/mcp/
      status: documented
    slug: textmagic
    status: profiled
    tags: &id008
    - Communications
    - Messaging
    - SMS
    - Text Messaging
    url: /providers/textmagic/
  layer: common
  name: Textmagic
  provider: textmagic
  says: ships the Textmagic SDK or integration code
  source: https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ride-hailing-mobility/open-source-bike-share/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.5
  mcp: *id001
  name: EuroSms
  slug: eurosms
  status: profiled
  tags: *id002
  url: /providers/eurosms/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: thin
  in_catalog: true
  kin_score: 27.5
  mcp: *id007
  name: Textmagic
  slug: textmagic
  status: profiled
  tags: *id008
  url: /providers/textmagic/
siblings:
- name: Bolt
  rows: 7
  url: /applications/ride-hailing-mobility/bolt/
- name: Fleetbase (Fleet-Ops)
  rows: 9
  url: /applications/ride-hailing-mobility/fleetbase-fleet-ops/
- name: Grab
  rows: 9
  url: /applications/ride-hailing-mobility/grab/
- name: Lime
  rows: 5
  url: /applications/ride-hailing-mobility/lime/
- name: Lyft
  rows: 4
  url: /applications/ride-hailing-mobility/lyft/
- name: Namma Yatri
  rows: 41
  url: /applications/ride-hailing-mobility/namma-yatri/
- name: Uber
  rows: 4
  url: /applications/ride-hailing-mobility/uber/
sitemap: true
title: 'Open Source Bike Share: Ride-Hailing & Micromobility reference app'
---
