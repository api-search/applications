---
access: understanding
agent_layer:
- app: Medplum
  finding: server depends on @modelcontextprotocol/sdk -- Medplum exposes its own MCP server over FHIR
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
- app: Ottehr
  finding: '@langchain/anthropic + @langchain/core in the root deps -- LLM features built on Claude'
  source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
  tier: observed
apps:
- anchor: teladoc
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bugfender
    provider: bugfender
    says: ships the Bugfender SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
    tier: observed
  kind: commercial
  name: Teladoc
  page: /applications/telehealth-patient/teladoc/
  slug: teladoc
  url: https://www.teladoc.com/
- anchor: zocdoc
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Optimizely
    provider: optimizely
    says: ships the Optimizely SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
    tier: observed
  kind: commercial
  name: Zocdoc
  page: /applications/telehealth-patient/zocdoc/
  slug: zocdoc
  url: https://www.zocdoc.com/
- anchor: doctor-on-demand-(included-health)
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics + Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics + Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
    tier: observed
  kind: commercial
  name: Doctor On Demand (Included Health)
  page: /applications/telehealth-patient/doctor-on-demand-included-health/
  slug: doctor-on-demand-included-health
  url: https://doctorondemand.com/
- anchor: mdlive
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.mdlive.mobile/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Braze
    provider: braze
    says: ships the Braze SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mdlive.mobile/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics + Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics + Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mdlive.mobile/latest/
    tier: observed
  kind: commercial
  name: MDLIVE
  page: /applications/telehealth-patient/mdlive/
  slug: mdlive
  url: https://www.mdlive.com/
- anchor: doctolib
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adjust
    provider: adjust
    says: ships the Adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Didomi
    provider: didomi
    says: ships the Didomi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
    tier: observed
  kind: commercial
  name: Doctolib
  page: /applications/telehealth-patient/doctolib/
  slug: doctolib
  url: https://www.doctolib.fr/
- anchor: mychart-(epic)
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/epic.mychart.android/latest/
  integrations: []
  kind: commercial
  name: MyChart (Epic)
  page: /applications/telehealth-patient/mychart-epic/
  slug: mychart-epic
  url: https://www.mychart.org/
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
    name: Authorize.net
    provider: authorizenet
    says: ships the Authorize.net SDK or integration code
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
    name: Comlink telehealth
    provider: comlink
    says: ships the Comlink telehealth SDK or integration code
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
    name: DORN lab network
    provider: dorn
    says: ships the DORN lab network SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.20
      key: external-communications-management
      name: External Communications Management
      url: /capabilities/external-communications-management/
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
    name: Google (google/apiclient)
    provider: google
    says: ships the Google (google/apiclient) SDK or integration code
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
    layer: domain
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
  page: /applications/telehealth-patient/openemr/
  slug: openemr
  url: https://github.com/openemr/openemr
- anchor: medplum
  counts:
    declared: 14
    observed: 12
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
      id: AE-110.40
      key: AE-110.40
      name: Language & Document Understanding
      url: /capabilities/language-document-understanding/
      via_parent: null
    credit: null
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
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
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
  kind: open-source-saas
  name: Medplum
  page: /applications/telehealth-patient/medplum/
  slug: medplum
  url: https://github.com/medplum/medplum
- anchor: ottehr
  counts:
    declared: 0
    observed: 12
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
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
    tier: observed
  kind: open-source-saas
  name: Ottehr
  page: /applications/telehealth-patient/ottehr/
  slug: ottehr
  url: https://github.com/masslight/ottehr
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: telehealth-patient
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Medical
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Health & Fitness
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Medical
  store: google-play
  url: https://play.google.com/store/apps/category/MEDICAL
- category: Healthcare & Life Sciences
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
name: Telehealth & Patient Apps
needs:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: in-app product analytics SDKs in the patient apps
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep links [AE node AE-902 (Mobile Attribution & Deep Linking) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash reporting / APM
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: ad SDK present in the APK [AE node AE-903 (In-App Ad Monetisation) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: A/B testing SDKs
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: push/email lifecycle messaging to members
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: AE-150.40
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  fit: exact
  layer: common
  why: patient-clinician messaging / realtime [AE node AE-150.40 (In-App Chat) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app patient surveys
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  fit: exact
  layer: common
  why: GDPR consent management platform
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: copays and self-pay visits
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  fit: exact
  layer: domain
  why: insurance claims and clearinghouse submission
- capability:
    attribution: Turbo EA
    id: BC-850.20
    key: external-communications-management
    name: External Communications Management
    url: /capabilities/external-communications-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: clinical fax (no fax capability in BC or AE)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Google sign-in [AE node AE-160.10.30 (Social & Federated Login) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: hardware-key 2FA for clinicians [AE node AE-160.10.20 (Multi-Factor Authentication) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: the virtual visit itself; BC has no video-calling capability [AE node AE-150.60 (Video Calling) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  fit: exact
  layer: domain
  why: e-prescribing after a virtual visit
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  fit: exact
  layer: domain
  why: lab orders and results
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: appointment reminders and patient texting [AE node AE-150.20.10 (SMS) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: documents, images, attachments
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: system email to patients [AE node AE-150.10.10 (Transactional Email) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  fit: exact
  layer: agent
  why: medical NLP and OCR of clinical documents [AE node AE-110.40 (Language & Document Understanding) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: agent
  why: LLM features (charting assist, bots)
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: common
  why: server secrets for a PHI platform
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  fit: exact
  layer: common
  why: breached-password checks [AE node AE-160.60 (Credential Security) -- dotted AE ids fail the schema capability_ref pattern]
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: FHIR / EHR record exchange
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: patient and clinician sign-in
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: visit booking
- capability:
    attribution: Turbo EA
    id: BC-2830
    key: clinical-documentation-management
    name: Clinical Documentation Management
    url: /capabilities/clinical-documentation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: scanning paper documents into the chart
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2860.10
      key: laboratory-services-management
      name: Laboratory Services Management
      url: /capabilities/laboratory-services-management/
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
        status: unknown
      name: DORN lab network
      slug: dorn
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 74.5
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
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Medplum
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: none
      name: Labcorp
      slug: labcorp
      sources:
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
      - Medplum
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        status: none
      name: Quest Diagnostics
      slug: quest-diagnostics
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Diagnostics
      - Fortune 500
      - Healthcare
      - Laboratory
      tier: declared
      url: /providers/quest-diagnostics/
  - capability:
      attribution: Turbo EA
      id: BC-2870
      key: healthcare-revenue-cycle-management
      name: Healthcare Revenue Cycle Management
      url: /capabilities/healthcare-revenue-cycle-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Medplum
      - Ottehr
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        status: none
      name: Candid Health
      slug: candid-health
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Claims
      - Healthcare
      - Medical Billing
      - Revenue Cycle Management
      tier: observed
      url: /providers/candid-health/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - OpenEMR
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: none
      name: Claim.Revolution
      slug: claimrev
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/composer.json
      status: profiled
      tags:
      - Billing
      - Claims
      - Company
      - Healthcare
      tier: observed
      url: /providers/claimrev/
  - capability:
      attribution: Turbo EA
      id: BC-2850
      key: pharmacy-medication-management
      name: Pharmacy & Medication Management
      url: /capabilities/pharmacy-medication-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMR
      band: minimal
      in_catalog: true
      kin_score: 10.0
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
      agent_readiness: 30.7
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 59.9
      mcp:
        status: none
      name: DoseSpot
      slug: dosespot
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Electronic Health Records
      - Healthcare
      - e-Prescribing
      - eRx
      tier: declared
      url: /providers/dosespot/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Medplum
      band: minimal
      in_catalog: true
      kin_score: 1.3
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
      id: BC-850.20
      key: external-communications-management
      name: External Communications Management
      url: /capabilities/external-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - OpenEMR
      band: strong
      in_catalog: true
      kin_score: 61.5
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
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - OpenEMR
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        status: none
      name: etherFAX
      slug: etherfax
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Fax
      - Secure
      tier: observed
      url: /providers/etherfax/
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Ottehr
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Oystehr
      slug: oystehr
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      status: profiled
      tags:
      - Company
      - Developer-First
      - Electronic Health Records
      - Health Tech
      tier: observed
      url: /providers/oystehr/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 61.4
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
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.9
      apps:
      - Medplum
      band: thin
      in_catalog: true
      kin_score: 38.2
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
      agent_readiness: 24.5
      apps:
      - Medplum
      band: thin
      in_catalog: true
      kin_score: 31.4
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
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - Ottehr
      band: emerging
      in_catalog: true
      kin_score: 22.4
      mcp:
        status: none
      name: Amazon Chime SDK
      slug: amazon-chime
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/apps/ehr/package.json
      status: profiled
      tags:
      - Communications
      - Messaging
      - SDK
      - Video
      tier: observed
      url: /providers/amazon-chime/
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenEMR
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: none
      name: Comlink telehealth
      slug: comlink
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2830
      key: clinical-documentation-management
      name: Clinical Documentation Management
      url: /capabilities/clinical-documentation-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Ottehr
      band: emerging
      in_catalog: true
      kin_score: 21.2
      mcp:
        source: https://www.dynamsoft.com/codepool/mcp-server-dynamsoft-sdk-integration.html
        status: documented
      name: Dynamsoft Web TWAIN
      slug: dynamsoft
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/apps/ehr/package.json
      status: profiled
      tags:
      - Barcodes
      - Company
      - Document-Capture
      - SDK
      tier: observed
      url: /providers/dynamsoft/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Doctor On Demand (Included Health)
      - MDLIVE
      - Teladoc
      - Zocdoc
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mdlive.mobile/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Doctor On Demand (Included Health)
      - Teladoc
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Teladoc
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-ready
      agent_readiness: 48.3
      apps:
      - Teladoc
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Medplum
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        status: none
      name: Amazon CloudFront
      slug: cloudfront
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      - https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - CDN
      - Caching
      - Content Delivery
      tier: observed
      url: /providers/cloudfront/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Medplum
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
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
      agent_readiness: 45.3
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 71.7
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
      agent_readiness: 40.9
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 68.5
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
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Doctor On Demand (Included Health)
      - Teladoc
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Teladoc
      - Zocdoc
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Doctolib
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Doctolib
      - Ottehr
      - Zocdoc
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Teladoc
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: null
      agent_readiness: null
      apps:
      - Teladoc
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        source: https://github.com/bugfender/bugfender-mcp
        status: verified
      name: Bugfender
      slug: bugfender
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.teladoc.members/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Medplum
      - OpenEMR
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/packages/zambdas/package.json
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
      agent_readiness: 25.9
      apps:
      - OpenEMR
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.net
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
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - Medplum
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp: &id001
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      - https://www.medplum.com/docs/integration
      status: profiled
      tags: &id002
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 77.2
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
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - OpenEMR
      band: thin
      in_catalog: true
      kin_score: 33.2
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
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 70.3
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
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Medplum
      band: developing
      in_catalog: true
      kin_score: 53.6
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
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Medplum
      band: developing
      in_catalog: true
      kin_score: 53.3
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
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Doctor On Demand (Included Health)
      - Zocdoc
      band: exemplar
      in_catalog: true
      kin_score: 80.5
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - MDLIVE
      band: exemplar
      in_catalog: true
      kin_score: 75.2
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mdlive.mobile/latest/
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: observed
      url: /providers/braze/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Medplum
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: observed
      url: /providers/auth0/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 78.0
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
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp: *id001
      name: Twilio
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Doctor On Demand (Included Health)
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 80.6
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
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Medplum
      band: developing
      in_catalog: true
      kin_score: 48.4
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
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.0
      apps:
      - Doctor On Demand (Included Health)
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.doctorondemand.android.patient/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Doctolib
      band: exemplar
      in_catalog: true
      kin_score: 81.3
      mcp:
        status: none
      name: Didomi
      slug: didomi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.doctolib.www/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - CCPA
      - CMP
      tier: observed
      url: /providers/didomi/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Zocdoc
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - OpenEMR
      band: strong
      in_catalog: true
      kin_score: 58.3
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
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Zocdoc
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zocdoc.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - OpenEMR
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google (google/apiclient)
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
  layer: common
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Ottehr
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/masslight/ottehr/develop/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 71.4
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
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 81.8
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
      agent_readiness: 33.5
      apps:
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 60.3
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
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Medplum
      band: developing
      in_catalog: true
      kin_score: 52.7
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
  layer: agent
summary:
  coverage_pct: 94.9
  declared_only: 10
  distinct_providers: 59
  in_catalog: 56
  mcp:
    documented: 3
    none: 31
    unchecked: 0
    verified: 23
  mcp_verified: 23
  mean_kin_score: 56.8
  observed: 49
  queued: 3
  reference_apps: 9
title: 'Telehealth & Patient Apps: application blueprint'
---
