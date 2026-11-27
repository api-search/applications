---
app: Element / Matrix (Synapse)
app_slug: element-matrix-synapse
app_url: https://github.com/element-hq/element-web
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Jitsi
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
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
  id: messaging-chat
  name: Messaging & Team Chat
  url: /applications/messaging-chat/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/im.vector.app/latest/
- route: dependency manifest
  url: https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
- route: dependency manifest
  url: https://github.com/element-hq/synapse/blob/develop/pyproject.toml
- route: source code
  url: https://github.com/element-hq/element-web/blob/develop/apps/web/config.sample.json
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id001
      status: none
    slug: google-admob
    status: profiled
    tags: &id002
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/im.vector.app/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.7
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id003
      status: none
    slug: jitsi-org
    status: profiled
    tags: &id004
    - Open Source
    - Real-Time Communication
    - Video Conferencing
    - WebRTC
    url: /providers/jitsi-org/
  layer: domain
  name: Jitsi
  provider: jitsi-org
  says: ships the Jitsi SDK or integration code
  source: https://github.com/element-hq/element-web/blob/develop/apps/web/config.sample.json
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
    mcp: &id005
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id006
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
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
  source: https://github.com/element-hq/element-web/blob/develop/apps/web/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/messaging-chat/element-matrix-synapse/
providers:
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id002
  url: /providers/google-admob/
- agent_band: human-only
  agent_readiness: 3.7
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id003
  name: Jitsi
  slug: jitsi-org
  status: profiled
  tags: *id004
  url: /providers/jitsi-org/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id005
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id006
  url: /providers/posthog/
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
- name: Discord
  rows: 23
  url: /applications/messaging-chat/discord/
- name: Mattermost
  rows: 25
  url: /applications/messaging-chat/mattermost/
- name: Rocket.Chat
  rows: 11
  url: /applications/messaging-chat/rocket-chat/
- name: Signal
  rows: 7
  url: /applications/messaging-chat/signal/
- name: Slack
  rows: 24
  url: /applications/messaging-chat/slack/
- name: Zulip
  rows: 11
  url: /applications/messaging-chat/zulip/
sitemap: true
title: 'Element / Matrix (Synapse): Messaging & Team Chat reference app'
---
