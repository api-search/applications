---
app: Leantime
app_slug: leantime
app_url: https://github.com/Leantime/leantime
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Gitea
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Crisp
  url: /capabilities/customer-service-management/
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
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
  - Auth0
  - authentik
  - Google sign-in
  - Keycloak
  - Microsoft Entra ID
  - Okta
  - PropelAuth
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.60.20
  key: AE-110.60.20
  layer: common
  name: Vector Search
  providers:
  - Qdrant
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
category:
  id: project-management
  name: Project & Work Management
  url: /applications/project-management/
counts:
  declared: 0
  observed: 15
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id003
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id004
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.2
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id005
      status: none
    slug: authentik
    status: profiled
    tags: &id006
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id007
      status: none
    slug: crisp
    status: profiled
    tags: &id008
    - Customer Service
    - Help Desk
    - Live Chat
    - Messaging
    url: /providers/crisp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: exemplar
    in_catalog: true
    kin_score: 69.8
    mcp: &id009
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id010
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id013
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id015
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id016
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id017
      status: none
    slug: keycloak
    status: profiled
    tags: &id018
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id019
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id020
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.1
    band: strong
    in_catalog: true
    kin_score: 61.2
    mcp: &id023
      status: none
    slug: propelauth
    status: profiled
    tags: &id024
    - Authentication
    - B2B
    - Identity
    - Multi-Tenancy
    url: /providers/propelauth/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id025
      source: https://github.com/qdrant/mcp-server-qdrant
      status: verified
    slug: qdrant
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Database
    - Vector Search
    url: /providers/qdrant/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id029
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id030
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/Leantime/leantime/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/project-management/leantime/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id003
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id004
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id005
  name: authentik
  slug: authentik
  status: profiled
  tags: *id006
  url: /providers/authentik/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id007
  name: Crisp
  slug: crisp
  status: profiled
  tags: *id008
  url: /providers/crisp/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: exemplar
  in_catalog: true
  kin_score: 69.8
  mcp: *id009
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id010
  url: /providers/gitea/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id011
  name: GitHub
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id013
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id014
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id015
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id017
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id018
  url: /providers/keycloak/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id019
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id020
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id021
  name: Okta
  slug: okta
  status: profiled
  tags: *id022
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: strong
  in_catalog: true
  kin_score: 61.2
  mcp: *id023
  name: PropelAuth
  slug: propelauth
  status: profiled
  tags: *id024
  url: /providers/propelauth/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id025
  name: Qdrant
  slug: qdrant
  status: profiled
  tags: *id026
  url: /providers/qdrant/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id027
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id028
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id029
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id030
  url: /providers/stripe/
siblings:
- name: Asana
  rows: 22
  url: /applications/project-management/asana/
- name: Jira (Android)
  rows: 3
  url: /applications/project-management/jira-android/
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
- name: Vikunja
  rows: 8
  url: /applications/project-management/vikunja/
sitemap: true
title: 'Leantime: Project & Work Management reference app'
---
