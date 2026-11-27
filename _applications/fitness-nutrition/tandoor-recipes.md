---
app: Tandoor Recipes
app_slug: tandoor-recipes
app_url: https://github.com/TandoorRecipes/recipes
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - amazon-web-services
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - stripe
  url: /capabilities/subscription-billing-revenue-management/
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
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
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
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id003
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id004
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: stripe
  provider: stripe
  says: ships the stripe SDK or integration code
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/tandoor-recipes/
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
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id003
  name: stripe
  slug: stripe
  status: profiled
  tags: *id004
  url: /providers/stripe/
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
- name: wger
  rows: 2
  url: /applications/fitness-nutrition/wger/
sitemap: true
title: 'Tandoor Recipes: Fitness & Nutrition Tracking reference app'
---
