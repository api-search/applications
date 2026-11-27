---
app: Endurain
app_slug: endurain
app_url: https://github.com/joaovitoriasilva/endurain
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.30
  key: AE-130.10.30
  layer: domain
  name: Running & Cycling Tracking
  providers:
  - strava
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - garmin
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - amazon-web-services
  url: /capabilities/asset-storage-tiering/
  via_parent: null
category:
  id: fitness-nutrition
  name: Fitness & Nutrition Tracking
  url: /applications/fitness-nutrition/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
- route: documentation
  url: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/README.md
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: amazon-web-services
  provider: amazon-web-services
  says: ships the amazon-web-services SDK or integration code
  source: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id003
      status: none
    slug: garmin
    status: profiled
    tags: &id004
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
  layer: domain
  name: garmin
  provider: garmin
  says: ships the garmin SDK or integration code
  source: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.3
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id005
      status: none
    slug: strava
    status: profiled
    tags: &id006
    - Cycling
    - Fitness
    - Fitness Tracking
    - Running
    url: /providers/strava/
  layer: domain
  name: strava
  provider: strava
  says: ships the strava SDK or integration code
  source: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/endurain/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: amazon-web-services
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id003
  name: garmin
  slug: garmin
  status: profiled
  tags: *id004
  url: /providers/garmin/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id005
  name: strava
  slug: strava
  status: profiled
  tags: *id006
  url: /providers/strava/
siblings:
- name: Cronometer
  rows: 13
  url: /applications/fitness-nutrition/cronometer/
- name: FitTrackee
  rows: 1
  url: /applications/fitness-nutrition/fittrackee/
- name: Lose It!
  rows: 9
  url: /applications/fitness-nutrition/lose-it/
- name: Mealie
  rows: 1
  url: /applications/fitness-nutrition/mealie/
- name: MyFitnessPal
  rows: 26
  url: /applications/fitness-nutrition/myfitnesspal/
- name: SparkyFitness
  rows: 28
  url: /applications/fitness-nutrition/sparkyfitness/
- name: Strava
  rows: 17
  url: /applications/fitness-nutrition/strava/
- name: Tandoor Recipes
  rows: 2
  url: /applications/fitness-nutrition/tandoor-recipes/
- name: wger
  rows: 2
  url: /applications/fitness-nutrition/wger/
sitemap: true
title: 'Endurain: Fitness & Nutrition Tracking reference app'
---
