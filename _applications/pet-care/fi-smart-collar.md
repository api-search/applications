---
app: Fi Smart Collar
app_slug: fi-smart-collar
app_url: https://tryfi.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.20
  key: AE-130.10.20
  layer: domain
  name: Activity & Step Tracking
  providers:
  - Strava
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Apple Watch
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics / Crashlytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: pet-care
  name: Pet Care
  url: /applications/pet-care/
counts:
  declared: 2
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
- route: documentation
  url: https://blog.fitracking.com/the-first-ai-smart-collar-for-your-dog/
- route: documentation
  url: https://support.strava.com/hc/en-us/articles/24330606303501-The-Fi-Collar-and-Strava
- route: source code
  url: https://www.tryfi.com/
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
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id004
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id005
      status: none
    slug: segment
    status: profiled
    tags: &id006
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.barkinglabs.fi/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Watch
  provider: apple
  says: lists Apple Watch as an integration
  source: https://blog.fitracking.com/the-first-ai-smart-collar-for-your-dog/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.20
    key: AE-130.10.20
    name: Activity & Step Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.3
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id007
      status: none
    slug: strava
    status: profiled
    tags: &id008
    - Cycling
    - Fitness
    - Fitness Tracking
    - Running
    url: /providers/strava/
  layer: domain
  name: Strava
  provider: strava
  says: lists Strava as an integration
  source: https://support.strava.com/hc/en-us/articles/24330606303501-The-Fi-Collar-and-Strava
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pet-care/fi-smart-collar/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple Watch
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Google Firebase Analytics / Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id005
  name: Segment
  slug: segment
  status: profiled
  tags: *id006
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id007
  name: Strava
  slug: strava
  status: profiled
  tags: *id008
  url: /providers/strava/
siblings:
- name: Chewy
  rows: 4
  url: /applications/pet-care/chewy/
- name: oh-my-petcare
  rows: 2
  url: /applications/pet-care/oh-my-petcare/
- name: PawSome AI
  rows: 2
  url: /applications/pet-care/pawsome-ai/
- name: PetDesk
  rows: 10
  url: /applications/pet-care/petdesk/
- name: PETLIBRO
  rows: 10
  url: /applications/pet-care/petlibro/
- name: Rover
  rows: 10
  url: /applications/pet-care/rover/
- name: Tractive
  rows: 7
  url: /applications/pet-care/tractive/
sitemap: true
title: 'Fi Smart Collar: Pet Care reference app'
---
