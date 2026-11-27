---
app: Mealime
app_slug: mealime
app_url: https://www.mealime.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: recipe-meal-planning
  name: Recipes & Meal Planning
  url: /applications/recipe-meal-planning/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.mealime/latest/
- route: integrations page
  url: https://www.mealime.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id001
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id002
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mealime/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recipe-meal-planning/mealime/
providers:
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id001
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id002
  url: /providers/sentry-system/
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
- name: Paprika Recipe Manager
  rows: 3
  url: /applications/recipe-meal-planning/paprika-recipe-manager/
- name: Tandoor Recipes
  rows: 13
  url: /applications/recipe-meal-planning/tandoor-recipes/
sitemap: true
title: 'Mealime: Recipes & Meal Planning reference app'
---
