---
app: Short.io
app_slug: short-io
app_url: https://short.io/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - AdRoll
  - Meta Pixel
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: domain
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
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
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 8
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://short.io/integrations/
integrations:
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
    agent_readiness: 29.1
    band: developing
    in_catalog: true
    kin_score: 51.1
    mcp: &id001
      status: none
    slug: adroll
    status: profiled
    tags: &id002
    - Advertising
    - Display Advertising
    - Marketing
    - Retargeting
    url: /providers/adroll/
  layer: domain
  name: AdRoll
  provider: adroll
  says: lists AdRoll as an integration
  source: https://short.io/integrations/
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
    mcp: &id003
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://short.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id005
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id006
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: domain
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://short.io/integrations/
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
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id007
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id008
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://short.io/integrations/
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
  layer: domain
  name: Meta Pixel
  provider: facebook
  says: lists Meta Pixel as an integration
  source: https://short.io/integrations/
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
    mcp: &id011
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id012
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://short.io/integrations/
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
    mcp: &id013
      status: none
    slug: segment
    status: profiled
    tags: &id014
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: lists Twilio Segment as an integration
  source: https://short.io/integrations/
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
    mcp: &id015
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id016
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://short.io/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/short-io/
providers:
- agent_band: agent-ready
  agent_readiness: 29.1
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id001
  name: AdRoll
  slug: adroll
  status: profiled
  tags: *id002
  url: /providers/adroll/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id005
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id006
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id007
  name: Make
  slug: make
  status: profiled
  tags: *id008
  url: /providers/make/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id009
  name: Meta Pixel
  slug: facebook
  status: profiled
  tags: *id010
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id011
  name: Slack
  slug: slack
  status: profiled
  tags: *id012
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id013
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id014
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id015
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id016
  url: /providers/zapier/
siblings:
- name: Bitly
  rows: 55
  url: /applications/url-shortener-links/bitly/
- name: Dub
  rows: 25
  url: /applications/url-shortener-links/dub/
- name: Kutt
  rows: 1
  url: /applications/url-shortener-links/kutt/
- name: Shlink
  rows: 6
  url: /applications/url-shortener-links/shlink/
- name: Sink
  rows: 5
  url: /applications/url-shortener-links/sink/
- name: YOURLS
  rows: 2
  url: /applications/url-shortener-links/yourls/
sitemap: true
title: 'Short.io: Link Management & URL Shorteners reference app'
---
