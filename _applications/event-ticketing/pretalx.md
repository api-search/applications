---
app: pretalx
app_slug: pretalx
app_url: https://github.com/pretalx/pretalx
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.40
  key: AE-160.10.40
  layer: domain
  name: Account Linking
  providers:
  - ORCID
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - Vimeo
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Friendly Captcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
category:
  id: event-ticketing
  name: Events & Ticketing
  url: /applications/event-ticketing/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/pretalx/pretalx/blob/main/pyproject.toml
- route: source code
  url: https://github.com/pretalx
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id001
      status: none
    slug: friendly-captcha
    status: profiled
    tags: &id002
    - Bot Defense
    - CAPTCHA
    - Privacy
    - Proof of Work
    url: /providers/friendly-captcha/
  layer: common
  name: Friendly Captcha
  provider: friendly-captcha
  says: lists Friendly Captcha as an integration
  source: https://github.com/pretalx/pretalx-friendly-captcha
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id003
      status: none
    slug: orcid
    status: profiled
    tags: &id004
    - Academic
    - Identity
    - ORCID
    - Researchers
    url: /providers/orcid/
  layer: domain
  name: ORCID
  provider: orcid
  says: lists ORCID as an integration
  source: https://github.com/pretalx/pretalx-orcid
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id005
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id006
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: lists Vimeo as an integration
  source: https://github.com/pretalx/pretalx-vimeo
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id007
      status: none
    slug: youtube
    status: profiled
    tags: &id008
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://github.com/pretalx/pretalx-youtube
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/event-ticketing/pretalx/
providers:
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id001
  name: Friendly Captcha
  slug: friendly-captcha
  status: profiled
  tags: *id002
  url: /providers/friendly-captcha/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id003
  name: ORCID
  slug: orcid
  status: profiled
  tags: *id004
  url: /providers/orcid/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id005
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id006
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id007
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id008
  url: /providers/youtube/
siblings:
- name: alf.io
  rows: 13
  url: /applications/event-ticketing/alf-io/
- name: Hi.Events
  rows: 6
  url: /applications/event-ticketing/hi-events/
- name: Indico
  rows: 11
  url: /applications/event-ticketing/indico/
- name: Luma
  rows: 3
  url: /applications/event-ticketing/luma/
- name: pretix
  rows: 23
  url: /applications/event-ticketing/pretix/
- name: Ticketmaster
  rows: 4
  url: /applications/event-ticketing/ticketmaster/
- name: Tito
  rows: 3
  url: /applications/event-ticketing/tito/
sitemap: true
title: 'pretalx: Events & Ticketing reference app'
---
