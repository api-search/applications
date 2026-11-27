---
app: FreshRSS
app_slug: freshrss
app_url: https://github.com/FreshRSS/FreshRSS
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - LinkAce
  - linkding
  - Nextcloud Bookmarks
  - Omnivore
  - Pinboard
  - Raindrop.io
  - Shaarli
  - Wallabag
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Bluesky
  - Buffer
  - diaspora*
  - Facebook
  - Lemmy
  - LinkedIn
  - Mastodon
  - Pinterest
  - Reddit
  - X (Twitter)
  - XING
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Telegram
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 0
  observed: 21
credits: []
evidence:
- route: source code
  url: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id001
      status: none
    slug: bluesky
    status: profiled
    tags: &id002
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: domain
  name: Bluesky
  provider: bluesky
  says: ships the Bluesky SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_band: agent-ready
    agent_readiness: 43.2
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id003
      status: none
    slug: buffer
    status: profiled
    tags: &id004
    - Analytics
    - Publishing
    - Scheduling
    - Social Media
    url: /providers/buffer/
  layer: domain
  name: Buffer
  provider: buffer
  says: ships the Buffer SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 44.2
    mcp: &id005
      status: none
    slug: diaspora
    status: profiled
    tags: &id006
    - Company
    - Decentralized
    - Social
    - Social Network
    url: /providers/diaspora/
  layer: domain
  name: diaspora*
  provider: diaspora
  says: ships the diaspora* SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_readiness: 20.4
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id009
      status: none
    slug: lemmy
    status: profiled
    tags: &id010
    - Community
    - Federated
    - Fediverse
    - Link Aggregator
    url: /providers/lemmy/
  layer: domain
  name: Lemmy
  provider: lemmy
  says: ships the Lemmy SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.1
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id011
      status: none
    slug: linkace
    status: profiled
    tags: &id012
    - Bookmarking
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkace/
  layer: domain
  name: LinkAce
  provider: linkace
  says: ships the LinkAce SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id013
      status: none
    slug: linkding
    status: profiled
    tags: &id014
    - Bookmark
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkding/
  layer: domain
  name: linkding
  provider: linkding
  says: ships the linkding SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id015
      status: none
    slug: linkedin
    status: profiled
    tags: &id016
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    mcp: &id017
      status: none
    slug: mastodon
    status: profiled
    tags: &id018
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
  layer: domain
  name: Mastodon
  provider: mastodon
  says: ships the Mastodon SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id019
      status: none
    slug: nextcloud
    status: profiled
    tags: &id020
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud Bookmarks
  provider: nextcloud
  says: ships the Nextcloud Bookmarks SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: omnivore
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Omnivore
  provider: omnivore
  says: ships the Omnivore SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.3
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id023
      status: unknown
    slug: pinboard
    status: profiled
    tags: &id024
    - Bookmarking
    - Company
    - Productivity
    - Social
    url: /providers/pinboard/
  layer: domain
  name: Pinboard
  provider: pinboard
  says: ships the Pinboard SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_band: agent-ready
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id025
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id026
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: domain
  name: Pinterest
  provider: pinterest
  says: ships the Pinterest SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.1
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id027
      source: https://help.raindrop.io/integrations/mcp
      status: verified
    slug: raindrop-io
    status: profiled
    tags: &id028
    - Bookmark
    - Cloud
    - Collaboration
    - Productivity
    url: /providers/raindrop-io/
  layer: domain
  name: Raindrop.io
  provider: raindrop-io
  says: ships the Raindrop.io SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_band: agent-ready
    agent_readiness: 43.0
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id029
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id030
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: ships the Reddit SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id031
      status: none
    slug: shaarli
    status: profiled
    tags: &id032
    - Bookmarking
    - Open Source
    - PHP
    - Self-Hosted
    url: /providers/shaarli/
  layer: domain
  name: Shaarli
  provider: shaarli
  says: ships the Shaarli SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id033
      status: none
    slug: telegram
    status: profiled
    tags: &id034
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 20.1
    mcp: &id035
      status: none
    slug: wallabag
    status: profiled
    tags: &id036
    - Open Source
    - Privacy
    - Read-it-later
    - Self-Hosted
    url: /providers/wallabag/
  layer: domain
  name: Wallabag
  provider: wallabag
  says: ships the Wallabag SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id037
      status: none
    slug: whatsapp
    status: profiled
    tags: &id038
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp
  provider: whatsapp
  says: ships the WhatsApp SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    mcp: &id039
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id040
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    agent_band: agent-ready
    agent_readiness: 34.8
    band: developing
    in_catalog: true
    kin_score: 40.3
    mcp: &id041
      status: none
    slug: xing
    status: profiled
    tags: &id042
    - Company
    - Job
    - Networking
    - Recruiters
    url: /providers/xing/
  layer: domain
  name: XING
  provider: xing
  says: ships the XING SDK or integration code
  source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/freshrss/
providers:
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id001
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id002
  url: /providers/bluesky/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id003
  name: Buffer
  slug: buffer
  status: profiled
  tags: *id004
  url: /providers/buffer/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 44.2
  mcp: *id005
  name: diaspora*
  slug: diaspora
  status: profiled
  tags: *id006
  url: /providers/diaspora/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 20.4
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id009
  name: Lemmy
  slug: lemmy
  status: profiled
  tags: *id010
  url: /providers/lemmy/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id011
  name: LinkAce
  slug: linkace
  status: profiled
  tags: *id012
  url: /providers/linkace/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id013
  name: linkding
  slug: linkding
  status: profiled
  tags: *id014
  url: /providers/linkding/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id015
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id016
  url: /providers/linkedin/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id017
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id018
  url: /providers/mastodon/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id019
  name: Nextcloud Bookmarks
  slug: nextcloud
  status: profiled
  tags: *id020
  url: /providers/nextcloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Omnivore
  slug: omnivore
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: agent-aware
  agent_readiness: 5.3
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id023
  name: Pinboard
  slug: pinboard
  status: profiled
  tags: *id024
  url: /providers/pinboard/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id025
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id026
  url: /providers/pinterest/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id027
  name: Raindrop.io
  slug: raindrop-io
  status: profiled
  tags: *id028
  url: /providers/raindrop-io/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id029
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id030
  url: /providers/reddit/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id031
  name: Shaarli
  slug: shaarli
  status: profiled
  tags: *id032
  url: /providers/shaarli/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id033
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id034
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id035
  name: Wallabag
  slug: wallabag
  status: profiled
  tags: *id036
  url: /providers/wallabag/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id037
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id038
  url: /providers/whatsapp/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id039
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id040
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: developing
  in_catalog: true
  kin_score: 40.3
  mcp: *id041
  name: XING
  slug: xing
  status: profiled
  tags: *id042
  url: /providers/xing/
siblings:
- name: Feedly
  rows: 8
  url: /applications/news-feed-reader/feedly/
- name: Karakeep
  rows: 4
  url: /applications/news-feed-reader/karakeep/
- name: Linkwarden
  rows: 55
  url: /applications/news-feed-reader/linkwarden/
- name: Miniflux
  rows: 28
  url: /applications/news-feed-reader/miniflux/
- name: NewsBlur
  rows: 11
  url: /applications/news-feed-reader/newsblur/
- name: Readwise Reader
  rows: 10
  url: /applications/news-feed-reader/readwise-reader/
- name: Wallabag
  rows: 8
  url: /applications/news-feed-reader/wallabag/
sitemap: true
title: 'FreshRSS: News, Feeds & Read-Later reference app'
---
