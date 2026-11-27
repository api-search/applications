---
app: Sharetribe (hosted)
app_slug: sharetribe-hosted
app_url: https://www.sharetribe.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-440.30
  key: discount-promotion-management
  layer: domain
  name: Discount & Promotion Management
  providers:
  - Voucherify
  url: /capabilities/discount-promotion-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40
  key: in-app-chat
  layer: domain
  name: In-App Chat
  providers:
  - Sendbird
  url: /capabilities/in-app-chat/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  url: /capabilities/customer-service-management/
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
  id: AE-150.80
  key: mailbox-calendar-sync
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - Hotjar
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: AE-150.20
  layer: common
  name: SMS & Messaging Apps
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: null
category:
  id: resale-marketplace
  name: Resale & Second-hand Marketplaces
  url: /applications/resale-marketplace/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
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
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: mailbox-calendar-sync
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
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id004
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    agent_band: agent-aware
    agent_readiness: 27.3
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id005
      status: none
    slug: hotjar
    status: profiled
    tags: &id006
    - Analytics
    - Personalization
    - Surveys
    - Tracking
    url: /providers/hotjar/
  layer: common
  name: Hotjar
  provider: hotjar
  says: lists Hotjar as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id007
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    mcp: &id009
      status: none
    slug: mailchimp
    status: profiled
    tags: &id010
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id011
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id012
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: in-app-chat
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id013
      status: none
    slug: sendbird
    status: profiled
    tags: &id014
    - Customer Service
    - Omnichannel
    - Video
    - Voice
    url: /providers/sendbird/
  layer: domain
  name: Sendbird
  provider: sendbird
  says: lists Sendbird as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    mcp: &id015
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id016
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id017
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id018
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-440.30
    key: discount-promotion-management
    name: Discount & Promotion Management
    url: /capabilities/discount-promotion-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.7
    band: developing
    in_catalog: true
    kin_score: 49.2
    mcp: &id019
      source: https://docs.voucherify.io/guides/voucherify-core-mcp
      status: verified
    slug: voucherify
    status: profiled
    tags: &id020
    - Company
    - Incentives
    - Loyalty
    - Promotions
    url: /providers/voucherify/
  layer: domain
  name: Voucherify
  provider: voucherify
  says: lists Voucherify as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    mcp: &id021
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id022
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: domain
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/resale-marketplace/sharetribe-hosted/
providers:
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id001
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id002
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id003
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id004
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id005
  name: Hotjar
  slug: hotjar
  status: profiled
  tags: *id006
  url: /providers/hotjar/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id007
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id008
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id009
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id010
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id011
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id012
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id013
  name: Sendbird
  slug: sendbird
  status: profiled
  tags: *id014
  url: /providers/sendbird/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id015
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id016
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id017
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id018
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 43.7
  band: developing
  in_catalog: true
  kin_score: 49.2
  mcp: *id019
  name: Voucherify
  slug: voucherify
  status: profiled
  tags: *id020
  url: /providers/voucherify/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id021
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id022
  url: /providers/zapier/
siblings:
- name: Cocorico
  rows: 5
  url: /applications/resale-marketplace/cocorico/
- name: Depop
  rows: 6
  url: /applications/resale-marketplace/depop/
- name: Mercari
  rows: 9
  url: /applications/resale-marketplace/mercari/
- name: Poshmark
  rows: 11
  url: /applications/resale-marketplace/poshmark/
- name: Sharetribe Go
  rows: 11
  url: /applications/resale-marketplace/sharetribe-go/
- name: Sharetribe Web Template
  rows: 6
  url: /applications/resale-marketplace/sharetribe-web-template/
- name: Vinted
  rows: 25
  url: /applications/resale-marketplace/vinted/
sitemap: true
title: 'Sharetribe (hosted): Resale & Second-hand Marketplaces reference app'
---
