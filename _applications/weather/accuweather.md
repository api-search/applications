---
app: AccuWeather
app_slug: accuweather
app_url: https://www.accuweather.com/
author: API Evangelist
capabilities:
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics / Crashlytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Airship (Urbanairship)
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id001
      source: https://github.com/urbanairship/agent-tools
      status: verified
    slug: airship
    status: profiled
    tags: &id002
    - Email
    - Mobile
    - Notification
    - Push
    url: /providers/airship/
  layer: common
  name: Airship (Urbanairship)
  provider: airship
  says: ships the Airship (Urbanairship) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
  tier: observed
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
    mcp: &id003
      status: none
    slug: google-admob
    status: profiled
    tags: &id004
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id006
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/accuweather/
providers:
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id001
  name: Airship (Urbanairship)
  slug: airship
  status: profiled
  tags: *id002
  url: /providers/airship/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id003
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id004
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Google Firebase Analytics / Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
siblings:
- name: Breezy Weather
  rows: 51
  url: /applications/weather/breezy-weather/
- name: Carrot Weather
  rows: 3
  url: /applications/weather/carrot-weather/
- name: MagicMirror2 weather module
  rows: 13
  url: /applications/weather/magicmirror2-weather-module/
- name: WeeWX
  rows: 6
  url: /applications/weather/weewx/
- name: Windy
  rows: 6
  url: /applications/weather/windy/
- name: wttr.in
  rows: 5
  url: /applications/weather/wttr-in/
sitemap: true
title: 'AccuWeather: Weather & Environmental Alerts reference app'
---
