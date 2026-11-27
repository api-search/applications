---
app: ownCloud Infinite Scale
app_slug: owncloud-infinite-scale
app_url: https://github.com/owncloud/ocis
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: common
  name: End-User Computing Management
  providers:
  - Collabora Online
  - Microsoft Office (WOPI)
  - ONLYOFFICE
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/owncloud/ocis/master/go.mod
- route: documentation
  url: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id001
      status: none
    slug: collabora-online
    status: profiled
    tags: &id002
    - Collaboration
    - Company
    - Office Suite
    - Real-Time Editing
    url: /providers/collabora-online/
  layer: common
  name: Collabora Online
  provider: collabora-online
  says: lists Collabora Online as an integration
  source: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: documented
    slug: microsoft-office
    status: profiled
    tags: &id004
    - Collaboration
    - Documents
    - Microsoft
    - Office
    url: /providers/microsoft-office/
  layer: common
  name: Microsoft Office (WOPI)
  provider: microsoft-office
  says: lists Microsoft Office (WOPI) as an integration
  source: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id005
      status: unchecked
    slug: onlyoffice
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: common
  name: ONLYOFFICE
  provider: onlyoffice
  says: lists ONLYOFFICE as an integration
  source: https://raw.githubusercontent.com/owncloud/ocis/master/services/collaboration/README.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/owncloud-infinite-scale/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id001
  name: Collabora Online
  slug: collabora-online
  status: profiled
  tags: *id002
  url: /providers/collabora-online/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id003
  name: Microsoft Office (WOPI)
  slug: microsoft-office
  status: profiled
  tags: *id004
  url: /providers/microsoft-office/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: ONLYOFFICE
  slug: onlyoffice
  status: queued for profiling
  tags: *id006
  url: null
siblings:
- name: Box
  rows: 18
  url: /applications/cloud-storage-file-sync/box/
- name: Dropbox
  rows: 18
  url: /applications/cloud-storage-file-sync/dropbox/
- name: Filestash
  rows: 8
  url: /applications/cloud-storage-file-sync/filestash/
- name: Nextcloud
  rows: 32
  url: /applications/cloud-storage-file-sync/nextcloud/
- name: rclone
  rows: 71
  url: /applications/cloud-storage-file-sync/rclone/
- name: Seafile
  rows: 8
  url: /applications/cloud-storage-file-sync/seafile/
- name: Syncthing
  rows: 2
  url: /applications/cloud-storage-file-sync/syncthing/
sitemap: true
title: 'ownCloud Infinite Scale: Cloud Storage & File Sync reference app'
---
