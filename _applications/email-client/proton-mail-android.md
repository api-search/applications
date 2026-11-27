---
app: Proton Mail (Android)
app_slug: proton-mail-android
app_url: https://github.com/ProtonMail/android-mail
author: API Evangelist
capabilities:
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
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
category:
  id: email-client
  name: Email Client & Hosting
  url: /applications/email-client/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
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
  source: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
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
    mcp: &id003
      status: none
    slug: google-play
    status: profiled
    tags: &id004
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play Billing
  provider: google-play
  says: ships the Google Play Billing SDK or integration code
  source: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
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
  source: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/proton-mail-android/
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
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id003
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id004
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id005
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id006
  url: /providers/sentry-system/
siblings:
- name: FairEmail
  rows: 26
  url: /applications/email-client/fairemail/
- name: Mail-in-a-Box
  rows: 5
  url: /applications/email-client/mail-in-a-box/
- name: 'mailcow: dockerized'
  rows: 2
  url: /applications/email-client/mailcow-dockerized/
- name: Roundcube Webmail
  rows: 11
  url: /applications/email-client/roundcube-webmail/
- name: Stalwart Mail Server
  rows: 19
  url: /applications/email-client/stalwart-mail-server/
- name: Thunderbird for Android
  rows: 7
  url: /applications/email-client/thunderbird-for-android/
sitemap: true
title: 'Proton Mail (Android): Email Client & Hosting reference app'
---
