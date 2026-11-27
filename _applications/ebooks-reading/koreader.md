---
app: KOReader
app_slug: koreader
app_url: https://github.com/koreader/koreader
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - wallabag
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-230.90
  key: AE-230.90
  layer: domain
  name: Dictionaries & Lexical Reference
  providers:
  - Wikipedia
  url: /capabilities/dictionaries-lexical-reference/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: ebooks-reading
  name: E-books, Reading & Comics
  url: /applications/ebooks-reading/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.koreader.launcher/latest/
- route: source code
  url: https://github.com/koreader/koreader/blob/master/frontend/ui/wikipedia.lua
- route: source code
  url: https://github.com/koreader/koreader/tree/master/plugins
- route: source code
  url: https://github.com/koreader/koreader/tree/master/plugins/cloudstorage.koplugin/providers
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id001
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id002
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/koreader/koreader/tree/master/plugins/cloudstorage.koplugin/providers
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
    mcp: &id003
      status: none
    slug: wallabag
    status: profiled
    tags: &id004
    - Open Source
    - Privacy
    - Read-it-later
    - Self-Hosted
    url: /providers/wallabag/
  layer: domain
  name: wallabag
  provider: wallabag
  says: ships the wallabag SDK or integration code
  source: https://github.com/koreader/koreader/tree/master/plugins/wallabag.koplugin
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.90
    key: AE-230.90
    name: Dictionaries & Lexical Reference
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id005
      status: none
    slug: wikipedia
    status: profiled
    tags: &id006
    - Encyclopedia
    - Open Data
    - Open Knowledge
    - Public APIs
    url: /providers/wikipedia/
  layer: domain
  name: Wikipedia
  provider: wikipedia
  says: ships the Wikipedia SDK or integration code
  source: https://github.com/koreader/koreader/blob/master/frontend/ui/wikipedia.lua
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ebooks-reading/koreader/
providers:
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id001
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id002
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id003
  name: wallabag
  slug: wallabag
  status: profiled
  tags: *id004
  url: /providers/wallabag/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id005
  name: Wikipedia
  slug: wikipedia
  status: profiled
  tags: *id006
  url: /providers/wikipedia/
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
- name: Komga
  rows: 1
  url: /applications/ebooks-reading/komga/
- name: Readest
  rows: 14
  url: /applications/ebooks-reading/readest/
sitemap: true
title: 'KOReader: E-books, Reading & Comics reference app'
---
