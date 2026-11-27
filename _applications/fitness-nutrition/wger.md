---
app: wger
app_slug: wger
app_url: https://github.com/wger-project/wger
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.30.10
  key: AE-130.30.10
  layer: domain
  name: Food Composition Databases
  providers:
  - open-food-facts
  url: /capabilities/nutrition-food-data/
  via_parent: Nutrition & Food Data
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
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
- route: documentation
  url: https://raw.githubusercontent.com/wger-project/wger/master/README.md
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
  source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 66.2
    mcp: &id003
      status: none
    slug: open-food-facts
    status: profiled
    tags: &id004
    - Food
    - Nutrition
    - Open Data
    - Product Data
    url: /providers/open-food-facts/
  layer: domain
  name: open-food-facts
  provider: open-food-facts
  says: ships the open-food-facts SDK or integration code
  source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/wger/
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
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id003
  name: open-food-facts
  slug: open-food-facts
  status: profiled
  tags: *id004
  url: /providers/open-food-facts/
siblings:
- name: Cronometer
  rows: 13
  url: /applications/fitness-nutrition/cronometer/
- name: Endurain
  rows: 3
  url: /applications/fitness-nutrition/endurain/
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
sitemap: true
title: 'wger: Fitness & Nutrition Tracking reference app'
---
