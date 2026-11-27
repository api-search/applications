---
app: Sense
app_slug: sense
app_url: https://sense.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Wootric
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
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
  id: solar-energy-monitoring
  name: Home Energy & Solar Monitoring
  url: /applications/solar-energy-monitoring/
counts:
  declared: 0
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.sense.androidclient
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
    mcp: &id002
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id003
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
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
    mcp: &id004
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id005
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
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
    mcp: &id006
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id007
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
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
    mcp: &id008
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id009
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id010
      status: none
    slug: wootric
    status: profiled
    tags: &id011
    - CES
    - CSAT
    - Customer Experience
    - NPS
    url: /providers/wootric/
  layer: common
  name: Wootric
  provider: wootric
  says: ships the Wootric SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/solar-energy-monitoring/sense/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id002
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id003
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id004
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id005
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id006
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id007
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id008
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id009
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id010
  name: Wootric
  slug: wootric
  status: profiled
  tags: *id011
  url: /providers/wootric/
siblings:
- name: Enphase App (Enlighten)
  rows: 4
  url: /applications/solar-energy-monitoring/enphase-app-enlighten/
- name: mySolarEdge
  rows: 2
  url: /applications/solar-energy-monitoring/mysolaredge/
- name: OpenEMS
  rows: 27
  url: /applications/solar-energy-monitoring/openems/
- name: OpenEnergyMonitor (emonHub)
  rows: 11
  url: /applications/solar-energy-monitoring/openenergymonitor-emonhub/
- name: Predbat
  rows: 31
  url: /applications/solar-energy-monitoring/predbat/
- name: PVOutput
  rows: 22
  url: /applications/solar-energy-monitoring/pvoutput/
sitemap: true
title: 'Sense: Home Energy & Solar Monitoring reference app'
---
