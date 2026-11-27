---
app: Square Point of Sale
app_slug: square-point-of-sale
app_url: https://squareup.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - Bushfire
  - SimpleTix
  - TicketSocket
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Ecwid
  - GoDaddy
  - Magento
  - Wix
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-530
  key: inventory-management
  layer: domain
  name: Inventory Management
  providers:
  - BevSpot
  - MarketMan
  - Shopventory
  - SKU IQ
  url: /capabilities/inventory-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4070.30
  key: kitchen-production-operations
  layer: domain
  name: Kitchen Production Operations
  providers:
  - Fresh KDS
  url: /capabilities/kitchen-production-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - Easyship
  - ShipBob
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.60
  key: AE-210.60
  layer: domain
  name: Restaurant Reservations
  providers:
  - TablesReady
  url: /capabilities/restaurant-reservations/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Domo
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Poptin
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Airtax
  - Intuit QuickBooks
  - MYOB
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: common
  name: Link Shortening & Link-in-Bio
  providers:
  - Linktree
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: point-of-sale
  name: Point of Sale & In-Person Payments
  url: /applications/point-of-sale/
counts:
  declared: 25
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
- route: integrations page
  url: https://squareup.com/au/townsquare/business-apps-integrate-square
- route: integrations page
  url: https://squareup.com/us/en/app-marketplace
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id003
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id004
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
  tier: observed
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id009
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id010
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id037
      status: none
    slug: pusher
    status: profiled
    tags: &id038
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: airtax
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: common
  name: Airtax
  provider: airtax
  says: lists Airtax as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.6
    mcp: &id005
      status: none
    slug: bevspot
    status: profiled
    tags: &id006
    - Ai Apps
    - Company
    - Hospitality
    - Restaurant
    url: /providers/bevspot/
  layer: domain
  name: BevSpot
  provider: bevspot
  says: lists BevSpot as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id007
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id008
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.9
    mcp: &id011
      status: unknown
    slug: bushfire
    status: profiled
    tags: &id012
    - Australia
    - Company
    - Fire Protection
    - Sprinkler Systems
    url: /providers/bushfire/
  layer: domain
  name: Bushfire
  provider: bushfire
  says: lists Bushfire as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id013
      status: none
    slug: domo
    status: profiled
    tags: &id014
    - Analysis
    - Business Intelligence
    - Data
    - Pipelines
    url: /providers/domo/
  layer: common
  name: Domo
  provider: domo
  says: lists Domo as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.1
    band: developing
    in_catalog: true
    kin_score: 44.2
    mcp: &id015
      source: https://github.com/easyship/easyship-mcp-plugin
      status: verified
    slug: easyship
    status: profiled
    tags: &id016
    - E-Commerce
    - Fulfillment
    - Logistics
    - Shipping
    url: /providers/easyship/
  layer: domain
  name: Easyship
  provider: easyship
  says: lists Easyship as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id017
      status: none
    slug: ecwid
    status: profiled
    tags: &id018
    - E-Commerce
    - Online Store
    - Retail
    - Storefront
    url: /providers/ecwid/
  layer: domain
  name: Ecwid
  provider: ecwid
  says: lists Ecwid as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4070.30
    key: kitchen-production-operations
    name: Kitchen Production Operations
    url: /capabilities/kitchen-production-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id019
      status: unknown
    slug: fresh-kds
    status: profiled
    tags: &id020
    - Enterprise
    - Kitchen Display System
    - POS Integration
    - Restaurant
    url: /providers/fresh-kds/
  layer: domain
  name: Fresh KDS
  provider: fresh-kds
  says: lists Fresh KDS as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.4
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id021
      source: https://developer.godaddy.com/mcp
      status: verified
    slug: godaddy
    status: profiled
    tags: &id022
    - Aftermarket
    - Certificates
    - DNS
    - Domains
    url: /providers/godaddy/
  layer: domain
  name: GoDaddy
  provider: godaddy
  says: lists GoDaddy as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.4
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id023
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id024
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: lists IFTTT as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id025
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id026
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: Intuit QuickBooks
  provider: quickbooks
  says: lists Intuit QuickBooks as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.8
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id027
      status: none
    slug: linktree
    status: profiled
    tags: &id028
    - Company
    - Creator Economy
    - Link-in-bio
    - Media
    url: /providers/linktree/
  layer: common
  name: Linktree
  provider: linktree
  says: lists Linktree as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id029
      status: none
    slug: magento
    status: profiled
    tags: &id030
    - Catalog
    - E-Commerce
    - Headless Commerce
    - Magento
    url: /providers/magento/
  layer: domain
  name: Magento
  provider: magento
  says: lists Magento as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id031
      status: none
    slug: marketman
    status: profiled
    tags: &id032
    - Inventory
    - Purchasing
    - Restaurant
    - Supply Chain
    url: /providers/marketman/
  layer: domain
  name: MarketMan
  provider: marketman
  says: lists MarketMan as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id033
      status: none
    slug: myob
    status: profiled
    tags: &id034
    - Accounting
    - Bills
    - Business Management
    - Invoices
    url: /providers/myob/
  layer: common
  name: MYOB
  provider: myob
  says: lists MYOB as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id035
      status: none
    slug: poptin
    status: profiled
    tags: &id036
    - Company
    - Email Marketing
    - Marketing
    - Marketing Automation
    url: /providers/poptin/
  layer: common
  name: Poptin
  provider: poptin
  says: lists Poptin as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.0
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id039
      source: https://developer.shipbob.com/mcp-server/overview
      status: verified
    slug: shipbob
    status: profiled
    tags: &id040
    - 3PL
    - E-Commerce
    - Fulfillment
    - Logistics
    url: /providers/shipbob/
  layer: domain
  name: ShipBob
  provider: shipbob
  says: lists ShipBob as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.2
    mcp: &id041
      status: none
    slug: shopventory
    status: profiled
    tags: &id042
    - Company
    - Inventory
    - Point-of-Sale
    - Retail
    url: /providers/shopventory/
  layer: domain
  name: Shopventory
  provider: shopventory
  says: lists Shopventory as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id043
      status: unknown
    slug: simpletix
    status: profiled
    tags: &id044
    - Company
    - Event
    - Software-as-a-Service
    - Ticketing
    url: /providers/simpletix/
  layer: domain
  name: SimpleTix
  provider: simpletix
  says: lists SimpleTix as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id045
      status: none
    slug: sku-iq
    status: profiled
    tags: &id046
    - E-Commerce
    - Inventory
    - Point-of-Sale
    - Sync
    url: /providers/sku-iq/
  layer: domain
  name: SKU IQ
  provider: sku-iq
  says: lists SKU IQ as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.60
    key: AE-210.60
    name: Restaurant Reservations
    url: /capabilities/restaurant-reservations/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id047
      status: none
    slug: tablesready
    status: profiled
    tags: &id048
    - Company
    - Restaurant
    - Scheduling
    - Waitlist
    url: /providers/tablesready/
  layer: domain
  name: TablesReady
  provider: tablesready
  says: lists TablesReady as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.3
    mcp: &id049
      status: unknown
    slug: ticketsocket
    status: profiled
    tags: &id050
    - Company
    - Event
    - Marketing
    - Ticketing
    url: /providers/ticketsocket/
  layer: domain
  name: TicketSocket
  provider: ticketsocket
  says: lists TicketSocket as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id051
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id052
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id053
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id054
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id055
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id056
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://squareup.com/au/townsquare/business-apps-integrate-square
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/point-of-sale/square-point-of-sale/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Airtax
  slug: airtax
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id003
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id004
  url: /providers/appsflyer/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id005
  name: BevSpot
  slug: bevspot
  status: profiled
  tags: *id006
  url: /providers/bevspot/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id007
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id008
  url: /providers/bigcommerce/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id009
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id010
  url: /providers/bugsnag/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id011
  name: Bushfire
  slug: bushfire
  status: profiled
  tags: *id012
  url: /providers/bushfire/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id013
  name: Domo
  slug: domo
  status: profiled
  tags: *id014
  url: /providers/domo/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: developing
  in_catalog: true
  kin_score: 44.2
  mcp: *id015
  name: Easyship
  slug: easyship
  status: profiled
  tags: *id016
  url: /providers/easyship/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id017
  name: Ecwid
  slug: ecwid
  status: profiled
  tags: *id018
  url: /providers/ecwid/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id019
  name: Fresh KDS
  slug: fresh-kds
  status: profiled
  tags: *id020
  url: /providers/fresh-kds/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id021
  name: GoDaddy
  slug: godaddy
  status: profiled
  tags: *id022
  url: /providers/godaddy/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id023
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id024
  url: /providers/ifttt/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id025
  name: Intuit QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id026
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 43.8
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id027
  name: Linktree
  slug: linktree
  status: profiled
  tags: *id028
  url: /providers/linktree/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id029
  name: Magento
  slug: magento
  status: profiled
  tags: *id030
  url: /providers/magento/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id031
  name: MarketMan
  slug: marketman
  status: profiled
  tags: *id032
  url: /providers/marketman/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id033
  name: MYOB
  slug: myob
  status: profiled
  tags: *id034
  url: /providers/myob/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id035
  name: Poptin
  slug: poptin
  status: profiled
  tags: *id036
  url: /providers/poptin/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id037
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id038
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id039
  name: ShipBob
  slug: shipbob
  status: profiled
  tags: *id040
  url: /providers/shipbob/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id041
  name: Shopventory
  slug: shopventory
  status: profiled
  tags: *id042
  url: /providers/shopventory/
- agent_band: human-only
  agent_readiness: 0.7
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id043
  name: SimpleTix
  slug: simpletix
  status: profiled
  tags: *id044
  url: /providers/simpletix/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id045
  name: SKU IQ
  slug: sku-iq
  status: profiled
  tags: *id046
  url: /providers/sku-iq/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id047
  name: TablesReady
  slug: tablesready
  status: profiled
  tags: *id048
  url: /providers/tablesready/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.3
  mcp: *id049
  name: TicketSocket
  slug: ticketsocket
  status: profiled
  tags: *id050
  url: /providers/ticketsocket/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id051
  name: Wix
  slug: wix
  status: profiled
  tags: *id052
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id053
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id054
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id055
  name: Xero
  slug: xero
  status: profiled
  tags: *id056
  url: /providers/xero/
siblings:
- name: Lightspeed Restaurant
  rows: 16
  url: /applications/point-of-sale/lightspeed-restaurant/
- name: Loyverse POS
  rows: 33
  url: /applications/point-of-sale/loyverse-pos/
- name: NexoPOS
  rows: 2
  url: /applications/point-of-sale/nexopos/
- name: Odoo Point of Sale
  rows: 16
  url: /applications/point-of-sale/odoo-point-of-sale/
- name: Open Source Point of Sale
  rows: 3
  url: /applications/point-of-sale/open-source-point-of-sale/
sitemap: true
title: 'Square Point of Sale: Point of Sale & In-Person Payments reference app'
---
