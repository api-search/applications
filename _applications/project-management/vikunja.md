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
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - Gravatar
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Unsplash
  url: /capabilities/media-asset-management/
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
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: project-management
  name: Project & Work Management
  url: /applications/project-management/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
- route: source code
  url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/avatar/gravatar
- route: source code
  url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background/unsplash
- route: source code
  url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id003
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id004
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
  layer: common
  name: Gravatar
  provider: gravatar
  says: ships the Gravatar SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/avatar/gravatar
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
    band: strong
    in_catalog: true
    kin_score: 58.2
    mcp: &id005
      status: none
    slug: microsoft-to-do
    status: profiled
    tags: &id006
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
    kin_score: 80.7
    mcp: &id007
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id008
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
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id009
      source: https://help.ticktick.com/articles/7438129581631995904
      status: verified
    slug: ticktick
    status: profiled
    tags: &id010
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
    agent_readiness: 22.2
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id011
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id012
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
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id013
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id014
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: Trello
  provider: trello
  says: ships the Trello SDK or integration code
  source: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id015
      status: none
    slug: unsplash
    status: profiled
    tags: &id016
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: common
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background/unsplash
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/project-management/vikunja/
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
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id003
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id004
  url: /providers/gravatar/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 58.2
  mcp: *id005
  name: Microsoft To Do
  slug: microsoft-to-do
  status: profiled
  tags: *id006
  url: /providers/microsoft-to-do/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id007
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id008
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id009
  name: TickTick
  slug: ticktick
  status: profiled
  tags: *id010
  url: /providers/ticktick/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id011
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id012
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id013
  name: Trello
  slug: trello
  status: profiled
  tags: *id014
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id015
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id016
  url: /providers/unsplash/
siblings:
- name: Asana
  rows: 22
  url: /applications/project-management/asana/
- name: Jira (Android)
  rows: 3
  url: /applications/project-management/jira-android/
- name: Leantime
  rows: 15
  url: /applications/project-management/leantime/
- name: monday.com (Android)
  rows: 4
  url: /applications/project-management/monday-com-android/
- name: OpenProject
  rows: 15
  url: /applications/project-management/openproject/
- name: Plane
  rows: 9
  url: /applications/project-management/plane/
- name: Taiga
  rows: 10
  url: /applications/project-management/taiga/
- name: Trello (Android)
  rows: 3
  url: /applications/project-management/trello-android/
sitemap: true
title: 'Vikunja: Project & Work Management reference app'
---
