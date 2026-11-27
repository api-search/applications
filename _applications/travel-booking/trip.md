---
app: TRIP
app_slug: trip
app_url: https://github.com/itskovacs/trip
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.40.10
  key: AE-120.40.10
  layer: domain
  name: Place Search
  providers:
  - Google Places API (New)
  url: /capabilities/places-points-of-interest/
  via_parent: Places & Points of Interest
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - OpenStreetMap tiles
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Nominatim (OSM)
  - Photon (komoot)
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.10
  key: AE-120.10
  layer: common
  name: Geocoding
  providers:
  - Google Geocoding + Routes
  url: /capabilities/geocoding/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.30.10
  key: AE-120.30.10
  layer: common
  name: Turn-by-Turn Directions
  providers:
  - FOSSGIS OSRM routing
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
category:
  id: travel-booking
  name: Travel Booking & Trip Planning
  url: /applications/travel-booking/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/itskovacs/trip/blob/main/backend/trip/requirements.txt
- route: source code
  url: https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
- route: source code
  url: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
- route: source code
  url: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
- route: source code
  url: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/photon.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.0
    mcp: &id001
      status: none
    slug: fossgis
    status: profiled
    tags: &id002
    - GIS
    - Geospatial
    - Open Source
    - Routing
    url: /providers/fossgis/
  layer: common
  name: FOSSGIS OSRM routing
  provider: fossgis
  says: ships the FOSSGIS OSRM routing SDK or integration code
  source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
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
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id003
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id004
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Geocoding + Routes
  provider: google-maps
  says: ships the Google Geocoding + Routes SDK or integration code
  source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
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
    agent_readiness: 40.3
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id005
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-places
    status: profiled
    tags: &id006
    - Geolocation
    - Google
    - Location
    - Restaurant
    url: /providers/google-places/
  layer: domain
  name: Google Places API (New)
  provider: google-places
  says: ships the Google Places API (New) SDK or integration code
  source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id007
      status: none
    slug: nominatim
    status: profiled
    tags: &id008
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim (OSM)
  provider: nominatim
  says: ships the Nominatim (OSM) SDK or integration code
  source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id009
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id010
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: common
  name: OpenStreetMap tiles
  provider: openstreetmap
  says: ships the OpenStreetMap tiles SDK or integration code
  source: https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: komoot
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: common
  name: Photon (komoot)
  provider: komoot
  says: ships the Photon (komoot) SDK or integration code
  source: https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/travel-booking/trip/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.0
  mcp: *id001
  name: FOSSGIS OSRM routing
  slug: fossgis
  status: profiled
  tags: *id002
  url: /providers/fossgis/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id003
  name: Google Geocoding + Routes
  slug: google-maps
  status: profiled
  tags: *id004
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id005
  name: Google Places API (New)
  slug: google-places
  status: profiled
  tags: *id006
  url: /providers/google-places/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: Nominatim (OSM)
  slug: nominatim
  status: profiled
  tags: *id008
  url: /providers/nominatim/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id009
  name: OpenStreetMap tiles
  slug: openstreetmap
  status: profiled
  tags: *id010
  url: /providers/openstreetmap/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Photon (komoot)
  slug: komoot
  status: queued for profiling
  tags: *id012
  url: null
siblings:
- name: AdventureLog
  rows: 14
  url: /applications/travel-booking/adventurelog/
- name: Airbnb
  rows: 4
  url: /applications/travel-booking/airbnb/
- name: Booking.com
  rows: 5
  url: /applications/travel-booking/booking-com/
- name: Expedia
  rows: 7
  url: /applications/travel-booking/expedia/
- name: TripIt
  rows: 4
  url: /applications/travel-booking/tripit/
sitemap: true
title: 'TRIP: Travel Booking & Trip Planning reference app'
---
