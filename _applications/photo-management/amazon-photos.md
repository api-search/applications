---
app: Amazon Photos
app_slug: amazon-photos
app_url: https://www.amazon.com/photos
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - moengage
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.10
  key: product-telemetry-instrumentation
  layer: common
  name: Product Telemetry Instrumentation
  providers:
  - branch-io
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: null
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.10
    key: product-telemetry-instrumentation
    name: Product Telemetry Instrumentation
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id001
      status: none
    slug: branch-io
    status: profiled
    tags: &id002
    - Company
    url: /providers/branch-io/
  layer: common
  name: branch-io
  provider: branch-io
  says: ships the branch-io SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-native
    agent_readiness: 65.1
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id003
      status: none
    slug: moengage
    status: profiled
    tags: &id004
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
  layer: common
  name: moengage
  provider: moengage
  says: ships the moengage SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/amazon-photos/
providers:
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id001
  name: branch-io
  slug: branch-io
  status: profiled
  tags: *id002
  url: /providers/branch-io/
- agent_band: agent-native
  agent_readiness: 65.1
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id003
  name: moengage
  slug: moengage
  status: profiled
  tags: *id004
  url: /providers/moengage/
siblings:
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
- name: PhotoPrism
  rows: 1
  url: /applications/photo-management/photoprism/
- name: Piwigo
  rows: 0
  url: /applications/photo-management/piwigo/
sitemap: true
title: 'Amazon Photos: Photo & Video Library Management reference app'
---
