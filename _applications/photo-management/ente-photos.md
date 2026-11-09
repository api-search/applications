---
app: Ente Photos
app_slug: ente-photos
app_url: https://github.com/ente-io/ente
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - firebase
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510.40
  key: exception-and-alert-management
  layer: common
  name: Exception and Alert Management
  providers:
  - discord
  url: /capabilities/exception-and-alert-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - backblaze
  - wasabi
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-3750.20
  key: subscription-entitlement-management
  layer: common
  name: Subscription & Entitlement Management
  providers:
  - apple
  - google-play
  url: /capabilities/subscription-entitlement-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - stripe
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 3
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ente-io/ente/blob/main/server/go.mod
- route: dependency manifest
  url: https://github.com/ente-io/ente/blob/main/web/packages/base/package.json
- route: source code
  url: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: apple
  provider: apple
  says: ships the apple SDK or integration code
  source: https://github.com/ente-io/ente/blob/main/server/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2510.40
    key: exception-and-alert-management
    name: Exception and Alert Management
    url: /capabilities/exception-and-alert-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id005
      status: none
    slug: discord
    status: profiled
    tags: &id006
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: discord
  provider: discord
  says: ships the discord SDK or integration code
  source: https://github.com/ente-io/ente/blob/main/server/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id009
      status: none
    slug: google-play
    status: profiled
    tags: &id010
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: google-play
  provider: google-play
  says: ships the google-play SDK or integration code
  source: https://github.com/ente-io/ente/blob/main/server/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id011
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id012
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: stripe
  provider: stripe
  says: ships the stripe SDK or integration code
  source: https://github.com/ente-io/ente/blob/main/server/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id003
      source: https://github.com/backblaze-labs/b2-mcp
      status: verified
    slug: backblaze
    status: profiled
    tags: &id004
    - Backup
    - Cloud Storage
    - Object Storage
    - Storage
    url: /providers/backblaze/
  layer: common
  name: backblaze
  provider: backblaze
  says: lists backblaze as an integration
  source: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id008
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: firebase
  provider: firebase
  says: lists firebase as an integration
  source: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id013
      status: none
    slug: wasabi
    status: profiled
    tags: &id014
    - Cloud Storage
    - Object Storage
    - REST API
    - S3 Compatible
    url: /providers/wasabi/
  layer: common
  name: wasabi
  provider: wasabi
  says: lists wasabi as an integration
  source: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/ente-photos/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id001
  name: apple
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id003
  name: backblaze
  slug: backblaze
  status: profiled
  tags: *id004
  url: /providers/backblaze/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id005
  name: discord
  slug: discord
  status: profiled
  tags: *id006
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id007
  name: firebase
  slug: firebase
  status: profiled
  tags: *id008
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id009
  name: google-play
  slug: google-play
  status: profiled
  tags: *id010
  url: /providers/google-play/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id011
  name: stripe
  slug: stripe
  status: profiled
  tags: *id012
  url: /providers/stripe/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id013
  name: wasabi
  slug: wasabi
  status: profiled
  tags: *id014
  url: /providers/wasabi/
siblings:
- name: Amazon Photos
  rows: 2
  url: /applications/photo-management/amazon-photos/
- name: Apple Photos
  rows: 0
  url: /applications/photo-management/apple-photos/
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
title: 'Ente Photos: Photo & Video Library Management reference app'
---
