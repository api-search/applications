---
app: Medplum
app_slug: medplum
app_url: https://github.com/medplum/medplum
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2800.30
  key: eligibility-benefits-verification
  layer: domain
  name: Eligibility & Benefits Verification
  providers:
  - Stedi
  url: /capabilities/eligibility-benefits-verification/
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
- attribution: Turbo EA
  id: BC-2860.10
  key: laboratory-services-management
  layer: domain
  name: Laboratory Services Management
  providers:
  - Health Gorilla
  url: /capabilities/laboratory-services-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.20.20
  key: AE-130.20.20
  layer: domain
  name: Personal Health Records
  providers:
  - Epic
  url: /capabilities/wearable-health-data-sync/
  via_parent: Wearable & Health Data Sync
- attribution: Turbo EA
  id: BC-2850
  key: pharmacy-medication-management
  layer: domain
  name: Pharmacy & Medication Management
  providers:
  - DoseSpot
  - ScriptSure
  url: /capabilities/pharmacy-medication-management/
  via_parent: null
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
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
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: pharmacy-prescriptions
  name: Pharmacy & Prescriptions
  url: /applications/pharmacy-prescriptions/
counts:
  declared: 6
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
- route: integrations page
  url: https://www.medplum.com/docs/integration
- route: source code
  url: https://github.com/medplum/medplum/tree/main/packages
integrations:
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
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id003
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id007
      status: none
    slug: dosespot
    status: profiled
    tags: &id008
    - Electronic Health Records
    - Healthcare
    - e-Prescribing
    - eRx
    url: /providers/dosespot/
  layer: domain
  name: DoseSpot
  provider: dosespot
  says: ships the DoseSpot SDK or integration code
  source: https://github.com/medplum/medplum/tree/main/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.5
    band: exemplar
    in_catalog: true
    kin_score: 75.7
    mcp: &id011
      status: none
    slug: health-gorilla
    status: profiled
    tags: &id012
    - Clinical Data
    - FHIR
    - Health
    - Interoperability
    url: /providers/health-gorilla/
  layer: domain
  name: Health Gorilla
  provider: health-gorilla
  says: ships the Health Gorilla SDK or integration code
  source: https://github.com/medplum/medplum/tree/main/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id013
      status: unknown
    slug: scriptsure
    status: profiled
    tags: &id014
    - Company
    url: /providers/scriptsure/
  layer: domain
  name: ScriptSure
  provider: scriptsure
  says: ships the ScriptSure SDK or integration code
  source: https://github.com/medplum/medplum/tree/main/packages
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
    mcp: &id005
      status: none
    slug: candid-health
    status: profiled
    tags: &id006
    - Claims
    - Healthcare
    - Medical Billing
    - Revenue Cycle Management
    url: /providers/candid-health/
  layer: domain
  name: Candid Health
  provider: candid-health
  says: lists Candid Health as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.20
    key: AE-130.20.20
    name: Personal Health Records
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id009
      status: none
    slug: epic-systems
    status: profiled
    tags: &id010
    - Electronic Health Records
    - FHIR
    - Healthcare
    - United States
    url: /providers/epic-systems/
  layer: domain
  name: Epic
  provider: epic-systems
  says: lists Epic as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
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
    mcp: &id015
      status: none
    slug: sendgrid
    status: profiled
    tags: &id016
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: lists SendGrid as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.30
    key: eligibility-benefits-verification
    name: Eligibility & Benefits Verification
    url: /capabilities/eligibility-benefits-verification/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id017
      source: https://www.stedi.com/docs/healthcare/mcp-server
      status: verified
    slug: stedi
    status: profiled
    tags: &id018
    - Clearinghouse
    - EDI
    - Electronic Data Interchange
    - Healthcare
    url: /providers/stedi/
  layer: domain
  name: Stedi
  provider: stedi
  says: lists Stedi as an integration
  source: https://www.medplum.com/docs/integration
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
    mcp: &id019
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id020
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
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
    mcp: &id021
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id022
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pharmacy-prescriptions/medplum/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id005
  name: Candid Health
  slug: candid-health
  status: profiled
  tags: *id006
  url: /providers/candid-health/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id007
  name: DoseSpot
  slug: dosespot
  status: profiled
  tags: *id008
  url: /providers/dosespot/
- agent_band: agent-ready
  agent_readiness: 36.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id009
  name: Epic
  slug: epic-systems
  status: profiled
  tags: *id010
  url: /providers/epic-systems/
- agent_band: agent-ready
  agent_readiness: 42.5
  band: exemplar
  in_catalog: true
  kin_score: 75.7
  mcp: *id011
  name: Health Gorilla
  slug: health-gorilla
  status: profiled
  tags: *id012
  url: /providers/health-gorilla/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id013
  name: ScriptSure
  slug: scriptsure
  status: profiled
  tags: *id014
  url: /providers/scriptsure/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id015
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id016
  url: /providers/sendgrid/
- agent_band: agent-native
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id017
  name: Stedi
  slug: stedi
  status: profiled
  tags: *id018
  url: /providers/stedi/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id019
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id020
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id021
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id022
  url: /providers/twilio/
siblings:
- name: CVS Health
  rows: 8
  url: /applications/pharmacy-prescriptions/cvs-health/
- name: GoodRx
  rows: 8
  url: /applications/pharmacy-prescriptions/goodrx/
- name: Medisafe
  rows: 9
  url: /applications/pharmacy-prescriptions/medisafe/
- name: OpenEMR
  rows: 11
  url: /applications/pharmacy-prescriptions/openemr/
- name: Walgreens
  rows: 8
  url: /applications/pharmacy-prescriptions/walgreens/
sitemap: true
title: 'Medplum: Pharmacy & Prescriptions reference app'
---
