---
app: Go Vocal (CitizenLab)
app_slug: go-vocal-citizenlab
app_url: https://github.com/CitizenLabDotCo/citizenlab
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-3740.30
  key: content-delivery-network-operations
  layer: common
  name: Content Delivery Network Operations
  providers:
  - Amazon CloudFront
  url: /capabilities/content-delivery-network-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id003
      status: none
    slug: cloudfront
    status: profiled
    tags: &id004
    - Amazon Web Services
    - CDN
    - Caching
    - Content Delivery
    url: /providers/cloudfront/
  layer: common
  name: Amazon CloudFront
  provider: cloudfront
  says: ships the Amazon CloudFront SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id009
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id010
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
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
  layer: common
  name: Intercom
  provider: intercom
  says: ships the Intercom SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id013
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id014
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id015
      status: none
    slug: segment
    status: profiled
    tags: &id016
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id017
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id018
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id019
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id020
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/go-vocal-citizenlab/
providers:
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id001
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id002
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id003
  name: Amazon CloudFront
  slug: cloudfront
  status: profiled
  tags: *id004
  url: /providers/cloudfront/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id009
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
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
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id013
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id014
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id015
  name: Segment
  slug: segment
  status: profiled
  tags: *id016
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id017
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id018
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id019
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id020
  url: /providers/twilio/
siblings:
- name: Accela Civic Platform
  rows: 4
  url: /applications/civic-government-services/accela-civic-platform/
- name: Alaveteli
  rows: 4
  url: /applications/civic-government-services/alaveteli/
- name: CONSUL Democracy
  rows: 5
  url: /applications/civic-government-services/consul-democracy/
- name: Decidim
  rows: 7
  url: /applications/civic-government-services/decidim/
- name: FixMyStreet
  rows: 8
  url: /applications/civic-government-services/fixmystreet/
- name: Granicus (govDelivery)
  rows: 1
  url: /applications/civic-government-services/granicus-govdelivery/
- name: SeeClickFix (CivicPlus)
  rows: 21
  url: /applications/civic-government-services/seeclickfix-civicplus/
sitemap: true
title: 'Go Vocal (CitizenLab): Civic & Government Services reference app'
---
