---
app: Miniflux
app_slug: miniflux
app_url: https://github.com/miniflux/v2
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - Betula
  - Cubox
  - Espial
  - Instapaper
  - Karakeep
  - LinkAce
  - linkding
  - LinkTaco
  - Linkwarden
  - Omnivore
  - Pinboard
  - Raindrop.io
  - Readeck
  - Readwise
  - RSS-Bridge
  - Shaarli
  - Shiori
  - Wallabag
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: Turbo EA
  id: BC-830.10
  key: knowledge-capture-management
  layer: domain
  name: Knowledge Capture Management
  providers:
  - Notion
  url: /capabilities/knowledge-capture-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.40.40
  key: AE-230.40.40
  layer: domain
  name: Web Archiving & Page Snapshots
  providers:
  - Internet Archive (Wayback save)
  url: /capabilities/web-data/
  via_parent: Web Data
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Apprise
  - Gotify
  - ntfy
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Discord
  - Matrix
  - Slack
  - Telegram
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 0
  observed: 28
credits: []
evidence:
- route: source code
  url: https://github.com/miniflux/v2/tree/main/internal/integration
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: apprise
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: common
  name: Apprise
  provider: apprise
  says: ships the Apprise SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 27.7
    band: emerging
    in_catalog: true
    kin_score: 18.7
    mcp: &id003
      status: unknown
    slug: betula
    status: profiled
    tags: &id004
    - Bookmark manager
    - Federated
    - Open Source
    - Self-Hosted
    url: /providers/betula/
  layer: domain
  name: Betula
  provider: betula
  says: ships the Betula SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id005
      status: unknown
    slug: cubox
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Company
    - Knowledge Management
    - Reading
    url: /providers/cubox/
  layer: domain
  name: Cubox
  provider: cubox
  says: ships the Cubox SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id007
      status: none
    slug: discord
    status: profiled
    tags: &id008
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    kin_score: 6.3
    mcp: &id009
      status: unknown
    slug: espial
    status: profiled
    tags: &id010
    - Bookmarking
    - Company
    - Haskell
    - Open Source
    url: /providers/espial/
  layer: domain
  name: Espial
  provider: espial
  says: ships the Espial SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id011
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id012
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 8.5
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id013
      status: none
    slug: instapaper
    status: profiled
    tags: &id014
    - Company
    - Productivity
    - Read-it-later
    - Web Service
    url: /providers/instapaper/
  layer: domain
  name: Instapaper
  provider: instapaper
  says: ships the Instapaper SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.40
    key: AE-230.40.40
    name: Web Archiving & Page Snapshots
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id015
      status: none
    slug: internet-archive
    status: profiled
    tags: &id016
    - Archival
    - Digital Library
    - Non-Profit
    - Open Access
    url: /providers/internet-archive/
  layer: domain
  name: Internet Archive (Wayback save)
  provider: internet-archive
  says: ships the Internet Archive (Wayback save) SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 19.7
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id017
      source: https://docs.karakeep.app/mcp
      status: verified
    slug: karakeep
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Bookmarking
    - Collaboration
    - Company
    url: /providers/karakeep/
  layer: domain
  name: Karakeep
  provider: karakeep
  says: ships the Karakeep SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id019
      status: none
    slug: linkace
    status: profiled
    tags: &id020
    - Bookmarking
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkace/
  layer: domain
  name: LinkAce
  provider: linkace
  says: ships the LinkAce SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id021
      status: none
    slug: linkding
    status: profiled
    tags: &id022
    - Bookmark
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkding/
  layer: domain
  name: linkding
  provider: linkding
  says: ships the linkding SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    kin_score: 9.2
    mcp: &id023
      status: unknown
    slug: linktaco
    status: profiled
    tags: &id024
    - Bookmarking
    - Company
    - LinkShortening
    - Open Source
    url: /providers/linktaco/
  layer: domain
  name: LinkTaco
  provider: linktaco
  says: ships the LinkTaco SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id025
      status: none
    slug: linkwarden
    status: profiled
    tags: &id026
    - Bookmarking
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkwarden/
  layer: domain
  name: Linkwarden
  provider: linkwarden
  says: ships the Linkwarden SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id027
      status: none
    slug: matrix
    status: profiled
    tags: &id028
    - Decentralized
    - Federated
    - Messaging
    - Open Standard
    url: /providers/matrix/
  layer: common
  name: Matrix
  provider: matrix
  says: ships the Matrix SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.10
    key: knowledge-capture-management
    name: Knowledge Capture Management
    url: /capabilities/knowledge-capture-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id029
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id030
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: ships the Notion SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id031
      status: none
    slug: ntfy
    status: profiled
    tags: &id032
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id033
      status: unchecked
    slug: omnivore
    status: queued for profiling
    tags: &id034 []
    url: null
  layer: domain
  name: Omnivore
  provider: omnivore
  says: ships the Omnivore SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id035
      status: unknown
    slug: pinboard
    status: profiled
    tags: &id036
    - Bookmarking
    - Company
    - Productivity
    - Social
    url: /providers/pinboard/
  layer: domain
  name: Pinboard
  provider: pinboard
  says: ships the Pinboard SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id037
      status: none
    slug: pushover
    status: profiled
    tags: &id038
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id039
      source: https://help.raindrop.io/integrations/mcp
      status: verified
    slug: raindrop-io
    status: profiled
    tags: &id040
    - Bookmark
    - Cloud
    - Collaboration
    - Productivity
    url: /providers/raindrop-io/
  layer: domain
  name: Raindrop.io
  provider: raindrop-io
  says: ships the Raindrop.io SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id041
      status: none
    slug: readeck
    status: profiled
    tags: &id042
    - Bookmarking
    - Company
    - Content Curation
    - Reading
    url: /providers/readeck/
  layer: domain
  name: Readeck
  provider: readeck
  says: ships the Readeck SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id043
      source: https://readwise.io/mcp
      status: verified
    slug: readwise
    status: profiled
    tags: &id044
    - Knowledge Management
    - Productivity
    - Reading
    - Software-as-a-Service
    url: /providers/readwise/
  layer: domain
  name: Readwise
  provider: readwise
  says: ships the Readwise SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id045
      status: none
    slug: rss-bridge
    status: profiled
    tags: &id046
    - Aggregator
    - Open Source
    - PHP
    - RSS
    url: /providers/rss-bridge/
  layer: domain
  name: RSS-Bridge
  provider: rss-bridge
  says: ships the RSS-Bridge SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id047
      status: none
    slug: shaarli
    status: profiled
    tags: &id048
    - Bookmarking
    - Open Source
    - PHP
    - Self-Hosted
    url: /providers/shaarli/
  layer: domain
  name: Shaarli
  provider: shaarli
  says: ships the Shaarli SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id049
      status: none
    slug: shiori
    status: profiled
    tags: &id050
    - Bookmarks
    - Go
    - Open Source
    - Self-Hosted
    url: /providers/shiori/
  layer: domain
  name: Shiori
  provider: shiori
  says: ships the Shiori SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id051
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id052
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id053
      status: none
    slug: telegram
    status: profiled
    tags: &id054
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    mcp: &id055
      status: none
    slug: wallabag
    status: profiled
    tags: &id056
    - Open Source
    - Privacy
    - Read-it-later
    - Self-Hosted
    url: /providers/wallabag/
  layer: domain
  name: Wallabag
  provider: wallabag
  says: ships the Wallabag SDK or integration code
  source: https://github.com/miniflux/v2/tree/main/internal/integration
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/miniflux/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Apprise
  slug: apprise
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-aware
  agent_readiness: 27.7
  band: emerging
  in_catalog: true
  kin_score: 18.7
  mcp: *id003
  name: Betula
  slug: betula
  status: profiled
  tags: *id004
  url: /providers/betula/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id005
  name: Cubox
  slug: cubox
  status: profiled
  tags: *id006
  url: /providers/cubox/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id007
  name: Discord
  slug: discord
  status: profiled
  tags: *id008
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.3
  mcp: *id009
  name: Espial
  slug: espial
  status: profiled
  tags: *id010
  url: /providers/espial/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id011
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id012
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 8.5
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id013
  name: Instapaper
  slug: instapaper
  status: profiled
  tags: *id014
  url: /providers/instapaper/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id015
  name: Internet Archive (Wayback save)
  slug: internet-archive
  status: profiled
  tags: *id016
  url: /providers/internet-archive/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id017
  name: Karakeep
  slug: karakeep
  status: profiled
  tags: *id018
  url: /providers/karakeep/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id019
  name: LinkAce
  slug: linkace
  status: profiled
  tags: *id020
  url: /providers/linkace/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id021
  name: linkding
  slug: linkding
  status: profiled
  tags: *id022
  url: /providers/linkding/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id023
  name: LinkTaco
  slug: linktaco
  status: profiled
  tags: *id024
  url: /providers/linktaco/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id025
  name: Linkwarden
  slug: linkwarden
  status: profiled
  tags: *id026
  url: /providers/linkwarden/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id027
  name: Matrix
  slug: matrix
  status: profiled
  tags: *id028
  url: /providers/matrix/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id029
  name: Notion
  slug: notion
  status: profiled
  tags: *id030
  url: /providers/notion/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id031
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id032
  url: /providers/ntfy/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id033
  name: Omnivore
  slug: omnivore
  status: queued for profiling
  tags: *id034
  url: null
- agent_band: agent-aware
  agent_readiness: 5.3
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id035
  name: Pinboard
  slug: pinboard
  status: profiled
  tags: *id036
  url: /providers/pinboard/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id037
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id038
  url: /providers/pushover/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id039
  name: Raindrop.io
  slug: raindrop-io
  status: profiled
  tags: *id040
  url: /providers/raindrop-io/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id041
  name: Readeck
  slug: readeck
  status: profiled
  tags: *id042
  url: /providers/readeck/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id043
  name: Readwise
  slug: readwise
  status: profiled
  tags: *id044
  url: /providers/readwise/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id045
  name: RSS-Bridge
  slug: rss-bridge
  status: profiled
  tags: *id046
  url: /providers/rss-bridge/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id047
  name: Shaarli
  slug: shaarli
  status: profiled
  tags: *id048
  url: /providers/shaarli/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id049
  name: Shiori
  slug: shiori
  status: profiled
  tags: *id050
  url: /providers/shiori/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id051
  name: Slack
  slug: slack
  status: profiled
  tags: *id052
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id053
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id054
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id055
  name: Wallabag
  slug: wallabag
  status: profiled
  tags: *id056
  url: /providers/wallabag/
siblings:
- name: Feedly
  rows: 8
  url: /applications/news-feed-reader/feedly/
- name: FreshRSS
  rows: 21
  url: /applications/news-feed-reader/freshrss/
- name: Karakeep
  rows: 4
  url: /applications/news-feed-reader/karakeep/
- name: Linkwarden
  rows: 55
  url: /applications/news-feed-reader/linkwarden/
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
title: 'Miniflux: News, Feeds & Read-Later reference app'
---
