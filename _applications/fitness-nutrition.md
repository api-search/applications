---
access: understanding
agent_layer: []
apps:
- anchor: sparkyfitness
  counts:
    declared: 24
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
  - route: documentation
    url: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: anthropic
    provider: anthropic
    says: ships the anthropic SDK or integration code
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: garmin
    provider: garmin
    says: ships the garmin SDK or integration code
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: google
    provider: google
    says: ships the google SDK or integration code
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: openai
    provider: openai
    says: ships the openai SDK or integration code
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: apple
    provider: apple
    says: lists apple as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: coros
    provider: coros
    says: lists coros as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: fatsecret
    provider: fatsecret
    says: lists fatsecret as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: fitbit
    provider: fitbit
    says: lists fitbit as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.10
      key: AE-130.10.10
      name: Workout Logging
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: free-exercise-db
    provider: free-exercise-db
    says: lists free-exercise-db as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: google
    provider: google
    says: lists google as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: health-canada
    provider: health-canada
    says: lists health-canada as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.10
      key: AE-130.10.10
      name: Workout Logging
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: hevy
    provider: hevy
    says: lists hevy as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: livsmedelsverket
    provider: livsmedelsverket
    says: lists livsmedelsverket as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4070.10
      key: menu-engineering-recipe-management
      name: Menu Engineering & Recipe Management
      url: /capabilities/menu-engineering-recipe-management/
      via_parent: null
    credit: null
    layer: domain
    name: mealie
    provider: mealie
    says: lists mealie as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4070.10
      key: menu-engineering-recipe-management
      name: Menu Engineering & Recipe Management
      url: /capabilities/menu-engineering-recipe-management/
      via_parent: null
    credit: null
    layer: domain
    name: norish
    provider: norish
    says: lists norish as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: nutritionix
    provider: nutritionix
    says: lists nutritionix as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
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
    says: lists open-food-facts as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: oura-ring
    provider: oura-ring
    says: lists oura-ring as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: pikapods
    provider: pikapods
    says: lists pikapods as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: polar
    provider: polar
    says: lists polar as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: strava
    provider: strava
    says: lists strava as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: swiss-food-composition-database
    provider: swiss-food-composition-database
    says: lists swiss-food-composition-database as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4070.10
      key: menu-engineering-recipe-management
      name: Menu Engineering & Recipe Management
      url: /capabilities/menu-engineering-recipe-management/
      via_parent: null
    credit: null
    layer: domain
    name: tandoor
    provider: tandoor
    says: lists tandoor as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
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
    says: lists usda as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.10
      key: AE-130.10.10
      name: Workout Logging
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: wger
    provider: wger
    says: lists wger as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: withings
    provider: withings
    says: lists withings as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: yazio
    provider: yazio
    says: lists yazio as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: zenith-hosting
    provider: zenith-hosting
    says: lists zenith-hosting as an integration
    source: https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
    tier: declared
  kind: self-hosted
  name: SparkyFitness
  page: /applications/fitness-nutrition/sparkyfitness/
  slug: sparkyfitness
  url: https://github.com/CodeWithCJ/SparkyFitness
- anchor: wger
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
  - route: documentation
    url: https://raw.githubusercontent.com/wger-project/wger/master/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: amazon-web-services
    provider: amazon-web-services
    says: ships the amazon-web-services SDK or integration code
    source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
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
    name: open-food-facts
    provider: open-food-facts
    says: ships the open-food-facts SDK or integration code
    source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
    tier: observed
  kind: self-hosted
  name: wger
  page: /applications/fitness-nutrition/wger/
  slug: wger
  url: https://github.com/wger-project/wger
- anchor: endurain
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
  - route: documentation
    url: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: amazon-web-services
    provider: amazon-web-services
    says: ships the amazon-web-services SDK or integration code
    source: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: garmin
    provider: garmin
    says: ships the garmin SDK or integration code
    source: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: strava
    provider: strava
    says: ships the strava SDK or integration code
    source: https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
    tier: observed
  kind: self-hosted
  name: Endurain
  page: /applications/fitness-nutrition/endurain/
  slug: endurain
  url: https://github.com/joaovitoriasilva/endurain
- anchor: fittrackee
  counts:
    declared: 1
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/SamR1/FitTrackee/main/pyproject.toml
  - route: documentation
    url: https://raw.githubusercontent.com/SamR1/FitTrackee/main/README.md
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: openstreetmap
    provider: openstreetmap
    says: lists openstreetmap as an integration
    source: https://raw.githubusercontent.com/SamR1/FitTrackee/main/README.md
    tier: declared
  kind: self-hosted
  name: FitTrackee
  page: /applications/fitness-nutrition/fittrackee/
  slug: fittrackee
  url: https://github.com/SamR1/FitTrackee
- anchor: mealie
  counts:
    declared: 0
    observed: 1
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
    layer: agent
    name: openai
    provider: openai
    says: ships the openai SDK or integration code
    source: https://raw.githubusercontent.com/mealie-recipes/mealie/mealie-next/pyproject.toml
    tier: observed
  kind: self-hosted
  name: Mealie
  page: /applications/fitness-nutrition/mealie/
  slug: mealie
  url: https://github.com/mealie-recipes/mealie
- anchor: tandoor-recipes
  counts:
    declared: 0
    observed: 2
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
    layer: common
    name: stripe
    provider: stripe
    says: ships the stripe SDK or integration code
    source: https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
    tier: observed
  kind: self-hosted
  name: Tandoor Recipes
  page: /applications/fitness-nutrition/tandoor-recipes/
  slug: tandoor-recipes
  url: https://github.com/TandoorRecipes/recipes
- anchor: myfitnesspal
  counts:
    declared: 13
    observed: 13
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  - route: integrations page
    url: https://www.myfitnesspal.com/apps
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: amazon
    provider: amazon
    says: ships the amazon SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    name: amplitude
    provider: amplitude
    says: ships the amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.60
      key: advertising-revenue-reporting
      name: Advertising Revenue Reporting
      url: /capabilities/advertising-revenue-reporting/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: appsflyer
    provider: appsflyer
    says: ships the appsflyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: brightcove
    provider: brightcove
    says: ships the brightcove SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    name: facebook
    provider: facebook
    says: ships the facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: facebook
    provider: facebook
    says: ships the facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: fyber
    provider: fyber
    says: ships the fyber SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: google-admob
    provider: google-admob
    says: ships the google-admob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: iab-tech-lab
    provider: iab-tech-lab
    says: ships the iab-tech-lab SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: split
    provider: split
    says: ships the split SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: unity
    provider: unity
    says: ships the unity SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.20
      key: AE-130.10.20
      name: Activity & Step Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: accupedo
    provider: accupedo
    says: lists accupedo as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: fitbit
    provider: fitbit
    says: lists fitbit as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: garmin
    provider: garmin
    says: lists garmin as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.60
      key: AE-130.60
      name: Women's & Reproductive Health
      url: /capabilities/women-s-reproductive-health/
      via_parent: null
    credit: null
    layer: domain
    name: glow-fertility
    provider: glow-fertility
    says: lists glow-fertility as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: google
    provider: google
    says: lists google as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: polar
    provider: polar
    says: lists polar as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.20
      key: AE-130.10.20
      name: Activity & Step Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: renpho
    provider: renpho
    says: lists renpho as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: runkeeper
    provider: runkeeper
    says: lists runkeeper as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: strava
    provider: strava
    says: lists strava as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: trainingpeaks
    provider: trainingpeaks
    says: lists trainingpeaks as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: under-armour
    provider: under-armour
    says: lists under-armour as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.20
      key: AE-130.10.20
      name: Activity & Step Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: vesync
    provider: vesync
    says: lists vesync as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: withings
    provider: withings
    says: lists withings as an integration
    source: https://www.myfitnesspal.com/apps
    tier: declared
  kind: commercial
  name: MyFitnessPal
  page: /applications/fitness-nutrition/myfitnesspal/
  slug: myfitnesspal
  url: https://www.myfitnesspal.com/
- anchor: strava
  counts:
    declared: 12
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
  - route: documentation
    url: https://support.strava.com/hc/en-us/articles/223297187
  - route: integrations page
    url: https://www.strava.com/apps
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3760.60
      key: advertising-revenue-reporting
      name: Advertising Revenue Reporting
      url: /capabilities/advertising-revenue-reporting/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: branch-io
    provider: branch-io
    says: ships the branch-io SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
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
    name: facebook
    provider: facebook
    says: ships the facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: facebook
    provider: facebook
    says: ships the facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
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
    name: sentry-system
    provider: sentry-system
    says: ships the sentry-system SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: coros
    provider: coros
    says: lists coros as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: fitbit
    provider: fitbit
    says: lists fitbit as an integration
    source: https://www.strava.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: garmin
    provider: garmin
    says: lists garmin as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: nike
    provider: nike
    says: lists nike as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: oura-ring
    provider: oura-ring
    says: lists oura-ring as an integration
    source: https://www.strava.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.40
      key: AE-130.10.40
      name: Connected Fitness Equipment
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: peloton
    provider: peloton
    says: lists peloton as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: polar
    provider: polar
    says: lists polar as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: samsung
    provider: samsung
    says: lists samsung as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: suunto
    provider: suunto
    says: lists suunto as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.40
      key: AE-130.10.40
      name: Connected Fitness Equipment
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: wahoo
    provider: wahoo
    says: lists wahoo as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: whoop
    provider: whoop
    says: lists whoop as an integration
    source: https://www.strava.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.40
      key: AE-130.10.40
      name: Connected Fitness Equipment
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: zwift
    provider: zwift
    says: lists zwift as an integration
    source: https://support.strava.com/hc/en-us/articles/223297187
    tier: declared
  kind: commercial
  name: Strava
  page: /applications/fitness-nutrition/strava/
  slug: strava
  url: https://www.strava.com/
- anchor: cronometer
  counts:
    declared: 8
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
  - route: documentation
    url: https://cronometer.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3760.60
      key: advertising-revenue-reporting
      name: Advertising Revenue Reporting
      url: /capabilities/advertising-revenue-reporting/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: adjust
    provider: adjust
    says: ships the adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
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
    name: amplitude
    provider: amplitude
    says: ships the amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: google-admob
    provider: google-admob
    says: ships the google-admob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: apple
    provider: apple
    says: lists apple as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900
      key: health-information-management
      name: Health Information Management
      url: /capabilities/health-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: dexcom
    provider: dexcom
    says: lists dexcom as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: fitbit
    provider: fitbit
    says: lists fitbit as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: garmin
    provider: garmin
    says: lists garmin as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: oura-ring
    provider: oura-ring
    says: lists oura-ring as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: polar
    provider: polar
    says: lists polar as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: whoop
    provider: whoop
    says: lists whoop as an integration
    source: https://cronometer.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: withings
    provider: withings
    says: lists withings as an integration
    source: https://cronometer.com/
    tier: declared
  kind: commercial
  name: Cronometer
  page: /applications/fitness-nutrition/cronometer/
  slug: cronometer
  url: https://cronometer.com/
- anchor: lose-it!
  counts:
    declared: 2
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
  - route: documentation
    url: https://www.loseit.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: amazon
    provider: amazon
    says: ships the amazon SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    name: amplitude
    provider: amplitude
    says: ships the amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: google-admob
    provider: google-admob
    says: ships the google-admob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
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
    name: rollbar
    provider: rollbar
    says: ships the rollbar SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.60
      key: advertising-revenue-reporting
      name: Advertising Revenue Reporting
      url: /capabilities/advertising-revenue-reporting/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: singular
    provider: singular
    says: ships the singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: apple
    provider: apple
    says: lists apple as an integration
    source: https://www.loseit.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: google
    provider: google
    says: lists google as an integration
    source: https://www.loseit.com/
    tier: declared
  kind: commercial
  name: Lose It!
  page: /applications/fitness-nutrition/lose-it/
  slug: lose-it
  url: https://www.loseit.com/
author: API Evangelist
candidates:
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  capability:
    attribution: Turbo EA
    id: BC-5060.40
    key: geospatial-survey-management
    name: Geospatial & Survey Management
    url: /capabilities/geospatial-survey-management/
    via_parent: null
  in_catalog: true
  kin_score: 45.5
  mcp:
    status: none
  name: openstreetmap
  provider: openstreetmap
  slug: openstreetmap
  status: profiled
  tags:
  - Geocoding
  - Geospatial
  - Mapping
  - Open Data
  url: /providers/openstreetmap/
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: fitness-nutrition
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Health & Fitness
  store: apple-app-store
  url: https://apps.apple.com/us/charts/iphone/health-fitness-apps/6013
- category: Health & Fitness
  store: google-play
  url: https://play.google.com/store/apps/category/HEALTH_AND_FITNESS
name: Fitness & Nutrition Tracking
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: wearable / device / health-platform data sync (Fitbit, Garmin, Apple Health, Health Connect...)
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  fit: exact
  layer: domain
  why: food-composition and nutrition databases, exercise libraries -- closest BC fit; the model has no food-database capability
- capability:
    attribution: Turbo EA
    id: BC-4070.10
    key: menu-engineering-recipe-management
    name: Menu Engineering & Recipe Management
    url: /capabilities/menu-engineering-recipe-management/
    via_parent: null
  fit: exact
  layer: domain
  why: recipe sources and meal planning (Mealie, Tandoor, Norish)
- capability:
    attribution: Turbo EA
    id: BC-2900
    key: health-information-management
    name: Health Information Management
    url: /capabilities/health-information-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'health records adjacent data: CGM (Dexcom), clinical-grade measurements'
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: sign-in, social login (Facebook Login), OIDC
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: common
  why: premium subscriptions (Stripe in Tandoor hosted)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics SDKs (Amplitude, Firebase Analytics)
- capability:
    attribution: Turbo EA
    id: BC-3760.60
    key: advertising-revenue-reporting
    name: Advertising Revenue Reporting
    url: /capabilities/advertising-revenue-reporting/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution / deep links (AppsFlyer, Adjust, Singular, Branch)
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app advertising SDKs (AdMob, Amazon, Unity, Fyber)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash/error monitoring (Crashlytics, Sentry, Rollbar)
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature flags / experimentation (Split)
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  fit: exact
  layer: common
  why: maps and route data (OpenStreetMap)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for media/uploads (S3 via boto3)
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: agent
  why: LLM bring-your-own and MCP server
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Cronometer
      - Endurain
      - MyFitnessPal
      - SparkyFitness
      - Strava
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: none
      name: garmin
      slug: garmin
      sources:
      - https://cronometer.com/
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
      - https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
      status: profiled
      tags:
      - Fitness
      - GPS
      - Outdoor
      - Wearables
      tier: observed
      url: /providers/garmin/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Cronometer
      - MyFitnessPal
      - SparkyFitness
      - Strava
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: fitbit
      slug: fitbit
      sources:
      - https://cronometer.com/
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Activity Tracking
      - Fitness
      - Health
      - Wearables
      tier: declared
      url: /providers/fitbit/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Cronometer
      - MyFitnessPal
      - SparkyFitness
      - Strava
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        status: unknown
      name: polar
      slug: polar
      sources:
      - https://cronometer.com/
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Fitness
      - Health
      - Heart Rate
      - Wearables
      tier: declared
      url: /providers/polar/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Lose It!
      - MyFitnessPal
      - SparkyFitness
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp: &id005
        source: https://github.com/google/mcp
        status: verified
      name: google
      slug: google
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://www.loseit.com/
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags: &id006
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Cronometer
      - Lose It!
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: apple
      slug: apple
      sources:
      - https://cronometer.com/
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://www.loseit.com/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - Cronometer
      - SparkyFitness
      - Strava
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        status: none
      name: oura-ring
      slug: oura-ring
      sources:
      - https://cronometer.com/
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://www.strava.com/apps
      status: profiled
      tags:
      - Activity
      - Biometrics
      - Cardiovascular
      - Fitness
      tier: declared
      url: /providers/oura-ring/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Cronometer
      - MyFitnessPal
      - SparkyFitness
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        status: none
      name: withings
      slug: withings
      sources:
      - https://cronometer.com/
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Body Composition
      - Connected Devices
      - Health
      - Wearables
      tier: declared
      url: /providers/withings/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Cronometer
      - Strava
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: whoop
      slug: whoop
      sources:
      - https://cronometer.com/
      - https://www.strava.com/apps
      status: profiled
      tags:
      - Fitness
      - Health
      - Recovery
      - Wearables
      tier: declared
      url: /providers/whoop/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - SparkyFitness
      - Strava
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        source: https://github.com/coroslab/COROS-MCP
        status: verified
      name: coros
      slug: coros
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Company
      - Fitness
      - GPS Watches
      - Wearables
      tier: declared
      url: /providers/coros/
    - agent_band: agent-aware
      agent_readiness: 17.1
      apps:
      - Strava
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: suunto
      slug: suunto
      sources:
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Company
      - Outdoor
      - Sports
      - Wearables
      tier: declared
      url: /providers/suunto/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Strava
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: samsung
      slug: samsung
      sources:
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Consumer Electronics
      - Developer Platform
      - IoT
      - Mobile
      tier: declared
      url: /providers/samsung/
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
      - SparkyFitness
      - wger
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: open-food-facts
      slug: open-food-facts
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
      status: profiled
      tags:
      - Food
      - Nutrition
      - Open Data
      - Product Data
      tier: observed
      url: /providers/open-food-facts/
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: fatsecret
      slug: fatsecret
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Barcode Scanning
      - Calories
      - Diets
      tier: declared
      url: /providers/fatsecret/
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        status: none
      name: swiss-food-composition-database
      slug: swiss-food-composition-database
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Food
      - Health
      - Nutrition
      - food-composition
      tier: declared
      url: /providers/swiss-food-composition-database/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - SparkyFitness
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        status: none
      name: nutritionix
      slug: nutritionix
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Food
      - Health
      - Nutrition
      - Restaurant
      tier: declared
      url: /providers/nutritionix/
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - SparkyFitness
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: usda
      slug: usda
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Agriculture
      - Food Safety
      - Nutrition
      - Statistics
      tier: declared
      url: /providers/usda/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - SparkyFitness
      band: emerging
      in_catalog: true
      kin_score: 14.3
      mcp:
        status: none
      name: yazio
      slug: yazio
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Digital Health
      - Health
      - Nutrition
      tier: declared
      url: /providers/yazio/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SparkyFitness
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: livsmedelsverket
      slug: livsmedelsverket
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Food Safety
      - Government
      - Nutrition
      tier: declared
      url: /providers/livsmedelsverket/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SparkyFitness
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp:
        status: unknown
      name: health-canada
      slug: health-canada
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Government
      - Health
      - Nutrition
      tier: declared
      url: /providers/health-canada/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - Endurain
      - MyFitnessPal
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: strava
      slug: strava
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      - https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Cycling
      - Fitness
      - Fitness Tracking
      - Running
      tier: observed
      url: /providers/strava/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - MyFitnessPal
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        status: none
      name: under-armour
      slug: under-armour
      sources:
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Connected Fitness
      - Fitness
      - Health
      - Wearables
      tier: declared
      url: /providers/under-armour/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - MyFitnessPal
      band: thin
      in_catalog: true
      kin_score: 29.4
      mcp:
        status: none
      name: trainingpeaks
      slug: trainingpeaks
      sources:
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Coaching
      - Endurance Training
      - Fitness
      - Workouts
      tier: declared
      url: /providers/trainingpeaks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MyFitnessPal
      band: emerging
      in_catalog: true
      kin_score: 13.9
      mcp:
        status: none
      name: runkeeper
      slug: runkeeper
      sources:
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Fitness
      - Mobile App
      - Social
      - Tracking
      tier: declared
      url: /providers/runkeeper/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Strava
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: none
      name: nike
      slug: nike
      sources:
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Apparel
      - Fashion
      - Footwear
      - Fortune 500
      tier: declared
      url: /providers/nike/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.20
      key: AE-130.10.20
      name: Activity & Step Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: human-only
      agent_readiness: 4.4
      apps:
      - MyFitnessPal
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: unknown
      name: renpho
      slug: renpho
      sources:
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Company
      - Health Tech
      - IoT
      - Wellness
      tier: declared
      url: /providers/renpho/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MyFitnessPal
      band: minimal
      in_catalog: true
      kin_score: 8.3
      mcp:
        status: unknown
      name: vesync
      slug: vesync
      sources:
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Company
      - Consumer Electronics
      - IoT
      - Smart Home
      tier: declared
      url: /providers/vesync/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MyFitnessPal
      band: minimal
      in_catalog: true
      kin_score: 7.6
      mcp:
        status: unknown
      name: accupedo
      slug: accupedo
      sources:
      - https://www.myfitnesspal.com/apps
      status: profiled
      tags:
      - Company
      - Fitness
      - Health
      - Mobile App
      tier: declared
      url: /providers/accupedo/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.40
      key: AE-130.10.40
      name: Connected Fitness Equipment
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - Strava
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: none
      name: wahoo
      slug: wahoo
      sources:
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Bike Computers
      - Cycling
      - Endurance Training
      - Fitness
      tier: declared
      url: /providers/wahoo/
    - agent_band: agent-aware
      agent_readiness: 12.2
      apps:
      - Strava
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: peloton
      slug: peloton
      sources:
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Connected Fitness
      - Fitness
      - Subscription
      - Wellness
      tier: declared
      url: /providers/peloton/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Strava
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        status: none
      name: zwift
      slug: zwift
      sources:
      - https://support.strava.com/hc/en-us/articles/223297187
      status: profiled
      tags:
      - Cycling
      - Indoor Cycling
      - Running
      - Smart Trainers
      tier: declared
      url: /providers/zwift/
  - capability:
      attribution: Turbo EA
      id: BC-4070.10
      key: menu-engineering-recipe-management
      name: Menu Engineering & Recipe Management
      url: /capabilities/menu-engineering-recipe-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - SparkyFitness
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: tandoor
      slug: tandoor
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Food
      - Meal Planning
      - Nutrition
      - Recipes
      tier: declared
      url: /providers/tandoor/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: none
      name: mealie
      slug: mealie
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Food
      - Meal Planning
      - Recipes
      tier: declared
      url: /providers/mealie/
    - agent_band: agent-aware
      agent_readiness: 9.0
      apps:
      - SparkyFitness
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: norish
      slug: norish
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Groceries
      - Meal Planning
      - Recipes
      tier: declared
      url: /providers/norish/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.10
      key: AE-130.10.10
      name: Workout Logging
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://github.com/wger-project/mcp-server
        status: verified
      name: wger
      slug: wger
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Fitness
      - Health
      - Nutrition
      - Public APIs
      tier: declared
      url: /providers/wger/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - SparkyFitness
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: hevy
      slug: hevy
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Fitness
      - Health
      - Workout Tracking
      tier: declared
      url: /providers/hevy/
    - agent_band: agent-aware
      agent_readiness: 6.2
      apps:
      - SparkyFitness
      band: emerging
      in_catalog: true
      kin_score: 23.6
      mcp:
        status: none
      name: free-exercise-db
      slug: free-exercise-db
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - Exercise
      - Fitness
      - Open Data
      tier: declared
      url: /providers/free-exercise-db/
  - capability:
      attribution: Turbo EA
      id: BC-2900
      key: health-information-management
      name: Health Information Management
      url: /capabilities/health-information-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - Cronometer
      band: thin
      in_catalog: true
      kin_score: 33.5
      mcp:
        status: none
      name: dexcom
      slug: dexcom
      sources:
      - https://cronometer.com/
      status: profiled
      tags:
      - Continuous Glucose Monitoring
      - Diabetes
      - Digital Health
      - Glucose
      tier: declared
      url: /providers/dexcom/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.60
      key: AE-130.60
      name: Women's & Reproductive Health
      url: /capabilities/women-s-reproductive-health/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - MyFitnessPal
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: glow-fertility
      slug: glow-fertility
      sources:
      - https://www.myfitnesspal.com/apps
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Cronometer
      - Lose It!
      - MyFitnessPal
      - Strava
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Cronometer
      - Lose It!
      - MyFitnessPal
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - MyFitnessPal
      - Strava
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Cronometer
      - Lose It!
      - MyFitnessPal
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: google-admob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Lose It!
      - MyFitnessPal
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: amazon
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - MyFitnessPal
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://github.com/Unity-Technologies/industry-ai-workflows
        status: verified
      name: unity
      slug: unity
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - Game Development
      - Game Services
      - Multiplayer
      - Real-Time 3D
      tier: observed
      url: /providers/unity/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - MyFitnessPal
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: iab-tech-lab
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
    - agent_band: null
      agent_readiness: null
      apps:
      - MyFitnessPal
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: fyber
      slug: fyber
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Cronometer
      - Lose It!
      - MyFitnessPal
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Strava
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: sentry-system
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Lose It!
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        source: https://github.com/rollbar/rollbar-mcp-server
        status: verified
      name: rollbar
      slug: rollbar
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      status: profiled
      tags:
      - Debugging
      - DevOps
      - Error Tracking
      - Monitoring
      tier: observed
      url: /providers/rollbar/
  - capability:
      attribution: Turbo EA
      id: BC-3760.60
      key: advertising-revenue-reporting
      name: Advertising Revenue Reporting
      url: /capabilities/advertising-revenue-reporting/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - MyFitnessPal
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: appsflyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Lose It!
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fitnow.loseit/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Strava
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: branch-io
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Cronometer
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cronometer.android.gold/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Endurain
      - Tandoor Recipes
      - wger
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: amazon-web-services
      slug: amazon-web-services
      sources:
      - https://raw.githubusercontent.com/TandoorRecipes/recipes/develop/requirements.txt
      - https://raw.githubusercontent.com/joaovitoriasilva/endurain/master/backend/pyproject.toml
      - https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - MyFitnessPal
      - Strava
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.strava/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - SparkyFitness
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: zenith-hosting
      slug: zenith-hosting
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Cloud
      - Company
      - Hosting
      - Software-as-a-Service
      tier: declared
      url: /providers/zenith-hosting/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - SparkyFitness
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: none
      name: pikapods
      slug: pikapods
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/README.md
      status: profiled
      tags:
      - Company
      - IoT
      - Pet Tech
      - Smart Devices
      tier: declared
      url: /providers/pikapods/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - FitTrackee
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: openstreetmap
      slug: openstreetmap
      sources:
      - https://raw.githubusercontent.com/SamR1/FitTrackee/main/README.md
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: declared
      url: /providers/openstreetmap/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - MyFitnessPal
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: none
      name: split
      slug: split
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
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
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - MyFitnessPal
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: brightcove
      slug: brightcove
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
      status: profiled
      tags:
      - Live Streaming
      - Media
      - Streaming
      - Video
      tier: observed
      url: /providers/brightcove/
  layer: common
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Mealie
      - SparkyFitness
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: openai
      slug: openai
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
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
      agent_readiness: 46.6
      apps:
      - SparkyFitness
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - SparkyFitness
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp: *id005
      name: google
      slug: google
      sources:
      - https://raw.githubusercontent.com/CodeWithCJ/SparkyFitness/main/SparkyFitnessServer/package.json
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google/
  layer: agent
summary:
  coverage_pct: 96.7
  declared_only: 37
  distinct_providers: 61
  in_catalog: 59
  mcp:
    documented: 0
    none: 39
    unchecked: 2
    verified: 15
  mcp_verified: 15
  mean_kin_score: 42.0
  observed: 24
  queued: 2
  reference_apps: 10
title: 'Fitness & Nutrition Tracking: application blueprint'
---
