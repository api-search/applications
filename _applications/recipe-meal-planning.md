---
access: understanding
agent_layer: []
apps:
- anchor: mealie
  counts:
    declared: 0
    observed: 1
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
    layer: agent
    name: openai
    provider: openai
    says: ships the openai SDK or integration code
    source: https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/pyproject.toml
    tier: observed
  kind: self-hosted
  name: Mealie
  page: /applications/recipe-meal-planning/mealie/
  slug: mealie
  url: https://github.com/mealie-recipes/mealie
- anchor: tandoor-recipes
  counts:
    declared: 9
    observed: 4
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
    layer: common
    name: telegram
    provider: telegram
    says: lists telegram as an integration
    source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/telegram_bot.md
    tier: declared
  kind: self-hosted
  name: Tandoor Recipes
  page: /applications/recipe-meal-planning/tandoor-recipes/
  slug: tandoor-recipes
  url: https://github.com/TandoorRecipes/recipes
- anchor: kitchenowl
  counts:
    declared: 1
    observed: 1
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
    layer: common
    name: google-identity-platform
    provider: google-identity-platform
    says: lists google-identity-platform as an integration
    source: https://raw.githubusercontent.com/TomBursch/kitchenowl/main/docs/docs/self-hosting/oidc.md
    tier: declared
  kind: self-hosted
  name: KitchenOwl
  page: /applications/recipe-meal-planning/kitchenowl/
  slug: kitchenowl
  url: https://github.com/TomBursch/kitchenowl
- anchor: grocy
  counts:
    declared: 0
    observed: 1
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
    layer: domain
    name: open-food-facts
    provider: open-food-facts
    says: ships the open-food-facts SDK or integration code
    source: https://raw.githubusercontent.com/grocy/grocy/master/config-dist.php
    tier: observed
  kind: self-hosted
  name: Grocy
  page: /applications/recipe-meal-planning/grocy/
  slug: grocy
  url: https://github.com/grocy/grocy
- anchor: paprika-recipe-manager
  counts:
    declared: 0
    observed: 3
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
    layer: common
    name: Visual Studio App Center Crashes
    provider: microsoft-app-center
    says: ships the Visual Studio App Center Crashes SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
    tier: observed
  kind: commercial
  name: Paprika Recipe Manager
  page: /applications/recipe-meal-planning/paprika-recipe-manager/
  slug: paprika-recipe-manager
  url: https://www.paprikaapp.com/
- anchor: mealime
  counts:
    declared: 0
    observed: 1
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
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mealime/latest/
    tier: observed
  kind: commercial
  name: Mealime
  page: /applications/recipe-meal-planning/mealime/
  slug: mealime
  url: https://www.mealime.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: recipe-meal-planning
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Food & Drink
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Food & Drink
  store: google-play
  url: https://play.google.com/store/apps/category/FOOD_AND_DRINK
- category: Recipe Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#recipe-management
name: Recipes & Meal Planning
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  fit: exact
  layer: domain
  why: Nutrient and barcode lookup for ingredients (USDA FDC, Open Food Facts)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI recipe import, ingredient parsing and photo/video transcription
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LiteLLM/OpenRouter routing across model vendors
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Recipe files synced from Dropbox/Nextcloud
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: Shopping list pushed to a home hub
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: Chat bot adds shopping-list items
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Hosted-instance subscriptions
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Household sign-in via Google, Apple, GitHub or an OIDC IdP
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics SDKs ship in the mobile apps (Exodus)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting SDKs ship in the mobile apps (Exodus)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Grocy
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: open-food-facts
      slug: open-food-facts
      sources:
      - https://raw.githubusercontent.com/grocy/grocy/master/config-dist.php
      status: profiled
      tags:
      - Food
      - Nutrition
      - Open Data
      - Product Data
      tier: observed
      url: /providers/open-food-facts/
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - Tandoor Recipes
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: usda
      slug: usda
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/recipes/settings.py
      status: profiled
      tags:
      - Agriculture
      - Food Safety
      - Nutrition
      - Statistics
      tier: observed
      url: /providers/usda/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Tandoor Recipes
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        source: https://www.home-assistant.io/integrations/mcp_server/
        status: verified
      name: Home Assistant
      slug: home-assistant
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/connectors.md
      status: profiled
      tags:
      - Community
      - Home Automation
      - IoT
      - Open Source
      tier: declared
      url: /providers/home-assistant/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - KitchenOwl
      - Tandoor Recipes
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: google-identity-platform
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
      - https://raw.githubusercontent.com/TomBursch/kitchenowl/main/docs/docs/self-hosting/oidc.md
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - KitchenOwl
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/TomBursch/kitchenowl/main/kitchenowl/pubspec.yaml
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Tandoor Recipes
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: github
      slug: github
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Tandoor Recipes
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: authentik
      slug: authentik
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: declared
      url: /providers/authentik/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Tandoor Recipes
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: keycloak
      slug: keycloak
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/authentication.md
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: declared
      url: /providers/keycloak/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Tandoor Recipes
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: dropbox
      slug: dropbox
      sources:
      - https://api.github.com/repos/TandoorRecipes/recipes/contents/cookbook/provider
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Tandoor Recipes
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: nextcloud
      slug: nextcloud
      sources:
      - https://api.github.com/repos/TandoorRecipes/recipes/contents/cookbook/provider
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Mealime
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mealime/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: null
      agent_readiness: null
      apps:
      - Paprika Recipe Manager
      band: null
      in_catalog: false
      kin_score: null
      mcp: &id001
        status: unchecked
      name: Visual Studio App Center Crashes
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
      status: queued for profiling
      tags: &id002 []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Paprika Recipe Manager
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: Flurry
      slug: flurry
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
      status: profiled
      tags:
      - Analytics
      - Company
      - Mobile
      - SDK
      tier: observed
      url: /providers/flurry/
    - agent_band: null
      agent_readiness: null
      apps:
      - Paprika Recipe Manager
      band: null
      in_catalog: false
      kin_score: null
      mcp: *id001
      name: Visual Studio App Center Analytics
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hindsightlabs.paprika.android.v3/latest/
      status: queued for profiling
      tags: *id002
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Tandoor Recipes
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Tandoor Recipes
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: telegram
      slug: telegram
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/telegram_bot.md
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: declared
      url: /providers/telegram/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Mealie
      - Tandoor Recipes
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: openai
      slug: openai
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
      - https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Tandoor Recipes
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: google-gemini
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: declared
      url: /providers/google-gemini/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Tandoor Recipes
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: openrouter
      slug: openrouter
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/docs/features/ai.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: declared
      url: /providers/openrouter/
  layer: agent
summary:
  coverage_pct: 94.4
  declared_only: 8
  distinct_providers: 18
  in_catalog: 17
  mcp:
    documented: 0
    none: 10
    unchecked: 1
    verified: 7
  mcp_verified: 7
  mean_kin_score: 56.0
  observed: 10
  queued: 1
  reference_apps: 6
title: 'Recipes & Meal Planning: application blueprint'
---
