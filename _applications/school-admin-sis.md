---
access: understanding
agent_layer: []
apps:
- anchor: gibbon
  counts:
    declared: 4
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
  - route: source code
    url: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
  - route: source code
    url: https://github.com/GibbonEdu/core/tree/v31.0.00/src/Comms/Drivers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: mailbox-calendar-sync
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google APIs (google/apiclient)
    provider: google
    says: ships the Google APIs (google/apiclient) SDK or integration code
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: mailbox-calendar-sync
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    name: Microsoft sign-in
    provider: microsoft-entra
    says: ships the Microsoft sign-in SDK or integration code
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
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
    name: OneWaySMS
    provider: onewaysms
    says: ships the OneWaySMS SDK or integration code
    source: https://github.com/GibbonEdu/core/tree/v31.0.00/src/Comms/Drivers
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    name: Clockwork SMS
    provider: clockwork-sms
    says: lists Clockwork SMS as an integration
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
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
    name: Nexmo (Vonage)
    provider: vonage
    says: lists Nexmo (Vonage) as an integration
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
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
    name: Textlocal
    provider: textlocal
    says: lists Textlocal as an integration
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
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
    source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
    tier: declared
  kind: self-hosted
  name: Gibbon
  page: /applications/school-admin-sis/gibbon/
  slug: gibbon
  url: https://github.com/GibbonEdu/core
- anchor: rosariosis
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/francoisjacquet/rosariosis/blob/mobile/composer.json
  - route: integrations page
    url: https://www.rosariosis.org/add-ons/
  - route: source code
    url: https://github.com/francoisjacquet/rosariosis/tree/mobile/plugins
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Moodle
    provider: moodle
    says: ships the Moodle SDK or integration code
    source: https://github.com/francoisjacquet/rosariosis/tree/mobile/plugins
    tier: observed
  kind: self-hosted
  name: RosarioSIS
  page: /applications/school-admin-sis/rosariosis/
  slug: rosariosis
  url: https://github.com/francoisjacquet/rosariosis
- anchor: frappe-education
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: source code
    url: https://github.com/frappe/education/blob/develop/education/education/billing.py
  - route: source code
    url: https://github.com/frappe/education/blob/develop/education/education/doctype/education_settings/education_settings.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: ERPNext
    provider: erpnext
    says: ships the ERPNext SDK or integration code
    source: https://github.com/frappe/education/blob/develop/education/education/billing.py
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
    name: Razorpay
    provider: razorpay
    says: ships the Razorpay SDK or integration code
    source: https://github.com/frappe/education/blob/develop/education/education/billing.py
    tier: observed
  kind: self-hosted
  name: Frappe Education
  page: /applications/school-admin-sis/frappe-education/
  slug: frappe-education
  url: https://github.com/frappe/education
- anchor: gradelink
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.gradelink.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-944
      key: AE-944
      name: K-12 Rostering & Roster Sync
      url: /capabilities/k-12-rostering-roster-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Apple School Manager
    provider: apple
    says: lists Apple School Manager as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Canvas LMS
    provider: canvas
    says: lists Canvas LMS as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-944
      key: AE-944
      name: K-12 Rostering & Roster Sync
      url: /capabilities/k-12-rostering-roster-sync/
      via_parent: null
    credit: null
    layer: domain
    name: ClassLink
    provider: classlink
    says: lists ClassLink as an integration
    source: https://www.gradelink.com/integrations/
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
    name: ClassWallet
    provider: classwallet
    says: lists ClassWallet as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-944
      key: AE-944
      name: K-12 Rostering & Roster Sync
      url: /capabilities/k-12-rostering-roster-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Clever
    provider: clever
    says: lists Clever as an integration
    source: https://www.gradelink.com/integrations/
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
    name: FACTS Tuition Management
    provider: facts-management
    says: lists FACTS Tuition Management as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Classroom
    provider: google-classroom
    says: lists Google Classroom as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-944
      key: AE-944
      name: K-12 Rostering & Roster Sync
      url: /capabilities/k-12-rostering-roster-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft 365 (School Data Sync)
    provider: microsoft-365
    says: lists Microsoft 365 (School Data Sync) as an integration
    source: https://www.gradelink.com/integrations/
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
    name: PaySimple
    provider: paysimple
    says: lists PaySimple as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730
      key: teaching-learning-operations-management
      name: Teaching & Learning Operations Management
      url: /capabilities/teaching-learning-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Renaissance (RDI)
    provider: renaissance
    says: lists Renaissance (RDI) as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Schoology
    provider: schoology
    says: lists Schoology as an integration
    source: https://www.gradelink.com/integrations/
    tier: declared
  kind: commercial
  name: Gradelink
  page: /applications/school-admin-sis/gradelink/
  slug: gradelink
  url: https://www.gradelink.com/
- anchor: classe365
  counts:
    declared: 32
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.classe365.com/integrations/
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
    says: lists Authorize.net as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Blackboard
    provider: blackboard
    says: lists Blackboard as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Brightspace
    provider: brightspace
    says: lists Brightspace as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Canvas LMS
    provider: canvas
    says: lists Canvas LMS as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-944
      key: AE-944
      name: K-12 Rostering & Roster Sync
      url: /capabilities/k-12-rostering-roster-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Clever
    provider: clever
    says: lists Clever as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3780.50
      key: BC-3780.50
      name: Accessibility Compliance Management
      url: /capabilities/content-compliance-standards-management/
      via_parent: Content Compliance & Standards Management
    credit: null
    layer: common
    name: EqualWeb
    provider: equalweb
    says: lists EqualWeb as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Classroom
    provider: google-classroom
    says: lists Google Classroom as an integration
    source: https://www.classe365.com/integrations/
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
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    credit: null
    layer: common
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://www.classe365.com/integrations/
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
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: video-calling
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Moodle
    provider: moodle
    says: lists Moodle as an integration
    source: https://www.classe365.com/integrations/
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
    name: MYOB
    provider: myob
    says: lists MYOB as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: OneDrive
    provider: microsoft-onedrive
    says: lists OneDrive as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    credit: null
    layer: common
    name: PandaDoc
    provider: pandadoc
    says: lists PandaDoc as an integration
    source: https://www.classe365.com/integrations/
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    credit: null
    layer: common
    name: Power Automate
    provider: microsoft-power-automate
    says: lists Power Automate as an integration
    source: https://www.classe365.com/integrations/
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
    name: Power BI
    provider: power-bi
    says: lists Power BI as an integration
    source: https://www.classe365.com/integrations/
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
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: SharePoint
    provider: sharepoint
    says: lists SharePoint as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4740.20.30
      key: BC-4740.20.30
      name: Online & Remote Proctoring
      url: /capabilities/examination-operations/
      via_parent: Examination Operations
    credit: null
    layer: domain
    name: SMOWL
    provider: smowl
    says: lists SMOWL as an integration
    source: https://www.classe365.com/integrations/
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
    source: https://www.classe365.com/integrations/
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
    name: Twilio SMS
    provider: twilio
    says: lists Twilio SMS as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://www.classe365.com/integrations/
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
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: video-calling
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.classe365.com/integrations/
    tier: declared
  kind: commercial
  name: Classe365
  page: /applications/school-admin-sis/classe365/
  slug: classe365
  url: https://www.classe365.com/
- anchor: alma
  counts:
    declared: 1
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.getalma.com/solutions/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Classroom
    provider: google-classroom
    says: lists Google Classroom as an integration
    source: https://www.getalma.com/solutions/
    tier: declared
  kind: commercial
  name: Alma
  page: /applications/school-admin-sis/alma/
  slug: alma
  url: https://www.getalma.com/
- anchor: veracross
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.veracross.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4710
      key: student-recruitment-admissions-management
      name: Student Recruitment & Admissions Management
      url: /capabilities/student-recruitment-admissions-management/
      via_parent: null
    credit: null
    layer: domain
    name: Digistorm Websites
    provider: digistorm
    says: lists Digistorm Websites as an integration
    source: https://www.veracross.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: Double the Donation
    provider: double-the-donation
    says: lists Double the Donation as an integration
    source: https://www.veracross.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4770
      key: student-support-wellbeing-management
      name: Student Support & Wellbeing Management
      url: /capabilities/student-support-wellbeing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Epraise
    provider: epraise
    says: lists Epraise as an integration
    source: https://www.veracross.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Firefly
    provider: firefly-learning
    says: lists Firefly as an integration
    source: https://www.veracross.com/integrations
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
    name: Intellischool
    provider: intellischool
    says: lists Intellischool as an integration
    source: https://www.veracross.com/integrations
    tier: declared
  kind: commercial
  name: Veracross
  page: /applications/school-admin-sis/veracross/
  slug: veracross
  url: https://www.veracross.com/
- anchor: powerschool-sis
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.powerschool.portal/latest/
  - route: integrations page
    url: https://www.powerschool.com/partners/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.powerschool.portal/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.powerschool.portal/latest/
    tier: observed
  kind: commercial
  name: PowerSchool SIS
  page: /applications/school-admin-sis/powerschool-sis/
  slug: powerschool-sis
  url: https://www.powerschool.com/
- anchor: infinite-campus
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.infinitecampus.mobilePortal/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.infinitecampus.mobilePortal/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.infinitecampus.mobilePortal/latest/
    tier: observed
  kind: commercial
  name: Infinite Campus
  page: /applications/school-admin-sis/infinite-campus/
  slug: infinite-campus
  url: https://www.infinitecampus.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: school-admin-sis
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Education
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Education
  store: google-play
  url: https://play.google.com/store/apps/category/EDUCATION
- category: Student Information Systems (SIS)
  store: g2
  url: https://www.g2.com/categories/student-information-systems-sis
name: School Administration & SIS
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: mailbox-calendar-sync
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for mailbox & calendar sync
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: staff, student and parent sign-in with school Google/Microsoft accounts
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: fee, tuition and invoice payments
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: parent and staff SMS alerts (attendance, emergencies)
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: class/course sync to the LMS
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for general ledger management
- capability:
    attribution: API Evangelist extension
    id: AE-944
    key: AE-944
    name: K-12 Rostering & Roster Sync
    url: /capabilities/k-12-rostering-roster-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: 'K-12 Rostering & Roster Sync: Clever, ClassLink, Apple School Manager, Microsoft 365 (School Data Sync)'
- capability:
    attribution: Turbo EA
    id: BC-4730
    key: teaching-learning-operations-management
    name: Teaching & Learning Operations Management
    url: /capabilities/teaching-learning-operations-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for teaching & learning operations management
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: video-calling
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for video calling
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by the reference apps for email marketing sends
- capability:
    attribution: Turbo EA
    id: BC-930.60
    key: process-automation-governance
    name: Process Automation Governance
    url: /capabilities/process-automation-governance/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for process automation governance
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for customer relationship management
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for analytics & bi management
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for asset storage & tiering
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: named by the reference apps for whatsapp & ott messaging
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: AE-150.40
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for in-app chat
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for product usage analytics
- capability:
    attribution: Turbo EA
    id: BC-2500.50
    key: electronic-documentation-management
    name: Electronic Documentation Management
    url: /capabilities/electronic-documentation-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for electronic documentation management
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by the reference apps for fundraising campaign management
- capability:
    attribution: Turbo EA
    id: BC-4710
    key: student-recruitment-admissions-management
    name: Student Recruitment & Admissions Management
    url: /capabilities/student-recruitment-admissions-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for student recruitment & admissions management
- capability:
    attribution: Turbo EA
    id: BC-4770
    key: student-support-wellbeing-management
    name: Student Support & Wellbeing Management
    url: /capabilities/student-support-wellbeing-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by the reference apps for student support & wellbeing management
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
    id: BC-4740.20.30
    key: BC-4740.20.30
    name: Online & Remote Proctoring
    url: /capabilities/examination-operations/
    via_parent: Examination Operations
  fit: exact
  layer: domain
  why: SMOWL (Online & Remote Proctoring)
- capability:
    attribution: Turbo EA
    id: BC-3780.50
    key: BC-3780.50
    name: Accessibility Compliance Management
    url: /capabilities/content-compliance-standards-management/
    via_parent: Content Compliance & Standards Management
  fit: exact
  layer: common
  why: EqualWeb (Accessibility Compliance Management)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4730.30
      key: learning-environment-management
      name: Learning Environment Management
      url: /capabilities/learning-environment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.8
      apps:
      - Alma
      - Classe365
      - Gradelink
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developers.google.com/workspace/classroom/guides/mcp/configure-mcp-server
        status: verified
      name: Google Classroom
      slug: google-classroom
      sources:
      - https://www.classe365.com/integrations/
      - https://www.getalma.com/solutions/
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Assignments
      - Classroom
      - Courses
      - Education
      tier: declared
      url: /providers/google-classroom/
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - Classe365
      - RosarioSIS
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Moodle
      slug: moodle
      sources:
      - https://github.com/francoisjacquet/rosariosis/tree/mobile/plugins
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - E-Learning
      - EdTech
      - LMS
      - Moodle
      tier: observed
      url: /providers/moodle/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Classe365
      - Gradelink
      band: exemplar
      in_catalog: true
      kin_score: 70.0
      mcp:
        source: https://www.instructure.com/resources/infographic/context-king-mcp-explained
        status: documented
      name: Canvas LMS
      slug: canvas
      sources:
      - https://www.classe365.com/integrations/
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Canvas
      - EdTech
      - Education
      - GraphQL
      tier: declared
      url: /providers/canvas/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Classe365
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        status: none
      name: Brightspace
      slug: brightspace
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - EdTech
      - Education
      - LMS
      - Valence
      tier: declared
      url: /providers/brightspace/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Gradelink
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: unknown
      name: Schoology
      slug: schoology
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - EdTech
      - K-12
      - LMS
      tier: declared
      url: /providers/schoology/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Classe365
      band: emerging
      in_catalog: true
      kin_score: 12.3
      mcp:
        status: unknown
      name: Blackboard
      slug: blackboard
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - EdTech
      - LMS
      tier: declared
      url: /providers/blackboard/
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - Veracross
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: unchecked
      name: Firefly
      slug: firefly-learning
      sources:
      - https://www.veracross.com/integrations
      status: profiled
      tags:
      - EdTech
      - Education
      - Schools
      - Software-as-a-Service
      tier: declared
      url: /providers/firefly-learning/
  - capability:
      attribution: API Evangelist extension
      id: AE-944
      key: AE-944
      name: K-12 Rostering & Roster Sync
      url: /capabilities/k-12-rostering-roster-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Classe365
      - Gradelink
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: Clever
      slug: clever
      sources:
      - https://www.classe365.com/integrations/
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - EdTech
      - Education
      - K-12
      - SSO
      tier: declared
      url: /providers/clever/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Gradelink
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp: &id001
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365 (School Data Sync)
      slug: microsoft-365
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags: &id002
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Gradelink
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple School Manager
      slug: apple
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Gradelink
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: unknown
      name: ClassLink
      slug: classlink
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - EdTech
      - Education
      - Identity
      - SSO
      tier: declared
      url: /providers/classlink/
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Veracross
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: unknown
      name: Double the Donation
      slug: double-the-donation
      sources:
      - https://www.veracross.com/integrations
      status: profiled
      tags:
      - Company
      - Fundraising
      - Matching Gifts
      - Non-Profit
      tier: declared
      url: /providers/double-the-donation/
  - capability:
      attribution: Turbo EA
      id: BC-4740.20.30
      key: BC-4740.20.30
      name: Online & Remote Proctoring
      url: /capabilities/examination-operations/
      via_parent: Examination Operations
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Classe365
      band: emerging
      in_catalog: true
      kin_score: 16.0
      mcp:
        status: unchecked
      name: SMOWL
      slug: smowl
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Education
      - Monitoring
      - Proctoring
      - Software
      tier: declared
      url: /providers/smowl/
  - capability:
      attribution: Turbo EA
      id: BC-4710
      key: student-recruitment-admissions-management
      name: Student Recruitment & Admissions Management
      url: /capabilities/student-recruitment-admissions-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Veracross
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: unchecked
      name: Digistorm Websites
      slug: digistorm
      sources:
      - https://www.veracross.com/integrations
      status: profiled
      tags:
      - Education
      - K-12
      - SchoolSoftware
      - Software-as-a-Service
      tier: declared
      url: /providers/digistorm/
  - capability:
      attribution: Turbo EA
      id: BC-4770
      key: student-support-wellbeing-management
      name: Student Support & Wellbeing Management
      url: /capabilities/student-support-wellbeing-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Veracross
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: unchecked
      name: Epraise
      slug: epraise
      sources:
      - https://www.veracross.com/integrations
      status: profiled
      tags:
      - Education
      - Engagement
      - Rewards
      - SchoolTech
      tier: declared
      url: /providers/epraise/
  - capability:
      attribution: Turbo EA
      id: BC-4730
      key: teaching-learning-operations-management
      name: Teaching & Learning Operations Management
      url: /capabilities/teaching-learning-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - Gradelink
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        status: none
      name: Renaissance (RDI)
      slug: renaissance
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Assessment
      - EdTech
      - Education
      - K-12
      tier: declared
      url: /providers/renaissance/
  layer: domain
- capabilities:
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
      - Classe365
      - Gibbon
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Classe365
      - Gibbon
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Frappe Education
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://github.com/razorpay/razorpay-mcp-server
        status: verified
      name: Razorpay
      slug: razorpay
      sources:
      - https://github.com/frappe/education/blob/develop/education/education/billing.py
      status: profiled
      tags:
      - Fintech
      - India
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Gradelink
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        status: unchecked
      name: PaySimple
      slug: paysimple
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Billing
      - Company
      - Payments
      - Software-as-a-Service
      tier: declared
      url: /providers/paysimple/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Classe365
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.net
      slug: authorizenet
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/authorizenet/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Gradelink
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        status: unchecked
      name: FACTS Tuition Management
      slug: facts-management
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Education
      - School Management
      - Software-as-a-Service
      - Tuition
      tier: declared
      url: /providers/facts-management/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gradelink
      band: emerging
      in_catalog: true
      kin_score: 13.5
      mcp:
        status: unknown
      name: ClassWallet
      slug: classwallet
      sources:
      - https://www.gradelink.com/integrations/
      status: profiled
      tags:
      - Company
      - Digital Wallet
      - Fintech
      - Payments
      tier: declared
      url: /providers/classwallet/
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
      - Classe365
      - Gibbon
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gibbon
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        status: unchecked
      name: OneWaySMS
      slug: onewaysms
      sources:
      - https://github.com/GibbonEdu/core/tree/v31.0.00/src/Comms/Drivers
      status: profiled
      tags:
      - Communications
      - Malaysia
      - Marketing
      - SMS
      tier: observed
      url: /providers/onewaysms/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Gibbon
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Nexmo (Vonage)
      slug: vonage
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: declared
      url: /providers/vonage/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Gibbon
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: unchecked
      name: Clockwork SMS
      slug: clockwork-sms
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
      status: profiled
      tags:
      - Company
      - Marketing
      - SMS
      - United Kingdom
      tier: declared
      url: /providers/clockwork-sms/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gibbon
      band: minimal
      in_catalog: true
      kin_score: 3.6
      mcp:
        status: unknown
      name: Textlocal
      slug: textlocal
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/textlocal/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Frappe Education
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        source: https://github.com/frappe/mcp
        status: verified
      name: ERPNext
      slug: erpnext
      sources:
      - https://github.com/frappe/education/blob/develop/education/education/billing.py
      status: profiled
      tags:
      - Accounting
      - ERP
      - Inventory
      - Manufacturing
      tier: observed
      url: /providers/erpnext/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Classe365
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Classe365
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: none
      name: MYOB
      slug: myob
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bills
      - Business Management
      - Invoices
      tier: declared
      url: /providers/myob/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Gibbon
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft sign-in
      slug: microsoft-entra
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Gibbon
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp: *id001
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
  - capability:
      attribution: Turbo EA
      id: BC-930.60
      key: process-automation-governance
      name: Process Automation Governance
      url: /capabilities/process-automation-governance/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - Classe365
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Power Automate
      slug: microsoft-power-automate
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Automation
      - Business Process
      - Integration
      - Low-Code
      tier: declared
      url: /providers/microsoft-power-automate/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Classe365
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
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
      - Infinite Campus
      - PowerSchool SIS
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.infinitecampus.mobilePortal/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.powerschool.portal/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/powerbi-modeling-mcp
        status: verified
      name: Power BI
      slug: power-bi
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Analysis
      tier: declared
      url: /providers/power-bi/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Veracross
      band: developing
      in_catalog: true
      kin_score: 43.1
      mcp:
        status: unchecked
      name: Intellischool
      slug: intellischool
      sources:
      - https://www.veracross.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Data
      - Education
      tier: declared
      url: /providers/intellischool/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Classe365
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: SharePoint
      slug: sharepoint
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: declared
      url: /providers/sharepoint/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Classe365
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: mailbox-calendar-sync
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Gibbon
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Gibbon
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google APIs (google/apiclient)
      slug: google
      sources:
      - https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
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
      - Infinite Campus
      - PowerSchool SIS
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.infinitecampus.mobilePortal/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.powerschool.portal/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: video-calling
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Classe365
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Classe365
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: Turbo EA
      id: BC-3780.50
      key: BC-3780.50
      name: Accessibility Compliance Management
      url: /capabilities/content-compliance-standards-management/
      via_parent: Content Compliance & Standards Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Classe365
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: unchecked
      name: EqualWeb
      slug: equalweb
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Accessibility
      - Artificial Intelligence
      - Company
      - Compliance
      tier: declared
      url: /providers/equalweb/
  - capability:
      attribution: Turbo EA
      id: BC-2500.50
      key: electronic-documentation-management
      name: Electronic Documentation Management
      url: /capabilities/electronic-documentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Classe365
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        source: https://github.com/pandadoc/pandadoc-mcpb
        status: verified
      name: PandaDoc
      slug: pandadoc
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Document Automation
      - Document Generation
      - Document Management
      - E-Signature
      tier: declared
      url: /providers/pandadoc/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Classe365
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Classe365
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://www.classe365.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 44
  distinct_providers: 55
  in_catalog: 55
  mcp:
    documented: 1
    none: 13
    unchecked: 10
    verified: 25
  mcp_verified: 25
  mean_kin_score: 49.5
  observed: 11
  queued: 0
  reference_apps: 9
title: 'School Administration & SIS: application blueprint'
---
