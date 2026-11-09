---
app: OpenProject (BIM)
app_slug: openproject-bim
app_url: https://www.openproject.org/bim-project-management/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1120.50
  key: design-software-cad-management
  layer: domain
  name: Design Software & CAD Management
  providers:
  - Revit (add-in)
  url: /capabilities/design-software-cad-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Nextcloud
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: common
  name: Enterprise Content & Document Management
  providers:
  - SharePoint
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - XWiki
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
category:
  id: construction-management
  name: Construction Management
  url: /applications/construction-management/
counts:
  declared: 7
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.openproject.org/bim-project-management/
- route: documentation
  url: https://www.openproject.org/docs/system-admin-guide/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id001
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id002
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id003
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id004
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id005
      status: none
    slug: nextcloud
    status: profiled
    tags: &id006
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: common
  name: Nextcloud
  provider: nextcloud
  says: lists Nextcloud as an integration
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
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
    mcp: &id007
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id008
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1120.50
    key: design-software-cad-management
    name: Design Software & CAD Management
    url: /capabilities/design-software-cad-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.1
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id009
      source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
      status: verified
    slug: autodesk
    status: profiled
    tags: &id010
    - 3D Modeling
    - Autodesk
    - Digital Twin
    - Fortune 1000
    url: /providers/autodesk/
  layer: domain
  name: Revit (add-in)
  provider: autodesk
  says: lists Revit (add-in) as an integration
  source: https://www.openproject.org/bim-project-management/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id012
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: common
  name: SharePoint
  provider: sharepoint
  says: lists SharePoint as an integration
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.8
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id013
      source: https://github.com/xwiki-contrib/ai-llm
      status: verified
    slug: xwiki
    status: profiled
    tags: &id014
    - Company
    - Enterprise
    - Open Source
    - Wiki
    url: /providers/xwiki/
  layer: common
  name: XWiki
  provider: xwiki
  says: lists XWiki as an integration
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/openproject-bim/
providers:
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id001
  name: GitHub
  slug: github
  status: profiled
  tags: *id002
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id003
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id004
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id005
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id006
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id007
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id008
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 43.1
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id009
  name: Revit (add-in)
  slug: autodesk
  status: profiled
  tags: *id010
  url: /providers/autodesk/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id011
  name: SharePoint
  slug: sharepoint
  status: profiled
  tags: *id012
  url: /providers/sharepoint/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id013
  name: XWiki
  slug: xwiki
  status: profiled
  tags: *id014
  url: /providers/xwiki/
siblings:
- name: CompanyCam
  rows: 15
  url: /applications/construction-management/companycam/
- name: JobTread
  rows: 11
  url: /applications/construction-management/jobtread/
- name: Knowify
  rows: 9
  url: /applications/construction-management/knowify/
- name: Procore
  rows: 12
  url: /applications/construction-management/procore/
- name: Raken
  rows: 21
  url: /applications/construction-management/raken/
- name: Siteline
  rows: 11
  url: /applications/construction-management/siteline/
sitemap: true
title: 'OpenProject (BIM): Construction Management reference app'
---
