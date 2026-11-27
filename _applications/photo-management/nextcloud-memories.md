---
app: Nextcloud Memories
app_slug: nextcloud-memories
app_url: https://github.com/pulsejet/memories
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
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/pulsejet/memories/blob/master/composer.json
- route: dependency manifest
  url: https://github.com/pulsejet/memories/blob/master/package.json
integrations:
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
    mcp: &id001
      status: none
    slug: nextcloud
    status: profiled
    tags: &id002
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: nextcloud
  provider: nextcloud
  says: ships the nextcloud SDK or integration code
  source: https://github.com/pulsejet/memories/blob/master/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/nextcloud-memories/
providers:
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id001
  name: nextcloud
  slug: nextcloud
  status: profiled
  tags: *id002
  url: /providers/nextcloud/
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
- name: PhotoPrism
  rows: 1
  url: /applications/photo-management/photoprism/
- name: Piwigo
  rows: 0
  url: /applications/photo-management/piwigo/
sitemap: true
title: 'Nextcloud Memories: Photo & Video Library Management reference app'
---
