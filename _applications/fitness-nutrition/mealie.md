---
app: Mealie
app_slug: mealie
app_url: https://github.com/mealie-recipes/mealie
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: agent
  name: Artificial Intelligence Management
  providers:
  - openai
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
category:
  id: fitness-nutrition
  name: Fitness & Nutrition Tracking
  url: /applications/fitness-nutrition/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/pyproject.toml
integrations:
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id001
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: openai
  provider: openai
  says: ships the openai SDK or integration code
  source: https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/pyproject.toml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/mealie/
providers:
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id001
  name: openai
  slug: openai
  status: profiled
  tags: *id002
  url: /providers/openai/
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
title: 'Mealie: Fitness & Nutrition Tracking reference app'
---
