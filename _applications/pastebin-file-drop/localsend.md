---
app: LocalSend
app_slug: localsend
app_url: https://github.com/localsend/localsend
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Apple App Store in-app purchase
  - Google Play Billing
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
category:
  id: pastebin-file-drop
  name: Pastebin, File Drop & Quick Share
  url: /applications/pastebin-file-drop/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.localsend.localsend_app/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
integrations:
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple App Store in-app purchase
  provider: apple
  says: ships the Apple App Store in-app purchase SDK or integration code
  source: https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
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
  source: https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pastebin-file-drop/localsend/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id001
  name: Apple App Store in-app purchase
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id003
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id004
  url: /providers/google-play/
siblings:
- name: Pingvin Share
  rows: 5
  url: /applications/pastebin-file-drop/pingvin-share/
- name: PrivateBin
  rows: 5
  url: /applications/pastebin-file-drop/privatebin/
- name: PsiTransfer
  rows: 0
  url: /applications/pastebin-file-drop/psitransfer/
- name: Send (timvisee fork of Firefox Send)
  rows: 4
  url: /applications/pastebin-file-drop/send-timvisee-fork-of-firefox-send/
- name: WeTransfer
  rows: 2
  url: /applications/pastebin-file-drop/wetransfer/
- name: Zipline
  rows: 5
  url: /applications/pastebin-file-drop/zipline/
sitemap: true
title: 'LocalSend: Pastebin, File Drop & Quick Share reference app'
---
