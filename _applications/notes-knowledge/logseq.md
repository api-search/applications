---
app: Logseq
app_slug: logseq
app_url: https://github.com/logseq/logseq
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10
  key: AE-160.10
  layer: common
  name: Customer Sign-In
  providers:
  - Amazon Cognito (via aws-amplify)
  url: /capabilities/customer-sign-in/
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
  id: notes-knowledge
  name: Notes & Personal Knowledge Management
  url: /applications/notes-knowledge/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.logseq.app/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/logseq/logseq/master/package.json
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
    agent_band: agent-aware
    agent_readiness: 27.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id001
      status: none
    slug: amazon-cognito
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Authentication
    - Identity
    - OAuth
    url: /providers/amazon-cognito/
  layer: common
  name: Amazon Cognito (via aws-amplify)
  provider: amazon-cognito
  says: ships the Amazon Cognito (via aws-amplify) SDK or integration code
  source: https://raw.githubusercontent.com/logseq/logseq/master/package.json
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
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id003
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://raw.githubusercontent.com/logseq/logseq/master/package.json
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
    mcp: &id005
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id006
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/logseq/logseq/master/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/notes-knowledge/logseq/
providers:
- agent_band: agent-aware
  agent_readiness: 27.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id001
  name: Amazon Cognito (via aws-amplify)
  slug: amazon-cognito
  status: profiled
  tags: *id002
  url: /providers/amazon-cognito/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id003
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id004
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
siblings:
- name: AFFiNE
  rows: 16
  url: /applications/notes-knowledge/affine/
- name: BookStack
  rows: 11
  url: /applications/notes-knowledge/bookstack/
- name: Joplin
  rows: 5
  url: /applications/notes-knowledge/joplin/
- name: Notion
  rows: 12
  url: /applications/notes-knowledge/notion/
- name: Obsidian
  rows: 0
  url: /applications/notes-knowledge/obsidian/
- name: Outline
  rows: 18
  url: /applications/notes-knowledge/outline/
- name: Wiki.js
  rows: 21
  url: /applications/notes-knowledge/wiki-js/
sitemap: true
title: 'Logseq: Notes & Personal Knowledge Management reference app'
---
