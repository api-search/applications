---
app: Podverse
app_slug: podverse
app_url: https://github.com/podverse/podverse-api
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.40
  key: AE-170.20.40
  layer: domain
  name: Podcast Directories & Search
  providers:
  - PodcastIndex
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - BitPay
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Matomo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Manticore Search
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - AWS
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: podcasts-audiobooks
  name: Podcasts & Audiobooks
  url: /applications/podcasts-audiobooks/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/podverse/podverse-api/blob/develop/package.json
- route: source code
  url: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
integrations:
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
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS
  provider: amazon-web-services
  says: ships the AWS SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/package.json
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
    agent_band: agent-ready
    agent_readiness: 36.6
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id003
      status: none
    slug: bitpay
    status: profiled
    tags: &id004
    - Bitcoin
    - Blockchain
    - Cryptocurrency
    - Payments
    url: /providers/bitpay/
  layer: common
  name: BitPay
  provider: bitpay
  says: ships the BitPay SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id006
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id007
      source: https://github.com/manticoresoftware/mcp-manticore
      status: verified
    slug: manticore
    status: profiled
    tags: &id008
    - Elasticsearch Compatible
    - Full-Text Search
    - Search
    - Vector Search
    url: /providers/manticore/
  layer: common
  name: Manticore Search
  provider: manticore
  says: ships the Manticore Search SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/package.json
  tier: observed
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
    agent_readiness: 37.4
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id009
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id010
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
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
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id011
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id012
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.40
    key: AE-170.20.40
    name: Podcast Directories & Search
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id013
      status: none
    slug: podcastindex
    status: profiled
    tags: &id014
    - Discovery
    - Open Data
    - Podcast Index
    - Podcasts
    url: /providers/podcastindex/
  layer: domain
  name: PodcastIndex
  provider: podcastindex
  says: ships the PodcastIndex SDK or integration code
  source: https://github.com/podverse/podverse-api/blob/develop/src/config/index.ts
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/podcasts-audiobooks/podverse/
providers:
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id001
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id003
  name: BitPay
  slug: bitpay
  status: profiled
  tags: *id004
  url: /providers/bitpay/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id005
  name: Firebase Cloud Messaging
  slug: firebase
  status: profiled
  tags: *id006
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id007
  name: Manticore Search
  slug: manticore
  status: profiled
  tags: *id008
  url: /providers/manticore/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id009
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id010
  url: /providers/matomo/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id011
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id012
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id013
  name: PodcastIndex
  slug: podcastindex
  status: profiled
  tags: *id014
  url: /providers/podcastindex/
siblings:
- name: AntennaPod
  rows: 6
  url: /applications/podcasts-audiobooks/antennapod/
- name: Audible
  rows: 4
  url: /applications/podcasts-audiobooks/audible/
- name: Audiobookshelf
  rows: 8
  url: /applications/podcasts-audiobooks/audiobookshelf/
- name: Castopod
  rows: 1
  url: /applications/podcasts-audiobooks/castopod/
- name: Pocket Casts
  rows: 5
  url: /applications/podcasts-audiobooks/pocket-casts/
sitemap: true
title: 'Podverse: Podcasts & Audiobooks reference app'
---
