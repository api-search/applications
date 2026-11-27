---
app: Aircall
app_slug: aircall
app_url: https://aircall.io/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Attio
  - Bullhorn
  - Freshsales
  - HighLevel
  - HubSpot
  - Kommo
  - Microsoft Dynamics
  - Odoo
  - Pipedrive
  - Salesforce
  - Zendesk Sell
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Freshdesk
  - Front
  - Gorgias
  - Help Scout
  - Intercom
  - Kustomer
  - Missive
  - Re:amaze
  - Trengo
  - Zendesk
  - Zoho Desk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260
  key: customer-success-management
  layer: domain
  name: Customer Success Management
  providers:
  - Planhat
  url: /capabilities/customer-success-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - Klaviyo
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
  - Avoma
  - Chorus.ai
  - Fireflies
  - Gong
  - Jiminny
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Salesmsg
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-954
  key: AE-954
  layer: domain
  name: Sales Engagement & Sequencing
  providers:
  - lemlist
  - Outreach
  - Salesloft
  url: /capabilities/sales-engagement-sequencing/
  via_parent: null
- attribution: Turbo EA
  id: BC-410.70
  key: sales-performance-management
  layer: domain
  name: Sales Performance Management
  providers:
  - Mindtickle
  url: /capabilities/sales-performance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Chili Piper
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Geckoboard
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Fivetran
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - monday.com
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Pipedream
  - Tray.ai
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: sales-engagement
  name: Sales Engagement & Dialers
  url: /applications/sales-engagement/
counts:
  declared: 51
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
- route: integrations page
  url: https://aircall.io/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id016
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id017
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id074
      status: none
    slug: pusher
    status: profiled
    tags: &id075
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
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
    mcp: &id002
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id003
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: domain
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 44.8
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id004
      source: https://docs.attio.com/mcp/overview
      status: verified
    slug: attio
    status: profiled
    tags: &id005
    - CRM
    - Companies
    - Contacts
    - Sales
    url: /providers/attio/
  layer: domain
  name: Attio
  provider: attio
  says: lists Attio as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id006
      source: https://www.avoma.com/agentic-platform/mcp
      status: documented
    slug: avoma
    status: profiled
    tags: &id007
    - Artificial Intelligence
    - Automation
    - Meeting Assistant
    - Sales Enablement
    url: /providers/avoma/
  layer: domain
  name: Avoma
  provider: avoma
  says: lists Avoma as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id008
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id009
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 5.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id010
      status: none
    slug: bullhorn
    status: profiled
    tags: &id011
    - Applicant Tracking
    - Company
    - Recruiting
    - Staffing
    url: /providers/bullhorn/
  layer: domain
  name: Bullhorn
  provider: bullhorn
  says: lists Bullhorn as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 56.2
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id012
      source: https://www.chilipiper.com/products/mcp
      status: verified
    slug: chili-piper
    status: profiled
    tags: &id013
    - Lead Routing
    - Meetings
    - Sales
    - Scheduling
    url: /providers/chili-piper/
  layer: domain
  name: Chili Piper
  provider: chili-piper
  says: lists Chili Piper as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id014
      status: none
    slug: chorus-ai
    status: profiled
    tags: &id015
    - Analytics
    - Conversations
    - Revenue Intelligence
    - Sales
    url: /providers/chorus-ai/
  layer: domain
  name: Chorus.ai
  provider: chorus-ai
  says: lists Chorus.ai as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.4
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id018
      source: https://docs.fireflies.ai/mcp-tools/overview
      status: verified
    slug: fireflies
    status: profiled
    tags: &id019
    - Artificial Intelligence
    - Meeting Assistant
    - Summary
    - Transcription
    url: /providers/fireflies/
  layer: domain
  name: Fireflies
  provider: fireflies
  says: lists Fireflies as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id020
      source: https://github.com/fivetran/fivetran-mcp
      status: verified
    slug: fivetran
    status: profiled
    tags: &id021
    - Connectors
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/fivetran/
  layer: common
  name: Fivetran
  provider: fivetran
  says: lists Fivetran as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id022
      status: none
    slug: freshdesk
    status: profiled
    tags: &id023
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id024
      status: none
    slug: freshsales
    status: profiled
    tags: &id025
    - CRM
    - Contacts
    - Deals
    - Sales
    url: /providers/freshsales/
  layer: domain
  name: Freshsales
  provider: freshsales
  says: lists Freshsales as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id026
      source: https://dev.frontapp.com/docs/mcp
      status: documented
    slug: front
    status: profiled
    tags: &id027
    - Customer Operations
    - Customer Service
    - Email
    - Inbox
    url: /providers/front/
  layer: domain
  name: Front
  provider: front
  says: lists Front as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id028
      source: https://www.geckoboard.com/product/metrics-mcp/
      status: verified
    slug: geckoboard
    status: profiled
    tags: &id029
    - Business Intelligence
    - Dashboards
    - Data Visualization
    - KPI Tracking
    url: /providers/geckoboard/
  layer: common
  name: Geckoboard
  provider: geckoboard
  says: lists Geckoboard as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: exemplar
    in_catalog: true
    kin_score: 66.5
    mcp: &id030
      status: none
    slug: gong
    status: profiled
    tags: &id031
    - Analytics
    - Conversations
    - Revenue Intelligence
    - Sales
    url: /providers/gong/
  layer: domain
  name: Gong
  provider: gong
  says: lists Gong as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id032
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id033
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: domain
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id034
      status: none
    slug: helpscout
    status: profiled
    tags: &id035
    - Customer Service
    - Email
    - Help Desk
    - Live Chat
    url: /providers/helpscout/
  layer: domain
  name: Help Scout
  provider: helpscout
  says: lists Help Scout as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 37.5
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id036
      source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
      status: verified
    slug: highlevel
    status: profiled
    tags: &id037
    - CRM
    - Company
    - Marketing
    - Software-as-a-Service
    url: /providers/highlevel/
  layer: domain
  name: HighLevel
  provider: highlevel
  says: lists HighLevel as an integration
  source: https://aircall.io/integrations/
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
    mcp: &id038
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id039
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id040
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id041
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id042
      status: unchecked
    slug: jiminny
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - CRM Integration
    - Revenue
    - Sales Intelligence
    url: /providers/jiminny/
  layer: domain
  name: Jiminny
  provider: jiminny
  says: lists Jiminny as an integration
  source: https://aircall.io/integrations/
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
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id044
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id045
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: domain
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id046
      status: unchecked
    slug: kommo
    status: profiled
    tags: &id047
    - Artificial Intelligence
    - CRM
    - Messaging
    - Sales
    url: /providers/kommo/
  layer: domain
  name: Kommo
  provider: kommo
  says: lists Kommo as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id048
      status: none
    slug: kustomer
    status: profiled
    tags: &id049
    - CRM
    - Customer Service
    - Help Desk
    - Messaging
    url: /providers/kustomer/
  layer: domain
  name: Kustomer
  provider: kustomer
  says: lists Kustomer as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-954
    key: AE-954
    name: Sales Engagement & Sequencing
    url: /capabilities/sales-engagement-sequencing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.9
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id050
      source: https://api.lemlist.com/mcp
      status: verified
    slug: lemlist
    status: profiled
    tags: &id051
    - Cold Email
    - Email Outreach
    - Sales Automation
    - Sales Engagement
    url: /providers/lemlist/
  layer: domain
  name: lemlist
  provider: lemlist
  says: lists lemlist as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id052
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id053
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id054
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id055
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id056
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id057
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.70
    key: sales-performance-management
    name: Sales Performance Management
    url: /capabilities/sales-performance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: strong
    in_catalog: true
    kin_score: 56.6
    mcp: &id058
      status: none
    slug: mindtickle
    status: profiled
    tags: &id059
    - Coaching
    - Revenue Productivity
    - Sales Enablement
    - Sales Readiness
    url: /providers/mindtickle/
  layer: domain
  name: Mindtickle
  provider: mindtickle
  says: lists Mindtickle as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.6
    band: developing
    in_catalog: true
    kin_score: 47.6
    mcp: &id060
      source: https://mcp.missiveapp.com/.well-known/oauth-protected-resource
      status: verified
    slug: missive
    status: profiled
    tags: &id061
    - Collaboration
    - Email
    - Messaging
    - Team Inbox
    url: /providers/missive/
  layer: domain
  name: Missive
  provider: missive
  says: lists Missive as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id062
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id063
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: common
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 27.6
    mcp: &id064
      status: none
    slug: odoo
    status: profiled
    tags: &id065
    - Business Applications
    - CRM
    - ERP
    - Open Source
    url: /providers/odoo/
  layer: domain
  name: Odoo
  provider: odoo
  says: lists Odoo as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-954
    key: AE-954
    name: Sales Engagement & Sequencing
    url: /capabilities/sales-engagement-sequencing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 78.7
    mcp: &id066
      status: none
    slug: outreach
    status: profiled
    tags: &id067
    - CRM
    - Sales
    - Sales Engagement
    - Sequences
    url: /providers/outreach/
  layer: domain
  name: Outreach
  provider: outreach
  says: lists Outreach as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id068
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id069
    - Connect
    - Pipedream
    - Pro-Code-API-Composition
    - Workflows
    url: /providers/pipedream/
  layer: common
  name: Pipedream
  provider: pipedream
  says: lists Pipedream as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 28.7
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id070
      status: none
    slug: pipedrive
    status: profiled
    tags: &id071
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260
    key: customer-success-management
    name: Customer Success Management
    url: /capabilities/customer-success-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: strong
    in_catalog: true
    kin_score: 56.3
    mcp: &id072
      source: https://help.planhat.com/en/articles/15644693-how-to-connect-chatgpt-to-planhat-using-oauth-and-planhat-s-mcp-server
      status: verified
    slug: planhat
    status: profiled
    tags: &id073
    - Company
    - Customer Platform
    - Customer Success
    - Software-as-a-Service
    url: /providers/planhat/
  layer: domain
  name: Planhat
  provider: planhat
  says: lists Planhat as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id076
      status: none
    slug: reamaze
    status: profiled
    tags: &id077
    - Artificial Intelligence
    - Customer Service
    - Help Desk
    - Live Chat
    url: /providers/reamaze/
  layer: domain
  name: Re:amaze
  provider: reamaze
  says: lists Re:amaze as an integration
  source: https://aircall.io/integrations/
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
    mcp: &id078
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id079
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-954
    key: AE-954
    name: Sales Engagement & Sequencing
    url: /capabilities/sales-engagement-sequencing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.4
    band: strong
    in_catalog: true
    kin_score: 62.7
    mcp: &id080
      status: none
    slug: salesloft
    status: profiled
    tags: &id081
    - CRM
    - Cadences
    - Sales
    - Sales Engagement
    url: /providers/salesloft/
  layer: domain
  name: Salesloft
  provider: salesloft
  says: lists Salesloft as an integration
  source: https://aircall.io/integrations/
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
    agent_band: agent-ready
    agent_readiness: 42.4
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id082
      status: unchecked
    slug: salesmsg
    status: profiled
    tags: &id083
    - AI Agents
    - Business Calling
    - Business Texting
    - CRM Integration
    url: /providers/salesmsg/
  layer: domain
  name: Salesmsg
  provider: salesmsg
  says: lists Salesmsg as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id084
      status: none
    slug: segment
    status: profiled
    tags: &id085
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id086
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id087
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id088
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id089
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 60.3
    band: exemplar
    in_catalog: true
    kin_score: 89.5
    mcp: &id090
      source: https://docs.tray.ai/
      status: documented
    slug: tray-ai
    status: profiled
    tags: &id091
    - AI Agents
    - Automation
    - Integration
    - iPaaS
    url: /providers/tray-ai/
  layer: common
  name: Tray.ai
  provider: tray-ai
  says: lists Tray.ai as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id092
      source: https://mcp.trengo.com/.well-known/oauth-protected-resource/mcp
      status: verified
    slug: trengo
    status: profiled
    tags: &id093
    - Customer Engagement
    - Messaging
    - Omnichannel
    - Shared Inbox
    url: /providers/trengo/
  layer: domain
  name: Trengo
  provider: trengo
  says: lists Trengo as an integration
  source: https://aircall.io/integrations/
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
    agent_band: agent-ready
    agent_readiness: 42.6
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id094
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id095
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: common
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://aircall.io/integrations/
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
    mcp: &id096
      status: none
    slug: whatsapp
    status: profiled
    tags: &id097
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://aircall.io/integrations/
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
    mcp: &id098
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id099
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id100
      status: none
    slug: zendesk
    status: profiled
    tags: &id101
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://aircall.io/integrations/
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
    agent_readiness: 30.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id102
      status: none
    slug: zendesk-sell
    status: profiled
    tags: &id103
    - CRM
    - Leads
    - Sales
    - Sales Automation
    url: /providers/zendesk-sell/
  layer: domain
  name: Zendesk Sell
  provider: zendesk-sell
  says: lists Zendesk Sell as an integration
  source: https://aircall.io/integrations/
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
    mcp: &id104
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id105
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id106
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-desk
    status: profiled
    tags: &id107
    - Customer Service
    - Help Desk
    - Knowledge Base
    - Ticketing
    url: /providers/zoho-desk/
  layer: domain
  name: Zoho Desk
  provider: zoho-desk
  says: lists Zoho Desk as an integration
  source: https://aircall.io/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sales-engagement/aircall/
providers:
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id002
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id003
  url: /providers/activecampaign/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id004
  name: Attio
  slug: attio
  status: profiled
  tags: *id005
  url: /providers/attio/
- agent_band: agent-ready
  agent_readiness: 43.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id006
  name: Avoma
  slug: avoma
  status: profiled
  tags: *id007
  url: /providers/avoma/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id008
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id009
  url: /providers/bigcommerce/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id010
  name: Bullhorn
  slug: bullhorn
  status: profiled
  tags: *id011
  url: /providers/bullhorn/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id012
  name: Chili Piper
  slug: chili-piper
  status: profiled
  tags: *id013
  url: /providers/chili-piper/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id014
  name: Chorus.ai
  slug: chorus-ai
  status: profiled
  tags: *id015
  url: /providers/chorus-ai/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id016
  name: Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id017
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id018
  name: Fireflies
  slug: fireflies
  status: profiled
  tags: *id019
  url: /providers/fireflies/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id020
  name: Fivetran
  slug: fivetran
  status: profiled
  tags: *id021
  url: /providers/fivetran/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id022
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id023
  url: /providers/freshdesk/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id024
  name: Freshsales
  slug: freshsales
  status: profiled
  tags: *id025
  url: /providers/freshsales/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id026
  name: Front
  slug: front
  status: profiled
  tags: *id027
  url: /providers/front/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id028
  name: Geckoboard
  slug: geckoboard
  status: profiled
  tags: *id029
  url: /providers/geckoboard/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id030
  name: Gong
  slug: gong
  status: profiled
  tags: *id031
  url: /providers/gong/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id032
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id033
  url: /providers/gorgias/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id034
  name: Help Scout
  slug: helpscout
  status: profiled
  tags: *id035
  url: /providers/helpscout/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id036
  name: HighLevel
  slug: highlevel
  status: profiled
  tags: *id037
  url: /providers/highlevel/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id038
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id039
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id040
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id041
  url: /providers/intercom/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id042
  name: Jiminny
  slug: jiminny
  status: profiled
  tags: *id043
  url: /providers/jiminny/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id044
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id045
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id046
  name: Kommo
  slug: kommo
  status: profiled
  tags: *id047
  url: /providers/kommo/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id048
  name: Kustomer
  slug: kustomer
  status: profiled
  tags: *id049
  url: /providers/kustomer/
- agent_band: agent-ready
  agent_readiness: 63.9
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id050
  name: lemlist
  slug: lemlist
  status: profiled
  tags: *id051
  url: /providers/lemlist/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id052
  name: Make
  slug: make
  status: profiled
  tags: *id053
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id054
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id055
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id056
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id057
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: strong
  in_catalog: true
  kin_score: 56.6
  mcp: *id058
  name: Mindtickle
  slug: mindtickle
  status: profiled
  tags: *id059
  url: /providers/mindtickle/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id060
  name: Missive
  slug: missive
  status: profiled
  tags: *id061
  url: /providers/missive/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id062
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id063
  url: /providers/monday-com/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 27.6
  mcp: *id064
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id065
  url: /providers/odoo/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 78.7
  mcp: *id066
  name: Outreach
  slug: outreach
  status: profiled
  tags: *id067
  url: /providers/outreach/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id068
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id069
  url: /providers/pipedream/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id070
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id071
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: strong
  in_catalog: true
  kin_score: 56.3
  mcp: *id072
  name: Planhat
  slug: planhat
  status: profiled
  tags: *id073
  url: /providers/planhat/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id074
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id075
  url: /providers/pusher/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id076
  name: Re:amaze
  slug: reamaze
  status: profiled
  tags: *id077
  url: /providers/reamaze/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id078
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id079
  url: /providers/salesforce/
- agent_band: agent-native
  agent_readiness: 44.4
  band: strong
  in_catalog: true
  kin_score: 62.7
  mcp: *id080
  name: Salesloft
  slug: salesloft
  status: profiled
  tags: *id081
  url: /providers/salesloft/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id082
  name: Salesmsg
  slug: salesmsg
  status: profiled
  tags: *id083
  url: /providers/salesmsg/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id084
  name: Segment
  slug: segment
  status: profiled
  tags: *id085
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id086
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id087
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id088
  name: Slack
  slug: slack
  status: profiled
  tags: *id089
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 60.3
  band: exemplar
  in_catalog: true
  kin_score: 89.5
  mcp: *id090
  name: Tray.ai
  slug: tray-ai
  status: profiled
  tags: *id091
  url: /providers/tray-ai/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id092
  name: Trengo
  slug: trengo
  status: profiled
  tags: *id093
  url: /providers/trengo/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id094
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id095
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id096
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id097
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id098
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id099
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id100
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id101
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id102
  name: Zendesk Sell
  slug: zendesk-sell
  status: profiled
  tags: *id103
  url: /providers/zendesk-sell/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id104
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id105
  url: /providers/zoho-crm/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id106
  name: Zoho Desk
  slug: zoho-desk
  status: profiled
  tags: *id107
  url: /providers/zoho-desk/
siblings:
- name: Apollo.io
  rows: 21
  url: /applications/sales-engagement/apollo-io/
- name: Close
  rows: 34
  url: /applications/sales-engagement/close/
- name: lemlist
  rows: 43
  url: /applications/sales-engagement/lemlist/
- name: Salesloft
  rows: 4
  url: /applications/sales-engagement/salesloft/
- name: VICIdial
  rows: 1
  url: /applications/sales-engagement/vicidial/
sitemap: true
title: 'Aircall: Sales Engagement & Dialers reference app'
---
