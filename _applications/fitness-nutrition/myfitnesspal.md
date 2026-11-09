---
app: MyFitnessPal
app_slug: myfitnesspal
app_url: https://www.myfitnesspal.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.20
  key: AE-130.10.20
  layer: domain
  name: Activity & Step Tracking
  providers:
  - accupedo
  - renpho
  - vesync
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.10.30
  key: AE-130.10.30
  layer: domain
  name: Running & Cycling Tracking
  providers:
  - runkeeper
  - strava
  - trainingpeaks
  - under-armour
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - fitbit
  - garmin
  - google
  - polar
  - withings
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.60
  key: AE-130.60
  layer: domain
  name: Women's & Reproductive Health
  providers:
  - glow-fertility
  url: /capabilities/women-s-reproductive-health/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.60
  key: advertising-revenue-reporting
  layer: common
  name: Advertising Revenue Reporting
  providers:
  - appsflyer
  url: /capabilities/advertising-revenue-reporting/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - split
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - facebook
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - amplitude
  - facebook
  - firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - amazon
  - fyber
  - google-admob
  - iab-tech-lab
  - unity
  url: /capabilities/programmatic-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: common
  name: Video Hosting & Encoding
  providers:
  - brightcove
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
category:
  id: fitness-nutrition
  name: Fitness & Nutrition Tracking
  url: /applications/fitness-nutrition/
counts:
  declared: 13
  observed: 13
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
- route: integrations page
  url: https://www.myfitnesspal.com/apps
integrations:
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
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id005
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id006
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: common
  name: amazon
  provider: amazon
  says: ships the amazon SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id007
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id008
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: amplitude
  provider: amplitude
  says: ships the amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.60
    key: advertising-revenue-reporting
    name: Advertising Revenue Reporting
    url: /capabilities/advertising-revenue-reporting/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id009
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id010
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: appsflyer
  provider: appsflyer
  says: ships the appsflyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id011
      status: none
    slug: brightcove
    status: profiled
    tags: &id012
    - Live Streaming
    - Media
    - Streaming
    - Video
    url: /providers/brightcove/
  layer: common
  name: brightcove
  provider: brightcove
  says: ships the brightcove SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id013
      status: none
    slug: facebook
    status: profiled
    tags: &id014
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: facebook
  provider: facebook
  says: ships the facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: facebook
  provider: facebook
  says: ships the facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id015
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id016
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: firebase
  provider: firebase
  says: ships the firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: common
  name: firebase
  provider: firebase
  says: ships the firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: fyber
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: common
  name: fyber
  provider: fyber
  says: ships the fyber SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id027
      status: none
    slug: google-admob
    status: profiled
    tags: &id028
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: google-admob
  provider: google-admob
  says: ships the google-admob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    mcp: &id029
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id030
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: iab-tech-lab
  provider: iab-tech-lab
  says: ships the iab-tech-lab SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id037
      status: none
    slug: split
    status: profiled
    tags: &id038
    - Experimentation
    - Feature Flags
    - Feature Management
    - Rollouts
    url: /providers/split/
  layer: common
  name: split
  provider: split
  says: ships the split SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
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
    agent_band: agent-aware
    agent_readiness: 25.8
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id045
      source: https://github.com/Unity-Technologies/industry-ai-workflows
      status: verified
    slug: unity
    status: profiled
    tags: &id046
    - Game Development
    - Game Services
    - Multiplayer
    - Real-Time 3D
    url: /providers/unity/
  layer: common
  name: unity
  provider: unity
  says: ships the unity SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.myfitnesspal.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.20
    key: AE-130.10.20
    name: Activity & Step Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id003
      status: unknown
    slug: accupedo
    status: profiled
    tags: &id004
    - Company
    - Fitness
    - Health
    - Mobile App
    url: /providers/accupedo/
  layer: domain
  name: accupedo
  provider: accupedo
  says: lists accupedo as an integration
  source: https://www.myfitnesspal.com/apps
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
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 61.6
    mcp: &id017
      status: none
    slug: fitbit
    status: profiled
    tags: &id018
    - Activity Tracking
    - Fitness
    - Health
    - Wearables
    url: /providers/fitbit/
  layer: domain
  name: fitbit
  provider: fitbit
  says: lists fitbit as an integration
  source: https://www.myfitnesspal.com/apps
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
    kin_score: 21.4
    mcp: &id021
      status: none
    slug: garmin
    status: profiled
    tags: &id022
    - Fitness
    - GPS
    - Outdoor
    - Wearables
    url: /providers/garmin/
  layer: domain
  name: garmin
  provider: garmin
  says: lists garmin as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.60
    key: AE-130.60
    name: Women's & Reproductive Health
    url: /capabilities/women-s-reproductive-health/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: glow-fertility
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: glow-fertility
  provider: glow-fertility
  says: lists glow-fertility as an integration
  source: https://www.myfitnesspal.com/apps
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
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id025
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id026
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: google
  provider: google
  says: lists google as an integration
  source: https://www.myfitnesspal.com/apps
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
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id031
      status: unknown
    slug: polar
    status: profiled
    tags: &id032
    - Fitness
    - Health
    - Heart Rate
    - Wearables
    url: /providers/polar/
  layer: domain
  name: polar
  provider: polar
  says: lists polar as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.20
    key: AE-130.10.20
    name: Activity & Step Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.4
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id033
      status: unknown
    slug: renpho
    status: profiled
    tags: &id034
    - Company
    - Health Tech
    - IoT
    - Wellness
    url: /providers/renpho/
  layer: domain
  name: renpho
  provider: renpho
  says: lists renpho as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.2
    mcp: &id035
      status: none
    slug: runkeeper
    status: profiled
    tags: &id036
    - Fitness
    - Mobile App
    - Social
    - Tracking
    url: /providers/runkeeper/
  layer: domain
  name: runkeeper
  provider: runkeeper
  says: lists runkeeper as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id039
      status: none
    slug: strava
    status: profiled
    tags: &id040
    - Cycling
    - Fitness
    - Fitness Tracking
    - Running
    url: /providers/strava/
  layer: domain
  name: strava
  provider: strava
  says: lists strava as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 30.2
    mcp: &id041
      status: none
    slug: trainingpeaks
    status: profiled
    tags: &id042
    - Coaching
    - Endurance Training
    - Fitness
    - Workouts
    url: /providers/trainingpeaks/
  layer: domain
  name: trainingpeaks
  provider: trainingpeaks
  says: lists trainingpeaks as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id043
      status: none
    slug: under-armour
    status: profiled
    tags: &id044
    - Connected Fitness
    - Fitness
    - Health
    - Wearables
    url: /providers/under-armour/
  layer: domain
  name: under-armour
  provider: under-armour
  says: lists under-armour as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.20
    key: AE-130.10.20
    name: Activity & Step Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.3
    mcp: &id047
      status: unknown
    slug: vesync
    status: profiled
    tags: &id048
    - Company
    - Consumer Electronics
    - IoT
    - Smart Home
    url: /providers/vesync/
  layer: domain
  name: vesync
  provider: vesync
  says: lists vesync as an integration
  source: https://www.myfitnesspal.com/apps
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id049
      status: none
    slug: withings
    status: profiled
    tags: &id050
    - Body Composition
    - Connected Devices
    - Health
    - Wearables
    url: /providers/withings/
  layer: domain
  name: withings
  provider: withings
  says: lists withings as an integration
  source: https://www.myfitnesspal.com/apps
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fitness-nutrition/myfitnesspal/
providers:
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id003
  name: accupedo
  slug: accupedo
  status: profiled
  tags: *id004
  url: /providers/accupedo/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id005
  name: amazon
  slug: amazon
  status: profiled
  tags: *id006
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id007
  name: amplitude
  slug: amplitude
  status: profiled
  tags: *id008
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id009
  name: appsflyer
  slug: appsflyer
  status: profiled
  tags: *id010
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id011
  name: brightcove
  slug: brightcove
  status: profiled
  tags: *id012
  url: /providers/brightcove/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id013
  name: facebook
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id015
  name: firebase
  slug: firebase
  status: profiled
  tags: *id016
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 61.6
  mcp: *id017
  name: fitbit
  slug: fitbit
  status: profiled
  tags: *id018
  url: /providers/fitbit/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: fyber
  slug: fyber
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id021
  name: garmin
  slug: garmin
  status: profiled
  tags: *id022
  url: /providers/garmin/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: glow-fertility
  slug: glow-fertility
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id025
  name: google
  slug: google
  status: profiled
  tags: *id026
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id027
  name: google-admob
  slug: google-admob
  status: profiled
  tags: *id028
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id029
  name: iab-tech-lab
  slug: iab-tech-lab
  status: profiled
  tags: *id030
  url: /providers/iab-tech-lab/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id031
  name: polar
  slug: polar
  status: profiled
  tags: *id032
  url: /providers/polar/
- agent_band: agent-aware
  agent_readiness: 7.4
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id033
  name: renpho
  slug: renpho
  status: profiled
  tags: *id034
  url: /providers/renpho/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id035
  name: runkeeper
  slug: runkeeper
  status: profiled
  tags: *id036
  url: /providers/runkeeper/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id037
  name: split
  slug: split
  status: profiled
  tags: *id038
  url: /providers/split/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id039
  name: strava
  slug: strava
  status: profiled
  tags: *id040
  url: /providers/strava/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 30.2
  mcp: *id041
  name: trainingpeaks
  slug: trainingpeaks
  status: profiled
  tags: *id042
  url: /providers/trainingpeaks/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id043
  name: under-armour
  slug: under-armour
  status: profiled
  tags: *id044
  url: /providers/under-armour/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id045
  name: unity
  slug: unity
  status: profiled
  tags: *id046
  url: /providers/unity/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.3
  mcp: *id047
  name: vesync
  slug: vesync
  status: profiled
  tags: *id048
  url: /providers/vesync/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id049
  name: withings
  slug: withings
  status: profiled
  tags: *id050
  url: /providers/withings/
siblings:
- name: Cronometer
  rows: 13
  url: /applications/fitness-nutrition/cronometer/
- name: Endurain
  rows: 3
  url: /applications/fitness-nutrition/endurain/
- name: FitTrackee
  rows: 1
  url: /applications/fitness-nutrition/fittrackee/
- name: Lose It!
  rows: 9
  url: /applications/fitness-nutrition/lose-it/
- name: Mealie
  rows: 1
  url: /applications/fitness-nutrition/mealie/
- name: SparkyFitness
  rows: 28
  url: /applications/fitness-nutrition/sparkyfitness/
- name: Strava
  rows: 17
  url: /applications/fitness-nutrition/strava/
- name: Tandoor Recipes
  rows: 2
  url: /applications/fitness-nutrition/tandoor-recipes/
- name: wger
  rows: 2
  url: /applications/fitness-nutrition/wger/
sitemap: true
title: 'MyFitnessPal: Fitness & Nutrition Tracking reference app'
---
