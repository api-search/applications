---
app: PhotoPrism
app_slug: photoprism
app_url: https://github.com/photoprism/photoprism
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20
  key: AE-120.20
  layer: domain
  name: Maps & Tiles
  providers:
  - maptiler
  url: /capabilities/maps-tiles/
  via_parent: null
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 1
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/photoprism/photoprism/blob/develop/frontend/package.json
- route: dependency manifest
  url: https://github.com/photoprism/photoprism/blob/develop/go.mod
- route: documentation
  url: https://docs.photoprism.app/getting-started/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id001
      status: none
    slug: maptiler
    status: profiled
    tags: &id002
    - Geospatial
    - Maps
    - Tiles
    - Vector Tiles
    url: /providers/maptiler/
  layer: domain
  name: maptiler
  provider: maptiler
  says: lists maptiler as an integration
  source: https://docs.photoprism.app/getting-started/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/photoprism/
providers:
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id001
  name: maptiler
  slug: maptiler
  status: profiled
  tags: *id002
  url: /providers/maptiler/
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
- name: LibrePhotos
  rows: 6
  url: /applications/photo-management/librephotos/
- name: Lychee
  rows: 19
  url: /applications/photo-management/lychee/
- name: Nextcloud Memories
  rows: 1
  url: /applications/photo-management/nextcloud-memories/
- name: Piwigo
  rows: 0
  url: /applications/photo-management/piwigo/
sitemap: true
title: 'PhotoPrism: Photo & Video Library Management reference app'
---
