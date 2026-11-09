---
app: Wallabag
app_slug: wallabag
app_url: https://github.com/wallabag/wallabag
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - Instapaper
  - Omnivore
  - Pinboard
  - Pocket
  - Shaarli
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Matomo (Piwik)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Gmail
  url: /capabilities/email/
  via_parent: Email
category:
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 0
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/fr.gaulupeau.apps.InThePoche/latest/
- route: dependency manifest
  url: https://github.com/wallabag/wallabag/blob/master/composer.json
- route: source code
  url: https://github.com/wallabag/wallabag/tree/master/src/Import
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id001
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id002
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: ships the Gmail SDK or integration code
  source: https://github.com/wallabag/wallabag/blob/master/composer.json
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
    agent_readiness: 11.5
    band: emerging
    in_catalog: true
    kin_score: 21.3
    mcp: &id003
      status: none
    slug: instapaper
    status: profiled
    tags: &id004
    - Company
    - Productivity
    - Read-it-later
    - Web Service
    url: /providers/instapaper/
  layer: domain
  name: Instapaper
  provider: instapaper
  says: ships the Instapaper SDK or integration code
  source: https://github.com/wallabag/wallabag/tree/master/src/Import
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
    mcp: &id005
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id006
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo (Piwik)
  provider: matomo
  says: ships the Matomo (Piwik) SDK or integration code
  source: https://github.com/wallabag/wallabag/blob/master/composer.json
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
    mcp: &id007
      status: unchecked
    slug: omnivore
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Omnivore
  provider: omnivore
  says: ships the Omnivore SDK or integration code
  source: https://github.com/wallabag/wallabag/tree/master/src/Import
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
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id009
      status: unknown
    slug: pinboard
    status: profiled
    tags: &id010
    - Bookmarking
    - Company
    - Productivity
    - Social
    url: /providers/pinboard/
  layer: domain
  name: Pinboard
  provider: pinboard
  says: ships the Pinboard SDK or integration code
  source: https://github.com/wallabag/wallabag/tree/master/src/Import
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
    kin_score: 4.2
    mcp: &id011
      status: none
    slug: pocket
    status: profiled
    tags: &id012
    - Bookmarking
    - Productivity
    - Public APIs
    url: /providers/pocket/
  layer: domain
  name: Pocket
  provider: pocket
  says: ships the Pocket SDK or integration code
  source: https://github.com/wallabag/wallabag/tree/master/src/Import
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/wallabag/wallabag/blob/master/composer.json
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
    agent_readiness: 23.2
    band: emerging
    in_catalog: true
    kin_score: 22.2
    mcp: &id015
      status: none
    slug: shaarli
    status: profiled
    tags: &id016
    - Bookmarking
    - Open Source
    - PHP
    - Self-Hosted
    url: /providers/shaarli/
  layer: domain
  name: Shaarli
  provider: shaarli
  says: ships the Shaarli SDK or integration code
  source: https://github.com/wallabag/wallabag/tree/master/src/Import
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/wallabag/
providers:
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id001
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id002
  url: /providers/google-gmail/
- agent_band: agent-aware
  agent_readiness: 11.5
  band: emerging
  in_catalog: true
  kin_score: 21.3
  mcp: *id003
  name: Instapaper
  slug: instapaper
  status: profiled
  tags: *id004
  url: /providers/instapaper/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id005
  name: Matomo (Piwik)
  slug: matomo
  status: profiled
  tags: *id006
  url: /providers/matomo/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Omnivore
  slug: omnivore
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id009
  name: Pinboard
  slug: pinboard
  status: profiled
  tags: *id010
  url: /providers/pinboard/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id011
  name: Pocket
  slug: pocket
  status: profiled
  tags: *id012
  url: /providers/pocket/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: emerging
  in_catalog: true
  kin_score: 22.2
  mcp: *id015
  name: Shaarli
  slug: shaarli
  status: profiled
  tags: *id016
  url: /providers/shaarli/
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
- name: Readwise Reader
  rows: 10
  url: /applications/news-feed-reader/readwise-reader/
sitemap: true
title: 'Wallabag: News, Feeds & Read-Later reference app'
---
