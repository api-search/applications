---
access: understanding
agent_layer:
- app: Farmbrite
  finding: Farmbrite exposes a REST API and webhooks for custom integrations and connects most apps through Zapier; no MCP server named
  source: https://www.farmbrite.com/integrations
  tier: declared
- app: farmOS
  finding: farmOS core ships a JSON:API (drupal/jsonapi_extras, jsonapi_schema) with OAuth (simple_oauth); no MCP server in the module tree
  source: https://raw.githubusercontent.com/farmOS/farmOS/3.x/composer.json
  tier: observed
apps:
- anchor: farmos
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/farmOS/farmOS/3.x/composer.json
  - route: source code
    url: https://github.com/farmOS/farmOS/tree/3.x/modules
  - route: source code
    url: https://raw.githubusercontent.com/farmOS/farmOS/3.x/modules/core/map/modules/mapbox/farm_map_mapbox.info.yml
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
    name: Mapbox
    provider: mapbox
    says: ships the Mapbox SDK or integration code
    source: https://raw.githubusercontent.com/farmOS/farmOS/3.x/modules/core/map/modules/mapbox/farm_map_mapbox.info.yml
    tier: observed
  kind: self-hosted
  name: farmOS
  page: /applications/farm-agriculture/farmos/
  slug: farmos
  url: https://github.com/farmOS/farmOS
- anchor: litefarm
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/webapp/package.json
  - route: source code
    url: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: DigitalOcean Spaces
    provider: digital-ocean
    says: ships the DigitalOcean Spaces SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3500.60
      key: irrigation-operations
      name: Irrigation Operations
      url: /capabilities/irrigation-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Ensemble Scientific (ESCI)
    provider: ensemble-scientific
    says: ships the Ensemble Scientific (ESCI) SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Gmail API
    provider: google-gmail
    says: ships the Gmail API SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
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
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/webapp/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: OpenWeather
    provider: openweathermap
    says: ships the OpenWeather SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: SurveyStack
    provider: surveystack
    says: ships the SurveyStack SDK or integration code
    source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
    tier: observed
  kind: open-source-saas
  name: LiteFarm
  page: /applications/farm-agriculture/litefarm/
  slug: litefarm
  url: https://github.com/LiteFarmOrg/LiteFarm
- anchor: open-food-network
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
  - route: source code
    url: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/.env
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
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
    name: GNU Taler
    provider: gnu-taler
    says: ships the GNU Taler SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/.env
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
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
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
    tier: observed
  kind: self-hosted
  name: Open Food Network
  page: /applications/farm-agriculture/open-food-network/
  slug: open-food-network
  url: https://github.com/openfoodfoundation/openfoodnetwork
- anchor: agriwebb
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.agriwebb.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-934
      key: AE-934
      name: Farm Water & Tank Monitoring
      url: /capabilities/farm-water-tank-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Agbot
    provider: agbot
    says: lists Agbot as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3590.60.10
      key: BC-3590.60.10
      name: Animal Identification Tagging
      url: /capabilities/livestock-identification-and-movement-compliance/
      via_parent: Livestock Identification and Movement Compliance
    credit: null
    layer: domain
    name: Allflex (MSD Animal Health)
    provider: allflex
    says: lists Allflex (MSD Animal Health) as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Cibo Labs
    provider: cibo-labs
    says: lists Cibo Labs as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-934
      key: AE-934
      name: Farm Water & Tank Monitoring
      url: /capabilities/farm-water-tank-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Farmbot Monitoring Solutions
    provider: farmbot-monitoring
    says: lists Farmbot Monitoring Solutions as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-934
      key: AE-934
      name: Farm Water & Tank Monitoring
      url: /capabilities/farm-water-tank-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Farmo
    provider: farmo
    says: lists Farmo as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Figured
    provider: figured
    says: lists Figured as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3510.70.10
      key: BC-3510.70.10
      name: Weight Gain Recording
      url: /capabilities/growth-and-performance-recording/
      via_parent: Growth and Performance Recording
    credit: null
    layer: domain
    name: Gallagher
    provider: gallagher-animal-management
    says: lists Gallagher as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3530
      key: agronomy-farm-advisory-management
      name: Agronomy & Farm Advisory Management
      url: /capabilities/agronomy-farm-advisory-management/
      via_parent: null
    credit: null
    layer: domain
    name: RCS (Resource Consulting Services)
    provider: rcs
    says: lists RCS (Resource Consulting Services) as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3590.60.10
      key: BC-3590.60.10
      name: Animal Identification Tagging
      url: /capabilities/livestock-identification-and-movement-compliance/
      via_parent: Livestock Identification and Movement Compliance
    credit: null
    layer: domain
    name: Shearwell Data
    provider: shearwell
    says: lists Shearwell Data as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3510.70.10
      key: BC-3510.70.10
      name: Weight Gain Recording
      url: /capabilities/growth-and-performance-recording/
      via_parent: Growth and Performance Recording
    credit: null
    layer: domain
    name: Te Pari
    provider: te-pari
    says: lists Te Pari as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3510.70.10
      key: BC-3510.70.10
      name: Weight Gain Recording
      url: /capabilities/growth-and-performance-recording/
      via_parent: Growth and Performance Recording
    credit: null
    layer: domain
    name: Tru-Test (Datamars)
    provider: tru-test
    says: lists Tru-Test (Datamars) as an integration
    source: https://www.agriwebb.com/integrations/
    tier: declared
  kind: commercial
  name: AgriWebb
  page: /applications/farm-agriculture/agriwebb/
  slug: agriwebb
  url: https://www.agriwebb.com/
- anchor: farmbrite
  counts:
    declared: 13
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.farmbrite.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Local Line
    provider: local-line
    says: lists Local Line as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft Excel
    provider: microsoft-excel
    says: lists Microsoft Excel as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.farmbrite.com/integrations
    tier: declared
  kind: commercial
  name: Farmbrite
  page: /applications/farm-agriculture/farmbrite/
  slug: farmbrite
  url: https://www.farmbrite.com/
- anchor: agworld
  counts:
    declared: 17
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.agworld.com/us/integrations/agronomy/
  - route: integrations page
    url: https://www.agworld.com/us/integrations/growers/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: Agvance (SSI)
    provider: agvance
    says: lists Agvance (SSI) as an integration
    source: https://www.agworld.com/us/integrations/agronomy/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: AgVantage
    provider: agvantage
    says: lists AgVantage as an integration
    source: https://www.agworld.com/us/integrations/agronomy/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: AgVend
    provider: agvend
    says: lists AgVend as an integration
    source: https://www.agworld.com/us/integrations/agronomy/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3240
      key: permits-licences-authorisations-management
      name: Permits, Licences & Authorisations Management
      url: /capabilities/permits-licences-authorisations-management/
      via_parent: null
    credit: null
    layer: domain
    name: CalAg
    provider: calag
    says: lists CalAg as an integration
    source: https://www.agworld.com/us/integrations/agronomy/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    credit: null
    layer: domain
    name: CNH FieldOps
    provider: cnh
    says: lists CNH FieldOps as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Davis Instruments
    provider: davis-instruments
    says: lists Davis Instruments as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: FarmReady (Bolt, Cart, Shed)
    provider: farmready
    says: lists FarmReady (Bolt, Cart, Shed) as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Figured
    provider: figured
    says: lists Figured as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    credit: null
    layer: domain
    name: John Deere Operations Center
    provider: john-deere
    says: lists John Deere Operations Center as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3530.20
      key: nutrient-management-planning
      name: Nutrient Management Planning
      url: /capabilities/nutrient-management-planning/
      via_parent: null
    credit: null
    layer: domain
    name: Kingman Ag
    provider: kingman-ag
    says: lists Kingman Ag as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Mapbox
    provider: mapbox
    says: lists Mapbox as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Power BI
    provider: power-bi
    says: lists Microsoft Power BI as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: OpenStreetMap
    provider: openstreetmap
    says: lists OpenStreetMap as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Pinion
    provider: pinion
    says: lists Pinion as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Raven Slingshot
    provider: raven-slingshot
    says: lists Raven Slingshot as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Satamap
    provider: satamap
    says: lists Satamap as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3500.70
      key: crop-monitoring-and-scouting
      name: Crop Monitoring and Scouting
      url: /capabilities/crop-monitoring-and-scouting/
      via_parent: null
    credit: null
    layer: domain
    name: Semios
    provider: semios
    says: lists Semios as an integration
    source: https://www.agworld.com/us/integrations/growers/
    tier: declared
  kind: commercial
  name: Agworld
  page: /applications/farm-agriculture/agworld/
  slug: agworld
  url: https://www.agworld.com/
- anchor: climate-fieldview
  counts:
    declared: 20
    observed: 0
  evidence:
  - route: integrations page
    url: https://climate.com/en-us/partners.html
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ag Leader AgFiniti / SMS
    provider: ag-leader
    says: lists Ag Leader AgFiniti / SMS as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: Agvance (SSI)
    provider: agvance
    says: lists Agvance (SSI) as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3600
      key: agri-environmental-stewardship-management
      name: Agri-Environmental Stewardship Management
      url: /capabilities/agri-environmental-stewardship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Arva Intelligence
    provider: arva-intelligence
    says: lists Arva Intelligence as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3500
      key: crop-production-management
      name: Crop Production Management
      url: /capabilities/crop-production-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bushel Farm
    provider: bushel
    says: lists Bushel Farm as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    credit: null
    layer: domain
    name: CLAAS
    provider: claas
    says: lists CLAAS as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3570
      key: commodity-origination-merchandising-management
      name: Commodity Origination & Merchandising Management
      url: /capabilities/commodity-origination-merchandising-management/
      via_parent: null
    credit: null
    layer: domain
    name: Combyne
    provider: combyne
    says: lists Combyne as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3500.70
      key: crop-monitoring-and-scouting
      name: Crop Monitoring and Scouting
      url: /capabilities/crop-monitoring-and-scouting/
      via_parent: null
    credit: null
    layer: domain
    name: DroneDeploy
    provider: dronedeploy
    says: lists DroneDeploy as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-120.50
      key: BC-120.50
      name: Corporate Insurance Management
      url: /capabilities/corporate-insurance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Farmers Mutual Hail
    provider: farmers-mutual-hail
    says: lists Farmers Mutual Hail as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-120.50
      key: BC-120.50
      name: Corporate Insurance Management
      url: /capabilities/corporate-insurance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Great American Insurance Group
    provider: great-american-insurance-group
    says: lists Great American Insurance Group as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3500.70
      key: crop-monitoring-and-scouting
      name: Crop Monitoring and Scouting
      url: /capabilities/crop-monitoring-and-scouting/
      via_parent: null
    credit: null
    layer: domain
    name: Intelinair
    provider: intelinair
    says: lists Intelinair as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    credit: null
    layer: domain
    name: John Deere Operations Center
    provider: john-deere
    says: lists John Deere Operations Center as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-120.50
      key: BC-120.50
      name: Corporate Insurance Management
      url: /capabilities/corporate-insurance-management/
      via_parent: null
    credit: null
    layer: domain
    name: MyAgData
    provider: myagdata
    says: lists MyAgData as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3530.20
      key: nutrient-management-planning
      name: Nutrient Management Planning
      url: /capabilities/nutrient-management-planning/
      via_parent: null
    credit: null
    layer: domain
    name: Pattern Ag
    provider: pattern-ag
    says: lists Pattern Ag as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pivot Bio
    provider: pivot-bio
    says: lists Pivot Bio as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3600
      key: agri-environmental-stewardship-management
      name: Agri-Environmental Stewardship Management
      url: /capabilities/agri-environmental-stewardship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Regrow
    provider: regrow
    says: lists Regrow as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3500.70
      key: crop-monitoring-and-scouting
      name: Crop Monitoring and Scouting
      url: /capabilities/crop-monitoring-and-scouting/
      via_parent: null
    credit: null
    layer: domain
    name: Sentera
    provider: sentera
    says: lists Sentera as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3530.20
      key: nutrient-management-planning
      name: Nutrient Management Planning
      url: /capabilities/nutrient-management-planning/
      via_parent: null
    credit: null
    layer: domain
    name: SoilOptix
    provider: soiloptix
    says: lists SoilOptix as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3530
      key: agronomy-farm-advisory-management
      name: Agronomy & Farm Advisory Management
      url: /capabilities/agronomy-farm-advisory-management/
      via_parent: null
    credit: null
    layer: domain
    name: TELUS Agriculture
    provider: telus
    says: lists TELUS Agriculture as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Traction Ag
    provider: traction-ag
    says: lists Traction Ag as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    credit: null
    layer: domain
    name: WinField United Data Silo
    provider: winfield-united
    says: lists WinField United Data Silo as an integration
    source: https://climate.com/en-us/partners.html
    tier: declared
  kind: commercial
  name: Climate FieldView
  page: /applications/farm-agriculture/climate-fieldview/
  slug: climate-fieldview
  url: https://climate.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: farm-agriculture
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Community-Supported Agriculture (CSA)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#community-supported-agriculture-csa
name: Farm & Agriculture Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: named by Agworld, LiteFarm, Open Food Network, farmOS
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by AgriWebb, Agworld, Climate FieldView, Farmbrite
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.20
    key: AE-120.20.20
    name: Satellite & Aerial Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: named by AgriWebb, Agworld
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Agworld, LiteFarm
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: named by LiteFarm, Open Food Network
- capability:
    attribution: Turbo EA
    id: BC-3550
    key: agricultural-inputs-management
    name: Agricultural Inputs Management
    url: /capabilities/agricultural-inputs-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Agworld, Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-3530
    key: agronomy-farm-advisory-management
    name: Agronomy & Farm Advisory Management
    url: /capabilities/agronomy-farm-advisory-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by AgriWebb, Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-3500.70
    key: crop-monitoring-and-scouting
    name: Crop Monitoring and Scouting
    url: /capabilities/crop-monitoring-and-scouting/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Agworld, Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-3540.30
    key: farm-equipment-management
    name: Farm Equipment Management
    url: /capabilities/farm-equipment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Agworld, Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-3500.60
    key: irrigation-operations
    name: Irrigation Operations
    url: /capabilities/irrigation-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: named by AgriWebb, LiteFarm
- capability:
    attribution: Turbo EA
    id: BC-3530.20
    key: nutrient-management-planning
    name: Nutrient Management Planning
    url: /capabilities/nutrient-management-planning/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Agworld, Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by LiteFarm, Open Food Network
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Farmbrite, Open Food Network
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: common
  why: named by Farmbrite
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by LiteFarm
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by Farmbrite
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: named by Farmbrite
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: named by LiteFarm
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: named by Farmbrite
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: named by LiteFarm
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: named by Farmbrite
- capability:
    attribution: Turbo EA
    id: BC-3600
    key: agri-environmental-stewardship-management
    name: Agri-Environmental Stewardship Management
    url: /capabilities/agri-environmental-stewardship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Agworld
- capability:
    attribution: Turbo EA
    id: BC-3570
    key: commodity-origination-merchandising-management
    name: Commodity Origination & Merchandising Management
    url: /capabilities/commodity-origination-merchandising-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-3500
    key: crop-production-management
    name: Crop Production Management
    url: /capabilities/crop-production-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-3540
    key: farm-land-asset-management
    name: Farm Land & Asset Management
    url: /capabilities/farm-land-asset-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-120.50
    key: BC-120.50
    name: Corporate Insurance Management
    url: /capabilities/corporate-insurance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Climate FieldView
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Farmbrite
- capability:
    attribution: Turbo EA
    id: BC-3510
    key: livestock-production-management
    name: Livestock Production Management
    url: /capabilities/livestock-production-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by AgriWebb
- capability:
    attribution: Turbo EA
    id: BC-3240
    key: permits-licences-authorisations-management
    name: Permits, Licences & Authorisations Management
    url: /capabilities/permits-licences-authorisations-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Agworld
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Farmbrite
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-3550
      key: agricultural-inputs-management
      name: Agricultural Inputs Management
      url: /capabilities/agricultural-inputs-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Agworld
      - Climate FieldView
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: unknown
      name: Agvance (SSI)
      slug: agvance
      sources:
      - https://climate.com/en-us/partners.html
      - https://www.agworld.com/us/integrations/agronomy/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/agvance/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - Agworld
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: FarmReady (Bolt, Cart, Shed)
      slug: farmready
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Agriculture
      - Company
      - Farm Management
      - Inventory
      tier: declared
      url: /providers/farmready/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Agworld
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: unknown
      name: AgVend
      slug: agvend
      sources:
      - https://www.agworld.com/us/integrations/agronomy/
      status: profiled
      tags:
      - AgTech
      - Agriculture
      - Company
      - Digital Commerce
      tier: declared
      url: /providers/agvend/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Agworld
      band: minimal
      in_catalog: true
      kin_score: 6.1
      mcp:
        status: none
      name: AgVantage
      slug: agvantage
      sources:
      - https://www.agworld.com/us/integrations/agronomy/
      status: profiled
      tags:
      - Agriculture
      - Company
      - Software
      - Software-as-a-Service
      tier: declared
      url: /providers/agvantage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Climate FieldView
      band: minimal
      in_catalog: true
      kin_score: 5.8
      mcp:
        status: unknown
      name: Pivot Bio
      slug: pivot-bio
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - AgTech
      - Agriculture
      - Biotechnology
      - Synthetic Biology
      tier: declared
      url: /providers/pivot-bio/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Climate FieldView
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: WinField United Data Silo
      slug: winfield-united
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - AgTech
      - Agriculture
      - Data
      - Farming
      tier: declared
      url: /providers/winfield-united/
  - capability:
      attribution: Turbo EA
      id: BC-3540.30
      key: farm-equipment-management
      name: Farm Equipment Management
      url: /capabilities/farm-equipment-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Agworld
      - Climate FieldView
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: John Deere Operations Center
      slug: john-deere
      sources:
      - https://climate.com/en-us/partners.html
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Agriculture
      - Combines
      - Construction
      - Excavators
      tier: declared
      url: /providers/john-deere/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Agworld
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp:
        status: unknown
      name: CNH FieldOps
      slug: cnh
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Agriculture
      - Construction
      - Equipment
      - Telematics
      tier: declared
      url: /providers/cnh/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Climate FieldView
      band: emerging
      in_catalog: true
      kin_score: 23.6
      mcp:
        status: unknown
      name: Ag Leader AgFiniti / SMS
      slug: ag-leader
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - Company
      - Farm Data
      - Precision Agriculture
      tier: declared
      url: /providers/ag-leader/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Climate FieldView
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        status: unknown
      name: CLAAS
      slug: claas
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - Germany
      - Machinery
      - Manufacturing
      tier: declared
      url: /providers/claas/
    - agent_band: null
      agent_readiness: null
      apps:
      - Agworld
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Raven Slingshot
      slug: raven-slingshot
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-3500.70
      key: crop-monitoring-and-scouting
      name: Crop Monitoring and Scouting
      url: /capabilities/crop-monitoring-and-scouting/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Climate FieldView
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: unknown
      name: DroneDeploy
      slug: dronedeploy
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Aerial Analytics
      - Drone Mapping
      - Geospatial
      - Reality Capture
      tier: declared
      url: /providers/dronedeploy/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Climate FieldView
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: unknown
      name: Sentera
      slug: sentera
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Aerial Imagery
      - Drones
      - Precision Agriculture
      - Sensors
      tier: declared
      url: /providers/sentera/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Agworld
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        status: unknown
      name: Semios
      slug: semios
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - AgTech
      - Agriculture
      - Crop-Management
      - Precision Agriculture
      tier: declared
      url: /providers/semios/
    - agent_band: null
      agent_readiness: null
      apps:
      - Climate FieldView
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Intelinair
      slug: intelinair
      sources:
      - https://climate.com/en-us/partners.html
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-120.50
      key: BC-120.50
      name: Corporate Insurance Management
      url: /capabilities/corporate-insurance-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Climate FieldView
      band: emerging
      in_catalog: true
      kin_score: 21.7
      mcp:
        status: unknown
      name: Great American Insurance Group
      slug: great-american-insurance-group
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Casualty
      - Insurance
      - Property
      - Specialty
      tier: declared
      url: /providers/great-american-insurance-group/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Climate FieldView
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: unknown
      name: MyAgData
      slug: myagdata
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - Company
      - Reporting
      - USDA
      tier: declared
      url: /providers/myagdata/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Climate FieldView
      band: emerging
      in_catalog: true
      kin_score: 13.0
      mcp:
        status: unknown
      name: Farmers Mutual Hail
      slug: farmers-mutual-hail
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - Company
      - Hail
      - Insurance
      tier: declared
      url: /providers/farmers-mutual-hail/
  - capability:
      attribution: API Evangelist extension
      id: AE-934
      key: AE-934
      name: Farm Water & Tank Monitoring
      url: /capabilities/farm-water-tank-monitoring/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 6.9
      apps:
      - AgriWebb
      band: emerging
      in_catalog: true
      kin_score: 20.7
      mcp:
        status: unknown
      name: Farmo
      slug: farmo
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Agriculture
      - Industrial
      - Remote Monitoring
      - Smart City
      tier: declared
      url: /providers/farmo/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - AgriWebb
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: unknown
      name: Farmbot Monitoring Solutions
      slug: farmbot-monitoring
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - AgTech
      - Australia
      - Sensors
      - Water Monitoring
      tier: declared
      url: /providers/farmbot-monitoring/
    - agent_band: null
      agent_readiness: null
      apps:
      - AgriWebb
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Agbot
      slug: agbot
      sources:
      - https://www.agriwebb.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-3530.20
      key: nutrient-management-planning
      name: Nutrient Management Planning
      url: /capabilities/nutrient-management-planning/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - Climate FieldView
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: SoilOptix
      slug: soiloptix
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - Mapping
      - Precision Agriculture
      - Soil-Analysis
      tier: declared
      url: /providers/soiloptix/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Agworld
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: unknown
      name: Kingman Ag
      slug: kingman-ag
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Agriculture
      - Autonomous Vehicles
      - Precision Agriculture
      - Tractor Retrofit
      tier: declared
      url: /providers/kingman-ag/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Climate FieldView
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unknown
      name: Pattern Ag
      slug: pattern-ag
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - AgTech
      - Agriculture
      - Company
      - Soil
      tier: declared
      url: /providers/pattern-ag/
  - capability:
      attribution: Turbo EA
      id: BC-3510.70.10
      key: BC-3510.70.10
      name: Weight Gain Recording
      url: /capabilities/growth-and-performance-recording/
      via_parent: Growth and Performance Recording
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - AgriWebb
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        status: unknown
      name: Gallagher
      slug: gallagher-animal-management
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Animal Management
      - Electric Fencing
      - Weighing
      - eID
      tier: declared
      url: /providers/gallagher-animal-management/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - AgriWebb
      band: emerging
      in_catalog: true
      kin_score: 19.5
      mcp:
        status: unknown
      name: Te Pari
      slug: te-pari
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Company
      - Equipment
      - Livestock
      - New Zealand
      tier: declared
      url: /providers/te-pari/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - AgriWebb
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: Tru-Test (Datamars)
      slug: tru-test
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Agriculture
      - Company
      - Data
      - Livestock
      tier: declared
      url: /providers/tru-test/
  - capability:
      attribution: Turbo EA
      id: BC-3600
      key: agri-environmental-stewardship-management
      name: Agri-Environmental Stewardship Management
      url: /capabilities/agri-environmental-stewardship-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Climate FieldView
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Arva Intelligence
      slug: arva-intelligence
      sources:
      - https://climate.com/en-us/partners.html
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Climate FieldView
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Regrow
      slug: regrow
      sources:
      - https://climate.com/en-us/partners.html
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-3530
      key: agronomy-farm-advisory-management
      name: Agronomy & Farm Advisory Management
      url: /capabilities/agronomy-farm-advisory-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Climate FieldView
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: none
      name: TELUS Agriculture
      slug: telus
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Broadband
      - Canada
      - Mobile Network Operator
      - Telecommunications
      tier: declared
      url: /providers/telus/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - AgriWebb
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: unknown
      name: RCS (Resource Consulting Services)
      slug: rcs
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Agriculture
      - Consulting
      - Professional Development
      - Training
      tier: declared
      url: /providers/rcs/
  - capability:
      attribution: Turbo EA
      id: BC-3590.60.10
      key: BC-3590.60.10
      name: Animal Identification Tagging
      url: /capabilities/livestock-identification-and-movement-compliance/
      via_parent: Livestock Identification and Movement Compliance
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - AgriWebb
      band: emerging
      in_catalog: true
      kin_score: 13.9
      mcp:
        status: unknown
      name: Shearwell Data
      slug: shearwell
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Animal Identification
      - Farm Management
      - Livestock
      - RFID
      tier: declared
      url: /providers/shearwell/
    - agent_band: null
      agent_readiness: null
      apps:
      - AgriWebb
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Allflex (MSD Animal Health)
      slug: allflex
      sources:
      - https://www.agriwebb.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - AgriWebb
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        status: none
      name: Cibo Labs
      slug: cibo-labs
      sources:
      - https://www.agriwebb.com/integrations/
      status: profiled
      tags:
      - Agriculture
      - Data Analytics
      - Geospatial
      - Satellite Imagery
      tier: declared
      url: /providers/cibo-labs/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Agworld
      band: emerging
      in_catalog: true
      kin_score: 19.2
      mcp:
        status: unknown
      name: Satamap
      slug: satamap
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Agriculture
      - Imagery
      - Remote Sensing
      - Satellite
      tier: declared
      url: /providers/satamap/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - LiteFarm
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeather
      slug: openweathermap
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/openweathermap/
    - agent_band: agent-aware
      agent_readiness: 7.8
      apps:
      - Agworld
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unknown
      name: Davis Instruments
      slug: davis-instruments
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Company
      - Instruments
      - Sensors
      - Weather
      tier: declared
      url: /providers/davis-instruments/
  - capability:
      attribution: Turbo EA
      id: BC-3570
      key: commodity-origination-merchandising-management
      name: Commodity Origination & Merchandising Management
      url: /capabilities/commodity-origination-merchandising-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Climate FieldView
      band: emerging
      in_catalog: true
      kin_score: 15.9
      mcp:
        status: unknown
      name: Combyne
      slug: combyne
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - Farming
      - Grain
      - Software-as-a-Service
      tier: declared
      url: /providers/combyne/
  - capability:
      attribution: Turbo EA
      id: BC-3500
      key: crop-production-management
      name: Crop Production Management
      url: /capabilities/crop-production-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Climate FieldView
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: unknown
      name: Bushel Farm
      slug: bushel
      sources:
      - https://climate.com/en-us/partners.html
      status: profiled
      tags:
      - Agriculture
      - CRM
      - Farm Management
      - Software-as-a-Service
      tier: declared
      url: /providers/bushel/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Farmbrite
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: none
      name: Local Line
      slug: local-line
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Agriculture
      - E-Commerce
      - Food Tech
      - Supply Chain
      tier: declared
      url: /providers/local-line/
  - capability:
      attribution: Turbo EA
      id: BC-3500.60
      key: irrigation-operations
      name: Irrigation Operations
      url: /capabilities/irrigation-operations/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - LiteFarm
      band: emerging
      in_catalog: true
      kin_score: 14.9
      mcp:
        status: none
      name: Ensemble Scientific (ESCI)
      slug: ensemble-scientific
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
      status: profiled
      tags:
      - Agriculture
      - IoT
      - Irrigation
      - Smart Agriculture
      tier: observed
      url: /providers/ensemble-scientific/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - LiteFarm
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unknown
      name: SurveyStack
      slug: surveystack
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
      status: profiled
      tags:
      - Analytics
      - Community
      - Data Collection
      - SurveyStack
      tier: observed
      url: /providers/surveystack/
  - capability:
      attribution: Turbo EA
      id: BC-3240
      key: permits-licences-authorisations-management
      name: Permits, Licences & Authorisations Management
      url: /capabilities/permits-licences-authorisations-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Agworld
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: CalAg
      slug: calag
      sources:
      - https://www.agworld.com/us/integrations/agronomy/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - AgriWebb
      - Agworld
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        status: unknown
      name: Figured
      slug: figured
      sources:
      - https://www.agriwebb.com/integrations/
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Agriculture
      - Farm Management
      - Finance
      - Software-as-a-Service
      tier: declared
      url: /providers/figured/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Farmbrite
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Agworld
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: unknown
      name: Pinion
      slug: pinion
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Advisory
      - Agriculture
      - Consulting
      - Food
      tier: declared
      url: /providers/pinion/
    - agent_band: null
      agent_readiness: null
      apps:
      - Climate FieldView
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Traction Ag
      slug: traction-ag
      sources:
      - https://climate.com/en-us/partners.html
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - LiteFarm
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/.env
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-ready
      agent_readiness: 45.2
      apps:
      - Agworld
      - farmOS
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://github.com/mapbox/mcp-server
        status: verified
      name: Mapbox
      slug: mapbox
      sources:
      - https://raw.githubusercontent.com/farmOS/farmOS/3.x/modules/core/map/modules/mapbox/farm_map_mapbox.info.yml
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Geospatial
      - Location
      - Mapping
      - Maps
      tier: observed
      url: /providers/mapbox/
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Agworld
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://www.agworld.com/us/integrations/growers/
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
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Open Food Network
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Open Food Network
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: unknown
      name: GNU Taler
      slug: gnu-taler
      sources:
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
      status: profiled
      tags:
      - Ecash
      - Finance
      - Open Source
      - Payments
      tier: observed
      url: /providers/gnu-taler/
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
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
      - LiteFarm
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Farmbrite
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Farmbrite
      band: strong
      in_catalog: true
      kin_score: 55.8
      mcp:
        status: none
      name: Microsoft Excel
      slug: microsoft-excel
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Automation
      - Data Analysis
      - Microsoft
      - Microsoft 365
      tier: declared
      url: /providers/microsoft-excel/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/openfoodfoundation/openfoodnetwork/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - LiteFarm
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean Spaces
      slug: digital-ocean
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Agworld
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/powerbi-modeling-mcp
        status: verified
      name: Microsoft Power BI
      slug: power-bi
      sources:
      - https://www.agworld.com/us/integrations/growers/
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Analysis
      tier: declared
      url: /providers/power-bi/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Farmbrite
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
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
      - LiteFarm
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/webapp/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - LiteFarm
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail API
      slug: google-gmail
      sources:
      - https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Farmbrite
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.farmbrite.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
summary:
  coverage_pct: 88.9
  declared_only: 57
  distinct_providers: 72
  in_catalog: 64
  mcp:
    documented: 0
    none: 14
    unchecked: 8
    verified: 21
  mcp_verified: 21
  mean_kin_score: 39.1
  observed: 15
  queued: 8
  reference_apps: 7
title: 'Farm & Agriculture Management: application blueprint'
---
