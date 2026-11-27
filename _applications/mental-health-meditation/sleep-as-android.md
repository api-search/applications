---
app: Sleep as Android
app_slug: sleep-as-android
app_url: https://sleep.urbandroid.org/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Spotify
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Home Assistant
  - MQTT
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10.10
  key: AE-200.10.10
  layer: domain
  name: Voice Assistant Smart-Home Integrations
  providers:
  - Google Assistant (App Actions)
  url: /capabilities/smart-home/
  via_parent: Smart Home
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Amazfit (Zepp Health)
  - Garmin
  - Google Fit
  - Google Home / Wear OS
  - Health Connect
  - Pebble smartwatch
  - Samsung Health
  - Xiaomi Mi Band
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Facebook Ads
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
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
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Automate (LlamaLab)
  - IFTTT
  - Tasker
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: mental-health-meditation
  name: Mental Health, Meditation & Sleep
  url: /applications/mental-health-meditation/
counts:
  declared: 16
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
- route: documentation
  url: https://sleep.urbandroid.org/docs/services/
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
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Ads
  provider: facebook
  says: ships the Facebook Ads SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
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
    mcp: &id009
      status: none
    slug: google-admob
    status: profiled
    tags: &id010
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
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
    mcp: &id015
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id016
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.urbandroid.sleep/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.4
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id001
      status: unknown
    slug: zepp-health
    status: profiled
    tags: &id002
    - Company
    - Health
    - IoT
    - Wearables
    url: /providers/zepp-health/
  layer: domain
  name: Amazfit (Zepp Health)
  provider: zepp-health
  says: lists Amazfit (Zepp Health) as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.7
    mcp: &id003
      status: none
    slug: automate
    status: profiled
    tags: &id004
    - Automotive
    - Company
    - Dealer Management
    - Software
    url: /providers/automate/
  layer: common
  name: Automate (LlamaLab)
  provider: automate
  says: lists Automate (LlamaLab) as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id007
      status: none
    slug: garmin
    status: profiled
    tags: &id008
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
  layer: domain
  name: Garmin
  provider: garmin
  says: lists Garmin as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10.10
    key: AE-200.10.10
    name: Voice Assistant Smart-Home Integrations
    url: /capabilities/smart-home/
    via_parent: Smart Home
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.5
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id011
      status: unknown
    slug: google-assistant
    status: profiled
    tags: &id012
    - Actions on Google
    - Conversational AI
    - Google Assistant
    - Natural-Language
    url: /providers/google-assistant/
  layer: domain
  name: Google Assistant (App Actions)
  provider: google-assistant
  says: lists Google Assistant (App Actions) as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id014
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id017
      status: none
    slug: google-fitness
    status: profiled
    tags: &id018
    - Activity Tracking
    - Fitness
    - Google
    - Health
    url: /providers/google-fitness/
  layer: domain
  name: Google Fit
  provider: google-fitness
  says: lists Google Fit as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id019
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id020
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google Home / Wear OS
  provider: google
  says: lists Google Home / Wear OS as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id021
      status: none
    slug: health-connect
    status: profiled
    tags: &id022
    - Android
    - Company
    - Data
    - Health
    url: /providers/health-connect/
  layer: domain
  name: Health Connect
  provider: health-connect
  says: lists Health Connect as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id023
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id024
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant
  provider: home-assistant
  says: lists Home Assistant as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.4
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id025
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id026
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: lists IFTTT as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.5
    band: emerging
    in_catalog: true
    kin_score: 15.4
    mcp: &id027
      status: none
    slug: mqtt
    status: profiled
    tags: &id028
    - IoT
    - MQTT
    - Messaging
    - Publish Subscribe
    url: /providers/mqtt/
  layer: domain
  name: MQTT
  provider: mqtt
  says: lists MQTT as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.9
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id029
      status: none
    slug: repebble
    status: profiled
    tags: &id030
    - Company
    - IoT
    - Smartwatch
    - Wearables
    url: /providers/repebble/
  layer: domain
  name: Pebble smartwatch
  provider: repebble
  says: lists Pebble smartwatch as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.6
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id031
      status: none
    slug: samsung
    status: profiled
    tags: &id032
    - Consumer Electronics
    - Developer Platform
    - IoT
    - Mobile
    url: /providers/samsung/
  layer: domain
  name: Samsung Health
  provider: samsung
  says: lists Samsung Health as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
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
    mcp: &id033
      status: none
    slug: spotify
    status: profiled
    tags: &id034
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: lists Spotify as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id035
      status: unchecked
    slug: tasker
    status: queued for profiling
    tags: &id036 []
    url: null
  layer: common
  name: Tasker
  provider: tasker
  says: lists Tasker as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id037
      status: none
    slug: xiaomi
    status: profiled
    tags: &id038
    - Consumer Electronics
    - IoT
    - Mobile
    - Smart Home
    url: /providers/xiaomi/
  layer: domain
  name: Xiaomi Mi Band
  provider: xiaomi
  says: lists Xiaomi Mi Band as an integration
  source: https://sleep.urbandroid.org/docs/services/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mental-health-meditation/sleep-as-android/
providers:
- agent_band: human-only
  agent_readiness: 4.4
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id001
  name: Amazfit (Zepp Health)
  slug: zepp-health
  status: profiled
  tags: *id002
  url: /providers/zepp-health/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id003
  name: Automate (LlamaLab)
  slug: automate
  status: profiled
  tags: *id004
  url: /providers/automate/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook Ads
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id007
  name: Garmin
  slug: garmin
  status: profiled
  tags: *id008
  url: /providers/garmin/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id009
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id010
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 29.5
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id011
  name: Google Assistant (App Actions)
  slug: google-assistant
  status: profiled
  tags: *id012
  url: /providers/google-assistant/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id013
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id014
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id015
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id016
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id017
  name: Google Fit
  slug: google-fitness
  status: profiled
  tags: *id018
  url: /providers/google-fitness/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id019
  name: Google Home / Wear OS
  slug: google
  status: profiled
  tags: *id020
  url: /providers/google/
- agent_band: human-only
  agent_readiness: 0.7
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id021
  name: Health Connect
  slug: health-connect
  status: profiled
  tags: *id022
  url: /providers/health-connect/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id023
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id024
  url: /providers/home-assistant/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id025
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id026
  url: /providers/ifttt/
- agent_band: agent-aware
  agent_readiness: 16.5
  band: emerging
  in_catalog: true
  kin_score: 15.4
  mcp: *id027
  name: MQTT
  slug: mqtt
  status: profiled
  tags: *id028
  url: /providers/mqtt/
- agent_band: agent-aware
  agent_readiness: 6.9
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id029
  name: Pebble smartwatch
  slug: repebble
  status: profiled
  tags: *id030
  url: /providers/repebble/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id031
  name: Samsung Health
  slug: samsung
  status: profiled
  tags: *id032
  url: /providers/samsung/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id033
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id034
  url: /providers/spotify/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id035
  name: Tasker
  slug: tasker
  status: queued for profiling
  tags: *id036
  url: null
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id037
  name: Xiaomi Mi Band
  slug: xiaomi
  status: profiled
  tags: *id038
  url: /providers/xiaomi/
siblings:
- name: Baseline
  rows: 8
  url: /applications/mental-health-meditation/baseline/
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
sitemap: true
title: 'Sleep as Android: Mental Health, Meditation & Sleep reference app'
---
