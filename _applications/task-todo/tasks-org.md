---
app: Tasks.org
app_slug: tasks-org
app_url: https://github.com/tasks/tasks
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: domain
  name: Personal Task & To-Do Lists
  providers:
  - EteSync
  - Google Tasks
  - Microsoft To Do
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Google Play Billing
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20
  key: AE-120.20
  layer: common
  name: Maps & Tiles
  providers:
  - Google Maps
  - OpenStreetMap
  url: /capabilities/maps-tiles/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: task-todo
  name: Tasks & To-do Lists
  url: /applications/task-todo/
counts:
  declared: 0
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.tasks/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-923
    key: AE-923
    name: Personal Task & To-Do Lists
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id001
      status: none
    slug: etesync
    status: profiled
    tags: &id002
    - Company
    - Privacy
    - Security
    - Sync
    url: /providers/etesync/
  layer: domain
  name: EteSync
  provider: etesync
  says: ships the EteSync SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id004
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
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
    mcp: &id005
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id007
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id008
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id009
      status: none
    slug: google-play
    status: profiled
    tags: &id010
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play Billing
  provider: google-play
  says: ships the Google Play Billing SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-923
    key: AE-923
    name: Personal Task & To-Do Lists
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 47.0
    mcp: &id011
      status: none
    slug: google-tasks
    status: profiled
    tags: &id012
    - Google
    - Productivity
    - Task
    - Task Management
    url: /providers/google-tasks/
  layer: domain
  name: Google Tasks
  provider: google-tasks
  says: ships the Google Tasks SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-923
    key: AE-923
    name: Personal Task & To-Do Lists
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 52.8
    mcp: &id013
      status: none
    slug: microsoft-to-do
    status: profiled
    tags: &id014
    - Microsoft
    - Microsoft 365
    - Productivity
    - Task
    url: /providers/microsoft-to-do/
  layer: domain
  name: Microsoft To Do
  provider: microsoft-to-do
  says: ships the Microsoft To Do SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id015
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id016
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: common
  name: OpenStreetMap
  provider: openstreetmap
  says: ships the OpenStreetMap SDK or integration code
  source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/task-todo/tasks-org/
providers:
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id001
  name: EteSync
  slug: etesync
  status: profiled
  tags: *id002
  url: /providers/etesync/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id003
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id004
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id005
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id006
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id007
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id008
  url: /providers/google-maps/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id009
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id010
  url: /providers/google-play/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id011
  name: Google Tasks
  slug: google-tasks
  status: profiled
  tags: *id012
  url: /providers/google-tasks/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 52.8
  mcp: *id013
  name: Microsoft To Do
  slug: microsoft-to-do
  status: profiled
  tags: *id014
  url: /providers/microsoft-to-do/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id015
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id016
  url: /providers/openstreetmap/
siblings:
- name: Donetick
  rows: 4
  url: /applications/task-todo/donetick/
- name: Super Productivity
  rows: 16
  url: /applications/task-todo/super-productivity/
- name: TickTick
  rows: 14
  url: /applications/task-todo/ticktick/
- name: Todoist
  rows: 32
  url: /applications/task-todo/todoist/
- name: Vikunja
  rows: 8
  url: /applications/task-todo/vikunja/
sitemap: true
title: 'Tasks.org: Tasks & To-do Lists reference app'
---
