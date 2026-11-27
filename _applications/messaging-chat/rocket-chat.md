---
app: Rocket.Chat
app_slug: rocket-chat
app_url: https://github.com/RocketChat/Rocket.Chat
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.40
  key: AE-160.10.40
  layer: domain
  name: Account Linking
  providers:
  - X (Twitter)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - LiveKit
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  - Firebase (Crashlytics, Analytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Apple (APNs, Sign in with Apple)
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: messaging-chat
  name: Messaging & Team Chat
  url: /applications/messaging-chat/
counts:
  declared: 0
  observed: 11
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/chat.rocket.android/latest/
- route: dependency manifest
  url: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
- route: source code
  url: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/server/services/omnichannel-integrations/providers/twilio.ts
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
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
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
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple (APNs, Sign in with Apple)
  provider: apple
  says: ships the Apple (APNs, Sign in with Apple) SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id005
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id006
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics, Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics, Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/chat.rocket.android/latest/
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
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    mcp: &id011
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id012
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
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
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id015
      status: none
    slug: livekit
    status: profiled
    tags: &id016
    - Audio
    - Real-Time
    - Video
    - WebRTC
    url: /providers/livekit/
  layer: domain
  name: LiveKit
  provider: livekit
  says: ships the LiveKit SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id017
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id018
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id019
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id020
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/server/services/omnichannel-integrations/providers/twilio.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id021
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id022
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/RocketChat/Rocket.Chat/blob/develop/apps/meteor/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/messaging-chat/rocket-chat/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple (APNs, Sign in with Apple)
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id005
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id006
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Firebase (Crashlytics, Analytics)
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id011
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id012
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id013
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id014
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id015
  name: LiveKit
  slug: livekit
  status: profiled
  tags: *id016
  url: /providers/livekit/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id017
  name: Slack
  slug: slack
  status: profiled
  tags: *id018
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id019
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id020
  url: /providers/twilio/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id021
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id022
  url: /providers/x/
siblings:
- name: Discord
  rows: 23
  url: /applications/messaging-chat/discord/
- name: Element / Matrix (Synapse)
  rows: 4
  url: /applications/messaging-chat/element-matrix-synapse/
- name: Mattermost
  rows: 25
  url: /applications/messaging-chat/mattermost/
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
title: 'Rocket.Chat: Messaging & Team Chat reference app'
---
