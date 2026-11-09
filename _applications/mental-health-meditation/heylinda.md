---
app: Heylinda
app_slug: heylinda
app_url: https://github.com/heylinda/heylinda-app
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: mental-health-meditation
  name: Mental Health, Meditation & Sleep
  url: /applications/mental-health-meditation/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/heylinda/heylinda-app/blob/main/package.json
integrations:
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://github.com/heylinda/heylinda-app/blob/main/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mental-health-meditation/heylinda/
providers:
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
siblings:
- name: Baseline
  rows: 8
  url: /applications/mental-health-meditation/baseline/
- name: BetterHelp
  rows: 3
  url: /applications/mental-health-meditation/betterhelp/
- name: Calm
  rows: 6
  url: /applications/mental-health-meditation/calm/
- name: Headspace
  rows: 4
  url: /applications/mental-health-meditation/headspace/
- name: Medito
  rows: 7
  url: /applications/mental-health-meditation/medito/
- name: Pixy Mood Tracker
  rows: 4
  url: /applications/mental-health-meditation/pixy-mood-tracker/
- name: Sleep as Android
  rows: 19
  url: /applications/mental-health-meditation/sleep-as-android/
sitemap: true
title: 'Heylinda: Mental Health, Meditation & Sleep reference app'
---
