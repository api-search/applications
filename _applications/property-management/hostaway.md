---
app: Hostaway
app_slug: hostaway
app_url: https://www.hostaway.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4010.50
  key: channel-manager-operations
  layer: domain
  name: Channel Manager Operations
  providers:
  - Airbnb
  - Booking.com
  - Expedia
  - Google Vacation Rentals
  - Vrbo
  url: /capabilities/channel-manager-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Ximplifi
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4060.20
  key: housekeeping-operations
  layer: domain
  name: Housekeeping Operations
  providers:
  - Breezeway
  - Turno
  url: /capabilities/housekeeping-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-2110
  key: insurance-distribution-management
  layer: domain
  name: Insurance Distribution Management
  providers:
  - Safely
  url: /capabilities/insurance-distribution-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Braintree
  - ChargeAutomation
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-440
  key: pricing-management
  layer: domain
  name: Pricing Management
  providers:
  - Beyond
  - PriceLabs
  - Wheelhouse
  url: /capabilities/pricing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Operto
  - RemoteLock
  url: /capabilities/smart-home/
  via_parent: null
category:
  id: property-management
  name: Property & Rental Management
  url: /applications/property-management/
counts:
  declared: 17
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.hostaway.com/marketplace/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id001
      status: none
    slug: airbnb
    status: profiled
    tags: &id002
    - Airbnb
    - Hospitality
    - Reservations
    - Travel
    url: /providers/airbnb/
  layer: domain
  name: Airbnb
  provider: airbnb
  says: lists Airbnb as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440
    key: pricing-management
    name: Pricing Management
    url: /capabilities/pricing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.2
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id003
      status: none
    slug: beyond-pricing
    status: profiled
    tags: &id004
    - Company
    - Revenue Management
    - Short-Term Rental
    - Vacation Rentals
    url: /providers/beyond-pricing/
  layer: domain
  name: Beyond
  provider: beyond-pricing
  says: lists Beyond as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id005
      status: none
    slug: booking-com
    status: profiled
    tags: &id006
    - Accommodation
    - Booking
    - Hospitality
    - Travel
    url: /providers/booking-com/
  layer: domain
  name: Booking.com
  provider: booking-com
  says: lists Booking.com as an integration
  source: https://www.hostaway.com/marketplace/
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
    agent_band: agent-ready
    agent_readiness: 53.6
    band: developing
    in_catalog: true
    kin_score: 44.7
    mcp: &id007
      status: none
    slug: braintree
    status: profiled
    tags: &id008
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: domain
  name: Braintree
  provider: braintree
  says: lists Braintree as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4060.20
    key: housekeeping-operations
    name: Housekeeping Operations
    url: /capabilities/housekeeping-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.4
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id009
      status: unknown
    slug: breezeway
    status: profiled
    tags: &id010
    - Guest Experience
    - Operations Automation
    - Property Management
    - Software-as-a-Service
    url: /providers/breezeway/
  layer: domain
  name: Breezeway
  provider: breezeway
  says: lists Breezeway as an integration
  source: https://www.hostaway.com/marketplace/
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
    agent_band: agent-aware
    agent_readiness: 7.7
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id011
      status: unknown
    slug: chargeautomation
    status: profiled
    tags: &id012
    - Company
    - Guest Experience
    - Hospitality
    - Payments
    url: /providers/chargeautomation/
  layer: domain
  name: ChargeAutomation
  provider: chargeautomation
  says: lists ChargeAutomation as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id013
      source: https://github.com/ExpediaGroup/expedia-travel-recommendations-mcp
      status: verified
    slug: expedia-group
    status: profiled
    tags: &id014
    - Flights
    - Hotels
    - Lodging
    - Travel
    url: /providers/expedia-group/
  layer: domain
  name: Expedia
  provider: expedia-group
  says: lists Expedia as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id015
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id016
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google Vacation Rentals
  provider: google
  says: lists Google Vacation Rentals as an integration
  source: https://www.hostaway.com/marketplace/
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
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id017
      status: none
    slug: operto
    status: profiled
    tags: &id018
    - Company
    - Guest Experience
    - Hospitality
    - Property Management
    url: /providers/operto/
  layer: domain
  name: Operto
  provider: operto
  says: lists Operto as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440
    key: pricing-management
    name: Pricing Management
    url: /capabilities/pricing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: pricelabs
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: PriceLabs
  provider: pricelabs
  says: lists PriceLabs as an integration
  source: https://www.hostaway.com/marketplace/
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
    agent_readiness: 25.0
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id021
      status: none
    slug: remotelock
    status: profiled
    tags: &id022
    - Access Control
    - IoT
    - Property Management
    - smart-locks
    url: /providers/remotelock/
  layer: domain
  name: RemoteLock
  provider: remotelock
  says: lists RemoteLock as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2110
    key: insurance-distribution-management
    name: Insurance Distribution Management
    url: /capabilities/insurance-distribution-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id023
      status: unknown
    slug: safely
    status: profiled
    tags: &id024
    - Company
    - Insurance
    - Insurtech
    - Short-Term Rental
    url: /providers/safely/
  layer: domain
  name: Safely
  provider: safely
  says: lists Safely as an integration
  source: https://www.hostaway.com/marketplace/
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
    mcp: &id025
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id026
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4060.20
    key: housekeeping-operations
    name: Housekeeping Operations
    url: /capabilities/housekeeping-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id027
      status: unchecked
    slug: turno
    status: queued for profiling
    tags: &id028 []
    url: null
  layer: domain
  name: Turno
  provider: turno
  says: lists Turno as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id029
      status: unchecked
    slug: vrbo
    status: profiled
    tags: &id030
    - Company
    url: /providers/vrbo/
  layer: domain
  name: Vrbo
  provider: vrbo
  says: lists Vrbo as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440
    key: pricing-management
    name: Pricing Management
    url: /capabilities/pricing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: wheelhouse
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: domain
  name: Wheelhouse
  provider: wheelhouse
  says: lists Wheelhouse as an integration
  source: https://www.hostaway.com/marketplace/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id033
      status: unknown
    slug: ximplifi
    status: profiled
    tags: &id034
    - Accounting
    - Property Management
    - Software-as-a-Service
    - Vacation Rentals
    url: /providers/ximplifi/
  layer: domain
  name: Ximplifi
  provider: ximplifi
  says: lists Ximplifi as an integration
  source: https://www.hostaway.com/marketplace/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/property-management/hostaway/
providers:
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id001
  name: Airbnb
  slug: airbnb
  status: profiled
  tags: *id002
  url: /providers/airbnb/
- agent_band: agent-ready
  agent_readiness: 46.2
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id003
  name: Beyond
  slug: beyond-pricing
  status: profiled
  tags: *id004
  url: /providers/beyond-pricing/
- agent_band: agent-ready
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id005
  name: Booking.com
  slug: booking-com
  status: profiled
  tags: *id006
  url: /providers/booking-com/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id007
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id008
  url: /providers/braintree/
- agent_band: agent-aware
  agent_readiness: 19.4
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id009
  name: Breezeway
  slug: breezeway
  status: profiled
  tags: *id010
  url: /providers/breezeway/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id011
  name: ChargeAutomation
  slug: chargeautomation
  status: profiled
  tags: *id012
  url: /providers/chargeautomation/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id013
  name: Expedia
  slug: expedia-group
  status: profiled
  tags: *id014
  url: /providers/expedia-group/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id015
  name: Google Vacation Rentals
  slug: google
  status: profiled
  tags: *id016
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id017
  name: Operto
  slug: operto
  status: profiled
  tags: *id018
  url: /providers/operto/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: PriceLabs
  slug: pricelabs
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-aware
  agent_readiness: 25.0
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id021
  name: RemoteLock
  slug: remotelock
  status: profiled
  tags: *id022
  url: /providers/remotelock/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id023
  name: Safely
  slug: safely
  status: profiled
  tags: *id024
  url: /providers/safely/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id025
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id026
  url: /providers/stripe/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id027
  name: Turno
  slug: turno
  status: queued for profiling
  tags: *id028
  url: null
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id029
  name: Vrbo
  slug: vrbo
  status: profiled
  tags: *id030
  url: /providers/vrbo/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: Wheelhouse
  slug: wheelhouse
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id033
  name: Ximplifi
  slug: ximplifi
  status: profiled
  tags: *id034
  url: /providers/ximplifi/
siblings:
- name: AppFolio
  rows: 6
  url: /applications/property-management/appfolio/
- name: Buildium
  rows: 15
  url: /applications/property-management/buildium/
- name: DoorLoop
  rows: 15
  url: /applications/property-management/doorloop/
- name: Guesty
  rows: 12
  url: /applications/property-management/guesty/
- name: Open Condo
  rows: 18
  url: /applications/property-management/open-condo/
sitemap: true
title: 'Hostaway: Property & Rental Management reference app'
---
