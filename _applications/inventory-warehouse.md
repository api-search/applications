---
access: understanding
agent_layer: []
apps:
- anchor: inventree
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
  - route: source code
    url: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
  - route: source code
    url: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/InvenTree/plugin/builtin/integration/currency_exchange.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Digi-Key
    provider: digi-key
    says: ships the Digi-Key SDK or integration code
    source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Frankfurter
    provider: frankfurter
    says: ships the Frankfurter SDK or integration code
    source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/InvenTree/plugin/builtin/integration/currency_exchange.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LCSC Electronics
    provider: lcsc
    says: ships the LCSC Electronics SDK or integration code
    source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mouser Electronics
    provider: mouser
    says: ships the Mouser Electronics SDK or integration code
    source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
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
    name: Postal (postalserver.io)
    provider: postal-server
    says: ships the Postal (postalserver.io) SDK or integration code
    source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
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
    source: https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: TME (Transfer Multisort Elektronik)
    provider: tme
    says: ships the TME (Transfer Multisort Elektronik) SDK or integration code
    source: https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
    tier: observed
  kind: self-hosted
  name: InvenTree
  page: /applications/inventory-warehouse/inventree/
  slug: inventree
  url: https://github.com/inventree/InvenTree
- anchor: snipe-it
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Chat
    provider: google-chat
    says: ships the Google Chat SDK or integration code
    source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
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
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
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
    name: Rollbar
    provider: rollbar
    says: ships the Rollbar SDK or integration code
    source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
    tier: observed
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
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
    tier: observed
  kind: self-hosted
  name: Snipe-IT
  page: /applications/inventory-warehouse/snipe-it/
  slug: snipe-it
  url: https://github.com/snipe/snipe-it
- anchor: part-db
  counts:
    declared: 0
    observed: 20
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
  - route: source code
    url: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adafruit
    provider: adafruit
    says: ships the Adafruit SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bambu Lab
    provider: bambu-lab
    says: ships the Bambu Lab SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Buerklin
    provider: buerklin
    says: ships the Buerklin SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Canopy API (canopyapi.co)
    provider: canopy-api
    says: ships the Canopy API (canopyapi.co) SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Conrad Electronic
    provider: conrad
    says: ships the Conrad Electronic SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Digi-Key
    provider: digi-key
    says: ships the Digi-Key SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: element14 / Farnell
    provider: element14
    says: ships the element14 / Farnell SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LCSC Electronics
    provider: lcsc
    says: ships the LCSC Electronics SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: LM Studio
    provider: lm-studio
    says: ships the LM Studio SDK or integration code
    source: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mouser Electronics
    provider: mouser
    says: ships the Mouser Electronics SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Octopart
    provider: octopart
    says: ships the Octopart SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: OEMsecrets
    provider: oemsecrets
    says: ships the OEMsecrets SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pollin Electronic
    provider: pollin
    says: ships the Pollin Electronic SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pololu
    provider: pololu
    says: ships the Pololu SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Reichelt Elektronik
    provider: reichelt
    says: ships the Reichelt Elektronik SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: SparkFun Electronics
    provider: sparkfun
    says: ships the SparkFun Electronics SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: TME (Transfer Multisort Elektronik)
    provider: tme
    says: ships the TME (Transfer Multisort Elektronik) SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: TrustedParts
    provider: trustedparts
    says: ships the TrustedParts SDK or integration code
    source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
    tier: observed
  kind: self-hosted
  name: Part-DB
  page: /applications/inventory-warehouse/part-db/
  slug: part-db
  url: https://github.com/Part-DB/Part-DB-server
- anchor: shelf
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Crisp
    provider: crisp
    says: ships the Crisp SDK or integration code
    source: https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
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
    source: https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
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
    source: https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Supabase
    provider: supabase
    says: ships the Supabase SDK or integration code
    source: https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
    tier: observed
  kind: open-source-saas
  name: Shelf
  page: /applications/inventory-warehouse/shelf/
  slug: shelf
  url: https://github.com/Shelf-nu/shelf.nu
- anchor: cin7
  counts:
    declared: 15
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.cin7.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon
    provider: amazon
    says: lists Amazon as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara
    provider: avalara
    says: lists Avalara as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: BigCommerce
    provider: bigcommerce
    says: lists BigCommerce as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Brightpearl
    provider: brightpearl
    says: lists Brightpearl as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: EasyPost
    provider: easypost
    says: lists EasyPost as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: eBay
    provider: ebay
    says: lists eBay as an integration
    source: https://www.cin7.com/integrations/
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
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle NetSuite
    provider: netsuite
    says: lists Oracle NetSuite as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: ShipStation
    provider: shipstation
    says: lists ShipStation as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: Starshipit
    provider: starshipit
    says: lists Starshipit as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Walmart
    provider: walmart
    says: lists Walmart as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.cin7.com/integrations/
    tier: declared
  kind: commercial
  name: Cin7
  page: /applications/inventory-warehouse/cin7/
  slug: cin7
  url: https://www.cin7.com/
- anchor: inflow-inventory
  counts:
    declared: 24
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.inflowinventory.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon
    provider: amazon
    says: lists Amazon as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: BigCommerce
    provider: bigcommerce
    says: lists BigCommerce as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: DHL
    provider: dhl
    says: lists DHL as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: EasyPost
    provider: easypost
    says: lists EasyPost as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: eBay
    provider: ebay
    says: lists eBay as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Etsy
    provider: etsy
    says: lists Etsy as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Faire
    provider: faire
    says: lists Faire as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: FedEx
    provider: fedex
    says: lists FedEx as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Shopping
    provider: google-shopping
    says: lists Google Shopping as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lightspeed Commerce
    provider: lightspeed
    says: lists Lightspeed Commerce as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Magento
    provider: magento
    says: lists Magento as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://www.inflowinventory.com/integrations
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: UPS
    provider: ups
    says: lists UPS as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: USPS
    provider: usps
    says: lists USPS as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Walmart
    provider: walmart
    says: lists Walmart as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://www.inflowinventory.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.inflowinventory.com/integrations
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
    source: https://www.inflowinventory.com/integrations
    tier: declared
  kind: commercial
  name: inFlow Inventory
  page: /applications/inventory-warehouse/inflow-inventory/
  slug: inflow-inventory
  url: https://www.inflowinventory.com/
- anchor: sortly
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.sortly.com/features/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.sortly.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.sortly.com/features/integrations/
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
    source: https://www.sortly.com/features/integrations/
    tier: declared
  kind: commercial
  name: Sortly
  page: /applications/inventory-warehouse/sortly/
  slug: sortly
  url: https://www.sortly.com/
- anchor: zoho-inventory
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.zoho.inventory/latest/
  integrations: []
  kind: commercial
  name: Zoho Inventory
  page: /applications/inventory-warehouse/zoho-inventory/
  slug: zoho-inventory
  url: https://www.zoho.com/inventory/
author: API Evangelist
candidates: []
credits: []
html: public
id: inventory-warehouse
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Inventory Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#inventory-management
- category: Orders and shipping
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Operations
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Commerce
  store: zapier
  url: https://zapier.com/apps
name: Inventory & Warehouse Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: extension node AE-150.10.10
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: supplier part lookup, pricing and barcode decoding is the defining self-hosted integration
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: extension node AE-230.20.10
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: low-stock and checkout alerts to team chat
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: extension node AE-110.10.40
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: extension node AE-110.10.30
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: app billing and order payments
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: nearest
  layer: common
  why: SSO / hosted auth (nearest)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app support chat
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  fit: exact
  layer: domain
  why: stock levels and orders synced to storefronts and marketplaces
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: inventory valuation and COGS posted to accounting
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  fit: exact
  layer: domain
  why: carrier labels, rates and tracking (nearest; no BC node for label purchase)
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sales tax on orders
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier / Make connectors; no BC or extension node
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: customer records sync
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-1930
      key: electronic-component-sourcing-management
      name: Electronic Component Sourcing Management
      url: /capabilities/electronic-component-sourcing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - InvenTree
      - Part-DB
      band: developing
      in_catalog: true
      kin_score: 47.2
      mcp:
        status: none
      name: Digi-Key
      slug: digi-key
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      - https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
      status: profiled
      tags:
      - Distribution
      - Electronic Components
      - Public APIs
      - Shopping
      tier: observed
      url: /providers/digi-key/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - InvenTree
      - Part-DB
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unknown
      name: TME (Transfer Multisort Elektronik)
      slug: tme
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      - https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/tme/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - InvenTree
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 4.7
      mcp:
        status: unknown
      name: LCSC Electronics
      slug: lcsc
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      - https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
      status: profiled
      tags:
      - Company
      - Components
      - Distributor
      - Electronics
      tier: observed
      url: /providers/lcsc/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - InvenTree
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 2.7
      mcp:
        status: none
      name: Mouser Electronics
      slug: mouser
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      - https://github.com/inventree/InvenTree/tree/master/src/backend/InvenTree/plugin/builtin/suppliers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/mouser/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        status: none
      name: Bambu Lab
      slug: bambu-lab
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - 3D Printing
      - Company
      - Consumer Technology
      - Hardware
      tier: observed
      url: /providers/bambu-lab/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: unknown
      name: Pollin Electronic
      slug: pollin
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Electronics
      - Retail
      tier: observed
      url: /providers/pollin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 8.4
      mcp:
        status: none
      name: SparkFun Electronics
      slug: sparkfun
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Education
      - Electronics
      - Maker
      - Retail
      tier: observed
      url: /providers/sparkfun/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        status: none
      name: Octopart
      slug: octopart
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Public APIs
      - Shopping
      tier: observed
      url: /providers/octopart/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: none
      name: Pololu
      slug: pololu
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Company
      - Electronics
      - Hobbyist
      - Robotics
      tier: observed
      url: /providers/pololu/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: unknown
      name: Conrad Electronic
      slug: conrad
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Electronics
      - Retail
      tier: observed
      url: /providers/conrad/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: none
      name: TrustedParts
      slug: trustedparts
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Automotive
      - B2B
      - E-Commerce
      - Parts
      tier: observed
      url: /providers/trustedparts/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 4.1
      mcp:
        status: none
      name: element14 / Farnell
      slug: element14
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Company
      - Distribution
      - Electronics
      - Engineering
      tier: observed
      url: /providers/element14/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Reichelt Elektronik
      slug: reichelt
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Components
      - Electronics
      - Hobbyist
      - Retail
      tier: observed
      url: /providers/reichelt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: Buerklin
      slug: buerklin
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/buerklin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Part-DB
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: OEMsecrets
      slug: oemsecrets
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/oemsecrets/
    - agent_band: null
      agent_readiness: null
      apps:
      - Part-DB
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Adafruit
      slug: adafruit
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Part-DB
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Canopy API (canopyapi.co)
      slug: canopy-api
      sources:
      - https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-410.60
      key: channel-sales-management
      name: Channel Sales Management
      url: /capabilities/channel-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - Cin7
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - Cin7
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Cin7
      - inFlow Inventory
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Walmart
      slug: walmart
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Commerce
      - Fortune 100
      - Retail
      - Walmart
      tier: declared
      url: /providers/walmart/
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Cin7
      - inFlow Inventory
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://github.com/eBay/npm-public-api-mcp
        status: verified
      name: eBay
      slug: ebay
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Auctions
      - Commerce
      - Marketplace
      - Product
      tier: declared
      url: /providers/ebay/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Cin7
      - inFlow Inventory
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Cin7
      - inFlow Inventory
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: declared
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 86.5
      mcp:
        status: none
      name: Lightspeed Commerce
      slug: lightspeed
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Commerce
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/lightspeed/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-native
      agent_readiness: 49.5
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 69.9
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - inFlow Inventory
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://developers.etsy.com/documentation/mcp_server/devmcpserver
        status: verified
      name: Etsy
      slug: etsy
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Handmade
      - Listings
      - Marketplace
      tier: declared
      url: /providers/etsy/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - inFlow Inventory
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        status: none
      name: Google Shopping
      slug: google-shopping
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Google Shopping
      - Merchant Center
      - Product Listings
      tier: declared
      url: /providers/google-shopping/
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - inFlow Inventory
      band: thin
      in_catalog: true
      kin_score: 30.6
      mcp:
        status: none
      name: Magento
      slug: magento
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Headless Commerce
      - Magento
      tier: declared
      url: /providers/magento/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Cin7
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        status: none
      name: Brightpearl
      slug: brightpearl
      sources:
      - https://www.cin7.com/integrations/
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Retail
      - Software-as-a-Service
      tier: declared
      url: /providers/brightpearl/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - inFlow Inventory
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: none
      name: Faire
      slug: faire
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Marketplace
      - Retail
      - Wholesale
      tier: declared
      url: /providers/faire/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Cin7
      - Sortly
      - inFlow Inventory
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      - https://www.sortly.com/features/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-native
      agent_readiness: 61.3
      apps:
      - Cin7
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Cin7
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: none
      name: Oracle NetSuite
      slug: netsuite
      sources:
      - https://www.cin7.com/integrations/
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Cin7
      - inFlow Inventory
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: EasyPost
      slug: easypost
      sources:
      - https://www.cin7.com/integrations/
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Logistics
      - Multi-Carrier
      - Shipping
      - Tracking
      tier: declared
      url: /providers/easypost/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Cin7
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: none
      name: ShipStation
      slug: shipstation
      sources:
      - https://www.cin7.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Labels
      - Logistics
      - ShipStation
      tier: declared
      url: /providers/shipstation/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Cin7
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        status: unknown
      name: Starshipit
      slug: starshipit
      sources:
      - https://www.cin7.com/integrations/
      status: profiled
      tags:
      - Automation
      - E-Commerce
      - Fulfilment
      - Shipping
      tier: declared
      url: /providers/starshipit/
  - capability:
      attribution: API Evangelist extension
      id: AE-928
      key: AE-928
      name: Parcel Rating & Label Purchase
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        status: none
      name: FedEx
      slug: fedex
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Address Validation
      - Freight
      - Logistics
      - Pickup
      tier: declared
      url: /providers/fedex/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - inFlow Inventory
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: USPS
      slug: usps
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Government
      - Logistics
      - Postal Service
      - Shipping
      tier: declared
      url: /providers/usps/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - inFlow Inventory
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        source: https://github.com/UPS-API/ups-mcp
        status: verified
      name: UPS
      slug: ups
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Fortune 500
      - Logistics
      - Shipping
      - Supply Chain
      tier: declared
      url: /providers/ups/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - inFlow Inventory
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: DHL
      slug: dhl
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Freight
      - Logistics
      - Shipping
      tier: declared
      url: /providers/dhl/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - InvenTree
      band: thin
      in_catalog: true
      kin_score: 33.5
      mcp:
        source: https://github.com/lineofflight/frankfurter-mcp
        status: verified
      name: Frankfurter
      slug: frankfurter
      sources:
      - https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/InvenTree/plugin/builtin/integration/currency_exchange.py
      status: profiled
      tags:
      - Foreign Exchange
      - MIT
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/frankfurter/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Cin7
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/avadev/mcp
        status: verified
      name: Avalara
      slug: avalara
      sources:
      - https://www.cin7.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Avalara
      - Tax
      tier: declared
      url: /providers/avalara/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Snipe-IT
      - Sortly
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
      - https://www.sortly.com/features/integrations/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Snipe-IT
      - Sortly
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
      - https://www.sortly.com/features/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Snipe-IT
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Chat
      slug: google-chat
      sources:
      - https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Google
      - Google Workspace
      tier: observed
      url: /providers/google-chat/
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
      - InvenTree
      - Shelf
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
      - https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Snipe-IT
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/rollbar/rollbar-mcp-server
        status: verified
      name: Rollbar
      slug: rollbar
      sources:
      - https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
      status: profiled
      tags:
      - Debugging
      - DevOps
      - Error Tracking
      - Monitoring
      tier: observed
      url: /providers/rollbar/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - InvenTree
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Snipe-IT
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/snipe/snipe-it/master/composer.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - InvenTree
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Postal (postalserver.io)
      slug: postal-server
      sources:
      - https://raw.githubusercontent.com/inventree/InvenTree/master/src/backend/requirements.txt
      status: profiled
      tags:
      - DevOps
      - Docker
      - Installations
      - Open Source
      tier: observed
      url: /providers/postal-server/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - Shelf
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase
      slug: supabase
      sources:
      - https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: observed
      url: /providers/supabase/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 78.0
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Shelf
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - inFlow Inventory
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - Cin7
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.cin7.com/integrations/
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - inFlow Inventory
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.inflowinventory.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Shelf
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: none
      name: Crisp
      slug: crisp
      sources:
      - https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Live Chat
      - Messaging
      tier: observed
      url: /providers/crisp/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Shelf
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/Shelf-nu/shelf.nu/main/apps/webapp/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Part-DB
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-aware
      agent_readiness: 18.2
      apps:
      - Part-DB
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: none
      name: LM Studio
      slug: lm-studio
      sources:
      - https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Local LLM
      - Machine Learning
      tier: observed
      url: /providers/lm-studio/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Part-DB
      band: strong
      in_catalog: true
      kin_score: 55.4
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  layer: agent
summary:
  coverage_pct: 96.8
  declared_only: 30
  distinct_providers: 63
  in_catalog: 61
  mcp:
    documented: 0
    none: 27
    unchecked: 2
    verified: 26
  mcp_verified: 26
  mean_kin_score: 42.3
  observed: 33
  queued: 2
  reference_apps: 8
title: 'Inventory & Warehouse Management: application blueprint'
---
