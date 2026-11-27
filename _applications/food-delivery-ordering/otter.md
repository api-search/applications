---
app: Otter
app_slug: otter
app_url: https://www.tryotter.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.100.20
  key: AE-140.100.20
  layer: domain
  name: Food Delivery
  providers:
  - Caviar
  - ClassPass
  - DoorDash
  - ezCater
  - Fantuan
  - Grubhub
  - HungryPanda
  - Postmates
  - Skip the Dishes
  - Uber Eats
  url: /capabilities/quick-local-commerce/
  via_parent: Quick & Local Commerce
- attribution: Turbo EA
  id: BC-530
  key: inventory-management
  layer: domain
  name: Inventory Management
  providers:
  - MarketMan
  - Restaurant365
  url: /capabilities/inventory-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2420.40
  key: last-mile-delivery-operations-management
  layer: domain
  name: Last-Mile Delivery Operations Management
  providers:
  - DoorDash Drive
  - Nash
  - Shipday
  url: /capabilities/last-mile-delivery-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.20.20
  key: AE-140.20.20
  layer: domain
  name: Online Ordering
  providers:
  - BentoBox
  - ChowNow
  - Flipdish
  - Incentivio
  - Lunchbox
  - Ritual
  - Slice
  url: /capabilities/cart-checkout/
  via_parent: Cart & Checkout
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Clover
  - Epos Now
  - Lavu
  - Lightspeed
  - Loyverse
  - Oracle Micros
  - Revel
  - Shift4
  - Square
  - Toast
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2440.20
  key: rostering-and-scheduling-management
  layer: common
  name: Rostering and Scheduling Management
  providers:
  - 7shifts
  - Deputy
  - Homebase
  - When I Work
  url: /capabilities/rostering-and-scheduling-management/
  via_parent: null
category:
  id: food-delivery-ordering
  name: Food Delivery & Restaurant Ordering
  url: /applications/food-delivery-ordering/
counts:
  declared: 37
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.tryotter.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.6
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id001
      status: none
    slug: 7shifts
    status: profiled
    tags: &id002
    - Employee Scheduling
    - Restaurant
    - Scheduling
    - Workforce Management
    url: /providers/7shifts/
  layer: common
  name: 7shifts
  provider: 7shifts
  says: lists 7shifts as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.4
    mcp: &id003
      status: none
    slug: bentobox
    status: profiled
    tags: &id004
    - Commerce
    - Online Ordering
    - Restaurant
    - Websites
    url: /providers/bentobox/
  layer: domain
  name: BentoBox
  provider: bentobox
  says: lists BentoBox as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id005
      status: none
    slug: caviar
    status: profiled
    tags: &id006
    - Company
    - Food Delivery
    - Marketplace
    - Restaurant
    url: /providers/caviar/
  layer: domain
  name: Caviar
  provider: caviar
  says: lists Caviar as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id007
      status: none
    slug: chownow
    status: profiled
    tags: &id008
    - Food and Beverage
    - Online Ordering
    - Restaurant
    - Restaurant Technology
    url: /providers/chownow/
  layer: domain
  name: ChowNow
  provider: chownow
  says: lists ChowNow as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id009
      status: none
    slug: classpass
    status: profiled
    tags: &id010
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 41.3
    mcp: &id011
      status: none
    slug: clover
    status: profiled
    tags: &id012
    - Payments
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/clover/
  layer: domain
  name: Clover
  provider: clover
  says: lists Clover as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id013
      status: none
    slug: deputy
    status: profiled
    tags: &id014
    - Employee Scheduling
    - Time and Attendance
    - Timesheets
    - Workforce Management
    url: /providers/deputy/
  layer: common
  name: Deputy
  provider: deputy
  says: lists Deputy as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id015
      status: none
    slug: doordash
    status: profiled
    tags: &id016
    - Delivery
    - Last Mile Delivery
    - Logistics
    - On-Demand
    url: /providers/doordash/
  layer: domain
  name: DoorDash
  provider: doordash
  says: lists DoorDash as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id017
      status: unchecked
    slug: doordash-drive
    status: queued for profiling
    tags: &id018 []
    url: null
  layer: domain
  name: DoorDash Drive
  provider: doordash-drive
  says: lists DoorDash Drive as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id019
      status: none
    slug: epos-now
    status: profiled
    tags: &id020
    - Hospitality
    - Payments
    - Point-of-Sale
    - Retail
    url: /providers/epos-now/
  layer: domain
  name: Epos Now
  provider: epos-now
  says: lists Epos Now as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id021
      status: none
    slug: ezcater
    status: profiled
    tags: &id022
    - Catering
    - Company
    - Food
    - Marketplace
    url: /providers/ezcater/
  layer: domain
  name: ezCater
  provider: ezcater
  says: lists ezCater as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id023
      status: unknown
    slug: fantuan
    status: profiled
    tags: &id024
    - Food Delivery
    - Mobile App
    - Restaurant Partnerships
    - Takeout
    url: /providers/fantuan/
  layer: domain
  name: Fantuan
  provider: fantuan
  says: lists Fantuan as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.2
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id025
      status: none
    slug: flipdish
    status: profiled
    tags: &id026
    - Mobile App
    - Online Ordering
    - Point-of-Sale
    - Restaurant
    url: /providers/flipdish/
  layer: domain
  name: Flipdish
  provider: flipdish
  says: lists Flipdish as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: strong
    in_catalog: true
    kin_score: 61.3
    mcp: &id027
      status: none
    slug: grubhub
    status: profiled
    tags: &id028
    - Food Delivery
    - Marketplace
    - Online Ordering
    - Restaurant
    url: /providers/grubhub/
  layer: domain
  name: Grubhub
  provider: grubhub
  says: lists Grubhub as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id029
      status: none
    slug: homebase
    status: profiled
    tags: &id030
    - Human Resources
    - Payroll
    - Scheduling
    - Time Tracking
    url: /providers/homebase/
  layer: common
  name: Homebase
  provider: homebase
  says: lists Homebase as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.7
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id031
      status: none
    slug: hungrypanda
    status: profiled
    tags: &id032
    - Company
    - Delivery
    - Food Delivery
    - Marketplace
    url: /providers/hungrypanda/
  layer: domain
  name: HungryPanda
  provider: hungrypanda
  says: lists HungryPanda as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: developing
    in_catalog: true
    kin_score: 44.5
    mcp: &id033
      status: none
    slug: incentivio
    status: profiled
    tags: &id034
    - Guest Engagement
    - Loyalty
    - Online Ordering
    - Restaurant
    url: /providers/incentivio/
  layer: domain
  name: Incentivio
  provider: incentivio
  says: lists Incentivio as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: emerging
    in_catalog: true
    kin_score: 18.2
    mcp: &id035
      status: none
    slug: lavu
    status: profiled
    tags: &id036
    - Inventory
    - Payments
    - Point-of-Sale
    - Restaurant
    url: /providers/lavu/
  layer: domain
  name: Lavu
  provider: lavu
  says: lists Lavu as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id037
      status: none
    slug: lightspeed
    status: profiled
    tags: &id038
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id039
      status: none
    slug: loyverse
    status: profiled
    tags: &id040
    - Cafe and Restaurant
    - Inventory
    - Point-of-Sale
    - Retail
    url: /providers/loyverse/
  layer: domain
  name: Loyverse
  provider: loyverse
  says: lists Loyverse as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.9
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id041
      status: none
    slug: lunchbox
    status: profiled
    tags: &id042
    - Catering
    - Guest Engagement
    - Online Ordering
    - Restaurant
    url: /providers/lunchbox/
  layer: domain
  name: Lunchbox
  provider: lunchbox
  says: lists Lunchbox as an integration
  source: https://www.tryotter.com/integrations
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
    mcp: &id043
      status: none
    slug: marketman
    status: profiled
    tags: &id044
    - Inventory
    - Purchasing
    - Restaurant
    - Supply Chain
    url: /providers/marketman/
  layer: domain
  name: MarketMan
  provider: marketman
  says: lists MarketMan as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 62.9
    mcp: &id045
      status: none
    slug: nash
    status: profiled
    tags: &id046
    - Company
    - Delivery
    - Last Mile Delivery
    - Logistics
    url: /providers/nash/
  layer: domain
  name: Nash
  provider: nash
  says: lists Nash as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id047
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id048
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Micros
  provider: oracle
  says: lists Oracle Micros as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.2
    mcp: &id049
      status: none
    slug: postmates
    status: profiled
    tags: &id050
    - Acquired
    - Couriers
    - Delivery
    - Food Delivery
    url: /providers/postmates/
  layer: domain
  name: Postmates
  provider: postmates
  says: lists Postmates as an integration
  source: https://www.tryotter.com/integrations
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
    agent_readiness: 20.4
    band: thin
    in_catalog: true
    kin_score: 36.7
    mcp: &id051
      status: none
    slug: restaurant365
    status: profiled
    tags: &id052
    - Accounting
    - Inventory
    - Invoices
    - Restaurant
    url: /providers/restaurant365/
  layer: domain
  name: Restaurant365
  provider: restaurant365
  says: lists Restaurant365 as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id053
      status: none
    slug: revel-systems
    status: profiled
    tags: &id054
    - Point-of-Sale
    - Restaurant
    - Retail
    - iPad
    url: /providers/revel-systems/
  layer: domain
  name: Revel
  provider: revel-systems
  says: lists Revel as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id055
      status: unchecked
    slug: ritual-co
    status: queued for profiling
    tags: &id056 []
    url: null
  layer: domain
  name: Ritual
  provider: ritual-co
  says: lists Ritual as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.1
    band: developing
    in_catalog: true
    kin_score: 50.8
    mcp: &id057
      status: none
    slug: shift4
    status: profiled
    tags: &id058
    - Payment Gateway
    - Payment Processing
    - Payments
    - United States
    url: /providers/shift4/
  layer: domain
  name: Shift4
  provider: shift4
  says: lists Shift4 as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id059
      source: https://registry.modelcontextprotocol.io/v0/servers?search=com.shipday&limit=3
      status: verified
    slug: shipday
    status: profiled
    tags: &id060
    - Delivery
    - Last Mile Delivery
    - Local Delivery
    - Logistics
    url: /providers/shipday/
  layer: domain
  name: Shipday
  provider: shipday
  says: lists Shipday as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id061
      status: none
    slug: skipthedishes
    status: profiled
    tags: &id062
    - Company
    - Couriers
    - Food Delivery
    - Restaurant
    url: /providers/skipthedishes/
  layer: domain
  name: Skip the Dishes
  provider: skipthedishes
  says: lists Skip the Dishes as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id063
      status: none
    slug: slice
    status: profiled
    tags: &id064
    - Local Commerce
    - Online Ordering
    - Pizza
    - Restaurant
    url: /providers/slice/
  layer: domain
  name: Slice
  provider: slice
  says: lists Slice as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id065
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id066
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
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
    mcp: &id067
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id068
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id069
      status: none
    slug: toast
    status: profiled
    tags: &id070
    - Food Service
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/toast/
  layer: domain
  name: Toast
  provider: toast
  says: lists Toast as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id071
      status: none
    slug: uber-eats
    status: profiled
    tags: &id072
    - Food Delivery
    - Last Mile Delivery
    - Uber Direct
    - Uber Eats
    url: /providers/uber-eats/
  layer: domain
  name: Uber Eats
  provider: uber-eats
  says: lists Uber Eats as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.5
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id073
      status: none
    slug: when-i-work
    status: profiled
    tags: &id074
    - Employee Scheduling
    - Time Clock
    - Time Tracking
    - Workforce Management
    url: /providers/when-i-work/
  layer: common
  name: When I Work
  provider: when-i-work
  says: lists When I Work as an integration
  source: https://www.tryotter.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/food-delivery-ordering/otter/
providers:
- agent_band: agent-aware
  agent_readiness: 27.6
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id001
  name: 7shifts
  slug: 7shifts
  status: profiled
  tags: *id002
  url: /providers/7shifts/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.4
  mcp: *id003
  name: BentoBox
  slug: bentobox
  status: profiled
  tags: *id004
  url: /providers/bentobox/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id005
  name: Caviar
  slug: caviar
  status: profiled
  tags: *id006
  url: /providers/caviar/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id007
  name: ChowNow
  slug: chownow
  status: profiled
  tags: *id008
  url: /providers/chownow/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id009
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id010
  url: /providers/classpass/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 41.3
  mcp: *id011
  name: Clover
  slug: clover
  status: profiled
  tags: *id012
  url: /providers/clover/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id013
  name: Deputy
  slug: deputy
  status: profiled
  tags: *id014
  url: /providers/deputy/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id015
  name: DoorDash
  slug: doordash
  status: profiled
  tags: *id016
  url: /providers/doordash/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id017
  name: DoorDash Drive
  slug: doordash-drive
  status: queued for profiling
  tags: *id018
  url: null
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id019
  name: Epos Now
  slug: epos-now
  status: profiled
  tags: *id020
  url: /providers/epos-now/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id021
  name: ezCater
  slug: ezcater
  status: profiled
  tags: *id022
  url: /providers/ezcater/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id023
  name: Fantuan
  slug: fantuan
  status: profiled
  tags: *id024
  url: /providers/fantuan/
- agent_band: agent-ready
  agent_readiness: 40.2
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id025
  name: Flipdish
  slug: flipdish
  status: profiled
  tags: *id026
  url: /providers/flipdish/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: strong
  in_catalog: true
  kin_score: 61.3
  mcp: *id027
  name: Grubhub
  slug: grubhub
  status: profiled
  tags: *id028
  url: /providers/grubhub/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id029
  name: Homebase
  slug: homebase
  status: profiled
  tags: *id030
  url: /providers/homebase/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id031
  name: HungryPanda
  slug: hungrypanda
  status: profiled
  tags: *id032
  url: /providers/hungrypanda/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: developing
  in_catalog: true
  kin_score: 44.5
  mcp: *id033
  name: Incentivio
  slug: incentivio
  status: profiled
  tags: *id034
  url: /providers/incentivio/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id035
  name: Lavu
  slug: lavu
  status: profiled
  tags: *id036
  url: /providers/lavu/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id037
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id038
  url: /providers/lightspeed/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id039
  name: Loyverse
  slug: loyverse
  status: profiled
  tags: *id040
  url: /providers/loyverse/
- agent_band: agent-aware
  agent_readiness: 27.9
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id041
  name: Lunchbox
  slug: lunchbox
  status: profiled
  tags: *id042
  url: /providers/lunchbox/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id043
  name: MarketMan
  slug: marketman
  status: profiled
  tags: *id044
  url: /providers/marketman/
- agent_band: agent-native
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 62.9
  mcp: *id045
  name: Nash
  slug: nash
  status: profiled
  tags: *id046
  url: /providers/nash/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id047
  name: Oracle Micros
  slug: oracle
  status: profiled
  tags: *id048
  url: /providers/oracle/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id049
  name: Postmates
  slug: postmates
  status: profiled
  tags: *id050
  url: /providers/postmates/
- agent_band: agent-aware
  agent_readiness: 20.4
  band: thin
  in_catalog: true
  kin_score: 36.7
  mcp: *id051
  name: Restaurant365
  slug: restaurant365
  status: profiled
  tags: *id052
  url: /providers/restaurant365/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id053
  name: Revel
  slug: revel-systems
  status: profiled
  tags: *id054
  url: /providers/revel-systems/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id055
  name: Ritual
  slug: ritual-co
  status: queued for profiling
  tags: *id056
  url: null
- agent_band: agent-native
  agent_readiness: 54.1
  band: developing
  in_catalog: true
  kin_score: 50.8
  mcp: *id057
  name: Shift4
  slug: shift4
  status: profiled
  tags: *id058
  url: /providers/shift4/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id059
  name: Shipday
  slug: shipday
  status: profiled
  tags: *id060
  url: /providers/shipday/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id061
  name: Skip the Dishes
  slug: skipthedishes
  status: profiled
  tags: *id062
  url: /providers/skipthedishes/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id063
  name: Slice
  slug: slice
  status: profiled
  tags: *id064
  url: /providers/slice/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id065
  name: Square
  slug: square
  status: profiled
  tags: *id066
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id067
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id068
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id069
  name: Toast
  slug: toast
  status: profiled
  tags: *id070
  url: /providers/toast/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id071
  name: Uber Eats
  slug: uber-eats
  status: profiled
  tags: *id072
  url: /providers/uber-eats/
- agent_band: agent-ready
  agent_readiness: 29.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id073
  name: When I Work
  slug: when-i-work
  status: profiled
  tags: *id074
  url: /providers/when-i-work/
siblings:
- name: ChowNow
  rows: 12
  url: /applications/food-delivery-ordering/chownow/
- name: Enatega Multivendor
  rows: 11
  url: /applications/food-delivery-ordering/enatega-multivendor/
- name: Shipday
  rows: 23
  url: /applications/food-delivery-ordering/shipday/
- name: TastyIgniter
  rows: 13
  url: /applications/food-delivery-ordering/tastyigniter/
- name: UpMenu
  rows: 32
  url: /applications/food-delivery-ordering/upmenu/
sitemap: true
title: 'Otter: Food Delivery & Restaurant Ordering reference app'
---
