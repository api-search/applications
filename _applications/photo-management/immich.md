---
app: Immich
app_slug: immich
app_url: https://github.com/immich-app/immich
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.40
  key: AE-120.40
  layer: domain
  name: Places & Points of Interest
  providers:
  - geonames
  url: /capabilities/places-points-of-interest/
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
  url: https://github.com/immich-app/immich/blob/main/mobile/pubspec.yaml
- route: dependency manifest
  url: https://github.com/immich-app/immich/blob/main/server/package.json
- route: source code
  url: https://github.com/immich-app/immich/blob/main/docker/example.env
- route: source code
  url: https://github.com/immich-app/immich/blob/main/docs/docs/features/reverse-geocoding.md
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.40
    key: AE-120.40
    name: Places & Points of Interest
    url: /capabilities/places-points-of-interest/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id001
      status: none
    slug: geonames
    status: profiled
    tags: &id002
    - Geocoding
    - Public APIs
    url: /providers/geonames/
  layer: domain
  name: geonames
  provider: geonames
  says: lists geonames as an integration
  source: https://github.com/immich-app/immich/blob/main/docs/docs/features/reverse-geocoding.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/immich/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id001
  name: geonames
  slug: geonames
  status: profiled
  tags: *id002
  url: /providers/geonames/
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
- name: LibrePhotos
  rows: 6
  url: /applications/photo-management/librephotos/
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
title: 'Immich: Photo & Video Library Management reference app'
---
