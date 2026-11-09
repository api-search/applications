---
app: Calibre-Web
app_slug: calibre-web
app_url: https://github.com/janeczku/calibre-web
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.20
  key: AE-170.60.20
  layer: domain
  name: Books & E-Books
  providers:
  - Amazon
  - Comic Vine
  - Douban
  - Goodreads
  - Google Books
  - LubimyCzytac
  - Rakuten Kobo
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-230.100
  key: AE-230.100
  layer: domain
  name: Scholarly & Research Metadata
  providers:
  - Google Scholar
  url: /capabilities/scholarly-research-metadata/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: ebooks-reading
  name: E-books, Reading & Comics
  url: /applications/ebooks-reading/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
- route: source code
  url: https://github.com/janeczku/calibre-web/blob/master/cps/kobo.py
- route: source code
  url: https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
- route: source code
  url: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
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
  name: Amazon
  provider: amazon
  says: ships the Amazon SDK or integration code
  source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id003
      status: unknown
    slug: comic-vine
    status: profiled
    tags: &id004
    - Comics
    - Public APIs
    url: /providers/comic-vine/
  layer: domain
  name: Comic Vine
  provider: comic-vine
  says: ships the Comic Vine SDK or integration code
  source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id005
      status: none
    slug: douban
    status: profiled
    tags: &id006
    - China
    - Entertainment
    - Media
    - Social
    url: /providers/douban/
  layer: domain
  name: Douban
  provider: douban
  says: ships the Douban SDK or integration code
  source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id007
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id008
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.5
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id009
      status: none
    slug: goodreads
    status: profiled
    tags: &id010
    - Books
    - Company
    - Consumer
    - Reading
    url: /providers/goodreads/
  layer: domain
  name: Goodreads
  provider: goodreads
  says: ships the Goodreads SDK or integration code
  source: https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id011
      status: none
    slug: google-books
    status: profiled
    tags: &id012
    - Books
    - Ebooks
    - Google
    - Library
    url: /providers/google-books/
  layer: domain
  name: Google Books
  provider: google-books
  says: ships the Google Books SDK or integration code
  source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  tier: observed
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
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id014
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.100
    key: AE-230.100
    name: Scholarly & Research Metadata
    url: /capabilities/scholarly-research-metadata/
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
    slug: google-scholar
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Google Scholar
  provider: google-scholar
  says: ships the Google Scholar SDK or integration code
  source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id017
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id018
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.2
    mcp: &id019
      status: unknown
    slug: lubimyczytac
    status: profiled
    tags: &id020
    - Books
    - Company
    - Price Comparison
    - Reviews
    url: /providers/lubimyczytac/
  layer: domain
  name: LubimyCzytac
  provider: lubimyczytac
  says: ships the LubimyCzytac SDK or integration code
  source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  tier: observed
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
    mcp: &id021
      status: unchecked
    slug: rakuten-kobo
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Rakuten Kobo
  provider: rakuten-kobo
  says: ships the Rakuten Kobo SDK or integration code
  source: https://github.com/janeczku/calibre-web/blob/master/cps/kobo.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ebooks-reading/calibre-web/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id003
  name: Comic Vine
  slug: comic-vine
  status: profiled
  tags: *id004
  url: /providers/comic-vine/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id005
  name: Douban
  slug: douban
  status: profiled
  tags: *id006
  url: /providers/douban/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id007
  name: GitHub
  slug: github
  status: profiled
  tags: *id008
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 6.5
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id009
  name: Goodreads
  slug: goodreads
  status: profiled
  tags: *id010
  url: /providers/goodreads/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id011
  name: Google Books
  slug: google-books
  status: profiled
  tags: *id012
  url: /providers/google-books/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id013
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id014
  url: /providers/google-drive/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Google Scholar
  slug: google-scholar
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id017
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id018
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id019
  name: LubimyCzytac
  slug: lubimyczytac
  status: profiled
  tags: *id020
  url: /providers/lubimyczytac/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Rakuten Kobo
  slug: rakuten-kobo
  status: queued for profiling
  tags: *id022
  url: null
siblings:
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
- name: KOReader
  rows: 3
  url: /applications/ebooks-reading/koreader/
- name: Readest
  rows: 14
  url: /applications/ebooks-reading/readest/
sitemap: true
title: 'Calibre-Web: E-books, Reading & Comics reference app'
---
