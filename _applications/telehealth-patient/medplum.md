---
app: Medplum
app_slug: medplum
app_url: https://github.com/medplum/medplum
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2900.60
  key: healthcare-interoperability-operations
  layer: domain
  name: Healthcare Interoperability Operations
  providers:
  - Epic
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
- attribution: Turbo EA
  id: BC-2860.10
  key: laboratory-services-management
  layer: domain
  name: Laboratory Services Management
  providers:
  - Health Gorilla
  - Labcorp
  - Quest Diagnostics
  url: /capabilities/laboratory-services-management/
  via_parent: null
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
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Acuity Scheduling
  - Cal.com
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon CloudFront
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - AWS Secrets Manager
  - Azure Key Vault
  - Google Cloud Secret Manager
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.60
  key: AE-160.60
  layer: common
  name: Credential Security
  providers:
  - Have I Been Pwned
  url: /capabilities/credential-security/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Auth0
  - Okta
  url: /capabilities/identity-access-management/
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
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: agent
  name: Artificial Intelligence Management
  providers:
  - AWS Lambda
  - OpenAI
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40
  key: AE-110.40
  layer: agent
  name: Language & Document Understanding
  providers:
  - Amazon Comprehend Medical
  - Amazon Textract
  url: /capabilities/language-document-understanding/
  via_parent: null
category:
  id: telehealth-patient
  name: Telehealth & Patient Apps
  url: /applications/telehealth-patient/
counts:
  declared: 14
  observed: 12
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
- route: integrations page
  url: https://www.medplum.com/docs/integration
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
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
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
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id005
      status: none
    slug: amazon-comprehend
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Machine Learning
    - Natural Language Processing
    - Text Analysis
    url: /providers/amazon-comprehend/
  layer: agent
  name: Amazon Comprehend Medical
  provider: amazon-comprehend
  says: ships the Amazon Comprehend Medical SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id008
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
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id009
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id010
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
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: developing
    in_catalog: true
    kin_score: 52.7
    mcp: &id011
      status: none
    slug: amazon-textract
    status: profiled
    tags: &id012
    - Amazon Web Services
    - Document Processing
    - Machine Learning
    - OCR
    url: /providers/amazon-textract/
  layer: agent
  name: Amazon Textract
  provider: amazon-textract
  says: ships the Amazon Textract SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
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
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id015
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id016
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
  layer: agent
  name: AWS Lambda
  provider: aws-lambda
  says: ships the AWS Lambda SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id017
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id018
    - Amazon Web Services
    - Configuration
    - Credentials
    - Rotation
    url: /providers/amazon-secrets-manager/
  layer: common
  name: AWS Secrets Manager
  provider: amazon-secrets-manager
  says: ships the AWS Secrets Manager SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
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
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id019
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id020
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 53.3
    mcp: &id021
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-key-vault
    status: profiled
    tags: &id022
    - Certificates
    - Cloud Security
    - Cryptography
    - Key Management
    url: /providers/microsoft-azure-key-vault/
  layer: common
  name: Azure Key Vault
  provider: microsoft-azure-key-vault
  says: ships the Azure Key Vault SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id031
      status: none
    slug: google-cloud-secret-manager
    status: profiled
    tags: &id032
    - Configuration
    - Credentials
    - Google Cloud
    - Key Management
    url: /providers/google-cloud-secret-manager/
  layer: common
  name: Google Cloud Secret Manager
  provider: google-cloud-secret-manager
  says: ships the Google Cloud Secret Manager SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id033
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id034
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id035
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id036
    - Data Breaches
    - Identity
    - Pwned Passwords
    - Security
    url: /providers/have-i-been-pwned/
  layer: common
  name: Have I Been Pwned
  provider: have-i-been-pwned
  says: ships the Have I Been Pwned SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.5
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id001
      status: none
    slug: acuity-scheduling
    status: profiled
    tags: &id002
    - Appointment Scheduling
    - Booking
    - Calendar
    - Scheduling
    url: /providers/acuity-scheduling/
  layer: domain
  name: Acuity Scheduling
  provider: acuity-scheduling
  says: lists Acuity Scheduling as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id013
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id014
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0
  provider: auth0
  says: lists Auth0 as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.9
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id023
      source: https://github.com/calcom/cal-mcp
      status: verified
    slug: cal-com
    status: profiled
    tags: &id024
    - Calendar
    - Open Source
    - Productivity
    - Scheduling
    url: /providers/cal-com/
  layer: domain
  name: Cal.com
  provider: cal-com
  says: lists Cal.com as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
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
    agent_readiness: 36.9
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id025
      status: none
    slug: candid-health
    status: profiled
    tags: &id026
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
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id027
      status: none
    slug: dosespot
    status: profiled
    tags: &id028
    - Electronic Health Records
    - Healthcare
    - e-Prescribing
    - eRx
    url: /providers/dosespot/
  layer: domain
  name: DoseSpot
  provider: dosespot
  says: lists DoseSpot as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id029
      status: none
    slug: epic-systems
    status: profiled
    tags: &id030
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
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id037
      status: none
    slug: health-gorilla
    status: profiled
    tags: &id038
    - Clinical Data
    - FHIR
    - Health
    - Interoperability
    url: /providers/health-gorilla/
  layer: domain
  name: Health Gorilla
  provider: health-gorilla
  says: lists Health Gorilla as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id039
      status: none
    slug: labcorp
    status: profiled
    tags: &id040
    - Diagnostics
    - FHIR
    - Fortune 500
    - Healthcare
    url: /providers/labcorp/
  layer: domain
  name: Labcorp
  provider: labcorp
  says: lists Labcorp as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
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
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id041
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id042
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id043
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id045
      status: none
    slug: quest-diagnostics
    status: profiled
    tags: &id046
    - Diagnostics
    - Fortune 500
    - Healthcare
    - Laboratory
    url: /providers/quest-diagnostics/
  layer: domain
  name: Quest Diagnostics
  provider: quest-diagnostics
  says: lists Quest Diagnostics as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id047
      status: unknown
    slug: scriptsure
    status: profiled
    tags: &id048
    - Company
    url: /providers/scriptsure/
  layer: domain
  name: ScriptSure
  provider: scriptsure
  says: lists ScriptSure as an integration
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id049
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id050
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id051
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id052
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
permalink: /applications/telehealth-patient/medplum/
providers:
- agent_band: agent-aware
  agent_readiness: 24.5
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id001
  name: Acuity Scheduling
  slug: acuity-scheduling
  status: profiled
  tags: *id002
  url: /providers/acuity-scheduling/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id003
  name: Amazon CloudFront
  slug: cloudfront
  status: profiled
  tags: *id004
  url: /providers/cloudfront/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id005
  name: Amazon Comprehend Medical
  slug: amazon-comprehend
  status: profiled
  tags: *id006
  url: /providers/amazon-comprehend/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id007
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id008
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id009
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id010
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 52.7
  mcp: *id011
  name: Amazon Textract
  slug: amazon-textract
  status: profiled
  tags: *id012
  url: /providers/amazon-textract/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id013
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id014
  url: /providers/auth0/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id015
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id016
  url: /providers/aws-lambda/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id017
  name: AWS Secrets Manager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id018
  url: /providers/amazon-secrets-manager/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id019
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id020
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 53.3
  mcp: *id021
  name: Azure Key Vault
  slug: microsoft-azure-key-vault
  status: profiled
  tags: *id022
  url: /providers/microsoft-azure-key-vault/
- agent_band: agent-ready
  agent_readiness: 51.9
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id023
  name: Cal.com
  slug: cal-com
  status: profiled
  tags: *id024
  url: /providers/cal-com/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id025
  name: Candid Health
  slug: candid-health
  status: profiled
  tags: *id026
  url: /providers/candid-health/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id027
  name: DoseSpot
  slug: dosespot
  status: profiled
  tags: *id028
  url: /providers/dosespot/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id029
  name: Epic
  slug: epic-systems
  status: profiled
  tags: *id030
  url: /providers/epic-systems/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id031
  name: Google Cloud Secret Manager
  slug: google-cloud-secret-manager
  status: profiled
  tags: *id032
  url: /providers/google-cloud-secret-manager/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id033
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id034
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id035
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id036
  url: /providers/have-i-been-pwned/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id037
  name: Health Gorilla
  slug: health-gorilla
  status: profiled
  tags: *id038
  url: /providers/health-gorilla/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id039
  name: Labcorp
  slug: labcorp
  status: profiled
  tags: *id040
  url: /providers/labcorp/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id041
  name: Okta
  slug: okta
  status: profiled
  tags: *id042
  url: /providers/okta/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id043
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id044
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id045
  name: Quest Diagnostics
  slug: quest-diagnostics
  status: profiled
  tags: *id046
  url: /providers/quest-diagnostics/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id047
  name: ScriptSure
  slug: scriptsure
  status: profiled
  tags: *id048
  url: /providers/scriptsure/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id049
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id050
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id051
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id052
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
- name: MyChart (Epic)
  rows: 0
  url: /applications/telehealth-patient/mychart-epic/
- name: OpenEMR
  rows: 13
  url: /applications/telehealth-patient/openemr/
- name: Ottehr
  rows: 12
  url: /applications/telehealth-patient/ottehr/
- name: Teladoc
  rows: 8
  url: /applications/telehealth-patient/teladoc/
- name: Zocdoc
  rows: 6
  url: /applications/telehealth-patient/zocdoc/
sitemap: true
title: 'Medplum: Telehealth & Patient Apps reference app'
---
