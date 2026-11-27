---
access: understanding
agent_layer:
- app: Medplum
  finding: server depends on @modelcontextprotocol/sdk (Medplum ships its own MCP server surface); also a $ai operation backed by OpenAI
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
apps:
- anchor: openemr
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  - route: source code
    url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
  - route: source code
    url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Authorize.Net
    provider: authorizenet
    says: ships the Authorize.Net SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    credit: null
    layer: domain
    name: Claim.Revolution
    provider: claimrev
    says: ships the Claim.Revolution SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Clickatell
    provider: clickatell
    says: ships the Clickatell SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Comlink
    provider: comlink
    says: ships the Comlink SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2860.10
      key: laboratory-services-management
      name: Laboratory Services Management
      url: /capabilities/laboratory-services-management/
      via_parent: null
    credit: null
    layer: domain
    name: DORN
    provider: dorn
    says: ships the DORN SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: domain
    name: etherFAX
    provider: etherfax
    says: ships the etherFAX SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google
    provider: google
    says: ships the Google SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.20
      key: external-communications-management
      name: External Communications Management
      url: /capabilities/external-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: RingCentral
    provider: ringcentral
    says: ships the RingCentral SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: SignalWire
    provider: signalwire
    says: ships the SignalWire SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    credit: null
    layer: domain
    name: Weno Exchange
    provider: weno
    says: ships the Weno Exchange SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Yubico
    provider: yubico
    says: ships the Yubico SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
    tier: observed
  kind: self-hosted
  name: OpenEMR
  page: /applications/ehr-clinical/openemr/
  slug: openemr
  url: https://github.com/openemr/openemr
- anchor: openmrs-(o3-reference-application)
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/frontend/spa-assemble-config.json
  - route: source code
    url: https://github.com/openmrs/openmrs-module-openconceptlab
  - route: source code
    url: https://raw.githubusercontent.com/Bahmni/openmrs-module-teleconsultation/master/README.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bahmni
    provider: bahmni
    says: ships the Bahmni SDK or integration code
    source: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-945
      key: AE-945
      name: Clinical & Drug Terminology Services
      url: /capabilities/medical-coding-management/
      via_parent: Medical Coding Management
    credit: null
    layer: domain
    name: Open Concept Lab (OCL)
    provider: openconceptlab
    says: ships the Open Concept Lab (OCL) SDK or integration code
    source: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
    tier: observed
  kind: self-hosted
  name: OpenMRS (O3 Reference Application)
  page: /applications/ehr-clinical/openmrs-o3-reference-application/
  slug: openmrs-o3-reference-application
  url: https://github.com/openmrs/openmrs-distro-referenceapplication
- anchor: medplum
  counts:
    declared: 24
    observed: 13
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
    layer: domain
    name: Zus Health
    provider: zus
    says: lists Zus Health as an integration
    source: https://www.medplum.com/docs/integration
    tier: declared
  kind: open-source-saas
  name: Medplum
  page: /applications/ehr-clinical/medplum/
  slug: medplum
  url: https://github.com/medplum/medplum
- anchor: healthie
  counts:
    declared: 23
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.gethealthie.com/
  - route: integrations page
    url: https://www.gethealthie.com/healthie-harbor
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2830.40
      key: clinical-decision-support
      name: Clinical Decision Support
      url: /capabilities/clinical-decision-support/
      via_parent: null
    credit: null
    layer: domain
    name: Alvee Health
    provider: alvee
    says: lists Alvee Health as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Apple Health
    provider: apple
    says: lists Apple Health as an integration
    source: https://www.gethealthie.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    credit: null
    layer: domain
    name: Candid Health
    provider: candid-health
    says: lists Candid Health as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    credit: null
    layer: domain
    name: Claim.MD
    provider: claim-md
    says: lists Claim.MD as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    credit: null
    layer: domain
    name: Claim.Revolution
    provider: claimrev
    says: lists Claim.Revolution as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    credit: null
    layer: domain
    name: DoseSpot
    provider: dosespot
    says: lists DoseSpot as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: domain
    name: etherFAX
    provider: etherfax
    says: lists etherFAX as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Fitbit
    provider: fitbit
    says: lists Fitbit as an integration
    source: https://www.gethealthie.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fullscript
    provider: fullscript
    says: lists Fullscript as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Google Fit
    provider: google-fitness
    says: lists Google Fit as an integration
    source: https://www.gethealthie.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Keragon
    provider: keragon
    says: lists Keragon as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2860.10
      key: laboratory-services-management
      name: Laboratory Services Management
      url: /capabilities/laboratory-services-management/
      via_parent: null
    credit: null
    layer: domain
    name: Labcorp
    provider: labcorp
    says: lists Labcorp as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Metriport
    provider: metriport
    says: lists Metriport as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Morf Health
    provider: morf
    says: lists Morf Health as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2910.10
      key: patient-engagement-communication
      name: Patient Engagement & Communication
      url: /capabilities/patient-engagement-communication/
      via_parent: null
    credit: null
    layer: domain
    name: OhMD
    provider: ohmd
    says: lists OhMD as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60.40
      key: BC-2900.60.40
      name: Provider Directory Maintenance
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: Healthcare Interoperability Operations
    credit: null
    layer: domain
    name: Orderly Health
    provider: orderly-health
    says: lists Orderly Health as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Oura
    provider: oura-ring
    says: lists Oura as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2860.10
      key: laboratory-services-management
      name: Laboratory Services Management
      url: /capabilities/laboratory-services-management/
      via_parent: null
    credit: null
    layer: domain
    name: Quest Diagnostics
    provider: quest-diagnostics
    says: lists Quest Diagnostics as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: domain
    name: Sfax
    provider: sfax
    says: lists Sfax as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30
      key: nutrition-food-data
      name: Nutrition & Food Data
      url: /capabilities/nutrition-food-data/
      via_parent: null
    credit: null
    layer: domain
    name: Sifter Solutions
    provider: sifter-solutions
    says: lists Sifter Solutions as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2910.10
      key: patient-engagement-communication
      name: Patient Engagement & Communication
      url: /capabilities/patient-engagement-communication/
      via_parent: null
    credit: null
    layer: domain
    name: Tellescope
    provider: tellescope
    says: lists Tellescope as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zocdoc
    provider: zocdoc
    says: lists Zocdoc as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Zus Health
    provider: zus
    says: lists Zus Health as an integration
    source: https://www.gethealthie.com/healthie-harbor
    tier: declared
  kind: commercial
  name: Healthie
  page: /applications/ehr-clinical/healthie/
  slug: healthie
  url: https://www.gethealthie.com/
- anchor: elation-health
  counts:
    declared: 24
    observed: 0
  evidence:
  - route: integrations page
    url: https://partners.elationhealth.com/
  - route: integrations page
    url: https://www.elationhealth.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2880
      key: population-health-management
      name: Population Health Management
      url: /capabilities/population-health-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aledade
    provider: aledade
    says: lists Aledade as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2820
      key: care-coordination-management
      name: Care Coordination Management
      url: /capabilities/care-coordination-management/
      via_parent: null
    credit: null
    layer: domain
    name: Awell
    provider: awell
    says: lists Awell as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    credit: null
    layer: domain
    name: Candid Health
    provider: candid-health
    says: lists Candid Health as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2880
      key: population-health-management
      name: Population Health Management
      url: /capabilities/population-health-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cozeva
    provider: cozeva
    says: lists Cozeva as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2830
      key: clinical-documentation-management
      name: Clinical Documentation Management
      url: /capabilities/clinical-documentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: FlexScanMD
    provider: flexscanmd
    says: lists FlexScanMD as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.20
      key: patient-registration-management
      name: Patient Registration Management
      url: /capabilities/patient-registration-management/
      via_parent: null
    credit: null
    layer: domain
    name: FormDr
    provider: formdr
    says: lists FormDr as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fullscript
    provider: fullscript
    says: lists Fullscript as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Heads Up Health
    provider: heads-up-health
    says: lists Heads Up Health as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.20
      key: patient-registration-management
      name: Patient Registration Management
      url: /capabilities/patient-registration-management/
      via_parent: null
    credit: null
    layer: domain
    name: IntakeQ
    provider: intakeq
    says: lists IntakeQ as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Keragon
    provider: keragon
    says: lists Keragon as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: domain
    name: Medsender
    provider: medsender
    says: lists Medsender as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Metriport
    provider: metriport
    says: lists Metriport as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Morf Health
    provider: morf
    says: lists Morf Health as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2810.80.40
      key: BC-2810.80.40
      name: Remote Monitoring Care
      url: /capabilities/home-community-care-delivery/
      via_parent: Home & Community Care Delivery
    credit: null
    layer: domain
    name: Nsight Health
    provider: nsight-health
    says: lists Nsight Health as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2810.80.40
      key: BC-2810.80.40
      name: Remote Monitoring Care
      url: /capabilities/home-community-care-delivery/
      via_parent: Home & Community Care Delivery
    credit: null
    layer: domain
    name: Prevounce
    provider: prevounce
    says: lists Prevounce as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: rater8
    provider: rater8
    says: lists rater8 as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.30
      key: AE-150.50.30
      name: Virtual Receptionists & Answering Services
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Talkie.ai
    provider: talkie-ai
    says: lists Talkie.ai as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2820
      key: care-coordination-management
      name: Care Coordination Management
      url: /capabilities/care-coordination-management/
      via_parent: null
    credit: null
    layer: domain
    name: ThoroughCare
    provider: thoroughcare
    says: lists ThoroughCare as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2910.10
      key: patient-engagement-communication
      name: Patient Engagement & Communication
      url: /capabilities/patient-engagement-communication/
      via_parent: null
    credit: null
    layer: domain
    name: Updox
    provider: updox
    says: lists Updox as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    credit: null
    layer: domain
    name: VaxCare
    provider: vaxcare
    says: lists VaxCare as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2910.10
      key: patient-engagement-communication
      name: Patient Engagement & Communication
      url: /capabilities/patient-engagement-communication/
      via_parent: null
    credit: null
    layer: domain
    name: Weave
    provider: weave
    says: lists Weave as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.20
      key: patient-registration-management
      name: Patient Registration Management
      url: /capabilities/patient-registration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Yosi Health
    provider: yosi-health
    says: lists Yosi Health as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zocdoc
    provider: zocdoc
    says: lists Zocdoc as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Zus Health
    provider: zus
    says: lists Zus Health as an integration
    source: https://partners.elationhealth.com/
    tier: declared
  kind: commercial
  name: Elation Health
  page: /applications/ehr-clinical/elation-health/
  slug: elation-health
  url: https://www.elationhealth.com/
- anchor: tebra-(kareo-+-patientpop)
  counts:
    declared: 7
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.tebra.com/partner-marketplace
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    credit: null
    layer: domain
    name: Advantum Health
    provider: advantum-health
    says: lists Advantum Health as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2830
      key: clinical-documentation-management
      name: Clinical Documentation Management
      url: /capabilities/clinical-documentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: FlexScanMD
    provider: flexscanmd
    says: lists FlexScanMD as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    credit: null
    layer: domain
    name: GoodRx
    provider: goodrx
    says: lists GoodRx as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: domain
    name: Medsender
    provider: medsender
    says: lists Medsender as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2810.80.40
      key: BC-2810.80.40
      name: Remote Monitoring Care
      url: /capabilities/home-community-care-delivery/
      via_parent: Home & Community Care Delivery
    credit: null
    layer: domain
    name: Optimize Health
    provider: optimize-health
    says: lists Optimize Health as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2810.60
      key: behavioural-health-care-delivery
      name: Behavioural Health Care Delivery
      url: /capabilities/behavioural-health-care-delivery/
      via_parent: null
    credit: null
    layer: domain
    name: Rethink Behavioral Health
    provider: rethink-behavioral-health
    says: lists Rethink Behavioral Health as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2830
      key: clinical-documentation-management
      name: Clinical Documentation Management
      url: /capabilities/clinical-documentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: WoundZoom
    provider: woundzoom
    says: lists WoundZoom as an integration
    source: https://www.tebra.com/partner-marketplace
    tier: declared
  kind: commercial
  name: Tebra (Kareo + PatientPop)
  page: /applications/ehr-clinical/tebra-kareo-patientpop/
  slug: tebra-kareo-patientpop
  url: https://www.tebra.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: ehr-clinical
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Medical
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Medical
  store: google-play
  url: https://play.google.com/store/apps/category/MEDICAL
- category: Partners & Integrations
  store: elation-partner-hub
  url: https://partners.elationhealth.com/
- category: Integrations
  store: healthie-harbor
  url: https://www.gethealthie.com/healthie-harbor
- category: Featured Partners
  store: tebra-partner-marketplace
  url: https://www.tebra.com/partner-marketplace
- category: App Marketplace
  store: drchrono-marketplace
  url: https://www.drchrono.com/partners/
name: EHR & Clinical Practice
needs:
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 5 of 6 reference apps: Elation Health, Healthie, Medplum, OpenEMR, Tebra (Kareo + PatientPop)'
- capability:
    attribution: Turbo EA
    id: BC-850.20
    key: external-communications-management
    name: External Communications Management
    url: /capabilities/external-communications-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'used by 5 of 6 reference apps: Elation Health, Healthie, Medplum, OpenEMR, Tebra (Kareo + PatientPop)'
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 5 of 6 reference apps: Elation Health, Healthie, Medplum, OpenEMR, Tebra (Kareo + PatientPop)'
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 4 of 6 reference apps: Elation Health, Healthie, Medplum, OpenMRS (O3 Reference Application)'
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 3 of 6 reference apps: Healthie, Medplum, OpenEMR'
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 3 of 6 reference apps: Elation Health, Healthie, Medplum'
- capability:
    attribution: Turbo EA
    id: BC-2880
    key: population-health-management
    name: Population Health Management
    url: /capabilities/population-health-management/
    via_parent: null
  fit: gap
  layer: domain
  why: 'used by 3 of 6 reference apps: Elation Health, Medplum, Tebra (Kareo + PatientPop)'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 2 of 6 reference apps: Medplum, OpenEMR'
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: 'used by 2 of 6 reference apps: Medplum, OpenEMR'
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: 'used by 2 of 6 reference apps: Medplum, OpenEMR'
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: 'used by 2 of 6 reference apps: Elation Health, Healthie'
- capability:
    attribution: Turbo EA
    id: BC-2910.10
    key: patient-engagement-communication
    name: Patient Engagement & Communication
    url: /capabilities/patient-engagement-communication/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 2 of 6 reference apps: Elation Health, Healthie'
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  fit: exact
  layer: domain
  why: 'used by 2 of 6 reference apps: Elation Health, Healthie'
- capability:
    attribution: Turbo EA
    id: BC-2830
    key: clinical-documentation-management
    name: Clinical Documentation Management
    url: /capabilities/clinical-documentation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'used by 2 of 6 reference apps: Elation Health, Tebra (Kareo + PatientPop)'
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: OpenEMR'
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: OpenEMR'
- capability:
    attribution: API Evangelist extension
    id: AE-945
    key: AE-945
    name: Clinical & Drug Terminology Services
    url: /capabilities/medical-coding-management/
    via_parent: Medical Coding Management
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: OpenMRS (O3 Reference Application)'
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-930.60
    key: process-automation-governance
    name: Process Automation Governance
    url: /capabilities/process-automation-governance/
    via_parent: null
  fit: nearest
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-2800.30
    key: eligibility-benefits-verification
    name: Eligibility & Benefits Verification
    url: /capabilities/eligibility-benefits-verification/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: 'used by 1 of 6 reference apps: Medplum'
- capability:
    attribution: Turbo EA
    id: BC-2830.40
    key: clinical-decision-support
    name: Clinical Decision Support
    url: /capabilities/clinical-decision-support/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Healthie'
- capability:
    attribution: API Evangelist extension
    id: AE-130.30
    key: nutrition-food-data
    name: Nutrition & Food Data
    url: /capabilities/nutrition-food-data/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Healthie'
- capability:
    attribution: Turbo EA
    id: BC-2820
    key: care-coordination-management
    name: Care Coordination Management
    url: /capabilities/care-coordination-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Elation Health'
- capability:
    attribution: Turbo EA
    id: BC-2800.20
    key: patient-registration-management
    name: Patient Registration Management
    url: /capabilities/patient-registration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Elation Health'
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Elation Health'
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: domain
  why: 'used by 1 of 6 reference apps: Elation Health'
- capability:
    attribution: Turbo EA
    id: BC-2810.60
    key: behavioural-health-care-delivery
    name: Behavioural Health Care Delivery
    url: /capabilities/behavioural-health-care-delivery/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'used by 1 of 6 reference apps: Tebra (Kareo + PatientPop)'
- capability:
    attribution: API Evangelist extension
    id: AE-150.110
    key: AE-150.110
    name: Cloud Fax
    url: /capabilities/cloud-fax/
    via_parent: null
  fit: exact
  layer: domain
  why: etherFAX, eFax (Cloud Fax)
- capability:
    attribution: Turbo EA
    id: BC-2810.80.40
    key: BC-2810.80.40
    name: Remote Monitoring Care
    url: /capabilities/home-community-care-delivery/
    via_parent: Home & Community Care Delivery
  fit: exact
  layer: domain
  why: AnyBio, Nsight Health, Prevounce (Remote Monitoring Care)
- capability:
    attribution: Turbo EA
    id: BC-2900.60.40
    key: BC-2900.60.40
    name: Provider Directory Maintenance
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: Healthcare Interoperability Operations
  fit: exact
  layer: domain
  why: NPPES NPI Registry, Orderly Health (Provider Directory Maintenance)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Healthie
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        status: none
      name: DoseSpot
      slug: dosespot
      sources:
      - https://www.gethealthie.com/healthie-harbor
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Electronic Health Records
      - Healthcare
      - e-Prescribing
      - eRx
      tier: declared
      url: /providers/dosespot/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Elation Health
      - Healthie
      band: emerging
      in_catalog: true
      kin_score: 25.4
      mcp:
        status: unchecked
      name: Fullscript
      slug: fullscript
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Healthcare
      - Lab Testing
      - Patient Care
      - Supplements
      tier: declared
      url: /providers/fullscript/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMR
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: Weno Exchange
      slug: weno
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
      status: profiled
      tags:
      - Company
      - Healthcare
      - Pharmacy
      - e-Prescribing
      tier: observed
      url: /providers/weno/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Elation Health
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: unchecked
      name: VaxCare
      slug: vaxcare
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Contraceptives
      - Health Systems
      - Pediatrics
      - Vaccines
      tier: declared
      url: /providers/vaxcare/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Tebra (Kareo + PatientPop)
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unchecked
      name: GoodRx
      slug: goodrx
      sources:
      - https://www.tebra.com/partner-marketplace
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/goodrx/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Medplum
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unknown
      name: ScriptSure
      slug: scriptsure
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/scriptsure/
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Elation Health
      - Healthie
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Zus Health
      slug: zus
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - FHIR
      - Health
      - Interoperability
      - Patient Data
      tier: declared
      url: /providers/zus/
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Elation Health
      - Healthie
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://mcp.metriport.com/.well-known/oauth-protected-resource
        status: verified
      name: Metriport
      slug: metriport
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - FHIR
      - Health Data
      - Healthcare
      - Medical Records
      tier: declared
      url: /providers/metriport/
    - agent_band: agent-ready
      agent_readiness: 42.5
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 75.7
      mcp:
        status: none
      name: Health Gorilla
      slug: health-gorilla
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Clinical Data
      - FHIR
      - Health
      - Interoperability
      tier: declared
      url: /providers/health-gorilla/
    - agent_band: agent-ready
      agent_readiness: 36.8
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        status: none
      name: Epic
      slug: epic-systems
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Electronic Health Records
      - FHIR
      - Healthcare
      - United States
      tier: declared
      url: /providers/epic-systems/
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Elation Health
      - Healthie
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Candid Health
      slug: candid-health
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Claims
      - Healthcare
      - Medical Billing
      - Revenue Cycle Management
      tier: declared
      url: /providers/candid-health/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - Healthie
      - OpenEMR
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        status: none
      name: Claim.Revolution
      slug: claimrev
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Billing
      - Claims
      - Company
      - Healthcare
      tier: observed
      url: /providers/claimrev/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Healthie
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: unknown
      name: Claim.MD
      slug: claim-md
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Clearinghouse
      - EDI
      - Healthcare
      - Medical Claims
      tier: declared
      url: /providers/claim-md/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Tebra (Kareo + PatientPop)
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unchecked
      name: Advantum Health
      slug: advantum-health
      sources:
      - https://www.tebra.com/partner-marketplace
      status: profiled
      tags:
      - Artificial Intelligence
      - Billing
      - Healthcare
      - Revenue Cycle Management
      tier: declared
      url: /providers/advantum-health/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Healthie
      - OpenEMR
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: etherFAX
      slug: etherfax
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Fax
      - Secure
      tier: observed
      url: /providers/etherfax/
    - agent_band: agent-ready
      agent_readiness: 44.0
      apps:
      - Elation Health
      - Tebra (Kareo + PatientPop)
      band: strong
      in_catalog: true
      kin_score: 55.0
      mcp:
        status: unchecked
      name: Medsender
      slug: medsender
      sources:
      - https://partners.elationhealth.com/
      - https://www.tebra.com/partner-marketplace
      status: profiled
      tags:
      - Call Automation
      - Fax Automation
      - Patient Recapture
      - Referral Management
      tier: declared
      url: /providers/medsender/
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Medplum
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: unchecked
      name: eFax
      slug: efax
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Cloud Fax
      - Fax
      - Government
      - Healthcare
      tier: declared
      url: /providers/efax/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Healthie
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: Sfax
      slug: sfax
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/sfax/
  - capability:
      attribution: Turbo EA
      id: BC-2860.10
      key: laboratory-services-management
      name: Laboratory Services Management
      url: /capabilities/laboratory-services-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Healthie
      - Medplum
      band: emerging
      in_catalog: true
      kin_score: 12.2
      mcp:
        status: none
      name: Labcorp
      slug: labcorp
      sources:
      - https://www.gethealthie.com/healthie-harbor
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Diagnostics
      - FHIR
      - Fortune 500
      - Healthcare
      tier: declared
      url: /providers/labcorp/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Healthie
      - Medplum
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: none
      name: Quest Diagnostics
      slug: quest-diagnostics
      sources:
      - https://www.gethealthie.com/healthie-harbor
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Diagnostics
      - Fortune 500
      - Healthcare
      - Laboratory
      tier: declared
      url: /providers/quest-diagnostics/
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenEMR
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unknown
      name: DORN
      slug: dorn
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.10
      key: AE-130.20.10
      name: Wearable Data Aggregation
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Healthie
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Fitbit
      slug: fitbit
      sources:
      - https://www.gethealthie.com/
      status: profiled
      tags:
      - Activity Tracking
      - Fitness
      - Health
      - Wearables
      tier: declared
      url: /providers/fitbit/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Healthie
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Health
      slug: apple
      sources:
      - https://www.gethealthie.com/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Healthie
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Google Fit
      slug: google-fitness
      sources:
      - https://www.gethealthie.com/
      status: profiled
      tags:
      - Activity Tracking
      - Fitness
      - Google
      - Health
      tier: declared
      url: /providers/google-fitness/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - Healthie
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        status: none
      name: Oura
      slug: oura-ring
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Activity
      - Biometrics
      - Cardiovascular
      - Fitness
      tier: declared
      url: /providers/oura-ring/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Elation Health
      band: emerging
      in_catalog: true
      kin_score: 26.0
      mcp:
        status: unchecked
      name: Heads Up Health
      slug: heads-up-health
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Artificial Intelligence
      - Clinical Intelligence
      - Health
      - Wearables
      tier: declared
      url: /providers/heads-up-health/
  - capability:
      attribution: Turbo EA
      id: BC-2910.10
      key: patient-engagement-communication
      name: Patient Engagement & Communication
      url: /capabilities/patient-engagement-communication/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Elation Health
      band: strong
      in_catalog: true
      kin_score: 58.1
      mcp:
        status: none
      name: Weave
      slug: weave
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Communications
      - Company
      - Messaging
      - Payments
      tier: declared
      url: /providers/weave/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Healthie
      band: thin
      in_catalog: true
      kin_score: 26.7
      mcp:
        status: unchecked
      name: Tellescope
      slug: tellescope
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Digital Health
      - EHR Integration
      - Patient Intake
      - Telehealth
      tier: declared
      url: /providers/tellescope/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Elation Health
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: unknown
      name: Updox
      slug: updox
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Electronic Fax
      - Healthcare
      - Patient Engagement
      - Secure Messaging
      tier: declared
      url: /providers/updox/
    - agent_band: human-only
      agent_readiness: 3.7
      apps:
      - Healthie
      band: emerging
      in_catalog: true
      kin_score: 20.4
      mcp:
        status: unchecked
      name: OhMD
      slug: ohmd
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Artificial Intelligence
      - HIPAA
      - Healthcare
      - Patient Communication
      tier: declared
      url: /providers/ohmd/
  - capability:
      attribution: Turbo EA
      id: BC-2810.80.40
      key: BC-2810.80.40
      name: Remote Monitoring Care
      url: /capabilities/home-community-care-delivery/
      via_parent: Home & Community Care Delivery
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Elation Health
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unchecked
      name: Nsight Health
      slug: nsight-health
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Artificial Intelligence
      - Chronic Care
      - Healthcare
      - Remote Monitoring
      tier: declared
      url: /providers/nsight-health/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Elation Health
      band: emerging
      in_catalog: true
      kin_score: 11.5
      mcp:
        status: unchecked
      name: Prevounce
      slug: prevounce
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Healthcare
      - Remote Monitoring
      tier: declared
      url: /providers/prevounce/
    - agent_band: null
      agent_readiness: null
      apps:
      - Medplum
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: AnyBio
      slug: anybio
      sources:
      - https://www.medplum.com/docs/integration
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Tebra (Kareo + PatientPop)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Optimize Health
      slug: optimize-health
      sources:
      - https://www.tebra.com/partner-marketplace
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - Elation Health
      - Healthie
      band: developing
      in_catalog: true
      kin_score: 47.0
      mcp:
        status: none
      name: Morf Health
      slug: morf
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Automation
      - Company
      - Health IT
      - Healthcare
      tier: declared
      url: /providers/morf/
    - agent_band: agent-aware
      agent_readiness: 20.4
      apps:
      - Elation Health
      - Healthie
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: unchecked
      name: Keragon
      slug: keragon
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Healthcare
      - Integration
      tier: declared
      url: /providers/keragon/
  - capability:
      attribution: Turbo EA
      id: BC-2830
      key: clinical-documentation-management
      name: Clinical Documentation Management
      url: /capabilities/clinical-documentation-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 7.4
      apps:
      - Elation Health
      - Tebra (Kareo + PatientPop)
      band: emerging
      in_catalog: true
      kin_score: 16.7
      mcp:
        status: unchecked
      name: FlexScanMD
      slug: flexscanmd
      sources:
      - https://partners.elationhealth.com/
      - https://www.tebra.com/partner-marketplace
      status: profiled
      tags:
      - Cloud‑based
      - Compliance
      - Inventory
      - Medical Software
      tier: declared
      url: /providers/flexscanmd/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Tebra (Kareo + PatientPop)
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: unchecked
      name: WoundZoom
      slug: woundzoom
      sources:
      - https://www.tebra.com/partner-marketplace
      status: profiled
      tags:
      - Healthcare Software
      - Hospitals
      - Long-Term Care
      - Wound Care
      tier: declared
      url: /providers/woundzoom/
  - capability:
      attribution: Turbo EA
      id: BC-2800.20
      key: patient-registration-management
      name: Patient Registration Management
      url: /capabilities/patient-registration-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Elation Health
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp:
        status: unchecked
      name: FormDr
      slug: formdr
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Forms
      - HIPAA
      - Healthcare
      - Patient Intake
      tier: declared
      url: /providers/formdr/
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - Elation Health
      band: thin
      in_catalog: true
      kin_score: 26.7
      mcp:
        status: unknown
      name: IntakeQ
      slug: intakeq
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Health and Wellness
      - Intake Forms
      - Practice Management
      - Scheduling
      tier: declared
      url: /providers/intakeq/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Elation Health
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: unchecked
      name: Yosi Health
      slug: yosi-health
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Healthcare
      - Patient Intake
      - Scheduling
      - Telehealth
      tier: declared
      url: /providers/yosi-health/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - Elation Health
      - Healthie
      band: strong
      in_catalog: true
      kin_score: 55.0
      mcp:
        source: https://api-docs.zocdoc.com/guides
        status: documented
      name: Zocdoc
      slug: zocdoc
      sources:
      - https://partners.elationhealth.com/
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Appointments
      - Booking
      - Healthcare
      - Providers
      tier: declared
      url: /providers/zocdoc/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenMRS (O3 Reference Application)
      band: minimal
      in_catalog: true
      kin_score: 6.7
      mcp:
        status: unchecked
      name: Bahmni
      slug: bahmni
      sources:
      - https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
      status: profiled
      tags:
      - Electronic Health Records
      - Healthcare
      - Hospital Information System
      - Open Source
      tier: observed
      url: /providers/bahmni/
  - capability:
      attribution: Turbo EA
      id: BC-2820
      key: care-coordination-management
      name: Care Coordination Management
      url: /capabilities/care-coordination-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Elation Health
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: unchecked
      name: Awell
      slug: awell
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Artificial Intelligence
      - CareOps
      - Healthcare
      - Platform
      tier: declared
      url: /providers/awell/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Elation Health
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: ThoroughCare
      slug: thoroughcare
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/thoroughcare/
  - capability:
      attribution: Turbo EA
      id: BC-2880
      key: population-health-management
      name: Population Health Management
      url: /capabilities/population-health-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - Elation Health
      band: emerging
      in_catalog: true
      kin_score: 14.9
      mcp:
        status: unknown
      name: Aledade
      slug: aledade
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Company
      - Healthcare
      - Life Sciences
      - Value-Based Care
      tier: declared
      url: /providers/aledade/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Elation Health
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: unchecked
      name: Cozeva
      slug: cozeva
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Data Platform
      - Healthcare
      - Quality Measurement
      - Risk Adjustment
      tier: declared
      url: /providers/cozeva/
  - capability:
      attribution: Turbo EA
      id: BC-2900.60.40
      key: BC-2900.60.40
      name: Provider Directory Maintenance
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: Healthcare Interoperability Operations
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - Healthie
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Orderly Health
      slug: orderly-health
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Company
      - Healthcare
      - Provider Data
      - Provider Directory
      tier: declared
      url: /providers/orderly-health/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Medplum
      band: minimal
      in_catalog: true
      kin_score: 2.8
      mcp:
        status: unknown
      name: NPPES NPI Registry
      slug: nppes
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Health
      - Public APIs
      tier: declared
      url: /providers/nppes/
  - capability:
      attribution: Turbo EA
      id: BC-2810.60
      key: behavioural-health-care-delivery
      name: Behavioural Health Care Delivery
      url: /capabilities/behavioural-health-care-delivery/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.5
      apps:
      - Tebra (Kareo + PatientPop)
      band: thin
      in_catalog: true
      kin_score: 31.2
      mcp:
        status: unchecked
      name: Rethink Behavioral Health
      slug: rethink-behavioral-health
      sources:
      - https://www.tebra.com/partner-marketplace
      status: profiled
      tags:
      - ABA
      - Healthcare
      - Practice Management
      - Software
      tier: declared
      url: /providers/rethink-behavioral-health/
  - capability:
      attribution: API Evangelist extension
      id: AE-945
      key: AE-945
      name: Clinical & Drug Terminology Services
      url: /capabilities/medical-coding-management/
      via_parent: Medical Coding Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.5
      apps:
      - OpenMRS (O3 Reference Application)
      band: developing
      in_catalog: true
      kin_score: 44.2
      mcp:
        status: unchecked
      name: Open Concept Lab (OCL)
      slug: openconceptlab
      sources:
      - https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
      status: profiled
      tags:
      - Company
      - Health
      - Open Source
      - Terminology
      tier: observed
      url: /providers/openconceptlab/
  - capability:
      attribution: Turbo EA
      id: BC-2830.40
      key: clinical-decision-support
      name: Clinical Decision Support
      url: /capabilities/clinical-decision-support/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Healthie
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: unknown
      name: Alvee Health
      slug: alvee
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Company
      - Healthcare
      - SDOH
      - Social Determinants of Health
      tier: declared
      url: /providers/alvee/
  - capability:
      attribution: Turbo EA
      id: BC-2800.30
      key: eligibility-benefits-verification
      name: Eligibility & Benefits Verification
      url: /capabilities/eligibility-benefits-verification/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 65.7
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://www.stedi.com/docs/healthcare/mcp-server
        status: verified
      name: Stedi
      slug: stedi
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Clearinghouse
      - EDI
      - Electronic Data Interchange
      - Healthcare
      tier: declared
      url: /providers/stedi/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30
      key: nutrition-food-data
      name: Nutrition & Food Data
      url: /capabilities/nutrition-food-data/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Healthie
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: unchecked
      name: Sifter Solutions
      slug: sifter-solutions
      sources:
      - https://www.gethealthie.com/healthie-harbor
      status: profiled
      tags:
      - Company
      - Food
      - Healthcare
      - Nutrition
      tier: declared
      url: /providers/sifter-solutions/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - Elation Health
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: unchecked
      name: rater8
      slug: rater8
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Healthcare
      - Management
      - Reputation
      - Software-as-a-Service
      tier: declared
      url: /providers/rater8/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenEMR
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: none
      name: Comlink
      slug: comlink
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.30
      key: AE-150.50.30
      name: Virtual Receptionists & Answering Services
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Elation Health
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        status: unchecked
      name: Talkie.ai
      slug: talkie-ai
      sources:
      - https://partners.elationhealth.com/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Healthcare
      - MedicalReceptionist
      tier: declared
      url: /providers/talkie-ai/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        status: none
      name: Amazon CloudFront
      slug: cloudfront
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - CDN
      - Caching
      - Content Delivery
      tier: observed
      url: /providers/cloudfront/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Medplum
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 74.2
      mcp:
        status: none
      name: SignalWire
      slug: signalwire
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      status: profiled
      tags:
      - CPaaS
      - Communications
      - Company
      - Voice
      tier: observed
      url: /providers/signalwire/
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - OpenEMR
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        status: none
      name: Clickatell
      slug: clickatell
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      status: profiled
      tags:
      - Company
      - Messaging
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/clickatell/
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 39.2
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 77.5
      mcp:
        status: none
      name: AWS Secrets Manager
      slug: amazon-secrets-manager
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Configuration
      - Credentials
      - Rotation
      tier: observed
      url: /providers/amazon-secrets-manager/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        status: none
      name: Google Cloud Secret Manager
      slug: google-cloud-secret-manager
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Configuration
      - Credentials
      - Google Cloud
      - Key Management
      tier: observed
      url: /providers/google-cloud-secret-manager/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Key Vault
      slug: microsoft-azure-key-vault
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Certificates
      - Cloud Security
      - Cryptography
      - Key Management
      tier: observed
      url: /providers/microsoft-azure-key-vault/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Medplum
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - OpenEMR
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.Net
      slug: authorizenet
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google
      slug: google
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra
      slug: microsoft-entra
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: declared
      url: /providers/auth0/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.2
      apps:
      - Medplum
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        source: https://github.com/calcom/cal-mcp
        status: verified
      name: Cal.com
      slug: cal-com
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Calendar
      - Open Source
      - Productivity
      - Scheduling
      tier: declared
      url: /providers/cal-com/
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - Medplum
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Acuity Scheduling
      slug: acuity-scheduling
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Appointment Scheduling
      - Booking
      - Calendar
      - Scheduling
      tier: declared
      url: /providers/acuity-scheduling/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: declared
      url: /providers/snowflake/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: declared
      url: /providers/google-recaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - Medplum
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp:
        status: none
      name: Have I Been Pwned
      slug: have-i-been-pwned
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Data Breaches
      - Identity
      - Pwned Passwords
      - Security
      tier: observed
      url: /providers/have-i-been-pwned/
  - capability:
      attribution: Turbo EA
      id: BC-850.20
      key: external-communications-management
      name: External Communications Management
      url: /capabilities/external-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.6
      apps:
      - OpenEMR
      band: strong
      in_catalog: true
      kin_score: 59.4
      mcp:
        source: https://developers.ringcentral.com/mcp
        status: documented
      name: RingCentral
      slug: ringcentral
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      status: profiled
      tags:
      - Communications
      - UCaaS
      - Video
      - Voice
      tier: observed
      url: /providers/ringcentral/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40
      key: AE-110.40
      name: Language & Document Understanding
      url: /capabilities/language-document-understanding/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: Amazon Comprehend Medical
      slug: amazon-comprehend
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Machine Learning
      - Natural Language Processing
      - Text Analysis
      tier: observed
      url: /providers/amazon-comprehend/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.0
      apps:
      - OpenEMR
      band: strong
      in_catalog: true
      kin_score: 58.0
      mcp:
        status: none
      name: Yubico
      slug: yubico
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Company
      - Enterprise
      - Security
      tier: observed
      url: /providers/yubico/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-native
      agent_readiness: 41.6
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 69.2
      mcp:
        status: none
      name: Amazon Textract
      slug: amazon-textract
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Document Processing
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/amazon-textract/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 74.9
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
        status: verified
      name: AWS Lambda
      slug: aws-lambda
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Serverless
      tier: observed
      url: /providers/aws-lambda/
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 42.2
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 73.8
      mcp:
        source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
        status: documented
      name: Amazon GuardDuty
      slug: amazon-guardduty
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Anomaly Detection
      - Compliance
      - Machine Learning
      tier: observed
      url: /providers/amazon-guardduty/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
  layer: common
summary:
  coverage_pct: 95.5
  declared_only: 60
  distinct_providers: 88
  in_catalog: 84
  mcp:
    documented: 3
    none: 32
    unchecked: 28
    verified: 17
  mcp_verified: 17
  mean_kin_score: 45.0
  observed: 28
  queued: 4
  reference_apps: 6
title: 'EHR & Clinical Practice: application blueprint'
---
