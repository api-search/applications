---
app: Cloudbeds
app_slug: cloudbeds
app_url: https://www.cloudbeds.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - Reputize
  - TrustYou
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - CartStack
  - The Hotels Network
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.30.10
  key: AE-160.30.10
  layer: domain
  name: Document Verification
  providers:
  - Chekin
  url: /capabilities/identity-verification/
  via_parent: Identity Verification
- attribution: API Evangelist extension
  id: AE-210.30
  key: ground-transport
  layer: domain
  name: Ground Transport
  providers:
  - Welcome PickUps
  url: /capabilities/ground-transport/
  via_parent: null
- attribution: Turbo EA
  id: BC-4060.20
  key: housekeeping-operations
  layer: domain
  name: Housekeeping Operations
  providers:
  - Flexkeeping
  url: /capabilities/housekeeping-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.30
  key: AE-160.30
  layer: domain
  name: Identity Verification
  providers:
  - Autohost
  url: /capabilities/identity-verification/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.90
  key: AE-200.90
  layer: domain
  name: Physical Access Control & Mobile Keys
  providers:
  - 4SUITES
  - FLEXIPASS
  url: /capabilities/physical-access-control-mobile-keys/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Lightspeed
  - Poster POS
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4060.10.30
  key: BC-4060.10.30
  layer: domain
  name: Room Assignment & Upgrade
  providers:
  - UpsellGuru
  url: /capabilities/front-office-operations/
  via_parent: Front Office Operations
- attribution: Turbo EA
  id: BC-4010
  key: travel-distribution-channel-management
  layer: domain
  name: Travel Distribution & Channel Management
  providers:
  - Airbnb
  - Booking.com
  - Expedia
  url: /capabilities/travel-distribution-channel-management/
  via_parent: null
category:
  id: hotel-pms
  name: Hotel Property Management
  url: /applications/hotel-pms/
counts:
  declared: 16
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
- route: integrations page
  url: https://myfrontdesk.cloudbeds.com/hc/en-us/articles/360003183494-Apps-integrated-with-myfrontdesk
- route: integrations page
  url: https://www.cloudbeds.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
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
    slug: 4suites
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: 4SUITES
  provider: 4suites
  says: lists 4SUITES as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id003
      status: none
    slug: airbnb
    status: profiled
    tags: &id004
    - Airbnb
    - Hospitality
    - Reservations
    - Travel
    url: /providers/airbnb/
  layer: domain
  name: Airbnb
  provider: airbnb
  says: lists Airbnb as an integration
  source: https://www.cloudbeds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 42.0
    mcp: &id005
      source: https://docs.autohost.ai/docs/remote-mcp-server
      status: verified
    slug: autohost
    status: profiled
    tags: &id006
    - Background Checks
    - Company
    - Fraud Prevention
    - Identity Verification
    url: /providers/autohost/
  layer: domain
  name: Autohost
  provider: autohost
  says: lists Autohost as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id007
      status: none
    slug: booking-com
    status: profiled
    tags: &id008
    - Accommodation
    - Booking
    - Hospitality
    - Travel
    url: /providers/booking-com/
  layer: domain
  name: Booking.com
  provider: booking-com
  says: lists Booking.com as an integration
  source: https://www.cloudbeds.com/integrations/
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
    agent_readiness: 10.6
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id009
      status: unchecked
    slug: cartstack
    status: profiled
    tags: &id010
    - Cart Recovery
    - Company
    - E-Commerce
    - Software-as-a-Service
    url: /providers/cartstack/
  layer: domain
  name: CartStack
  provider: cartstack
  says: lists CartStack as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.10
    key: AE-160.30.10
    name: Document Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 22.0
    mcp: &id011
      status: unknown
    slug: chekin
    status: profiled
    tags: &id012
    - Check-in
    - Compliance
    - Hospitality
    - SDK
    url: /providers/chekin/
  layer: domain
  name: Chekin
  provider: chekin
  says: lists Chekin as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
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
  source: https://www.cloudbeds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: flexipass
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: FLEXIPASS
  provider: flexipass
  says: lists FLEXIPASS as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id017
      status: unknown
    slug: flexkeeping
    status: profiled
    tags: &id018
    - Company
    - Hospitality
    - Hotel Operations
    - Hotels
    url: /providers/flexkeeping/
  layer: domain
  name: Flexkeeping
  provider: flexkeeping
  says: lists Flexkeeping as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
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
    mcp: &id019
      status: none
    slug: lightspeed
    status: profiled
    tags: &id020
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: poster
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Poster POS
  provider: poster
  says: lists Poster POS as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id023
      status: unchecked
    slug: reputize
    status: profiled
    tags: &id024
    - Analytics
    - Company
    - Hotels
    - Reputation Management
    url: /providers/reputize/
  layer: domain
  name: Reputize
  provider: reputize
  says: lists Reputize as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
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
    agent_band: human-only
    agent_readiness: 3.2
    band: emerging
    in_catalog: true
    kin_score: 24.5
    mcp: &id025
      status: unchecked
    slug: the-hotels-network
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Direct Booking
    - Hospitality
    - HotelTech
    url: /providers/the-hotels-network/
  layer: domain
  name: The Hotels Network
  provider: the-hotels-network
  says: lists The Hotels Network as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id027
      status: unchecked
    slug: trustyou
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Data Analytics
    - Guest Experience
    - Hospitality
    url: /providers/trustyou/
  layer: domain
  name: TrustYou
  provider: trustyou
  says: lists TrustYou as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4060.10.30
    key: BC-4060.10.30
    name: Room Assignment & Upgrade
    url: /capabilities/front-office-operations/
    via_parent: Front Office Operations
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: developing
    in_catalog: true
    kin_score: 42.1
    mcp: &id029
      status: unchecked
    slug: upsellguru
    status: profiled
    tags: &id030
    - Company
    - Hospitality
    - Revenue
    - Software-as-a-Service
    url: /providers/upsellguru/
  layer: domain
  name: UpsellGuru
  provider: upsellguru
  says: lists UpsellGuru as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30
    key: ground-transport
    name: Ground Transport
    url: /capabilities/ground-transport/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id031
      status: unchecked
    slug: welcome-pickups
    status: profiled
    tags: &id032
    - Booking
    - Tours
    - Transfers
    - Travel
    url: /providers/welcome-pickups/
  layer: domain
  name: Welcome PickUps
  provider: welcome-pickups
  says: lists Welcome PickUps as an integration
  source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hotel-pms/cloudbeds/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: 4SUITES
  slug: 4suites
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id003
  name: Airbnb
  slug: airbnb
  status: profiled
  tags: *id004
  url: /providers/airbnb/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 42.0
  mcp: *id005
  name: Autohost
  slug: autohost
  status: profiled
  tags: *id006
  url: /providers/autohost/
- agent_band: agent-ready
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id007
  name: Booking.com
  slug: booking-com
  status: profiled
  tags: *id008
  url: /providers/booking-com/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id009
  name: CartStack
  slug: cartstack
  status: profiled
  tags: *id010
  url: /providers/cartstack/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 22.0
  mcp: *id011
  name: Chekin
  slug: chekin
  status: profiled
  tags: *id012
  url: /providers/chekin/
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
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: FLEXIPASS
  slug: flexipass
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id017
  name: Flexkeeping
  slug: flexkeeping
  status: profiled
  tags: *id018
  url: /providers/flexkeeping/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id019
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id020
  url: /providers/lightspeed/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Poster POS
  slug: poster
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id023
  name: Reputize
  slug: reputize
  status: profiled
  tags: *id024
  url: /providers/reputize/
- agent_band: human-only
  agent_readiness: 3.2
  band: emerging
  in_catalog: true
  kin_score: 24.5
  mcp: *id025
  name: The Hotels Network
  slug: the-hotels-network
  status: profiled
  tags: *id026
  url: /providers/the-hotels-network/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id027
  name: TrustYou
  slug: trustyou
  status: profiled
  tags: *id028
  url: /providers/trustyou/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: developing
  in_catalog: true
  kin_score: 42.1
  mcp: *id029
  name: UpsellGuru
  slug: upsellguru
  status: profiled
  tags: *id030
  url: /providers/upsellguru/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id031
  name: Welcome PickUps
  slug: welcome-pickups
  status: profiled
  tags: *id032
  url: /providers/welcome-pickups/
siblings:
- name: apaleo
  rows: 8
  url: /applications/hotel-pms/apaleo/
- name: Beds24
  rows: 12
  url: /applications/hotel-pms/beds24/
- name: Hotelogix
  rows: 32
  url: /applications/hotel-pms/hotelogix/
- name: Mews
  rows: 13
  url: /applications/hotel-pms/mews/
- name: QloApps
  rows: 3
  url: /applications/hotel-pms/qloapps/
sitemap: true
title: 'Cloudbeds: Hotel Property Management reference app'
---
