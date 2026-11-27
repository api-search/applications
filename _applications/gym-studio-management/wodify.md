---
app: Wodify
app_slug: wodify
app_url: https://www.wodify.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.50
  key: AE-130.10.50
  layer: domain
  name: Fitness Class Aggregators & Corporate Wellness Networks
  providers:
  - ClassPass
  - Wellhub
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-130.20
  key: wearable-health-data-sync
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Myzone
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: common
  name: Content Management
  providers:
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Meta (Pixel, Leads)
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-912
  key: AE-912
  layer: common
  name: Direct Mail APIs
  providers:
  - AMcards
  - Thankster
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.50
  key: AE-140.30.50
  layer: common
  name: HSA/FSA Eligible Payments
  providers:
  - Truemed
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: common
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
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
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - SurveyMonkey
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: voice-telephony
  layer: common
  name: Voice & Telephony
  providers:
  - Callingly
  url: /capabilities/voice-telephony/
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
  id: gym-studio-management
  name: Gym & Fitness Studio Management
  url: /applications/gym-studio-management/
counts:
  declared: 19
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.wodify.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id001
      status: unchecked
    slug: amcards
    status: profiled
    tags: &id002
    - Appreciation-Marketing
    - Cards
    - Company
    - Customer Engagement
    url: /providers/amcards/
  layer: common
  name: AMcards
  provider: amcards
  says: lists AMcards as an integration
  source: https://www.wodify.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: voice-telephony
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: callingly
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: common
  name: Callingly
  provider: callingly
  says: lists Callingly as an integration
  source: https://www.wodify.com/integrations
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
    mcp: &id005
      status: none
    slug: classpass
    status: profiled
    tags: &id006
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://www.wodify.com/integrations
  tier: declared
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
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
  says: lists Google Analytics as an integration
  source: https://www.wodify.com/integrations
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
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.wodify.com/integrations
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
    mcp: &id011
      status: none
    slug: mailchimp
    status: profiled
    tags: &id012
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.wodify.com/integrations
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
  name: Meta (Pixel, Leads)
  provider: facebook
  says: lists Meta (Pixel, Leads) as an integration
  source: https://www.wodify.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: wearable-health-data-sync
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id015
      status: unchecked
    slug: myzone
    status: profiled
    tags: &id016
    - Fitness
    - Gym Management
    - MotivationTechnology
    - Wearables
    url: /providers/myzone/
  layer: domain
  name: Myzone
  provider: myzone
  says: lists Myzone as an integration
  source: https://www.wodify.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id017
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id018
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.wodify.com/integrations
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
    mcp: &id019
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id020
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.wodify.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id021
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id022
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.wodify.com/integrations
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
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.wodify.com/integrations
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
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id025
      source: https://www.surveymonkey.com/apps/
      status: documented
    slug: surveymonkey
    status: profiled
    tags: &id026
    - Feedback
    - Market Research
    - NPS
    - Surveys
    url: /providers/surveymonkey/
  layer: common
  name: SurveyMonkey
  provider: surveymonkey
  says: lists SurveyMonkey as an integration
  source: https://www.wodify.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id027
      status: unchecked
    slug: thankster
    status: profiled
    tags: &id028
    - Automation
    - B2B
    - Direct Mail
    - Handwritten Cards
    url: /providers/thankster/
  layer: common
  name: Thankster
  provider: thankster
  says: lists Thankster as an integration
  source: https://www.wodify.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.50
    key: AE-140.30.50
    name: HSA/FSA Eligible Payments
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 55.0
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id029
      status: unchecked
    slug: truemed
    status: profiled
    tags: &id030
    - Company
    - Fintech
    - HSA
    - Health
    url: /providers/truemed/
  layer: common
  name: Truemed
  provider: truemed
  says: lists Truemed as an integration
  source: https://www.wodify.com/integrations
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
    agent_readiness: 42.6
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id031
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id032
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: common
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://www.wodify.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 34.5
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id033
      status: unknown
    slug: wellhub
    status: profiled
    tags: &id034
    - Company
    - Corporate Benefits
    - Health
    - Wellbeing
    url: /providers/wellhub/
  layer: domain
  name: Wellhub
  provider: wellhub
  says: lists Wellhub as an integration
  source: https://www.wodify.com/integrations
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
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id035
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id036
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: common
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://www.wodify.com/integrations
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
    mcp: &id037
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id038
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.wodify.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/gym-studio-management/wodify/
providers:
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id001
  name: AMcards
  slug: amcards
  status: profiled
  tags: *id002
  url: /providers/amcards/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Callingly
  slug: callingly
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id005
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id006
  url: /providers/classpass/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id007
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id008
  url: /providers/google-analytics/
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
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id011
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id012
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id013
  name: Meta (Pixel, Leads)
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id015
  name: Myzone
  slug: myzone
  status: profiled
  tags: *id016
  url: /providers/myzone/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id017
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id018
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id019
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id020
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id021
  name: Slack
  slug: slack
  status: profiled
  tags: *id022
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id025
  name: SurveyMonkey
  slug: surveymonkey
  status: profiled
  tags: *id026
  url: /providers/surveymonkey/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id027
  name: Thankster
  slug: thankster
  status: profiled
  tags: *id028
  url: /providers/thankster/
- agent_band: agent-native
  agent_readiness: 55.0
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id029
  name: Truemed
  slug: truemed
  status: profiled
  tags: *id030
  url: /providers/truemed/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id031
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id032
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id033
  name: Wellhub
  slug: wellhub
  status: profiled
  tags: *id034
  url: /providers/wellhub/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id035
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id036
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id037
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id038
  url: /providers/zapier/
siblings:
- name: GYM One
  rows: 4
  url: /applications/gym-studio-management/gym-one/
- name: Mindbody
  rows: 24
  url: /applications/gym-studio-management/mindbody/
- name: TeamUp
  rows: 2
  url: /applications/gym-studio-management/teamup/
- name: wger (gym module)
  rows: 5
  url: /applications/gym-studio-management/wger-gym-module/
- name: Zen Planner
  rows: 21
  url: /applications/gym-studio-management/zen-planner/
sitemap: true
title: 'Wodify: Gym & Fitness Studio Management reference app'
---
