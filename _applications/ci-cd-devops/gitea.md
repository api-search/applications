---
app: Gitea
app_slug: gitea
app_url: https://github.com/go-gitea/gitea
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.30
  key: release-engineering-management
  layer: domain
  name: Release Engineering Management
  providers:
  - Packagist webhook
  url: /capabilities/release-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - AWS CodeCommit (migrations/codecommit.go)
  - Bitbucket Server (migrations/bitbucketserver.go)
  - Codebase (migrations/codebase.go)
  - GitHub (go-github, migrations/github.go)
  - GitLab (migrations/gitlab.go)
  - OneDev (migrations/onedev.go)
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - DingTalk webhook
  - Discord webhook
  - Feishu webhook
  - MS Teams webhook
  - Slack webhook
  - Telegram webhook
  - WeChat Work (WeCom) webhook
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - goth azuread / microsoftonline
  - goth bitbucket
  - goth discord
  - goth dropbox
  - goth facebook
  - goth github
  - goth gitlab
  - goth google
  - goth twitter
  - goth yandex
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: ci-cd-devops
  name: Code Hosting, CI/CD & DevOps
  url: /applications/ci-cd-devops/
counts:
  declared: 0
  observed: 24
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/go-gitea/gitea/main/go.mod
- route: source code
  url: https://github.com/go-gitea/gitea/tree/main/services/migrations
- route: source code
  url: https://github.com/go-gitea/gitea/tree/main/services/webhook
- route: source code
  url: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
- route: source code
  url: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    agent_readiness: 37.3
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id005
      status: none
    slug: amazon-codecommit
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Cloud
    - Company
    - Version Control
    url: /providers/amazon-codecommit/
  layer: domain
  name: AWS CodeCommit (migrations/codecommit.go)
  provider: amazon-codecommit
  says: ships the AWS CodeCommit (migrations/codecommit.go) SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/migrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id007
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id008
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket Server (migrations/bitbucketserver.go)
  provider: bitbucket
  says: ships the Bitbucket Server (migrations/bitbucketserver.go) SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/migrations
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
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id009
      status: unknown
    slug: codebasehq
    status: profiled
    tags: &id010
    - Company
    - Mercurial
    - Subversion
    - Version Control
    url: /providers/codebasehq/
  layer: domain
  name: Codebase (migrations/codebase.go)
  provider: codebasehq
  says: ships the Codebase (migrations/codebase.go) SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/migrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id011
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id012
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: common
  name: DingTalk webhook
  provider: dingtalk
  says: ships the DingTalk webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id013
      status: none
    slug: discord
    status: profiled
    tags: &id014
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord webhook
  provider: discord
  says: ships the Discord webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: feishu
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: common
  name: Feishu webhook
  provider: feishu
  says: ships the Feishu webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: &id003
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id017
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id018
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub (go-github, migrations/github.go)
  provider: github
  says: ships the GitHub (go-github, migrations/github.go) SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/migrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: &id004
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id019
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id020
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab (migrations/gitlab.go)
  provider: gitlab
  says: ships the GitLab (migrations/gitlab.go) SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/migrations
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
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
  name: goth azuread / microsoftonline
  provider: microsoft-entra
  says: ships the goth azuread / microsoftonline SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: goth bitbucket
  provider: bitbucket
  says: ships the goth bitbucket SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: *id002
  layer: common
  name: goth discord
  provider: discord
  says: ships the goth discord SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id023
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id024
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: goth dropbox
  provider: dropbox
  says: ships the goth dropbox SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id025
      status: none
    slug: facebook
    status: profiled
    tags: &id026
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: goth facebook
  provider: facebook
  says: ships the goth facebook SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: *id003
  layer: common
  name: goth github
  provider: github
  says: ships the goth github SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: *id004
  layer: common
  name: goth gitlab
  provider: gitlab
  says: ships the goth gitlab SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_custom.go
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id027
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id028
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: goth google
  provider: google-identity-platform
  says: ships the goth google SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id029
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id030
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: goth twitter
  provider: x
  says: ships the goth twitter SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: yandex
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: common
  name: goth yandex
  provider: yandex
  says: ships the goth yandex SDK or integration code
  source: https://raw.githubusercontent.com/go-gitea/gitea/main/services/auth/source/oauth2/providers_simple.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id033
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id034
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: MS Teams webhook
  provider: microsoft-teams
  says: ships the MS Teams webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
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
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id035
      source: https://docs.onedev.io/tutorials/ai/working-with-mcp
      status: documented
    slug: onedev
    status: profiled
    tags: &id036
    - CI/CD
    - Company
    - Development
    - Version Control
    url: /providers/onedev/
  layer: domain
  name: OneDev (migrations/onedev.go)
  provider: onedev
  says: ships the OneDev (migrations/onedev.go) SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/migrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.6
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id037
      status: none
    slug: packagist
    status: profiled
    tags: &id038
    - Composer
    - Dependency Management
    - PHP
    - Package Registry
    url: /providers/packagist/
  layer: domain
  name: Packagist webhook
  provider: packagist
  says: ships the Packagist webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id039
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id040
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack webhook
  provider: slack
  says: ships the Slack webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id041
      status: none
    slug: telegram
    status: profiled
    tags: &id042
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram webhook
  provider: telegram
  says: ships the Telegram webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id043
      status: unchecked
    slug: wecom
    status: queued for profiling
    tags: &id044 []
    url: null
  layer: common
  name: WeChat Work (WeCom) webhook
  provider: wecom
  says: ships the WeChat Work (WeCom) webhook SDK or integration code
  source: https://github.com/go-gitea/gitea/tree/main/services/webhook
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ci-cd-devops/gitea/
providers:
- agent_band: agent-ready
  agent_readiness: 37.3
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id005
  name: AWS CodeCommit (migrations/codecommit.go)
  slug: amazon-codecommit
  status: profiled
  tags: *id006
  url: /providers/amazon-codecommit/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id007
  name: Bitbucket Server (migrations/bitbucketserver.go)
  slug: bitbucket
  status: profiled
  tags: *id008
  url: /providers/bitbucket/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id009
  name: Codebase (migrations/codebase.go)
  slug: codebasehq
  status: profiled
  tags: *id010
  url: /providers/codebasehq/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id011
  name: DingTalk webhook
  slug: dingtalk
  status: profiled
  tags: *id012
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id013
  name: Discord webhook
  slug: discord
  status: profiled
  tags: *id014
  url: /providers/discord/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Feishu webhook
  slug: feishu
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id017
  name: GitHub (go-github, migrations/github.go)
  slug: github
  status: profiled
  tags: *id018
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id019
  name: GitLab (migrations/gitlab.go)
  slug: gitlab
  status: profiled
  tags: *id020
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id021
  name: goth azuread / microsoftonline
  slug: microsoft-entra
  status: profiled
  tags: *id022
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id023
  name: goth dropbox
  slug: dropbox
  status: profiled
  tags: *id024
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id025
  name: goth facebook
  slug: facebook
  status: profiled
  tags: *id026
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id027
  name: goth google
  slug: google-identity-platform
  status: profiled
  tags: *id028
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id029
  name: goth twitter
  slug: x
  status: profiled
  tags: *id030
  url: /providers/x/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: goth yandex
  slug: yandex
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id033
  name: MS Teams webhook
  slug: microsoft-teams
  status: profiled
  tags: *id034
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id035
  name: OneDev (migrations/onedev.go)
  slug: onedev
  status: profiled
  tags: *id036
  url: /providers/onedev/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id037
  name: Packagist webhook
  slug: packagist
  status: profiled
  tags: *id038
  url: /providers/packagist/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id039
  name: Slack webhook
  slug: slack
  status: profiled
  tags: *id040
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id041
  name: Telegram webhook
  slug: telegram
  status: profiled
  tags: *id042
  url: /providers/telegram/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id043
  name: WeChat Work (WeCom) webhook
  slug: wecom
  status: queued for profiling
  tags: *id044
  url: null
siblings:
- name: CircleCI
  rows: 54
  url: /applications/ci-cd-devops/circleci/
- name: Coolify
  rows: 21
  url: /applications/ci-cd-devops/coolify/
- name: GitHub
  rows: 6
  url: /applications/ci-cd-devops/github/
- name: GitLab
  rows: 54
  url: /applications/ci-cd-devops/gitlab/
- name: Woodpecker CI
  rows: 3
  url: /applications/ci-cd-devops/woodpecker-ci/
sitemap: true
title: 'Gitea: Code Hosting, CI/CD & DevOps reference app'
---
