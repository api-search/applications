---
app: Readwise Reader
app_slug: readwise-reader
app_url: https://readwise.io/read
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - Instapaper
  - Pocket
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-170.60.20
  key: AE-170.60.20
  layer: domain
  name: Books & E-Books
  providers:
  - Amazon Kindle
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: Turbo EA
  id: BC-830.10
  key: knowledge-capture-management
  layer: domain
  name: Knowledge Capture Management
  providers:
  - Evernote
  - Logseq
  - Notion
  - Obsidian
  - Roam Research
  url: /capabilities/knowledge-capture-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
category:
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 10
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://readwise.io/read
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon Kindle
  provider: amazon
  says: lists Amazon Kindle as an integration
  source: https://readwise.io/read
  tier: declared
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
    agent_readiness: 28.6
    band: developing
    in_catalog: true
    kin_score: 51.2
    mcp: &id003
      source: https://dev.evernote.com/
      status: documented
    slug: evernote
    status: profiled
    tags: &id004
    - Company
    - Knowledge Management
    - Note Taking
    - Productivity
    url: /providers/evernote/
  layer: domain
  name: Evernote
  provider: evernote
  says: lists Evernote as an integration
  source: https://readwise.io/read
  tier: declared
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
    agent_readiness: 11.5
    band: emerging
    in_catalog: true
    kin_score: 21.3
    mcp: &id005
      status: none
    slug: instapaper
    status: profiled
    tags: &id006
    - Company
    - Productivity
    - Read-it-later
    - Web Service
    url: /providers/instapaper/
  layer: domain
  name: Instapaper
  provider: instapaper
  says: lists Instapaper as an integration
  source: https://readwise.io/read
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.10
    key: knowledge-capture-management
    name: Knowledge Capture Management
    url: /capabilities/knowledge-capture-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id007
      status: none
    slug: logseq
    status: profiled
    tags: &id008
    - Company
    - Knowledge Management
    - Note Taking
    - Productivity
    url: /providers/logseq/
  layer: domain
  name: Logseq
  provider: logseq
  says: lists Logseq as an integration
  source: https://readwise.io/read
  tier: declared
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
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id009
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id010
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://readwise.io/read
  tier: declared
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
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id011
      status: none
    slug: obsidian
    status: profiled
    tags: &id012
    - Knowledge Management
    - Markdown
    - Notes
    - Productivity
    url: /providers/obsidian/
  layer: domain
  name: Obsidian
  provider: obsidian
  says: lists Obsidian as an integration
  source: https://readwise.io/read
  tier: declared
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
    kin_score: 4.2
    mcp: &id013
      status: none
    slug: pocket
    status: profiled
    tags: &id014
    - Bookmarking
    - Productivity
    - Public APIs
    url: /providers/pocket/
  layer: domain
  name: Pocket
  provider: pocket
  says: lists Pocket as an integration
  source: https://readwise.io/read
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.10
    key: knowledge-capture-management
    name: Knowledge Capture Management
    url: /capabilities/knowledge-capture-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: roam-research
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Roam Research
  provider: roam-research
  says: lists Roam Research as an integration
  source: https://readwise.io/read
  tier: declared
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
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id017
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id018
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: lists X (Twitter) as an integration
  source: https://readwise.io/read
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id019
      status: none
    slug: youtube
    status: profiled
    tags: &id020
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://readwise.io/read
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/readwise-reader/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon Kindle
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id003
  name: Evernote
  slug: evernote
  status: profiled
  tags: *id004
  url: /providers/evernote/
- agent_band: agent-aware
  agent_readiness: 11.5
  band: emerging
  in_catalog: true
  kin_score: 21.3
  mcp: *id005
  name: Instapaper
  slug: instapaper
  status: profiled
  tags: *id006
  url: /providers/instapaper/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id007
  name: Logseq
  slug: logseq
  status: profiled
  tags: *id008
  url: /providers/logseq/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id009
  name: Notion
  slug: notion
  status: profiled
  tags: *id010
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id011
  name: Obsidian
  slug: obsidian
  status: profiled
  tags: *id012
  url: /providers/obsidian/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id013
  name: Pocket
  slug: pocket
  status: profiled
  tags: *id014
  url: /providers/pocket/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Roam Research
  slug: roam-research
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id017
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id018
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id019
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id020
  url: /providers/youtube/
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
- name: Miniflux
  rows: 28
  url: /applications/news-feed-reader/miniflux/
- name: NewsBlur
  rows: 11
  url: /applications/news-feed-reader/newsblur/
- name: Wallabag
  rows: 8
  url: /applications/news-feed-reader/wallabag/
sitemap: true
title: 'Readwise Reader: News, Feeds & Read-Later reference app'
---
