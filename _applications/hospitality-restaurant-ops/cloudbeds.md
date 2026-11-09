---
app: Cloudbeds
app_slug: cloudbeds
app_url: https://www.cloudbeds.com/
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
  url: /capabilities/channel-manager-operations/
  via_parent: null
category:
  id: hospitality-restaurant-ops
  name: Hotel & Restaurant Operations
  url: /applications/hospitality-restaurant-ops/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.cloudbeds.com/integrations/
- route: integrations page
  url: https://www.cloudbeds.com/marketplace/
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
    agent_readiness: 31.1
    band: developing
    in_catalog: true
    kin_score: 44.8
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
  source: https://www.cloudbeds.com/marketplace/
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
    agent_readiness: 45.8
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id003
      status: none
    slug: booking-com
    status: profiled
    tags: &id004
    - Accommodation
    - Booking
    - Hospitality
    - Travel
    url: /providers/booking-com/
  layer: domain
  name: Booking.com
  provider: booking-com
  says: lists Booking.com as an integration
  source: https://www.cloudbeds.com/marketplace/
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
    agent_readiness: 30.8
    band: thin
    in_catalog: true
    kin_score: 34.8
    mcp: &id005
      source: https://github.com/ExpediaGroup/expedia-travel-recommendations-mcp
      status: verified
    slug: expedia-group
    status: profiled
    tags: &id006
    - Flights
    - Hotels
    - Lodging
    - Travel
    url: /providers/expedia-group/
  layer: domain
  name: Expedia
  provider: expedia-group
  says: lists Expedia as an integration
  source: https://www.cloudbeds.com/marketplace/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hospitality-restaurant-ops/cloudbeds/
providers:
- agent_band: agent-ready
  agent_readiness: 31.1
  band: developing
  in_catalog: true
  kin_score: 44.8
  mcp: *id001
  name: Airbnb
  slug: airbnb
  status: profiled
  tags: *id002
  url: /providers/airbnb/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id003
  name: Booking.com
  slug: booking-com
  status: profiled
  tags: *id004
  url: /providers/booking-com/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: thin
  in_catalog: true
  kin_score: 34.8
  mcp: *id005
  name: Expedia
  slug: expedia-group
  status: profiled
  tags: *id006
  url: /providers/expedia-group/
siblings:
- name: 7shifts
  rows: 12
  url: /applications/hospitality-restaurant-ops/7shifts/
- name: apaleo
  rows: 5
  url: /applications/hospitality-restaurant-ops/apaleo/
- name: MarketMan
  rows: 31
  url: /applications/hospitality-restaurant-ops/marketman/
- name: Mews
  rows: 11
  url: /applications/hospitality-restaurant-ops/mews/
- name: QloApps
  rows: 3
  url: /applications/hospitality-restaurant-ops/qloapps/
- name: TastyIgniter
  rows: 11
  url: /applications/hospitality-restaurant-ops/tastyigniter/
sitemap: true
title: 'Cloudbeds: Hotel & Restaurant Operations reference app'
---
