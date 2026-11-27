---
app: Baby Buddy
app_slug: baby-buddy
app_url: https://github.com/babybuddy/babybuddy
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Home Assistant
  url: /capabilities/smart-home/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
category:
  id: kids-family-parenting
  name: Kids, Family & Parenting
  url: /applications/kids-family-parenting/
counts:
  declared: 1
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/babybuddy/babybuddy/master/Pipfile
- route: documentation
  url: https://raw.githubusercontent.com/babybuddy/babybuddy/master/README.md
- route: source code
  url: https://raw.githubusercontent.com/babybuddy/babybuddy/master/babybuddy/settings/base.py
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/babybuddy/babybuddy/master/babybuddy/settings/base.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id003
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id004
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant
  provider: home-assistant
  says: lists Home Assistant as an integration
  source: https://raw.githubusercontent.com/babybuddy/babybuddy/master/README.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/kids-family-parenting/baby-buddy/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id003
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id004
  url: /providers/home-assistant/
siblings:
- name: Brightwheel
  rows: 3
  url: /applications/kids-family-parenting/brightwheel/
- name: Cozi
  rows: 9
  url: /applications/kids-family-parenting/cozi/
- name: Gramps Web
  rows: 2
  url: /applications/kids-family-parenting/gramps-web/
- name: Greenlight
  rows: 0
  url: /applications/kids-family-parenting/greenlight/
- name: Life360
  rows: 25
  url: /applications/kids-family-parenting/life360/
- name: OurFamilyWizard
  rows: 4
  url: /applications/kids-family-parenting/ourfamilywizard/
sitemap: true
title: 'Baby Buddy: Kids, Family & Parenting reference app'
---
