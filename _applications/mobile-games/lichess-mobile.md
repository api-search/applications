---
app: Lichess mobile
app_slug: lichess-mobile
app_url: https://github.com/lichess-org/mobile
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
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
  id: mobile-games
  name: Mobile & Casual Games (live-ops backend)
  url: /applications/mobile-games/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
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
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-games/lichess-mobile/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id002
  name: Firebase Cloud Messaging
  slug: google-firebase
  status: profiled
  tags: *id003
  url: /providers/google-firebase/
siblings:
- name: Candy Crush Saga
  rows: 15
  url: /applications/mobile-games/candy-crush-saga/
- name: Clash of Clans
  rows: 49
  url: /applications/mobile-games/clash-of-clans/
- name: Mindustry
  rows: 4
  url: /applications/mobile-games/mindustry/
- name: Nakama
  rows: 10
  url: /applications/mobile-games/nakama/
- name: Subway Surfers
  rows: 29
  url: /applications/mobile-games/subway-surfers/
- name: Talo
  rows: 7
  url: /applications/mobile-games/talo/
- name: Unciv
  rows: 3
  url: /applications/mobile-games/unciv/
sitemap: true
title: 'Lichess mobile: Mobile & Casual Games (live-ops backend) reference app'
---
