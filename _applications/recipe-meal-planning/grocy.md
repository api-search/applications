---
app: Grocy
app_slug: grocy
app_url: https://github.com/grocy/grocy
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
  url: https://raw.githubusercontent.com/grocy/grocy/master/composer.json
- route: source code
  url: https://api.github.com/repos/grocy/grocy/contents/plugins
- route: source code
  url: https://raw.githubusercontent.com/grocy/grocy/master/config-dist.php
integrations:
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
    mcp: &id001
      status: none
    slug: open-food-facts
    status: profiled
    tags: &id002
    - Food
    - Nutrition
    - Open Data
    - Product Data
    url: /providers/open-food-facts/
  layer: domain
  name: open-food-facts
  provider: open-food-facts
  says: ships the open-food-facts SDK or integration code
  source: https://raw.githubusercontent.com/grocy/grocy/master/config-dist.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recipe-meal-planning/grocy/
providers:
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id001
  name: open-food-facts
  slug: open-food-facts
  status: profiled
  tags: *id002
  url: /providers/open-food-facts/
siblings:
- name: KitchenOwl
  rows: 2
  url: /applications/recipe-meal-planning/kitchenowl/
- name: Mealie
  rows: 1
  url: /applications/recipe-meal-planning/mealie/
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
title: 'Grocy: Recipes & Meal Planning reference app'
---
