---
app: PrivateBin
app_slug: privatebin
app_url: https://github.com/PrivateBin/PrivateBin
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Chhoto URL
  - Shlink
  - YOURLS
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: pastebin-file-drop
  name: Pastebin, File Drop & Quick Share
  url: /applications/pastebin-file-drop/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/composer.json
- route: source code
  url: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
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
  layer: domain
  name: Amazon S3
  provider: amazon-s3
  says: lists Amazon S3 as an integration
  source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id003
      status: unknown
    slug: chhoto-url
    status: profiled
    tags: &id004
    - Open Source
    - Rust
    - Self-Hosted
    - URL Shorteners
    url: /providers/chhoto-url/
  layer: domain
  name: Chhoto URL
  provider: chhoto-url
  says: lists Chhoto URL as an integration
  source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id005
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id006
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: domain
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: lists Google Cloud Storage as an integration
  source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id007
      status: none
    slug: shlink
    status: profiled
    tags: &id008
    - Company
    - PHP
    - Self-Hosted
    - URL Shorteners
    url: /providers/shlink/
  layer: domain
  name: Shlink
  provider: shlink
  says: lists Shlink as an integration
  source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id009
      status: none
    slug: yourls
    status: profiled
    tags: &id010
    - Company
    - Open Source
    - PHP
    - URL Shorteners
    url: /providers/yourls/
  layer: domain
  name: YOURLS
  provider: yourls
  says: lists YOURLS as an integration
  source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pastebin-file-drop/privatebin/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id003
  name: Chhoto URL
  slug: chhoto-url
  status: profiled
  tags: *id004
  url: /providers/chhoto-url/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id005
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id006
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id007
  name: Shlink
  slug: shlink
  status: profiled
  tags: *id008
  url: /providers/shlink/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id009
  name: YOURLS
  slug: yourls
  status: profiled
  tags: *id010
  url: /providers/yourls/
siblings:
- name: LocalSend
  rows: 2
  url: /applications/pastebin-file-drop/localsend/
- name: Pingvin Share
  rows: 5
  url: /applications/pastebin-file-drop/pingvin-share/
- name: PsiTransfer
  rows: 0
  url: /applications/pastebin-file-drop/psitransfer/
- name: Send (timvisee fork of Firefox Send)
  rows: 4
  url: /applications/pastebin-file-drop/send-timvisee-fork-of-firefox-send/
- name: WeTransfer
  rows: 2
  url: /applications/pastebin-file-drop/wetransfer/
- name: Zipline
  rows: 5
  url: /applications/pastebin-file-drop/zipline/
sitemap: true
title: 'PrivateBin: Pastebin, File Drop & Quick Share reference app'
---
