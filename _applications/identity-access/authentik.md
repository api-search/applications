---
app: Authentik
app_slug: authentik
app_url: https://github.com/goauthentik/authentik
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: domain
  name: Identity & Access Management
  providers:
  - Google Workspace
  - Microsoft Graph
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.20
  key: AE-160.10.20
  layer: domain
  name: Multi-Factor Authentication
  providers:
  - Duo Security
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Discord
  - Facebook
  - GitHub
  - GitLab
  - Google sign-in
  - Patreon
  - Reddit
  - Sign in with Apple
  - Slack
  - Twitch
  - WeChat
  - X (Twitter)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind GeoIP2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
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
  id: AE-150.20.30
  key: AE-150.20.30
  layer: common
  name: One-Time Passcodes
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: identity-access
  name: Identity, SSO & Access Management
  url: /applications/identity-access/
counts:
  declared: 0
  observed: 20
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
- route: source code
  url: https://github.com/goauthentik/authentik/tree/main/authentik/enterprise/providers
- route: source code
  url: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
- route: source code
  url: https://raw.githubusercontent.com/goauthentik/authentik/main/authentik/stages/authenticator_sms/models.py
integrations:
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id001
      status: none
    slug: discord
    status: profiled
    tags: &id002
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id003
      status: none
    slug: duo-security
    status: profiled
    tags: &id004
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: domain
  name: Duo Security
  provider: duo-security
  says: ships the Duo Security SDK or integration code
  source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id007
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id008
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id009
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id013
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id014
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: domain
  name: Google Workspace
  provider: google-workspace
  says: ships the Google Workspace SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/enterprise/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id015
      status: none
    slug: maxmind
    status: profiled
    tags: &id016
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind GeoIP2
  provider: maxmind
  says: ships the MaxMind GeoIP2 SDK or integration code
  source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
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
    mcp: &id017
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id018
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id019
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id020
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: domain
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id021
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id022
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: ships the Okta SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id023
      status: none
    slug: patreon
    status: profiled
    tags: &id024
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: domain
  name: Patreon
  provider: patreon
  says: ships the Patreon SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 43.0
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id025
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id026
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: ships the Reddit SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    mcp: &id027
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id028
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id029
      status: none
    slug: apple
    status: profiled
    tags: &id030
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id033
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id034
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/goauthentik/authentik/main/authentik/stages/authenticator_sms/models.py
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
    agent_readiness: 36.9
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id035
      status: none
    slug: twitch
    status: profiled
    tags: &id036
    - Entertainment
    - Gaming
    - Live Streaming
    - Streaming
    url: /providers/twitch/
  layer: domain
  name: Twitch
  provider: twitch
  says: ships the Twitch SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id037
      status: none
    slug: wechat
    status: profiled
    tags: &id038
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeChat
  provider: wechat
  says: ships the WeChat SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id039
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id040
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/identity-access/authentik/
providers:
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id001
  name: Discord
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id003
  name: Duo Security
  slug: duo-security
  status: profiled
  tags: *id004
  url: /providers/duo-security/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id007
  name: GitHub
  slug: github
  status: profiled
  tags: *id008
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id009
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id010
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id013
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id014
  url: /providers/google-workspace/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id015
  name: MaxMind GeoIP2
  slug: maxmind
  status: profiled
  tags: *id016
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id017
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id018
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id019
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id020
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id021
  name: Okta
  slug: okta
  status: profiled
  tags: *id022
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id023
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id024
  url: /providers/patreon/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id025
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id026
  url: /providers/reddit/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id027
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id028
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id029
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id030
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id033
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id034
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id035
  name: Twitch
  slug: twitch
  status: profiled
  tags: *id036
  url: /providers/twitch/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id037
  name: WeChat
  slug: wechat
  status: profiled
  tags: *id038
  url: /providers/wechat/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id039
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id040
  url: /providers/x/
siblings:
- name: Authelia
  rows: 1
  url: /applications/identity-access/authelia/
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
- name: Ory Kratos
  rows: 22
  url: /applications/identity-access/ory-kratos/
- name: Zitadel
  rows: 8
  url: /applications/identity-access/zitadel/
sitemap: true
title: 'Authentik: Identity, SSO & Access Management reference app'
---
