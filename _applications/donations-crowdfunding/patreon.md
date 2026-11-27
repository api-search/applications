---
app: Patreon
app_slug: patreon
app_url: https://www.patreon.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.60
  key: card-issuance-management
  layer: domain
  name: Card Issuance Management
  providers:
  - Karat (creator card)
  url: /capabilities/card-issuance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3280.50
  key: cash-and-treasury-operations
  layer: domain
  name: Cash and Treasury Operations
  providers:
  - Mercury
  url: /capabilities/cash-and-treasury-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-180.40
  key: AE-180.40
  layer: domain
  name: Game Publishing & Distribution
  providers:
  - itch.io
  url: /capabilities/game-publishing-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10
  key: AE-140.10
  layer: domain
  name: Storefront Platforms
  providers:
  - Sellfy
  url: /capabilities/storefront-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: common
  name: Content Management
  providers:
  - Wix
  url: /capabilities/content-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.60
  key: AE-160.60
  layer: common
  name: Credential Security
  providers:
  - Keeper
  url: /capabilities/credential-security/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - 99designs
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - ConvertKit (Kit)
  - ToneDen
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
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
  - Amplitude
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Facebook
  - Discord
  - Discourse
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30
  key: AE-110.30
  layer: common
  name: Speech & Voice
  providers:
  - Sonix
  url: /capabilities/speech-voice/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Crowdcast
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: common
  name: Video Platforms
  providers:
  - TubeBuddy
  - Vimeo
  url: /capabilities/video-platforms/
  via_parent: null
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
  id: donations-crowdfunding
  name: Donations & Crowdfunding
  url: /applications/donations-crowdfunding/
counts:
  declared: 16
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
- route: integrations page
  url: https://www.patreon.com/apps
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
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id005
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id006
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id007
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id008
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id020
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
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
    mcp: &id031
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id032
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.patreon.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.4
    band: strong
    in_catalog: true
    kin_score: 56.4
    mcp: &id003
      status: none
    slug: 99designs
    status: profiled
    tags: &id004
    - Company
    - Design
    - Marketplace
    - Media
    url: /providers/99designs/
  layer: common
  name: 99designs
  provider: 99designs
  says: lists 99designs as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 80.4
    mcp: &id009
      status: none
    slug: convertkit
    status: profiled
    tags: &id010
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: common
  name: ConvertKit (Kit)
  provider: convertkit
  says: lists ConvertKit (Kit) as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id011
      status: unknown
    slug: crowdcast
    status: profiled
    tags: &id012
    - Community
    - Live Streaming
    - Video
    - Webinars
    url: /providers/crowdcast/
  layer: common
  name: Crowdcast
  provider: crowdcast
  says: lists Crowdcast as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id013
      status: none
    slug: discord
    status: profiled
    tags: &id014
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id015
      source: https://github.com/discourse/discourse-mcp
      status: verified
    slug: discourse
    status: profiled
    tags: &id016
    - Community
    - Forums
    - Open Source
    url: /providers/discourse/
  layer: common
  name: Discourse
  provider: discourse
  says: lists Discourse as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-180.40
    key: AE-180.40
    name: Game Publishing & Distribution
    url: /capabilities/game-publishing-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id021
      status: none
    slug: itch-io
    status: profiled
    tags: &id022
    - Game Distribution
    - Game Marketplace
    - Games
    - Indie Games
    url: /providers/itch-io/
  layer: domain
  name: itch.io
  provider: itch-io
  says: lists itch.io as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.60
    key: card-issuance-management
    name: Card Issuance Management
    url: /capabilities/card-issuance-management/
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
    slug: karat-financial
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: Karat (creator card)
  provider: karat-financial
  says: lists Karat (creator card) as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.6
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id025
      source: https://github.com/Keeper-Security/keeper-mcp-golang-docker
      status: verified
    slug: keeper-security
    status: profiled
    tags: &id026
    - Company
    - Cybersecurity
    - Password Manager
    - Secrets Management
    url: /providers/keeper-security/
  layer: common
  name: Keeper
  provider: keeper-security
  says: lists Keeper as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3280.50
    key: cash-and-treasury-operations
    name: Cash and Treasury Operations
    url: /capabilities/cash-and-treasury-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id027
      source: https://mercury.com/mcp
      status: verified
    slug: mercury
    status: profiled
    tags: &id028
    - Banking
    - Fintech
    - Startups
    - Treasury
    url: /providers/mercury/
  layer: domain
  name: Mercury
  provider: mercury
  says: lists Mercury as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10
    key: AE-140.10
    name: Storefront Platforms
    url: /capabilities/storefront-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id029
      source: https://sellfy.com/mcp/
      status: verified
    slug: sellfy
    status: profiled
    tags: &id030
    - Digital Products
    - E-Commerce
    - Payments
    - Software-as-a-Service
    url: /providers/sellfy/
  layer: domain
  name: Sellfy
  provider: sellfy
  says: lists Sellfy as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30
    key: AE-110.30
    name: Speech & Voice
    url: /capabilities/speech-voice/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id033
      status: none
    slug: sonix
    status: profiled
    tags: &id034
    - Audio Transcription
    - Speech-to-Text
    - Subtitles
    - Transcription
    url: /providers/sonix/
  layer: common
  name: Sonix
  provider: sonix
  says: lists Sonix as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id035
      status: unchecked
    slug: toneden
    status: queued for profiling
    tags: &id036 []
    url: null
  layer: common
  name: ToneDen
  provider: toneden
  says: lists ToneDen as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.5
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id037
      status: unknown
    slug: tubebuddy
    status: profiled
    tags: &id038
    - Company
    - SEO
    - VideoTools
    - YouTube
    url: /providers/tubebuddy/
  layer: common
  name: TubeBuddy
  provider: tubebuddy
  says: lists TubeBuddy as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id039
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id040
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: common
  name: Vimeo
  provider: vimeo
  says: lists Vimeo as an integration
  source: https://www.patreon.com/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id041
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id042
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: common
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://www.patreon.com/apps
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
    mcp: &id043
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id044
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.patreon.com/apps
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/donations-crowdfunding/patreon/
providers:
- agent_band: agent-aware
  agent_readiness: 27.4
  band: strong
  in_catalog: true
  kin_score: 56.4
  mcp: *id003
  name: 99designs
  slug: 99designs
  status: profiled
  tags: *id004
  url: /providers/99designs/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id005
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id006
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id007
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id008
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 80.4
  mcp: *id009
  name: ConvertKit (Kit)
  slug: convertkit
  status: profiled
  tags: *id010
  url: /providers/convertkit/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id011
  name: Crowdcast
  slug: crowdcast
  status: profiled
  tags: *id012
  url: /providers/crowdcast/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id013
  name: Discord
  slug: discord
  status: profiled
  tags: *id014
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id015
  name: Discourse
  slug: discourse
  status: profiled
  tags: *id016
  url: /providers/discourse/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id019
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id020
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id021
  name: itch.io
  slug: itch-io
  status: profiled
  tags: *id022
  url: /providers/itch-io/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: Karat (creator card)
  slug: karat-financial
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-aware
  agent_readiness: 14.6
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id025
  name: Keeper
  slug: keeper-security
  status: profiled
  tags: *id026
  url: /providers/keeper-security/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id027
  name: Mercury
  slug: mercury
  status: profiled
  tags: *id028
  url: /providers/mercury/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id029
  name: Sellfy
  slug: sellfy
  status: profiled
  tags: *id030
  url: /providers/sellfy/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id031
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id032
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id033
  name: Sonix
  slug: sonix
  status: profiled
  tags: *id034
  url: /providers/sonix/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id035
  name: ToneDen
  slug: toneden
  status: queued for profiling
  tags: *id036
  url: null
- agent_band: agent-aware
  agent_readiness: 21.5
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id037
  name: TubeBuddy
  slug: tubebuddy
  status: profiled
  tags: *id038
  url: /providers/tubebuddy/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id039
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id040
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id041
  name: Wix
  slug: wix
  status: profiled
  tags: *id042
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id043
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id044
  url: /providers/zapier/
siblings:
- name: Givebutter
  rows: 50
  url: /applications/donations-crowdfunding/givebutter/
- name: GiveWP
  rows: 3
  url: /applications/donations-crowdfunding/givewp/
- name: GoFundMe Pro (Classy)
  rows: 47
  url: /applications/donations-crowdfunding/gofundme-pro-classy/
- name: HCB (Hack Club Bank)
  rows: 13
  url: /applications/donations-crowdfunding/hcb-hack-club-bank/
- name: Liberapay
  rows: 4
  url: /applications/donations-crowdfunding/liberapay/
- name: Open Collective
  rows: 10
  url: /applications/donations-crowdfunding/open-collective/
sitemap: true
title: 'Patreon: Donations & Crowdfunding reference app'
---
