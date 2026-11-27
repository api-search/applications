---
app: Headspace
app_slug: headspace
app_url: https://www.headspace.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Qualtrics
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
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
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id003
      status: none
    slug: branch-io
    status: profiled
    tags: &id004
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id005
      status: none
    slug: qualtrics
    status: profiled
    tags: &id006
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: common
  name: Qualtrics
  provider: qualtrics
  says: ships the Qualtrics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
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
    mcp: &id007
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id008
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.getsomeheadspace.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mental-health-meditation/headspace/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id003
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id004
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id005
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id006
  url: /providers/qualtrics/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id007
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id008
  url: /providers/sentry-system/
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
- name: Heylinda
  rows: 1
  url: /applications/mental-health-meditation/heylinda/
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
title: 'Headspace: Mental Health, Meditation & Sleep reference app'
---
