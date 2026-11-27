---
app: Planning Center
app_slug: planning-center
app_url: https://www.planningcenter.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Checkr
  - MinistrySafe
  - Protect My Ministry
  - Verified First
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: API Evangelist extension
  id: AE-170.10.40
  key: AE-170.10.40
  layer: domain
  name: Live Presentation & Broadcast Control
  providers:
  - ProPresenter (Renewed Vision)
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3740.20
  key: ott-streaming-delivery
  layer: domain
  name: OTT & Streaming Delivery
  providers:
  - BoxCast
  url: /capabilities/ott-streaming-delivery/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.70
  key: AE-170.20.70
  layer: domain
  name: Worship Song Licensing & Chord Charts
  providers:
  - CCLI SongSelect
  - PraiseCharts
  - RehearsalMix
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  - Firebase
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Pendo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Clearstream (church texting)
  - Text In Church
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: church-faith-management
  name: Church & Faith Community Management
  url: /applications/church-faith-management/
counts:
  declared: 13
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
- route: integrations page
  url: https://www.planningcenter.com/integrations
integrations:
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id004
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id005
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id012
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id013
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
    mcp: &id014
      status: none
    slug: google-admob
    status: profiled
    tags: &id015
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id020
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id021
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: ships the Pendo SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id028
      status: none
    slug: pusher
    status: profiled
    tags: &id029
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id032
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id033
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3740.20
    key: ott-streaming-delivery
    name: OTT & Streaming Delivery
    url: /capabilities/ott-streaming-delivery/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id002
      status: none
    slug: boxcast
    status: profiled
    tags: &id003
    - Company
    - Live
    - Streaming
    - Video
    url: /providers/boxcast/
  layer: domain
  name: BoxCast
  provider: boxcast
  says: lists BoxCast as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.70
    key: AE-170.20.70
    name: Worship Song Licensing & Chord Charts
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id006
      status: unchecked
    slug: ccli
    status: profiled
    tags: &id007
    - Company
    - Licensing
    - Music
    - Worship
    url: /providers/ccli/
  layer: domain
  name: CCLI SongSelect
  provider: ccli
  says: lists CCLI SongSelect as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.8
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id008
      status: none
    slug: checkr
    status: profiled
    tags: &id009
    - Background Checks
    - Compliance
    - Employment Screening
    - Human Resources
    url: /providers/checkr/
  layer: domain
  name: Checkr
  provider: checkr
  says: lists Checkr as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id010
      status: unchecked
    slug: clearstream-io
    status: profiled
    tags: &id011
    - Church
    - Company
    - Messaging
    - SMS
    url: /providers/clearstream-io/
  layer: common
  name: Clearstream (church texting)
  provider: clearstream-io
  says: lists Clearstream (church texting) as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id016
      status: none
    slug: mailchimp
    status: profiled
    tags: &id017
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id018
      status: unchecked
    slug: ministrysafe
    status: profiled
    tags: &id019
    - Child Safety
    - Education
    - Non-Profit
    - Training
    url: /providers/ministrysafe/
  layer: domain
  name: MinistrySafe
  provider: ministrysafe
  says: lists MinistrySafe as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.70
    key: AE-170.20.70
    name: Worship Song Licensing & Chord Charts
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id022
      status: unchecked
    slug: praisecharts
    status: profiled
    tags: &id023
    - Christian
    - Music
    - Sheet Music
    - Worship
    url: /providers/praisecharts/
  layer: domain
  name: PraiseCharts
  provider: praisecharts
  says: lists PraiseCharts as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.40
    key: AE-170.10.40
    name: Live Presentation & Broadcast Control
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id024
      status: unchecked
    slug: renewed-vision
    status: profiled
    tags: &id025
    - Company
    - Live Production
    - Media
    - Presentation
    url: /providers/renewed-vision/
  layer: domain
  name: ProPresenter (Renewed Vision)
  provider: renewed-vision
  says: lists ProPresenter (Renewed Vision) as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id026
      status: unchecked
    slug: protect-my-ministry
    status: profiled
    tags: &id027
    - Background Checks
    - Child Safety Training
    - Church Screening
    - Volunteer Screening
    url: /providers/protect-my-ministry/
  layer: domain
  name: Protect My Ministry
  provider: protect-my-ministry
  says: lists Protect My Ministry as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.70
    key: AE-170.20.70
    name: Worship Song Licensing & Chord Charts
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id030
      status: unchecked
    slug: rehearsalmix
    status: profiled
    tags: &id031
    - Audio
    - Collaboration
    - Music
    - Rehearsal
    url: /providers/rehearsalmix/
  layer: domain
  name: RehearsalMix
  provider: rehearsalmix
  says: lists RehearsalMix as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: developing
    in_catalog: true
    kin_score: 43.1
    mcp: &id034
      status: unchecked
    slug: text-in-church
    status: profiled
    tags: &id035
    - Church
    - Communications
    - Company
    - Messaging
    url: /providers/text-in-church/
  layer: common
  name: Text In Church
  provider: text-in-church
  says: lists Text In Church as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id036
      status: none
    slug: verified-first
    status: profiled
    tags: &id037
    - Background Checks
    - Company
    - Screening
    - Verification
    url: /providers/verified-first/
  layer: domain
  name: Verified First
  provider: verified-first
  says: lists Verified First as an integration
  source: https://www.planningcenter.com/integrations
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id038
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id039
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.planningcenter.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/church-faith-management/planning-center/
providers:
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id002
  name: BoxCast
  slug: boxcast
  status: profiled
  tags: *id003
  url: /providers/boxcast/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id004
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id005
  url: /providers/bugsnag/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id006
  name: CCLI SongSelect
  slug: ccli
  status: profiled
  tags: *id007
  url: /providers/ccli/
- agent_band: agent-ready
  agent_readiness: 52.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id008
  name: Checkr
  slug: checkr
  status: profiled
  tags: *id009
  url: /providers/checkr/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id010
  name: Clearstream (church texting)
  slug: clearstream-io
  status: profiled
  tags: *id011
  url: /providers/clearstream-io/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id012
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id013
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id014
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id015
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id016
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id017
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id018
  name: MinistrySafe
  slug: ministrysafe
  status: profiled
  tags: *id019
  url: /providers/ministrysafe/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id020
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id021
  url: /providers/pendoio/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id022
  name: PraiseCharts
  slug: praisecharts
  status: profiled
  tags: *id023
  url: /providers/praisecharts/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id024
  name: ProPresenter (Renewed Vision)
  slug: renewed-vision
  status: profiled
  tags: *id025
  url: /providers/renewed-vision/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id026
  name: Protect My Ministry
  slug: protect-my-ministry
  status: profiled
  tags: *id027
  url: /providers/protect-my-ministry/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id028
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id029
  url: /providers/pusher/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id030
  name: RehearsalMix
  slug: rehearsalmix
  status: profiled
  tags: *id031
  url: /providers/rehearsalmix/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id032
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id033
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: developing
  in_catalog: true
  kin_score: 43.1
  mcp: *id034
  name: Text In Church
  slug: text-in-church
  status: profiled
  tags: *id035
  url: /providers/text-in-church/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id036
  name: Verified First
  slug: verified-first
  status: profiled
  tags: *id037
  url: /providers/verified-first/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id038
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id039
  url: /providers/zapier/
siblings:
- name: ChurchCRM
  rows: 7
  url: /applications/church-faith-management/churchcrm/
- name: OpenLP
  rows: 6
  url: /applications/church-faith-management/openlp/
- name: Pushpay
  rows: 20
  url: /applications/church-faith-management/pushpay/
- name: Rock RMS
  rows: 21
  url: /applications/church-faith-management/rock-rms/
- name: Tithe.ly
  rows: 11
  url: /applications/church-faith-management/tithe-ly/
sitemap: true
title: 'Planning Center: Church & Faith Community Management reference app'
---
