---
app: JustCall
app_slug: justcall
app_url: https://justcall.io/
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
  - Close
  - Copper
  - Freshsales
  - HighLevel
  - HubSpot
  - Keap
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
  - Zendesk Support
  - Zoho Desk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
  - Fireflies.ai
  - Gong
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: Turbo EA
  id: BC-410
  key: sales-management
  layer: domain
  name: Sales Management
  providers:
  - Apollo.io
  - Outreach
  - Salesloft
  url: /capabilities/sales-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Fivetran
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Google Contacts
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: common
  name: Scheduling & Appointment Management
  providers:
  - Calendly
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Pipedream
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: voip-call-center
  name: VoIP, Phone & Contact Center
  url: /applications/voip-call-center/
counts:
  declared: 36
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://justcall.io/integrations/
integrations:
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
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 82.0
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
  source: https://justcall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410
    key: sales-management
    name: Sales Management
    url: /capabilities/sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.2
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id003
      source: https://docs.apollo.io/docs/apollo-mcp
      status: verified
    slug: apollo-io
    status: profiled
    tags: &id004
    - B2B Data
    - Engagement
    - Prospecting
    - Sales Intelligence
    url: /providers/apollo-io/
  layer: domain
  name: Apollo.io
  provider: apollo-io
  says: lists Apollo.io as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 45.3
    band: emerging
    in_catalog: true
    kin_score: 21.9
    mcp: &id005
      source: https://docs.attio.com/mcp/overview
      status: verified
    slug: attio
    status: profiled
    tags: &id006
    - CRM
    - Companies
    - Contacts
    - Sales
    url: /providers/attio/
  layer: domain
  name: Attio
  provider: attio
  says: lists Attio as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 48.1
    band: developing
    in_catalog: true
    kin_score: 45.0
    mcp: &id007
      source: https://developer.calendly.com/calendly-mcp-server
      status: documented
    slug: calendly
    status: profiled
    tags: &id008
    - Appointments
    - Automation
    - Booking
    - Calendar
    url: /providers/calendly/
  layer: common
  name: Calendly
  provider: calendly
  says: lists Calendly as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id009
      source: https://developer.close.com/mcp
      status: verified
    slug: close
    status: profiled
    tags: &id010
    - CRM
    - Calling
    - Inside Sales
    - Sales Engagement
    url: /providers/close/
  layer: domain
  name: Close
  provider: close
  says: lists Close as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 24.5
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id011
      status: none
    slug: copper
    status: profiled
    tags: &id012
    - Activities
    - Companies
    - Contact Relationship Management
    - Contacts
    url: /providers/copper/
  layer: domain
  name: Copper
  provider: copper
  says: lists Copper as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 72.7
    mcp: &id013
      source: https://docs.fireflies.ai/mcp-tools/overview
      status: verified
    slug: fireflies
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Meeting Assistant
    - Summary
    - Transcription
    url: /providers/fireflies/
  layer: domain
  name: Fireflies.ai
  provider: fireflies
  says: lists Fireflies.ai as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 36.4
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id015
      source: https://github.com/fivetran/fivetran-mcp
      status: verified
    slug: fivetran
    status: profiled
    tags: &id016
    - Connectors
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/fivetran/
  layer: common
  name: Fivetran
  provider: fivetran
  says: lists Fivetran as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id017
      status: none
    slug: freshdesk
    status: profiled
    tags: &id018
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 36.1
    mcp: &id019
      status: none
    slug: freshsales
    status: profiled
    tags: &id020
    - CRM
    - Contacts
    - Deals
    - Sales
    url: /providers/freshsales/
  layer: domain
  name: Freshsales
  provider: freshsales
  says: lists Freshsales as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 27.0
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id021
      source: https://dev.frontapp.com/docs/mcp
      status: documented
    slug: front
    status: profiled
    tags: &id022
    - Customer Operations
    - Customer Service
    - Email
    - Inbox
    url: /providers/front/
  layer: domain
  name: Front
  provider: front
  says: lists Front as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 55.5
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id023
      status: none
    slug: gong
    status: profiled
    tags: &id024
    - Analytics
    - Conversations
    - Revenue Intelligence
    - Sales
    url: /providers/gong/
  layer: domain
  name: Gong
  provider: gong
  says: lists Gong as an integration
  source: https://justcall.io/integrations/
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
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id025
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id026
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://justcall.io/integrations/
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id027
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id028
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: common
  name: Google Contacts
  provider: google-people
  says: lists Google Contacts as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id029
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id030
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: domain
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 25.4
    band: developing
    in_catalog: true
    kin_score: 51.7
    mcp: &id031
      status: none
    slug: helpscout
    status: profiled
    tags: &id032
    - Customer Service
    - Email
    - Help Desk
    - Live Chat
    url: /providers/helpscout/
  layer: domain
  name: Help Scout
  provider: helpscout
  says: lists Help Scout as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id033
      source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
      status: verified
    slug: highlevel
    status: profiled
    tags: &id034
    - CRM
    - Company
    - Marketing
    - Software-as-a-Service
    url: /providers/highlevel/
  layer: domain
  name: HighLevel
  provider: highlevel
  says: lists HighLevel as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id035
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id036
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id037
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 45.4
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id039
      status: none
    slug: keap
    status: profiled
    tags: &id040
    - CRM
    - Marketing Automation
    - Sales
    - Small Business
    url: /providers/keap/
  layer: domain
  name: Keap
  provider: keap
  says: lists Keap as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id041
      status: none
    slug: kustomer
    status: profiled
    tags: &id042
    - CRM
    - Customer Service
    - Help Desk
    - Messaging
    url: /providers/kustomer/
  layer: domain
  name: Kustomer
  provider: kustomer
  says: lists Kustomer as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 43.9
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id043
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id044
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id045
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id046
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://justcall.io/integrations/
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
    kin_score: 33.6
    mcp: &id047
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id048
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: domain
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id049
      status: none
    slug: odoo
    status: profiled
    tags: &id050
    - Business Applications
    - CRM
    - ERP
    - Open Source
    url: /providers/odoo/
  layer: domain
  name: Odoo
  provider: odoo
  says: lists Odoo as an integration
  source: https://justcall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410
    key: sales-management
    name: Sales Management
    url: /capabilities/sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.1
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id051
      status: none
    slug: outreach
    status: profiled
    tags: &id052
    - CRM
    - Sales
    - Sales Engagement
    - Sequences
    url: /providers/outreach/
  layer: domain
  name: Outreach
  provider: outreach
  says: lists Outreach as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 31.3
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id053
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id054
    - Connect
    - Pipedream
    - Pro-Code-API-Composition
    - Workflows
    url: /providers/pipedream/
  layer: common
  name: Pipedream
  provider: pipedream
  says: lists Pipedream as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 29.3
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id055
      status: none
    slug: pipedrive
    status: profiled
    tags: &id056
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
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
  source: https://justcall.io/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410
    key: sales-management
    name: Sales Management
    url: /capabilities/sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.4
    band: strong
    in_catalog: true
    kin_score: 62.5
    mcp: &id059
      status: none
    slug: salesloft
    status: profiled
    tags: &id060
    - CRM
    - Cadences
    - Sales
    - Sales Engagement
    url: /providers/salesloft/
  layer: domain
  name: Salesloft
  provider: salesloft
  says: lists Salesloft as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id061
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id062
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id063
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id064
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 30.1
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id065
      status: none
    slug: zendesk-sell
    status: profiled
    tags: &id066
    - CRM
    - Leads
    - Sales
    - Sales Automation
    url: /providers/zendesk-sell/
  layer: domain
  name: Zendesk Sell
  provider: zendesk-sell
  says: lists Zendesk Sell as an integration
  source: https://justcall.io/integrations/
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
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id067
      status: none
    slug: zendesk
    status: profiled
    tags: &id068
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk Support
  provider: zendesk
  says: lists Zendesk Support as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 44.2
    band: exemplar
    in_catalog: true
    kin_score: 86.0
    mcp: &id069
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id070
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://justcall.io/integrations/
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
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id071
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-desk
    status: profiled
    tags: &id072
    - Customer Service
    - Help Desk
    - Knowledge Base
    - Ticketing
    url: /providers/zoho-desk/
  layer: domain
  name: Zoho Desk
  provider: zoho-desk
  says: lists Zoho Desk as an integration
  source: https://justcall.io/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/voip-call-center/justcall/
providers:
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id001
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id002
  url: /providers/activecampaign/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id003
  name: Apollo.io
  slug: apollo-io
  status: profiled
  tags: *id004
  url: /providers/apollo-io/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: emerging
  in_catalog: true
  kin_score: 21.9
  mcp: *id005
  name: Attio
  slug: attio
  status: profiled
  tags: *id006
  url: /providers/attio/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: developing
  in_catalog: true
  kin_score: 45.0
  mcp: *id007
  name: Calendly
  slug: calendly
  status: profiled
  tags: *id008
  url: /providers/calendly/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id009
  name: Close
  slug: close
  status: profiled
  tags: *id010
  url: /providers/close/
- agent_band: agent-aware
  agent_readiness: 24.5
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id011
  name: Copper
  slug: copper
  status: profiled
  tags: *id012
  url: /providers/copper/
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 72.7
  mcp: *id013
  name: Fireflies.ai
  slug: fireflies
  status: profiled
  tags: *id014
  url: /providers/fireflies/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id015
  name: Fivetran
  slug: fivetran
  status: profiled
  tags: *id016
  url: /providers/fivetran/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id017
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id018
  url: /providers/freshdesk/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 36.1
  mcp: *id019
  name: Freshsales
  slug: freshsales
  status: profiled
  tags: *id020
  url: /providers/freshsales/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id021
  name: Front
  slug: front
  status: profiled
  tags: *id022
  url: /providers/front/
- agent_band: agent-ready
  agent_readiness: 55.5
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id023
  name: Gong
  slug: gong
  status: profiled
  tags: *id024
  url: /providers/gong/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id025
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id026
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id027
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id028
  url: /providers/google-people/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id029
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id030
  url: /providers/gorgias/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id031
  name: Help Scout
  slug: helpscout
  status: profiled
  tags: *id032
  url: /providers/helpscout/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id033
  name: HighLevel
  slug: highlevel
  status: profiled
  tags: *id034
  url: /providers/highlevel/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id035
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id036
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id037
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id038
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 45.4
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id039
  name: Keap
  slug: keap
  status: profiled
  tags: *id040
  url: /providers/keap/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id041
  name: Kustomer
  slug: kustomer
  status: profiled
  tags: *id042
  url: /providers/kustomer/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id043
  name: Make
  slug: make
  status: profiled
  tags: *id044
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id045
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id046
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id047
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id048
  url: /providers/monday-com/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id049
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id050
  url: /providers/odoo/
- agent_band: agent-ready
  agent_readiness: 53.1
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id051
  name: Outreach
  slug: outreach
  status: profiled
  tags: *id052
  url: /providers/outreach/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id053
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id054
  url: /providers/pipedream/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id055
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id056
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id057
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id058
  url: /providers/salesforce/
- agent_band: agent-native
  agent_readiness: 45.4
  band: strong
  in_catalog: true
  kin_score: 62.5
  mcp: *id059
  name: Salesloft
  slug: salesloft
  status: profiled
  tags: *id060
  url: /providers/salesloft/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id061
  name: Slack
  slug: slack
  status: profiled
  tags: *id062
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id063
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id064
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id065
  name: Zendesk Sell
  slug: zendesk-sell
  status: profiled
  tags: *id066
  url: /providers/zendesk-sell/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id067
  name: Zendesk Support
  slug: zendesk
  status: profiled
  tags: *id068
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 86.0
  mcp: *id069
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id070
  url: /providers/zoho-crm/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id071
  name: Zoho Desk
  slug: zoho-desk
  status: profiled
  tags: *id072
  url: /providers/zoho-desk/
siblings:
- name: Aircall
  rows: 42
  url: /applications/voip-call-center/aircall/
- name: Dialpad
  rows: 5
  url: /applications/voip-call-center/dialpad/
- name: Fonoster
  rows: 14
  url: /applications/voip-call-center/fonoster/
- name: jambonz
  rows: 36
  url: /applications/voip-call-center/jambonz/
- name: Talkdesk
  rows: 25
  url: /applications/voip-call-center/talkdesk/
sitemap: true
title: 'JustCall: VoIP, Phone & Contact Center reference app'
---
