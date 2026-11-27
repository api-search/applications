---
access: understanding
agent_layer:
- app: Expensify
  finding: integrations page has an "AI & MCP" category listing Claude, ChatGPT, Cursor and Grok
  source: https://use.expensify.com/integrations
  tier: declared
- app: Ramp
  finding: site footer links "Ramp for Agents" and API documentation
  source: https://ramp.com/integrations
  tier: declared
- app: Brex
  finding: ChatGPT and Claude listed as integrations
  source: https://www.brex.com/product/integrations
  tier: declared
- app: Spliit
  finding: OpenAI (or any OpenAI-compatible endpoint via OPENAI_BASE_URL) extracts receipts and suggests categories
  source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
  tier: observed
apps:
- anchor: expensify
  counts:
    declared: 77
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
  - route: integrations page
    url: https://use.expensify.com/integrations
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
    name: FullStory
    provider: fullstory
    says: ships the FullStory SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Urbanairship
    provider: airship
    says: ships the Urbanairship SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: 9Spokes
    provider: 9spokes
    says: lists 9Spokes as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP
    provider: adp
    says: lists ADP as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: AirPlus International
    provider: airplus
    says: lists AirPlus International as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: American Airlines
    provider: american-airlines
    says: lists American Airlines as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: American Express
    provider: american-express
    says: lists American Express as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: ANZ
    provider: anz
    says: lists ANZ as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: BambooHR
    provider: bamboohr
    says: lists BambooHR as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bank of America
    provider: bank-of-america
    says: lists Bank of America as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Bolt
    provider: bolt-eu
    says: lists Bolt as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Breathe
    provider: breathe-hr
    says: lists Breathe as an integration
    source: https://use.expensify.com/integrations
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
    name: Campfire AI
    provider: campfire
    says: lists Campfire AI as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Capital One
    provider: capital-one
    says: lists Capital One as an integration
    source: https://use.expensify.com/integrations
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
    name: Certinia
    provider: certinia
    says: lists Certinia as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chase
    provider: chase
    says: lists Chase as an integration
    source: https://use.expensify.com/integrations
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
    name: ChatGPT
    provider: openai
    says: lists ChatGPT as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Citi
    provider: citi
    says: lists Citi as an integration
    source: https://use.expensify.com/integrations
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
    name: Claude
    provider: anthropic
    says: lists Claude as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4040
      key: guest-traveller-management
      name: Guest & Traveller Management
      url: /capabilities/guest-traveller-management/
      via_parent: null
    credit: null
    layer: domain
    name: Corporate Traveler
    provider: flight-centre
    says: lists Corporate Traveler as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4040
      key: guest-traveller-management
      name: Guest & Traveller Management
      url: /capabilities/guest-traveller-management/
      via_parent: null
    credit: null
    layer: domain
    name: CTM
    provider: corporate-travel-management
    says: lists CTM as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.10
      key: AE-100.70.10
      name: Coding Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Cursor
    provider: cursor
    says: lists Cursor as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dayforce
    provider: dayforce
    says: lists Dayforce as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Deel
    provider: deel-com
    says: lists Deel as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Delta
    provider: delta-airlines
    says: lists Delta as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: DoorDash
    provider: doordash
    says: lists DoorDash as an integration
    source: https://use.expensify.com/integrations
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
    name: DualEntry
    provider: dualentry
    says: lists DualEntry as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Egencia
    provider: egencia
    says: lists Egencia as an integration
    source: https://use.expensify.com/integrations
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
    name: Fintua
    provider: fintua
    says: lists Fintua as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshteam
    provider: freshteam
    says: lists Freshteam as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Grab
    provider: grab
    says: lists Grab as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenhouse
    provider: greenhouse
    says: lists Greenhouse as an integration
    source: https://use.expensify.com/integrations
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
    name: Grok
    provider: xai
    says: lists Grok as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: lists HiBob as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.20.10
      key: AE-210.20.10
      name: Hotel Booking
      url: /capabilities/lodging-stays/
      via_parent: Lodging & Stays
    credit: null
    layer: domain
    name: Hotel Engine
    provider: hotel-engine
    says: lists Hotel Engine as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HR Cloud
    provider: hr-cloud
    says: lists HR Cloud as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Humaans
    provider: humaans-io
    says: lists Humaans as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Insperity
    provider: insperity
    says: lists Insperity as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: inteliHR
    provider: intelihr
    says: lists inteliHR as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: IRIS Practice Engine
    provider: iris-software
    says: lists IRIS Practice Engine as an integration
    source: https://use.expensify.com/integrations
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
    name: JumpCloud
    provider: jumpcloud
    says: lists JumpCloud as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Justworks
    provider: justworks
    says: lists Justworks as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kallidus
    provider: kallidus
    says: lists Kallidus as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: KAYAK for Business
    provider: kayak
    says: lists KAYAK for Business as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Keka
    provider: keka
    says: lists Keka as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kiwibank
    provider: kiwibank
    says: lists Kiwibank as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Locomote
    provider: locomote
    says: lists Locomote as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lucca
    provider: lucca
    says: lists Lucca as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft
    provider: lyft
    says: lists Lyft as an integration
    source: https://use.expensify.com/integrations
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
    name: Microsoft Dynamics
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Namely
    provider: namely
    says: lists Namely as an integration
    source: https://use.expensify.com/integrations
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
    name: NetSuite
    provider: netsuite
    says: lists NetSuite as an integration
    source: https://use.expensify.com/integrations
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
    name: Oracle
    provider: oracle
    says: lists Oracle as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.30
      key: AE-210.30.30
      name: Parking
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: ParkWhiz
    provider: parkwhiz
    says: lists ParkWhiz as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paychex
    provider: paychex-developer
    says: lists Paychex as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paycor
    provider: paycor
    says: lists Paycor as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paylocity
    provider: paylocity
    says: lists Paylocity as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: PeopleHR
    provider: peoplehr
    says: lists PeopleHR as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Perk
    provider: perk
    says: lists Perk as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Playroll
    provider: playroll
    says: lists Playroll as an integration
    source: https://use.expensify.com/integrations
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
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Revel Systems
    provider: revel-systems
    says: lists Revel Systems as an integration
    source: https://use.expensify.com/integrations
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
    name: Rillet
    provider: rillet
    says: lists Rillet as an integration
    source: https://use.expensify.com/integrations
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
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Simployer
    provider: simployer
    says: lists Simployer as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.30
      key: AE-210.30.30
      name: Parking
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: SpotHero
    provider: spothero
    says: lists SpotHero as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Spotnana
    provider: spotnana
    says: lists Spotnana as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.30
      key: AE-210.30.30
      name: Parking
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: The Parking Spot
    provider: the-parking-spot
    says: lists The Parking Spot as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220
      key: tax-management
      name: Tax Management
      url: /capabilities/tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Thomson Reuters
    provider: thomson-reuters
    says: lists Thomson Reuters as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: TriNet
    provider: trinet-group
    says: lists TriNet as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.20
      key: AE-210.30.20
      name: Car Rental & Sharing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Tripcatcher
    provider: tripcatcher
    says: lists Tripcatcher as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Uber
    provider: uber
    says: lists Uber as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: UKG
    provider: ukg
    says: lists UKG as an integration
    source: https://use.expensify.com/integrations
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
    name: VAT IT
    provider: vat-it
    says: lists VAT IT as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wells Fargo
    provider: wells-fargo
    says: lists Wells Fargo as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220
      key: tax-management
      name: Tax Management
      url: /capabilities/tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wolters Kluwer
    provider: wolters-kluwer
    says: lists Wolters Kluwer as an integration
    source: https://use.expensify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://use.expensify.com/integrations
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
    source: https://use.expensify.com/integrations
    tier: declared
  kind: commercial
  name: Expensify
  page: /applications/expense-management/expensify/
  slug: expensify
  url: https://www.expensify.com/
- anchor: ramp
  counts:
    declared: 59
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
  - route: integrations page
    url: https://ramp.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Acumatica
    provider: acumatica
    says: lists Acumatica as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP
    provider: adp
    says: lists ADP as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ally Bank
    provider: ally-financial
    says: lists Ally Bank as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alpine Bank
    provider: alpine-bank
    says: lists Alpine Bank as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Business
    provider: amazon
    says: lists Amazon Business as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: American Airlines AAdvantage Business
    provider: american-airlines
    says: lists American Airlines AAdvantage Business as an integration
    source: https://ramp.com/integrations
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
    name: Aplos
    provider: aplos
    says: lists Aplos as an integration
    source: https://ramp.com/integrations
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
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: BambooHR
    provider: bamboohr
    says: lists BambooHR as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bank of America
    provider: bank-of-america
    says: lists Bank of America as an integration
    source: https://ramp.com/integrations
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
    name: Blackbaud
    provider: blackbaud
    says: lists Blackbaud as an integration
    source: https://ramp.com/integrations
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
    name: Campfire
    provider: campfire
    says: lists Campfire as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    credit: null
    layer: domain
    name: CloudEagle
    provider: cloudeagle
    says: lists CloudEagle as an integration
    source: https://ramp.com/integrations
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
    name: Deltek Vantagepoint
    provider: deltek
    says: lists Deltek Vantagepoint as an integration
    source: https://ramp.com/integrations
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
    name: Digits
    provider: digits-com
    says: lists Digits as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: common
    name: Docusign
    provider: docusign
    says: lists Docusign as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: DoorDash
    provider: doordash
    says: lists DoorDash as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4290
      key: saas-trust-service-compliance-management
      name: SaaS Trust & Service Compliance Management
      url: /capabilities/saas-trust-service-compliance-management/
      via_parent: null
    credit: null
    layer: common
    name: Drata
    provider: drata
    says: lists Drata as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://ramp.com/integrations
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
    name: DualEntry
    provider: dualentry
    says: lists DualEntry as an integration
    source: https://ramp.com/integrations
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
    name: Finaloop
    provider: finaloop
    says: lists Finaloop as an integration
    source: https://ramp.com/integrations
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
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: common
    name: Ironclad
    provider: ironclad
    says: lists Ironclad as an integration
    source: https://ramp.com/integrations
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
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Justworks
    provider: justworks
    says: lists Justworks as an integration
    source: https://ramp.com/integrations
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
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft
    provider: lyft
    says: lists Lyft as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mercury
    provider: mercury
    says: lists Mercury as an integration
    source: https://ramp.com/integrations
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
    name: Microsoft Dynamics 365 Business Central
    provider: microsoft-dynamics-365-business-central
    says: lists Microsoft Dynamics 365 Business Central as an integration
    source: https://ramp.com/integrations
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
    name: Microsoft Dynamics 365 Finance and Operations
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 Finance and Operations as an integration
    source: https://ramp.com/integrations
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
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://ramp.com/integrations
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
    name: NetSuite
    provider: netsuite
    says: lists NetSuite as an integration
    source: https://ramp.com/integrations
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
    name: Odoo
    provider: odoo
    says: lists Odoo as an integration
    source: https://ramp.com/integrations
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
    source: https://ramp.com/integrations
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
    name: Oracle Fusion Cloud
    provider: oracle
    says: lists Oracle Fusion Cloud as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paychex
    provider: paychex-developer
    says: lists Paychex as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paylocity
    provider: paylocity
    says: lists Paylocity as an integration
    source: https://ramp.com/integrations
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
    name: Puzzle
    provider: puzzle
    says: lists Puzzle as an integration
    source: https://ramp.com/integrations
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
    name: QuickBooks Online / Desktop
    provider: quickbooks
    says: lists QuickBooks Online / Desktop as an integration
    source: https://ramp.com/integrations
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
    name: Rillet
    provider: rillet
    says: lists Rillet as an integration
    source: https://ramp.com/integrations
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
    name: Sage 100 / Sage 300
    provider: sage
    says: lists Sage 100 / Sage 300 as an integration
    source: https://ramp.com/integrations
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
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP SuccessFactors
    provider: sap-successfactors
    says: lists SAP SuccessFactors as an integration
    source: https://ramp.com/integrations
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
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square Payroll
    provider: square
    says: lists Square Payroll as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: TD Bank
    provider: td-bank
    says: lists TD Bank as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: TriNet
    provider: trinet-group
    says: lists TriNet as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Uber
    provider: uber
    says: lists Uber as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: UKG Pro / UKG Ready
    provider: ukg
    says: lists UKG Pro / UKG Ready as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: US Bank
    provider: us-bancorp
    says: lists US Bank as an integration
    source: https://ramp.com/integrations
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
    name: Viewpoint Spectrum / Vista
    provider: trimble
    says: lists Viewpoint Spectrum / Vista as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wells Fargo
    provider: wells-fargo
    says: lists Wells Fargo as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://ramp.com/integrations
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
    name: Workday Financial Management
    provider: workday
    says: lists Workday Financial Management as an integration
    source: https://ramp.com/integrations
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
    source: https://ramp.com/integrations
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
    name: Yardi
    provider: yardi
    says: lists Yardi as an integration
    source: https://ramp.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zenefits
    provider: zenefits
    says: lists Zenefits as an integration
    source: https://ramp.com/integrations
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
    name: Zoho Books
    provider: zoho-books
    says: lists Zoho Books as an integration
    source: https://ramp.com/integrations
    tier: declared
  kind: commercial
  name: Ramp
  page: /applications/expense-management/ramp/
  slug: ramp
  url: https://ramp.com/
- anchor: brex
  counts:
    declared: 81
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.brex.mobile/latest/
  - route: integrations page
    url: https://www.brex.com/product/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.brex.mobile/latest/
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
    name: 1Password
    provider: 1password
    says: lists 1Password as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP Workforce Now
    provider: adp
    says: lists ADP Workforce Now as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alexis
    provider: alexishr
    says: lists Alexis as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Altera Payroll
    provider: altera-payroll
    says: lists Altera Payroll as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bamboo HR
    provider: bamboohr
    says: lists Bamboo HR as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Breathe
    provider: breathe-hr
    says: lists Breathe as an integration
    source: https://www.brex.com/product/integrations
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
    name: Campfire
    provider: campfire
    says: lists Campfire as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Charlie
    provider: charliehr
    says: lists Charlie as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ChartHop
    provider: charthop
    says: lists ChartHop as an integration
    source: https://www.brex.com/product/integrations
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
    name: ChatGPT
    provider: openai
    says: lists ChatGPT as an integration
    source: https://www.brex.com/product/integrations
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
    name: Claude
    provider: anthropic
    says: lists Claude as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClayHR
    provider: clayhr
    says: lists ClayHR as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Conferma
    provider: conferma
    says: lists Conferma as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    credit: null
    layer: domain
    name: Coupa
    provider: coupa
    says: lists Coupa as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    credit: null
    layer: common
    name: Dashblock
    provider: dashblock
    says: lists Dashblock as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dayforce
    provider: dayforce
    says: lists Dayforce as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Deel
    provider: deel-com
    says: lists Deel as an integration
    source: https://www.brex.com/product/integrations
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
    name: Digits
    provider: digits-com
    says: lists Digits as an integration
    source: https://www.brex.com/product/integrations
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
    name: DualEntry
    provider: dualentry
    says: lists DualEntry as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    credit: null
    layer: domain
    name: Expensify
    provider: expensify
    says: lists Expensify as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshteam
    provider: freshteam
    says: lists Freshteam as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    credit: null
    layer: domain
    name: GEP
    provider: gep
    says: lists GEP as an integration
    source: https://www.brex.com/product/integrations
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
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.brex.com/product/integrations
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
    name: Hanover Park
    provider: hanover-park
    says: lists Hanover Park as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: lists HiBob as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HR Cloud
    provider: hr-cloud
    says: lists HR Cloud as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HR Partner
    provider: hr-partner
    says: lists HR Partner as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Humaans
    provider: humaans-io
    says: lists Humaans as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220
      key: tax-management
      name: Tax Management
      url: /capabilities/tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Inkle
    provider: inkle
    says: lists Inkle as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Insperity Premier
    provider: insperity
    says: lists Insperity Premier as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: IntelliHR
    provider: intelihr
    says: lists IntelliHR as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Justworks
    provider: justworks
    says: lists Justworks as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kallidus
    provider: kallidus
    says: lists Kallidus as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lano
    provider: lano
    says: lists Lano as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lattice
    provider: lattice
    says: lists Lattice as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lucca
    provider: lucca
    says: lists Lucca as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft Business
    provider: lyft
    says: lists Lyft Business as an integration
    source: https://www.brex.com/product/integrations
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
    name: Microsoft Azure AD
    provider: microsoft-entra
    says: lists Microsoft Azure AD as an integration
    source: https://www.brex.com/product/integrations
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
    name: Microsoft Dynamics 365 Business Central
    provider: microsoft-dynamics-365-business-central
    says: lists Microsoft Dynamics 365 Business Central as an integration
    source: https://www.brex.com/product/integrations
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
    name: Microsoft Dynamics 365 F&O
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 F&O as an integration
    source: https://www.brex.com/product/integrations
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
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Namely
    provider: namely
    says: lists Namely as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Navan
    provider: navan
    says: lists Navan as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nmbrs
    provider: nmbrs
    says: lists Nmbrs as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Officient
    provider: officient
    says: lists Officient as an integration
    source: https://www.brex.com/product/integrations
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
    source: https://www.brex.com/product/integrations
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
    name: Oracle Fusion Cloud ERP
    provider: oracle
    says: lists Oracle Fusion Cloud ERP as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle Fusion Cloud HCM
    provider: oracle
    says: lists Oracle Fusion Cloud HCM as an integration
    source: https://www.brex.com/product/integrations
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
    name: Oracle Netsuite
    provider: netsuite
    says: lists Oracle Netsuite as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paychex
    provider: paychex-developer
    says: lists Paychex as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paycor
    provider: paycor
    says: lists Paycor as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paylocity
    provider: paylocity
    says: lists Paylocity as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Personio
    provider: personio
    says: lists Personio as an integration
    source: https://www.brex.com/product/integrations
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
    name: Pipedream
    provider: pipedream
    says: lists Pipedream as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ProLiant
    provider: proliant
    says: lists ProLiant as an integration
    source: https://www.brex.com/product/integrations
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
    name: Puzzle
    provider: puzzle
    says: lists Puzzle as an integration
    source: https://www.brex.com/product/integrations
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
    name: QuickBooks Desktop / Online
    provider: quickbooks
    says: lists QuickBooks Desktop / Online as an integration
    source: https://www.brex.com/product/integrations
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
    name: Rillet
    provider: rillet
    says: lists Rillet as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rippling
    provider: rippling
    says: lists Rippling as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: Sabre
    provider: sabre
    says: lists Sabre as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sage HR
    provider: sage-hr
    says: lists Sage HR as an integration
    source: https://www.brex.com/product/integrations
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
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP Concur
    provider: concur
    says: lists SAP Concur as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP SuccessFactors
    provider: sap-successfactors
    says: lists SAP SuccessFactors as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sesame
    provider: sesame-hr
    says: lists Sesame as an integration
    source: https://www.brex.com/product/integrations
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
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: TriNet
    provider: trinet-group
    says: lists TriNet as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Uber for Business
    provider: uber
    says: lists Uber for Business as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: UKG
    provider: ukg
    says: lists UKG as an integration
    source: https://www.brex.com/product/integrations
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
    name: VAT IT
    provider: vat-it
    says: lists VAT IT as an integration
    source: https://www.brex.com/product/integrations
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
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://www.brex.com/product/integrations
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
    name: Workato
    provider: workato
    says: lists Workato as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://www.brex.com/product/integrations
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
    name: Workday Financials ERP
    provider: workday
    says: lists Workday Financials ERP as an integration
    source: https://www.brex.com/product/integrations
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
    source: https://www.brex.com/product/integrations
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
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zenefits
    provider: zenefits
    says: lists Zenefits as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zip
    provider: zip
    says: lists Zip as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.brex.com/product/integrations
    tier: declared
  kind: commercial
  name: Brex
  page: /applications/expense-management/brex/
  slug: brex
  url: https://www.brex.com/
- anchor: sap-concur
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
  - route: integrations page
    url: https://www.concur.com/app-center
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
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Apptentive
    provider: apptentive
    says: ships the Apptentive SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
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
    name: Dynatrace
    provider: dynatrace
    says: ships the Dynatrace SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
    tier: observed
  kind: commercial
  name: SAP Concur
  page: /applications/expense-management/sap-concur/
  slug: sap-concur
  url: https://www.concur.com/
- anchor: splitwise
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
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
    name: Amazon Analytics (Amazon insights)
    provider: amazon-web-services
    says: ships the Amazon Analytics (Amazon insights) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
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
    name: Google Crashlytics
    provider: firebase
    says: ships the Google Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
    tier: observed
  kind: commercial
  name: Splitwise
  page: /applications/expense-management/splitwise/
  slug: splitwise
  url: https://www.splitwise.com/
- anchor: spliit
  counts:
    declared: 2
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/spliit-app/spliit/main/package.json
  - route: source code
    url: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/spliit-app/spliit/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
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
    name: Plausible
    provider: plausible
    says: lists Plausible as an integration
    source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Umami
    provider: umami
    says: lists Umami as an integration
    source: https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
    tier: declared
  kind: self-hosted
  name: Spliit
  page: /applications/expense-management/spliit/
  slug: spliit
  url: https://github.com/spliit-app/spliit
- anchor: ihatemoney
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/spiral-project/ihatemoney/master/pyproject.toml
  - route: source code
    url: https://raw.githubusercontent.com/spiral-project/ihatemoney/master/ihatemoney/currency_convertor.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: exchangerate.host
    provider: exchangerate-host
    says: ships the exchangerate.host SDK or integration code
    source: https://raw.githubusercontent.com/spiral-project/ihatemoney/master/ihatemoney/currency_convertor.py
    tier: observed
  kind: self-hosted
  name: IHateMoney
  page: /applications/expense-management/ihatemoney/
  slug: ihatemoney
  url: https://github.com/spiral-project/ihatemoney
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: expense-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
- category: Finance
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Finance
  store: slack-marketplace
  url: https://slack.com/apps
- category: Accounting
  store: zapier
  url: https://zapier.com/apps
name: Expense & Spend Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry seen in the mobile apps / web analytics in self-hosted apps
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and performance monitoring
- capability:
    attribution: API Evangelist extension
    id: AE-210.10
    key: AE-210.10
    name: Flight Search & Booking
    url: /capabilities/flight-search-booking/
    via_parent: null
  fit: exact
  layer: domain
  why: airline and travel-booking receipts and itineraries
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: ride-hailing receipts
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: every expense tool syncs coded spend to the ERP / GL; the single largest integration group
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: domain
  why: HRIS / payroll sync provisions cardholders, approvers and reimbursements
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: SSO and user provisioning
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM assistants listed as integrations (Claude, ChatGPT, Grok) in the AI & MCP category
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  fit: exact
  layer: domain
  why: meal delivery receipts
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: receipt image storage
- capability:
    attribution: Turbo EA
    id: BC-1340.70
    key: card-transaction-processing-management
    name: Card Transaction Processing Management
    url: /capabilities/card-transaction-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: company and bring-your-own card feeds
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app surveys
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: VAT reclaim on foreign spend
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: approvals and receipt nudges in chat
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: itemized receipts straight from the POS
- capability:
    attribution: Turbo EA
    id: BC-500
    key: procurement-management
    name: Procurement Management
    url: /capabilities/procurement-management/
    via_parent: null
  fit: exact
  layer: domain
  why: procurement and purchasing systems feed spend requests
- capability:
    attribution: Turbo EA
    id: BC-220
    key: tax-management
    name: Tax Management
    url: /capabilities/tax-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: tax and accountant-practice software
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  fit: exact
  layer: agent
  why: coding agent listed in the AI & MCP category
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: agent
  why: receipt scanning / extraction
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: receipt capture over messaging
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: nearest
  layer: common
  why: push notifications for approvals
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: nearest
  layer: common
  why: meeting tooling
- capability:
    attribution: API Evangelist extension
    id: AE-210.20.10
    key: AE-210.20.10
    name: Hotel Booking
    url: /capabilities/lodging-stays/
    via_parent: Lodging & Stays
  fit: exact
  layer: domain
  why: hotel booking receipts
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.20
    key: AE-210.30.20
    name: Car Rental & Sharing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: nearest
  layer: domain
  why: mileage tracking
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.30
    key: AE-210.30.30
    name: Parking
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: parking receipts
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: multi-currency conversion
- capability:
    attribution: API Evangelist extension
    id: AE-230.70
    key: AE-230.70
    name: Calendar & Holiday Data
    url: /capabilities/calendar-holiday-data/
    via_parent: null
  fit: nearest
  layer: common
  why: calendar context for trips and meetings
- capability:
    attribution: Turbo EA
    id: BC-200.20
    key: accounts-payable-management
    name: Accounts Payable Management
    url: /capabilities/accounts-payable-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: expense tools sync with one another and with AP
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: finance dashboards and practice reporting
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: bank connections fund cards and pay reimbursements
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  fit: exact
  layer: common
  why: vendor contracts tied to spend requests
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: deep linking / attribution
- capability:
    attribution: Turbo EA
    id: BC-4040
    key: guest-traveller-management
    name: Guest & Traveller Management
    url: /capabilities/guest-traveller-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: travel management companies hand trip spend to the expense report
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code automation of expense workflows
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: spend requests linked to work tracking
- capability:
    attribution: Turbo EA
    id: BC-4290
    key: saas-trust-service-compliance-management
    name: SaaS Trust & Service Compliance Management
    url: /capabilities/saas-trust-service-compliance-management/
    via_parent: null
  fit: exact
  layer: common
  why: compliance evidence on spend controls
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  fit: exact
  layer: domain
  why: candidate expenses from the ATS
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp: &id003
        status: none
      name: Workday
      slug: workday
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags: &id004
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: declared
      url: /providers/workday/
    - agent_band: agent-ready
      agent_readiness: 44.9
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Justworks
      slug: justworks
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - Human Resources
      - PEO
      - Payroll
      tier: declared
      url: /providers/justworks/
    - agent_band: agent-ready
      agent_readiness: 39.8
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        status: none
      name: ADP
      slug: adp
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/adp/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        source: https://documentation.bamboohr.com/docs/mcp-server
        status: verified
      name: BambooHR
      slug: bamboohr
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Payroll
      - Time Tracking
      tier: declared
      url: /providers/bamboohr/
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: Paychex
      slug: paychex-developer
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Paychex Flex
      tier: declared
      url: /providers/paychex-developer/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Brex
      - Expensify
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: Paylocity
      slug: paylocity
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/paylocity/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: none
      name: UKG
      slug: ukg
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HCM
      - Human Resources
      - Payroll
      - Workforce Management
      tier: declared
      url: /providers/ukg/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Brex
      - Expensify
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: TriNet
      slug: trinet-group
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - Compliance
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/trinet-group/
    - agent_band: agent-native
      agent_readiness: 52.0
      apps:
      - Brex
      - Expensify
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://developer.deel.com/docs/mcp
        status: documented
      name: Deel
      slug: deel-com
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Employer of Record
      - Global Payroll
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/deel-com/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Brex
      - Expensify
      band: strong
      in_catalog: true
      kin_score: 59.4
      mcp:
        status: none
      name: Namely
      slug: namely
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Employee Data
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/namely/
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Brex
      - Expensify
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Humaans
      slug: humaans-io
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - People Analytics
      - People Operations
      tier: declared
      url: /providers/humaans-io/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Brex
      - Expensify
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Lucca
      slug: lucca
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - Human Resources
      - Payroll
      - Software-as-a-Service
      tier: declared
      url: /providers/lucca/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Brex
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 30.6
      mcp:
        status: none
      name: Breathe
      slug: breathe-hr
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Absence Management
      - Employee Management
      - HRIS
      - Human Resources
      tier: declared
      url: /providers/breathe-hr/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Brex
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        source: https://apidocs.hibob.com/docs/hibob-mcp-server
        status: verified
      name: HiBob
      slug: bob
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Employee Management
      - HRIS
      - Human Resources
      - Time Off
      tier: declared
      url: /providers/bob/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Brex
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: SAP SuccessFactors
      slug: sap-successfactors
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HCM
      - Human Resources
      - Payroll
      - Talent Management
      tier: declared
      url: /providers/sap-successfactors/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Brex
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: Freshteam
      slug: freshteam
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Applicant Tracking
      - HRIS
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/freshteam/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Brex
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 20.1
      mcp:
        status: none
      name: Dayforce
      slug: dayforce
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - HCM
      - Payroll
      - Workforce Management
      tier: declared
      url: /providers/dayforce/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Brex
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 19.3
      mcp:
        status: none
      name: Zenefits
      slug: zenefits
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits Administration
      - HRIS
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/zenefits/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Brex
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 16.8
      mcp:
        status: unknown
      name: Kallidus
      slug: kallidus
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - Compliance
      - LMS
      - Performance Management
      tier: declared
      url: /providers/kallidus/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Brex
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: none
      name: HR Cloud
      slug: hr-cloud
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Frontline
      - Human Resources
      - Software-as-a-Service
      tier: declared
      url: /providers/hr-cloud/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Brex
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        status: none
      name: Insperity
      slug: insperity
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits
      - Fortune 1000
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/insperity/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Brex
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: none
      name: Paycor
      slug: paycor
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Benefits Administration
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/paycor/
    - agent_band: null
      agent_readiness: null
      apps:
      - Brex
      - Expensify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: inteliHR
      slug: intelihr
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp: &id009
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square Payroll
      slug: square
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags: &id010
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp: &id001
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Fusion Cloud HCM
      slug: oracle
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags: &id002
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Brex
      band: strong
      in_catalog: true
      kin_score: 59.9
      mcp:
        status: none
      name: ChartHop
      slug: charthop
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - HRIS
      - Human Resources
      - People Analytics
      tier: declared
      url: /providers/charthop/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Brex
      band: developing
      in_catalog: true
      kin_score: 43.2
      mcp:
        source: https://github.com/HR-Partner/hrpartner-mcp
        status: verified
      name: HR Partner
      slug: hr-partner
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Employee Records
      - HRIS
      - Human Resources
      - Leave Management
      tier: declared
      url: /providers/hr-partner/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        status: none
      name: Lattice
      slug: lattice
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Human Resources
      - OKRs
      - People Management
      - Performance Management
      tier: declared
      url: /providers/lattice/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        source: https://www.clayhr.com/mcp-ai-powered-hr-data-access
        status: verified
      name: ClayHR
      slug: clayhr
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - HRMS
      - Human Resources
      - Software-as-a-Service
      tier: declared
      url: /providers/clayhr/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: Sage HR
      slug: sage-hr
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - People
      - Small Business
      tier: declared
      url: /providers/sage-hr/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: Rippling
      slug: rippling
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HCM
      - Human Resources
      - IT
      - Payroll
      tier: declared
      url: /providers/rippling/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 30.6
      mcp:
        status: unknown
      name: PeopleHR
      slug: peoplehr
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      - Human Resources
      - Payroll
      - Software-as-a-Service
      tier: declared
      url: /providers/peoplehr/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: Charlie
      slug: charliehr
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Leave
      - People
      tier: declared
      url: /providers/charliehr/
    - agent_band: agent-ready
      agent_readiness: 41.0
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Personio
      slug: personio
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Applicant Tracking
      - HRIS
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/personio/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: none
      name: Nmbrs
      slug: nmbrs
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Employee Management
      - HRIS
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/nmbrs/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        status: unknown
      name: Lano
      slug: lano
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - Employer of Record
      - Global Hiring
      - Payroll
      tier: declared
      url: /providers/lano/
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: none
      name: Keka
      slug: keka
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Attendance
      - Human Resources
      - Leave Management
      - Payroll
      tier: declared
      url: /providers/keka/
    - agent_band: agent-ready
      agent_readiness: 47.3
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Sesame
      slug: sesame-hr
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Time Tracking
      - Workforce Management
      tier: declared
      url: /providers/sesame-hr/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - Brex
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: unknown
      name: Alexis
      slug: alexishr
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - AI Chatbot
      - Integration
      - Payroll
      - People Analytics
      tier: declared
      url: /providers/alexishr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: none
      name: Simployer
      slug: simployer
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Cloud
      - Human Resources
      - Payroll
      - Software-as-a-Service
      tier: declared
      url: /providers/simployer/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Brex
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        status: unknown
      name: ProLiant
      slug: proliant
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Cloud
      - Human Resources
      - Payroll
      - Software-as-a-Service
      tier: declared
      url: /providers/proliant/
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: none
      name: Playroll
      slug: playroll
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Contractor Management
      - Employer of Record
      - Global Payroll
      - Human Resources
      tier: declared
      url: /providers/playroll/
    - agent_band: null
      agent_readiness: null
      apps:
      - Brex
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Altera Payroll
      slug: altera-payroll
      sources:
      - https://www.brex.com/product/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Brex
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Officient
      slug: officient
      sources:
      - https://www.brex.com/product/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Brex
      - Expensify
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Brex
      - Expensify
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp: *id001
      name: Oracle
      slug: oracle
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Brex
      - Expensify
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics
      slug: microsoft-dynamics-365
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-native
      agent_readiness: 50.4
      apps:
      - Brex
      - Expensify
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Rillet
      slug: rillet
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Company
      - ERP
      - Fintech
      tier: declared
      url: /providers/rillet/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Brex
      - Expensify
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 55.0
      mcp:
        source: https://docs.campfire.ai/guides/ai-integration
        status: verified
      name: Campfire AI
      slug: campfire
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Company
      - ERP
      - Finance
      tier: declared
      url: /providers/campfire/
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        source: https://docs.dualentry.com/developers/guides/integrations-and-tools/mcp
        status: documented
      name: DualEntry
      slug: dualentry
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Artificial Intelligence
      - Company
      - ERP
      tier: declared
      url: /providers/dualentry/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Brex
      - Expensify
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Brex
      - Expensify
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: NetSuite
      slug: netsuite
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Brex
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Microsoft Dynamics 365 Business Central
      slug: microsoft-dynamics-365-business-central
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Cloud ERP
      - ERP
      - Finance
      tier: declared
      url: /providers/microsoft-dynamics-365-business-central/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Brex
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://github.com/digits/mcp-skills
        status: documented
      name: Digits
      slug: digits-com
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - General Ledger
      tier: declared
      url: /providers/digits-com/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Brex
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp: *id003
      name: Workday Financial Management
      slug: workday
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/workday/
    - agent_band: agent-ready
      agent_readiness: 34.1
      apps:
      - Brex
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 49.3
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=io.puzzle/puzzle
        status: verified
      name: Puzzle
      slug: puzzle
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Company
      - Finance
      tier: declared
      url: /providers/puzzle/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 66.6
      mcp:
        status: none
      name: Viewpoint Spectrum / Vista
      slug: trimble
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Construction
      - GPS
      - Geospatial
      - Transportation
      tier: declared
      url: /providers/trimble/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Blackbaud
      slug: blackbaud
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - CRM
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/blackbaud/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: documented
      name: Zoho Books
      slug: zoho-books
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Expenses
      - Invoicing
      tier: declared
      url: /providers/zoho-books/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: none
      name: Sage 100 / Sage 300
      slug: sage
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Cloud Software
      - ERP
      tier: declared
      url: /providers/sage/
    - agent_band: agent-aware
      agent_readiness: 25.0
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://claude.com/connectors/yardi-virtuoso
        status: documented
      name: Yardi
      slug: yardi
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Accounting
      - Co-Working
      - Commercial Real Estate
      - Investment Management
      tier: declared
      url: /providers/yardi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Aplos
      slug: aplos
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Accounting
      - Company
      - Non-Profit
      - Software
      tier: declared
      url: /providers/aplos/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        status: none
      name: Odoo
      slug: odoo
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Business Applications
      - CRM
      - ERP
      - Open Source
      tier: declared
      url: /providers/odoo/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 21.0
      mcp:
        status: unknown
      name: Fintua
      slug: fintua
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      - Compliance
      - Tax
      - VAT
      tier: declared
      url: /providers/fintua/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        source: https://learning.deltek.com/bundle/MCP_Server_Setup_Guide_for_REST_APIs/page/overview.html
        status: documented
      name: Deltek Vantagepoint
      slug: deltek
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Company
      - Enterprise
      - Project Management
      - Software
      tier: declared
      url: /providers/deltek/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Brex
      band: emerging
      in_catalog: true
      kin_score: 17.7
      mcp:
        status: none
      name: Hanover Park
      slug: hanover-park
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - Enterprise Software
      - Fund Administration
      - Private Equity
      tier: declared
      url: /providers/hanover-park/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 17.1
      mcp:
        status: none
      name: Acumatica
      slug: acumatica
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Cloud ERP
      - ERP
      - Financial Management
      - Inventory
      tier: declared
      url: /providers/acumatica/
    - agent_band: agent-aware
      agent_readiness: 13.0
      apps:
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 16.6
      mcp:
        status: none
      name: Finaloop
      slug: finaloop
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Company
      - E-Commerce
      tier: declared
      url: /providers/finaloop/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: none
      name: Certinia
      slug: certinia
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - ASC 606
      - ERP
      - Professional Services Automation
      - Revenue Recognition
      tier: declared
      url: /providers/certinia/
  - capability:
      attribution: Turbo EA
      id: BC-1340.70
      key: card-transaction-processing-management
      name: Card Transaction Processing Management
      url: /capabilities/card-transaction-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 51.8
      apps:
      - Expensify
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        status: none
      name: Citi
      slug: citi
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Banking
      - Financial Services
      - Open Banking
      - Payments
      tier: declared
      url: /providers/citi/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Expensify
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: ANZ
      slug: anz
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Banks
      - CDR
      - Finance
      - Open Banking
      tier: declared
      url: /providers/anz/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Expensify
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp: &id005
        status: none
      name: Wells Fargo
      slug: wells-fargo
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags: &id006
      - Banking
      - Consumer Banking
      - Fortune 100
      tier: declared
      url: /providers/wells-fargo/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp: &id007
        status: none
      name: Bank of America
      slug: bank-of-america
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags: &id008
      - Banking
      - Corporate Banking
      - Finance
      - Payments
      tier: declared
      url: /providers/bank-of-america/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        status: none
      name: Chase
      slug: chase
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Account Aggregation
      - Banking
      - Consent
      - Credit Cards
      tier: declared
      url: /providers/chase/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Capital One
      slug: capital-one
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Authorization
      - Auto Finance
      - Banking
      - Credit Cards
      tier: declared
      url: /providers/capital-one/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 20.3
      mcp:
        status: none
      name: American Express
      slug: american-express
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Card Network
      - Credit Cards
      - Financial Services
      - Payments
      tier: declared
      url: /providers/american-express/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Brex
      band: emerging
      in_catalog: true
      kin_score: 16.8
      mcp:
        status: unknown
      name: Conferma
      slug: conferma
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Company
      - Fintech
      - Payments
      - Virtual Card
      tier: declared
      url: /providers/conferma/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 9.5
      mcp:
        status: none
      name: AirPlus International
      slug: airplus
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      - Corporate Cards
      - Expense Management
      - Payments
      tier: declared
      url: /providers/airplus/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 2.0
      mcp:
        status: unknown
      name: Kiwibank
      slug: kiwibank
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Banking
      - Company
      - Finance
      - New Zealand
      tier: declared
      url: /providers/kiwibank/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Expensify
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: American Airlines
      slug: american-airlines
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Airlines
      - Aviation
      - Flights
      - Travel
      tier: declared
      url: /providers/american-airlines/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Expensify
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        status: none
      name: Perk
      slug: perk
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      - Corporate Travel
      - Expense Management
      - Spend Management
      tier: declared
      url: /providers/perk/
    - agent_band: agent-ready
      agent_readiness: 46.1
      apps:
      - Expensify
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Spotnana
      slug: spotnana
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      - Corporate Travel
      - Travel
      - Travel Management
      tier: declared
      url: /providers/spotnana/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Brex
      band: developing
      in_catalog: true
      kin_score: 40.3
      mcp:
        status: none
      name: Sabre
      slug: sabre
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Airlines
      - GDS
      - Hotels
      - Travel
      tier: declared
      url: /providers/sabre/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        source: https://developer.navan.com/mcp/
        status: verified
      name: Navan
      slug: navan
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Corporate Cards
      - Corporate Travel
      - Expense Management
      - Spend Management
      tier: declared
      url: /providers/navan/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 22.7
      mcp:
        status: none
      name: KAYAK for Business
      slug: kayak
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      - Flights
      - Metasearch
      - Travel
      tier: declared
      url: /providers/kayak/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        status: none
      name: Delta
      slug: delta-airlines
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Air Travel
      - Airlines
      - Aviation
      - Booking
      tier: declared
      url: /providers/delta-airlines/
    - agent_band: null
      agent_readiness: null
      apps:
      - Expensify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Egencia
      slug: egencia
      sources:
      - https://use.expensify.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Expensify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Locomote
      slug: locomote
      sources:
      - https://use.expensify.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: Lyft
      slug: lyft
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Micromobility
      - Mobility
      - Ride Hailing
      - Transportation
      tier: declared
      url: /providers/lyft/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Brex
      - Expensify
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: none
      name: Uber
      slug: uber
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Food Delivery
      - Ride Hailing
      - Taxis
      - Transportation
      tier: declared
      url: /providers/uber/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        status: none
      name: Bolt
      slug: bolt-eu
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Mobility
      - Ride Booking
      - Ride Hailing
      - Transportation
      tier: declared
      url: /providers/bolt-eu/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Grab
      slug: grab
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Digital Payments
      - Food Delivery
      - Last Mile Delivery
      - Ride Hailing
      tier: declared
      url: /providers/grab/
  - capability:
      attribution: Turbo EA
      id: BC-210.10
      key: cash-management
      name: Cash Management
      url: /capabilities/cash-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp: *id005
      name: Wells Fargo
      slug: wells-fargo
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/wells-fargo/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://mercury.com/mcp
        status: verified
      name: Mercury
      slug: mercury
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Banking
      - Fintech
      - Startups
      - Treasury
      tier: declared
      url: /providers/mercury/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        status: none
      name: TD Bank
      slug: td-bank
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - AML
      - Account Aggregation
      - Akoya
      - Banking
      tier: declared
      url: /providers/td-bank/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp: *id007
      name: Bank of America
      slug: bank-of-america
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/bank-of-america/
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: none
      name: US Bank
      slug: us-bancorp
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Banking
      - Corporate Banking
      - Finance
      - Fortune 500
      tier: declared
      url: /providers/us-bancorp/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Ramp
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: unknown
      name: Alpine Bank
      slug: alpine-bank
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Banking
      - Colorado
      - Company
      - Financial Services
      tier: declared
      url: /providers/alpine-bank/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ramp
      band: minimal
      in_catalog: true
      kin_score: 10.4
      mcp:
        status: none
      name: Ally Bank
      slug: ally-financial
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Auto Finance
      - Banking
      - Investing
      - Lending
      tier: declared
      url: /providers/ally-financial/
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Business
      slug: amazon
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: declared
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Brex
      band: developing
      in_catalog: true
      kin_score: 52.6
      mcp:
        status: none
      name: Coupa
      slug: coupa
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - BSM
      - Business Spend Management
      - Cloud Platform
      - Enterprise
      tier: declared
      url: /providers/coupa/
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: CloudEagle
      slug: cloudeagle
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Access Governance
      - Cost Optimization
      - License Management
      - Procurement
      tier: declared
      url: /providers/cloudeagle/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: none
      name: Zip
      slug: zip
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Approval Workflows
      - Intake to Pay
      - Procurement
      - Spend Management
      tier: declared
      url: /providers/zip/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Brex
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        status: none
      name: GEP
      slug: gep
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Procurement
      - Supply Chain
      tier: declared
      url: /providers/gep/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.30
      key: AE-210.30.30
      name: Parking
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        status: none
      name: ParkWhiz
      slug: parkwhiz
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Booking
      - Mobility
      - Parking
      - Reservations
      tier: declared
      url: /providers/parkwhiz/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: SpotHero
      slug: spothero
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Mobility
      - Navigation
      - Parking
      - Transportation
      tier: declared
      url: /providers/spothero/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 1.1
      mcp:
        status: unknown
      name: The Parking Spot
      slug: the-parking-spot
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/the-parking-spot/
  - capability:
      attribution: Turbo EA
      id: BC-220
      key: tax-management
      name: Tax Management
      url: /capabilities/tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.1
      apps:
      - Expensify
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        status: none
      name: Thomson Reuters
      slug: thomson-reuters
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Finance
      - Legal
      - Risk Management
      - Tax
      tier: declared
      url: /providers/thomson-reuters/
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: unknown
      name: Inkle
      slug: inkle
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Company
      - Tax
      tier: declared
      url: /providers/inkle/
    - agent_band: null
      agent_readiness: null
      apps:
      - Expensify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Wolters Kluwer
      slug: wolters-kluwer
      sources:
      - https://use.expensify.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Brex
      band: developing
      in_catalog: true
      kin_score: 42.3
      mcp:
        status: none
      name: SAP Concur
      slug: concur
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Expense Management
      - Finance
      - Invoices
      - SAP
      tier: declared
      url: /providers/concur/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Brex
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: none
      name: Expensify
      slug: expensify
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Corporate Cards
      - Expense Management
      - Expense Reporting
      - Receipt Scanning
      tier: declared
      url: /providers/expensify/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 17.0
      mcp:
        status: unknown
      name: IRIS Practice Engine
      slug: iris-software
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Accounting
      - Company
      - Payroll
      - Software
      tier: declared
      url: /providers/iris-software/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Expensify
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: 9Spokes
      slug: 9spokes
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Banking
      - Company
      - Fintech
      - Small Business
      tier: declared
      url: /providers/9spokes/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.20
      key: AE-140.100.20
      name: Food Delivery
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Expensify
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        status: none
      name: DoorDash
      slug: doordash
      sources:
      - https://ramp.com/integrations
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Delivery
      - Last Mile Delivery
      - Logistics
      - On-Demand
      tier: declared
      url: /providers/doordash/
  - capability:
      attribution: Turbo EA
      id: BC-4040
      key: guest-traveller-management
      name: Guest & Traveller Management
      url: /capabilities/guest-traveller-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: CTM
      slug: corporate-travel-management
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Australia
      - Corporate Travel
      - Travel
      - Travel Management Company
      tier: declared
      url: /providers/corporate-travel-management/
    - agent_band: agent-aware
      agent_readiness: 13.0
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: Corporate Traveler
      slug: flight-centre
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Australia
      - Corporate Travel
      - Travel
      - Travel Agency
      tier: declared
      url: /providers/flight-centre/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Brex
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 16.5
      mcp:
        status: unknown
      name: VAT IT
      slug: vat-it
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Compliance
      - Tax
      tier: declared
      url: /providers/vat-it/
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp: *id009
      name: Square
      slug: square
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags: *id010
      tier: declared
      url: /providers/square/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Expensify
      band: emerging
      in_catalog: true
      kin_score: 19.6
      mcp:
        status: none
      name: Revel Systems
      slug: revel-systems
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Point-of-Sale
      - Restaurant
      - Retail
      - iPad
      tier: declared
      url: /providers/revel-systems/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.20
      key: AE-210.30.20
      name: Car Rental & Sharing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Expensify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Tripcatcher
      slug: tripcatcher
      sources:
      - https://use.expensify.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - IHateMoney
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: none
      name: exchangerate.host
      slug: exchangerate-host
      sources:
      - https://raw.githubusercontent.com/spiral-project/ihatemoney/master/ihatemoney/currency_convertor.py
      status: profiled
      tags:
      - Exchange Rates
      - Foreign Exchange
      - Public APIs
      tier: observed
      url: /providers/exchangerate-host/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.20.10
      key: AE-210.20.10
      name: Hotel Booking
      url: /capabilities/lodging-stays/
      via_parent: Lodging & Stays
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - Expensify
      band: strong
      in_catalog: true
      kin_score: 64.0
      mcp:
        status: none
      name: Hotel Engine
      slug: hotel-engine
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Business Travel
      - Company
      - Lodging
      - Travel
      tier: declared
      url: /providers/hotel-engine/
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Expensify
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        status: none
      name: Greenhouse
      slug: greenhouse
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Applicant Tracking
      - Greenhouse
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/greenhouse/
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
      agent_readiness: 37.9
      apps:
      - Splitwise
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Analytics (Amazon insights)
      slug: amazon-web-services
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - SAP Concur
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Expensify
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id011
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
      status: profiled
      tags: &id012
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/fullstory/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Spliit
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Umami
      slug: umami
      sources:
      - https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
      status: profiled
      tags:
      - Cookieless Tracking
      - Open Source
      - Privacy
      - Web Analytics
      tier: declared
      url: /providers/umami/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Spliit
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: declared
      url: /providers/plausible/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Brex
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Azure AD
      slug: microsoft-entra
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://1password.dev/environments/mcp-server
        status: verified
      name: 1Password
      slug: 1password
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Password Manager
      - Passwords
      - Secrets
      - Security
      tier: declared
      url: /providers/1password/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
        status: verified
      name: JumpCloud
      slug: jumpcloud
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Directory Services
      - Identity
      - MFA
      - SSO
      tier: declared
      url: /providers/jumpcloud/
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
      - Brex
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Brex
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://ramp.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
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
      - Expensify
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - SAP Concur
      band: exemplar
      in_catalog: true
      kin_score: 85.6
      mcp:
        source: https://github.com/dynatrace-oss/dynatrace-mcp
        status: verified
      name: Dynatrace
      slug: dynatrace
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
      status: profiled
      tags:
      - AI Operations
      - APM
      - Analytics
      - Application Performance Monitoring
      tier: observed
      url: /providers/dynatrace/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Splitwise
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id011
      name: Google Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.Splitwise.SplitwiseMobile/latest/
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: declared
      url: /providers/linear-app/
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
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://docs.workato.com/mcp.html
        status: verified
      name: Workato
      slug: workato
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - AI Agents
      - API Management
      - Automation
      - B2B
      tier: declared
      url: /providers/workato/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Brex
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://pipedream.com/docs/connect/mcp
        status: verified
      name: Pipedream
      slug: pipedream
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Connect
      - Pipedream
      - Pro-Code-API-Composition
      - Workflows
      tier: declared
      url: /providers/pipedream/
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 71.5
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: Docusign
      slug: docusign
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: Ironclad
      slug: ironclad
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Contract Lifecycle Management
      - Contracts
      - Legal Tech
      - LegalOps
      tier: declared
      url: /providers/ironclad/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Brex
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.brex.mobile/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - SAP Concur
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        status: none
      name: Apptentive
      slug: apptentive
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.concur.breeze/latest/
      status: profiled
      tags:
      - Company
      - Customer Feedback
      - Enterprise
      - Mobile
      tier: observed
      url: /providers/apptentive/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Spliit
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/spliit-app/spliit/main/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
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
      - Ramp
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
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
      - Ramp
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://ramp.com/integrations
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
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Ramp
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Brex
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Dashblock
      slug: dashblock
      sources:
      - https://www.brex.com/product/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Urbanairship
      slug: airship
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
      status: profiled
      tags:
      - Email
      - Mobile
      - Notification
      - Push
      tier: observed
      url: /providers/airship/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.me.mobiexpensifyg/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: Turbo EA
      id: BC-4290
      key: saas-trust-service-compliance-management
      name: SaaS Trust & Service Compliance Management
      url: /capabilities/saas-trust-service-compliance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Ramp
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://developers.drata.com/developer-portal/v2/mcp-server
        status: verified
      name: Drata
      slug: drata
      sources:
      - https://ramp.com/integrations
      status: profiled
      tags:
      - Compliance
      - GRC
      - ISO 27001
      - SOC 2
      tier: declared
      url: /providers/drata/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Brex
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Brex
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
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
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Brex
      - Expensify
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude
      slug: anthropic
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Brex
      - Expensify
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id013
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT
      slug: openai
      sources:
      - https://use.expensify.com/integrations
      - https://www.brex.com/product/integrations
      status: profiled
      tags: &id014
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Expensify
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: none
      name: Grok
      slug: xai
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: declared
      url: /providers/xai/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.10
      key: AE-100.70.10
      name: Coding Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Expensify
      band: strong
      in_catalog: true
      kin_score: 60.0
      mcp:
        status: none
      name: Cursor
      slug: cursor
      sources:
      - https://use.expensify.com/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Editor
      - Developer Tools
      tier: declared
      url: /providers/cursor/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Spliit
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id013
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/spliit-app/spliit/main/.env.example
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 95.0
  declared_only: 146
  distinct_providers: 161
  in_catalog: 153
  mcp:
    documented: 8
    none: 94
    unchecked: 8
    verified: 38
  mcp_verified: 38
  mean_kin_score: 42.2
  observed: 15
  queued: 8
  reference_apps: 7
title: 'Expense & Spend Management: application blueprint'
---
