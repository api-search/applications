---
app: Kavita
app_slug: kavita
app_url: https://github.com/Kareadita/Kavita
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.100
  key: AE-170.100
  layer: domain
  name: Watch & Listen History Sync
  providers:
  - AniList
  - Hardcover
  - MyAnimeList
  url: /capabilities/watch-listen-history-sync/
  via_parent: null
category:
  id: ebooks-reading
  name: E-books, Reading & Comics
  url: /applications/ebooks-reading/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Kareadita/Kavita/blob/develop/Kavita.Common/Kavita.Common.csproj
- route: source code
  url: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.6
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id001
      status: none
    slug: anilist
    status: profiled
    tags: &id002
    - Anime
    - Entertainment
    - Manga
    - Media
    url: /providers/anilist/
  layer: domain
  name: AniList
  provider: anilist
  says: ships the AniList SDK or integration code
  source: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id003
      status: none
    slug: hardcover
    status: profiled
    tags: &id004
    - Book
    - Company
    - Reading
    - Social
    url: /providers/hardcover/
  layer: domain
  name: Hardcover
  provider: hardcover
  says: ships the Hardcover SDK or integration code
  source: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id005
      status: none
    slug: myanimelist
    status: profiled
    tags: &id006
    - Anime
    - Public APIs
    url: /providers/myanimelist/
  layer: domain
  name: MyAnimeList
  provider: myanimelist
  says: ships the MyAnimeList SDK or integration code
  source: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ebooks-reading/kavita/
providers:
- agent_band: agent-ready
  agent_readiness: 36.6
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id001
  name: AniList
  slug: anilist
  status: profiled
  tags: *id002
  url: /providers/anilist/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id003
  name: Hardcover
  slug: hardcover
  status: profiled
  tags: *id004
  url: /providers/hardcover/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id005
  name: MyAnimeList
  slug: myanimelist
  status: profiled
  tags: *id006
  url: /providers/myanimelist/
siblings:
- name: Calibre-Web
  rows: 11
  url: /applications/ebooks-reading/calibre-web/
- name: Goodreads
  rows: 3
  url: /applications/ebooks-reading/goodreads/
- name: Kindle
  rows: 2
  url: /applications/ebooks-reading/kindle/
- name: Komga
  rows: 1
  url: /applications/ebooks-reading/komga/
- name: KOReader
  rows: 3
  url: /applications/ebooks-reading/koreader/
- name: Readest
  rows: 14
  url: /applications/ebooks-reading/readest/
sitemap: true
title: 'Kavita: E-books, Reading & Comics reference app'
---
