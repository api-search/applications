---
app: Coolify
app_slug: coolify
app_url: https://github.com/coollabsio/coolify
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: domain
  name: Configuration & Secrets Management
  providers:
  - DopplerService
  - InfisicalService
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: domain
  name: IT Infrastructure Management
  providers:
  - DigitalOceanService
  - HetznerService
  - HostingerService
  - VultrService
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GithubApp / GithubRunner
  - GitlabApp
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - DiscordChannel
  - SlackChannel
  - TelegramChannel
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2600.20
  key: network-configuration-management
  layer: common
  name: Network Configuration Management
  providers:
  - CloudflareTunnelService / CloudflareTokenValidator
  url: /capabilities/network-configuration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - stripe/stripe-php
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - PushoverChannel
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - socialiteproviders/clerk
  - socialiteproviders/discord
  - socialiteproviders/google
  - socialiteproviders/infomaniak
  - socialiteproviders/microsoft-azure
  - socialiteproviders/zitadel
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - resend/resend-laravel
  url: /capabilities/email/
  via_parent: Email
category:
  id: ci-cd-devops
  name: Code Hosting, CI/CD & DevOps
  url: /applications/ci-cd-devops/
counts:
  declared: 0
  observed: 21
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
- route: source code
  url: https://github.com/coollabsio/coolify/tree/main/app/Models
- route: source code
  url: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
- route: source code
  url: https://github.com/coollabsio/coolify/tree/main/app/Services
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2600.20
    key: network-configuration-management
    name: Network Configuration Management
    url: /capabilities/network-configuration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id002
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id003
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: CloudflareTunnelService / CloudflareTokenValidator
  provider: cloudflare
  says: ships the CloudflareTunnelService / CloudflareTokenValidator SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id004
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id005
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
  layer: domain
  name: DigitalOceanService
  provider: digital-ocean
  says: ships the DigitalOceanService SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id006
      status: none
    slug: discord
    status: profiled
    tags: &id007
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: DiscordChannel
  provider: discord
  says: ships the DiscordChannel SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id008
      source: https://github.com/DopplerHQ/mcp-server
      status: verified
    slug: doppler
    status: profiled
    tags: &id009
    - Configuration Management
    - DevOps
    - SecretOps
    - Secrets Management
    url: /providers/doppler/
  layer: domain
  name: DopplerService
  provider: doppler
  says: ships the DopplerService SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
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
    mcp: &id010
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id011
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GithubApp / GithubRunner
  provider: github
  says: ships the GithubApp / GithubRunner SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Models
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
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id012
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id013
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitlabApp
  provider: gitlab
  says: ships the GitlabApp SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Models
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id014
      status: none
    slug: hetzner
    status: profiled
    tags: &id015
    - Cloud Hosting
    - DNS
    - Infrastructure
    - Servers
    url: /providers/hetzner/
  layer: domain
  name: HetznerService
  provider: hetzner
  says: ships the HetznerService SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id016
      source: https://github.com/hostinger/api-mcp-server
      status: verified
    slug: hostinger
    status: profiled
    tags: &id017
    - Cloud
    - Company
    - Domains
    - Hosting
    url: /providers/hostinger/
  layer: domain
  name: HostingerService
  provider: hostinger
  says: ships the HostingerService SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id018
      source: https://github.com/Infisical/infisical-mcp-server
      status: verified
    slug: infisical
    status: profiled
    tags: &id019
    - DevOps
    - Developer Tools
    - Secrets Management
    - Security
    url: /providers/infisical/
  layer: domain
  name: InfisicalService
  provider: infisical
  says: ships the InfisicalService SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id020
      status: none
    slug: pushover
    status: profiled
    tags: &id021
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: PushoverChannel
  provider: pushover
  says: ships the PushoverChannel SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id022
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id023
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: resend/resend-laravel
  provider: resend
  says: ships the resend/resend-laravel SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id024
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id025
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: SlackChannel
  provider: slack
  says: ships the SlackChannel SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
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
    agent_readiness: 51.9
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id026
      source: https://github.com/clerk/mcp-tools
      status: verified
    slug: clerk-com
    status: profiled
    tags: &id027
    - Authentication
    - Authorization
    - B2B SaaS
    - CIAM
    url: /providers/clerk-com/
  layer: common
  name: socialiteproviders/clerk
  provider: clerk-com
  says: ships the socialiteproviders/clerk SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
  name: socialiteproviders/discord
  provider: discord
  says: ships the socialiteproviders/discord SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    mcp: &id028
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id029
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: socialiteproviders/google
  provider: google-identity-platform
  says: ships the socialiteproviders/google SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    agent_readiness: 13.4
    band: emerging
    in_catalog: true
    kin_score: 16.0
    mcp: &id030
      source: https://github.com/Infomaniak/mcp-server-kdrive
      status: verified
    slug: infomaniak
    status: profiled
    tags: &id031
    - Cloud
    - Company
    - Email
    - Hosting
    url: /providers/infomaniak/
  layer: common
  name: socialiteproviders/infomaniak
  provider: infomaniak
  says: ships the socialiteproviders/infomaniak SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    mcp: &id032
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id033
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: socialiteproviders/microsoft-azure
  provider: microsoft-entra
  says: ships the socialiteproviders/microsoft-azure SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id034
      status: none
    slug: zitadel
    status: profiled
    tags: &id035
    - Authentication
    - Authorization
    - Identity and Access Management
    - Open Source
    url: /providers/zitadel/
  layer: common
  name: socialiteproviders/zitadel
  provider: zitadel
  says: ships the socialiteproviders/zitadel SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id036
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id037
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: stripe/stripe-php
  provider: stripe
  says: ships the stripe/stripe-php SDK or integration code
  source: https://raw.githubusercontent.com/coollabsio/coolify/main/composer.json
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
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id038
      status: none
    slug: telegram
    status: profiled
    tags: &id039
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: TelegramChannel
  provider: telegram
  says: ships the TelegramChannel SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Notifications/Channels
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: developing
    in_catalog: true
    kin_score: 43.3
    mcp: &id040
      source: https://github.com/vultr/vultr-mcp
      status: verified
    slug: vultr
    status: profiled
    tags: &id041
    - Cloud
    - Company
    - Compute
    - Infrastructure
    url: /providers/vultr/
  layer: domain
  name: VultrService
  provider: vultr
  says: ships the VultrService SDK or integration code
  source: https://github.com/coollabsio/coolify/tree/main/app/Services
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ci-cd-devops/coolify/
providers:
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id002
  name: CloudflareTunnelService / CloudflareTokenValidator
  slug: cloudflare
  status: profiled
  tags: *id003
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id004
  name: DigitalOceanService
  slug: digital-ocean
  status: profiled
  tags: *id005
  url: /providers/digital-ocean/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id006
  name: DiscordChannel
  slug: discord
  status: profiled
  tags: *id007
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id008
  name: DopplerService
  slug: doppler
  status: profiled
  tags: *id009
  url: /providers/doppler/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id010
  name: GithubApp / GithubRunner
  slug: github
  status: profiled
  tags: *id011
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id012
  name: GitlabApp
  slug: gitlab
  status: profiled
  tags: *id013
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id014
  name: HetznerService
  slug: hetzner
  status: profiled
  tags: *id015
  url: /providers/hetzner/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id016
  name: HostingerService
  slug: hostinger
  status: profiled
  tags: *id017
  url: /providers/hostinger/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id018
  name: InfisicalService
  slug: infisical
  status: profiled
  tags: *id019
  url: /providers/infisical/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id020
  name: PushoverChannel
  slug: pushover
  status: profiled
  tags: *id021
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id022
  name: resend/resend-laravel
  slug: resend
  status: profiled
  tags: *id023
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id024
  name: SlackChannel
  slug: slack
  status: profiled
  tags: *id025
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 51.9
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id026
  name: socialiteproviders/clerk
  slug: clerk-com
  status: profiled
  tags: *id027
  url: /providers/clerk-com/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id028
  name: socialiteproviders/google
  slug: google-identity-platform
  status: profiled
  tags: *id029
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 13.4
  band: emerging
  in_catalog: true
  kin_score: 16.0
  mcp: *id030
  name: socialiteproviders/infomaniak
  slug: infomaniak
  status: profiled
  tags: *id031
  url: /providers/infomaniak/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id032
  name: socialiteproviders/microsoft-azure
  slug: microsoft-entra
  status: profiled
  tags: *id033
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id034
  name: socialiteproviders/zitadel
  slug: zitadel
  status: profiled
  tags: *id035
  url: /providers/zitadel/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id036
  name: stripe/stripe-php
  slug: stripe
  status: profiled
  tags: *id037
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id038
  name: TelegramChannel
  slug: telegram
  status: profiled
  tags: *id039
  url: /providers/telegram/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: developing
  in_catalog: true
  kin_score: 43.3
  mcp: *id040
  name: VultrService
  slug: vultr
  status: profiled
  tags: *id041
  url: /providers/vultr/
siblings:
- name: CircleCI
  rows: 54
  url: /applications/ci-cd-devops/circleci/
- name: Gitea
  rows: 24
  url: /applications/ci-cd-devops/gitea/
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
title: 'Coolify: Code Hosting, CI/CD & DevOps reference app'
---
