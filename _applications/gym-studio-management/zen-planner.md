---
app: Zen Planner
app_slug: zen-planner
app_url: https://zenplanner.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10.50
  key: AE-130.10.50
  layer: domain
  name: Fitness Class Aggregators & Corporate Wellness Networks
  providers:
  - ClassPass
  - Optum
  - Wellhub
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: Turbo EA
  id: BC-4050.10
  key: loyalty-programme-design
  layer: domain
  name: Loyalty Programme Design
  providers:
  - Perkville
  url: /capabilities/loyalty-programme-design/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.90
  key: AE-200.90
  layer: domain
  name: Physical Access Control & Mobile Keys
  providers:
  - HybridAF
  url: /capabilities/physical-access-control-mobile-keys/
  via_parent: null
- attribution: Turbo EA
  id: BC-2880.20
  key: preventive-care-wellness
  layer: domain
  name: Preventive Care & Wellness
  providers:
  - Welld Health
  url: /capabilities/preventive-care-wellness/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.10.10
  key: AE-130.10.10
  layer: domain
  name: Workout Logging
  providers:
  - SugarWOD
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook
  url: /capabilities/digital-marketing-management/
  via_parent: null
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
  - Microsoft 365
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.120
  key: AE-140.120
  layer: common
  name: Print-on-Demand Fulfilment
  providers:
  - Printful
  url: /capabilities/print-on-demand-fulfilment/
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
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Instagram
  - LinkedIn
  - TikTok
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
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
  id: gym-studio-management
  name: Gym & Fitness Studio Management
  url: /applications/gym-studio-management/
counts:
  declared: 21
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://zenplanner.com/integrations/
integrations:
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
    mcp: &id001
      status: none
    slug: classpass
    status: profiled
    tags: &id002
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id003
      status: none
    slug: facebook
    status: profiled
    tags: &id004
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id005
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id006
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id008
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
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
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id011
      status: unchecked
    slug: hybridaf
    status: profiled
    tags: &id012
    - Access Control
    - Company
    - Fitness
    - Software-as-a-Service
    url: /providers/hybridaf/
  layer: domain
  name: HybridAF
  provider: hybridaf
  says: lists HybridAF as an integration
  source: https://zenplanner.com/integrations/
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
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id013
      status: none
    slug: instagram
    status: profiled
    tags: &id014
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: common
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://zenplanner.com/integrations/
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id015
      status: none
    slug: linkedin
    status: profiled
    tags: &id016
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: common
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id017
      status: none
    slug: mailchimp
    status: profiled
    tags: &id018
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://zenplanner.com/integrations/
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
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id019
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id020
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: common
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://zenplanner.com/integrations/
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
    agent_readiness: 39.8
    band: exemplar
    in_catalog: true
    kin_score: 69.8
    mcp: &id021
      status: none
    slug: optum
    status: profiled
    tags: &id022
    - Claims
    - Company
    - Health Insurance
    - Healthcare
    url: /providers/optum/
  layer: domain
  name: Optum
  provider: optum
  says: lists Optum as an integration
  source: https://zenplanner.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 33.8
    band: developing
    in_catalog: true
    kin_score: 44.5
    mcp: &id023
      status: unchecked
    slug: perkville
    status: profiled
    tags: &id024
    - Customer Engagement
    - Loyalty
    - Referral Program
    - Software-as-a-Service
    url: /providers/perkville/
  layer: domain
  name: Perkville
  provider: perkville
  says: lists Perkville as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.120
    key: AE-140.120
    name: Print-on-Demand Fulfilment
    url: /capabilities/print-on-demand-fulfilment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id025
      status: none
    slug: printful
    status: profiled
    tags: &id026
    - Dropshipping
    - E-Commerce
    - Fulfillment
    - Print on Demand
    url: /providers/printful/
  layer: common
  name: Printful
  provider: printful
  says: lists Printful as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id027
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id028
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id029
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id030
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.10
    key: AE-130.10.10
    name: Workout Logging
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.2
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id031
      status: unchecked
    slug: sugarwod
    status: profiled
    tags: &id032
    - Fitness
    - Gym Management
    - Software-as-a-Service
    - Workouts
    url: /providers/sugarwod/
  layer: domain
  name: SugarWOD
  provider: sugarwod
  says: lists SugarWOD as an integration
  source: https://zenplanner.com/integrations/
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
    agent_readiness: 19.2
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id033
      status: none
    slug: tiktok
    status: profiled
    tags: &id034
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: common
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2880.20
    key: preventive-care-wellness
    name: Preventive Care & Wellness
    url: /capabilities/preventive-care-wellness/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id035
      status: unchecked
    slug: welld-health
    status: profiled
    tags: &id036
    - Company
    - Health
    - Payments
    - Platform
    url: /providers/welld-health/
  layer: domain
  name: Welld Health
  provider: welld-health
  says: lists Welld Health as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id037
      status: unknown
    slug: wellhub
    status: profiled
    tags: &id038
    - Company
    - Corporate Benefits
    - Health
    - Wellbeing
    url: /providers/wellhub/
  layer: domain
  name: Wellhub
  provider: wellhub
  says: lists Wellhub as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id039
      status: none
    slug: whatsapp
    status: profiled
    tags: &id040
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://zenplanner.com/integrations/
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
    mcp: &id041
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id042
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://zenplanner.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/gym-studio-management/zen-planner/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id001
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id002
  url: /providers/classpass/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id003
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id004
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id005
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id006
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id007
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id008
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id009
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id010
  url: /providers/google-drive/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id011
  name: HybridAF
  slug: hybridaf
  status: profiled
  tags: *id012
  url: /providers/hybridaf/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id013
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id014
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id015
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id016
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id017
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id018
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id019
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id020
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 39.8
  band: exemplar
  in_catalog: true
  kin_score: 69.8
  mcp: *id021
  name: Optum
  slug: optum
  status: profiled
  tags: *id022
  url: /providers/optum/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: developing
  in_catalog: true
  kin_score: 44.5
  mcp: *id023
  name: Perkville
  slug: perkville
  status: profiled
  tags: *id024
  url: /providers/perkville/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id025
  name: Printful
  slug: printful
  status: profiled
  tags: *id026
  url: /providers/printful/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id027
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id028
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id029
  name: Slack
  slug: slack
  status: profiled
  tags: *id030
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 6.2
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id031
  name: SugarWOD
  slug: sugarwod
  status: profiled
  tags: *id032
  url: /providers/sugarwod/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id033
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id034
  url: /providers/tiktok/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id035
  name: Welld Health
  slug: welld-health
  status: profiled
  tags: *id036
  url: /providers/welld-health/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id037
  name: Wellhub
  slug: wellhub
  status: profiled
  tags: *id038
  url: /providers/wellhub/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id039
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id040
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id041
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id042
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
- name: Wodify
  rows: 19
  url: /applications/gym-studio-management/wodify/
sitemap: true
title: 'Zen Planner: Gym & Fitness Studio Management reference app'
---
