---
app: ESPN
app_slug: espn
app_url: https://www.espn.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Adobe Experience Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Kochava
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Comscore
  - Conviva
  - Google Firebase Analytics
  - Nielsen
  - Parse.ly
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
category:
  id: sports-fantasy
  name: Sports Scores & Fantasy
  url: /applications/sports-fantasy/
counts:
  declared: 0
  observed: 10
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 54.1
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id002
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id003
      status: none
    slug: comscore
    status: profiled
    tags: &id004
    - Audience Analytics
    - Cloud Saas
    - Company
    - Media Measurement
    url: /providers/comscore/
  layer: common
  name: Comscore
  provider: comscore
  says: ships the Comscore SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id005
      source: https://github.com/Conviva/mcp-marketplace
      status: verified
    slug: conviva
    status: profiled
    tags: &id006
    - Analytics
    - Observability
    - Streaming
    - Video
    url: /providers/conviva/
  layer: common
  name: Conviva
  provider: conviva
  says: ships the Conviva SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    mcp: &id007
      status: none
    slug: google-admob
    status: profiled
    tags: &id008
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    mcp: &id011
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id012
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: kochava
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: common
  name: Kochava
  provider: kochava
  says: ships the Kochava SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    agent_readiness: 45.7
    band: exemplar
    in_catalog: true
    kin_score: 76.5
    mcp: &id015
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id016
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    agent_readiness: 3.6
    band: emerging
    in_catalog: true
    kin_score: 11.3
    mcp: &id017
      status: unknown
    slug: nielsen
    status: profiled
    tags: &id018
    - Audience Measurement
    - Company
    - DataInsights
    - Media Analytics
    url: /providers/nielsen/
  layer: common
  name: Nielsen
  provider: nielsen
  says: ships the Nielsen SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: parse-ly
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: common
  name: Parse.ly
  provider: parse-ly
  says: ships the Parse.ly SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sports-fantasy/espn/
providers:
- agent_band: agent-ready
  agent_readiness: 54.1
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id001
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id002
  url: /providers/adobe-experience-cloud/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id003
  name: Comscore
  slug: comscore
  status: profiled
  tags: *id004
  url: /providers/comscore/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id005
  name: Conviva
  slug: conviva
  status: profiled
  tags: *id006
  url: /providers/conviva/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id007
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id008
  url: /providers/google-admob/
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
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id011
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id012
  url: /providers/iab-tech-lab/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Kochava
  slug: kochava
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id015
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id016
  url: /providers/new-relic/
- agent_band: human-only
  agent_readiness: 3.6
  band: emerging
  in_catalog: true
  kin_score: 11.3
  mcp: *id017
  name: Nielsen
  slug: nielsen
  status: profiled
  tags: *id018
  url: /providers/nielsen/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Parse.ly
  slug: parse-ly
  status: queued for profiling
  tags: *id020
  url: null
siblings:
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
- name: Yahoo Fantasy
  rows: 8
  url: /applications/sports-fantasy/yahoo-fantasy/
sitemap: true
title: 'ESPN: Sports Scores & Fantasy reference app'
---
