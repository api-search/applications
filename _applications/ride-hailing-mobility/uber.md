---
app: Uber
app_slug: uber
app_url: https://www.uber.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.30.50
  key: AE-210.30.50
  layer: domain
  name: Micromobility & Bike Share
  providers:
  - Lime
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
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
  declared: 1
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
- route: integrations page
  url: https://www.uber.com/us/en/ride/how-it-works/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
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
    mcp: &id004
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id005
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Tech Lab
  provider: iab-tech-lab
  says: ships the IAB Tech Lab SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.7
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id006
      status: none
    slug: lime
    status: profiled
    tags: &id007
    - Electric Bikes
    - Electric Scooters
    - Micromobility
    - Shared Mobility
    url: /providers/lime/
  layer: domain
  name: Lime
  provider: lime
  says: lists Lime as an integration
  source: https://www.uber.com/us/en/ride/how-it-works/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ride-hailing-mobility/uber/
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
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id004
  name: IAB Tech Lab
  slug: iab-tech-lab
  status: profiled
  tags: *id005
  url: /providers/iab-tech-lab/
- agent_band: agent-aware
  agent_readiness: 16.7
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id006
  name: Lime
  slug: lime
  status: profiled
  tags: *id007
  url: /providers/lime/
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
- name: Open Source Bike Share
  rows: 4
  url: /applications/ride-hailing-mobility/open-source-bike-share/
sitemap: true
title: 'Uber: Ride-Hailing & Micromobility reference app'
---
