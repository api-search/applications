---
app: Baseline
app_slug: baseline
app_url: https://github.com/nkalupahana/baseline
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Spotify embeds
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-160.10
  key: AE-160.10
  layer: common
  name: Customer Sign-In
  providers:
  - Firebase Authentication
  url: /capabilities/customer-sign-in/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Google Cloud Pub/Sub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail API
  url: /capabilities/mailbox-calendar-sync/
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
  - Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: mental-health-meditation
  name: Mental Health, Meditation & Sleep
  url: /applications/mental-health-meditation/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
- route: dependency manifest
  url: https://github.com/nkalupahana/baseline/blob/main/package.json
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id003
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Authentication
  provider: firebase
  says: ships the Firebase Authentication SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id004
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id005
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail API
  provider: google-gmail
  says: ships the Gmail API SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id006
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id007
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
  layer: common
  name: Google Cloud Pub/Sub
  provider: google-cloud-pubsub
  says: ships the Google Cloud Pub/Sub SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id008
      status: none
    slug: google-sheets
    status: profiled
    tags: &id009
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/backend/package.json
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
    mcp: &id010
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id011
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id012
      status: none
    slug: spotify
    status: profiled
    tags: &id013
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify embeds
  provider: spotify
  says: ships the Spotify embeds SDK or integration code
  source: https://github.com/nkalupahana/baseline/blob/main/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mental-health-meditation/baseline/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id002
  name: Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id003
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id004
  name: Gmail API
  slug: google-gmail
  status: profiled
  tags: *id005
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id006
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id007
  url: /providers/google-cloud-pubsub/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id008
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id009
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id010
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id011
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id012
  name: Spotify embeds
  slug: spotify
  status: profiled
  tags: *id013
  url: /providers/spotify/
siblings:
- name: BetterHelp
  rows: 3
  url: /applications/mental-health-meditation/betterhelp/
- name: Calm
  rows: 6
  url: /applications/mental-health-meditation/calm/
- name: Headspace
  rows: 4
  url: /applications/mental-health-meditation/headspace/
- name: Heylinda
  rows: 1
  url: /applications/mental-health-meditation/heylinda/
- name: Medito
  rows: 7
  url: /applications/mental-health-meditation/medito/
- name: Pixy Mood Tracker
  rows: 4
  url: /applications/mental-health-meditation/pixy-mood-tracker/
- name: Sleep as Android
  rows: 19
  url: /applications/mental-health-meditation/sleep-as-android/
sitemap: true
title: 'Baseline: Mental Health, Meditation & Sleep reference app'
---
