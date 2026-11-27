---
app: Mixpanel
app_slug: mixpanel
app_url: https://mixpanel.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Databox
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1300.10
  key: customer-onboarding-management
  layer: domain
  name: Customer Onboarding Management
  providers:
  - Chameleon
  url: /capabilities/customer-onboarding-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook / Meta Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: domain
  name: Feature Flag Management
  providers:
  - Flagsmith
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250.70
  key: subscription-revenue-analytics
  layer: domain
  name: Subscription Revenue Analytics
  providers:
  - Apphud
  url: /capabilities/subscription-revenue-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.20.10
  key: BC-4280.20.10
  layer: domain
  name: Telemetry Schema Governance
  providers:
  - Avo (avo.app tracking plans)
  url: /capabilities/telemetry-quality-governance/
  via_parent: Telemetry Quality & Governance
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - Braze
  - ChurnZero
  - Insider
  - MoEngage
  - Pushwoosh
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make (formerly Integromat)
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://docs.mixpanel.com/docs/mcp
- route: integrations page
  url: https://mixpanel.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: developing
    in_catalog: true
    kin_score: 45.3
    mcp: &id001
      status: none
    slug: apphud
    status: profiled
    tags: &id002
    - Analytics
    - Mobile
    - SDK
    - Subscription
    url: /providers/apphud/
  layer: domain
  name: Apphud
  provider: apphud
  says: lists Apphud as an integration
  source: https://mixpanel.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.20.10
    key: BC-4280.20.10
    name: Telemetry Schema Governance
    url: /capabilities/telemetry-quality-governance/
    via_parent: Telemetry Quality & Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id003
      source: https://github.com/avohq/avo-mcp
      status: verified
    slug: avo-app
    status: profiled
    tags: &id004
    - Analytics
    - Artificial Intelligence
    - Company
    - Data Governance
    url: /providers/avo-app/
  layer: domain
  name: Avo (avo.app tracking plans)
  provider: avo-app
  says: lists Avo (avo.app tracking plans) as an integration
  source: https://mixpanel.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id005
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id006
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: common
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://mixpanel.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1300.10
    key: customer-onboarding-management
    name: Customer Onboarding Management
    url: /capabilities/customer-onboarding-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id007
      status: none
    slug: chameleon
    status: profiled
    tags: &id008
    - In-App Guidance
    - Onboarding
    - Product
    - Surveys
    url: /providers/chameleon/
  layer: domain
  name: Chameleon
  provider: chameleon
  says: lists Chameleon as an integration
  source: https://mixpanel.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id009
      status: none
    slug: churnzero
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Company
    - Customer Success
    - Software-as-a-Service
    url: /providers/churnzero/
  layer: common
  name: ChurnZero
  provider: churnzero
  says: lists ChurnZero as an integration
  source: https://mixpanel.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id011
      source: https://github.com/databox/databox-mcp
      status: verified
    slug: databox
    status: profiled
    tags: &id012
    - Analytics
    - Artificial Intelligence
    - Company
    - Data Integration
    url: /providers/databox/
  layer: domain
  name: Databox
  provider: databox
  says: lists Databox as an integration
  source: https://mixpanel.com/integrations
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
  layer: domain
  name: Facebook / Meta Ads
  provider: facebook
  says: lists Facebook / Meta Ads as an integration
  source: https://mixpanel.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 79.4
    mcp: &id015
      source: https://github.com/Flagsmith/flagsmith-mcp
      status: verified
    slug: flagsmith
    status: profiled
    tags: &id016
    - A/B Testing
    - Feature Flags
    - Release Management
    - Remote Config
    url: /providers/flagsmith/
  layer: domain
  name: Flagsmith
  provider: flagsmith
  says: lists Flagsmith as an integration
  source: https://mixpanel.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 54.3
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id017
      status: none
    slug: insider
    status: profiled
    tags: &id018
    - Company
    - Customer Data Platform
    - Customer Engagement
    - Personalization
    url: /providers/insider/
  layer: common
  name: Insider
  provider: insider
  says: lists Insider as an integration
  source: https://mixpanel.com/integrations
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
    mcp: &id019
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id020
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make (formerly Integromat)
  provider: make
  says: lists Make (formerly Integromat) as an integration
  source: https://mixpanel.com/integrations
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
    agent_readiness: 65.1
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id021
      status: none
    slug: moengage
    status: profiled
    tags: &id022
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
  layer: common
  name: MoEngage
  provider: moengage
  says: lists MoEngage as an integration
  source: https://mixpanel.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 28.5
    band: emerging
    in_catalog: true
    kin_score: 22.0
    mcp: &id023
      status: none
    slug: pushwoosh
    status: profiled
    tags: &id024
    - Email
    - Notification
    - Push
    - SMS
    url: /providers/pushwoosh/
  layer: common
  name: Pushwoosh
  provider: pushwoosh
  says: lists Pushwoosh as an integration
  source: https://mixpanel.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/mixpanel/
providers:
- agent_band: agent-aware
  agent_readiness: 19.3
  band: developing
  in_catalog: true
  kin_score: 45.3
  mcp: *id001
  name: Apphud
  slug: apphud
  status: profiled
  tags: *id002
  url: /providers/apphud/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id003
  name: Avo (avo.app tracking plans)
  slug: avo-app
  status: profiled
  tags: *id004
  url: /providers/avo-app/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id005
  name: Braze
  slug: braze
  status: profiled
  tags: *id006
  url: /providers/braze/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id007
  name: Chameleon
  slug: chameleon
  status: profiled
  tags: *id008
  url: /providers/chameleon/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id009
  name: ChurnZero
  slug: churnzero
  status: profiled
  tags: *id010
  url: /providers/churnzero/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id011
  name: Databox
  slug: databox
  status: profiled
  tags: *id012
  url: /providers/databox/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id013
  name: Facebook / Meta Ads
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 79.4
  mcp: *id015
  name: Flagsmith
  slug: flagsmith
  status: profiled
  tags: *id016
  url: /providers/flagsmith/
- agent_band: agent-ready
  agent_readiness: 54.3
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id017
  name: Insider
  slug: insider
  status: profiled
  tags: *id018
  url: /providers/insider/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id019
  name: Make (formerly Integromat)
  slug: make
  status: profiled
  tags: *id020
  url: /providers/make/
- agent_band: agent-native
  agent_readiness: 65.1
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id021
  name: MoEngage
  slug: moengage
  status: profiled
  tags: *id022
  url: /providers/moengage/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: emerging
  in_catalog: true
  kin_score: 22.0
  mcp: *id023
  name: Pushwoosh
  slug: pushwoosh
  status: profiled
  tags: *id024
  url: /providers/pushwoosh/
siblings:
- name: Amplitude
  rows: 50
  url: /applications/web-analytics/amplitude/
- name: Google Analytics
  rows: 4
  url: /applications/web-analytics/google-analytics/
- name: Matomo
  rows: 18
  url: /applications/web-analytics/matomo/
- name: Plausible
  rows: 16
  url: /applications/web-analytics/plausible/
- name: PostHog
  rows: 42
  url: /applications/web-analytics/posthog/
- name: Umami
  rows: 4
  url: /applications/web-analytics/umami/
sitemap: true
title: 'Mixpanel: Web & Product Analytics reference app'
---
