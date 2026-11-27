---
app: Mindbody
app_slug: mindbody
app_url: https://www.mindbodyonline.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.50
  key: AE-130.10.50
  layer: domain
  name: Fitness Class Aggregators & Corporate Wellness Networks
  providers:
  - ClassPass
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: Turbo EA
  id: BC-4050.10
  key: loyalty-programme-design
  layer: domain
  name: Loyalty Programme Design
  providers:
  - Referrizer
  url: /capabilities/loyalty-programme-design/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - QuickerNotes
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Tealium
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook
  - REACH ai
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - Constant Contact
  - Klaviyo
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Bench
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: common
  name: Hosted Storefronts
  providers:
  - Shopify (ShopifyConnect)
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-150.40
  key: AE-150.40
  layer: common
  name: In-App Chat
  providers:
  - Healthdesk
  url: /capabilities/in-app-chat/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.80
  key: AE-140.80
  layer: common
  name: Marketplaces
  providers:
  - Groupon
  url: /capabilities/marketplaces/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.30
  key: AE-140.10.30
  layer: common
  name: Mobile Commerce App Builders
  providers:
  - Studio Stack
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - WaiverKing
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: common
  name: Product Telemetry & Experimentation Management
  providers:
  - Optimizely
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook
  - Firebase
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: sms-messaging-apps
  layer: common
  name: SMS & Messaging Apps
  providers:
  - Weave
  url: /capabilities/sms-messaging-apps/
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
category:
  id: gym-studio-management
  name: Gym & Fitness Studio Management
  url: /applications/gym-studio-management/
counts:
  declared: 14
  observed: 10
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
- route: integrations page
  url: https://integrations.mindbodyonline.com/
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
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id007
      status: none
    slug: branch-io
    status: profiled
    tags: &id008
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
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
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id023
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id024
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
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
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id025
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id026
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id027
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id028
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: common
  name: Optimizely
  provider: optimizely
  says: ships the Optimizely SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: exemplar
    in_catalog: true
    kin_score: 66.5
    mcp: &id039
      source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
      status: documented
    slug: tealium
    status: profiled
    tags: &id040
    - AudienceStream
    - CDP
    - Customer Data Platform
    - Tag Management
    url: /providers/tealium/
  layer: common
  name: Tealium
  provider: tealium
  says: ships the Tealium SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mindbodyonline.connect/latest/
  tier: observed
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
    agent_readiness: 51.0
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id003
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id004
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: common
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id005
      status: unknown
    slug: bench
    status: profiled
    tags: &id006
    - Accounting
    - Bookkeeping
    - Small Business
    - Software-as-a-Service
    url: /providers/bench/
  layer: common
  name: Bench
  provider: bench
  says: lists Bench as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.50
    key: AE-130.10.50
    name: Fitness Class Aggregators & Corporate Wellness Networks
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id009
      status: none
    slug: classpass
    status: profiled
    tags: &id010
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://integrations.mindbodyonline.com/
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
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id011
      status: none
    slug: constant-contact
    status: profiled
    tags: &id012
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: AE-140.80
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 9.4
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id017
      status: none
    slug: groupon
    status: profiled
    tags: &id018
    - E-Commerce
    - Fortune 1000
    - Local Commerce
    - Marketplace
    url: /providers/groupon/
  layer: common
  name: Groupon
  provider: groupon
  says: lists Groupon as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: AE-150.40
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: healthdesk
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: common
  name: Healthdesk
  provider: healthdesk
  says: lists Healthdesk as an integration
  source: https://integrations.mindbodyonline.com/
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
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id021
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id022
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: common
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: quickernotes
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: QuickerNotes
  provider: quickernotes
  says: lists QuickerNotes as an integration
  source: https://integrations.mindbodyonline.com/
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
    mcp: &id031
      status: unchecked
    slug: reach-ai
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: common
  name: REACH ai
  provider: reach-ai
  says: lists REACH ai as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4050.10
    key: loyalty-programme-design
    name: Loyalty Programme Design
    url: /capabilities/loyalty-programme-design/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id033
      status: unchecked
    slug: referrizer
    status: profiled
    tags: &id034
    - Lead Management
    - Marketing Automation
    - Referral Marketing
    - Reputation Management
    url: /providers/referrizer/
  layer: domain
  name: Referrizer
  provider: referrizer
  says: lists Referrizer as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id035
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id036
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify (ShopifyConnect)
  provider: shopify
  says: lists Shopify (ShopifyConnect) as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.30
    key: AE-140.10.30
    name: Mobile Commerce App Builders
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: studio-stack
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: common
  name: Studio Stack
  provider: studio-stack
  says: lists Studio Stack as an integration
  source: https://integrations.mindbodyonline.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.1
    mcp: &id041
      status: unchecked
    slug: waiverking
    status: profiled
    tags: &id042
    - Digital Forms
    - Fitness
    - Software-as-a-Service
    - Wellness
    url: /providers/waiverking/
  layer: common
  name: WaiverKing
  provider: waiverking
  says: lists WaiverKing as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: strong
    in_catalog: true
    kin_score: 58.1
    mcp: &id043
      status: none
    slug: weave
    status: profiled
    tags: &id044
    - Communications
    - Company
    - Messaging
    - Payments
    url: /providers/weave/
  layer: common
  name: Weave
  provider: weave
  says: lists Weave as an integration
  source: https://integrations.mindbodyonline.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/gym-studio-management/mindbody/
providers:
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id003
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id004
  url: /providers/activecampaign/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id005
  name: Bench
  slug: bench
  status: profiled
  tags: *id006
  url: /providers/bench/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id007
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id008
  url: /providers/branch-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id009
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id010
  url: /providers/classpass/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id011
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id012
  url: /providers/constant-contact/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id013
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id015
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id016
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 9.4
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id017
  name: Groupon
  slug: groupon
  status: profiled
  tags: *id018
  url: /providers/groupon/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Healthdesk
  slug: healthdesk
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id021
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id022
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id023
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id024
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id025
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id026
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id027
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id028
  url: /providers/optimizely/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: QuickerNotes
  slug: quickernotes
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: REACH ai
  slug: reach-ai
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id033
  name: Referrizer
  slug: referrizer
  status: profiled
  tags: *id034
  url: /providers/referrizer/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id035
  name: Shopify (ShopifyConnect)
  slug: shopify
  status: profiled
  tags: *id036
  url: /providers/shopify/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: Studio Stack
  slug: studio-stack
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-ready
  agent_readiness: 34.9
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id039
  name: Tealium
  slug: tealium
  status: profiled
  tags: *id040
  url: /providers/tealium/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id041
  name: WaiverKing
  slug: waiverking
  status: profiled
  tags: *id042
  url: /providers/waiverking/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: strong
  in_catalog: true
  kin_score: 58.1
  mcp: *id043
  name: Weave
  slug: weave
  status: profiled
  tags: *id044
  url: /providers/weave/
siblings:
- name: GYM One
  rows: 4
  url: /applications/gym-studio-management/gym-one/
- name: TeamUp
  rows: 2
  url: /applications/gym-studio-management/teamup/
- name: wger (gym module)
  rows: 5
  url: /applications/gym-studio-management/wger-gym-module/
- name: Wodify
  rows: 19
  url: /applications/gym-studio-management/wodify/
- name: Zen Planner
  rows: 21
  url: /applications/gym-studio-management/zen-planner/
sitemap: true
title: 'Mindbody: Gym & Fitness Studio Management reference app'
---
