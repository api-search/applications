---
app: Retently
app_slug: retently
app_url: https://www.retently.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Klaviyo
  url: /capabilities/customer-lifecycle-engagement/
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
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Freshdesk
  - Gladly
  - Gorgias
  - Intercom
  - Kustomer
  - Richpanel
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Okendo
  - Yotpo
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: customer-feedback-nps
  name: Customer Feedback & NPS
  url: /applications/customer-feedback-nps/
counts:
  declared: 17
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.retently.com/integrations/
integrations:
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
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id001
      status: none
    slug: freshdesk
    status: profiled
    tags: &id002
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://www.retently.com/integrations/
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
    agent_readiness: 34.3
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id003
      status: none
    slug: gladly
    status: profiled
    tags: &id004
    - AI Customer Service
    - Contact Center
    - Customer Experience
    - Customer Service
    url: /providers/gladly/
  layer: domain
  name: Gladly
  provider: gladly
  says: lists Gladly as an integration
  source: https://www.retently.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id005
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id006
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: domain
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://www.retently.com/integrations/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id007
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id008
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.retently.com/integrations/
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
    mcp: &id009
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.retently.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id011
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id012
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: domain
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://www.retently.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id013
      status: none
    slug: kustomer
    status: profiled
    tags: &id014
    - CRM
    - Customer Service
    - Help Desk
    - Messaging
    url: /providers/kustomer/
  layer: domain
  name: Kustomer
  provider: kustomer
  says: lists Kustomer as an integration
  source: https://www.retently.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id015
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id016
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.retently.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 20.2
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id017
      status: none
    slug: okendo
    status: profiled
    tags: &id018
    - Business Applications
    - Company
    - Ratings
    - Reviews
    url: /providers/okendo/
  layer: domain
  name: Okendo
  provider: okendo
  says: lists Okendo as an integration
  source: https://www.retently.com/integrations/
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
    agent_readiness: 28.7
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id019
      status: none
    slug: pipedrive
    status: profiled
    tags: &id020
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://www.retently.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 25.0
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id021
      status: unchecked
    slug: richpanel
    status: profiled
    tags: &id022
    - AI Support
    - Automation
    - E-Commerce
    - Help Desk
    url: /providers/richpanel/
  layer: domain
  name: Richpanel
  provider: richpanel
  says: lists Richpanel as an integration
  source: https://www.retently.com/integrations/
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id023
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id024
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.retently.com/integrations/
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id025
      status: none
    slug: segment
    status: profiled
    tags: &id026
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://www.retently.com/integrations/
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
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.retently.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
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
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.retently.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 33.5
    mcp: &id031
      source: https://core-api.yotpo.com/docs/connect-to-yotpo-mcp
      status: verified
    slug: yotpo
    status: profiled
    tags: &id032
    - E-Commerce
    - Loyalty
    - Retention Marketing
    - Reviews
    url: /providers/yotpo/
  layer: domain
  name: Yotpo
  provider: yotpo
  says: lists Yotpo as an integration
  source: https://www.retently.com/integrations/
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
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id033
      status: none
    slug: zendesk
    status: profiled
    tags: &id034
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.retently.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/customer-feedback-nps/retently/
providers:
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id001
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id002
  url: /providers/freshdesk/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id003
  name: Gladly
  slug: gladly
  status: profiled
  tags: *id004
  url: /providers/gladly/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id005
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id006
  url: /providers/gorgias/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id007
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id008
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id009
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id010
  url: /providers/intercom/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id011
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id012
  url: /providers/klaviyo/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id013
  name: Kustomer
  slug: kustomer
  status: profiled
  tags: *id014
  url: /providers/kustomer/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id015
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id016
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id017
  name: Okendo
  slug: okendo
  status: profiled
  tags: *id018
  url: /providers/okendo/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id019
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id020
  url: /providers/pipedrive/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id021
  name: Richpanel
  slug: richpanel
  status: profiled
  tags: *id022
  url: /providers/richpanel/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id023
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id024
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id025
  name: Segment
  slug: segment
  status: profiled
  tags: *id026
  url: /providers/segment/
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
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 33.5
  mcp: *id031
  name: Yotpo
  slug: yotpo
  status: profiled
  tags: *id032
  url: /providers/yotpo/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id033
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id034
  url: /providers/zendesk/
siblings:
- name: Canny
  rows: 18
  url: /applications/customer-feedback-nps/canny/
- name: ClearFlask
  rows: 15
  url: /applications/customer-feedback-nps/clearflask/
- name: Fider
  rows: 8
  url: /applications/customer-feedback-nps/fider/
- name: Formbricks
  rows: 22
  url: /applications/customer-feedback-nps/formbricks/
- name: SurveyMonkey
  rows: 6
  url: /applications/customer-feedback-nps/surveymonkey/
- name: Survicate
  rows: 25
  url: /applications/customer-feedback-nps/survicate/
sitemap: true
title: 'Retently: Customer Feedback & NPS reference app'
---
