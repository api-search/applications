---
app: Acuity Scheduling
app_slug: acuity-scheduling
app_url: https://acuityscheduling.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Squarespace
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Daylite
  - Infusionsoft (Keap)
  - Salesforce
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook Business + Instagram
  - ReferralCandy
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - AWeber
  - Constant Contact
  - ConvertKit
  - Drip
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-4330.50
  key: invoice-generation-management
  layer: domain
  name: Invoice Generation Management
  providers:
  - FreshBooks
  - QuickBooks
  url: /capabilities/invoice-generation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Google Contacts
  - iCloud
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - Wufoo
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - ClassPass
  - Reserve with Google
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Google Hangouts Meet
  - GoToMeeting / join.me
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Tune
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  - Instabug
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Square
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Google Firebase Analytics
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Google Sheets
  - Zapier
  - Zoho Flow
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: booking-scheduling
  name: Appointment Booking & Scheduling
  url: /applications/booking-scheduling/
counts:
  declared: 32
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
- route: integrations page
  url: https://acuityscheduling.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id003
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id007
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id008
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id023
      status: none
    slug: google-admob
    status: profiled
    tags: &id024
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id031
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id032
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id043
      source: https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features.md
      status: documented
    slug: instabug
    status: profiled
    tags: &id044
    - AI Agents
    - APM
    - Application Performance Monitoring
    - Bug Reporting
    url: /providers/instabug/
  layer: common
  name: Instabug
  provider: instabug
  says: ships the Instabug SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id065
      status: unknown
    slug: tune
    status: profiled
    tags: &id066
    - Advertising
    - Affiliates
    - Marketing
    - Software-as-a-Service
    url: /providers/tune/
  layer: common
  name: Tune
  provider: tune
  says: ships the Tune SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  tier: observed
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
    agent_readiness: 51.0
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id001
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id002
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: domain
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id005
      source: https://github.com/aweber/aweber-mcp
      status: verified
    slug: aweber
    status: profiled
    tags: &id006
    - Email
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/aweber/
  layer: domain
  name: AWeber
  provider: aweber
  says: lists AWeber as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id009
      status: none
    slug: classpass
    status: profiled
    tags: &id010
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id011
      status: none
    slug: constant-contact
    status: profiled
    tags: &id012
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: domain
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 80.4
    mcp: &id013
      status: none
    slug: convertkit
    status: profiled
    tags: &id014
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: domain
  name: ConvertKit
  provider: convertkit
  says: lists ConvertKit as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 24.0
    band: developing
    in_catalog: true
    kin_score: 49.9
    mcp: &id015
      status: unknown
    slug: daylite
    status: profiled
    tags: &id016
    - CRM
    - Company
    - Mac
    - Small Business
    url: /providers/daylite/
  layer: domain
  name: Daylite
  provider: daylite
  says: lists Daylite as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 47.6
    band: strong
    in_catalog: true
    kin_score: 63.9
    mcp: &id017
      status: none
    slug: drip
    status: profiled
    tags: &id018
    - Customer Engagement
    - E-Commerce
    - Email Marketing
    - Marketing Automation
    url: /providers/drip/
  layer: domain
  name: Drip
  provider: drip
  says: lists Drip as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id019
      status: none
    slug: facebook
    status: profiled
    tags: &id020
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook Business + Instagram
  provider: facebook
  says: lists Facebook Business + Instagram as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id021
      status: none
    slug: freshbooks
    status: profiled
    tags: &id022
    - Accounting
    - Expense Tracking
    - Invoicing
    - Time Tracking
    url: /providers/freshbooks/
  layer: domain
  name: FreshBooks
  provider: freshbooks
  says: lists FreshBooks as an integration
  source: https://acuityscheduling.com/integrations
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
    mcp: &id025
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id026
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id027
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id028
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id029
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id030
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: domain
  name: Google Contacts
  provider: google-people
  says: lists Google Contacts as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id033
      status: none
    slug: google-meet
    status: profiled
    tags: &id034
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Hangouts Meet
  provider: google-meet
  says: lists Google Hangouts Meet as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id035
      status: none
    slug: google-sheets
    status: profiled
    tags: &id036
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id037
      status: none
    slug: goto
    status: profiled
    tags: &id038
    - Company
    - Consumer
    - Indonesia
    - Super App
    url: /providers/goto/
  layer: domain
  name: GoToMeeting / join.me
  provider: goto
  says: lists GoToMeeting / join.me as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id039
      status: none
    slug: apple
    status: profiled
    tags: &id040
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: iCloud
  provider: apple
  says: lists iCloud as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 44.5
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id041
      status: none
    slug: keap
    status: profiled
    tags: &id042
    - CRM
    - Marketing Automation
    - Sales
    - Small Business
    url: /providers/keap/
  layer: domain
  name: Infusionsoft (Keap)
  provider: keap
  says: lists Infusionsoft (Keap) as an integration
  source: https://acuityscheduling.com/integrations
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
    mcp: &id045
      status: none
    slug: mailchimp
    status: profiled
    tags: &id046
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id047
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id048
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://acuityscheduling.com/integrations
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
    mcp: &id049
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id050
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id051
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id052
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id053
      status: none
    slug: referralcandy
    status: profiled
    tags: &id054
    - Affiliates
    - Company
    - E-Commerce
    - Referrals
    url: /providers/referralcandy/
  layer: domain
  name: ReferralCandy
  provider: referralcandy
  says: lists ReferralCandy as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id055
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id056
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Reserve with Google
  provider: google
  says: lists Reserve with Google as an integration
  source: https://acuityscheduling.com/integrations
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
    mcp: &id057
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id058
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id059
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id060
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: common
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id061
      status: none
    slug: squarespace
    status: profiled
    tags: &id062
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://acuityscheduling.com/integrations
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
    mcp: &id063
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id064
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id067
      status: none
    slug: wufoo
    status: profiled
    tags: &id068
    - Data Collection
    - Form Builder
    - Forms
    - Surveys
    url: /providers/wufoo/
  layer: domain
  name: Wufoo
  provider: wufoo
  says: lists Wufoo as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id069
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id070
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://acuityscheduling.com/integrations
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
    agent_readiness: 43.3
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id071
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id072
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.4
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id073
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id074
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: common
  name: Zoho Flow
  provider: zoho
  says: lists Zoho Flow as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
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
    mcp: &id075
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id076
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://acuityscheduling.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/booking-scheduling/acuity-scheduling/
providers:
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id001
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id002
  url: /providers/activecampaign/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id003
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id004
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id005
  name: AWeber
  slug: aweber
  status: profiled
  tags: *id006
  url: /providers/aweber/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id007
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id008
  url: /providers/bugsnag/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id009
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id010
  url: /providers/classpass/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id011
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id012
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 80.4
  mcp: *id013
  name: ConvertKit
  slug: convertkit
  status: profiled
  tags: *id014
  url: /providers/convertkit/
- agent_band: agent-aware
  agent_readiness: 24.0
  band: developing
  in_catalog: true
  kin_score: 49.9
  mcp: *id015
  name: Daylite
  slug: daylite
  status: profiled
  tags: *id016
  url: /providers/daylite/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id017
  name: Drip
  slug: drip
  status: profiled
  tags: *id018
  url: /providers/drip/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id019
  name: Facebook Business + Instagram
  slug: facebook
  status: profiled
  tags: *id020
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id021
  name: FreshBooks
  slug: freshbooks
  status: profiled
  tags: *id022
  url: /providers/freshbooks/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id023
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id024
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id025
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id026
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id027
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id028
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id029
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id030
  url: /providers/google-people/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id031
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id032
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id033
  name: Google Hangouts Meet
  slug: google-meet
  status: profiled
  tags: *id034
  url: /providers/google-meet/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id035
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id036
  url: /providers/google-sheets/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id037
  name: GoToMeeting / join.me
  slug: goto
  status: profiled
  tags: *id038
  url: /providers/goto/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id039
  name: iCloud
  slug: apple
  status: profiled
  tags: *id040
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 44.5
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id041
  name: Infusionsoft (Keap)
  slug: keap
  status: profiled
  tags: *id042
  url: /providers/keap/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id043
  name: Instabug
  slug: instabug
  status: profiled
  tags: *id044
  url: /providers/instabug/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id045
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id046
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id047
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id048
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id049
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id050
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id051
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id052
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id053
  name: ReferralCandy
  slug: referralcandy
  status: profiled
  tags: *id054
  url: /providers/referralcandy/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id055
  name: Reserve with Google
  slug: google
  status: profiled
  tags: *id056
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id057
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id058
  url: /providers/salesforce/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id059
  name: Square
  slug: square
  status: profiled
  tags: *id060
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id061
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id062
  url: /providers/squarespace/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id063
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id064
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id065
  name: Tune
  slug: tune
  status: profiled
  tags: *id066
  url: /providers/tune/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id067
  name: Wufoo
  slug: wufoo
  status: profiled
  tags: *id068
  url: /providers/wufoo/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id069
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id070
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id071
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id072
  url: /providers/zoho-crm/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id073
  name: Zoho Flow
  slug: zoho
  status: profiled
  tags: *id074
  url: /providers/zoho/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id075
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id076
  url: /providers/zoom/
siblings:
- name: Booksy Biz
  rows: 6
  url: /applications/booking-scheduling/booksy-biz/
- name: Cal.com
  rows: 71
  url: /applications/booking-scheduling/cal-com/
- name: Calendly
  rows: 54
  url: /applications/booking-scheduling/calendly/
- name: Easy!Appointments
  rows: 1
  url: /applications/booking-scheduling/easy-appointments/
- name: LibreBooking
  rows: 8
  url: /applications/booking-scheduling/librebooking/
- name: Rallly
  rows: 13
  url: /applications/booking-scheduling/rallly/
sitemap: true
title: 'Acuity Scheduling: Appointment Booking & Scheduling reference app'
---
