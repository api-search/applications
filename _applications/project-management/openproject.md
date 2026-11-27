---
app: OpenProject
app_slug: openproject
app_url: https://github.com/opf/openproject
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: domain
  name: Knowledge Sharing & Collaboration Management
  providers:
  - XWiki
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  - Google reCAPTCHA
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Microsoft OneDrive
  - Microsoft SharePoint
  - Nextcloud
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail API
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Airbrake
  - AppSignal
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
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Google sign-in
  - Microsoft Entra ID
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: project-management
  name: Project & Work Management
  url: /applications/project-management/
counts:
  declared: 3
  observed: 12
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
- route: documentation
  url: https://www.openproject.org/docs/system-admin-guide/integrations/
- route: source code
  url: https://github.com/opf/openproject/tree/dev/modules/llm
- route: source code
  url: https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
- route: source code
  url: https://raw.githubusercontent.com/opf/openproject/dev/modules/openid_connect/app/models/openid_connect/provider.rb
- route: source code
  url: https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
integrations:
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
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 25.8
    mcp: &id001
      status: none
    slug: airbrake
    status: profiled
    tags: &id002
    - Application Performance Monitoring
    - DevOps
    - Error Monitoring
    - Observability
    url: /providers/airbrake/
  layer: common
  name: Airbrake
  provider: airbrake
  says: ships the Airbrake SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
  tier: observed
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
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
    agent_readiness: 36.0
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id005
      source: https://github.com/appsignal/appsignal-mcp
      status: verified
    slug: appsignal
    status: profiled
    tags: &id006
    - Error Tracking
    - Monitoring
    - Observability
    - Performance
    url: /providers/appsignal/
  layer: common
  name: AppSignal
  provider: appsignal
  says: ships the AppSignal SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
  tier: observed
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
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id007
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id008
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
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
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id013
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id014
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail API
  provider: google-gmail
  says: ships the Gmail API SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id015
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id016
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id017
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id018
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/modules/openid_connect/app/models/openid_connect/provider.rb
  tier: observed
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
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id019
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id020
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id021
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id022
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://raw.githubusercontent.com/opf/openproject/dev/modules/openid_connect/app/models/openid_connect/provider.rb
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
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id023
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id024
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: ships the Microsoft OneDrive SDK or integration code
  source: https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
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
    agent_readiness: 32.3
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id025
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id026
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: common
  name: Microsoft SharePoint
  provider: sharepoint
  says: ships the Microsoft SharePoint SDK or integration code
  source: https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id027
      status: none
    slug: nextcloud
    status: profiled
    tags: &id028
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: common
  name: Nextcloud
  provider: nextcloud
  says: ships the Nextcloud SDK or integration code
  source: https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
  tier: observed
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
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
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
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
  says: lists GitLab as an integration
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
    agent_readiness: 10.6
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id029
      source: https://github.com/xwiki-contrib/ai-llm
      status: verified
    slug: xwiki
    status: profiled
    tags: &id030
    - Company
    - Enterprise
    - Open Source
    - Wiki
    url: /providers/xwiki/
  layer: domain
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
permalink: /applications/project-management/openproject/
providers:
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 25.8
  mcp: *id001
  name: Airbrake
  slug: airbrake
  status: profiled
  tags: *id002
  url: /providers/airbrake/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id005
  name: AppSignal
  slug: appsignal
  status: profiled
  tags: *id006
  url: /providers/appsignal/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id007
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id008
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id011
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id012
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id013
  name: Gmail API
  slug: google-gmail
  status: profiled
  tags: *id014
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id015
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id016
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id017
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id018
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id019
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id020
  url: /providers/hcaptcha/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id021
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id022
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id023
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id024
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id025
  name: Microsoft SharePoint
  slug: sharepoint
  status: profiled
  tags: *id026
  url: /providers/sharepoint/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id027
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id028
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id029
  name: XWiki
  slug: xwiki
  status: profiled
  tags: *id030
  url: /providers/xwiki/
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
- name: Plane
  rows: 9
  url: /applications/project-management/plane/
- name: Taiga
  rows: 10
  url: /applications/project-management/taiga/
- name: Trello (Android)
  rows: 3
  url: /applications/project-management/trello-android/
- name: Vikunja
  rows: 8
  url: /applications/project-management/vikunja/
sitemap: true
title: 'OpenProject: Project & Work Management reference app'
---
