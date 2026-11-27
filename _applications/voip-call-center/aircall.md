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
  - ActiveCampaign
  - Attio
  - Copper
  - Freshsales
  - HighLevel
  - HubSpot
  - Microsoft Dynamics
  - monday.com
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
  - Nicereply
  - Zendesk CTI
  - Zoho Desk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
  - Avoma
  - Fireflies
  - Gong
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: Turbo EA
  id: BC-430.30.30
  key: BC-430.30.30
  layer: domain
  name: Quality Monitoring and Coaching
  providers:
  - Klaus
  url: /capabilities/contact-centre-operations-management/
  via_parent: Contact Centre Operations Management
- attribution: API Evangelist extension
  id: AE-954
  key: AE-954
  layer: domain
  name: Sales Engagement & Sequencing
  providers:
  - Outreach
  - Salesloft
  url: /capabilities/sales-engagement-sequencing/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Fivetran
  - Geckoboard
  - Segment
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  url: /capabilities/product-usage-analytics/
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
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Sinch Engage
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp Messaging Channel
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Pipedream
  - Tray.io
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: voip-call-center
  name: VoIP, Phone & Contact Center
  url: /applications/voip-call-center/
counts:
  declared: 39
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
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id010
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id011
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
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
    mcp: &id058
      status: none
    slug: pusher
    status: profiled
    tags: &id059
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
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
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
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.7
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id008
      status: none
    slug: copper
    status: profiled
    tags: &id009
    - Activities
    - Companies
    - Contact Relationship Management
    - Contacts
    url: /providers/copper/
  layer: domain
  name: Copper
  provider: copper
  says: lists Copper as an integration
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
    mcp: &id012
      source: https://docs.fireflies.ai/mcp-tools/overview
      status: verified
    slug: fireflies
    status: profiled
    tags: &id013
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
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id014
      source: https://github.com/fivetran/fivetran-mcp
      status: verified
    slug: fivetran
    status: profiled
    tags: &id015
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
    mcp: &id016
      status: none
    slug: freshdesk
    status: profiled
    tags: &id017
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
    mcp: &id018
      status: none
    slug: freshsales
    status: profiled
    tags: &id019
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
    mcp: &id020
      source: https://dev.frontapp.com/docs/mcp
      status: documented
    slug: front
    status: profiled
    tags: &id021
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
    mcp: &id022
      source: https://www.geckoboard.com/product/metrics-mcp/
      status: verified
    slug: geckoboard
    status: profiled
    tags: &id023
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
    mcp: &id024
      status: none
    slug: gong
    status: profiled
    tags: &id025
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
    mcp: &id026
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id027
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
    mcp: &id028
      status: none
    slug: helpscout
    status: profiled
    tags: &id029
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
    mcp: &id030
      source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
      status: verified
    slug: highlevel
    status: profiled
    tags: &id031
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
    mcp: &id032
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id033
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
    mcp: &id034
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id035
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
    attribution: Turbo EA
    id: BC-430.30.30
    key: BC-430.30.30
    name: Quality Monitoring and Coaching
    url: /capabilities/contact-centre-operations-management/
    via_parent: Contact Centre Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id036
      status: none
    slug: klaus
    status: profiled
    tags: &id037
    - Company
    - Customer Experience
    - Customer Service
    - Quality Assurance
    url: /providers/klaus/
  layer: domain
  name: Klaus
  provider: klaus
  says: lists Klaus as an integration
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
    mcp: &id038
      status: none
    slug: kustomer
    status: profiled
    tags: &id039
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
    mcp: &id040
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id041
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
    mcp: &id042
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id043
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
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id044
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id045
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
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id046
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id047
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: domain
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.2
    mcp: &id048
      status: none
    slug: nicereply
    status: profiled
    tags: &id049
    - CES
    - CSAT
    - NPS
    - Surveys
    url: /providers/nicereply/
  layer: domain
  name: Nicereply
  provider: nicereply
  says: lists Nicereply as an integration
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
    mcp: &id050
      status: none
    slug: odoo
    status: profiled
    tags: &id051
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
    mcp: &id052
      status: none
    slug: outreach
    status: profiled
    tags: &id053
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
    mcp: &id054
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id055
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
    mcp: &id056
      status: none
    slug: pipedrive
    status: profiled
    tags: &id057
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
    mcp: &id060
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id061
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
    mcp: &id062
      status: none
    slug: salesloft
    status: profiled
    tags: &id063
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
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id064
      status: none
    slug: segment
    status: profiled
    tags: &id065
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
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.3
    band: exemplar
    in_catalog: true
    kin_score: 71.6
    mcp: &id066
      source: https://github.com/sinch/sinch-mcp-server
      status: verified
    slug: sinch
    status: profiled
    tags: &id067
    - Communications
    - Messaging
    - SMS
    - Voice
    url: /providers/sinch/
  layer: common
  name: Sinch Engage
  provider: sinch
  says: lists Sinch Engage as an integration
  source: https://aircall.io/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id068
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id069
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
    mcp: &id070
      source: https://docs.tray.ai/
      status: documented
    slug: tray-ai
    status: profiled
    tags: &id071
    - AI Agents
    - Automation
    - Integration
    - iPaaS
    url: /providers/tray-ai/
  layer: common
  name: Tray.io
  provider: tray-ai
  says: lists Tray.io as an integration
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
    mcp: &id072
      status: none
    slug: whatsapp
    status: profiled
    tags: &id073
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp Messaging Channel
  provider: whatsapp
  says: lists WhatsApp Messaging Channel as an integration
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
    mcp: &id074
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id075
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
    mcp: &id076
      status: none
    slug: zendesk
    status: profiled
    tags: &id077
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk CTI
  provider: zendesk
  says: lists Zendesk CTI as an integration
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
    mcp: &id078
      status: none
    slug: zendesk-sell
    status: profiled
    tags: &id079
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
    mcp: &id080
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id081
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
    mcp: &id082
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-desk
    status: profiled
    tags: &id083
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
permalink: /applications/voip-call-center/aircall/
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
- agent_band: agent-aware
  agent_readiness: 26.7
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id008
  name: Copper
  slug: copper
  status: profiled
  tags: *id009
  url: /providers/copper/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id010
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id011
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id012
  name: Fireflies
  slug: fireflies
  status: profiled
  tags: *id013
  url: /providers/fireflies/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id014
  name: Fivetran
  slug: fivetran
  status: profiled
  tags: *id015
  url: /providers/fivetran/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id016
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id017
  url: /providers/freshdesk/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id018
  name: Freshsales
  slug: freshsales
  status: profiled
  tags: *id019
  url: /providers/freshsales/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id020
  name: Front
  slug: front
  status: profiled
  tags: *id021
  url: /providers/front/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id022
  name: Geckoboard
  slug: geckoboard
  status: profiled
  tags: *id023
  url: /providers/geckoboard/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id024
  name: Gong
  slug: gong
  status: profiled
  tags: *id025
  url: /providers/gong/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id026
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id027
  url: /providers/gorgias/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id028
  name: Help Scout
  slug: helpscout
  status: profiled
  tags: *id029
  url: /providers/helpscout/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id030
  name: HighLevel
  slug: highlevel
  status: profiled
  tags: *id031
  url: /providers/highlevel/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id032
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id033
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id034
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id035
  url: /providers/intercom/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id036
  name: Klaus
  slug: klaus
  status: profiled
  tags: *id037
  url: /providers/klaus/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id038
  name: Kustomer
  slug: kustomer
  status: profiled
  tags: *id039
  url: /providers/kustomer/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id040
  name: Make
  slug: make
  status: profiled
  tags: *id041
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id042
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id043
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id044
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id045
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id046
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id047
  url: /providers/monday-com/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id048
  name: Nicereply
  slug: nicereply
  status: profiled
  tags: *id049
  url: /providers/nicereply/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 27.6
  mcp: *id050
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id051
  url: /providers/odoo/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 78.7
  mcp: *id052
  name: Outreach
  slug: outreach
  status: profiled
  tags: *id053
  url: /providers/outreach/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id054
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id055
  url: /providers/pipedream/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id056
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id057
  url: /providers/pipedrive/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id058
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id059
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id060
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id061
  url: /providers/salesforce/
- agent_band: agent-native
  agent_readiness: 44.4
  band: strong
  in_catalog: true
  kin_score: 62.7
  mcp: *id062
  name: Salesloft
  slug: salesloft
  status: profiled
  tags: *id063
  url: /providers/salesloft/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id064
  name: Segment
  slug: segment
  status: profiled
  tags: *id065
  url: /providers/segment/
- agent_band: agent-native
  agent_readiness: 60.3
  band: exemplar
  in_catalog: true
  kin_score: 71.6
  mcp: *id066
  name: Sinch Engage
  slug: sinch
  status: profiled
  tags: *id067
  url: /providers/sinch/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id068
  name: Slack
  slug: slack
  status: profiled
  tags: *id069
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 60.3
  band: exemplar
  in_catalog: true
  kin_score: 89.5
  mcp: *id070
  name: Tray.io
  slug: tray-ai
  status: profiled
  tags: *id071
  url: /providers/tray-ai/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id072
  name: WhatsApp Messaging Channel
  slug: whatsapp
  status: profiled
  tags: *id073
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id074
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id075
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id076
  name: Zendesk CTI
  slug: zendesk
  status: profiled
  tags: *id077
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id078
  name: Zendesk Sell
  slug: zendesk-sell
  status: profiled
  tags: *id079
  url: /providers/zendesk-sell/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id080
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id081
  url: /providers/zoho-crm/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id082
  name: Zoho Desk
  slug: zoho-desk
  status: profiled
  tags: *id083
  url: /providers/zoho-desk/
siblings:
- name: Dialpad
  rows: 5
  url: /applications/voip-call-center/dialpad/
- name: Fonoster
  rows: 14
  url: /applications/voip-call-center/fonoster/
- name: jambonz
  rows: 36
  url: /applications/voip-call-center/jambonz/
- name: JustCall
  rows: 36
  url: /applications/voip-call-center/justcall/
- name: Talkdesk
  rows: 25
  url: /applications/voip-call-center/talkdesk/
sitemap: true
title: 'Aircall: VoIP, Phone & Contact Center reference app'
---
