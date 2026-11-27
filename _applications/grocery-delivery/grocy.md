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
  - Open Food Facts
  url: /capabilities/nutrition-food-data/
  via_parent: Nutrition & Food Data
category:
  id: grocery-delivery
  name: Grocery Delivery
  url: /applications/grocery-delivery/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/grocy/grocy/blob/master/composer.json
- route: source code
  url: https://github.com/grocy/grocy/blob/master/config-dist.php
- route: source code
  url: https://github.com/grocy/grocy/tree/master/plugins
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
  name: Open Food Facts
  provider: open-food-facts
  says: ships the Open Food Facts SDK or integration code
  source: https://github.com/grocy/grocy/tree/master/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/grocery-delivery/grocy/
providers:
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id001
  name: Open Food Facts
  slug: open-food-facts
  status: profiled
  tags: *id002
  url: /providers/open-food-facts/
siblings:
- name: Ever Demand
  rows: 12
  url: /applications/grocery-delivery/ever-demand/
- name: Instacart
  rows: 8
  url: /applications/grocery-delivery/instacart/
- name: Open Food Network
  rows: 8
  url: /applications/grocery-delivery/open-food-network/
- name: Picnic
  rows: 4
  url: /applications/grocery-delivery/picnic/
- name: Shipt
  rows: 5
  url: /applications/grocery-delivery/shipt/
- name: Weee!
  rows: 7
  url: /applications/grocery-delivery/weee/
sitemap: true
title: 'Grocy: Grocery Delivery reference app'
---
