---
app: Audiobookshelf
app_slug: audiobookshelf
app_url: https://github.com/advplyr/audiobookshelf
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.30
  key: AE-170.20.30
  layer: domain
  name: Audiobooks
  providers:
  - Audible
  - AudiobookCovers
  - Audnexus
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.60.20
  key: AE-170.60.20
  layer: domain
  name: Books & E-Books
  providers:
  - FantLab
  - Google Books
  - Open Library
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - MusicBrainz
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.20.40
  key: AE-170.20.40
  layer: domain
  name: Podcast Directories & Search
  providers:
  - Apple (iTunes Search API)
  url: /capabilities/audio-music/
  via_parent: Audio & Music
category:
  id: podcasts-audiobooks
  name: Podcasts & Audiobooks
  url: /applications/podcasts-audiobooks/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/advplyr/audiobookshelf/blob/master/package.json
- route: source code
  url: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.40
    key: AE-170.20.40
    name: Podcast Directories & Search
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple (iTunes Search API)
  provider: apple
  says: ships the Apple (iTunes Search API) SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.30
    key: AE-170.20.30
    name: Audiobooks
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id003
      status: unknown
    slug: audible
    status: profiled
    tags: &id004
    - Audiobooks
    - Company
    - Consumer
    - Podcasts
    url: /providers/audible/
  layer: domain
  name: Audible
  provider: audible
  says: ships the Audible SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.30
    key: AE-170.20.30
    name: Audiobooks
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.4
    mcp: &id005
      status: none
    slug: audiobookcovers
    status: profiled
    tags: &id006
    - Audiobooks
    - Community
    - Company
    - CoverArt
    url: /providers/audiobookcovers/
  layer: domain
  name: AudiobookCovers
  provider: audiobookcovers
  says: ships the AudiobookCovers SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.30
    key: AE-170.20.30
    name: Audiobooks
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.8
    band: emerging
    in_catalog: true
    kin_score: 15.9
    mcp: &id007
      status: none
    slug: audnexus
    status: profiled
    tags: &id008
    - Audiobooks
    - Company
    - Metadata
    - Search
    url: /providers/audnexus/
  layer: domain
  name: Audnexus
  provider: audnexus
  says: ships the Audnexus SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
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
    kin_score: 5.1
    mcp: &id009
      status: none
    slug: fantlab
    status: profiled
    tags: &id010
    - Community
    - Company
    - Literature
    - Science Fiction
    url: /providers/fantlab/
  layer: domain
  name: FantLab
  provider: fantlab
  says: ships the FantLab SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
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
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id013
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id014
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
  layer: domain
  name: MusicBrainz
  provider: musicbrainz
  says: ships the MusicBrainz SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
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
    agent_readiness: 19.8
    band: emerging
    in_catalog: true
    kin_score: 23.9
    mcp: &id015
      status: unknown
    slug: open-library
    status: profiled
    tags: &id016
    - Authors
    - Books
    - Catalog
    - Covers
    url: /providers/open-library/
  layer: domain
  name: Open Library
  provider: open-library
  says: ships the Open Library SDK or integration code
  source: https://github.com/advplyr/audiobookshelf/tree/master/server/providers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/podcasts-audiobooks/audiobookshelf/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id001
  name: Apple (iTunes Search API)
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id003
  name: Audible
  slug: audible
  status: profiled
  tags: *id004
  url: /providers/audible/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.4
  mcp: *id005
  name: AudiobookCovers
  slug: audiobookcovers
  status: profiled
  tags: *id006
  url: /providers/audiobookcovers/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: emerging
  in_catalog: true
  kin_score: 15.9
  mcp: *id007
  name: Audnexus
  slug: audnexus
  status: profiled
  tags: *id008
  url: /providers/audnexus/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id009
  name: FantLab
  slug: fantlab
  status: profiled
  tags: *id010
  url: /providers/fantlab/
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
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id013
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id014
  url: /providers/musicbrainz/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: emerging
  in_catalog: true
  kin_score: 23.9
  mcp: *id015
  name: Open Library
  slug: open-library
  status: profiled
  tags: *id016
  url: /providers/open-library/
siblings:
- name: AntennaPod
  rows: 6
  url: /applications/podcasts-audiobooks/antennapod/
- name: Audible
  rows: 4
  url: /applications/podcasts-audiobooks/audible/
- name: Castopod
  rows: 1
  url: /applications/podcasts-audiobooks/castopod/
- name: Pocket Casts
  rows: 5
  url: /applications/podcasts-audiobooks/pocket-casts/
- name: Podverse
  rows: 7
  url: /applications/podcasts-audiobooks/podverse/
sitemap: true
title: 'Audiobookshelf: Podcasts & Audiobooks reference app'
---
