---
access: understanding
agent_layer: []
apps:
- anchor: jitsi-meet
  counts:
    declared: 0
    observed: 9
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
    layer: domain
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
    tier: observed
  kind: self-hosted
  name: Jitsi Meet
  page: /applications/video-conferencing/jitsi-meet/
  slug: jitsi-meet
  url: https://github.com/jitsi/jitsi-meet
- anchor: bigbluebutton
  counts:
    declared: 1
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
  - route: source code
    url: https://raw.githubusercontent.com/bigbluebutton/bbb-transcription-controller/main/config/default.example.yml
  - route: source code
    url: https://raw.githubusercontent.com/bigbluebutton/bigbluebutton/develop/bigbluebutton-web/grails-app/conf/bigbluebutton.properties
  - route: source code
    url: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/sample.env
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Gladia
    provider: gladia
    says: ships the Gladia SDK or integration code
    source: https://raw.githubusercontent.com/bigbluebutton/bbb-transcription-controller/main/config/default.example.yml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Papertrail
    provider: papertrail
    says: lists Papertrail as an integration
    source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/sample.env
    tier: declared
  kind: self-hosted
  name: BigBlueButton
  page: /applications/video-conferencing/bigbluebutton/
  slug: bigbluebutton
  url: https://github.com/bigbluebutton/bigbluebutton
- anchor: livekit-meet
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
  - route: source code
    url: https://raw.githubusercontent.com/livekit-examples/meet/main/.env.example
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30
      key: AE-110.30
      name: Speech & Voice
      url: /capabilities/speech-voice/
      via_parent: null
    credit: null
    layer: domain
    name: Krisp
    provider: krisp
    says: ships the Krisp SDK or integration code
    source: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: LiveKit (Cloud or self-hosted SFU)
    provider: livekit
    says: ships the LiveKit (Cloud or self-hosted SFU) SDK or integration code
    source: https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
    tier: observed
  kind: open-source-saas
  name: LiveKit Meet
  page: /applications/video-conferencing/livekit-meet/
  slug: livekit-meet
  url: https://github.com/livekit-examples/meet
- anchor: nextcloud-talk
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.nextcloud.talk2/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/nextcloud/spreed/main/composer.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/nextcloud/spreed/main/package.json
  - route: source code
    url: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Rocket.Chat
    provider: rocketchat
    says: ships the Rocket.Chat SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Steam chat
    provider: steam
    says: ships the Steam chat SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Zulip
    provider: zulip
    says: ships the Zulip SDK or integration code
    source: https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
    tier: observed
  kind: self-hosted
  name: Nextcloud Talk
  page: /applications/video-conferencing/nextcloud-talk/
  slug: nextcloud-talk
  url: https://github.com/nextcloud/spreed
- anchor: zoom
  counts:
    declared: 7
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/us.zoom.videomeetings/latest/
  - route: integrations page
    url: https://www.zoom.com/en/products/collaboration-tools/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Atlassian
    provider: atlassian
    says: lists Atlassian as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google
    provider: google
    says: lists Google as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft
    provider: microsoft
    says: lists Microsoft as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle
    provider: oracle
    says: lists Oracle as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: domain
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://www.zoom.com/en/products/collaboration-tools/
    tier: declared
  kind: commercial
  name: Zoom
  page: /applications/video-conferencing/zoom/
  slug: zoom
  url: https://zoom.us/
- anchor: webex-meetings
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.cisco.webex.meetings/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cisco.webex.meetings/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cisco.webex.meetings/latest/
    tier: observed
  kind: commercial
  name: Webex Meetings
  page: /applications/video-conferencing/webex-meetings/
  slug: webex-meetings
  url: https://www.webex.com/
- anchor: microsoft-teams
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.teams/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Visual Studio App Center Crashes
    provider: microsoft-app-center
    says: ships the Visual Studio App Center Crashes SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.teams/latest/
    tier: observed
  kind: commercial
  name: Microsoft Teams
  page: /applications/video-conferencing/microsoft-teams/
  slug: microsoft-teams
  url: https://www.microsoft.com/microsoft-teams/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: video-conferencing
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Communication
  store: google-play
  url: https://play.google.com/store/apps/category/COMMUNICATION
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Communication - Video Conferencing
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---video-conferencing
- category: Communication
  store: slack-marketplace
  url: https://slack.com/apps
- category: Video
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Video & Audio
  store: zapier
  url: https://zapier.com/apps
name: Video Conferencing & Webinars
needs:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: Client analytics in the apps.
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: Avatars and GIF pickers inside the meeting UI; no avatar or GIF node exists.
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: Calendar integration to list and join scheduled meetings.
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Sign in with Google (also unlocks calendar and YouTube scopes).
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Recording and upload storage; no generic object-storage capability exists.
- capability:
    attribution: Turbo EA
    id: BC-3740.20.30
    key: BC-3740.20.30
    name: Live Streaming Operations
    url: /capabilities/ott-streaming-delivery/
    via_parent: OTT & Streaming Delivery
  fit: exact
  layer: domain
  why: Live-streaming a meeting out to a public video platform.
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: Crash reporting and log shipping.
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: CAPTCHA on room sign-up.
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: Live captions and meeting transcription.
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: 'The meeting itself: the hosted WebRTC/SFU media layer an app builds on instead of running its own.'
- capability:
    attribution: API Evangelist extension
    id: AE-110.30
    key: AE-110.30
    name: Speech & Voice
    url: /capabilities/speech-voice/
    via_parent: null
  fit: exact
  layer: domain
  why: Noise suppression / speech enhancement on the call audio (Krisp).
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: domain
  why: Bridging meeting chat into team-chat platforms; no team-chat interop node exists.
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: Partner workplace suites a commercial meeting product plugs into.
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: Workforce SSO into the meeting product.
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Nextcloud Talk
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Nextcloud Talk
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Nextcloud Talk
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Nextcloud Talk
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Nextcloud Talk
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Nextcloud Talk
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        status: none
      name: Steam chat
      slug: steam
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Distribution
      - Gaming
      - Steamworks
      - Valve
      tier: observed
      url: /providers/steam/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Nextcloud Talk
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        source: https://github.com/zulip/zulipmcp
        status: verified
      name: Zulip
      slug: zulip
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Team Chat
      - Webhook
      tier: observed
      url: /providers/zulip/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Nextcloud Talk
      band: minimal
      in_catalog: true
      kin_score: 2.9
      mcp:
        source: https://docs.rocket.chat/docs/mcp-server
        status: verified
      name: Rocket.Chat
      slug: rocketchat
      sources:
      - https://raw.githubusercontent.com/nextcloud/spreed/main/src/components/ConversationSettings/Matterbridge/matterbridgeTypes.ts
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Open Source
      tier: observed
      url: /providers/rocketchat/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Zoom
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Zoom
      band: exemplar
      in_catalog: true
      kin_score: 79.8
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Atlassian
      slug: atlassian
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Code
      - Collaboration
      - Platform
      - Productivity
      tier: declared
      url: /providers/atlassian/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Zoom
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft
      slug: microsoft
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Cloud
      - Fortune 100
      - Microsoft
      - Software
      tier: declared
      url: /providers/microsoft/
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Zoom
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle
      slug: oracle
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Zoom
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google
      slug: google
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Zoom
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Jitsi Meet
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph (Outlook calendar)
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Jitsi Meet
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
  - capability:
      attribution: Turbo EA
      id: BC-3740.20.30
      key: BC-3740.20.30
      name: Live Streaming Operations
      url: /capabilities/ott-streaming-delivery/
      via_parent: OTT & Streaming Delivery
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Jitsi Meet
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30
      key: AE-110.30
      name: Speech & Voice
      url: /capabilities/speech-voice/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - LiveKit Meet
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        status: none
      name: Krisp
      slug: krisp
      sources:
      - https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Speech
      - Voice AI
      tier: observed
      url: /providers/krisp/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - BigBlueButton
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/gladiaio/gladia-mcp
        status: verified
      name: Gladia
      slug: gladia
      sources:
      - https://raw.githubusercontent.com/bigbluebutton/bbb-transcription-controller/main/config/default.example.yml
      status: profiled
      tags:
      - Audio Intelligence
      - Real-Time
      - Speech-to-Text
      - Transcription
      tier: observed
      url: /providers/gladia/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - LiveKit Meet
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: LiveKit (Cloud or self-hosted SFU)
      slug: livekit
      sources:
      - https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
      status: profiled
      tags:
      - Audio
      - Real-Time
      - Video
      - WebRTC
      tier: observed
      url: /providers/livekit/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - LiveKit Meet
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://raw.githubusercontent.com/livekit-examples/meet/main/package.json
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Jitsi Meet
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics, Analytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.jitsi.meet/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: null
      agent_readiness: null
      apps:
      - Microsoft Teams
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Visual Studio App Center Crashes
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.teams/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - BigBlueButton
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Papertrail
      slug: papertrail
      sources:
      - https://raw.githubusercontent.com/bigbluebutton/greenlight/master/sample.env
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Jitsi Meet
      - Webex Meetings
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.cisco.webex.meetings/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Webex Meetings
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cisco.webex.meetings/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Jitsi Meet
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: observed
      url: /providers/giphy/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Jitsi Meet
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/config.js
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - BigBlueButton
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - BigBlueButton
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - BigBlueButton
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Jitsi Meet
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Jitsi Meet
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/jitsi/jitsi-meet/master/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Zoom
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.zoom.com/en/products/collaboration-tools/
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
  layer: common
summary:
  coverage_pct: 93.9
  declared_only: 8
  distinct_providers: 33
  in_catalog: 31
  mcp:
    documented: 0
    none: 11
    unchecked: 2
    verified: 20
  mcp_verified: 20
  mean_kin_score: 58.1
  observed: 25
  queued: 2
  reference_apps: 7
title: 'Video Conferencing & Webinars: application blueprint'
---
