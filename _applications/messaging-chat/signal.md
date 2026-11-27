---
app: Signal
app_slug: signal
app_url: https://github.com/signalapp/Signal-Android
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.40
  key: AE-190.40
  layer: domain
  name: Remittances & P2P
  providers:
  - MobileCoin
  url: /capabilities/remittances-p2p/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: common
  name: Digital & Mobile Wallets
  providers:
  - Google Pay
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Google Play Billing
  url: /capabilities/in-app-purchases-app-store-billing/
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
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google ID / Credential Manager
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: messaging-chat
  name: Messaging & Team Chat
  url: /applications/messaging-chat/
counts:
  declared: 0
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.thoughtcrime.securesms/latest/
- route: dependency manifest
  url: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
- route: source code
  url: https://github.com/signalapp/Signal-Android/blob/main/app/build.gradle.kts
integrations:
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id002
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
    mcp: &id003
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id004
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google ID / Credential Manager
  provider: google-identity-platform
  says: ships the Google ID / Credential Manager SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id005
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id006
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id007
      status: none
    slug: google-pay
    status: profiled
    tags: &id008
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: common
  name: Google Pay
  provider: google-pay
  says: ships the Google Pay SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id009
      status: none
    slug: google-play
    status: profiled
    tags: &id010
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play Billing
  provider: google-play
  says: ships the Google Play Billing SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.40
    key: AE-190.40
    name: Remittances & P2P
    url: /capabilities/remittances-p2p/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.2
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id011
      status: none
    slug: mobilecoin
    status: profiled
    tags: &id012
    - Blockchain
    - Company
    - Cryptocurrency
    - Payments
    url: /providers/mobilecoin/
  layer: domain
  name: MobileCoin
  provider: mobilecoin
  says: ships the MobileCoin SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/gradle/libs.versions.toml
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
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id013
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id014
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/signalapp/Signal-Android/blob/main/app/build.gradle.kts
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/messaging-chat/signal/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Firebase Cloud Messaging
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id003
  name: Google ID / Credential Manager
  slug: google-identity-platform
  status: profiled
  tags: *id004
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id005
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id006
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id007
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id008
  url: /providers/google-pay/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id009
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id010
  url: /providers/google-play/
- agent_band: agent-aware
  agent_readiness: 6.2
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id011
  name: MobileCoin
  slug: mobilecoin
  status: profiled
  tags: *id012
  url: /providers/mobilecoin/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id013
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id014
  url: /providers/stripe/
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
- name: Rocket.Chat
  rows: 11
  url: /applications/messaging-chat/rocket-chat/
- name: Slack
  rows: 24
  url: /applications/messaging-chat/slack/
- name: Zulip
  rows: 11
  url: /applications/messaging-chat/zulip/
sitemap: true
title: 'Signal: Messaging & Team Chat reference app'
---
