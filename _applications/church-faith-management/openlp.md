---
app: OpenLP
app_slug: openlp
app_url: https://gitlab.com/openlp/openlp
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.10.40
  key: AE-170.10.40
  layer: domain
  name: Live Presentation & Broadcast Control
  providers:
  - OBS Studio
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-170.60.50
  key: AE-170.60.50
  layer: domain
  name: Scripture & Religious Text Content
  providers:
  - Bible Gateway
  - Bible Study Tools (Crosswalk)
  - BibleServer
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-170.20.70
  key: AE-170.20.70
  layer: domain
  name: Worship Song Licensing & Chord Charts
  providers:
  - CCLI SongSelect
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-943
  key: AE-943
  layer: common
  name: Church Management System Sync
  providers:
  - Planning Center
  url: /capabilities/church-management-system-sync/
  via_parent: null
category:
  id: church-faith-management
  name: Church & Faith Community Management
  url: /applications/church-faith-management/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: source code
  url: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
- route: source code
  url: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.50
    key: AE-170.60.50
    name: Scripture & Religious Text Content
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id001
      status: unchecked
    slug: biblegateway
    status: profiled
    tags: &id002
    - Audio Bibles
    - Bible
    - Online Scripture
    - Reading Plans
    url: /providers/biblegateway/
  layer: domain
  name: Bible Gateway
  provider: biblegateway
  says: ships the Bible Gateway SDK or integration code
  source: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.50
    key: AE-170.60.50
    name: Scripture & Religious Text Content
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.7
    mcp: &id003
      status: unchecked
    slug: biblestudytools
    status: profiled
    tags: &id004
    - Bible
    - Company
    - Scripture
    - Study Tools
    url: /providers/biblestudytools/
  layer: domain
  name: Bible Study Tools (Crosswalk)
  provider: biblestudytools
  says: ships the Bible Study Tools (Crosswalk) SDK or integration code
  source: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.50
    key: AE-170.60.50
    name: Scripture & Religious Text Content
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.4
    mcp: &id005
      status: unchecked
    slug: bibleserver
    status: profiled
    tags: &id006
    - Bible
    - Community
    - Religion
    - Study
    url: /providers/bibleserver/
  layer: domain
  name: BibleServer
  provider: bibleserver
  says: ships the BibleServer SDK or integration code
  source: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.70
    key: AE-170.20.70
    name: Worship Song Licensing & Chord Charts
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id007
      status: unchecked
    slug: ccli
    status: profiled
    tags: &id008
    - Company
    - Licensing
    - Music
    - Worship
    url: /providers/ccli/
  layer: domain
  name: CCLI SongSelect
  provider: ccli
  says: ships the CCLI SongSelect SDK or integration code
  source: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/songs/lib
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.40
    key: AE-170.10.40
    name: Live Presentation & Broadcast Control
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id009
      status: unchecked
    slug: obs-studio
    status: profiled
    tags: &id010
    - Live Streaming
    - Open-source software
    - Video Recording
    url: /providers/obs-studio/
  layer: domain
  name: OBS Studio
  provider: obs-studio
  says: ships the OBS Studio SDK or integration code
  source: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/obs_studio
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id011
      source: https://mcp.planningcenteronline.com/mcp
      status: verified
    slug: planning-center
    status: profiled
    tags: &id012
    - ChMS
    - Church Management
    - Faith
    - Giving
    url: /providers/planning-center/
  layer: common
  name: Planning Center
  provider: planning-center
  says: ships the Planning Center SDK or integration code
  source: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/planningcenter
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/church-faith-management/openlp/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id001
  name: Bible Gateway
  slug: biblegateway
  status: profiled
  tags: *id002
  url: /providers/biblegateway/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id003
  name: Bible Study Tools (Crosswalk)
  slug: biblestudytools
  status: profiled
  tags: *id004
  url: /providers/biblestudytools/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.4
  mcp: *id005
  name: BibleServer
  slug: bibleserver
  status: profiled
  tags: *id006
  url: /providers/bibleserver/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id007
  name: CCLI SongSelect
  slug: ccli
  status: profiled
  tags: *id008
  url: /providers/ccli/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id009
  name: OBS Studio
  slug: obs-studio
  status: profiled
  tags: *id010
  url: /providers/obs-studio/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id011
  name: Planning Center
  slug: planning-center
  status: profiled
  tags: *id012
  url: /providers/planning-center/
siblings:
- name: ChurchCRM
  rows: 7
  url: /applications/church-faith-management/churchcrm/
- name: Planning Center
  rows: 20
  url: /applications/church-faith-management/planning-center/
- name: Pushpay
  rows: 20
  url: /applications/church-faith-management/pushpay/
- name: Rock RMS
  rows: 21
  url: /applications/church-faith-management/rock-rms/
- name: Tithe.ly
  rows: 11
  url: /applications/church-faith-management/tithe-ly/
sitemap: true
title: 'OpenLP: Church & Faith Community Management reference app'
---
