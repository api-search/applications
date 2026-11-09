---
app: Help Scout
app_slug: help-scout
app_url: https://www.helpscout.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.30
  key: contact-centre-operations-management
  layer: domain
  name: Contact Centre Operations Management
  providers:
  - Aircall
  - Talkdesk
  url: /capabilities/contact-centre-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Segment.io
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - SurveyMonkey
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Pipedrive
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: domain
  name: Software Product Engineering Management
  providers:
  - Asana
  - GitHub
  - Jira
  - Linear
  - Trello
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Instagram
  - Messenger by Facebook
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Klaviyo
  - Mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
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
  - Gmail
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Shopify
  - Stripe
  - WooCommerce
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Mixpanel
  url: /capabilities/product-usage-analytics/
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
  id: helpdesk-ticketing
  name: Help Desk & Customer Support
  url: /applications/helpdesk-ticketing/
counts:
  declared: 24
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.helpscout.com/apps/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id001
      status: none
    slug: aircall
    status: profiled
    tags: &id002
    - CRM
    - Cloud Phone
    - Communications
    - Voice
    url: /providers/aircall/
  layer: domain
  name: Aircall
  provider: aircall
  says: lists Aircall as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id003
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id004
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.helpscout.com/apps/
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id007
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id008
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.helpscout.com/apps/
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
    mcp: &id009
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id010
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id011
      status: none
    slug: instagram
    status: profiled
    tags: &id012
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id013
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id014
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://www.helpscout.com/apps/
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
    agent_band: agent-native
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id015
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id016
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: common
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id017
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id018
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id019
      status: none
    slug: mailchimp
    status: profiled
    tags: &id020
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.helpscout.com/apps/
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
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id021
      status: none
    slug: facebook
    status: profiled
    tags: &id022
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Messenger by Facebook
  provider: facebook
  says: lists Messenger by Facebook as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 60.3
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
  says: lists Mixpanel as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 29.3
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id025
      status: none
    slug: pipedrive
    status: profiled
    tags: &id026
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id027
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id028
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id029
      status: none
    slug: segment
    status: profiled
    tags: &id030
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment.io
  provider: segment
  says: lists Segment.io as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id031
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id032
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id033
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id034
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id035
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id036
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id037
      source: https://www.surveymonkey.com/apps/
      status: documented
    slug: surveymonkey
    status: profiled
    tags: &id038
    - Feedback
    - Market Research
    - NPS
    - Surveys
    url: /providers/surveymonkey/
  layer: domain
  name: SurveyMonkey
  provider: surveymonkey
  says: lists SurveyMonkey as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.0
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id039
      status: none
    slug: talkdesk
    status: profiled
    tags: &id040
    - CCaaS
    - Contact Center
    - Voice
    - Webhook
    url: /providers/talkdesk/
  layer: domain
  name: Talkdesk
  provider: talkdesk
  says: lists Talkdesk as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id041
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id042
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id043
      status: none
    slug: whatsapp
    status: profiled
    tags: &id044
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://www.helpscout.com/apps/
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
    agent_readiness: 35.4
    band: developing
    in_catalog: true
    kin_score: 50.4
    mcp: &id045
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id046
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: common
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.helpscout.com/apps/
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
    mcp: &id047
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id048
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.helpscout.com/apps/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/helpdesk-ticketing/help-scout/
providers:
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id001
  name: Aircall
  slug: aircall
  status: profiled
  tags: *id002
  url: /providers/aircall/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id003
  name: Asana
  slug: asana
  status: profiled
  tags: *id004
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id005
  name: GitHub
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id007
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id008
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id009
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id010
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id011
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id012
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id013
  name: Jira
  slug: jira
  status: profiled
  tags: *id014
  url: /providers/jira/
- agent_band: agent-native
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id015
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id016
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id017
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id018
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id019
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id020
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id021
  name: Messenger by Facebook
  slug: facebook
  status: profiled
  tags: *id022
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id023
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id024
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id025
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id026
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id027
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id028
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id029
  name: Segment.io
  slug: segment
  status: profiled
  tags: *id030
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id031
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id032
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id033
  name: Slack
  slug: slack
  status: profiled
  tags: *id034
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id035
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id036
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id037
  name: SurveyMonkey
  slug: surveymonkey
  status: profiled
  tags: *id038
  url: /providers/surveymonkey/
- agent_band: agent-aware
  agent_readiness: 14.0
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id039
  name: Talkdesk
  slug: talkdesk
  status: profiled
  tags: *id040
  url: /providers/talkdesk/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id041
  name: Trello
  slug: trello
  status: profiled
  tags: *id042
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id043
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id044
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id045
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id046
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id047
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id048
  url: /providers/zapier/
siblings:
- name: Chatwoot
  rows: 33
  url: /applications/helpdesk-ticketing/chatwoot/
- name: FreeScout
  rows: 12
  url: /applications/helpdesk-ticketing/freescout/
- name: Freshdesk
  rows: 6
  url: /applications/helpdesk-ticketing/freshdesk/
- name: Intercom
  rows: 1
  url: /applications/helpdesk-ticketing/intercom/
- name: Zammad
  rows: 23
  url: /applications/helpdesk-ticketing/zammad/
- name: Zendesk
  rows: 2
  url: /applications/helpdesk-ticketing/zendesk/
sitemap: true
title: 'Help Scout: Help Desk & Customer Support reference app'
---
