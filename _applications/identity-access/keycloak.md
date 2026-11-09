---
app: Keycloak
app_slug: keycloak
app_url: https://github.com/keycloak/keycloak
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Bitbucket
  - Facebook
  - GitHub
  - GitLab
  - Google sign-in
  - Instagram
  - LinkedIn
  - Microsoft
  - PayPal
  - Red Hat OpenShift
  - Stack Overflow
  - X (Twitter)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: identity-access
  name: Identity, SSO & Access Management
  url: /applications/identity-access/
counts:
  declared: 0
  observed: 12
credits: []
evidence:
- route: source code
  url: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id001
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id002
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: ships the Bitbucket SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    mcp: &id003
      status: none
    slug: facebook
    status: profiled
    tags: &id004
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    mcp: &id007
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id008
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id011
      status: none
    slug: instagram
    status: profiled
    tags: &id012
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: ships the Instagram SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    mcp: &id013
      status: none
    slug: linkedin
    status: profiled
    tags: &id014
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id015
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id016
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id017
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id018
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    agent_readiness: 19.0
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id019
      source: https://github.com/openshift/kubernetes-mcp-server
      status: verified
    slug: red-hat-openshift
    status: profiled
    tags: &id020
    - Containers
    - Enterprise
    - Hybrid Cloud
    - Kubernetes
    url: /providers/red-hat-openshift/
  layer: domain
  name: Red Hat OpenShift
  provider: red-hat-openshift
  says: ships the Red Hat OpenShift SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    agent_readiness: 28.6
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id021
      source: https://github.com/StackExchange/Stack-MCP
      status: verified
    slug: stack-overflow
    status: profiled
    tags: &id022
    - Answers
    - Code
    - Developer Community
    - Developer Tools
    url: /providers/stack-overflow/
  layer: domain
  name: Stack Overflow
  provider: stack-overflow
  says: ships the Stack Overflow SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
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
    mcp: &id023
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id024
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/identity-access/keycloak/
providers:
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id001
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id002
  url: /providers/bitbucket/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id003
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id004
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id005
  name: GitHub
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id007
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id008
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id009
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id011
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id012
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id013
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id014
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id015
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id016
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id017
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id018
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id019
  name: Red Hat OpenShift
  slug: red-hat-openshift
  status: profiled
  tags: *id020
  url: /providers/red-hat-openshift/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id021
  name: Stack Overflow
  slug: stack-overflow
  status: profiled
  tags: *id022
  url: /providers/stack-overflow/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id023
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id024
  url: /providers/x/
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
title: 'Keycloak: Identity, SSO & Access Management reference app'
---
