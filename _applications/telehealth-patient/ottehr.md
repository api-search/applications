---
app: Ottehr
app_slug: ottehr
app_url: https://github.com/masslight/ottehr
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2830
  key: clinical-documentation-management
  layer: domain
  name: Clinical Documentation Management
  providers:
  - Dynamsoft Web TWAIN
  url: /capabilities/clinical-documentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2900.60
  key: healthcare-interoperability-operations
  layer: domain
  name: Healthcare Interoperability Operations
  providers:
  - Oystehr
  url: /capabilities/healthcare-interoperability-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-2870
  key: healthcare-revenue-cycle-management
  layer: domain
  name: Healthcare Revenue Cycle Management
  providers:
  - Candid Health
  url: /capabilities/healthcare-revenue-cycle-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Amazon Chime SDK
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon CloudFront
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Auth0
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40
  key: AE-150.40
  layer: common
  name: In-App Chat
  providers:
  - Twilio
  url: /capabilities/in-app-chat/
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: agent
  name: Artificial Intelligence Management
  providers:
  - Anthropic
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
category:
  id: telehealth-patient
  name: Telehealth & Patient Apps
  url: /applications/telehealth-patient/
counts:
  declared: 0
  observed: 12
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/masslight/ottehr/develop/apps/ehr/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/masslight/ottehr/develop/packages/zambdas/package.json
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.5
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id001
      status: none
    slug: amazon-chime
    status: profiled
    tags: &id002
    - Communications
    - Messaging
    - SDK
    - Video
    url: /providers/amazon-chime/
  layer: domain
  name: Amazon Chime SDK
  provider: amazon-chime
  says: ships the Amazon Chime SDK SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/apps/ehr/package.json
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
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
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
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id009
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id010
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0
  provider: auth0
  says: ships the Auth0 SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id011
      status: none
    slug: candid-health
    status: profiled
    tags: &id012
    - Claims
    - Healthcare
    - Medical Billing
    - Revenue Cycle Management
    url: /providers/candid-health/
  layer: domain
  name: Candid Health
  provider: candid-health
  says: ships the Candid Health SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2830
    key: clinical-documentation-management
    name: Clinical Documentation Management
    url: /capabilities/clinical-documentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id013
      source: https://www.dynamsoft.com/codepool/mcp-server-dynamsoft-sdk-integration.html
      status: documented
    slug: dynamsoft
    status: profiled
    tags: &id014
    - Barcodes
    - Company
    - Document-Capture
    - SDK
    url: /providers/dynamsoft/
  layer: domain
  name: Dynamsoft Web TWAIN
  provider: dynamsoft
  says: ships the Dynamsoft Web TWAIN SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/apps/ehr/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id015
      status: none
    slug: oystehr
    status: profiled
    tags: &id016
    - Company
    - Electronic Health Records
    - Health Tech
    url: /providers/oystehr/
  layer: domain
  name: Oystehr
  provider: oystehr
  says: ships the Oystehr SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
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
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id017
      status: none
    slug: sendgrid
    status: profiled
    tags: &id018
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
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
    mcp: &id019
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id020
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
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
    mcp: &id021
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id022
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/packages/zambdas/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: AE-150.40
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id023
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id024
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/telehealth-patient/ottehr/
providers:
- agent_band: agent-native
  agent_readiness: 42.5
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id001
  name: Amazon Chime SDK
  slug: amazon-chime
  status: profiled
  tags: *id002
  url: /providers/amazon-chime/
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
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id009
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id010
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id011
  name: Candid Health
  slug: candid-health
  status: profiled
  tags: *id012
  url: /providers/candid-health/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id013
  name: Dynamsoft Web TWAIN
  slug: dynamsoft
  status: profiled
  tags: *id014
  url: /providers/dynamsoft/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id015
  name: Oystehr
  slug: oystehr
  status: profiled
  tags: *id016
  url: /providers/oystehr/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id017
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id018
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id019
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id020
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id021
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id022
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id023
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id024
  url: /providers/twilio/
siblings:
- name: Doctolib
  rows: 3
  url: /applications/telehealth-patient/doctolib/
- name: Doctor On Demand (Included Health)
  rows: 6
  url: /applications/telehealth-patient/doctor-on-demand-included-health/
- name: MDLIVE
  rows: 2
  url: /applications/telehealth-patient/mdlive/
- name: Medplum
  rows: 26
  url: /applications/telehealth-patient/medplum/
- name: MyChart (Epic)
  rows: 0
  url: /applications/telehealth-patient/mychart-epic/
- name: OpenEMR
  rows: 13
  url: /applications/telehealth-patient/openemr/
- name: Teladoc
  rows: 8
  url: /applications/telehealth-patient/teladoc/
- name: Zocdoc
  rows: 6
  url: /applications/telehealth-patient/zocdoc/
sitemap: true
title: 'Ottehr: Telehealth & Patient Apps reference app'
---
