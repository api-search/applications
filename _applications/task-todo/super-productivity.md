---
app: Super Productivity
app_slug: super-productivity
app_url: https://github.com/super-productivity/super-productivity
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: domain
  name: Personal Task & To-Do Lists
  providers:
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
  - Azure DevOps
  - ClickUp
  - Gitea
  - GitHub
  - GitLab
  - Jira
  - Linear
  - Nextcloud Deck
  - OpenProject
  - Redmine
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: task-todo
  name: Tasks & To-do Lists
  url: /applications/task-todo/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
- route: source code
  url: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
- route: source code
  url: https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
integrations:
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
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id001
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id002
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure DevOps
  provider: microsoft-azure-devops
  says: ships the Azure DevOps SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_readiness: 57.0
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id003
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id004
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: domain
  name: ClickUp
  provider: clickup
  says: ships the ClickUp SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id005
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
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
    agent_readiness: 31.0
    band: exemplar
    in_catalog: true
    kin_score: 69.8
    mcp: &id007
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id008
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
  layer: domain
  name: Gitea
  provider: gitea
  says: ships the Gitea SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id009
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id011
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id014
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id015
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id016
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
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
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id017
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id018
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: ships the Linear SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id019
      status: none
    slug: nextcloud
    status: profiled
    tags: &id020
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud Deck
  provider: nextcloud
  says: ships the Nextcloud Deck SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id021
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id022
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: ships the OneDrive SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
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
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 42.1
    mcp: &id023
      source: https://www.openproject.org/docs/system-admin-guide/integrations/mcp-server/
      status: verified
    slug: openproject
    status: profiled
    tags: &id024
    - Agile
    - Gantt
    - Open Source
    - Project Management
    url: /providers/openproject/
  layer: domain
  name: OpenProject
  provider: openproject
  says: ships the OpenProject SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
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
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id025
      status: none
    slug: redmine
    status: profiled
    tags: &id026
    - Issue Tracking
    - Open Source
    - Project Management
    - Ruby on Rails
    url: /providers/redmine/
  layer: domain
  name: Redmine
  provider: redmine
  says: ships the Redmine SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    mcp: &id027
      source: https://help.ticktick.com/articles/7438129581631995904
      status: verified
    slug: ticktick
    status: profiled
    tags: &id028
    - Calendar
    - Company
    - Productivity
    - Task Management
    url: /providers/ticktick/
  layer: domain
  name: TickTick
  provider: ticktick
  says: ships the TickTick SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    mcp: &id029
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id030
    - Productivity
    - Task
    - Task Management
    - To-Do
    url: /providers/todoist/
  layer: domain
  name: Todoist
  provider: todoist
  says: ships the Todoist SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    mcp: &id031
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id032
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: Trello
  provider: trello
  says: ships the Trello SDK or integration code
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/task-todo/super-productivity/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id001
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id002
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 57.0
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id003
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id004
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id005
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id006
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: exemplar
  in_catalog: true
  kin_score: 69.8
  mcp: *id007
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id008
  url: /providers/gitea/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id011
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id012
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id013
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id014
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id015
  name: Jira
  slug: jira
  status: profiled
  tags: *id016
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id017
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id018
  url: /providers/linear-app/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id019
  name: Nextcloud Deck
  slug: nextcloud
  status: profiled
  tags: *id020
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id021
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id022
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 42.1
  mcp: *id023
  name: OpenProject
  slug: openproject
  status: profiled
  tags: *id024
  url: /providers/openproject/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id025
  name: Redmine
  slug: redmine
  status: profiled
  tags: *id026
  url: /providers/redmine/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id027
  name: TickTick
  slug: ticktick
  status: profiled
  tags: *id028
  url: /providers/ticktick/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id029
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id030
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id031
  name: Trello
  slug: trello
  status: profiled
  tags: *id032
  url: /providers/trello/
siblings:
- name: Donetick
  rows: 4
  url: /applications/task-todo/donetick/
- name: Tasks.org
  rows: 8
  url: /applications/task-todo/tasks-org/
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
title: 'Super Productivity: Tasks & To-do Lists reference app'
---
