---
app: Hightouch
app_slug: hightouch
app_url: https://hightouch.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Intercom
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook / Meta Ads
  - Google Ads
  - LinkedIn Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Braze
  - Iterable
  - Marketo
  url: /capabilities/email/
  via_parent: Email
category:
  id: data-integration-etl
  name: Data Integration & ETL
  url: /applications/data-integration-etl/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: domain
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id003
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id004
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: common
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook / Meta Ads
  provider: facebook
  says: lists Facebook / Meta Ads as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id007
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id008
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://docs.hightouch.com/destinations/overview
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
  source: https://docs.hightouch.com/destinations/overview
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
    mcp: &id011
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id013
      source: https://github.com/Iterable/mcp-server
      status: verified
    slug: iterable
    status: profiled
    tags: &id014
    - Cross-Channel Messaging
    - Customer Engagement
    - Email
    - Marketing Automation
    url: /providers/iterable/
  layer: common
  name: Iterable
  provider: iterable
  says: lists Iterable as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id015
      status: none
    slug: linkedin-ads
    status: profiled
    tags: &id016
    - Advertising
    - Lead Generation
    - LinkedIn
    - Marketing
    url: /providers/linkedin-ads/
  layer: domain
  name: LinkedIn Ads
  provider: linkedin-ads
  says: lists LinkedIn Ads as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id017
      status: none
    slug: marketo
    status: profiled
    tags: &id018
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
  layer: common
  name: Marketo
  provider: marketo
  says: lists Marketo as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id019
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id020
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: domain
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    mcp: &id021
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id022
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://docs.hightouch.com/destinations/overview
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
    mcp: &id023
      status: none
    slug: zendesk
    status: profiled
    tags: &id024
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://docs.hightouch.com/destinations/overview
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/data-integration-etl/hightouch/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id003
  name: Braze
  slug: braze
  status: profiled
  tags: *id004
  url: /providers/braze/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook / Meta Ads
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id007
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id008
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id009
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id010
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id011
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id012
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id013
  name: Iterable
  slug: iterable
  status: profiled
  tags: *id014
  url: /providers/iterable/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id015
  name: LinkedIn Ads
  slug: linkedin-ads
  status: profiled
  tags: *id016
  url: /providers/linkedin-ads/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id017
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id018
  url: /providers/marketo/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id019
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id020
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id021
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id022
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id023
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id024
  url: /providers/zendesk/
siblings:
- name: Airbyte
  rows: 135
  url: /applications/data-integration-etl/airbyte/
- name: Apache NiFi
  rows: 35
  url: /applications/data-integration-etl/apache-nifi/
- name: dlt (dltHub)
  rows: 27
  url: /applications/data-integration-etl/dlt-dlthub/
- name: Estuary Flow
  rows: 87
  url: /applications/data-integration-etl/estuary-flow/
- name: Fivetran
  rows: 99
  url: /applications/data-integration-etl/fivetran/
sitemap: true
title: 'Hightouch: Data Integration & ETL reference app'
---
