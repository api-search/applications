---
app: MOTIS (Transitous)
app_slug: motis-transitous
app_url: https://github.com/motis-project/motis
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120
  key: location-mapping
  layer: domain
  name: Location & Mapping
  providers:
  - OpenStreetMap
  url: /capabilities/location-mapping/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.30.50
  key: AE-210.30.50
  layer: domain
  name: Micromobility & Bike Share
  providers:
  - BIXI Montreal
  - MobiData BW
  - nextbike
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-210.30.40
  key: AE-210.30.40
  layer: domain
  name: Public Transit Data
  providers:
  - Deutsche Bahn (FaSta)
  - opentransportdata.swiss
  - OVapi
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
category:
  id: public-transit
  name: Public Transit
  url: /applications/public-transit/
counts:
  declared: 6
  observed: 1
credits: []
evidence:
- route: documentation
  url: https://github.com/motis-project/motis/blob/master/docs/setup.md
- route: source code
  url: https://github.com/motis-project/motis/tree/master/src/elevators
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id003
      status: unknown
    slug: deutsche-bahn
    status: profiled
    tags: &id004
    - Company
    - Railways
    - Transportation
    - Travel
    url: /providers/deutsche-bahn/
  layer: domain
  name: Deutsche Bahn (FaSta)
  provider: deutsche-bahn
  says: ships the Deutsche Bahn (FaSta) SDK or integration code
  source: https://github.com/motis-project/motis/tree/master/src/elevators
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.3
    mcp: &id001
      status: unchecked
    slug: bixi
    status: profiled
    tags: &id002
    - Company
    url: /providers/bixi/
  layer: domain
  name: BIXI Montreal
  provider: bixi
  says: lists BIXI Montreal as an integration
  source: https://github.com/motis-project/motis/blob/master/docs/setup.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id005
      status: unchecked
    slug: mobidata-bw
    status: profiled
    tags: &id006
    - Company
    - Mobility
    - Open Data
    - Transportation
    url: /providers/mobidata-bw/
  layer: domain
  name: MobiData BW
  provider: mobidata-bw
  says: lists MobiData BW as an integration
  source: https://github.com/motis-project/motis/blob/master/docs/setup.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id007
      status: none
    slug: nextbike
    status: profiled
    tags: &id008
    - Bike Sharing
    - Europe
    - Mobility
    - Transportation
    url: /providers/nextbike/
  layer: domain
  name: nextbike
  provider: nextbike
  says: lists nextbike as an integration
  source: https://github.com/motis-project/motis/blob/master/docs/setup.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: location-mapping
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
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
  layer: domain
  name: OpenStreetMap
  provider: openstreetmap
  says: lists OpenStreetMap as an integration
  source: https://github.com/motis-project/motis/blob/master/docs/setup.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: opentransportdata-swiss
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: opentransportdata.swiss
  provider: opentransportdata-swiss
  says: lists opentransportdata.swiss as an integration
  source: https://github.com/motis-project/motis/blob/master/docs/setup.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id013
      status: unchecked
    slug: ovapi
    status: profiled
    tags: &id014
    - Company
    - GTFS
    - Public Data
    - Transportation
    url: /providers/ovapi/
  layer: domain
  name: OVapi
  provider: ovapi
  says: lists OVapi as an integration
  source: https://github.com/motis-project/motis/blob/master/docs/setup.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/public-transit/motis-transitous/
providers:
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.3
  mcp: *id001
  name: BIXI Montreal
  slug: bixi
  status: profiled
  tags: *id002
  url: /providers/bixi/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id003
  name: Deutsche Bahn (FaSta)
  slug: deutsche-bahn
  status: profiled
  tags: *id004
  url: /providers/deutsche-bahn/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id005
  name: MobiData BW
  slug: mobidata-bw
  status: profiled
  tags: *id006
  url: /providers/mobidata-bw/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id007
  name: nextbike
  slug: nextbike
  status: profiled
  tags: *id008
  url: /providers/nextbike/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id009
  name: OpenStreetMap
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
  name: opentransportdata.swiss
  slug: opentransportdata-swiss
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id013
  name: OVapi
  slug: ovapi
  status: profiled
  tags: *id014
  url: /providers/ovapi/
siblings:
- name: Citymapper
  rows: 23
  url: /applications/public-transit/citymapper/
- name: Moovit
  rows: 17
  url: /applications/public-transit/moovit/
- name: OneBusAway Android
  rows: 8
  url: /applications/public-transit/onebusaway-android/
- name: OpenTripPlanner
  rows: 9
  url: /applications/public-transit/opentripplanner/
- name: Transit
  rows: 9
  url: /applications/public-transit/transit/
sitemap: true
title: 'MOTIS (Transitous): Public Transit reference app'
---
