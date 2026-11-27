---
app: Jitsi Meet
app_slug: jitsi-meet
app_url: https://github.com/jitsi/jitsi-meet
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3740.20.30
  key: BC-3740.20.30
  layer: domain
  name: Live Streaming Operations
  providers:
  - YouTube
  url: /capabilities/ott-streaming-delivery/
  via_parent: OTT & Streaming Delivery
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Microsoft Graph (Outlook calendar)
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - GIPHY
  - Gravatar
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics, Analytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: video-conferencing
  name: Video Conferencing & Webinars
  url: /applications/video-conferencing/
counts:
  declared: 0
  observed: 9
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.jitsi.meet/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
- route: source code
  url: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id003
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id004
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
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
  name: Firebase (Crashlytics, Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics, Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.jitsi.meet/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id007
      status: none
    slug: giphy
    status: profiled
    tags: &id008
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
  layer: common
  name: GIPHY
  provider: giphy
  says: ships the GIPHY SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id010
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id013
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id014
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
  layer: common
  name: Gravatar
  provider: gravatar
  says: ships the Gravatar SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
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
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id016
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: domain
  name: Microsoft Graph (Outlook calendar)
  provider: microsoft-graph
  says: ships the Microsoft Graph (Outlook calendar) SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3740.20.30
    key: BC-3740.20.30
    name: Live Streaming Operations
    url: /capabilities/ott-streaming-delivery/
    via_parent: OTT & Streaming Delivery
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id017
      status: none
    slug: youtube
    status: profiled
    tags: &id018
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-conferencing/jitsi-meet/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id003
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id004
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Firebase (Crashlytics, Analytics)
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id007
  name: GIPHY
  slug: giphy
  status: profiled
  tags: *id008
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id009
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id010
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id013
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id014
  url: /providers/gravatar/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id015
  name: Microsoft Graph (Outlook calendar)
  slug: microsoft-graph
  status: profiled
  tags: *id016
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id017
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id018
  url: /providers/youtube/
siblings:
- name: BigBlueButton
  rows: 5
  url: /applications/video-conferencing/bigbluebutton/
- name: LiveKit Meet
  rows: 3
  url: /applications/video-conferencing/livekit-meet/
- name: Microsoft Teams
  rows: 1
  url: /applications/video-conferencing/microsoft-teams/
- name: Nextcloud Talk
  rows: 8
  url: /applications/video-conferencing/nextcloud-talk/
- name: Webex Meetings
  rows: 2
  url: /applications/video-conferencing/webex-meetings/
- name: Zoom
  rows: 7
  url: /applications/video-conferencing/zoom/
sitemap: true
title: 'Jitsi Meet: Video Conferencing & Webinars reference app'
---
