---
app: LibrePhotos
app_slug: librephotos
app_url: https://github.com/LibrePhotos/librephotos
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: domain
  name: Media Asset Management
  providers:
  - nextcloud
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: domain
  name: Reverse Geocoding
  providers:
  - mapbox
  - maptiler
  - nominatim
  - opencage
  - tomtom
  url: /capabilities/geocoding/
  via_parent: Geocoding
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/requirements.txt
- route: source code
  url: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.2
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id001
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id002
    - Geospatial
    - Location
    - Mapping
    - Maps
    url: /providers/mapbox/
  layer: domain
  name: mapbox
  provider: mapbox
  says: ships the mapbox SDK or integration code
  source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id003
      status: none
    slug: maptiler
    status: profiled
    tags: &id004
    - Geospatial
    - Maps
    - Tiles
    - Vector Tiles
    url: /providers/maptiler/
  layer: domain
  name: maptiler
  provider: maptiler
  says: ships the maptiler SDK or integration code
  source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id005
      status: none
    slug: nextcloud
    status: profiled
    tags: &id006
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: nextcloud
  provider: nextcloud
  says: ships the nextcloud SDK or integration code
  source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/requirements.txt
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
  layer: domain
  name: nominatim
  provider: nominatim
  says: ships the nominatim SDK or integration code
  source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
    agent_band: human-only
    agent_readiness: 1.7
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id009
      source: https://github.com/OpenCageData/opencage-geocoding-mcp
      status: verified
    slug: opencage
    status: profiled
    tags: &id010
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/opencage/
  layer: domain
  name: opencage
  provider: opencage
  says: ships the opencage SDK or integration code
  source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
    agent_band: agent-ready
    agent_readiness: 40.9
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id011
      source: https://github.com/tomtom-international/tomtom-mcp
      status: verified
    slug: tomtom
    status: profiled
    tags: &id012
    - Maps
    - Navigation
    - Traffic
    - Transportation
    url: /providers/tomtom/
  layer: domain
  name: tomtom
  provider: tomtom
  says: ships the tomtom SDK or integration code
  source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/librephotos/
providers:
- agent_band: agent-ready
  agent_readiness: 45.2
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id001
  name: mapbox
  slug: mapbox
  status: profiled
  tags: *id002
  url: /providers/mapbox/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id003
  name: maptiler
  slug: maptiler
  status: profiled
  tags: *id004
  url: /providers/maptiler/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id005
  name: nextcloud
  slug: nextcloud
  status: profiled
  tags: *id006
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: nominatim
  slug: nominatim
  status: profiled
  tags: *id008
  url: /providers/nominatim/
- agent_band: human-only
  agent_readiness: 1.7
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id009
  name: opencage
  slug: opencage
  status: profiled
  tags: *id010
  url: /providers/opencage/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id011
  name: tomtom
  slug: tomtom
  status: profiled
  tags: *id012
  url: /providers/tomtom/
siblings:
- name: Amazon Photos
  rows: 2
  url: /applications/photo-management/amazon-photos/
- name: Apple Photos
  rows: 0
  url: /applications/photo-management/apple-photos/
- name: Ente Photos
  rows: 7
  url: /applications/photo-management/ente-photos/
- name: Flickr
  rows: 4
  url: /applications/photo-management/flickr/
- name: Google Photos
  rows: 1
  url: /applications/photo-management/google-photos/
- name: Immich
  rows: 1
  url: /applications/photo-management/immich/
- name: Lychee
  rows: 19
  url: /applications/photo-management/lychee/
- name: Nextcloud Memories
  rows: 1
  url: /applications/photo-management/nextcloud-memories/
- name: PhotoPrism
  rows: 1
  url: /applications/photo-management/photoprism/
- name: Piwigo
  rows: 0
  url: /applications/photo-management/piwigo/
sitemap: true
title: 'LibrePhotos: Photo & Video Library Management reference app'
---
