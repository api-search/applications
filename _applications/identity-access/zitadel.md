---
app: Zitadel
app_slug: zitadel
app_url: https://github.com/zitadel/zitadel
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - GitHub
  - GitLab
  - Google sign-in
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google Cloud Profiler
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
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: identity-access
  name: Identity, SSO & Access Management
  url: /applications/identity-access/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
- route: source code
  url: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
- route: source code
  url: https://github.com/zitadel/zitadel/tree/main/internal/notification/channels
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
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
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
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
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
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
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id005
      status: none
    slug: google-cloud-profiler
    status: profiled
    tags: &id006
    - CPU
    - Flame Graphs
    - Google Cloud
    - Memory
    url: /providers/google-cloud-profiler/
  layer: common
  name: Google Cloud Profiler
  provider: google-cloud-profiler
  says: ships the Google Cloud Profiler SDK or integration code
  source: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id007
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id008
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
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
    mcp: &id009
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id010
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
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
    mcp: &id011
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id012
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
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
    mcp: &id013
      status: none
    slug: apple
    status: profiled
    tags: &id014
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
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
    mcp: &id015
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id016
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/identity-access/zitadel/
providers:
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id001
  name: GitHub
  slug: github
  status: profiled
  tags: *id002
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id003
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id004
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id005
  name: Google Cloud Profiler
  slug: google-cloud-profiler
  status: profiled
  tags: *id006
  url: /providers/google-cloud-profiler/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id007
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id008
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id009
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id011
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id012
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id013
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id014
  url: /providers/apple/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id015
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id016
  url: /providers/twilio/
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
- name: Ory Kratos
  rows: 22
  url: /applications/identity-access/ory-kratos/
sitemap: true
title: 'Zitadel: Identity, SSO & Access Management reference app'
---
