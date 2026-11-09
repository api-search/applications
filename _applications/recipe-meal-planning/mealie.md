---
app: Mealie
app_slug: mealie
app_url: https://github.com/mealie-recipes/mealie
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - openai
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: recipe-meal-planning
  name: Recipes & Meal Planning
  url: /applications/recipe-meal-planning/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/pyproject.toml
- route: documentation
  url: https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/docs/docs/documentation/getting-started/installation/ai-providers.md
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
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
permalink: /applications/recipe-meal-planning/mealie/
providers:
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id001
  name: openai
  slug: openai
  status: profiled
  tags: *id002
  url: /providers/openai/
siblings:
- name: Grocy
  rows: 1
  url: /applications/recipe-meal-planning/grocy/
- name: KitchenOwl
  rows: 2
  url: /applications/recipe-meal-planning/kitchenowl/
- name: Mealime
  rows: 1
  url: /applications/recipe-meal-planning/mealime/
- name: Paprika Recipe Manager
  rows: 3
  url: /applications/recipe-meal-planning/paprika-recipe-manager/
- name: Tandoor Recipes
  rows: 13
  url: /applications/recipe-meal-planning/tandoor-recipes/
sitemap: true
title: 'Mealie: Recipes & Meal Planning reference app'
---
