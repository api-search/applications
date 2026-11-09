---
app: Ory Kratos
app_slug: ory-kratos
app_url: https://github.com/ory/kratos
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - DingTalk
  - Discord
  - Facebook
  - GitHub
  - GitLab
  - Google sign-in
  - Lark / Feishu
  - LINE
  - LinkedIn
  - Login with Amazon
  - netID
  - Patreon
  - Sign in with Apple
  - Slack
  - Spotify
  - UAE PASS
  - VK
  - X
  - Yandex ID
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Auth0
  - Microsoft
  - Salesforce
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: identity-access
  name: Identity, SSO & Access Management
  url: /applications/identity-access/
counts:
  declared: 0
  observed: 22
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/ory/kratos/master/go.mod
- route: source code
  url: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
integrations:
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id001
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id002
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: domain
  name: Auth0
  provider: auth0
  says: ships the Auth0 SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id003
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id004
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: domain
  name: DingTalk
  provider: dingtalk
  says: ships the DingTalk SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id005
      status: none
    slug: discord
    status: profiled
    tags: &id006
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
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
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
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
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id013
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id014
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id015
      source: https://github.com/larksuite/lark-openapi-mcp
      status: verified
    slug: larksuite
    status: profiled
    tags: &id016
    - Global Collaboration
    - No-code Workflow
    - Productivity
    - Team Collaboration
    url: /providers/larksuite/
  layer: domain
  name: Lark / Feishu
  provider: larksuite
  says: ships the Lark / Feishu SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 47.9
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id017
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id018
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id019
      status: none
    slug: linkedin
    status: profiled
    tags: &id020
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id021
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id022
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Login with Amazon
  provider: amazon
  says: ships the Login with Amazon SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
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
    mcp: &id023
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id024
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id025
      status: unknown
    slug: netid
    status: profiled
    tags: &id026
    - Authentication
    - Company
    - Identity
    - Login
    url: /providers/netid/
  layer: domain
  name: netID
  provider: netid
  says: ships the netID SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id027
      status: none
    slug: patreon
    status: profiled
    tags: &id028
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: domain
  name: Patreon
  provider: patreon
  says: ships the Patreon SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id029
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id030
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: ships the Salesforce SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id031
      status: none
    slug: apple
    status: profiled
    tags: &id032
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id033
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id034
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id035
      status: none
    slug: spotify
    status: profiled
    tags: &id036
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: emerging
    in_catalog: true
    kin_score: 19.4
    mcp: &id037
      status: none
    slug: uae-pass
    status: profiled
    tags: &id038
    - Authentication
    - Company
    - Identity
    - United Arab Emirates
    url: /providers/uae-pass/
  layer: domain
  name: UAE PASS
  provider: uae-pass
  says: ships the UAE PASS SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id039
      status: none
    slug: vk
    status: profiled
    tags: &id040
    - Public APIs
    - Social
    url: /providers/vk/
  layer: domain
  name: VK
  provider: vk
  says: ships the VK SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id041
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id042
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X
  provider: x
  says: ships the X SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id043
      status: unchecked
    slug: yandex
    status: queued for profiling
    tags: &id044 []
    url: null
  layer: domain
  name: Yandex ID
  provider: yandex
  says: ships the Yandex ID SDK or integration code
  source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/identity-access/ory-kratos/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id001
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id002
  url: /providers/auth0/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id003
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id004
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id005
  name: Discord
  slug: discord
  status: profiled
  tags: *id006
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id007
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
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
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id013
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id014
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id015
  name: Lark / Feishu
  slug: larksuite
  status: profiled
  tags: *id016
  url: /providers/larksuite/
- agent_band: agent-native
  agent_readiness: 47.9
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id017
  name: LINE
  slug: line
  status: profiled
  tags: *id018
  url: /providers/line/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id019
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id020
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id021
  name: Login with Amazon
  slug: amazon
  status: profiled
  tags: *id022
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id023
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id024
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id025
  name: netID
  slug: netid
  status: profiled
  tags: *id026
  url: /providers/netid/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id027
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id028
  url: /providers/patreon/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id029
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id030
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id031
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id032
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id033
  name: Slack
  slug: slack
  status: profiled
  tags: *id034
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id035
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id036
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: emerging
  in_catalog: true
  kin_score: 19.4
  mcp: *id037
  name: UAE PASS
  slug: uae-pass
  status: profiled
  tags: *id038
  url: /providers/uae-pass/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id039
  name: VK
  slug: vk
  status: profiled
  tags: *id040
  url: /providers/vk/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id041
  name: X
  slug: x
  status: profiled
  tags: *id042
  url: /providers/x/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id043
  name: Yandex ID
  slug: yandex
  status: queued for profiling
  tags: *id044
  url: null
siblings:
- name: Authelia
  rows: 1
  url: /applications/identity-access/authelia/
- name: Authentik
  rows: 20
  url: /applications/identity-access/authentik/
- name: Casdoor
  rows: 40
  url: /applications/identity-access/casdoor/
- name: Keycloak
  rows: 12
  url: /applications/identity-access/keycloak/
- name: Logto
  rows: 39
  url: /applications/identity-access/logto/
- name: Okta Verify
  rows: 3
  url: /applications/identity-access/okta-verify/
- name: Zitadel
  rows: 8
  url: /applications/identity-access/zitadel/
sitemap: true
title: 'Ory Kratos: Identity, SSO & Access Management reference app'
---
