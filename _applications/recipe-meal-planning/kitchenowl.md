---
app: KitchenOwl
app_slug: kitchenowl
app_url: https://github.com/TomBursch/kitchenowl
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - apple
  - google-identity-platform
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: recipe-meal-planning
  name: Recipes & Meal Planning
  url: /applications/recipe-meal-planning/
counts:
  declared: 1
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/TomBursch/kitchenowl/main/backend/pyproject.toml
- route: dependency manifest
  url: https://raw.githubusercontent.com/TomBursch/kitchenowl/main/kitchenowl/pubspec.yaml
- route: documentation
  url: https://raw.githubusercontent.com/TomBursch/kitchenowl/main/docs/docs/self-hosting/oidc.md
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
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
  layer: common
  name: apple
  provider: apple
  says: ships the apple SDK or integration code
  source: https://raw.githubusercontent.com/TomBursch/kitchenowl/main/kitchenowl/pubspec.yaml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id003
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id004
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: google-identity-platform
  provider: google-identity-platform
  says: lists google-identity-platform as an integration
  source: https://raw.githubusercontent.com/TomBursch/kitchenowl/main/docs/docs/self-hosting/oidc.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recipe-meal-planning/kitchenowl/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: apple
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id003
  name: google-identity-platform
  slug: google-identity-platform
  status: profiled
  tags: *id004
  url: /providers/google-identity-platform/
siblings:
- name: Grocy
  rows: 1
  url: /applications/recipe-meal-planning/grocy/
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
title: 'KitchenOwl: Recipes & Meal Planning reference app'
---
