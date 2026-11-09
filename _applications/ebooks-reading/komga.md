---
app: Komga
app_slug: komga
app_url: https://github.com/gotson/komga
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.20
  key: AE-170.60.20
  layer: domain
  name: Books & E-Books
  providers:
  - Rakuten Kobo
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
category:
  id: ebooks-reading
  name: E-books, Reading & Comics
  url: /applications/ebooks-reading/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/gotson/komga/blob/master/komga/build.gradle.kts
- route: source code
  url: https://github.com/gotson/komga/blob/master/komga/src/main/kotlin/org/gotson/komga/infrastructure/kobo/KoboProxy.kt
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: rakuten-kobo
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Rakuten Kobo
  provider: rakuten-kobo
  says: ships the Rakuten Kobo SDK or integration code
  source: https://github.com/gotson/komga/blob/master/komga/src/main/kotlin/org/gotson/komga/infrastructure/kobo/KoboProxy.kt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ebooks-reading/komga/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Rakuten Kobo
  slug: rakuten-kobo
  status: queued for profiling
  tags: *id002
  url: null
siblings:
- name: Calibre-Web
  rows: 11
  url: /applications/ebooks-reading/calibre-web/
- name: Goodreads
  rows: 3
  url: /applications/ebooks-reading/goodreads/
- name: Kavita
  rows: 3
  url: /applications/ebooks-reading/kavita/
- name: Kindle
  rows: 2
  url: /applications/ebooks-reading/kindle/
- name: KOReader
  rows: 3
  url: /applications/ebooks-reading/koreader/
- name: Readest
  rows: 14
  url: /applications/ebooks-reading/readest/
sitemap: true
title: 'Komga: E-books, Reading & Comics reference app'
---
