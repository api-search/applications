---
app: Thunderbird for Android
app_slug: thunderbird-for-android
app_url: https://github.com/thunderbird/thunderbird-android
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - AOL Mail
  - Fastmail
  - Gmail
  - Outlook / Microsoft 365
  - Yahoo Mail
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Mozilla Glean
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: email-client
  name: Email Client & Hosting
  url: /applications/email-client/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
- route: source code
  url: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
integrations:
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
    agent_readiness: 35.3
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id001
      status: none
    slug: aol
    status: profiled
    tags: &id002
    - Advertising
    - Digital Media
    - Entertainment
    - News
    url: /providers/aol/
  layer: domain
  name: AOL Mail
  provider: aol
  says: ships the AOL Mail SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
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
    agent_band: agent-aware
    agent_readiness: 17.3
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id003
      status: none
    slug: fastmail
    status: profiled
    tags: &id004
    - Business
    - Email
    - Privacy
    - Security
    url: /providers/fastmail/
  layer: domain
  name: Fastmail
  provider: fastmail
  says: ships the Fastmail SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
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
    mcp: &id005
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id006
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: ships the Gmail SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
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
    mcp: &id007
      status: none
    slug: google-play
    status: profiled
    tags: &id008
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play Billing
  provider: google-play
  says: ships the Google Play Billing SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
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
    agent_band: agent-aware
    agent_readiness: 20.8
    band: thin
    in_catalog: true
    kin_score: 26.3
    mcp: &id009
      source: https://github.com/mozilla/firefox-devtools-mcp
      status: verified
    slug: mozilla
    status: profiled
    tags: &id010
    - Data Engineering
    - Open Source
    - SDK
    - Telemetry
    url: /providers/mozilla/
  layer: common
  name: Mozilla Glean
  provider: mozilla
  says: ships the Mozilla Glean SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id012
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook / Microsoft 365
  provider: microsoft-outlook
  says: ships the Outlook / Microsoft 365 SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
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
    agent_band: agent-aware
    agent_readiness: 15.8
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id013
      status: none
    slug: yahoo
    status: profiled
    tags: &id014
    - Advertising
    - DSP
    - Fantasy Sports
    - Programmatic Advertising
    url: /providers/yahoo/
  layer: domain
  name: Yahoo Mail
  provider: yahoo
  says: ships the Yahoo Mail SDK or integration code
  source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/thunderbird-for-android/
providers:
- agent_band: agent-ready
  agent_readiness: 35.3
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id001
  name: AOL Mail
  slug: aol
  status: profiled
  tags: *id002
  url: /providers/aol/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id003
  name: Fastmail
  slug: fastmail
  status: profiled
  tags: *id004
  url: /providers/fastmail/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id005
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id006
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id007
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id008
  url: /providers/google-play/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id009
  name: Mozilla Glean
  slug: mozilla
  status: profiled
  tags: *id010
  url: /providers/mozilla/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id011
  name: Outlook / Microsoft 365
  slug: microsoft-outlook
  status: profiled
  tags: *id012
  url: /providers/microsoft-outlook/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id013
  name: Yahoo Mail
  slug: yahoo
  status: profiled
  tags: *id014
  url: /providers/yahoo/
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
- name: Proton Mail (Android)
  rows: 3
  url: /applications/email-client/proton-mail-android/
- name: Roundcube Webmail
  rows: 11
  url: /applications/email-client/roundcube-webmail/
- name: Stalwart Mail Server
  rows: 19
  url: /applications/email-client/stalwart-mail-server/
sitemap: true
title: 'Thunderbird for Android: Email Client & Hosting reference app'
---
