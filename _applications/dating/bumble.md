---
app: Bumble
app_slug: bumble
app_url: https://bumble.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.30.10
  key: AE-160.30.10
  layer: domain
  name: Document Verification
  providers:
  - Veriff
  url: /capabilities/identity-verification/
  via_parent: Identity Verification
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
  id: AE-150.50.20
  key: AE-150.50.20
  layer: domain
  name: Number Verification
  providers:
  - Prove
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: Turbo EA
  id: BC-3780.40
  key: user-generated-content-moderation
  layer: domain
  name: User-Generated Content Moderation
  providers:
  - Cinder
  url: /capabilities/user-generated-content-moderation/
  via_parent: null
- attribution: Turbo EA
  id: BC-3770.50
  key: audience-insights-research-management
  layer: common
  name: Audience Insights & Research Management
  providers:
  - Kantar
  url: /capabilities/audience-insights-research-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - Google Cloud
  url: /capabilities/it-infrastructure-management/
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
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Apple
  - Google Play
  url: /capabilities/in-app-purchases-app-store-billing/
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
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.30
  key: AE-150.20.30
  layer: common
  name: One-Time Passcodes
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook
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
  - Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Facebook
  - Instagram
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-100.70.30
  key: AE-100.70.30
  layer: agent
  name: Support & Assist Agents
  providers:
  - Sierra
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
category:
  id: dating
  name: Dating
  url: /applications/dating/
counts:
  declared: 16
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
- route: documentation
  url: https://bumble.com/en/privacy
integrations:
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
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id005
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id006
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id009
      status: none
    slug: facebook
    status: profiled
    tags: &id010
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    mcp: &id011
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id012
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    mcp: &id013
      status: none
    slug: google-admob
    status: profiled
    tags: &id014
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    kin_score: 80.6
    mcp: &id029
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id030
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts: *id002
  layer: common
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3780.40
    key: user-generated-content-moderation
    name: User-Generated Content Moderation
    url: /capabilities/user-generated-content-moderation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id007
      status: unknown
    slug: cinder
    status: profiled
    tags: &id008
    - Company
    - Content Moderation
    - Security
    - Trust and Safety
    url: /providers/cinder/
  layer: domain
  name: Cinder
  provider: cinder
  says: lists Cinder as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.7
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id015
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id016
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: common
  name: Google Cloud
  provider: google-cloud-platform
  says: lists Google Cloud as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id017
      status: none
    slug: google-play
    status: profiled
    tags: &id018
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play
  provider: google-play
  says: lists Google Play as an integration
  source: https://bumble.com/en/privacy
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
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id019
      status: none
    slug: instagram
    status: profiled
    tags: &id020
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3770.50
    key: audience-insights-research-management
    name: Audience Insights & Research Management
    url: /capabilities/audience-insights-research-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id021
      status: unknown
    slug: kantar
    status: profiled
    tags: &id022
    - Analytics
    - Data
    - Insights
    - Market Research
    url: /providers/kantar/
  layer: common
  name: Kantar
  provider: kantar
  says: lists Kantar as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id023
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id025
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id026
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.20
    key: AE-150.50.20
    name: Number Verification
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.6
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id027
      status: none
    slug: prove
    status: profiled
    tags: &id028
    - Authentication
    - Identity Verification
    - KYC
    - Phone Intelligence
    url: /providers/prove/
  layer: domain
  name: Prove
  provider: prove
  says: lists Prove as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.30
    key: AE-100.70.30
    name: Support & Assist Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 9.3
    band: emerging
    in_catalog: true
    kin_score: 17.8
    mcp: &id031
      status: none
    slug: sierra
    status: profiled
    tags: &id032
    - Agents
    - Artificial Intelligence
    - Chat
    - Conversational AI
    url: /providers/sierra/
  layer: agent
  name: Sierra
  provider: sierra
  says: lists Sierra as an integration
  source: https://bumble.com/en/privacy
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
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
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
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id035
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id036
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.5
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id037
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id038
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: common
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.10
    key: AE-160.30.10
    name: Document Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id039
      status: none
    slug: veriff
    status: profiled
    tags: &id040
    - Biometrics
    - Fraud Prevention
    - Identity Verification
    - KYC
    url: /providers/veriff/
  layer: domain
  name: Veriff
  provider: veriff
  says: lists Veriff as an integration
  source: https://bumble.com/en/privacy
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id041
      status: none
    slug: zendesk
    status: profiled
    tags: &id042
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://bumble.com/en/privacy
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/dating/bumble/
providers:
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id005
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id006
  url: /providers/appsflyer/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id007
  name: Cinder
  slug: cinder
  status: profiled
  tags: *id008
  url: /providers/cinder/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id009
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id010
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id011
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id012
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id013
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id014
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 50.7
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id015
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id016
  url: /providers/google-cloud-platform/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id017
  name: Google Play
  slug: google-play
  status: profiled
  tags: *id018
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id019
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id020
  url: /providers/instagram/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id021
  name: Kantar
  slug: kantar
  status: profiled
  tags: *id022
  url: /providers/kantar/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id023
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id024
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id025
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id026
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id027
  name: Prove
  slug: prove
  status: profiled
  tags: *id028
  url: /providers/prove/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id029
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id030
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 9.3
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id031
  name: Sierra
  slug: sierra
  status: profiled
  tags: *id032
  url: /providers/sierra/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id033
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id034
  url: /providers/spotify/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id035
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id036
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 43.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id037
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id038
  url: /providers/typeform/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id039
  name: Veriff
  slug: veriff
  status: profiled
  tags: *id040
  url: /providers/veriff/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id041
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id042
  url: /providers/zendesk/
siblings:
- name: Alovoa
  rows: 2
  url: /applications/dating/alovoa/
- name: Duolicious
  rows: 9
  url: /applications/dating/duolicious/
- name: Grindr
  rows: 24
  url: /applications/dating/grindr/
- name: Hinge
  rows: 53
  url: /applications/dating/hinge/
- name: pH7Builder
  rows: 8
  url: /applications/dating/ph7builder/
- name: Tinder
  rows: 15
  url: /applications/dating/tinder/
sitemap: true
title: 'Bumble: Dating reference app'
---
