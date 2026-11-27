---
access: understanding
agent_layer:
- app: OpenProject
  finding: ships its own MCP server (mcp gem; docs page integrations/mcp-server)
  source: https://www.openproject.org/docs/system-admin-guide/integrations/
  tier: declared
- app: OpenProject
  finding: mcp ~> 1.7 gem in Gemfile
  source: https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
  tier: observed
- app: Leantime
  finding: laravel/mcp in composer.json (own MCP server)
  source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
  tier: observed
- app: Vikunja
  finding: pkg/modules/mcp + McpClientGuide.vue (own MCP server)
  source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/mcp
  tier: observed
- app: Plane
  finding: 'BYO LLM: OpenAI, Anthropic, Gemini provider classes'
  source: https://github.com/makeplane/plane/blob/preview/apps/api/plane/app/views/external/base.py
  tier: observed
apps:
- anchor: plane
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
  - route: dependency manifest
    url: https://raw.githubusercontent.com/makeplane/plane/preview/apps/web/package.json
  - route: source code
    url: https://github.com/makeplane/plane/blob/preview/apps/api/plane/app/views/external/base.py
  - route: source code
    url: https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
  - route: source code
    url: https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/plane/settings/common.py
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/makeplane/plane/blob/preview/apps/api/plane/app/views/external/base.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/makeplane/plane/blob/preview/apps/api/plane/app/views/external/base.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Scout APM
    provider: scout-apm
    says: ships the Scout APM SDK or integration code
    source: https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
    tier: observed
  kind: open-source-saas
  name: Plane
  page: /applications/project-management/plane/
  slug: plane
  url: https://github.com/makeplane/plane
- anchor: openproject
  counts:
    declared: 3
    observed: 12
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
    layer: domain
    name: XWiki
    provider: xwiki
    says: lists XWiki as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  kind: self-hosted
  name: OpenProject
  page: /applications/project-management/openproject/
  slug: openproject
  url: https://github.com/opf/openproject
- anchor: taiga
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements-contribs.txt
  - route: dependency manifest
    url: https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements.txt
  - route: source code
    url: https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
  - route: source code
    url: https://github.com/taigaio/taiga-back/tree/main/taiga/importers
  - route: source code
    url: https://raw.githubusercontent.com/taigaio/taiga-back/main/taiga/telemetry/tasks.py
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: ships the Asana SDK or integration code
    source: https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: ships the Bitbucket SDK or integration code
    source: https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gogs
    provider: gogs
    says: ships the Gogs SDK or integration code
    source: https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/taigaio/taiga-back/tree/main/taiga/importers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: RudderStack
    provider: rudderstack
    says: ships the RudderStack SDK or integration code
    source: https://raw.githubusercontent.com/taigaio/taiga-back/main/taiga/telemetry/tasks.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements-contribs.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: ships the Trello SDK or integration code
    source: https://github.com/taigaio/taiga-back/tree/main/taiga/importers
    tier: observed
  kind: self-hosted
  name: Taiga
  page: /applications/project-management/taiga/
  slug: taiga
  url: https://github.com/taigaio/taiga-back
- anchor: vikunja
  counts:
    declared: 0
    observed: 8
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
    layer: common
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background/unsplash
    tier: observed
  kind: self-hosted
  name: Vikunja
  page: /applications/project-management/vikunja/
  slug: vikunja
  url: https://github.com/go-vikunja/vikunja
- anchor: leantime
  counts:
    declared: 0
    observed: 15
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Auth0
    provider: auth0
    says: ships the Auth0 SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: authentik
    provider: authentik
    says: ships the authentik SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Crisp
    provider: crisp
    says: ships the Crisp SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Keycloak
    provider: keycloak
    says: ships the Keycloak SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: PropelAuth
    provider: propelauth
    says: ships the PropelAuth SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: common
    name: Qdrant
    provider: qdrant
    says: ships the Qdrant SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
    tier: observed
  kind: self-hosted
  name: Leantime
  page: /applications/project-management/leantime/
  slug: leantime
  url: https://github.com/Leantime/leantime
- anchor: jira-(android)
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
    tier: observed
  kind: commercial
  name: Jira (Android)
  page: /applications/project-management/jira-android/
  slug: jira-android
  url: https://www.atlassian.com/software/jira
- anchor: asana
  counts:
    declared: 19
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
  - route: integrations page
    url: https://asana.com/apps
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Analytics/Crashlytics)
    provider: firebase
    says: ships the Firebase (Analytics/Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    credit: null
    layer: common
    name: Loom
    provider: loom
    says: lists Loom as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Power BI
    provider: power-bi
    says: lists Power BI as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Tableau
    provider: tableau
    says: lists Tableau as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://asana.com/apps
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://asana.com/apps
    tier: declared
  kind: commercial
  name: Asana
  page: /applications/project-management/asana/
  slug: asana
  url: https://asana.com/
- anchor: trello-(android)
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.trello/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Analytics/Crashlytics)
    provider: firebase
    says: ships the Firebase (Analytics/Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.trello/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.trello/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.trello/latest/
    tier: observed
  kind: commercial
  name: Trello (Android)
  page: /applications/project-management/trello-android/
  slug: trello-android
  url: https://trello.com/
- anchor: mondaycom-(android)
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Analytics/Crashlytics)
    provider: firebase
    says: ships the Firebase (Analytics/Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
    tier: observed
  kind: commercial
  name: monday.com (Android)
  page: /applications/project-management/monday-com-android/
  slug: monday-com-android
  url: https://monday.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: project-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Software Development - Project Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---project-management
- category: Task Management & To-do Lists
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#task-management--to-do-lists
- category: Project Management
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Project Management
  store: slack-marketplace
  url: https://slack.com/apps
- category: Project Management
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Project Management
  store: zapier
  url: https://zapier.com/apps
name: Project & Work Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: the category itself; importers/sync with other PM tools (Asana, Jira, Trello, Todoist, MS To Do)
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: source-control webhooks and issue linking (GitHub, GitLab, Bitbucket, Gitea, Gogs)
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: chat/meeting notifications (Slack, Zoom, Loom, Gmail, Outlook, Pusher realtime)
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: file storage links (Nextcloud, OneDrive, SharePoint, Google Drive, Dropbox, Box)
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: wiki integration (XWiki)
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: SSO/OIDC sign-in
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring + APM
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: mobile + product telemetry
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: nearest
  layer: common
  why: attachments, backgrounds, avatars
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: captcha on sign-up/login
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: agent
  why: BYO LLM keys for AI features; vector store
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: SaaS billing (Leantime cloud)
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app support chat; helpdesk links
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CRM sync from marketplace
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: BI dashboards on work data
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: calendar sync
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile install attribution
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: domain
  why: design file embeds (Figma)
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: iPaaS connectors (Zapier); no BC capability fits
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Asana
      - Leantime
      - OpenProject
      - Plane
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://asana.com/apps
      - https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
      - https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Asana
      - Leantime
      - OpenProject
      - Plane
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://asana.com/apps
      - https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
      - https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Leantime
      - Plane
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - Taiga
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Gogs
      slug: gogs
      sources:
      - https://github.com/taigaio/taiga-back/tree/main/taiga/hooks
      status: profiled
      tags:
      - Company
      - Open Source
      - Self-Hosted
      - Version Control
      tier: observed
      url: /providers/gogs/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Asana
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://asana.com/apps
      - https://github.com/taigaio/taiga-back/tree/main/taiga/importers
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Taiga
      - Vikunja
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://github.com/taigaio/taiga-back/tree/main/taiga/importers
      - https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: observed
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements.txt
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: observed
      url: /providers/asana/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Asana
      - Plane
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://asana.com/apps
      - https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
      - https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements-contribs.txt
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Vikunja
      band: strong
      in_catalog: true
      kin_score: 58.2
      mcp:
        status: none
      name: Microsoft To Do
      slug: microsoft-to-do
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      status: profiled
      tags:
      - Microsoft
      - Microsoft 365
      - Productivity
      - Task
      tier: observed
      url: /providers/microsoft-to-do/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Vikunja
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        source: https://developer.todoist.com/api/v1/#tag/MCP
        status: verified
      name: Todoist
      slug: todoist
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      status: profiled
      tags:
      - Productivity
      - Task
      - Task Management
      - To-Do
      tier: observed
      url: /providers/todoist/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Vikunja
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        source: https://help.ticktick.com/articles/7438129581631995904
        status: verified
      name: TickTick
      slug: ticktick
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      status: profiled
      tags:
      - Calendar
      - Company
      - Productivity
      - Task Management
      tier: observed
      url: /providers/ticktick/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - OpenProject
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        source: https://github.com/xwiki-contrib/ai-llm
        status: verified
      name: XWiki
      slug: xwiki
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      status: profiled
      tags:
      - Company
      - Enterprise
      - Open Source
      - Wiki
      tier: declared
      url: /providers/xwiki/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.2
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: declared
      url: /providers/figma/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Leantime
      - OpenProject
      - Plane
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/makeplane/plane/tree/preview/apps/api/plane/authentication/provider/oauth
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      - https://raw.githubusercontent.com/opf/openproject/dev/modules/openid_connect/app/models/openid_connect/provider.rb
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Leantime
      - OpenProject
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      - https://raw.githubusercontent.com/opf/openproject/dev/modules/openid_connect/app/models/openid_connect/provider.rb
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Leantime
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Leantime
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: authentik
      slug: authentik
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: observed
      url: /providers/authentik/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Leantime
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: observed
      url: /providers/auth0/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Leantime
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        status: none
      name: PropelAuth
      slug: propelauth
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Authentication
      - B2B
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/propelauth/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Leantime
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: observed
      url: /providers/keycloak/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Jira (Android)
      - Leantime
      - Taiga
      - Trello (Android)
      - Vikunja
      - monday.com (Android)
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      - https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
      - https://raw.githubusercontent.com/taigaio/taiga-back/main/requirements.txt
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - OpenProject
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        source: https://github.com/appsignal/appsignal-mcp
        status: verified
      name: AppSignal
      slug: appsignal
      sources:
      - https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
      status: profiled
      tags:
      - Error Tracking
      - Monitoring
      - Observability
      - Performance
      tier: observed
      url: /providers/appsignal/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Plane
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp:
        source: https://github.com/scoutapp/scout-mcp-local
        status: verified
      name: Scout APM
      slug: scout-apm
      sources:
      - https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
      status: profiled
      tags:
      - AI-assisted
      - APM
      - Company
      - Monitoring
      tier: observed
      url: /providers/scout-apm/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - OpenProject
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: none
      name: Airbrake
      slug: airbrake
      sources:
      - https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
      status: profiled
      tags:
      - Application Performance Monitoring
      - DevOps
      - Error Monitoring
      - Observability
      tier: observed
      url: /providers/airbrake/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Asana
      - Trello (Android)
      - monday.com (Android)
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Analytics/Crashlytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.trello/latest/
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Asana
      - Jira (Android)
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Jira (Android)
      - Trello (Android)
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.trello/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Taiga
      band: exemplar
      in_catalog: true
      kin_score: 79.1
      mcp:
        source: https://github.com/rudderlabs/rudderstack-mcp
        status: verified
      name: RudderStack
      slug: rudderstack
      sources:
      - https://raw.githubusercontent.com/taigaio/taiga-back/main/taiga/telemetry/tasks.py
      status: profiled
      tags:
      - CDP
      - Customer Data Platform
      - Data Pipeline
      - Open Source
      tier: observed
      url: /providers/rudderstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - OpenProject
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft SharePoint
      slug: sharepoint
      sources:
      - https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: observed
      url: /providers/sharepoint/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - OpenProject
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - OpenProject
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Nextcloud
      slug: nextcloud
      sources:
      - https://github.com/opf/openproject/tree/dev/modules/storages/app/models/storages
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Asana
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Asana
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - OpenProject
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - OpenProject
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - OpenProject
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/opf/openproject/dev/modules/recaptcha/lib/open_project/recaptcha.rb
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - OpenProject
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail API
      slug: google-gmail
      sources:
      - https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Outlook
      slug: microsoft-outlook
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Asana
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Leantime
      - OpenProject
      - Vikunja
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      - https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
      - https://raw.githubusercontent.com/opf/openproject/dev/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/powerbi-modeling-mcp
        status: verified
      name: Power BI
      slug: power-bi
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Analysis
      tier: declared
      url: /providers/power-bi/
    - agent_band: agent-ready
      agent_readiness: 55.0
      apps:
      - Asana
      band: developing
      in_catalog: true
      kin_score: 49.9
      mcp:
        source: https://github.com/tableau/tableau-mcp
        status: verified
      name: Tableau
      slug: tableau
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Visualization
      tier: declared
      url: /providers/tableau/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Leantime
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: Crisp
      slug: crisp
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Live Chat
      - Messaging
      tier: observed
      url: /providers/crisp/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Asana
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: Loom
      slug: loom
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Async
      - Communications
      - Productivity
      - Video
      tier: declared
      url: /providers/loom/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Vikunja
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/avatar/gravatar
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 70.0
      apps:
      - Asana
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.6
      apps:
      - Vikunja
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background/unsplash
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - monday.com (Android)
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Leantime
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - monday.com (Android)
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.monday.monday/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Asana
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.asana.app/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Leantime
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/qdrant/mcp-server-qdrant
        status: verified
      name: Qdrant
      slug: qdrant
      sources:
      - https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Database
      - Vector Search
      tier: observed
      url: /providers/qdrant/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Asana
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://asana.com/apps
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  layer: common
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Plane
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/makeplane/plane/blob/preview/apps/api/plane/app/views/external/base.py
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Plane
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/makeplane/plane/preview/apps/api/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Plane
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/makeplane/plane/blob/preview/apps/api/plane/app/views/external/base.py
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 16
  distinct_providers: 62
  in_catalog: 62
  mcp:
    documented: 0
    none: 20
    unchecked: 0
    verified: 42
  mcp_verified: 42
  mean_kin_score: 60.7
  observed: 46
  queued: 0
  reference_apps: 9
title: 'Project & Work Management: application blueprint'
---
