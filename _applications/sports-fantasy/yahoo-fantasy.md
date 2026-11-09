---
app: Yahoo Fantasy
app_slug: yahoo-fantasy
app_url: https://sports.yahoo.com/fantasy/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  - Taboola
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Comscore
  - Flurry
  - Google Analytics
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - IAB Open Measurement
  url: /capabilities/programmatic-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: sports-fantasy
  name: Sports Scores & Fantasy
  url: /applications/sports-fantasy/
counts:
  declared: 0
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id001
      status: none
    slug: comscore
    status: profiled
    tags: &id002
    - Audience Analytics
    - Cloud Saas
    - Company
    - Media Measurement
    url: /providers/comscore/
  layer: common
  name: Comscore
  provider: comscore
  says: ships the Comscore SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id003
      status: none
    slug: flurry
    status: profiled
    tags: &id004
    - Analytics
    - Company
    - Mobile
    - SDK
    url: /providers/flurry/
  layer: common
  name: Flurry
  provider: flurry
  says: ships the Flurry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id005
      status: none
    slug: google-admob
    status: profiled
    tags: &id006
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id007
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id008
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id009
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id010
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id011
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id012
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id013
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id014
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    agent_readiness: 31.3
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id015
      source: https://github.com/taboola/realize-mcp
      status: verified
    slug: taboola
    status: profiled
    tags: &id016
    - Advertising
    - Discovery
    - Native Advertising
    - Performance Marketing
    url: /providers/taboola/
  layer: common
  name: Taboola
  provider: taboola
  says: ships the Taboola SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sports-fantasy/yahoo-fantasy/
providers:
- agent_band: agent-aware
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id001
  name: Comscore
  slug: comscore
  status: profiled
  tags: *id002
  url: /providers/comscore/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id003
  name: Flurry
  slug: flurry
  status: profiled
  tags: *id004
  url: /providers/flurry/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id005
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id006
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id007
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id008
  url: /providers/google-analytics/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id009
  name: Google Firebase Analytics
  slug: firebase
  status: profiled
  tags: *id010
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id011
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id012
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id013
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id014
  url: /providers/iab-tech-lab/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id015
  name: Taboola
  slug: taboola
  status: profiled
  tags: *id016
  url: /providers/taboola/
siblings:
- name: ESPN
  rows: 10
  url: /applications/sports-fantasy/espn/
- name: ffscrapr
  rows: 6
  url: /applications/sports-fantasy/ffscrapr/
- name: GameDay Bot (fantasy_football_chat_bot)
  rows: 4
  url: /applications/sports-fantasy/gameday-bot-fantasy-football-chat-bot/
- name: MMM-MyScoreboard
  rows: 2
  url: /applications/sports-fantasy/mmm-myscoreboard/
- name: Sleeper
  rows: 8
  url: /applications/sports-fantasy/sleeper/
- name: Team Tracker (Home Assistant)
  rows: 4
  url: /applications/sports-fantasy/team-tracker-home-assistant/
- name: theScore
  rows: 26
  url: /applications/sports-fantasy/thescore/
sitemap: true
title: 'Yahoo Fantasy: Sports Scores & Fantasy reference app'
---
