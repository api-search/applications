---
app: Vikunja
app_slug: vikunja
app_url: https://github.com/go-vikunja/vikunja
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: domain
  name: Personal Task & To-Do Lists
  providers:
  - Microsoft To Do
  - TickTick
  - Todoist
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Planka
  - Trello
  - WeKan
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: common
  name: Photo & Image Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
category:
  id: task-todo
  name: Tasks & To-do Lists
  url: /applications/task-todo/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
- route: source code
  url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background
- route: source code
  url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 52.8
    mcp: &id001
      status: none
    slug: microsoft-to-do
    status: profiled
    tags: &id002
    - Microsoft
    - Microsoft 365
    - Productivity
    - Task
    url: /providers/microsoft-to-do/
  layer: domain
  name: Microsoft To Do
  provider: microsoft-to-do
  says: ships the Microsoft To Do SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 5.0
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id003
      status: none
    slug: planka
    status: profiled
    tags: &id004
    - Agile
    - Kanban
    - Project Management
    - Self-Hosted
    url: /providers/planka/
  layer: domain
  name: Planka
  provider: planka
  says: ships the Planka SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    mcp: &id005
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id006
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 17.6
    mcp: &id007
      source: https://help.ticktick.com/articles/7438129581631995904
      status: verified
    slug: ticktick
    status: profiled
    tags: &id008
    - Calendar
    - Company
    - Productivity
    - Task Management
    url: /providers/ticktick/
  layer: domain
  name: TickTick
  provider: ticktick
  says: ships the TickTick SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    agent_readiness: 22.6
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id009
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id010
    - Productivity
    - Task
    - Task Management
    - To-Do
    url: /providers/todoist/
  layer: domain
  name: Todoist
  provider: todoist
  says: ships the Todoist SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id011
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id012
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: Trello
  provider: trello
  says: ships the Trello SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 40.2
    mcp: &id013
      status: none
    slug: unsplash
    status: profiled
    tags: &id014
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: common
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: emerging
    in_catalog: true
    kin_score: 18.6
    mcp: &id015
      status: none
    slug: wekan
    status: profiled
    tags: &id016
    - Company
    url: /providers/wekan/
  layer: domain
  name: WeKan
  provider: wekan
  says: ships the WeKan SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/task-todo/vikunja/
providers:
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 52.8
  mcp: *id001
  name: Microsoft To Do
  slug: microsoft-to-do
  status: profiled
  tags: *id002
  url: /providers/microsoft-to-do/
- agent_band: human-only
  agent_readiness: 5.0
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id003
  name: Planka
  slug: planka
  status: profiled
  tags: *id004
  url: /providers/planka/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id007
  name: TickTick
  slug: ticktick
  status: profiled
  tags: *id008
  url: /providers/ticktick/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id009
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id010
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id011
  name: Trello
  slug: trello
  status: profiled
  tags: *id012
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 40.2
  mcp: *id013
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id014
  url: /providers/unsplash/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: emerging
  in_catalog: true
  kin_score: 18.6
  mcp: *id015
  name: WeKan
  slug: wekan
  status: profiled
  tags: *id016
  url: /providers/wekan/
siblings:
- name: Donetick
  rows: 4
  url: /applications/task-todo/donetick/
- name: Super Productivity
  rows: 16
  url: /applications/task-todo/super-productivity/
- name: Tasks.org
  rows: 8
  url: /applications/task-todo/tasks-org/
- name: TickTick
  rows: 14
  url: /applications/task-todo/ticktick/
- name: Todoist
  rows: 32
  url: /applications/task-todo/todoist/
sitemap: true
title: 'Vikunja: Tasks & To-do Lists reference app'
---
