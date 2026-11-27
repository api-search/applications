---
app: Mixpost
app_slug: mixpost
app_url: https://github.com/inovector/mixpost
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Tenor
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Facebook
  - Mastodon
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
category:
  id: social-media-management
  name: Social Media Management & Scheduling
  url: /applications/social-media-management/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/inovector/mixpost/main/composer.json
- route: source code
  url: https://github.com/inovector/mixpost/tree/main/src/Services
- route: source code
  url: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id003
      status: none
    slug: mastodon
    status: profiled
    tags: &id004
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
  layer: domain
  name: Mastodon
  provider: mastodon
  says: ships the Mastodon SDK or integration code
  source: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 49.2
    mcp: &id005
      status: none
    slug: tenor
    status: profiled
    tags: &id006
    - Animated Images
    - GIFs
    - Media
    - Search
    url: /providers/tenor/
  layer: domain
  name: Tenor
  provider: tenor
  says: ships the Tenor SDK or integration code
  source: https://github.com/inovector/mixpost/tree/main/src/Services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id007
      status: none
    slug: unsplash
    status: profiled
    tags: &id008
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: domain
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://github.com/inovector/mixpost/tree/main/src/Services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id009
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id010
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-media-management/mixpost/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id003
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id004
  url: /providers/mastodon/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 49.2
  mcp: *id005
  name: Tenor
  slug: tenor
  status: profiled
  tags: *id006
  url: /providers/tenor/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id007
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id008
  url: /providers/unsplash/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id009
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id010
  url: /providers/x/
siblings:
- name: Buffer
  rows: 39
  url: /applications/social-media-management/buffer/
- name: Hootsuite
  rows: 42
  url: /applications/social-media-management/hootsuite/
- name: Planoly
  rows: 8
  url: /applications/social-media-management/planoly/
- name: Postiz
  rows: 57
  url: /applications/social-media-management/postiz/
- name: Socioboard
  rows: 22
  url: /applications/social-media-management/socioboard/
- name: Sprout Social
  rows: 43
  url: /applications/social-media-management/sprout-social/
sitemap: true
title: 'Mixpost: Social Media Management & Scheduling reference app'
---
