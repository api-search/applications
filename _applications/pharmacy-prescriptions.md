---
access: understanding
agent_layer:
- app: Medplum
  finding: server depends on @modelcontextprotocol/sdk -- Medplum exposes its own MCP server over FHIR (incl. MedicationRequest)
  source: https://raw.githubusercontent.com/medplum/medplum/main/packages/server/package.json
  tier: observed
apps:
- anchor: openemr
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  - route: source code
    url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
  - route: source code
    url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
  - route: source code
    url: https://github.com/openemr/openemr/tree/master/src/Rx/Ensora
  - route: source code
    url: https://raw.githubusercontent.com/openemr/openemr/master/src/Rx/RxList.php
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
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: common
    name: etherFAX
    provider: etherfax
    says: ships the etherFAX SDK or integration code
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
    name: NewCrop eRx (Ensora)
    provider: newcrop
    says: ships the NewCrop eRx (Ensora) SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/src/Rx/Ensora
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
    name: NLM RxNav / RxNorm
    provider: national-library-of-medicine
    says: ships the NLM RxNav / RxNorm SDK or integration code
    source: https://raw.githubusercontent.com/openemr/openemr/master/src/Rx/RxList.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
      via_parent: null
    credit: null
    layer: common
    name: RingCentral
    provider: ringcentral
    says: ships the RingCentral SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
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
    name: Weno Exchange (eRx)
    provider: weno
    says: ships the Weno Exchange (eRx) SDK or integration code
    source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-weno
    tier: observed
  kind: self-hosted
  name: OpenEMR
  page: /applications/pharmacy-prescriptions/openemr/
  slug: openemr
  url: https://github.com/openemr/openemr
- anchor: medplum
  counts:
    declared: 6
    observed: 5
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
  kind: open-source-saas
  name: Medplum
  page: /applications/pharmacy-prescriptions/medplum/
  slug: medplum
  url: https://github.com/medplum/medplum
- anchor: medisafe
  counts:
    declared: 1
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
  - route: store listing
    url: https://apps.apple.com/us/app/medisafe-medication-management/id573916946
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.medisafe.android.client
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
    name: Amazon Web Services (Mobile Analytics / Amplify)
    provider: amazon-web-services
    says: ships the Amazon Web Services (Mobile Analytics / Amplify) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    name: AppNexus
    provider: appnexus
    says: ships the AppNexus SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Tech Lab (Open Measurement)
    provider: iab-tech-lab
    says: ships the IAB Tech Lab (Open Measurement) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-920
      key: AE-920
      name: Barcode, RFID & Mobile Data Capture
      url: /capabilities/storage-and-inventory-operations-management/
      via_parent: Storage and Inventory Operations Management
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Scandit
    provider: scandit
    says: ships the Scandit SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.20
      key: AE-130.20.20
      name: Personal Health Records
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Apple HealthKit
    provider: apple
    says: lists Apple HealthKit as an integration
    source: https://apps.apple.com/us/app/medisafe-medication-management/id573916946
    tier: declared
  kind: commercial
  name: Medisafe
  page: /applications/pharmacy-prescriptions/medisafe/
  slug: medisafe
  url: https://www.medisafe.com/
- anchor: goodrx
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
  - route: store listing
    url: https://apps.apple.com/us/app/goodrx-prescription-savings/id485357017
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.goodrx
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
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
    name: Braze
    provider: braze
    says: ships the Braze SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
    tier: observed
  kind: commercial
  name: GoodRx
  page: /applications/pharmacy-prescriptions/goodrx/
  slug: goodrx
  url: https://www.goodrx.com/
- anchor: cvs-health
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
  - route: store listing
    url: https://apps.apple.com/us/app/cvs-health/id395545555
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.cvs.launchers.cvs
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
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bazaarvoice
    provider: bazaarvoice
    says: ships the Bazaarvoice SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    name: Braze
    provider: braze
    says: ships the Braze SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    name: Tapstream
    provider: tapstream
    says: ships the Tapstream SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
    tier: observed
  kind: commercial
  name: CVS Health
  page: /applications/pharmacy-prescriptions/cvs-health/
  slug: cvs-health
  url: https://www.cvs.com/
- anchor: walgreens
  counts:
    declared: 1
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
  - route: store listing
    url: https://apps.apple.com/us/app/walgreens/id335364882
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.usablenet.mobile.walgreen
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
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.20
      key: AE-130.20.20
      name: Personal Health Records
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    credit: null
    layer: domain
    name: Apple Health app
    provider: apple
    says: lists Apple Health app as an integration
    source: https://apps.apple.com/us/app/walgreens/id335364882
    tier: declared
  kind: commercial
  name: Walgreens
  page: /applications/pharmacy-prescriptions/walgreens/
  slug: walgreens
  url: https://www.walgreens.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: pharmacy-prescriptions
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Medical
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Medical
  store: google-play
  url: https://play.google.com/store/apps/category/MEDICAL
- category: Health and Fitness
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#health-and-fitness
name: Pharmacy & Prescriptions
needs:
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the category is the prescription: sending eRx (incl. EPCS) to a pharmacy and tracking it'
- capability:
    attribution: API Evangelist extension
    id: AE-945
    key: AE-945
    name: Clinical & Drug Terminology Services
    url: /capabilities/medical-coding-management/
    via_parent: Medical Coding Management
  fit: exact
  layer: domain
  why: 'Clinical & Drug Terminology Services: NLM RxNav / RxNorm'
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  fit: exact
  layer: domain
  why: claims for prescribed services and benefits
- capability:
    attribution: Turbo EA
    id: BC-2800.30
    key: eligibility-benefits-verification
    name: Eligibility & Benefits Verification
    url: /capabilities/eligibility-benefits-verification/
    via_parent: null
  fit: exact
  layer: domain
  why: coverage check before fill / copay
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  fit: exact
  layer: domain
  why: lab orders and results that gate prescribing
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.20
    key: AE-130.20.20
    name: Personal Health Records
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  fit: exact
  layer: domain
  why: medication and vitals sync with Apple Health / EHR records
- capability:
    attribution: API Evangelist extension
    id: AE-150.110
    key: AE-150.110
    name: Cloud Fax
    url: /capabilities/cloud-fax/
    via_parent: null
  fit: exact
  layer: common
  why: 'Cloud Fax: RingCentral, etherFAX'
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: refill-ready and reminder texts
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: order/refill notifications
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: copays and cash-price purchases
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: documents and attachments; nearest, no generic object-storage capability
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad SDK in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution SDKs in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: ad measurement and ad SDKs in the mobile apps
- capability:
    attribution: API Evangelist extension
    id: AE-920
    key: AE-920
    name: Barcode, RFID & Mobile Data Capture
    url: /capabilities/storage-and-inventory-operations-management/
    via_parent: Storage and Inventory Operations Management
  fit: exact
  layer: common
  why: barcode scanning SDK seen in an Android build
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: A/B testing in the mobile app
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: on-site popups that capture sign-ups for the loyalty program
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: common
  why: product reviews on storefront
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: marketing tags on storefronts
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
      - Medplum
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        status: none
      name: DoseSpot
      slug: dosespot
      sources:
      - https://github.com/medplum/medplum/tree/main/packages
      status: profiled
      tags:
      - Electronic Health Records
      - Healthcare
      - e-Prescribing
      - eRx
      tier: observed
      url: /providers/dosespot/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMR
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: Weno Exchange (eRx)
      slug: weno
      sources:
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-weno
      status: profiled
      tags:
      - Company
      - Healthcare
      - Pharmacy
      - e-Prescribing
      tier: observed
      url: /providers/weno/
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
      - https://github.com/medplum/medplum/tree/main/packages
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/scriptsure/
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenEMR
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: NewCrop eRx (Ensora)
      slug: newcrop
      sources:
      - https://github.com/openemr/openemr/tree/master/src/Rx/Ensora
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20.20
      key: AE-130.20.20
      name: Personal Health Records
      url: /capabilities/wearable-health-data-sync/
      via_parent: Wearable & Health Data Sync
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Medisafe
      - Walgreens
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple HealthKit
      slug: apple
      sources:
      - https://apps.apple.com/us/app/medisafe-medication-management/id573916946
      - https://apps.apple.com/us/app/walgreens/id335364882
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
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
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
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
      status: profiled
      tags:
      - Billing
      - Claims
      - Company
      - Healthcare
      tier: observed
      url: /providers/claimrev/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Candid Health
      slug: candid-health
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Claims
      - Healthcare
      - Medical Billing
      - Revenue Cycle Management
      tier: declared
      url: /providers/candid-health/
  - capability:
      attribution: API Evangelist extension
      id: AE-945
      key: AE-945
      name: Clinical & Drug Terminology Services
      url: /capabilities/medical-coding-management/
      via_parent: Medical Coding Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - OpenEMR
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: unknown
      name: NLM RxNav / RxNorm
      slug: national-library-of-medicine
      sources:
      - https://raw.githubusercontent.com/openemr/openemr/master/src/Rx/RxList.php
      status: profiled
      tags:
      - Federal Government
      - Health
      - Library
      - Medicine
      tier: observed
      url: /providers/national-library-of-medicine/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - GoodRx
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
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
      attribution: Turbo EA
      id: BC-2860.10
      key: laboratory-services-management
      name: Laboratory Services Management
      url: /capabilities/laboratory-services-management/
      via_parent: null
    providers:
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
      - https://github.com/medplum/medplum/tree/main/packages
      status: profiled
      tags:
      - Clinical Data
      - FHIR
      - Health
      - Interoperability
      tier: observed
      url: /providers/health-gorilla/
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
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - CVS Health
      - GoodRx
      - Medisafe
      - Walgreens
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - CVS Health
      - Walgreens
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Walgreens
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Medisafe
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services (Mobile Analytics / Amplify)
      slug: amazon-web-services
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - GoodRx
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - CVS Health
      - GoodRx
      - Medisafe
      - Walgreens
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - GoodRx
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: null
      agent_readiness: null
      apps:
      - CVS Health
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Tapstream
      slug: tapstream
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - CVS Health
      - GoodRx
      - Walgreens
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-aware
      agent_readiness: 8.4
      apps:
      - Medisafe
      band: thin
      in_catalog: true
      kin_score: 38.5
      mcp:
        status: unchecked
      name: AppNexus
      slug: appnexus
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Programmatic
      tier: observed
      url: /providers/appnexus/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Medisafe
      - Walgreens
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Medisafe
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - CVS Health
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
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
      id: AE-150.110
      key: AE-150.110
      name: Cloud Fax
      url: /capabilities/cloud-fax/
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
      - https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
      status: profiled
      tags:
      - Communications
      - UCaaS
      - Video
      - Voice
      tier: observed
      url: /providers/ringcentral/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
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
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - CVS Health
      - GoodRx
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: observed
      url: /providers/braze/
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
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Medplum
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://www.medplum.com/docs/integration
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: declared
      url: /providers/sendgrid/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
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
  - capability:
      attribution: API Evangelist extension
      id: AE-920
      key: AE-920
      name: Barcode, RFID & Mobile Data Capture
      url: /capabilities/storage-and-inventory-operations-management/
      via_parent: Storage and Inventory Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 7.0
      apps:
      - Medisafe
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        source: https://ssl.scandit.com/mcp
        status: verified
      name: Scandit
      slug: scandit
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags:
      - Barcode Scanning
      - Company
      - Data Capture
      - Frontier Tech
      tier: observed
      url: /providers/scandit/
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.6
      apps:
      - GoodRx
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodrx/latest/
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Medisafe
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Tech Lab (Open Measurement)
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.medisafe.android.client/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - CVS Health
      band: exemplar
      in_catalog: true
      kin_score: 67.4
      mcp:
        status: none
      name: Bazaarvoice
      slug: bazaarvoice
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
      status: profiled
      tags:
      - BazaarVoice
      - Company
      - Ratings
      - Reviews
      tier: observed
      url: /providers/bazaarvoice/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Walgreens
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.usablenet.mobile.walgreen/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  layer: common
summary:
  coverage_pct: 95.0
  declared_only: 5
  distinct_providers: 40
  in_catalog: 38
  mcp:
    documented: 2
    none: 18
    unchecked: 3
    verified: 15
  mcp_verified: 15
  mean_kin_score: 59.8
  observed: 35
  queued: 2
  reference_apps: 6
title: 'Pharmacy & Prescriptions: application blueprint'
---
