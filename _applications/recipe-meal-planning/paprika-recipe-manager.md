---
app: Paprika Recipe Manager
app_slug: paprika-recipe-manager
app_url: https://www.paprikaapp.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Visual Studio App Center Crashes
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Flurry
  - Visual Studio App Center Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: recipe-meal-planning
  name: Recipes & Meal Planning
  url: /applications/recipe-meal-planning/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
- route: integrations page
  url: https://www.paprikaapp.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.6
    mcp: &id002
      status: none
    slug: flurry
    status: profiled
    tags: &id003
    - Analytics
    - Company
    - Mobile
    - SDK
    url: /providers/flurry/
  layer: common
  name: Flurry
  provider: flurry
  says: ships the Flurry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id004
      status: unchecked
    slug: microsoft-app-center
    status: queued for profiling
    tags: &id005 []
    url: null
  layer: common
  name: Visual Studio App Center Analytics
  provider: microsoft-app-center
  says: ships the Visual Studio App Center Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Visual Studio App Center Crashes
  provider: microsoft-app-center
  says: ships the Visual Studio App Center Crashes SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recipe-meal-planning/paprika-recipe-manager/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.6
  mcp: *id002
  name: Flurry
  slug: flurry
  status: profiled
  tags: *id003
  url: /providers/flurry/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id004
  name: Visual Studio App Center Analytics
  slug: microsoft-app-center
  status: queued for profiling
  tags: *id005
  url: null
siblings:
- name: Grocy
  rows: 1
  url: /applications/recipe-meal-planning/grocy/
- name: KitchenOwl
  rows: 2
  url: /applications/recipe-meal-planning/kitchenowl/
- name: Mealie
  rows: 1
  url: /applications/recipe-meal-planning/mealie/
- name: Mealime
  rows: 1
  url: /applications/recipe-meal-planning/mealime/
- name: Tandoor Recipes
  rows: 13
  url: /applications/recipe-meal-planning/tandoor-recipes/
sitemap: true
title: 'Paprika Recipe Manager: Recipes & Meal Planning reference app'
---
