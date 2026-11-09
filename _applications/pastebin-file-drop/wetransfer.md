---
app: WeTransfer
app_slug: wetransfer
app_url: https://wetransfer.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google CrashLytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
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
  url: https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
- route: documentation
  url: https://wetransfer.com/help-center
- route: integrations page
  url: https://wetransfer.com/products/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id002
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id003
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pastebin-file-drop/wetransfer/
providers:
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id002
  name: Google CrashLytics
  slug: firebase
  status: profiled
  tags: *id003
  url: /providers/firebase/
siblings:
- name: LocalSend
  rows: 2
  url: /applications/pastebin-file-drop/localsend/
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
- name: Zipline
  rows: 5
  url: /applications/pastebin-file-drop/zipline/
sitemap: true
title: 'WeTransfer: Pastebin, File Drop & Quick Share reference app'
---
