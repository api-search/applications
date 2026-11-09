---
app: Thinkific
app_slug: thinkific
app_url: https://www.thinkific.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4790
  key: educational-content-learning-resource-management
  layer: domain
  name: Educational Content & Learning Resource Management
  providers:
  - iorad
  - ThingLink
  url: /capabilities/educational-content-learning-resource-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - JivoChat
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Meta Pixel
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Kit
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Sync
  url: /capabilities/general-ledger-management/
  via_parent: null
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics (GA4)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - Smartarget
  - WiserNotify
  url: /capabilities/reviews-social-proof/
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
  id: online-courses-lms
  name: Online Courses & Learning Management
  url: /applications/online-courses-lms/
counts:
  declared: 13
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.thinkific.com/app-store/
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id001
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id002
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics (GA4)
  provider: google-analytics
  says: lists Google Analytics (GA4) as an integration
  source: https://www.thinkific.com/app-store/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id003
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id004
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.thinkific.com/app-store/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4790
    key: educational-content-learning-resource-management
    name: Educational Content & Learning Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 19.8
    mcp: &id005
      status: none
    slug: iorad
    status: profiled
    tags: &id006
    - Company
    - Software Adoption
    - Training
    - Tutorial
    url: /providers/iorad/
  layer: domain
  name: iorad
  provider: iorad
  says: lists iorad as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.3
    mcp: &id007
      status: none
    slug: jivochat
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Company
    - Live Chat
    - Messaging
    url: /providers/jivochat/
  layer: common
  name: JivoChat
  provider: jivochat
  says: lists JivoChat as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 79.6
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
  name: Kit
  provider: convertkit
  says: lists Kit as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id011
      status: none
    slug: facebook
    status: profiled
    tags: &id012
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Meta Pixel
  provider: facebook
  says: lists Meta Pixel as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id013
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id014
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Sync
  provider: quickbooks
  says: lists QuickBooks Sync as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id015
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id016
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.thinkific.com/app-store/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.9
    mcp: &id017
      source: https://api-v2.smartarget.online/api/mcp/message
      status: verified
    slug: smartarget
    status: profiled
    tags: &id018
    - Banking APIs
    - Company
    - Fintech
    - Payments
    url: /providers/smartarget/
  layer: common
  name: Smartarget
  provider: smartarget
  says: lists Smartarget as an integration
  source: https://www.thinkific.com/app-store/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4790
    key: educational-content-learning-resource-management
    name: Educational Content & Learning Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id019
      status: none
    slug: thinglink
    status: profiled
    tags: &id020
    - Company
    - EdTech
    - Education
    - Interactive Media
    url: /providers/thinglink/
  layer: domain
  name: ThingLink
  provider: thinglink
  says: lists ThingLink as an integration
  source: https://www.thinkific.com/app-store/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id021
      status: none
    slug: wisernotify
    status: profiled
    tags: &id022
    - Company
    - Notification
    - Real-Time
    - Software-as-a-Service
    url: /providers/wisernotify/
  layer: common
  name: WiserNotify
  provider: wisernotify
  says: lists WiserNotify as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id023
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id024
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.thinkific.com/app-store/
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
    agent_band: agent-ready
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id025
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id026
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.thinkific.com/app-store/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/online-courses-lms/thinkific/
providers:
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id001
  name: Google Analytics (GA4)
  slug: google-analytics
  status: profiled
  tags: *id002
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id003
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id004
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 19.8
  mcp: *id005
  name: iorad
  slug: iorad
  status: profiled
  tags: *id006
  url: /providers/iorad/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id007
  name: JivoChat
  slug: jivochat
  status: profiled
  tags: *id008
  url: /providers/jivochat/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id009
  name: Kit
  slug: convertkit
  status: profiled
  tags: *id010
  url: /providers/convertkit/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id011
  name: Meta Pixel
  slug: facebook
  status: profiled
  tags: *id012
  url: /providers/facebook/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id013
  name: QuickBooks Sync
  slug: quickbooks
  status: profiled
  tags: *id014
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id015
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id016
  url: /providers/shopify/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id017
  name: Smartarget
  slug: smartarget
  status: profiled
  tags: *id018
  url: /providers/smartarget/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id019
  name: ThingLink
  slug: thinglink
  status: profiled
  tags: *id020
  url: /providers/thinglink/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id021
  name: WiserNotify
  slug: wisernotify
  status: profiled
  tags: *id022
  url: /providers/wisernotify/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id023
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id024
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id025
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id026
  url: /providers/zoom/
siblings:
- name: Canvas LMS
  rows: 25
  url: /applications/online-courses-lms/canvas-lms/
- name: Chamilo
  rows: 13
  url: /applications/online-courses-lms/chamilo/
- name: Coursera
  rows: 4
  url: /applications/online-courses-lms/coursera/
- name: LearnWorlds
  rows: 55
  url: /applications/online-courses-lms/learnworlds/
- name: Moodle
  rows: 27
  url: /applications/online-courses-lms/moodle/
- name: Open edX
  rows: 8
  url: /applications/online-courses-lms/open-edx/
- name: Udemy
  rows: 6
  url: /applications/online-courses-lms/udemy/
sitemap: true
title: 'Thinkific: Online Courses & Learning Management reference app'
---
