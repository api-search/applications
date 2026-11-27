---
app: Transit
app_slug: transit
app_url: https://transitapp.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.30.10
  key: AE-210.30.10
  layer: domain
  name: Ride Hailing
  providers:
  - Curb
  - iCabbi
  - Lyft
  - Ola
  - Uber
  - Via
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
  - Amplitude
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: public-transit
  name: Public Transit
  url: /applications/public-transit/
counts:
  declared: 6
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
- route: integrations page
  url: https://resources.transitapp.com/article/403-ridehail-and-taxi
- route: integrations page
  url: https://transitapp.com/partners
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
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
    mcp: &id006
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id007
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id004
      status: unchecked
    slug: curb-mobility
    status: profiled
    tags: &id005
    - Company
    - Mobility
    - Ride Hailing
    - Taxi
    url: /providers/curb-mobility/
  layer: domain
  name: Curb
  provider: curb-mobility
  says: lists Curb as an integration
  source: https://resources.transitapp.com/article/403-ridehail-and-taxi
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id008
      status: unchecked
    slug: icabbi
    status: profiled
    tags: &id009
    - Fleet Management
    - NEMT
    - Taxi Dispatch
    - Voice AI
    url: /providers/icabbi/
  layer: domain
  name: iCabbi
  provider: icabbi
  says: lists iCabbi as an integration
  source: https://resources.transitapp.com/article/403-ridehail-and-taxi
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id010
      status: none
    slug: lyft
    status: profiled
    tags: &id011
    - Micromobility
    - Mobility
    - Ride Hailing
    - Transportation
    url: /providers/lyft/
  layer: domain
  name: Lyft
  provider: lyft
  says: lists Lyft as an integration
  source: https://resources.transitapp.com/article/403-ridehail-and-taxi
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 8.7
    band: emerging
    in_catalog: true
    kin_score: 25.1
    mcp: &id012
      status: unknown
    slug: ola
    status: profiled
    tags: &id013
    - Geocoding
    - Maps
    - Ride Hailing
    - Transportation
    url: /providers/ola/
  layer: domain
  name: Ola
  provider: ola
  says: lists Ola as an integration
  source: https://resources.transitapp.com/article/403-ridehail-and-taxi
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id014
      status: none
    slug: uber
    status: profiled
    tags: &id015
    - Food Delivery
    - Ride Hailing
    - Taxis
    - Transportation
    url: /providers/uber/
  layer: domain
  name: Uber
  provider: uber
  says: lists Uber as an integration
  source: https://resources.transitapp.com/article/403-ridehail-and-taxi
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.9
    mcp: &id016
      status: unknown
    slug: via-transportation
    status: profiled
    tags: &id017
    - Mobility
    - On-Demand
    - Public Transit
    - Transportation
    url: /providers/via-transportation/
  layer: domain
  name: Via
  provider: via-transportation
  says: lists Via as an integration
  source: https://resources.transitapp.com/article/403-ridehail-and-taxi
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/public-transit/transit/
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
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id004
  name: Curb
  slug: curb-mobility
  status: profiled
  tags: *id005
  url: /providers/curb-mobility/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id006
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id007
  url: /providers/google-firebase/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id008
  name: iCabbi
  slug: icabbi
  status: profiled
  tags: *id009
  url: /providers/icabbi/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id010
  name: Lyft
  slug: lyft
  status: profiled
  tags: *id011
  url: /providers/lyft/
- agent_band: agent-aware
  agent_readiness: 8.7
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id012
  name: Ola
  slug: ola
  status: profiled
  tags: *id013
  url: /providers/ola/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id014
  name: Uber
  slug: uber
  status: profiled
  tags: *id015
  url: /providers/uber/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.9
  mcp: *id016
  name: Via
  slug: via-transportation
  status: profiled
  tags: *id017
  url: /providers/via-transportation/
siblings:
- name: Citymapper
  rows: 23
  url: /applications/public-transit/citymapper/
- name: Moovit
  rows: 17
  url: /applications/public-transit/moovit/
- name: MOTIS (Transitous)
  rows: 7
  url: /applications/public-transit/motis-transitous/
- name: OneBusAway Android
  rows: 8
  url: /applications/public-transit/onebusaway-android/
- name: OpenTripPlanner
  rows: 9
  url: /applications/public-transit/opentripplanner/
sitemap: true
title: 'Transit: Public Transit reference app'
---
