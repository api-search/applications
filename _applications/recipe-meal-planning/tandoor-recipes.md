---
app: Tandoor Recipes
app_slug: tandoor-recipes
app_url: https://github.com/TandoorRecipes/recipes
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.30.10
  key: AE-130.30.10
  layer: domain
  name: Food Composition Databases
  providers:
  - usda
  url: /capabilities/nutrition-food-data/
  via_parent: Nutrition & Food Data
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Home Assistant
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - dropbox
  - nextcloud
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - authentik
  - github
  - google-identity-platform
  - keycloak
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - google-gemini
  - openai
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: agent
  name: Model Routing & Gateways
  providers:
  - openrouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: recipe-meal-planning
  name: Recipes & Meal Planning
  url: /applications/recipe-meal-planning/
counts:
  declared: 9
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
- route: documentation
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
- route: documentation
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
- route: documentation
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/connectors.md
- route: documentation
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/external_recipes.md
- route: documentation
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/telegram_bot.md
- route: source code
  url: https://api.github.com/repos/TandoorRecipes/recipes/contents/cookbook/provider
- route: source code
  url: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/recipes/settings.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id003
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id004
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: dropbox
  provider: dropbox
  says: ships the dropbox SDK or integration code
  source: https://api.github.com/repos/TandoorRecipes/recipes/contents/cookbook/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id015
      status: none
    slug: nextcloud
    status: profiled
    tags: &id016
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: common
  name: nextcloud
  provider: nextcloud
  says: ships the nextcloud SDK or integration code
  source: https://api.github.com/repos/TandoorRecipes/recipes/contents/cookbook/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id021
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id022
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
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id025
      status: none
    slug: usda
    status: profiled
    tags: &id026
    - Agriculture
    - Food Safety
    - Nutrition
    - Statistics
    url: /providers/usda/
  layer: domain
  name: usda
  provider: usda
  says: ships the usda SDK or integration code
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/recipes/settings.py
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
    agent_readiness: 37.2
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id001
      status: none
    slug: authentik
    status: profiled
    tags: &id002
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
  layer: common
  name: authentik
  provider: authentik
  says: lists authentik as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
  tier: declared
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: github
  provider: github
  says: lists github as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id007
      status: none
    slug: google-gemini
    status: profiled
    tags: &id008
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: google-gemini
  provider: google-gemini
  says: lists google-gemini as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
  tier: declared
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
    mcp: &id009
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id010
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: google-identity-platform
  provider: google-identity-platform
  says: lists google-identity-platform as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id011
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id012
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant
  provider: home-assistant
  says: lists Home Assistant as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/connectors.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id013
      status: none
    slug: keycloak
    status: profiled
    tags: &id014
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: common
  name: keycloak
  provider: keycloak
  says: lists keycloak as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
  tier: declared
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
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id017
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: openai
  provider: openai
  says: lists openai as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id019
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: agent
  name: openrouter
  provider: openrouter
  says: lists openrouter as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id023
      status: none
    slug: telegram
    status: profiled
    tags: &id024
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: telegram
  provider: telegram
  says: lists telegram as an integration
  source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/telegram_bot.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recipe-meal-planning/tandoor-recipes/
providers:
- agent_band: agent-ready
  agent_readiness: 37.2
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id001
  name: authentik
  slug: authentik
  status: profiled
  tags: *id002
  url: /providers/authentik/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id003
  name: dropbox
  slug: dropbox
  status: profiled
  tags: *id004
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id005
  name: github
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id007
  name: google-gemini
  slug: google-gemini
  status: profiled
  tags: *id008
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id009
  name: google-identity-platform
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id011
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id012
  url: /providers/home-assistant/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id013
  name: keycloak
  slug: keycloak
  status: profiled
  tags: *id014
  url: /providers/keycloak/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id015
  name: nextcloud
  slug: nextcloud
  status: profiled
  tags: *id016
  url: /providers/nextcloud/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id017
  name: openai
  slug: openai
  status: profiled
  tags: *id018
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id019
  name: openrouter
  slug: openrouter
  status: profiled
  tags: *id020
  url: /providers/openrouter/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id021
  name: stripe
  slug: stripe
  status: profiled
  tags: *id022
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id023
  name: telegram
  slug: telegram
  status: profiled
  tags: *id024
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id025
  name: usda
  slug: usda
  status: profiled
  tags: *id026
  url: /providers/usda/
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
- name: Paprika Recipe Manager
  rows: 3
  url: /applications/recipe-meal-planning/paprika-recipe-manager/
sitemap: true
title: 'Tandoor Recipes: Recipes & Meal Planning reference app'
---
