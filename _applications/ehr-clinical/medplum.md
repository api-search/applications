---
app: Medplum
app_slug: medplum
app_url: https://github.com/medplum/medplum
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.110
  key: AE-150.110
  layer: domain
  name: Cloud Fax
  providers:
  - eFax
  url: /capabilities/cloud-fax/
  via_parent: null
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
  id: BC-2900.60
  key: healthcare-interoperability-operations
  layer: domain
  name: Healthcare Interoperability Operations
  providers:
  - Epic
  - Health Gorilla
  - Zus Health
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
  id: BC-2900.60.40
  key: BC-2900.60.40
  layer: domain
  name: Provider Directory Maintenance
  providers:
  - NPPES NPI Registry
  url: /capabilities/healthcare-interoperability-operations/
  via_parent: Healthcare Interoperability Operations
- attribution: Turbo EA
  id: BC-2810.80.40
  key: BC-2810.80.40
  layer: domain
  name: Remote Monitoring Care
  providers:
  - AnyBio
  url: /capabilities/home-community-care-delivery/
  via_parent: Home & Community Care Delivery
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Snowflake
  url: /capabilities/analytics-bi-management/
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
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - reCAPTCHA
  url: /capabilities/bot-protection-captcha/
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
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
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
- attribution: API Evangelist extension
  id: AE-110.40
  key: AE-110.40
  layer: common
  name: Language & Document Understanding
  providers:
  - Amazon Comprehend Medical
  url: /capabilities/language-document-understanding/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: common
  name: OCR & Document AI
  providers:
  - Amazon Textract
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
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
- attribution: Turbo EA
  id: BC-930.60
  key: process-automation-governance
  layer: common
  name: Process Automation Governance
  providers:
  - AWS Lambda
  url: /capabilities/process-automation-governance/
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
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: common
  name: Scheduling & Appointment Management
  providers:
  - Acuity Scheduling
  - Cal.com
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  - Microsoft Entra
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: common
  name: Threat Detection & Response Management
  providers:
  - Amazon GuardDuty
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  url: /capabilities/email/
  via_parent: Email
category:
  id: ehr-clinical
  name: EHR & Clinical Practice
  url: /applications/ehr-clinical/
counts:
  declared: 24
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
- route: documentation
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
    agent_readiness: 32.8
    band: exemplar
    in_catalog: true
    kin_score: 70.7
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
  layer: common
  name: Amazon Comprehend Medical
  provider: amazon-comprehend
  says: ships the Amazon Comprehend Medical SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.2
    band: exemplar
    in_catalog: true
    kin_score: 73.8
    mcp: &id007
      source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
      status: documented
    slug: amazon-guardduty
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Anomaly Detection
    - Compliance
    - Machine Learning
    url: /providers/amazon-guardduty/
  layer: common
  name: Amazon GuardDuty
  provider: amazon-guardduty
  says: ships the Amazon GuardDuty SDK or integration code
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id009
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id010
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
    mcp: &id011
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id012
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
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.6
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id013
      status: none
    slug: amazon-textract
    status: profiled
    tags: &id014
    - Amazon Web Services
    - Document Processing
    - Machine Learning
    - OCR
    url: /providers/amazon-textract/
  layer: common
  name: Amazon Textract
  provider: amazon-textract
  says: ships the Amazon Textract SDK or integration code
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-930.60
    key: process-automation-governance
    name: Process Automation Governance
    url: /capabilities/process-automation-governance/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 74.9
    mcp: &id019
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id020
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
  layer: common
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
    agent_band: agent-native
    agent_readiness: 39.2
    band: exemplar
    in_catalog: true
    kin_score: 77.5
    mcp: &id021
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id022
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
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id023
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id024
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
    agent_band: agent-ready
    agent_readiness: 36.6
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id025
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-key-vault
    status: profiled
    tags: &id026
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
    agent_band: agent-ready
    agent_readiness: 33.7
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id039
      status: none
    slug: google-cloud-secret-manager
    status: profiled
    tags: &id040
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id041
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id042
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
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id045
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id046
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
    agent_readiness: 24.0
    band: thin
    in_catalog: true
    kin_score: 29.6
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
  layer: common
  name: Acuity Scheduling
  provider: acuity-scheduling
  says: lists Acuity Scheduling as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2810.80.40
    key: BC-2810.80.40
    name: Remote Monitoring Care
    url: /capabilities/home-community-care-delivery/
    via_parent: Home & Community Care Delivery
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: anybio
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: AnyBio
  provider: anybio
  says: lists AnyBio as an integration
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
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id017
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id018
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
    agent_readiness: 52.2
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id027
      source: https://github.com/calcom/cal-mcp
      status: verified
    slug: cal-com
    status: profiled
    tags: &id028
    - Calendar
    - Open Source
    - Productivity
    - Scheduling
    url: /providers/cal-com/
  layer: common
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
    agent_readiness: 36.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id029
      status: none
    slug: candid-health
    status: profiled
    tags: &id030
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
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id031
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id032
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
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
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id033
      status: none
    slug: dosespot
    status: profiled
    tags: &id034
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
    attribution: API Evangelist extension
    id: AE-150.110
    key: AE-150.110
    name: Cloud Fax
    url: /capabilities/cloud-fax/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id035
      status: unchecked
    slug: efax
    status: profiled
    tags: &id036
    - Cloud Fax
    - Fax
    - Government
    - Healthcare
    url: /providers/efax/
  layer: domain
  name: eFax
  provider: efax
  says: lists eFax as an integration
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
    agent_readiness: 36.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id037
      status: none
    slug: epic-systems
    status: profiled
    tags: &id038
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
    mcp: &id043
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id044
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
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
    agent_readiness: 42.5
    band: exemplar
    in_catalog: true
    kin_score: 75.7
    mcp: &id047
      status: none
    slug: health-gorilla
    status: profiled
    tags: &id048
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
    kin_score: 12.2
    mcp: &id049
      status: none
    slug: labcorp
    status: profiled
    tags: &id050
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
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id051
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id052
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Entra
  provider: microsoft-entra
  says: lists Microsoft Entra as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60.40
    key: BC-2900.60.40
    name: Provider Directory Maintenance
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: Healthcare Interoperability Operations
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.8
    mcp: &id053
      status: unknown
    slug: nppes
    status: profiled
    tags: &id054
    - Health
    - Public APIs
    url: /providers/nppes/
  layer: domain
  name: NPPES NPI Registry
  provider: nppes
  says: lists NPPES NPI Registry as an integration
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id055
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id056
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
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id057
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id058
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
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
    kin_score: 5.9
    mcp: &id059
      status: none
    slug: quest-diagnostics
    status: profiled
    tags: &id060
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
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id061
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id062
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: reCAPTCHA
  provider: google-recaptcha
  says: lists reCAPTCHA as an integration
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id063
      status: unknown
    slug: scriptsure
    status: profiled
    tags: &id064
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
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id065
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id066
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: common
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
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
    mcp: &id067
      source: https://www.stedi.com/docs/healthcare/mcp-server
      status: verified
    slug: stedi
    status: profiled
    tags: &id068
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
    mcp: &id069
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id070
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
    mcp: &id071
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id072
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
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id073
      status: none
    slug: zus
    status: profiled
    tags: &id074
    - FHIR
    - Health
    - Interoperability
    - Patient Data
    url: /providers/zus/
  layer: domain
  name: Zus Health
  provider: zus
  says: lists Zus Health as an integration
  source: https://www.medplum.com/docs/integration
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ehr-clinical/medplum/
providers:
- agent_band: agent-aware
  agent_readiness: 24.0
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id001
  name: Acuity Scheduling
  slug: acuity-scheduling
  status: profiled
  tags: *id002
  url: /providers/acuity-scheduling/
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
  agent_readiness: 32.8
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id005
  name: Amazon Comprehend Medical
  slug: amazon-comprehend
  status: profiled
  tags: *id006
  url: /providers/amazon-comprehend/
- agent_band: agent-native
  agent_readiness: 42.2
  band: exemplar
  in_catalog: true
  kin_score: 73.8
  mcp: *id007
  name: Amazon GuardDuty
  slug: amazon-guardduty
  status: profiled
  tags: *id008
  url: /providers/amazon-guardduty/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id009
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id010
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id011
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id012
  url: /providers/amazon-ses/
- agent_band: agent-native
  agent_readiness: 41.6
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id013
  name: Amazon Textract
  slug: amazon-textract
  status: profiled
  tags: *id014
  url: /providers/amazon-textract/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: AnyBio
  slug: anybio
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id017
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id018
  url: /providers/auth0/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 74.9
  mcp: *id019
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id020
  url: /providers/aws-lambda/
- agent_band: agent-native
  agent_readiness: 39.2
  band: exemplar
  in_catalog: true
  kin_score: 77.5
  mcp: *id021
  name: AWS Secrets Manager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id022
  url: /providers/amazon-secrets-manager/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id023
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id024
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id025
  name: Azure Key Vault
  slug: microsoft-azure-key-vault
  status: profiled
  tags: *id026
  url: /providers/microsoft-azure-key-vault/
- agent_band: agent-ready
  agent_readiness: 52.2
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id027
  name: Cal.com
  slug: cal-com
  status: profiled
  tags: *id028
  url: /providers/cal-com/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id029
  name: Candid Health
  slug: candid-health
  status: profiled
  tags: *id030
  url: /providers/candid-health/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id031
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id032
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id033
  name: DoseSpot
  slug: dosespot
  status: profiled
  tags: *id034
  url: /providers/dosespot/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id035
  name: eFax
  slug: efax
  status: profiled
  tags: *id036
  url: /providers/efax/
- agent_band: agent-ready
  agent_readiness: 36.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id037
  name: Epic
  slug: epic-systems
  status: profiled
  tags: *id038
  url: /providers/epic-systems/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id039
  name: Google Cloud Secret Manager
  slug: google-cloud-secret-manager
  status: profiled
  tags: *id040
  url: /providers/google-cloud-secret-manager/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id041
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id042
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id043
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id044
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id045
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id046
  url: /providers/have-i-been-pwned/
- agent_band: agent-ready
  agent_readiness: 42.5
  band: exemplar
  in_catalog: true
  kin_score: 75.7
  mcp: *id047
  name: Health Gorilla
  slug: health-gorilla
  status: profiled
  tags: *id048
  url: /providers/health-gorilla/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id049
  name: Labcorp
  slug: labcorp
  status: profiled
  tags: *id050
  url: /providers/labcorp/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id051
  name: Microsoft Entra
  slug: microsoft-entra
  status: profiled
  tags: *id052
  url: /providers/microsoft-entra/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.8
  mcp: *id053
  name: NPPES NPI Registry
  slug: nppes
  status: profiled
  tags: *id054
  url: /providers/nppes/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id055
  name: Okta
  slug: okta
  status: profiled
  tags: *id056
  url: /providers/okta/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id057
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id058
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id059
  name: Quest Diagnostics
  slug: quest-diagnostics
  status: profiled
  tags: *id060
  url: /providers/quest-diagnostics/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id061
  name: reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id062
  url: /providers/google-recaptcha/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id063
  name: ScriptSure
  slug: scriptsure
  status: profiled
  tags: *id064
  url: /providers/scriptsure/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id065
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id066
  url: /providers/snowflake/
- agent_band: agent-native
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id067
  name: Stedi
  slug: stedi
  status: profiled
  tags: *id068
  url: /providers/stedi/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id069
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id070
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id071
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id072
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id073
  name: Zus Health
  slug: zus
  status: profiled
  tags: *id074
  url: /providers/zus/
siblings:
- name: Elation Health
  rows: 24
  url: /applications/ehr-clinical/elation-health/
- name: Healthie
  rows: 23
  url: /applications/ehr-clinical/healthie/
- name: OpenEMR
  rows: 13
  url: /applications/ehr-clinical/openemr/
- name: OpenMRS (O3 Reference Application)
  rows: 2
  url: /applications/ehr-clinical/openmrs-o3-reference-application/
- name: Tebra (Kareo + PatientPop)
  rows: 7
  url: /applications/ehr-clinical/tebra-kareo-patientpop/
sitemap: true
title: 'Medplum: EHR & Clinical Practice reference app'
---
