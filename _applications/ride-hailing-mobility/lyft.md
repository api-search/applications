---
app: Lyft
app_slug: lyft
app_url: https://www.lyft.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Singular
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
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - IAB Tech Lab
  url: /capabilities/programmatic-sales-management/
  via_parent: null
category:
  id: ride-hailing-mobility
  name: Ride-Hailing & Micromobility
  url: /applications/ride-hailing-mobility/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
- route: documentation
  url: https://help.lyft.com/hc/en-us/all/articles/115013080048-Accepted-payment-methods
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id002
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 36.9
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id003
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id004
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Tech Lab
  provider: iab-tech-lab
  says: ships the IAB Tech Lab SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
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
    agent_band: agent-ready
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id007
      status: none
    slug: singular
    status: profiled
    tags: &id008
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: common
  name: Singular
  provider: singular
  says: ships the Singular SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ride-hailing-mobility/lyft/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id003
  name: IAB Tech Lab
  slug: iab-tech-lab
  status: profiled
  tags: *id004
  url: /providers/iab-tech-lab/
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
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id007
  name: Singular
  slug: singular
  status: profiled
  tags: *id008
  url: /providers/singular/
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
- name: Namma Yatri
  rows: 41
  url: /applications/ride-hailing-mobility/namma-yatri/
- name: Open Source Bike Share
  rows: 4
  url: /applications/ride-hailing-mobility/open-source-bike-share/
- name: Uber
  rows: 4
  url: /applications/ride-hailing-mobility/uber/
sitemap: true
title: 'Lyft: Ride-Hailing & Micromobility reference app'
---
