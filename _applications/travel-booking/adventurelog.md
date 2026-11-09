---
app: AdventureLog
app_slug: adventurelog
app_url: https://github.com/seanmorley15/AdventureLog
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30.20
  key: AE-170.30.20
  layer: domain
  name: Photo Sharing
  providers:
  - Immich
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-120.40.20
  key: AE-120.40.20
  layer: domain
  name: Place Content & Descriptions
  providers:
  - Wikipedia
  url: /capabilities/places-points-of-interest/
  via_parent: Places & Points of Interest
- attribution: API Evangelist extension
  id: AE-120.40.10
  key: AE-120.40.10
  layer: domain
  name: Place Search
  providers:
  - Google Places (New)
  - Overpass API
  url: /capabilities/places-points-of-interest/
  via_parent: Places & Points of Interest
- attribution: API Evangelist extension
  id: AE-130.10.30
  key: AE-130.10.30
  layer: domain
  name: Running & Cycling Tracking
  providers:
  - Endurain
  - Strava
  - wanderer
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-120.10
  key: AE-120.10
  layer: common
  name: Geocoding
  providers:
  - Google Maps Geocoding
  url: /capabilities/geocoding/
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Umami
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: common
  name: Reverse Geocoding
  providers:
  - Nominatim (OSM)
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - Authentik
  - Pocket ID
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: travel-booking
  name: Travel Booking & Trip Planning
  url: /applications/travel-booking/
counts:
  declared: 3
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/requirements.txt
- route: documentation
  url: https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/analytics.md
- route: documentation
  url: https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/google_maps_integration.md
- route: documentation
  url: https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
- route: source code
  url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/google.py
- route: source code
  url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/osm.py
- route: source code
  url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/places/wikipedia.py
- route: source code
  url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/osm.py
- route: source code
  url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/main/settings.py
- route: source code
  url: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id003
      status: none
    slug: endurain
    status: profiled
    tags: &id004
    - Company
    - Fitness
    - Open Source
    - Self-Hosted
    url: /providers/endurain/
  layer: domain
  name: Endurain
  provider: endurain
  says: ships the Endurain SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/main/settings.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id007
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id008
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Geocoding
  provider: google-maps
  says: ships the Google Maps Geocoding SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/google.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id009
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-places
    status: profiled
    tags: &id010
    - Geolocation
    - Google
    - Location
    - Restaurant
    url: /providers/google-places/
  layer: domain
  name: Google Places (New)
  provider: google-places
  says: ships the Google Places (New) SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/google.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.20
    key: AE-170.30.20
    name: Photo Sharing
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id011
      status: none
    slug: immich
    status: profiled
    tags: &id012
    - Photo Management
    - Privacy
    - Self-Hosted
    - Video Management
    url: /providers/immich/
  layer: domain
  name: Immich
  provider: immich
  says: ships the Immich SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id013
      status: none
    slug: nominatim
    status: profiled
    tags: &id014
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim (OSM)
  provider: nominatim
  says: ships the Nominatim (OSM) SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/osm.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id015
      status: unknown
    slug: overpass-api
    status: profiled
    tags: &id016
    - GIS
    - Geographic
    - OpenStreetMap
    - Spatial
    url: /providers/overpass-api/
  layer: domain
  name: Overpass API
  provider: overpass-api
  says: ships the Overpass API SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/osm.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id019
      status: none
    slug: strava
    status: profiled
    tags: &id020
    - Cycling
    - Fitness
    - Fitness Tracking
    - Running
    url: /providers/strava/
  layer: domain
  name: Strava
  provider: strava
  says: ships the Strava SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
  tier: observed
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id021
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id022
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id025
      status: unknown
    slug: wanderer
    status: profiled
    tags: &id026
    - Company
    url: /providers/wanderer/
  layer: domain
  name: wanderer
  provider: wanderer
  says: ships the wanderer SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.20
    key: AE-120.40.20
    name: Place Content & Descriptions
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id027
      status: none
    slug: wikipedia
    status: profiled
    tags: &id028
    - Encyclopedia
    - Open Data
    - Open Knowledge
    - Public APIs
    url: /providers/wikipedia/
  layer: domain
  name: Wikipedia
  provider: wikipedia
  says: ships the Wikipedia SDK or integration code
  source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/places/wikipedia.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.2
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id001
      status: none
    slug: authentik
    status: profiled
    tags: &id002
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
  layer: common
  name: Authentik
  provider: authentik
  says: lists Authentik as an integration
  source: https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: emerging
    in_catalog: true
    kin_score: 19.1
    mcp: &id017
      status: none
    slug: pocket-id
    status: profiled
    tags: &id018
    - Company
    - Identity
    - OAuth
    - OpenID Connect
    url: /providers/pocket-id/
  layer: common
  name: Pocket ID
  provider: pocket-id
  says: lists Pocket ID as an integration
  source: https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.4
    band: exemplar
    in_catalog: true
    kin_score: 73.3
    mcp: &id023
      status: none
    slug: umami
    status: profiled
    tags: &id024
    - Cookieless Tracking
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/umami/
  layer: common
  name: Umami
  provider: umami
  says: lists Umami as an integration
  source: https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/analytics.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/travel-booking/adventurelog/
providers:
- agent_band: agent-ready
  agent_readiness: 33.2
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id001
  name: Authentik
  slug: authentik
  status: profiled
  tags: *id002
  url: /providers/authentik/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id003
  name: Endurain
  slug: endurain
  status: profiled
  tags: *id004
  url: /providers/endurain/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id005
  name: GitHub
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id007
  name: Google Maps Geocoding
  slug: google-maps
  status: profiled
  tags: *id008
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id009
  name: Google Places (New)
  slug: google-places
  status: profiled
  tags: *id010
  url: /providers/google-places/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id011
  name: Immich
  slug: immich
  status: profiled
  tags: *id012
  url: /providers/immich/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id013
  name: Nominatim (OSM)
  slug: nominatim
  status: profiled
  tags: *id014
  url: /providers/nominatim/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id015
  name: Overpass API
  slug: overpass-api
  status: profiled
  tags: *id016
  url: /providers/overpass-api/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: emerging
  in_catalog: true
  kin_score: 19.1
  mcp: *id017
  name: Pocket ID
  slug: pocket-id
  status: profiled
  tags: *id018
  url: /providers/pocket-id/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id019
  name: Strava
  slug: strava
  status: profiled
  tags: *id020
  url: /providers/strava/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id021
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id022
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: exemplar
  in_catalog: true
  kin_score: 73.3
  mcp: *id023
  name: Umami
  slug: umami
  status: profiled
  tags: *id024
  url: /providers/umami/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id025
  name: wanderer
  slug: wanderer
  status: profiled
  tags: *id026
  url: /providers/wanderer/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id027
  name: Wikipedia
  slug: wikipedia
  status: profiled
  tags: *id028
  url: /providers/wikipedia/
siblings:
- name: Airbnb
  rows: 4
  url: /applications/travel-booking/airbnb/
- name: Booking.com
  rows: 5
  url: /applications/travel-booking/booking-com/
- name: Expedia
  rows: 7
  url: /applications/travel-booking/expedia/
- name: TRIP
  rows: 6
  url: /applications/travel-booking/trip/
- name: TripIt
  rows: 4
  url: /applications/travel-booking/tripit/
sitemap: true
title: 'AdventureLog: Travel Booking & Trip Planning reference app'
---
