---
app: Bluesky
app_slug: bluesky
app_url: https://github.com/bluesky-social/social-app
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - GrowthBook
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - bitdrift
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Expo
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: social-network
  name: Social Networking & Microblogging
  url: /applications/social-network/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/xyz.blueskyweb.app/latest/
- route: dependency manifest
  url: https://github.com/bluesky-social/social-app/blob/main/package.json
- route: source code
  url: https://github.com/bluesky-social/social-app/blob/main/.env.example
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id001
      source: https://docs.bitdrift.io/ai/mcp.md
      status: verified
    slug: bitdrift
    status: profiled
    tags: &id002
    - Company
    - Developer Tools
    - Mobile
    - Observability
    url: /providers/bitdrift/
  layer: common
  name: bitdrift
  provider: bitdrift
  says: ships the bitdrift SDK or integration code
  source: https://github.com/bluesky-social/social-app/blob/main/package.json
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
    agent_readiness: 20.5
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id003
      source: https://github.com/expo/expo-mcp
      status: verified
    slug: expo
    status: profiled
    tags: &id004
    - Build Automation
    - Mobile Development
    - Over-the-Air Updates
    - React Native
    url: /providers/expo/
  layer: common
  name: Expo
  provider: expo
  says: ships the Expo SDK or integration code
  source: https://github.com/bluesky-social/social-app/blob/main/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id005
      source: https://github.com/growthbook/growthbook-mcp
      status: verified
    slug: growthbook
    status: profiled
    tags: &id006
    - A/B Testing
    - Experimentation
    - Feature Flags
    - Open Source
    url: /providers/growthbook/
  layer: common
  name: GrowthBook
  provider: growthbook
  says: ships the GrowthBook SDK or integration code
  source: https://github.com/bluesky-social/social-app/blob/main/package.json
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
    mcp: &id007
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id008
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/bluesky-social/social-app/blob/main/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-network/bluesky/
providers:
- agent_band: agent-aware
  agent_readiness: 26.2
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id001
  name: bitdrift
  slug: bitdrift
  status: profiled
  tags: *id002
  url: /providers/bitdrift/
- agent_band: agent-aware
  agent_readiness: 20.5
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id003
  name: Expo
  slug: expo
  status: profiled
  tags: *id004
  url: /providers/expo/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id005
  name: GrowthBook
  slug: growthbook
  status: profiled
  tags: *id006
  url: /providers/growthbook/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id007
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id008
  url: /providers/sentry-system/
siblings:
- name: Friendica
  rows: 20
  url: /applications/social-network/friendica/
- name: Instagram
  rows: 2
  url: /applications/social-network/instagram/
- name: Mastodon
  rows: 9
  url: /applications/social-network/mastodon/
- name: Misskey
  rows: 11
  url: /applications/social-network/misskey/
- name: Pixelfed
  rows: 11
  url: /applications/social-network/pixelfed/
- name: Threads
  rows: 2
  url: /applications/social-network/threads/
sitemap: true
title: 'Bluesky: Social Networking & Microblogging reference app'
---
