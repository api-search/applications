---
access: understanding
agent_layer: []
apps:
- anchor: frappe-hr
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/frappe/hrms/develop/frontend/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/frappe/hrms/develop/pyproject.toml
  - route: source code
    url: https://raw.githubusercontent.com/frappe/hrms/develop/frontend/public/frappe-push-notification.js
  - route: source code
    url: https://raw.githubusercontent.com/frappe/hrms/develop/hrms/hooks.py
  - route: source code
    url: https://raw.githubusercontent.com/frappe/hrms/develop/hrms/telemetry.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://raw.githubusercontent.com/frappe/hrms/develop/frontend/public/frappe-push-notification.js
    tier: observed
  kind: self-hosted
  name: Frappe HR
  page: /applications/payroll-hr/frappe-hr/
  slug: frappe-hr
  url: https://github.com/frappe/hrms
- anchor: horilla
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/horilla/horilla-hr/master/requirements.txt
  - route: source code
    url: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/horilla_meet/views.py
  - route: source code
    url: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/outlook_auth/models.py
  - route: source code
    url: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/whatsapp/utils.py
  - route: source code
    url: https://raw.githubusercontent.com/horilla/horilla-hr/master/horilla/horilla_settings.py
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/master/horilla/horilla_settings.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/horilla_meet/views.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/master/requirements.txt
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
    name: Google Meet
    provider: google-meet
    says: ships the Google Meet SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/horilla_meet/views.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID sign-in
    provider: microsoft-entra
    says: ships the Microsoft Entra ID sign-in SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/master/requirements.txt
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
    name: Microsoft Graph (Outlook mail)
    provider: microsoft-graph
    says: ships the Microsoft Graph (Outlook mail) SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/outlook_auth/models.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: WhatsApp Cloud API
    provider: whatsapp
    says: ships the WhatsApp Cloud API SDK or integration code
    source: https://raw.githubusercontent.com/horilla/horilla-hr/2.0/whatsapp/utils.py
    tier: observed
  kind: self-hosted
  name: Horilla
  page: /applications/payroll-hr/horilla/
  slug: horilla
  url: https://github.com/horilla/horilla-hr
- anchor: orangehrm
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/orangehrm/orangehrm/main/src/composer.json
  - route: source code
    url: https://github.com/orangehrm/orangehrm/tree/main/src/plugins
  integrations: []
  kind: self-hosted
  name: OrangeHRM
  page: /applications/payroll-hr/orangehrm/
  slug: orangehrm
  url: https://github.com/orangehrm/orangehrm
- anchor: deel
  counts:
    declared: 32
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
  - route: integrations page
    url: https://www.deel.com/integrations/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ashby
    provider: ashby
    says: lists Ashby as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: BambooHR
    provider: bamboohr
    says: lists BambooHR as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: common
    name: CrowdStrike
    provider: crowdstrike
    says: lists CrowdStrike as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: DATEV
    provider: datev
    says: lists DATEV as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.30
      key: compensation-benefits-management
      name: Compensation & Benefits Management
      url: /capabilities/compensation-benefits-management/
      via_parent: null
    credit: null
    layer: domain
    name: Employee Navigator
    provider: employeenavigator
    says: lists Employee Navigator as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Fizard
    provider: fizard
    says: lists Fizard as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: FloCareer
    provider: flocareer
    says: lists FloCareer as an integration
    source: https://www.deel.com/integrations/
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
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenhouse
    provider: greenhouse
    says: lists Greenhouse as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: lists HiBob as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Hofy
    provider: hofy
    says: lists Hofy as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Hubstaff
    provider: hubstaff
    says: lists Hubstaff as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.30
      key: compensation-benefits-management
      name: Compensation & Benefits Management
      url: /capabilities/compensation-benefits-management/
      via_parent: null
    credit: null
    layer: domain
    name: Human Interest
    provider: human-interest
    says: lists Human Interest as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    credit: null
    layer: domain
    name: JobzMall
    provider: jobzmall
    says: lists JobzMall as an integration
    source: https://www.deel.com/integrations/
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
    name: JumpCloud
    provider: jumpcloud
    says: lists JumpCloud as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    credit: null
    layer: common
    name: Moss (getmoss.com)
    provider: getmoss
    says: lists Moss (getmoss.com) as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: NetSuite
    provider: netsuite
    says: lists NetSuite as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4320
      key: professional-workforce-resourcing-management
      name: Professional Workforce Resourcing Management
      url: /capabilities/professional-workforce-resourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pangea (contract-to-hire)
    provider: pangea-io
    says: lists Pangea (contract-to-hire) as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.30
      key: compensation-benefits-management
      name: Compensation & Benefits Management
      url: /capabilities/compensation-benefits-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pave
    provider: pave
    says: lists Pave as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Personio
    provider: personio
    says: lists Personio as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4320
      key: professional-workforce-resourcing-management
      name: Professional Workforce Resourcing Management
      url: /capabilities/professional-workforce-resourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pro5
    provider: pro5
    says: lists Pro5 as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Puzzle Financial
    provider: puzzle
    says: lists Puzzle Financial as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Sage
    provider: sage
    says: lists Sage as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP SuccessFactors
    provider: sap-successfactors
    says: lists SAP SuccessFactors as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.60
      key: employee-experience-management
      name: Employee Experience Management
      url: /capabilities/employee-experience-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snappy Gifts
    provider: snappy
    says: lists Snappy Gifts as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    credit: null
    layer: common
    name: Spendesk
    provider: spendesk
    says: lists Spendesk as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Time Doctor
    provider: time-doctor
    says: lists Time Doctor as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4320
      key: professional-workforce-resourcing-management
      name: Professional Workforce Resourcing Management
      url: /capabilities/professional-workforce-resourcing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webstarted
    provider: webstarted
    says: lists Webstarted as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.deel.com/integrations/
    tier: declared
  kind: commercial
  name: Deel
  page: /applications/payroll-hr/deel/
  slug: deel
  url: https://www.deel.com/
- anchor: adp-mobile-solutions
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Split (Harness FME)
    provider: split
    says: ships the Split (Harness FME) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
    tier: observed
  kind: commercial
  name: ADP Mobile Solutions
  page: /applications/payroll-hr/adp-mobile-solutions/
  slug: adp-mobile-solutions
  url: https://www.adp.com/
- anchor: paylocity
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: GIPHY
    provider: giphy
    says: ships the GIPHY SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
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
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
    tier: observed
  kind: commercial
  name: Paylocity
  page: /applications/payroll-hr/paylocity/
  slug: paylocity
  url: https://www.paylocity.com/
- anchor: workday
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.60
      key: employee-experience-management
      name: Employee Experience Management
      url: /capabilities/employee-experience-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
    tier: observed
  kind: commercial
  name: Workday
  page: /applications/payroll-hr/workday/
  slug: workday
  url: https://www.workday.com/
- anchor: homebase
  counts:
    declared: 16
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
  - route: integrations page
    url: https://www.joinhomebase.com/integrations
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP
    provider: adp
    says: lists ADP as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1330.10
      key: deposit-account-management
      name: Deposit Account Management
      url: /capabilities/deposit-account-management/
      via_parent: null
    credit: null
    layer: common
    name: Bank of America
    provider: bank-of-america
    says: lists Bank of America as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clover
    provider: clover
    says: lists Clover as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: GoDaddy (POS)
    provider: godaddy
    says: lists GoDaddy (POS) as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Heartland
    provider: heartland-payment-systems
    says: lists Heartland as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lightspeed
    provider: lightspeed
    says: lists Lightspeed as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Millennium Payroll Services
    provider: millennium-payroll-services
    says: lists Millennium Payroll Services as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: PAR
    provider: par-technology
    says: lists PAR as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paychex
    provider: paychex-developer
    says: lists Paychex as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks (Payroll)
    provider: quickbooks
    says: lists QuickBooks (Payroll) as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shopify POS
    provider: shopify
    says: lists Shopify POS as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square (POS + Square Payroll)
    provider: square
    says: lists Square (POS + Square Payroll) as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: SurePayroll
    provider: surepayroll
    says: lists SurePayroll as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Toast
    provider: toast
    says: lists Toast as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1330.10
      key: deposit-account-management
      name: Deposit Account Management
      url: /capabilities/deposit-account-management/
      via_parent: null
    credit: null
    layer: common
    name: Wells Fargo
    provider: wells-fargo
    says: lists Wells Fargo as an integration
    source: https://www.joinhomebase.com/integrations
    tier: declared
  kind: commercial
  name: Homebase
  page: /applications/payroll-hr/homebase/
  slug: homebase
  url: https://www.joinhomebase.com/
- anchor: connecteam
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
  integrations:
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
    tier: observed
  kind: commercial
  name: Connecteam
  page: /applications/payroll-hr/connecteam/
  slug: connecteam
  url: https://connecteam.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: payroll-hr
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Human Resources Management (HRM)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#human-resources-management-hrm
- category: Human Resources
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: HR & Team Culture
  store: slack-marketplace
  url: https://slack.com/apps
- category: HR Talent & Recruitment
  store: zapier
  url: https://zapier.com/apps
name: HR, Payroll & People Ops
needs:
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'payroll administration and HR service delivery: the category itself'
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: domain
  why: HRIS / employee record systems Deel syncs with
- capability:
    attribution: Turbo EA
    id: BC-300.30
    key: compensation-benefits-management
    name: Compensation & Benefits Management
    url: /capabilities/compensation-benefits-management/
    via_parent: null
  fit: exact
  layer: domain
  why: benefits admin, 401(k), comp benchmarking
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ATS integrations (Ashby, Greenhouse)
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  fit: exact
  layer: domain
  why: time tracking feeding payroll
- capability:
    attribution: Turbo EA
    id: BC-4320
    key: professional-workforce-resourcing-management
    name: Professional Workforce Resourcing Management
    url: /capabilities/professional-workforce-resourcing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: contract-to-hire / staffing partners
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: hourly-workforce apps (Homebase) pull shifts and sales from the POS
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: interview scheduling against a calendar
- capability:
    attribution: Turbo EA
    id: BC-300.60
    key: employee-experience-management
    name: Employee Experience Management
    url: /capabilities/employee-experience-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: surveys, gifting
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: payroll journal sync to accounting
- capability:
    attribution: Turbo EA
    id: BC-200.20
    key: accounts-payable-management
    name: Accounts Payable Management
    url: /capabilities/accounts-payable-management/
    via_parent: null
  fit: nearest
  layer: common
  why: spend management partners
- capability:
    attribution: Turbo EA
    id: BC-1330.10
    key: deposit-account-management
    name: Deposit Account Management
    url: /capabilities/deposit-account-management/
    via_parent: null
  fit: nearest
  layer: common
  why: banks on the Homebase integrations page
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: provisioning of new hires
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: SSO for employees
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: nearest
  layer: common
  why: endpoint security for onboarded devices
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: Slack
- capability:
    attribution: API Evangelist extension
    id: AE-150
    key: AE-150
    name: Application Communications
    url: /capabilities/application-communications/
    via_parent: null
  fit: exact
  layer: common
  why: push, WhatsApp, transactional mail and video calls (AE extension draft; leaves AE-150.10.10/.20.20/.30/.60 fail the schema id pattern)
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: AppsFlyer in Homebase (AE extension draft)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: document storage (S3 / GCS)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: mobile app analytics trackers
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash / error reporting
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: Split in ADP
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: GIPHY in Paylocity
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: IAB Open Measurement in Paylocity
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Homebase
      band: exemplar
      in_catalog: true
      kin_score: 86.5
      mcp:
        status: none
      name: Lightspeed
      slug: lightspeed
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Commerce
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/lightspeed/
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - Homebase
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify POS
      slug: shopify
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - Homebase
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square (POS + Square Payroll)
      slug: square
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - Homebase
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: Toast
      slug: toast
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Food Service
      - Hospitality
      - Point-of-Sale
      - Restaurant
      tier: declared
      url: /providers/toast/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Homebase
      band: developing
      in_catalog: true
      kin_score: 39.9
      mcp:
        status: none
      name: Clover
      slug: clover
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Payments
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/clover/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Homebase
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: PAR
      slug: par-technology
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Company
      - Hospitality
      - Loyalty
      - Point-of-Sale
      tier: declared
      url: /providers/par-technology/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Homebase
      band: thin
      in_catalog: true
      kin_score: 31.7
      mcp:
        source: https://developer.godaddy.com/mcp
        status: verified
      name: GoDaddy (POS)
      slug: godaddy
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Aftermarket
      - Certificates
      - DNS
      - Domains
      tier: declared
      url: /providers/godaddy/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Homebase
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        source: https://github.com/globalpayments/mcp-server
        status: verified
      name: Heartland
      slug: heartland-payment-systems
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Bill Pay
      - Card Not Present
      - Card Present
      - E-Commerce
      tier: declared
      url: /providers/heartland-payment-systems/
  - capability:
      attribution: Turbo EA
      id: BC-300.70
      key: hr-operations-management
      name: HR Operations Management
      url: /capabilities/hr-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Homebase
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp: &id001
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks (Payroll)
      slug: quickbooks
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags: &id002
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Homebase
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: ADP
      slug: adp
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/adp/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Homebase
      band: developing
      in_catalog: true
      kin_score: 42.0
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Homebase
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        status: none
      name: Paychex
      slug: paychex-developer
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Paychex Flex
      tier: declared
      url: /providers/paychex-developer/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Homebase
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: SurePayroll
      slug: surepayroll
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Human Resources
      - Paychex
      - Payroll
      - Small Business
      tier: declared
      url: /providers/surepayroll/
    - agent_band: null
      agent_readiness: null
      apps:
      - Deel
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Hofy
      slug: hofy
      sources:
      - https://www.deel.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Homebase
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Millennium Payroll Services
      slug: millennium-payroll-services
      sources:
      - https://www.joinhomebase.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Deel
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: Workday
      slug: workday
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: declared
      url: /providers/workday/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Deel
      band: developing
      in_catalog: true
      kin_score: 40.9
      mcp:
        source: https://documentation.bamboohr.com/docs/mcp-server
        status: verified
      name: BambooHR
      slug: bamboohr
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Payroll
      - Time Tracking
      tier: declared
      url: /providers/bamboohr/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Deel
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        status: none
      name: Personio
      slug: personio
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Applicant Tracking
      - HRIS
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/personio/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Deel
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        source: https://apidocs.hibob.com/docs/hibob-mcp-server
        status: verified
      name: HiBob
      slug: bob
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Employee Management
      - HRIS
      - Human Resources
      - Time Off
      tier: declared
      url: /providers/bob/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: SAP SuccessFactors
      slug: sap-successfactors
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - HCM
      - Human Resources
      - Payroll
      - Talent Management
      tier: declared
      url: /providers/sap-successfactors/
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.8
      apps:
      - Deel
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        status: none
      name: Greenhouse
      slug: greenhouse
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Applicant Tracking
      - Greenhouse
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/greenhouse/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Deel
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        status: none
      name: Ashby
      slug: ashby
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Applicant Tracking
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/ashby/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 22.1
      mcp:
        status: none
      name: JobzMall
      slug: jobzmall
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Company
      - Marketplace
      - Talent
      - Video
      tier: declared
      url: /providers/jobzmall/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: unknown
      name: FloCareer
      slug: flocareer
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Hiring
      - Interview
      tier: declared
      url: /providers/flocareer/
  - capability:
      attribution: Turbo EA
      id: BC-300.30
      key: compensation-benefits-management
      name: Compensation & Benefits Management
      url: /capabilities/compensation-benefits-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Deel
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        status: none
      name: Human Interest
      slug: human-interest
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - 401k
      - Company
      - Fintech
      - Retirement
      tier: declared
      url: /providers/human-interest/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: none
      name: Employee Navigator
      slug: employeenavigator
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Benefits Administration
      - Company
      - Human Resources
      - Insurance
      tier: declared
      url: /providers/employeenavigator/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 17.5
      mcp:
        status: none
      name: Pave
      slug: pave
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Company
      - Compensation
      - Compensation Benchmarking
      - Human Resources
      tier: declared
      url: /providers/pave/
  - capability:
      attribution: Turbo EA
      id: BC-4320
      key: professional-workforce-resourcing-management
      name: Professional Workforce Resourcing Management
      url: /capabilities/professional-workforce-resourcing-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: unknown
      name: Pangea (contract-to-hire)
      slug: pangea-io
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Company
      - FX Hedging
      - Finance
      - Risk Management
      tier: declared
      url: /providers/pangea-io/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Deel
      band: minimal
      in_catalog: true
      kin_score: 8.6
      mcp:
        status: none
      name: Webstarted
      slug: webstarted
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Latin America
      - Nearshore
      - Recruiting
      - Staff Augmentation
      tier: declared
      url: /providers/webstarted/
    - agent_band: null
      agent_readiness: null
      apps:
      - Deel
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Pro5
      slug: pro5
      sources:
      - https://www.deel.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Deel
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: Hubstaff
      slug: hubstaff
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Productivity
      - Time Tracking
      - Timesheets
      - Workforce Management
      tier: declared
      url: /providers/hubstaff/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 22.4
      mcp:
        source: https://www.timedoctor.com/mcp
        status: verified
      name: Time Doctor
      slug: time-doctor
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Company
      - Productivity
      - Time Tracking
      - Workforce Management
      tier: declared
      url: /providers/time-doctor/
  - capability:
      attribution: Turbo EA
      id: BC-300.60
      key: employee-experience-management
      name: Employee Experience Management
      url: /capabilities/employee-experience-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        status: none
      name: Snappy Gifts
      slug: snappy
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Company
      - Corporate Gifting
      - Employee Recognition
      - Human Resources
      tier: declared
      url: /providers/snappy/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Horilla
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/2.0/horilla_meet/views.py
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - Horilla
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: none
      name: Google Meet
      slug: google-meet
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/2.0/horilla_meet/views.py
      status: profiled
      tags:
      - Google
      - Google Workspace
      - Meetings
      - Recording
      tier: observed
      url: /providers/google-meet/
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
      - ADP Mobile Solutions
      - Connecteam
      - Deel
      - Homebase
      - Paylocity
      - Workday
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics / Analytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
      status: profiled
      tags: &id004
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Deel
      - Homebase
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - ADP Mobile Solutions
      - Paylocity
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - ADP Mobile Solutions
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.3
      apps:
      - Deel
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Deel
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp: *id001
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Deel
      band: developing
      in_catalog: true
      kin_score: 47.6
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=io.puzzle/puzzle
        status: verified
      name: Puzzle Financial
      slug: puzzle
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Company
      - Finance
      tier: declared
      url: /providers/puzzle/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Deel
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp:
        status: none
      name: Sage
      slug: sage
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Cloud Software
      - ERP
      tier: declared
      url: /providers/sage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: none
      name: NetSuite
      slug: netsuite
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
    - agent_band: agent-aware
      agent_readiness: 8.6
      apps:
      - Deel
      band: minimal
      in_catalog: true
      kin_score: 9.5
      mcp:
        status: unknown
      name: Fizard
      slug: fizard
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Automation
      - Integration
      - Payments
      tier: declared
      url: /providers/fizard/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Deel
      band: minimal
      in_catalog: true
      kin_score: 7.2
      mcp:
        status: none
      name: DATEV
      slug: datev
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Company
      - Software
      - Tax
      tier: declared
      url: /providers/datev/
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
      - Connecteam
      - Deel
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - Connecteam
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.connecteamco.Connecteam.app/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 48.9
      apps:
      - Deel
      band: strong
      in_catalog: true
      kin_score: 60.2
      mcp:
        status: none
      name: Spendesk
      slug: spendesk
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Corporate Cards
      - Expense Management
      - Invoices
      - Spend Management
      tier: declared
      url: /providers/spendesk/
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - Deel
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        source: https://www.getmoss.com
        status: documented
      name: Moss (getmoss.com)
      slug: getmoss
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Company
      - Finance
      tier: declared
      url: /providers/getmoss/
  - capability:
      attribution: Turbo EA
      id: BC-1330.10
      key: deposit-account-management
      name: Deposit Account Management
      url: /capabilities/deposit-account-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Homebase
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Wells Fargo
      slug: wells-fargo
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Banking
      - Consumer Banking
      - Fortune 100
      tier: declared
      url: /providers/wells-fargo/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Homebase
      band: thin
      in_catalog: true
      kin_score: 38.3
      mcp:
        status: none
      name: Bank of America
      slug: bank-of-america
      sources:
      - https://www.joinhomebase.com/integrations
      status: profiled
      tags:
      - Banking
      - Corporate Banking
      - Finance
      - Payments
      tier: declared
      url: /providers/bank-of-america/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Deel
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - Deel
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
        status: verified
      name: JumpCloud
      slug: jumpcloud
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Directory Services
      - Identity
      - MFA
      - SSO
      tier: declared
      url: /providers/jumpcloud/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Horilla
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/master/requirements.txt
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Horilla
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/master/horilla/horilla_settings.py
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
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Paylocity
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: observed
      url: /providers/giphy/
  - capability:
      attribution: Turbo EA
      id: BC-300.60
      key: employee-experience-management
      name: Employee Experience Management
      url: /capabilities/employee-experience-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.0
      apps:
      - Workday
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.workday.workdroidapp/latest/
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
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - ADP Mobile Solutions
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Split (Harness FME)
      slug: split
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Deel
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
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
      - Homebase
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Paylocity
      band: strong
      in_catalog: true
      kin_score: 56.1
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
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
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Frappe HR
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id003
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/frappe/hrms/develop/frontend/public/frappe-push-notification.js
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - ADP Mobile Solutions
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adpmobile.android/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Horilla
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft Entra ID sign-in
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/master/requirements.txt
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.1
      apps:
      - Deel
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://github.com/CrowdStrike/falcon-mcp
        status: verified
      name: CrowdStrike
      slug: crowdstrike
      sources:
      - https://www.deel.com/integrations/
      status: profiled
      tags:
      - Cybersecurity
      - Endpoint Detection and Response
      - Endpoint Security
      - Threat Intelligence
      tier: declared
      url: /providers/crowdstrike/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Horilla
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph (Outlook mail)
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/2.0/outlook_auth/models.py
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.0
      apps:
      - Horilla
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: WhatsApp Cloud API
      slug: whatsapp
      sources:
      - https://raw.githubusercontent.com/horilla/horilla-hr/2.0/whatsapp/utils.py
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
  layer: common
summary:
  coverage_pct: 95.5
  declared_only: 47
  distinct_providers: 66
  in_catalog: 63
  mcp:
    documented: 1
    none: 33
    unchecked: 3
    verified: 26
  mcp_verified: 26
  mean_kin_score: 46.8
  observed: 19
  queued: 3
  reference_apps: 9
title: 'HR, Payroll & People Ops: application blueprint'
---
