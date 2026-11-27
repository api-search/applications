---
app: Classe365
app_slug: classe365
app_url: https://www.classe365.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-944
  key: AE-944
  layer: domain
  name: K-12 Rostering & Roster Sync
  providers:
  - Clever
  url: /capabilities/k-12-rostering-roster-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4730.30
  key: learning-environment-management
  layer: domain
  name: Learning Environment Management
  providers:
  - Blackboard
  - Brightspace
  - Canvas LMS
  - Google Classroom
  - Moodle
  url: /capabilities/learning-environment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4740.20.30
  key: BC-4740.20.30
  layer: domain
  name: Online & Remote Proctoring
  providers:
  - SMOWL
  url: /capabilities/examination-operations/
  via_parent: Examination Operations
- attribution: Turbo EA
  id: BC-3780.50
  key: BC-3780.50
  layer: common
  name: Accessibility Compliance Management
  providers:
  - EqualWeb
  url: /capabilities/content-compliance-standards-management/
  via_parent: Content Compliance & Standards Management
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Power BI
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - OneDrive
  - SharePoint
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2500.50
  key: electronic-documentation-management
  layer: common
  name: Electronic Documentation Management
  providers:
  - PandaDoc
  url: /capabilities/electronic-documentation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - MYOB
  - QuickBooks Online
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40
  key: AE-150.40
  layer: common
  name: In-App Chat
  providers:
  - Intercom
  url: /capabilities/in-app-chat/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Authorize.net
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-930.60
  key: process-automation-governance
  layer: common
  name: Process Automation Governance
  providers:
  - Make
  - Power Automate
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio SMS
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google Workspace
  - Microsoft 365
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.60
  key: video-calling
  layer: common
  name: Video Calling
  providers:
  - Microsoft Teams
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: school-admin-sis
  name: School Administration & SIS
  url: /applications/school-admin-sis/
counts:
  declared: 32
  observed: 0
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id001
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id002
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.3
    mcp: &id003
      status: unknown
    slug: blackboard
    status: profiled
    tags: &id004
    - EdTech
    - LMS
    url: /providers/blackboard/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id005
      status: none
    slug: brightspace
    status: profiled
    tags: &id006
    - EdTech
    - Education
    - LMS
    - Valence
    url: /providers/brightspace/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: exemplar
    in_catalog: true
    kin_score: 70.0
    mcp: &id007
      source: https://www.instructure.com/resources/infographic/context-king-mcp-explained
      status: documented
    slug: canvas
    status: profiled
    tags: &id008
    - Canvas
    - EdTech
    - Education
    - GraphQL
    url: /providers/canvas/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id009
      status: none
    slug: clever
    status: profiled
    tags: &id010
    - EdTech
    - Education
    - K-12
    - SSO
    url: /providers/clever/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id011
      status: unchecked
    slug: equalweb
    status: profiled
    tags: &id012
    - Accessibility
    - Artificial Intelligence
    - Company
    - Compliance
    url: /providers/equalweb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id013
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id014
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id015
      source: https://developers.google.com/workspace/classroom/guides/mcp/configure-mcp-server
      status: verified
    slug: google-classroom
    status: profiled
    tags: &id016
    - Assignments
    - Classroom
    - Courses
    - Education
    url: /providers/google-classroom/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id017
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id018
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id019
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id020
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id021
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id023
      status: none
    slug: mailchimp
    status: profiled
    tags: &id024
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id025
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id026
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id027
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id028
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id029
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id030
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
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
  facts:
    agent_band: human-only
    agent_readiness: 1.7
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id031
      status: none
    slug: moodle
    status: profiled
    tags: &id032
    - E-Learning
    - EdTech
    - LMS
    - Moodle
    url: /providers/moodle/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id033
      status: none
    slug: myob
    status: profiled
    tags: &id034
    - Accounting
    - Bills
    - Business Management
    - Invoices
    url: /providers/myob/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id035
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id036
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id037
      source: https://github.com/pandadoc/pandadoc-mcpb
      status: verified
    slug: pandadoc
    status: profiled
    tags: &id038
    - Document Automation
    - Document Generation
    - Document Management
    - E-Signature
    url: /providers/pandadoc/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id039
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id040
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id041
      status: none
    slug: microsoft-power-automate
    status: profiled
    tags: &id042
    - Automation
    - Business Process
    - Integration
    - Low-Code
    url: /providers/microsoft-power-automate/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id043
      source: https://github.com/microsoft/powerbi-modeling-mcp
      status: verified
    slug: power-bi
    status: profiled
    tags: &id044
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Analysis
    url: /providers/power-bi/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id045
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id046
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id047
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id048
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id049
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id050
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 16.0
    mcp: &id051
      status: unchecked
    slug: smowl
    status: profiled
    tags: &id052
    - Education
    - Monitoring
    - Proctoring
    - Software
    url: /providers/smowl/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id053
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id054
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id055
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id056
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id057
      status: none
    slug: whatsapp
    status: profiled
    tags: &id058
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
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
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id059
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id060
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id061
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id062
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id063
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id064
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.classe365.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/school-admin-sis/classe365/
providers:
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id001
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id002
  url: /providers/authorizenet/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id003
  name: Blackboard
  slug: blackboard
  status: profiled
  tags: *id004
  url: /providers/blackboard/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id005
  name: Brightspace
  slug: brightspace
  status: profiled
  tags: *id006
  url: /providers/brightspace/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: exemplar
  in_catalog: true
  kin_score: 70.0
  mcp: *id007
  name: Canvas LMS
  slug: canvas
  status: profiled
  tags: *id008
  url: /providers/canvas/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id009
  name: Clever
  slug: clever
  status: profiled
  tags: *id010
  url: /providers/clever/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id011
  name: EqualWeb
  slug: equalweb
  status: profiled
  tags: *id012
  url: /providers/equalweb/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id013
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id014
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id015
  name: Google Classroom
  slug: google-classroom
  status: profiled
  tags: *id016
  url: /providers/google-classroom/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id017
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id018
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id019
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id020
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id021
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id022
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id023
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id024
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id025
  name: Make
  slug: make
  status: profiled
  tags: *id026
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id027
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id028
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id029
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id030
  url: /providers/microsoft-teams/
- agent_band: human-only
  agent_readiness: 1.7
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id031
  name: Moodle
  slug: moodle
  status: profiled
  tags: *id032
  url: /providers/moodle/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id033
  name: MYOB
  slug: myob
  status: profiled
  tags: *id034
  url: /providers/myob/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id035
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id036
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id037
  name: PandaDoc
  slug: pandadoc
  status: profiled
  tags: *id038
  url: /providers/pandadoc/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id039
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id040
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id041
  name: Power Automate
  slug: microsoft-power-automate
  status: profiled
  tags: *id042
  url: /providers/microsoft-power-automate/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id043
  name: Power BI
  slug: power-bi
  status: profiled
  tags: *id044
  url: /providers/power-bi/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id045
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id046
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id047
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id048
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id049
  name: SharePoint
  slug: sharepoint
  status: profiled
  tags: *id050
  url: /providers/sharepoint/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 16.0
  mcp: *id051
  name: SMOWL
  slug: smowl
  status: profiled
  tags: *id052
  url: /providers/smowl/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id053
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id054
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id055
  name: Twilio SMS
  slug: twilio
  status: profiled
  tags: *id056
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id057
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id058
  url: /providers/whatsapp/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id059
  name: Xero
  slug: xero
  status: profiled
  tags: *id060
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id061
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id062
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id063
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id064
  url: /providers/zoom/
siblings:
- name: Alma
  rows: 1
  url: /applications/school-admin-sis/alma/
- name: Frappe Education
  rows: 2
  url: /applications/school-admin-sis/frappe-education/
- name: Gibbon
  rows: 11
  url: /applications/school-admin-sis/gibbon/
- name: Gradelink
  rows: 11
  url: /applications/school-admin-sis/gradelink/
- name: Infinite Campus
  rows: 2
  url: /applications/school-admin-sis/infinite-campus/
- name: PowerSchool SIS
  rows: 2
  url: /applications/school-admin-sis/powerschool-sis/
- name: RosarioSIS
  rows: 1
  url: /applications/school-admin-sis/rosariosis/
- name: Veracross
  rows: 5
  url: /applications/school-admin-sis/veracross/
sitemap: true
title: 'Classe365: School Administration & SIS reference app'
---
