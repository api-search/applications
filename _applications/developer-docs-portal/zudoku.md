---
app: Zudoku
app_slug: zudoku
app_url: https://github.com/zuplo/zudoku
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-909
  key: AE-909
  layer: domain
  name: API Gateways
  providers:
  - Zuplo
  url: /capabilities/api-consumption-governance/
  via_parent: API Consumption Governance
- attribution: API Evangelist extension
  id: AE-160.10
  key: AE-160.10
  layer: domain
  name: Customer Sign-In
  providers:
  - Auth0
  - Azure AD B2C
  - Clerk
  - Firebase Auth
  - Supabase Auth
  url: /capabilities/customer-sign-in/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.60.30
  key: AE-110.60.30
  layer: domain
  name: Retrieval-Augmented Generation
  providers:
  - Inkeep
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
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
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: developer-docs-portal
  name: Developer Docs & API Portals
  url: /applications/developer-docs-portal/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
- route: source code
  url: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
- route: source code
  url: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id002
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id003
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: domain
  name: Auth0
  provider: auth0
  says: ships the Auth0 SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id004
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id005
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Azure AD B2C
  provider: microsoft-entra
  says: ships the Azure AD B2C SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.9
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id006
      source: https://github.com/clerk/mcp-tools
      status: verified
    slug: clerk-com
    status: profiled
    tags: &id007
    - Authentication
    - Authorization
    - B2B SaaS
    - CIAM
    url: /providers/clerk-com/
  layer: domain
  name: Clerk
  provider: clerk-com
  says: ships the Clerk SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id008
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id009
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: domain
  name: Firebase Auth
  provider: firebase
  says: ships the Firebase Auth SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id010
      source: https://docs.inkeep.com/talk-to-your-agents/mcp-server
      status: verified
    slug: inkeep
    status: profiled
    tags: &id011
    - Agents
    - Artificial Intelligence
    - RAG
    - Support
    url: /providers/inkeep/
  layer: domain
  name: Inkeep
  provider: inkeep
  says: ships the Inkeep SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
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
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id012
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id013
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
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
    mcp: &id014
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id015
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id016
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id017
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
  layer: domain
  name: Supabase Auth
  provider: supabase
  says: ships the Supabase Auth SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.2
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id018
      source: https://dev.zuplo.com/mcp
      status: verified
    slug: zuplo
    status: profiled
    tags: &id019
    - AI Gateway
    - API Management
    - Gateways
    - Platform
    url: /providers/zuplo/
  layer: domain
  name: Zuplo
  provider: zuplo
  says: ships the Zuplo SDK or integration code
  source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/developer-docs-portal/zudoku/
providers:
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id002
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id003
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id004
  name: Azure AD B2C
  slug: microsoft-entra
  status: profiled
  tags: *id005
  url: /providers/microsoft-entra/
- agent_band: agent-native
  agent_readiness: 51.9
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id006
  name: Clerk
  slug: clerk-com
  status: profiled
  tags: *id007
  url: /providers/clerk-com/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id008
  name: Firebase Auth
  slug: google-firebase
  status: profiled
  tags: *id009
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id010
  name: Inkeep
  slug: inkeep
  status: profiled
  tags: *id011
  url: /providers/inkeep/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id012
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id013
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id014
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id015
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id016
  name: Supabase Auth
  slug: supabase
  status: profiled
  tags: *id017
  url: /providers/supabase/
- agent_band: agent-ready
  agent_readiness: 57.2
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id018
  name: Zuplo
  slug: zuplo
  status: profiled
  tags: *id019
  url: /providers/zuplo/
siblings:
- name: Backstage
  rows: 37
  url: /applications/developer-docs-portal/backstage/
- name: Docusaurus
  rows: 7
  url: /applications/developer-docs-portal/docusaurus/
- name: GitBook
  rows: 56
  url: /applications/developer-docs-portal/gitbook/
- name: Mintlify
  rows: 49
  url: /applications/developer-docs-portal/mintlify/
- name: ReadMe
  rows: 17
  url: /applications/developer-docs-portal/readme/
- name: Redocly
  rows: 16
  url: /applications/developer-docs-portal/redocly/
sitemap: true
title: 'Zudoku: Developer Docs & API Portals reference app'
---
