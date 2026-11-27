---
app: mySolarEdge
app_slug: mysolaredge
app_url: https://www.solaredge.com/
author: API Evangelist
capabilities:
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
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: solar-energy-monitoring
  name: Home Energy & Solar Monitoring
  url: /applications/solar-energy-monitoring/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.solaredge.homeowner
integrations:
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
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id003
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/solar-energy-monitoring/mysolaredge/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id002
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id003
  url: /providers/google-firebase/
siblings:
- name: Enphase App (Enlighten)
  rows: 4
  url: /applications/solar-energy-monitoring/enphase-app-enlighten/
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
- name: Sense
  rows: 6
  url: /applications/solar-energy-monitoring/sense/
sitemap: true
title: 'mySolarEdge: Home Energy & Solar Monitoring reference app'
---
