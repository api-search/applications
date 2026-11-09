---
app: Kdenlive
app_slug: kdenlive
app_url: https://github.com/KDE/kdenlive
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Pexels
  - Pixabay
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.40
  key: AE-170.30.40
  layer: domain
  name: Stock Media & Royalty-Free Libraries
  providers:
  - Freesound
  - Internet Archive
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
category:
  id: video-editing-creation
  name: Video & Photo Editing / Creator Tools
  url: /applications/video-editing-creation/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: source code
  url: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id001
      status: none
    slug: freesound
    status: profiled
    tags: &id002
    - Music
    - Public APIs
    url: /providers/freesound/
  layer: domain
  name: Freesound
  provider: freesound
  says: ships the Freesound SDK or integration code
  source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/freesound.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id003
      status: none
    slug: internet-archive
    status: profiled
    tags: &id004
    - Archival
    - Digital Library
    - Non-Profit
    - Open Access
    url: /providers/internet-archive/
  layer: domain
  name: Internet Archive
  provider: internet-archive
  says: ships the Internet Archive SDK or integration code
  source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/archiveorg.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id005
      status: none
    slug: pexels
    status: profiled
    tags: &id006
    - Photos
    - Stock Media
    - Video
    url: /providers/pexels/
  layer: domain
  name: Pexels
  provider: pexels
  says: ships the Pexels SDK or integration code
  source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/pexels_photo.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id007
      status: none
    slug: pixabay
    status: profiled
    tags: &id008
    - Illustrations
    - Image
    - Stock Media
    - Video
    url: /providers/pixabay/
  layer: domain
  name: Pixabay
  provider: pixabay
  says: ships the Pixabay SDK or integration code
  source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/pixabay_photo.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-editing-creation/kdenlive/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id001
  name: Freesound
  slug: freesound
  status: profiled
  tags: *id002
  url: /providers/freesound/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id003
  name: Internet Archive
  slug: internet-archive
  status: profiled
  tags: *id004
  url: /providers/internet-archive/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id005
  name: Pexels
  slug: pexels
  status: profiled
  tags: *id006
  url: /providers/pexels/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id007
  name: Pixabay
  slug: pixabay
  status: profiled
  tags: *id008
  url: /providers/pixabay/
siblings:
- name: Canva
  rows: 6
  url: /applications/video-editing-creation/canva/
- name: CapCut
  rows: 11
  url: /applications/video-editing-creation/capcut/
- name: Descript
  rows: 30
  url: /applications/video-editing-creation/descript/
- name: Excalidraw
  rows: 2
  url: /applications/video-editing-creation/excalidraw/
- name: Penpot
  rows: 3
  url: /applications/video-editing-creation/penpot/
- name: Remotion
  rows: 10
  url: /applications/video-editing-creation/remotion/
sitemap: true
title: 'Kdenlive: Video & Photo Editing / Creator Tools reference app'
---
